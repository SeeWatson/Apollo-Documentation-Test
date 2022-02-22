# Room Listing Item Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "select_item",
  "apollo_event": "Room Listing Item Clicked",
    "ecommerce": {
        "currency": "<currency>",
        "facets": "<facets>",
        "item_list_id": "<item_list_id>",
        "item_list_name": "<item_list_name>",
        "items": [
            {
                "affiliation": "<affiliation>",
                "aggregate_rating": "<aggregate_rating>",
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
                "item_type": "<item_type>",
                "item_variant": "<item_variant>",
                "location_id": "<location_id>",
                "location_name": "<location_name>",
                "number_of_ratings": <number_of_ratings>,
                "point_range_high": <point_range_high>,
                "point_range_low": <point_range_low>,
                "price": <price>,
                "price_range_high": "<price_range_high>",
                "price_range_low": "<price_range_low>",
                "quantity": <quantity>,
                "rate_code": "<rate_code>",
                "units_available": <units_available>
            }
        ],
        "listing_context": "<listing_context>",
        "listing_driver": "<listing_driver>",
        "sort_order": "<sort_order>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|aggregate_rating|string|Captures the ID of each field contained on a form.|1.1, 2, 5|^[0-9]*(\.[0-9]{1,2})?$||||||
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|currency|string|Number of tickets associates with an event booking at the time of booking completion.|USD, CAD, GBP, CHF|^[A-Z]{3}$|3|3||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|facets|string|Number of points associated with an event booking at the time of booking completion.|sort\~price ascending\|color\~green\|size\~medium|||||||
|index|number|The index\/position of the item in a list.|1, 2, 3, 4|||||||
|item_brand|string|Item brand|Gucci|||||||
|item_category|string|Item Category \(context-specific\). item\_category2 through item\_category5 can also be used if the item has many categories.|pants|||||||
|item_category2|string|The second category of an item.||||||||
|item_category3|string|The third category of an item.||||||||
|item_category4|string|The fourth category of an item.||||||||
|item_category5|string|The fifth category of an item.||||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|item_list_id|string|The computer-readible machine name of the list the item showed up in \(if sent with a view\_item\_list event\). Use UUID provided by the component if no more specific ID is available.|12345abcde12345|||||||
|item_list_id|string|The computer-readible machine name of the list the item showed up in \(if sent with a view\_item\_list event\). Use UUID provided by the component if no more specific ID is available.|12345abcde12345|||||||
|item_list_name|string|The human-readible name of the item list the item showed up in \(if sent with a view\_item\_list event\). If one is not available, populate with numerical index of which list this is on the page \(1-indexed\). For filter\_by\_group component, use that value.|filter\_by\_group, recommended\_products, recently\_viewed\_products|||||||
|item_list_name|string|The human-readible name of the item list the item showed up in \(if sent with a view\_item\_list event\). If one is not available, populate with numerical index of which list this is on the page \(1-indexed\). For filter\_by\_group component, use that value.|filter\_by\_group, recommended\_products, recently\_viewed\_products|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|item_price_type|string|Captures the page name within which CTA links are used.|1st mark, 2nd mark, 3rd mark, clearance, sale, doorbuster|||||||
|item_type|string|Captures the room type code associated with a lodging room booking.|1-K-NS, 2-Q-S, S-K-NS-City|||||||
|item_variant|string|The variant of the item.|Black|||||||
|listing_context|string|Captures the name or ID associated with each conference.|Filter Added, Filter Removed, Sort Change, Pagination|||||||
|listing_driver|string|Captures the version \( i.e. JS2.14, H.26, JS4.3.1.. etc.\) of the analytics library.|Onsite Search, Curated Assortment, Navigation|||||||
|location_id|string|The location associated with the event. If possible, set to the Google Place ID that corresponds to the associated item. Can also be overridden to a custom location ID string.|L\_12345|||||||
|location_name|string|Captures the number of events displayed in an event listing.|Deerefiled Outlet, Old Orchard, Manhatten Midtown|||||||
|number_of_ratings|integer|Count of times that visitors started completing forms.|1, 5, 11, 200||||0|||
|point_range_high|integer|Captures the date associated with an event.|5000, 2520, 3200|||||||
|point_range_low|integer|Count of times that visitors began the event booking process.|1000, 1510, 1800|||||||
|price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||
|price_range_high|string|Captures the type associated with each event.||^[0-9]*(\.[0-9]{1,2})?$||||||
|price_range_low|string|Captures the type \(i.e. Adult, Student, Infant, Senior, Family\) associated with a ticket.||^[0-9]*(\.[0-9]{1,2})?$||||||
|quantity|integer|Item quantity.|1|||||||
|rate_code|string|Captures the room rate code associated with a lodging room booking.|AAA, MILITARY, CORP-567, CORP-345|||||||
|sort_order|unknown|Captures the selected sort value at the time a product was found to see the impact on downstream success or conversion.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||
|units_available|integer|Captures the numeric position of each form field within a form \(i.e. 1, 2, 3\).|0, 10, 20, 23||||0|||




