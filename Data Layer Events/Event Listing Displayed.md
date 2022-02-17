# Event Listing Displayed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "view_item_list",
  "apollo_event": "Event Listing Displayed",
    "ecommerce": {
        "currency": "<currency>",
        "default_sort_order": "<default_sort_order>",
        "facets": "<facets>",
        "item_list_id": "<item_list_id>",
        "item_list_name": "<item_list_name>",
        "items": [
            {
                "affiliation": "<affiliation>",
                "count_event_impressions": <count_event_impressions>,
                "coupon": "<coupon>",
                "currency": "<currency>",
                "discount": <discount>,
                "distance_from_poi": <distance_from_poi>,
                "event_id": "<event_id>",
                "event_name": "<event_name>",
                "event_status": "<event_status>",
                "index": "<index>",
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
                "item_type": "<item_type>",
                "item_variant": "<item_variant>",
                "latitude": <latitude>,
                "location_id": "<location_id>",
                "point_range_high": <point_range_high>,
                "point_range_low": <point_range_low>,
                "price": <price>,
                "price_range_high": "<price_range_high>",
                "price_range_low": "<price_range_low>",
                "quantity": <quantity>
            }
        ],
        "listing_context": "<listing_context>",
        "listing_driver": "<listing_driver>",
        "listing_filter_count": <listing_filter_count>,
        "listing_sort_order_value_merchandising": "<listing_sort_order_value_merchandising>",
        "number_of_items": "<number_of_items>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|count_event_impressions|boolean|Captures the number of tickets associated with an event|TRUE|||||||
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|currency|string|Number of tickets associates with an event booking at the time of booking completion.|USD, CAD, GBP, CHF|^[A-Z]{3}$|3|3||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|default_sort_order|string|Captures the name of the page or screen the visitor was on directly prior to the current one.|A to Z, Low to High, Newest to Oldest||||0|||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|distance_from_poi|integer|Captures the per person price. May vary by ticket type.|12, 3, 5, 200|||||||
|event_id|string|Captures the type of file that was downloaded \(i.e. PDF, EPUB, DMG\).|155, 65588, 987764448|||||||
|event_name|string|Captures the name or ID of the container within which download links are used.|Max your 401K, Structured JavaScript, Mid Day Yoga, Frosty 5K Fun Run, Whiskey Wednesday|||||||
|event_status|string|Captures the human-friendly name associated with each event.|Cancelled, Sold Out, Postponed, Rescheduled|||||||
|facets|string|Number of points associated with an event booking at the time of booking completion.|sort\~price ascending\|color\~green\|size\~medium|||||||
|index|string|Amount of money associated with an event booking at the time of booking completion.|1, 2, 3, 4, 5||||0|||
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
|item_type|string|Count of deliveries of email messages.|Webinar, Class, Conference, Race, Meet Up|||||||
|item_variant|string|The variant of the item.|Black|||||||
|latitude|number|Captures the per person point needed in exchange for a ticket. May variy by ticket type.|-90, 90, 48.858093|||||||
|listing_context|string|Captures the name or ID associated with each conference.|Filter Added, Filter Removed, Sort Change, Pagination|||||||
|listing_driver|string|Captures the version \( i.e. JS2.14, H.26, JS4.3.1.. etc.\) of the analytics library.|Onsite Search, Curated Assortment, Navigation|||||||
|listing_filter_count|integer|Captures the time associated with an event.|0, 20, 12||||0|||
|listing_sort_order_value_merchandising|string|Captures account information gathered from account-based marketing \(ABM\) tools in order to identify unauthenticated visitors based upon data from ABM tool.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||
|location_id|string|Captures a unique ID of a physical location such as a store, banking branch, atm, hotel, office, or other.|155, 65588, 987764448|||||||
|number_of_items|unknown|Captures a unique ID associated with each event.|1, 21, 111, 166||||0|||
|point_range_high|integer|Captures the date associated with an event.|5000, 2520, 3200|||||||
|point_range_low|integer|Count of times that visitors began the event booking process.|1000, 1510, 1800|||||||
|price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||
|price_range_high|string|Captures the type associated with each event.||^[0-9]*(\.[0-9]{1,2})?$||||||
|price_range_low|string|Captures the type \(i.e. Adult, Student, Infant, Senior, Family\) associated with a ticket.||^[0-9]*(\.[0-9]{1,2})?$||||||
|quantity|integer|Item quantity.|1|||||||
|type|string|Captures the methods that bring users to listings \(i.e. Onsite Search, Top Nav, External Link, Category Landing Page\). Does not update if listings are sorted, filtered, or paginated.|Product, Location, Event, Room, Content|||||||




