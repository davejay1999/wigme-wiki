* **Cronjob:** cronjob_for_oc_report.py<br>
**Frequency:** Every 3 minutes<br>
**Purpose:** This cronjob executes the report requests by omnycomm users one by one and generates excel files and mails the respective users. Generating reports in this manner instead of on demand report prevents a thread bomb on OC

* **Cronjob:** daily-update-of-b2b-sitemap<br>
**Frequency:** At 1:15 AM daily<br>
**Purpose:** Generate sitemaps for all ecommerce websites and push the files to the respective directories. Creates following sitemap xml files for all ecommerce websites - [sitemap.xml, super-categories.xml, categories.xml, sub-categories.xml, products.xml, brands.xml, information.xml]


* **Cronjob:** daily_and_monthly_sales_report.py<br>
**Frequency:** At 21:15 daily.<br>
**Purpose:** Generate two sales reports and send them via email - [Today's sale report, From 1st of current month to today]


* **Cronjob:** daily_update_dealshub_product_SEO_for_kwt_and_bah.py<br>
**Frequency:** At 2:30 AM daily<br>
**Purpose:** To auto generate SEO details for kwt's and bah's products which are created in last 24 hours.
SEO details updated are:- [SEO Title, SEO Keywords, SEO Description, Page Description]

* **Cronjob:** facebook-product-b2b.py (for shopnestob2b); facebook-product-update.py (for shopnesto); facebook-product-update-for-multiple-website-group.py (for all other websites)<br>
**Frequency:** At 01:00; At 00:00; At 23:10<br>
**Purpose:** Create xml file that would be read by facebook for facebook ads for marketing.


* **Cronjob:** mark_oc_report_as_processed.py<br>
**Frequency:** At 2:15 AM<br>
**Purpose:** Delete certain reports that are older than 3 days and have is_processed=False. Such reports are dead reports.


* **Cronjob:** notify-new-products.py<br>
**Frequency:** Every 12th hour<br>
**Purpose:** Send notification of new products to a certain set of OC users.


* **Cronjob:** sap-grn.py<br>
**Frequency:** At every 10th minute<br>
**Purpose:** Calls GRNProcessingCronAPI which is used for final billing for SAP punching.


* **Cronjob:** send_order_mail_request.py<br>
**Frequency:** Every hour<br>
**Purpose:** Send order notification emails to customers based on their ecommerce orders


* **Cronjob:** weekly-report.py<br>
**Frequency:** At 19:00 every week<br>
**Purpose:** To notify ecommerce managers the list of all unpublished ecommerce products (WIGme KWT and WIGme UAE) every week 