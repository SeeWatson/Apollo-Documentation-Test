# Cart Popup Displayed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "view_cart",
  "apollo_event": "Cart Popup Displayed",
    "ecommerce": {
        "cart_id": "<cart_id>",
        "currency": "<currency>",
        "items": [
            {
                "affiliation": "<affiliation>",
                "coupon": "<coupon>",
                "currency": "<currency>",
                "discount": <discount>,
                "index": <index>,
                "item_brand": "<item_brand>",
                "item_category": "<item_category>",
                "item_category2": "<item_category2>",
                "item_category3": "<item_category3>",
                "item_category4": "<item_category4>",
                "item_category5": "<item_category5>",
                "item_color": "<item_color>",
                "item_id": "<item_id>",
                "item_list_id": "<item_list_id>",
                "item_list_name": "<item_list_name>",
                "item_name": "<item_name>",
                "item_price_tier": "<item_price_tier>",
                "item_product_line": "<item_product_line>",
                "item_sku": "<item_sku>",
                "item_trademarked_technology": "<item_trademarked_technology>",
                "item_variant": "<item_variant>",
                "location_id": "<location_id>",
                "price": <price>,
                "quantity": <quantity>
            }
        ],
        "value": <value>,
        "view_cart": "<view_cart>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|cart_id|string|Captures the name or ID of the region within which CTA links are used.|12345, 435678, 34567, XCV456, XCV876|||||||
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|index|number|The index\/position of the item in a list.|1, 2, 3, 4|||||||
|item_brand|string|Item brand|Gucci|||||||
|item_category|string|Item Category \(context-specific\). item\_category2 through item\_category5 can also be used if the item has many categories.|pants|||||||
|item_category2|string|The second category of an item.||||||||
|item_category3|string|The third category of an item.||||||||
|item_category4|string|The fourth category of an item.||||||||
|item_category5|string|The fifth category of an item.||||||||
|item_color|string|Count of time that cart popups were displayed to visitors.|Antique Oak, Granite, Black Marble, Knotty Pine|||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|item_list_id|string|The computer-readible machine name of the list the item showed up in \(if sent with a view\_item\_list event\). Use UUID provided by the component if no more specific ID is available.|12345abcde12345|||||||
|item_list_name|string|The human-readible name of the item list the item showed up in \(if sent with a view\_item\_list event\). If one is not available, populate with numerical index of which list this is on the page \(1-indexed\). For filter\_by\_group component, use that value.|filter\_by\_group, recommended\_products, recently\_viewed\_products|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|item_price_tier|string|Captures the price type \(i.e. List, Markdown, Clearance, Bundle\) associated with a product.|Good, Better, Best, Bronze, Silver, Gold|||||||
|item_product_line|string|Captures the product SKU \(stock keeping unit\) associated with products.|Laminate Wood, Vinyl, Hardwood, Stone, Ceramic|||||||
|item_sku|string|Captures the ID associated with CTA links used.|34567890, 4567890, 00155-large-cornflower|||||||
|item_trademarked_technology|string|Count of times that visitors click on a Call to Action \(CTA\) link.|Stainmaster, GoreTex, WeatherShield|||||||
|item_variant|string|The variant of the item.|Black|||||||
|location_id|string|The location associated with the event. If possible, set to the Google Place ID that corresponds to the associated item. Can also be overridden to a custom location ID string.|L\_12345|||||||
|price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||
|quantity|integer|Item quantity.|1|||||||
|value|number|The monetary value of the event.|7.77, 239.55, 659|||||||
|view_cart|unknown|Count of orders taking place offline from internal databases for use in comparing to online orders.||||||||




