# Content Listing Displayed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "view_item_list",
  "apollo_event": "Content Listing Displayed",
    "ecommerce": {
        "count_content_listing_displayed": "<count_content_listing_displayed>",
        "default_sort_order": "<default_sort_order>",
        "item_list_id": "<item_list_id>",
        "item_list_name": "<item_list_name>",
        "items": [
            {
                "affiliation": "<affiliation>",
                "content_author": "<content_author>",
                "content_date": "<content_date>",
                "content_id": "<content_id>",
                "content_title": "<content_title>",
                "count_content_impressions": <count_content_impressions>,
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
                "item_variant": "<item_variant>",
                "location_id": "<location_id>",
                "number_of_items": <number_of_items>,
                "price": <price>,
                "quantity": <quantity>
            }
        ],
        "listing_context": "<listing_context>",
        "listing_driver": "<listing_driver>",
        "listing_sort_order_value_merchandising": "<listing_sort_order_value_merchandising>",
        "number_of_items_displayed": "<number_of_items_displayed>",
        "sort_order": "<sort_order>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|content_author|string|Captures the reason that a visitor submitted a Contact Us form.|Betsy Ross, Ben Franklin, Howard Hughes, Tipper Gore|||||||
|content_date|string|The sort value selected by default on listings.|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|content_id|string|Captures the optimization test IDs as concatenated list for active tests.||||||||
|content_title|string|Count of times when visitors began a contact request flow.|50 ways to use jello, Another look at pandas, Year end giving|||||||
|count_content_impressions|boolean|Count of times when visitors completed a contact request flow.|TRUE|||||||
|count_content_listing_displayed|string|Count of times that visitors completed registering for conferences.||||||||
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|default_sort_order|string|Captures the name of the page or screen the visitor was on directly prior to the current one.|A to Z, Low to High, Newest to Oldest||||0|||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
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
|item_variant|string|The variant of the item.|Black|||||||
|listing_context|string|Captures the name or ID associated with each conference.|Filter Added, Filter Removed, Sort Change, Pagination|||||||
|listing_driver|string|Captures the version \( i.e. JS2.14, H.26, JS4.3.1.. etc.\) of the analytics library.|Onsite Search, Curated Assortment, Navigation|||||||
|listing_sort_order_value_merchandising|string|Captures account information gathered from account-based marketing \(ABM\) tools in order to identify unauthenticated visitors based upon data from ABM tool.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||
|location_id|string|The location associated with the event. If possible, set to the Google Place ID that corresponds to the associated item. Can also be overridden to a custom location ID string.|L\_12345|||||||
|number_of_items|integer|Captures the current date \(UTC\).|1, 21, 111, 166||||0|||
|number_of_items_displayed|string|Count of times that visitors started registering for conferences.|10, 20, 30, 40||||0|||
|price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||
|quantity|integer|Item quantity.|1|||||||
|sort_order|unknown|Captures the selected sort value at the time a product was found to see the impact on downstream success or conversion.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||
|type|string|Captures the methods that bring users to listings \(i.e. Onsite Search, Top Nav, External Link, Category Landing Page\). Does not update if listings are sorted, filtered, or paginated.|Product, Location, Event, Room, Content|||||||




