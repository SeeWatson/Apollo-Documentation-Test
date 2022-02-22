# Product Added to Cart

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "add_to_cart",
  "apollo_event": "Product Added to Cart",
    "ecommerce": {
        "cart_id": "<cart_id>",
        "cart_modifications": <cart_modifications>,
        "currency": "<currency>",
        "fulfillment_method": "<fulfillment_method>",
        "items": [
            {
                "affiliation": "<affiliation>",
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
                "item_id": "<item_id>",
                "item_is_bopus_only": <item_is_bopus_only>,
                "item_is_sample": "<item_is_sample>",
                "item_is_web_exclusive": <item_is_web_exclusive>,
                "item_list_id": "<item_list_id>",
                "item_list_name": "<item_list_name>",
                "item_name": "<item_name>",
                "item_out_of_stock": <item_out_of_stock>,
                "item_price_tier": "<item_price_tier>",
                "item_price_type": "<item_price_type>",
                "item_product_line": "<item_product_line>",
                "item_sku": "<item_sku>",
                "item_trademarked_technology": "<item_trademarked_technology>",
                "item_variant": "<item_variant>",
                "location_id": "<location_id>",
                "price": "<price>",
                "product_offer_adds": <product_offer_adds>,
                "quantity": "<quantity>",
                "save_list_cart_adds": <save_list_cart_adds>,
                "third_party_vendor_id": "<third_party_vendor_id>"
            }
        ],
        "method": "<method>",
        "multiple_addition_detail": "<multiple_addition_detail>",
        "multiple_additions": <multiple_additions>,
        "sequence": "<sequence>",
        "value": <value>
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|cart_id|string|Captures the name or ID of the region within which CTA links are used.|12345, 435678, 34567, XCV456, XCV876|||||||
|cart_modifications|integer|Count of times the change in product quantity was the result of a cart modification.||||||||
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|fulfillment_method|string|Captures the Radius from the POI \(point of interest\) defining the location search area.|Shipped, Emailed, Pick Up In Store, Will Call|||||||
|index|number|The index\/position of the item in a list.|1, 2, 3, 4|||||||
|item_brand|string|Item brand|Gucci|||||||
|item_business_unit|string|Count of times that a location in a location listing was clicked.|Apparel, Shoes, Home|||||||
|item_category|string|Item Category \(context-specific\). item\_category2 through item\_category5 can also be used if the item has many categories.|pants|||||||
|item_category2|string|The second category of an item.||||||||
|item_category3|string|The third category of an item.||||||||
|item_category4|string|The fourth category of an item.||||||||
|item_category5|string|The fifth category of an item.||||||||
|item_color|string|Count of time that cart popups were displayed to visitors.|Antique Oak, Granite, Black Marble, Knotty Pine|||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|item_is_bopus_only|integer|Count of times the user engaged with a product whose only available shipping method was Buy Online Pick Up In Store \(i.e., BOPUS\).||||||||
|item_is_sample|string|Captures the name or ID of the container within which navigation links are used.|TRUE, FALSE|||||||
|item_is_web_exclusive|boolean|Captures the city\|state\|zip combination that was used to search for a store||||||||
|item_list_id|string|The computer-readible machine name of the list the item showed up in \(if sent with a view\_item\_list event\). Use UUID provided by the component if no more specific ID is available.|12345abcde12345|||||||
|item_list_name|string|The human-readible name of the item list the item showed up in \(if sent with a view\_item\_list event\). If one is not available, populate with numerical index of which list this is on the page \(1-indexed\). For filter\_by\_group component, use that value.|filter\_by\_group, recommended\_products, recently\_viewed\_products|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|item_out_of_stock|boolean|Count of times that products were out of stock on cart add.|TRUE, FALSE|||||||
|item_price_tier|string|Captures the price type \(i.e. List, Markdown, Clearance, Bundle\) associated with a product.|Good, Better, Best, Bronze, Silver, Gold|||||||
|item_price_type|string|Captures the page name within which CTA links are used.|1st mark, 2nd mark, 3rd mark, clearance, sale, doorbuster|||||||
|item_product_line|string|Captures the product SKU \(stock keeping unit\) associated with products.|Laminate Wood, Vinyl, Hardwood, Stone, Ceramic|||||||
|item_sku|string|Captures the ID associated with CTA links used.|34567890, 4567890, 00155-large-cornflower|||||||
|item_trademarked_technology|string|Count of times that visitors click on a Call to Action \(CTA\) link.|Stainmaster, GoreTex, WeatherShield|||||||
|item_variant|string|The variant of the item.|Black|||||||
|location_id|string|The location associated with the event. If possible, set to the Google Place ID that corresponds to the associated item. Can also be overridden to a custom location ID string.|L\_12345|||||||
|method|string|Captures how the visitors added products to the cart \(i.e. PDP, Product List, Wish List, etc.\).|PLP, PDP, Wishlist, Registry|||||||
|multiple_addition_detail|string|Captures how many products of the total displayed were added at the time of an add event \(i.e., cart add, wishlist add, registry add\).|all items, 3 of 5, 2 of 4|||||||
|multiple_additions|boolean|Count of times visitors added multiple items at the time of an event \(i.e., cart add, wishlist add, registry add\).|TRUE, FALSE|||||||
|price|string|Amount of money associated with products added to the shopping cart.|200, 29.99, 50, 0|^[0-9]*(\.[0-9]{1,2})?$||||||
|product_offer_adds|integer|Count of times an offered product \(e.g., Gift with Purchase, Purchase with Purchase\) is added to the cart.||||||||
|quantity|string|Count of product units associated with cart additions.|1, 2, 3, 4, 5||||1|||
|save_list_cart_adds|number|Count of times products were added to the cart from a "save for later" list.||||||||
|sequence|string|Captures the sequence items were added to the cart \(e.g. 1,2,3,4\)||||||||
|third_party_vendor_id|string|Captures the numeric value representing the zoom level of the map \(i.e. 1, 2, 3, 4\).||||||||
|value|number|The monetary value of the event.|7.77, 239.55, 659|||||||




