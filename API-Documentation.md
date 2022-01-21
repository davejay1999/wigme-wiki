## Ecommerce Module APIs

### FetchProductDetailsAPI<br>
**Description**: This API is called on ecommerce website's product description page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/fetch-product-details/](https://api.omnycomm.com/dealshub/fetch-product-details/)<br>
**Type**: POST<br>
```json
Request:
{
    "language": "en",
    "uuid": "99ef20cf-2daa-419d-b685-b4626d6bdec2"
}

Response:
{
    "user_manual": "https://www.product.com/user-manual.pdf",
    "brand": "Geepas",
    "superCategory": "Electronics",
    "category": "Kitchen Appliances",
    "subCategory": "Blender",
    "uuid": "99ef20cf-2daa-419d-b685-b4626d6bdec2",
    "name": "Geepas Blender",
    "stock": 4,
    "moq": 3,
    "allowedQty": 2,
    "price": 190,
    "wasPrice": 220,
    "currency": "AED",
    "warranty": "1 Year",
    "is_new_arrival": true,
    "is_on_sale": true,
    "dimensions": "12 cm x 10 cm x 40 cm",
    "color": "Red",
    "weight": "2 kg",
    "size": "NA",
    "size_unit": "NA",
    "capacity": "NA",
    "capacity_unit": "NA",
    "target_age_range": "NA",
    "material": "NA",
    "sellerSku": "GSB98990",
    "faqs": [
        {
            "question": "Does it cover warranty?",
            "answer": "Yes"
        }
    ],
    "how_to_use": [
        "Use case 1",
        "Use case 2"
    ]
    "is_cod_allowed": true,
    "start_time": "2020-06-30 04:03:00"
    "end_time": "2020-06-30 08:03:00"
    "remaining_time": {
        "days": 7,
        "hours": 12,
        "minutes": 53,
        "seconds": 32
    },
    "promotion_tag": "Diwali Promotion",
    "is_promotional": true,
    "product_is_promotional": false,
    "variant_list": [
        {
            "product_name": "",
            "image_url": "",
            "uuid": ""
        }
    ],
    "isStockAvailable": false,
    "productDispDetails": "Power your way through a wealth of different food preparation tasks with the Geepas 600W 4 in 1 Food Processor. This multi-function food processor is ideal for busy kitchens when space is at a premium. It has various uses and performs all food processing functions &amp; juicing. It is going to be the only food processor needed for any of the tasks including grinding, blending, mixing and juicing. This is an easy to operate appliance. Comes with various attachments: mixer, juicer, blender and a coffee mill to cope with everyday task. There are two different speed modes to allow you to handle soft or hard ingredients properly. Whether you need a quick spin or a thorough grinding, you can choose according to your needs. It provides continuous speed, giving you a quick and easy way to prepare your food with precise and consistent results every time. It comes with a safety interlock to lock-in lid and ensures the processor can only be activated once the lid is secured in place. Enjoy creating a range of meals and recipes with this powerful 600W food processor from Geepas. It has a wide Mouth to process large fruits and vegetables with minimal prep work. It is very easy to use in the kitchen as well as being completely dishwasher safe for simple cleaning.",
    "specifications": {
        "capacity": "1000 W"
    },
    "features": [
        "feature 1",
        "feature 2",
        "feature 3"
    ],
    "productImagesUrl": [
        {
            "high-res": "url",
            "original": "url",
            "thumbnail": "url"
        }
    ],
    "heroImageUrl": "https://cdn.omnycomm.com/midsize/1570428234GSB9890.jpg",
    "page_description": "",
    "seo_title": "",
    "seo_keywords": "",
    "seo_description": "",
    "similar_category_products": [],
    "similar_brand_products": [],
    "status": 200
}
```




### FetchSimilarProductsAPI<br>
**Description**: This API is called on ecommerce website's product description page to show similar brand and category products.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/fetch-similar-products/](https://api.omnycomm.com/dealshub/fetch-similar-products/)<br>
**Type**: POST<br>
```json
Request:
{
    "language": "en",
    "uuid": "99ef20cf-2daa-419d-b685-b4626d6bdec2"
}

Response:
{
    "similar_category_products": [
        {
            "name": "Geepas Mixer",
            "brand": "Geepas"
            "seller_sku": "GSB999",
            "link": "geepas-mixer-1000-watt",
            "now_price": 190,
            "was_price": 220,
            "promotional_price": 180,
            "stock": 8,
            "isStockAvailable": true,
            "currency": "AED",
            "uuid": "72ef20cf-2daa-419d-b685-b4626d6bdec2",
            "id": "72ef20cf-2daa-419d-b685-b4626d6bdec2",
            "heroImageUrl": "https://cdn.omnycomm.com/midsize/1570428234GSB9890.jpg",
            "is_new_arrival": true,
            "is_on_sale": true,
            "start_time": "2020-06-30 04:03:00"
            "end_time": "2020-06-30 08:03:00"
            "remaining_time": {
                "days": 7,
                "hours": 12,
                "minutes": 53,
                "seconds": 32
            },
            "promotion_tag": "Diwali Promotion",
            "is_promotional": true,
            "product_is_promotional": false
        }
    ],
    "similar_brand_products": [
        {
            "name": "Geepas Mixer",
            "brand": "Geepas"
            "seller_sku": "GSB999",
            "link": "geepas-mixer-1000-watt",
            "now_price": 190,
            "was_price": 220,
            "promotional_price": 180,
            "stock": 8,
            "isStockAvailable": true,
            "currency": "AED",
            "uuid": "72ef20cf-2daa-419d-b685-b4626d6bdec2",
            "id": "72ef20cf-2daa-419d-b685-b4626d6bdec2",
            "heroImageUrl": "https://cdn.omnycomm.com/midsize/1570428234GSB9890.jpg",
            "is_new_arrival": true,
            "is_on_sale": true,
            "start_time": "2020-06-30 04:03:00"
            "end_time": "2020-06-30 08:03:00"
            "remaining_time": {
                "days": 7,
                "hours": 12,
                "minutes": 53,
                "seconds": 32
            },
            "promotion_tag": "Diwali Promotion",
            "is_promotional": true,
            "product_is_promotional": false
        }
    ],
    "status": 200
}
```






### FetchOnSaleProductsAPI<br>
**Description**: This API is called on ecommerce website's [Sale Product Page](https://www.wigme.com/sale-products) to show on sale products<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/fetch-on-sale-products/](https://api.omnycomm.com/dealshub/fetch-on-sale-products/)<br>
**Type**: POST<br>
```json
Request:
{
    "language": "en",
    "locationGroupUuid": "99ef20cf-2daa-419d-b685-b4626d6bdec2",
    "page": 1
}

Response:
{
    "products": [
        {
            "name": "Geepas Mixer",
            "brand": "Geepas"
            "seller_sku": "GSB999",
            "link": "geepas-mixer-1000-watt",
            "now_price": 190,
            "was_price": 220,
            "promotional_price": 180,
            "stock": 8,
            "isStockAvailable": true,
            "currency": "AED",
            "uuid": "72ef20cf-2daa-419d-b685-b4626d6bdec2",
            "id": "72ef20cf-2daa-419d-b685-b4626d6bdec2",
            "heroImageUrl": "https://cdn.omnycomm.com/midsize/1570428234GSB9890.jpg",
            "is_new_arrival": true,
            "is_on_sale": true,
            "start_time": "2020-06-30 04:03:00"
            "end_time": "2020-06-30 08:03:00"
            "remaining_time": {
                "days": 7,
                "hours": 12,
                "minutes": 53,
                "seconds": 32
            },
            "promotion_tag": "Diwali Promotion",
            "is_promotional": true,
            "product_is_promotional": false
        }
    ],
    "is_available": true,
    "totalPages": 11,
    "is_user_authenticated": false
    "status": 200
}
```




### FetchNewArrivalProductsAPI<br>
**Description**: This API is called on ecommerce website's [New Arrival Page](https://www.wigme.com/new-arrivals) to show on sale products<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/fetch-new-arrival-products/](https://api.omnycomm.com/dealshub/fetch-new-arrival-products/)<br>
**Type**: POST<br>
```json
Request:
{
    "language": "en",
    "locationGroupUuid": "99ef20cf-2daa-419d-b685-b4626d6bdec2",
    "page": 1
}

Response:
{
    "products": [
        {
            "name": "Geepas Mixer",
            "brand": "Geepas"
            "seller_sku": "GSB999",
            "link": "geepas-mixer-1000-watt",
            "now_price": 190,
            "was_price": 220,
            "promotional_price": 180,
            "stock": 8,
            "isStockAvailable": true,
            "currency": "AED",
            "uuid": "72ef20cf-2daa-419d-b685-b4626d6bdec2",
            "id": "72ef20cf-2daa-419d-b685-b4626d6bdec2",
            "heroImageUrl": "https://cdn.omnycomm.com/midsize/1570428234GSB9890.jpg",
            "is_new_arrival": true,
            "is_on_sale": true,
            "start_time": "2020-06-30 04:03:00"
            "end_time": "2020-06-30 08:03:00"
            "remaining_time": {
                "days": 7,
                "hours": 12,
                "minutes": 53,
                "seconds": 32
            },
            "promotion_tag": "Diwali Promotion",
            "is_promotional": true,
            "product_is_promotional": false
        }
    ],
    "is_available": true,
    "totalPages": 11,
    "is_user_authenticated": false
    "status": 200
}
```


### FetchSectionProductsAPI<br>
**Description**: This API is called on ecommerce website's [Section Listing Page](https://www.wigme.com/carousel-listing/c02a22a8-48a7-4713-b024-89500213f59e/1) to show on all products inside that section. Sections are managed by OC user on OmnyComm<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/fetch-section-products/](https://api.omnycomm.com/dealshub/fetch-section-products/)<br>
**Type**: POST<br>
```json
Request:
{
    "language": "en",
    "brand": "",
    "min_price": "",
    "max_price": "",
    "rating": "",
    "discount_percent": "",
    "brand_filter": [],
    "sort_filter": {
        "price": "high-to-low/low-to-high"
    },
    "sectionUuid": "99ef20cf-2daa-419d-b685-b4626d6bdec2",
    "page": 1
}

Response:
{
    "sectionData": {
        "sectionName": "Diwali Offer",
        "productsArray": [
            {
                "name": "Geepas Mixer",
                "brand": "Geepas"
                "seller_sku": "GSB999",
                "link": "geepas-mixer-1000-watt",
                "now_price": 190,
                "was_price": 220,
                "promotional_price": 180,
                "stock": 8,
                "isStockAvailable": true,
                "currency": "AED",
                "uuid": "72ef20cf-2daa-419d-b685-b4626d6bdec2",
                "id": "72ef20cf-2daa-419d-b685-b4626d6bdec2",
                "heroImageUrl": "https://cdn.omnycomm.com/midsize/1570428234GSB9890.jpg",
                "is_new_arrival": true,
                "is_on_sale": true,
                "start_time": "2020-06-30 04:03:00"
                "end_time": "2020-06-30 08:03:00"
                "remaining_time": {
                    "days": 7,
                    "hours": 12,
                    "minutes": 53,
                    "seconds": 32
                },
                "promotion_tag": "Diwali Promotion",
                "is_promotional": true,
                "product_is_promotional": false
            }
        ]
    }
    "is_available": true,
    "totalPages": 11,
    "is_user_authenticated": false,
    "brand_list": [],
    "status": 200
}
```

### FetchSuperCategoriesAPI<br>
**Description**: This API is called on ecommerce website's navbar for displaying all supercategories<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/fetch-super-categories/](https://api.omnycomm.com/dealshub/fetch-super-categories/)<br>
**Type**: POST<br>
```json
Request:
{
    "language": "en",
    "websiteGroupName": "shopnesto"
}

Response:
{
    "superCategoryList": [
        {
            "name": "Electronics",
            "name_en": "Electronics",
            "uuid": "b19ec895-f07c-414f-ac09-ad8ff4b35c27",
            "imageUrl": "https://cdn.omnycomm.com/thumbnails/elec.png",
            "category_list": [
                {
                    "category_name": "Electronic Accessories",
                    "category_name_en": "Electronic Accessories",
                    "sub_category_list": [
                        {
                            "sub_category_name": "Power Accessories",
                            "sub_category_name_en": "Power Accessories"
                        }
                    ]         
                }
            ]
        }
    ],
    "status": 200
}
```

### FetchHeadingSuperCategoriesAPI<br>
**Description**: This API is called on geepas uganda's navbar for displaying all supercategories<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/fetch-heading-super-categories/](https://api.omnycomm.com/dealshub/fetch-heading-super-categories/)<br>
**Type**: POST<br>
```json
Request:
{
    "language": "en",
    "websiteGroupName": "shopnesto"
}

Response:
{
    "superCategoryList": [
        {
            "name": "Electronics",
            "uuid": "b19ec895-f07c-414f-ac09-ad8ff4b35c27",
            "imageUrl": "https://cdn.omnycomm.com/thumbnails/elec.png",
            "subCategoryList": [
                {
                    "name": "Electronic Accessories",
                    "uuid": "2946685b-dbb0-42ad-ad68-9da9f81c34cc"
                }
            ]
        }
    ],
    "status": 200
}
```

### FetchHeadingCategoriesAPI<br>
**Description**: This API is called on kryptonworld's navbar for displaying all categories<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/fetch-heading-categories/](https://api.omnycomm.com/dealshub/fetch-heading-categories/)<br>
**Type**: POST<br>
```json
Request:
{
    "language": "en",
    "websiteGroupName": "kryptonworld"
}

Response:
{
    "categoryList": [
        {
            "name": "Electronics",
            "uuid": "b19ec895-f07c-414f-ac09-ad8ff4b35c27",
            "imageUrl": "https://cdn.omnycomm.com/thumbnails/elec.png",
            "subCategoryList": [
                {
                    "name": "Electronic Accessories",
                    "uuid": "2946685b-dbb0-42ad-ad68-9da9f81c34cc"
                }
            ]
        }
    ],
    "status": 200
}
```


### FetchCategoriesForNewUserAPI<br>
**Description**: This API is called on wigme B2B's homepage when the user signs up for knowing which categories the user would be interested in.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/fetch-categories-for-new-user/](https://api.omnycomm.com/dealshub/fetch-categories-for-new-user/)<br>
**Type**: POST<br>
```json
Request:
{
    "websiteGroupName": "shopnestob2b"
}

Response:
{
    "categoryList": [
        {
            "name": "Electronics",
            "uuid": "b19ec895-f07c-414f-ac09-ad8ff4b35c27"
        }
    ],
    "isInterestedCategoriesSet": False
    "status": 200
}
```


### SetInterestedCategoriesForNewUserAPI<br>
**Description**: This API is called on wigme B2B's homepage when the user selects the interested categories<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/set-interested-categories-for-new-user/](https://api.omnycomm.com/dealshub/set-interested-categories-for-new-user/)<br>
**Type**: POST<br>
```json
Request:
{
    "locationGroupUuid": "b19ec895-f07c-414f-ac09-ad8ff4b35c27",
    "interestedCategories": [
        {
            "uuid": "534ec895-107c-414f-ac09-ad8ff4b35c94"
        }
    ]
}

Response:
{
    "status": 200
}
```

### SearchAPI<br>
**Description**: This API is used to retrieve search results on kryptonworld's and parajohn's website. Earlier it was used for wigme as well.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/search/](https://api.omnycomm.com/dealshub/search/)<br>
**Type**: POST<br>
```json
Request:
{
    "language": "en",
    "name": "washing machine",
    "superCategory": "",
    "category": "",
    "subcategory": "",
    "brand": "Geepas",
    "brand_filter": ["Geepas"],
    "sort_filter": {
        "price": "high-to-low"
    },
    "page": 1,
    "locationGroupUuid": "b19ec895-f07c-414f-ac09-ad8ff4b35c27"
}

Response:
{
    "search": {
        "products": [],
        "category": "",
        "filters": [
            {
                "key": "Wattage",
                "values": ["10 W", "20 W"]
            }
        ]
    },
    "brand_list": [],
    "subCategoryList": [
        {
            "name": "",
            "uuid": "",
            "productCount": ""
        }
    ],
    "categoryList": [
        {
            "name": "",
            "name_en": "",
            "uuid": "",
            "productCount": "",
            "subCategoryList": [
                {
                    "name": "",
                    "name_en": "",
                    "uuid": "",
                    "productCount": ""
                }
            ]
        }
    ],
    "isSuperCategoryAvailable": true,
    "is_available": true,
    "totalPages": 10,
    "total_products": 204,
    "status": 200
}
```




### SearchWIG2API<br>
**Description**: This API is used to retrieve search results on wigme b2b website.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/dealshub/search-wig2/](https://api.omnycomm.com/dealshub/search-wig2/)<br>
**Type**: POST<br>
```json
Request:
{
    "language": "en",
    "name": "washing machine",
    "superCategory": "",
    "category": "",
    "subcategory": "",
    "brand": "Geepas",
    "brand_filter": ["Geepas"],
    "sort_filter": {
        "price": "high-to-low"
    },
    "page": 1,
    "page_type": "super_category"
    "locationGroupUuid": "b19ec895-f07c-414f-ac09-ad8ff4b35c27"
}

Response:
{
    "search": {
        "products": [
            {
                "name": "Geepas Washing Machine",
                "brand": "Geepas",
                "seller_sku": "GB8882",
                "now_price": "1999",
                "was_price": "2400",
                "promotional_price": "1990",
                "moq": "10",
                "stock": "4",
                "is_new_arrival": true,
                "is_on_sale": true,
                "allowedQty": 4,
                "isStockAvailable": true,
                "currency": "AED",
                "uuid": "",
                "link": "",
                "id": "",
                "heroImageUrl": "",
                "start_time": "2020-06-30 04:03:00"
                "end_time": "2020-06-30 08:03:00"
                "remaining_time": {
                    "days": 7,
                    "hours": 12,
                    "minutes": 53,
                    "seconds": 32
                },
                "promotion_tag": "Diwali Promotion",
                "is_promotional": true,
                "product_is_promotional": false
            }
        ],
        "category": "",
        "filters": [
            {
                "key": "Wattage",
                "values": ["10 W", "20 W"]
            }
        ]
    },
    "brand_list": [],
    "subCategoryList": [
        {
            "name": "",
            "uuid": "",
            "productCount": ""
        }
    ],
    "categoryList": [
        {
            "name": "",
            "name_en": "",
            "uuid": "",
            "productCount": "",
            "subCategoryList": [
                {
                    "name": "",
                    "name_en": "",
                    "uuid": "",
                    "productCount": ""
                }
            ]
        }
    ],
    "isSuperCategoryAvailable": true,
    "is_available": true,
    "totalPages": 10,
    "total_products": 204,
    "is_user_authenticated": true,
    "page_description": "",
    "seo_title": "",
    "seo_keywords": "",
    "seo_description": "",
    "short_description": "",
    "long_description": "",
    "status": 200
}
```

## Inventory Module APIs

### FetchBaseProductDetailsAPI<br>
**Description**: This API is called on Omnycomm's product edit base product page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/fetch-base-product-details/](https://api.omnycomm.com/fetch-base-product-details/)<br>
**Type**: POST<br>
```json
Request:
{
    "base_product_pk": "21049"
}

Response:
{
    
 "status": 200,
 "brand_name": "Glass",
 "base_product_name": "adaasdasdds",
 "category": "Cleaning Supplies",
 "sub_category": "Cleaning Tools",
 "category_uuid": "fc81cbee-1c5c-4630-9c01-339da8a3f146",
 "sub_category_uuid": "c12fd430-eb1d-4e89-956b-4bbe8253c926",
 "seller_sku": "dasdasdasdasd",
 "manufacturer_part_number": "",
 "manufacturer": "",
 "base_dimensions": {
  "export_carton_quantity_l": "",
  "export_carton_quantity_l_metric": "",
  "export_carton_quantity_b": "",
  "export_carton_quantity_b_metric": "",
  "export_carton_quantity_h": "",
  "export_carton_quantity_h_metric": "",
  "export_carton_crm_l": "",
  "export_carton_crm_l_metric": "",
  "export_carton_crm_b": "",
  "export_carton_crm_b_metric": "",
  "export_carton_crm_h": "",
  "export_carton_crm_h_metric": "",
  "product_dimension_l": "",
  "product_dimension_l_metric": "",
  "product_dimension_b": "",
  "product_dimension_b_metric": "",
  "product_dimension_h": "",
  "product_dimension_h_metric": "",
  "giftbox_l": "",
  "giftbox_l_metric": "",
  "giftbox_b": "",
  "giftbox_b_metric": "",
  "giftbox_h": "",
  "giftbox_h_metric": ""
 },
 "super_category_uuid": "d74ce5f5-c374-494c-950b-0c9e046c13e9",
 "super_category": "Homeware"

}
```

### FetchProductDetailsAPI<br>
**Description**: This API is called on Omnycomm's product edit product page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/fetch-product-details/](https://api.omnycomm.com/fetch-product-details/)<br>
**Type**: POST<br>
```json
Request:
{
    "product_pk": "41372"
}

Response:
{
    
 "status": 200,
 "pfl_product_name": "12\" White Oval Plate",
 "pfl_product_features": [],
 "pfl_product_features_ar": [],
 "brand_logo": "https://cdn.omnycomm.com/royalford-logo_Jv2LmXz.png",
 "brand_name": "Royalford",
 "brand_name_ar": "",
 "base_product_name": "12\" White Oval Plate",
 "super_category": "Kitchenware",
 "category": "Tableware",
 "sub_category": "Dishware and Serving Pieces",
 "category_uuid": "54bb7d7b-051a-450c-adc9-a7a6df96b668",
 "super_category_uuid": "edd10a12-65f7-4eea-85ea-09b85a315606",
 "sub_category_uuid": "00adc8e0-4e5e-4031-9d97-16dfe5193dbc",
 "seller_sku": "RF4105",
 "manufacturer_part_number": "RF4105",
 "manufacturer": "Royalford",
 "base_dimensions": {
  "export_carton_quantity_l": "",
  "export_carton_quantity_l_metric": "",
  "export_carton_quantity_b": "",
  "export_carton_quantity_b_metric": "",
  "export_carton_quantity_h": "",
  "export_carton_quantity_h_metric": "",
  "export_carton_crm_l": "",
  "export_carton_crm_l_metric": "",
  "export_carton_crm_b": "",
  "export_carton_crm_b_metric": "",
  "export_carton_crm_h": "",
  "export_carton_crm_h_metric": "",
  "product_dimension_l": "",
  "product_dimension_l_metric": "",
  "product_dimension_b": "",
  "product_dimension_b_metric": "",
  "product_dimension_h": "",
  "product_dimension_h_metric": "",
  "giftbox_l": "",
  "giftbox_l_metric": "",
  "giftbox_b": "",
  "giftbox_b_metric": "",
  "giftbox_h": "",
  "giftbox_h_metric": ""
 },
 "product_name": "12\" White Oval Plate",
 "product_description": "",
 "product_name_sap": "12\" White Oval Plate",
 "product_id": "6294009926414",
 "barcode_string": "",
 "standard_price": "",
 "quantity": "",
 "factory_notes": null,
 "factory_code": "",
 "verified": false,
 "locked": false,
 "partially_verified": false,
 "color_map": "",
 "color": "",
 "weight": 0,
 "dimensions": "NA",
 "size": "NA",
 "size_unit": "",
 "capacity": "NA",
 "capacity_unit": "",
 "target_age_range": "",
 "min_price": 0,
 "max_price": 0,
 "is_bundle_product": false,
 "variant_price_permission": true,
 "product_description_amazon_uk": "",
 "special_features": [],
 "ecommerce_dimensions": {
  "package_length": "",
  "package_length_metric": "",
  "package_width": "",
  "package_width_metric": "",
  "package_height": "",
  "package_height_metric": "",
  "package_weight": "",
  "package_weight_metric": "",
  "package_quantity": "",
  "shipping_weight": "",
  "shipping_weight_metric": "",
  "item_display_weight": "",
  "item_display_weight_metric": "",
  "item_display_volume": "",
  "item_display_volume_metric": "",
  "item_display_length": "",
  "item_display_length_metric": "",
  "item_weight": "",
  "item_weight_metric": "",
  "item_length": "",
  "item_length_metric": "",
  "item_width": "",
  "item_width_metric": "",
  "item_height": "",
  "item_height_metric": "",
  "item_display_width": "",
  "item_display_width_metric": "",
  "item_display_height": "",
  "item_display_height_metric": ""
 },
 "product_id_type": "EAN",
 "material_type": "",
 "warehouses_information": [],
 "dynamic_form_attributes": {},
 "repr_image_url": "https://cdn.omnycomm.com/no-image-placeholder.png",
 "repr_high_def_url": "https://cdn.omnycomm.com/no-image-placeholder.png",
 "barcode_image_url": "",
 "pfl_pk": 97506,
 "product_pk": 97507,
 "product_uuid": "257955a1-aa9c-441f-b28d-aff9a9118135",
 "images": {
  "main_images": [],
  "sub_images": [],
  "pfl_images": [],
  "pfl_generated_images": [],
  "white_background_images": [],
  "lifestyle_images": [],
  "certificate_images": [],
  "giftbox_images": [],
  "diecut_images": [],
  "aplus_content_images": [],
  "ads_images": [],
  "unedited_images": [],
  "transparent_images": [],
  "best_images": [],
  "all_images": []
 },
 "base_product_pk": 83258,
 "verify_product": false,
 "delete_product": false,
 "faqs": [],
 "how_to_use": [],
 "user_manual": "",
 "is_sap_exception": false,
 "atp_threshold": 100,
 "holding_threshold": 5

}
```


### FetchDealsHubProductsAPI<br>
**Description**: This API is called on Omnycomm's product edit base product page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/fetch-dealshub-products/](https://api.omnycomm.com/fetch-dealshub-products/)<br>
**Type**: POST<br>
```json
Request:
{
    "page": "1"
    "search_list": "[]"
    "locationGroupUuid": "f17c7336-644c-44a3-bc92-4f0c0b11463b"
}

Response:
{
    
 
 "status": 200,
 "active_products": 10728,
 "inactive_products": 21450,
 "variant_price_permission": true,
 "dealshub_price_permission": true,
 "dealshub_stock_permission": true,
 "is_available": true,
 "total_products": 12682,
 "products": [
  {
   "product_pk": 97507,
   "product_uuid": "44794cc6",
   "product_id": "6294009926414",
   "product_name": "12\" White Oval Plate",
   "product_name_ar": "",
   "seller_sku": "RF4105",
   "brand_name": "Royalford",
   "channel_status": false,
   "is_cod_allowed": true,
   "is_new_arrival": false,
   "is_on_sale": false,
   "category": "Tableware",
   "sub_category": "Dishware and Serving Pieces",
   "was_price": "0.0",
   "now_price": "0.0",
   "stock": "0",
   "min_price": "0.0",
   "max_price": "0.0",
   "repr_image_url": "https://cdn.omnycomm.com/no-image-placeholder.png",
   "repr_high_def_url": "https://cdn.omnycomm.com/no-image-placeholder.png"
  }
 ]

}
```

### BulkUpdateDealshubProductPriceAPI<br>
**Description**: This API is called on Omnycomm's dealshub admin product's page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/bulk-update-dealshub-product-price/](https://api.omnycomm.com/bulk-update-dealshub-product-price/)<br>
**Type**: POST<br>
```json
Request:
{
    "locationGroupUuid": "4724a505-8b23-45fe-bf98-4d4b23817aa4",
    "import_file": "tmp/bulk-upload-price.xlsx"
}

Response:
{
    
 "status": 200,
 "approved": True
}
```

### BulkUpdateB2BDealshubProductPriceAPI<br>
**Description**: This API is called on Omnycomm's dealshub admin product's page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/bulk-update-b2b-dealshub-product-price/](https://api.omnycomm.com/bulk-update-dealshub-b2b-product-price/)<br>
**Type**: POST<br>
```json
Request:
{
    "locationGroupUuid": "4724a505-8b23-45fe-bf98-4d4b23817aa4",
    "import_file": "tmp/bulk-upload-b2b-price.xlsx"
}

Response:
{
    
 "status": 200,
 "approved": True
}
```

### BulkUpdateDealshubProductStockAPI<br>
**Description**: This API is called on Omnycomm's dealshub admin product's page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/bulk-update-dealshub-product-stock/](https://api.omnycomm.com/bulk-update-dealshub-product-stock/)<br>
**Type**: POST<br>
```json
Request:
{
    "locationGroupUuid": "4724a505-8b23-45fe-bf98-4d4b23817aa4",
    "import_file": "tmp/bulk-upload-stock.xlsx"
}

Response:
{
    
 "status": 200,
 "approved": True
}
```

### BulkUpdateDealshubProductPublishStatusAPI<br>
**Description**: This API is called on Omnycomm's dealshub admin product's page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/bulk-update-dealshub-product-publish-status/](https://api.omnycomm.com/bulk-update-dealshub-product-publish-status/)<br>
**Type**: POST<br>
```json
Request:
{
    "locationGroupUuid": "4724a505-8b23-45fe-bf98-4d4b23817aa4",
    "import_file": "tmp/bulk-upload-stock.xlsx"
}

Response:
{
    
 "status": 200,
 "approved": True
}
```



### BulkDownloadDealshubProductAPI<br>
**Description**: This API is called on Omnycomm's dealshub admin product's page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/bulk-download-dealshub-product/](https://api.omnycomm.com/bulk-download-dealshub-product/)<br>
**Type**: POST<br>
```json
Request:
{
    "locationGroupUuid": "4724a505-8b23-45fe-bf98-4d4b23817aa4",
}

Response:
{
    
 "status": 200,
 "approved": True
}
```

### SaveBaseProductAPI<br>
**Description**: This API is called on Omnycomm's edit base product page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/save-base-product/](https://api.omnycomm.com/save-base-product/)<br>
**Type**: POST<br>
```json
Request:
{
 "brand_name": "Glass",
 "base_product_name": "adaasdasdds",
 "category": "Cleaning Supplies",
 "sub_category": "Cleaning Tools",
 "category_uuid": "fc81cbee-1c5c-4630-9c01-339da8a3f146",
 "sub_category_uuid": "c12fd430-eb1d-4e89-956b-4bbe8253c926",
 "seller_sku": "dasdasdasdasd",
 "manufacturer_part_number": "",
 "manufacturer": "",
 "base_dimensions": {
  "export_carton_quantity_l": "",
  "export_carton_quantity_l_metric": "",
  "export_carton_quantity_b": "",
  "export_carton_quantity_b_metric": "",
  "export_carton_quantity_h": "",
  "export_carton_quantity_h_metric": "",
  "export_carton_crm_l": "",
  "export_carton_crm_l_metric": "",
  "export_carton_crm_b": "",
  "export_carton_crm_b_metric": "",
  "export_carton_crm_h": "",
  "export_carton_crm_h_metric": "",
  "product_dimension_l": "",
  "product_dimension_l_metric": "",
  "product_dimension_b": "",
  "product_dimension_b_metric": "",
  "product_dimension_h": "",
  "product_dimension_h_metric": "",
  "giftbox_l": "",
  "giftbox_l_metric": "",
  "giftbox_b": "",
  "giftbox_b_metric": "",
  "giftbox_h": "",
  "giftbox_h_metric": ""
 }
}


Response:
{
 "status": 200,
}
```

### SaveProductAPI<br>
**Description**: This API is called on Omnycomm's dealshub admin product's page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/bulk-download-dealshub-product/](https://api.omnycomm.com/bulk-download-dealshub-product/)<br>
**Type**: POST<br>
```json
Request:
{
    "product_pk": "41374",
    "product_name": "variant product name",
    "barcode_string": "NA"
    "barcode_type": "ASIN",
    "color": "NA", 
    "color_map": "NA", 
    "standard_price": "NA", 
    "quantity": "NA", 
    "product_id_type": ARTICLE
    "material_type": 
    "pfl_product_name": 
    "pfl_product_features": []
    "pfl_product_features_ar": []
    "factory_notes": 
    "product_id": 6294015181818
    "factory_code": 
    "is_bundle_product": false
    "is_sap_exception": true
    "is_cod_allowed": false
    "product_description": <p>b"</p><p>b''</p><p>"</p>
    "faqs": []
    "how_to_use": []
    "min_price": 0
    "max_price": 50
    "atp_threshold": 0
    "holding_threshold": 0
    "was_price": 0
    "now_price": 0
    "stock": 0
    "dynamic_form_attributes": {}
    "weight": "NA",
    "size": "NA",
    "size_unit": "NA",
    "capacity": "NA",
    "capacity_unit": "NA",
    "target_age_range": "NA",
 
}

Response:
{
  "status": 200,
  "variant_price_permission": true,
  "dealshub_price_permission": true,
  "dealshub_stock_permission": true
}
```


### FetchProductListAPI<br>
**Description**: This API is called on Omnycomm's product's page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/fetch-product-list/](https://api.omnycomm.com/fetch-product-list/)<br>
**Type**: POST<br>
```json
Request:
{
 "filter_parameters": {
  "brand_name": "Royalford",
  "end_date": "2022-01-04T05:33:13.920Z",
  "has_image": "1",
  "start_date": "2022-01-04T05:33:13.920Z",
  "verified": "false"
 },
 "page": "1",
 "tags": []
}

Response:
{
  "status": 200,
 "is_available": true,
 "total_products": 19828,
  "price_type": "true",
 "products": [
  {
   "base_product_pk": 21049,
   "product_name": "Base Product 1",
   "manufacturer": "",
   "manufacturer_part_number": "",
   "base_main_images": [
    {
     "main_url": "https://cdn.omnycomm.com/image_product.jpeg",
     "thumbnail_url": "https://cdn.omnycomm.com/thumbnails/image_product.jpeg",
     "midimage_url": "https://cdn.omnycomm.com/midsize/image_product.jpeg",
     "pk": 32647,
     "is_main_image": true
    }
   ],
}
```


### UploadProductImageAPI<br>
**Description**: This API is called on Omnycomm's product's page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/upload-product-image/](https://api.omnycomm.com/upload-product-image/)<br>
**Type**: POST<br>
```json
Request:
{
 "image_0": "image_object",
 "product_pk": "41374",
 "image_count": "1",
 "image_category": "sub_images"
}
** Note: Here the request payload is sent as Form-data **
Response:
{
  "status": 200,
}
```

### FetchBrandsAPI<br>
**Description**: This API is called on Omnycomm's dealshub-admin product's page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/fetch-brands/](https://api.omnycomm.com/fetch-brands/)<br>
**Type**: POST<br>
```json
Request:
{
  
}
** Note: Here the request payload is empty **
Response:
{
 "status": 200,
 "brand_list": [
  {
   "name": "Royalford",
   "name_ar": "",
   "pk": 2401
  },
  {
   "name": "5",
   "name_ar": "",
   "pk": 2402
  }
]
}
```
### FetchUserProfileAPI<br>
**Description**: This API is called on Omnycomm's User page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/fetch-user-profile/](https://api.omnycomm.com/fetch-user-profile/)<br>
**Type**: POST<br>
```json
Request:
{
  
}
** Note: Here the request payload is empty **
Response:
{
 "status": 200,
 "contact_number": "+971888888888",
 "designation": "Content Manager",
 "username": "dealshub",
 "first_name": "DealsHub",
 "last_name": "DealsHub",
 "email": "nisarg@omnycomm.com",
 "permissible_brands": [
  "Protein2O",
  "Gurmex",
  "Dates",
  "L'Or",
  "Hawaa",
  "Dr.Chef",
  "Crespo"
 ],
 "img_url": "",
 "permissions": [
  {
   "title": "Brand",
   "Items": [
    "Royalford",
    "5",
    "Glass",
    "122X40CM",
    "Royal",
    "Pepper",
    "Coffee",
    
   ]
  },
  {
   "title": "Ecommerce",
   "Items": [
    "WIGme - Dubai",
    "Daycart - KSA",
    "WIGme - B2B",
    "WIGme - KWT",
    "WIGme - BAH",
    "Geepas-Uganda",
    "Nesto - UAE - B2B",
    "Can Update Price",
    "Can Update Stock"
   ]
  },
  {
   "title": "Product",
   "Items": [
    "Can Update Min/Max Price",
    "Can Verify Product",
    "Can Add Image",
    "Can Change Image",
    "Can Delete Image",
    "Can Add Product",
    "Can Change Product",
    "Can Delete Product"
   ]
  },
  {
   "title": "Flyer",
   "Items": [
    "Can Add Flyer",
    "Can Change Flyer",
    "Can Delete Flyer"
   ]
  }
 ]
}
```


### FetchAdminActivityLogsAPI<br>
**Description**: This API is called on Omnycomm's activity-logs page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://api.omnycomm.com/fetch-admin-activity-logs/](https://api.omnycomm.com/fetch-admin-activity-logs/)<br>
**Type**: POST<br>
```json
Request:
{
"from_date": "2022-01-01 00:00:00",
"locationGroupUuid": "4724a505-8b23-45fe-bf98-4d4b23817aa4",
"page": "1",
"search_string": "",
"to_date": "2022-01-01 00:00:00"
}

Response:
{
 
 "status": 200,
 "is_available": false,
 "totalPages": 1,
 "totalActivites": 50,
 "activity_log_list": [
  {
   "username": "dealshub",
   "first_name": "DealsHub",
   "last_name": "DealsHub",
   "date": "04 Jan, 2022",
   "time": "11:16 AM",
   "table_name": "OCReport",
   "action_type": "created",
   "render": "Bulk update products status with report  bulk upload product is created",
   "prev_instance": {},
   "current_instance": {
    "id": "765",
    "name": "bulk upload product",
    "report_title": "bulk upload publish status",
    "created_date": "2022-01-04 07:16:15.431912+00:00",
    "created_by": "2",
    "is_processed": "False",
    "completion_date": "None",
    "note": "report for the bulk upload of the publish status",
    "filename": "files/reports/2022-01-04_11:16:15_bulk upload product.xlsx",
    "uuid": "cbd4054d-fdb8-433d-ac6a-f3dbeed7bb70",
    "organization": "1",
    "location_group": "1"
   }
  }
]
}
```


### SaveCompanyProfileAPI<br>
**Description**: This API is called on Omnycomm's company-profile page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://save-company-profile/](https://api.omnycomm.com/save-company-profile/)<br>
**Type**: POST<br>
```json
Request:
{
 {
 "company-data": {
  "color:scheme": {
   "add_to_cart_button_color": "#000000",
   "buy_now_button_color": "#D42512",
   "inquire_button_color": "#1EADD8",
   "navbar_text_color": "#FFFFFF",
   "primary_color": "#000000",
   "secondary_color": "#a11d1d"
  },
  "crunchbase_link": "crunch.test",
  "email_info": "nisarg@omnycomm.com",
  "facebook_link": "sdsdvvvvsdv.dv",
  "footer_logo_image_url": "https://cdn.omnycomm.com/FooterLogo_vtlSqih.png",
  "instagram_link": "sdfsdvsd.sd",
  "linkedin_link": "linkedin.ete",
  "logo_image_url": "https://cdn.omnycomm.com/Wigme_Logo_c1.jpg",
  "seo_google_meta": "",
  "seo_google_meta_title": "",
  "seo_long_description": "<p><br></p>",
  "seo_short_description": "",
  "seo_title": "",
  "twitter_link": "svsdvss.dd",
  "whatsapp_info": "504506246",
  "youtube_link": "test.testd"
 },
 "locationGroupUuid": "4724a505-8b23-45fe-bf98-4d4b23817aa4"
}
}

Response:
{
 "status": 200
}
```


### FetchLocationGroupListAPI<br>
**Description**: This API is called on Omnycomm's home page.<br>
**Response Time**: 200 ms<br>
**Endpoint**: [https://save-company-profile/](https://api.omnycomm.com/save-company-profile/)<br>
**Type**: POST<br>
```json
Request:
{
 
}

Response:
{
 "status": 200
}
```