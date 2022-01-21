### **Description**:
- SAP is a software western is using for inventory management and billing. We have used theirs API's for some of the functionalities and provide them with details on certain actions like selecting a shipping method, changing the stock.
- It is specifically configured for wigme location groups only.
- They have provided soap API. Where we have to define the xml body and pass certain parameters in them( checkout xml_generator_SAP.py file where all the request bodies have been defined )

### **Installation**: 
Have to set proper SAP API URLs and their constants in order to make their API's functional.

### **Important Note:**
- Need to understand the logic of holdings( can only be used when atp is not there) and ATP( Available To Promise used for billing )
- On billing, if atp < quantity option of selecting from holding is given. 
- If there is more atp at any point then they are transferred to holding and a max-holding qty is maintained.

### **Features/Example/tutorial:**
- Holding stock management and list of holdings by different channels in the eCommerce products page.
- Online order api call on selecting the shipping method. An intercompany sales order is created and then a cron job calls a final order api and informs the SAP about the order.
- Fetching prices and stock details


### **API Documentation**: 
views_SAP.py

1. FetchPriceAndStock - gives you price and stock info including holding, atp, prices from SAP by giving seller_sku and company_code
UpdateProductHoldingDetails - This allows us to send the stock from atp to holding and vice-versa. The stocks are in batches and we have to manage the total number of stocks into the batches
Example: batches have 3,4,5 qty each in holding(total=12) need to change holding to 10 so the batch we can send is 3,4,3.
Code for the above logic ( when reducing the holdings and sending them to atp) :

            change_in_holding = total_holding - final_holding # amount of change
            if change_in_holding > 0:

                for item in prices_and_stock_information["stock_list"]:
                    transfer_here = min(change_in_holding,item["holding_qty"]) # to not take more then available
                    temp_dict = {}
                    temp_dict["seller_sku"] = seller_sku
                    temp_dict["qty"] = item["holding_qty"] - transfer_here # final value of holding for this batch.
                    temp_dict["uom"] = item["uom"]
                    temp_dict["batch"] = item["batch"]
                    if temp_dict["qty"] > 0:
                        transfer_information.append(temp_dict)

                    change_in_holding = change_in_holding - transfer_here

                    if change_in_holding == 0:
                        break 
 
2. FetchProductHoldingDetails - gives you the holding details from the SAP api with channel sales persons holding details
3. HoldingTransfer - transferring from ATP to holding when holding goes less than holding threshold.

### **Issues**:
Cannot set the holding stock to zero. SAP api’s do not support it.

Contact **Rayees** or **Pradeep** from the SAP team if something goes wrong with theirs API's.


Edited By Nisarg
