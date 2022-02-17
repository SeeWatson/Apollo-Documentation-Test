# Product Added to Registry

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "add_to_wishlist",
  "apollo_event": "Product Added to Registry",
    "ecommerce": {
        "currency": "<currency>",
        "gift_registry_additions": "<gift_registry_additions>",
        "identifier": "<identifier>",
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
                "item_id": "<item_id>",
                "item_list_id": "<item_list_id>",
                "item_list_name": "<item_list_name>",
                "item_name": "<item_name>",
                "item_price_type": "<item_price_type>",
                "item_sku": "<item_sku>",
                "item_variant": "<item_variant>",
                "location_id": "<location_id>",
                "price": <price>,
                "quantity": <quantity>
            }
        ],
        "multiple_addition_detail": "<multiple_addition_detail>",
        "multiple_additions": <multiple_additions>,
        "type": "<type>",
        "value": <value>
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|gift_registry_additions|string|Count of times visitors added products to a gift registry.||||||||
|identifier|string|Captures the ID associated with a gift registry.|12345, 435678, 34567, XCV456, XCV876|||||||
|index|number|The index\/position of the item in a list.|1, 2, 3, 4|||||||
|item_brand|string|Item brand|Gucci|||||||
|item_category|string|Item Category \(context-specific\). item\_category2 through item\_category5 can also be used if the item has many categories.|pants|||||||
|item_category2|string|The second category of an item.||||||||
|item_category3|string|The third category of an item.||||||||
|item_category4|string|The fourth category of an item.||||||||
|item_category5|string|The fifth category of an item.||||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|item_list_id|string|The computer-readible machine name of the list the item showed up in \(if sent with a view\_item\_list event\). Use UUID provided by the component if no more specific ID is available.|12345abcde12345|||||||
|item_list_name|string|The human-readible name of the item list the item showed up in \(if sent with a view\_item\_list event\). If one is not available, populate with numerical index of which list this is on the page \(1-indexed\). For filter\_by\_group component, use that value.|filter\_by\_group, recommended\_products, recently\_viewed\_products|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|item_price_type|string|Captures the page name within which CTA links are used.|1st mark, 2nd mark, 3rd mark, clearance, sale, doorbuster|||||||
|item_sku|string|Captures the ID associated with CTA links used.|34567890, 4567890, 00155-large-cornflower|||||||
|item_variant|string|The variant of the item.|Black|||||||
|location_id|string|The location associated with the event. If possible, set to the Google Place ID that corresponds to the associated item. Can also be overridden to a custom location ID string.|L\_12345|||||||
|multiple_addition_detail|string|Captures how many products of the total displayed were added at the time of an add event \(i.e., cart add, wishlist add, registry add\).|all items, 3 of 5, 2 of 4|||||||
|multiple_additions|boolean|Count of times visitors added multiple items at the time of an event \(i.e., cart add, wishlist add, registry add\).|TRUE, FALSE|||||||
|price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||
|quantity|integer|Item quantity.|1|||||||
|type|string|Captures the type associated with a gift registry \(i.e. wedding, baby\).|Wedding, Baby, Birth Day, Anniversary|||||||
|value|number|The monetary value of the event.|7.77, 239.55, 659|||||||




