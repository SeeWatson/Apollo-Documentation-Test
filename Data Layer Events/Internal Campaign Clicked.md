# Internal Campaign Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "select_promotion",
  "apollo_event": "Internal Campaign Clicked",
    "ecommerce": {
        "creative_name": "<creative_name>",
        "creative_slot": "<creative_slot>",
        "items": [
            {
                "affiliation": "<affiliation>",
                "coupon": "<coupon>",
                "creative_name": "<creative_name>",
                "creative_slot": "<creative_slot>",
                "currency": "<currency>",
                "discount": <discount>,
                "index": <index>,
                "item_brand": "<item_brand>",
                "item_category": "<item_category>",
                "item_category2": "<item_category2>",
                "item_category3": "<item_category3>",
                "item_category4": "<item_category4>",
                "item_category5": "<item_category5>",
                "item_finding_method": "<item_finding_method>",
                "item_id": "<item_id>",
                "item_list_id": "<item_list_id>",
                "item_list_name": "<item_list_name>",
                "item_name": "<item_name>",
                "item_variant": "<item_variant>",
                "location_id": "<location_id>",
                "price": <price>,
                "promotion_id": "<promotion_id>",
                "promotion_name": "<promotion_name>",
                "quantity": <quantity>
            }
        ],
        "promotion_id": "<promotion_id>",
        "promotion_name": "<promotion_name>",
        "promotion_objective": "<promotion_objective>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|creative_name|string|Count of impressions for external campaigns taking place outside of the website \(i.e. Google Ads, Doubleclick display ads\).|Girl with bike, Mountain Top, River Cruise Danube|||||||
|creative_name|string|The name of a creative used in a promotional spot.|summer\_banner2|||||||
|creative_slot|string|The name of a creative slot.|featured\_app\_1|||||||
|creative_slot|string|The name of the promotional creative slot associated with the event.||||||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|index|number|The index\/position of the item in a list.|1, 2, 3, 4|||||||
|item_brand|string|Item brand|Gucci|||||||
|item_category|string|Item Category \(context-specific\). item\_category2 through item\_category5 can also be used if the item has many categories.|pants|||||||
|item_category2|string|The second category of an item.||||||||
|item_category3|string|The third category of an item.||||||||
|item_category4|string|The fourth category of an item.||||||||
|item_category5|string|The fifth category of an item.||||||||
|item_finding_method|string|Captures the name or ID of the container within which exit links are used.||||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|item_list_id|string|The computer-readible machine name of the list the item showed up in \(if sent with a view\_item\_list event\). Use UUID provided by the component if no more specific ID is available.|12345abcde12345|||||||
|item_list_name|string|The human-readible name of the item list the item showed up in \(if sent with a view\_item\_list event\). If one is not available, populate with numerical index of which list this is on the page \(1-indexed\). For filter\_by\_group component, use that value.|filter\_by\_group, recommended\_products, recently\_viewed\_products|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|item_variant|string|The variant of the item.|Black|||||||
|location_id|string|The location associated with the event. If possible, set to the Google Place ID that corresponds to the associated item. Can also be overridden to a custom location ID string.|L\_12345|||||||
|price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||
|promotion_id|string|The ID of a product promotion.|P\_12345|||||||
|promotion_id|string|The ID of the promotion associated with the event.||||||||
|promotion_name|string|Captures the name or ID of the region within which exit links are used.|Trek bikes for kids, REI Spring Sale 2019, Viking Cruise Fall Specials|||||||
|promotion_name|string|The name of a product promotion. One of promotion\_id or promotion name is required.|Summer Sale|||||||
|promotion_objective|string|Count of clicks on external campaigns taking place outside of the website \(i.e. Google Ads, Doubleclick display ads\).|Order Starter, Order Value, Newsletter Subscriptions, 12, 33, 44|||||||
|quantity|integer|Item quantity.|1|||||||




