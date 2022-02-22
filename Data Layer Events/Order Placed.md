# Order Placed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "purchase",
  "apollo_event": "Order Placed",
    "ecommerce": {
        "affiliation": "<affiliation>",
        "alternate_pickup_person": "<alternate_pickup_person>",
        "cart_id": "<cart_id>",
        "country": "<country>",
        "coupon": "<coupon>",
        "currency": "<currency>",
        "fulfillment_method": "<fulfillment_method>",
        "items": [
            {
                "affiliation": "<affiliation>",
                "coupon": "<coupon>",
                "currency": "<currency>",
                "discount": <discount>,
                "fulfillment_source": "<fulfillment_source>",
                "fulfillment_store_id": "<fulfillment_store_id>",
                "index": <index>,
                "item_brand": "<item_brand>",
                "item_business_unit": "<item_business_unit>",
                "item_category": "<item_category>",
                "item_category2": "<item_category2>",
                "item_category3": "<item_category3>",
                "item_category4": "<item_category4>",
                "item_category5": "<item_category5>",
                "item_color": "<item_color>",
                "item_cost": "<item_cost>",
                "item_gift_wrapped": <item_gift_wrapped>,
                "item_id": "<item_id>",
                "item_is_sample": "<item_is_sample>",
                "item_is_web_exclusive": <item_is_web_exclusive>,
                "item_list_id": "<item_list_id>",
                "item_list_name": "<item_list_name>",
                "item_markdown_price": "<item_markdown_price>",
                "item_name": "<item_name>",
                "item_price_tier": "<item_price_tier>",
                "item_price_type": "<item_price_type>",
                "item_product_line": "<item_product_line>",
                "item_sku": "<item_sku>",
                "item_trademarked_technology": "<item_trademarked_technology>",
                "item_variant": "<item_variant>",
                "location_id": "<location_id>",
                "loyalty_points_used": "<loyalty_points_used>",
                "price": <price>,
                "quantity": <quantity>,
                "third_party_vendor_id": "<third_party_vendor_id>"
            }
        ],
        "items_purchased_together": "<items_purchased_together>",
        "number_of_payment_methods": <number_of_payment_methods>,
        "order_level_discount": "<order_level_discount>",
        "payment_id": "<payment_id>",
        "payment_method": "<payment_method>",
        "postal_code": "<postal_code>",
        "product_skus_purchased_together": "<product_skus_purchased_together>",
        "revenue_band": "<revenue_band>",
        "sequence": <sequence>,
        "ship_to_country": "<ship_to_country>",
        "ship_to_postal_code": "<ship_to_postal_code>",
        "ship_to_state_or_province": "<ship_to_state_or_province>",
        "shipping": <shipping>,
        "shipping_amount_collected": "<shipping_amount_collected>",
        "shipping_coupon": "<shipping_coupon>",
        "shipping_discount": "<shipping_discount>",
        "shipping_tier": "<shipping_tier>",
        "state_province": "<state_province>",
        "tax": <tax>,
        "tax_amount_collected": "<tax_amount_collected>",
        "text_notification_selections": <text_notification_selections>,
        "transaction_id": "<transaction_id>",
        "value": <value>
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A order affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|alternate_pickup_person|string|Captures the Product Id requested in search criteria.||||||||
|cart_id|string|Captures the name or ID of the region within which CTA links are used.|12345, 435678, 34567, XCV456, XCV876|||||||
|country|string|Captures the type of on-site search performed \(i.e., content, product, location, product location, scheduled event, room, report\)|US, CA, FR, UK|^[A-Z]{2}$||||||
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|coupon|string|Order-level coupon code used for a purchase.|summer\_fun|||||||
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|fulfillment_method|string|Captures the Radius from the POI \(point of interest\) defining the location search area.|Shipped, Emailed, Pick Up In Store, Will Call|||||||
|fulfillment_source|string|Captures the technology vendor providing the map UI|Vendor:xyz, Store:43567, Email:system3, Warehouse:7865|||||||
|fulfillment_store_id|string|Captures the start date requested in search criteria. \(e.g. check-in date\)|stew's boot shop, kat's cat toys, 12345|||||||
|index|number|The index\/position of the item in a list.|1, 2, 3, 4|||||||
|item_brand|string|Item brand|Gucci|||||||
|item_business_unit|string|Count of times that a location in a location listing was clicked.|Apparel, Shoes, Home|||||||
|item_category|string|Item Category \(context-specific\). item\_category2 through item\_category5 can also be used if the item has many categories.|pants|||||||
|item_category2|string|The second category of an item.||||||||
|item_category3|string|The third category of an item.||||||||
|item_category4|string|The fourth category of an item.||||||||
|item_category5|string|The fifth category of an item.||||||||
|item_color|string|Count of time that cart popups were displayed to visitors.|Antique Oak, Granite, Black Marble, Knotty Pine|||||||
|item_cost|string|Count of locations displayed in location listings.||||||||
|item_gift_wrapped|boolean|Captures the number of children entered in search criteria.||||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|item_is_sample|string|Captures the name or ID of the container within which navigation links are used.|TRUE, FALSE|||||||
|item_is_web_exclusive|boolean|Captures the city\|state\|zip combination that was used to search for a store||||||||
|item_list_id|string|The computer-readible machine name of the list the item showed up in \(if sent with a view\_item\_list event\). Use UUID provided by the component if no more specific ID is available.|12345abcde12345|||||||
|item_list_name|string|The human-readible name of the item list the item showed up in \(if sent with a view\_item\_list event\). If one is not available, populate with numerical index of which list this is on the page \(1-indexed\). For filter\_by\_group component, use that value.|filter\_by\_group, recommended\_products, recently\_viewed\_products|||||||
|item_markdown_price|string|Position of the location clicked within a location listing view.|200, 29.99, 50, 0|^[0-9]*(\.[0-9]{1,2})?$||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|item_price_tier|string|Captures the price type \(i.e. List, Markdown, Clearance, Bundle\) associated with a product.|Good, Better, Best, Bronze, Silver, Gold|||||||
|item_price_type|string|Captures the page name within which CTA links are used.|1st mark, 2nd mark, 3rd mark, clearance, sale, doorbuster|||||||
|item_product_line|string|Captures the product SKU \(stock keeping unit\) associated with products.|Laminate Wood, Vinyl, Hardwood, Stone, Ceramic|||||||
|item_sku|string|Captures the ID associated with CTA links used.|34567890, 4567890, 00155-large-cornflower|||||||
|item_trademarked_technology|string|Count of times that visitors click on a Call to Action \(CTA\) link.|Stainmaster, GoreTex, WeatherShield|||||||
|item_variant|string|The variant of the item.|Black|||||||
|items_purchased_together|string|Captures the end date requested in search criteria.|1234\|7878\|9039, abc12\|deh213, abc12|||||||
|location_id|string|The location associated with the event. If possible, set to the Google Place ID that corresponds to the associated item. Can also be overridden to a custom location ID string.|L\_12345|||||||
|loyalty_points_used|string|Captures whether each room being booked was the first, second, third, etc. being booked in a multi-room booking.|100, 101, 1000|||||0||
|number_of_payment_methods|integer|Captures the Location Id requested in search criteria.||||||||
|order_level_discount|string|Captures the name or ID of the region within which navigation links are used.|5, 20, 10.22, 19.2|^[0-9]*(\.[0-9]{1,2})?$||||||
|payment_id|string|Captures the number of children associated with a lodging room booking.||ZPH-87698-098||||||
|payment_method|string|Captures the number of adults associated with a lodging room booking.|Credit Card, PayPal, Mastercard, Visa, Amex, Discover|||||||
|postal_code|string|Count of times that visitors encounter discount code entry failures.|53533, 30381, M1R 0E9, M3C 0C1|||||||
|price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||
|product_skus_purchased_together|string|Captures the name or ID of the navigation links used.|sku123\|sku465, 67890\|87576\|74674, $87,654|||||||
|quantity|integer|Item quantity.|1|||||||
|revenue_band|string|Captures the search text used in on-site searches.|125.05, 432.21, 90.22, 12.05|^[0-9]*(\.[0-9]{1,2})?$||||||
|sequence|integer|Total number of nights associated with a room booking.|1, 2, 3, 4, 5||||1|||
|ship_to_country|string|Captures the number of people entered in search criteria.|US, CA, FR, UK|^[A-Z]{2}$||||||
|ship_to_postal_code|string|Count of times that visitors clicked on a navigation link.|53533, 30381, M1R 0E9, M3C 0C1|||||||
|ship_to_state_or_province|string|Captures the latitude of the point on map from which distance from POI \(point of interest\) is calculated.|WI, GA, NB, ON|||||||
|shipping|number|Shipping cost associated with a transaction.|3.33|||||||
|shipping_amount_collected|string|Count of times that an on-site search was performed.|15.05, 2, 0.22, 2.2|^[0-9]*(\.[0-9]{1,2})?$||||||
|shipping_coupon|string|Captures the Unit of Measure for the location search radius|FREESHIPAPRIL, FREESHIP100|||||||
|shipping_discount|string|Count of times a user clicked a related search term to perform an onsite search.|5, 20, 10.22, 19.2|^[0-9]*(\.[0-9]{1,2})?$||||||
|shipping_tier|string|Count of times users performed searches that produced 0 results.|Regular, Overnight, Overnight AM, Overnight AM Sat, UPS Ground, UPS Air|||||||
|state_province|string|Captures the coupon code applied.|WI, GA, NB, ON|||||||
|tax|number|Tax cost associated with a transaction.|1.11|||||||
|tax_amount_collected|string|Captures the site destination of the navigation links used.|5.05, 20, 10.22, 9.2|^[0-9]*(\.[0-9]{1,2})?$||||||
|text_notification_selections|integer|The user's fields and values entered for multi-search.||||||||
|third_party_vendor_id|string|Captures the numeric value representing the zoom level of the map \(i.e. 1, 2, 3, 4\).||||||||
|transaction_id|string|The unique identifier of a transaction.|T\_12345, 19283j2nm9jdjs|^[a-zA-Z0-9]{6,20}$|6|20||||
|value|number|The monetary value of the event.|7.77, 239.55, 659|||||||




