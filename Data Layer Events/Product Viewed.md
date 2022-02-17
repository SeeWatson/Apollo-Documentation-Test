# Product Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "view_item",
  "apollo_event": "Product Viewed",
    "ecommerce": {
        "competitor_pricing": "<competitor_pricing>",
        "currency": "<currency>",
        "items": [
            {
                "affiliation": "<affiliation>",
                "aggregate_rating": "<aggregate_rating>",
                "count_and_average_combined": "<count_and_average_combined>",
                "coupon": "<coupon>",
                "currency": "<currency>",
                "discount": <discount>,
                "index": <index>,
                "item_brand": "<item_brand>",
                "item_business_unit": "<item_business_unit>",
                "item_category": "<item_category>",
                "item_category2": "<item_category2>",
                "item_category3": "<item_category3>",
                "item_category4": "<item_category4>",
                "item_category5": "<item_category5>",
                "item_color": "<item_color>",
                "item_fulfillment_options": "<item_fulfillment_options>",
                "item_id": "<item_id>",
                "item_is_best_seller": "<item_is_best_seller>",
                "item_is_bopus_only": <item_is_bopus_only>,
                "item_is_featured": <item_is_featured>,
                "item_is_third_party": "<item_is_third_party>",
                "item_is_top_rated": "<item_is_top_rated>",
                "item_is_web_exclusive": <item_is_web_exclusive>,
                "item_list_id": "<item_list_id>",
                "item_list_name": "<item_list_name>",
                "item_name": "<item_name>",
                "item_out_of_stock": <item_out_of_stock>,
                "item_price_tier": "<item_price_tier>",
                "item_price_type": "<item_price_type>",
                "item_product_line": "<item_product_line>",
                "item_quantity_available": "<item_quantity_available>",
                "item_sku": "<item_sku>",
                "item_sku_known": <item_sku_known>,
                "item_status": "<item_status>",
                "item_trademarked_technology": "<item_trademarked_technology>",
                "item_variant": "<item_variant>",
                "location_id": "<location_id>",
                "number_of_ratings": <number_of_ratings>,
                "price": <price>,
                "quantity": <quantity>,
                "third_party_vendor_id": "<third_party_vendor_id>"
            }
        ],
        "items_viewed_count_lifetime": "<items_viewed_count_lifetime>",
        "items_viewed_count_visit": "<items_viewed_count_visit>",
        "value": <value>
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|aggregate_rating|string|Captures the average product rating for each product.|1.1, 2, 5|^[0-9]*(\.[0-9]{1,2})?$||||||
|competitor_pricing|string|Captures the product ID, current price and competitor price for each product.||||||||
|count_and_average_combined|string|Captures the average product rating and number of ratings for each product.|23:4.5, 222:1.7, 1:5, 2:3.5|||||||
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|index|number|The index\/position of the item in a list.|1, 2, 3, 4|||||||
|item_brand|string|Item brand|Gucci|||||||
|item_business_unit|string|Count of times that a location in a location listing was clicked.|Apparel, Shoes, Home|||||||
|item_category|string|Item Category \(context-specific\). item\_category2 through item\_category5 can also be used if the item has many categories.|pants|||||||
|item_category2|string|The second category of an item.||||||||
|item_category3|string|The third category of an item.||||||||
|item_category4|string|The fourth category of an item.||||||||
|item_category5|string|The fifth category of an item.||||||||
|item_color|string|Count of time that cart popups were displayed to visitors.|Antique Oak, Granite, Black Marble, Knotty Pine|||||||
|item_fulfillment_options|string|Captures the product fulfillment options available for each product to view impact on conversion.|Shipped Only, In Store Only, Local Pickup Only, In Store or Ship, Digital \(Email or Text\)|||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|item_is_best_seller|unknown|Count of times the product was a best seller product.||||||||
|item_is_bopus_only|integer|Count of times the user engaged with a product whose only available shipping method was Buy Online Pick Up In Store \(i.e., BOPUS\).||||||||
|item_is_featured|integer|Count of times the product was a featured\/boosted product.||||||||
|item_is_third_party|unknown|Count of times a user viewed a product page for a third party \(e.g., marketplace vendor\) product.||||||||
|item_is_top_rated|unknown|Count of times the product was a top rated product.||||||||
|item_is_web_exclusive|boolean|Captures the city\|state\|zip combination that was used to search for a store||||||||
|item_list_id|string|The computer-readible machine name of the list the item showed up in \(if sent with a view\_item\_list event\). Use UUID provided by the component if no more specific ID is available.|12345abcde12345|||||||
|item_list_name|string|The human-readible name of the item list the item showed up in \(if sent with a view\_item\_list event\). If one is not available, populate with numerical index of which list this is on the page \(1-indexed\). For filter\_by\_group component, use that value.|filter\_by\_group, recommended\_products, recently\_viewed\_products|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|item_out_of_stock|boolean|Count of times that visitors clicked to select a product SKU that was out of stock.|TRUE, FALSE|||||||
|item_price_tier|string|Captures the price type \(i.e. List, Markdown, Clearance, Bundle\) associated with a product.|Good, Better, Best, Bronze, Silver, Gold|||||||
|item_price_type|string|Captures the page name within which CTA links are used.|1st mark, 2nd mark, 3rd mark, clearance, sale, doorbuster|||||||
|item_product_line|string|Captures the product SKU \(stock keeping unit\) associated with products.|Laminate Wood, Vinyl, Hardwood, Stone, Ceramic|||||||
|item_quantity_available|unknown|Captures the product quantity available.|1, 10, 100|||||||
|item_sku|string|Captures the ID associated with CTA links used.|34567890, 4567890, 00155-large-cornflower|||||||
|item_sku_known|boolean|Count of times that product sku was known on initial view of product detail page.|TRUE, FALSE|||||||
|item_status|string|Captures the status of each product.|In Stock, Out of Stcok, Back-Ordered|||||||
|item_trademarked_technology|string|Count of times that visitors click on a Call to Action \(CTA\) link.|Stainmaster, GoreTex, WeatherShield|||||||
|item_variant|string|The variant of the item.|Black|||||||
|items_viewed_count_lifetime|string|Captures how many times visitors viewed products across all visits. This is dependent upon cookie deletion.||||||||
|items_viewed_count_visit|string|Captures how many times visitors viewed products within the visit.||||||||
|location_id|string|The location associated with the event. If possible, set to the Google Place ID that corresponds to the associated item. Can also be overridden to a custom location ID string.|L\_12345|||||||
|number_of_ratings|integer|Captures the number of ratings for each product.|1, 5, 11, 200||||0|||
|price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||
|quantity|integer|Item quantity.|1|||||||
|third_party_vendor_id|string|Captures the numeric value representing the zoom level of the map \(i.e. 1, 2, 3, 4\).||||||||
|value|number|The monetary value of the event.|7.77, 239.55, 659|||||||




