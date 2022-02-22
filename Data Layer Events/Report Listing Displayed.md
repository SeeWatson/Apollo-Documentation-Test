# Report Listing Displayed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "view_item_list",
  "apollo_event": "Report Listing Displayed",
    "ecommerce": {
        "default_sort_order": "<default_sort_order>",
        "facets": "<facets>",
        "identifier": "<identifier>",
        "items": [
            {
                "count_report_impressions": <count_report_impressions>,
                "index": <index>
            }
        ],
        "listing_context": "<listing_context>",
        "listing_driver": "<listing_driver>",
        "listing_filter_count": <listing_filter_count>,
        "listing_sort_order_value_merchandising": "<listing_sort_order_value_merchandising>",
        "number_of_items": <number_of_items>,
        "number_of_items_displayed": <number_of_items_displayed>,
        "sort_order": "<sort_order>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|count_report_impressions|boolean|Count of reports displayed in report listings.|TRUE|||||||
|default_sort_order|string|Captures the name of the page or screen the visitor was on directly prior to the current one.|A to Z, Low to High, Newest to Oldest||||0|||
|facets|string|Number of points associated with an event booking at the time of booking completion.|sort\~price ascending\|color\~green\|size\~medium|||||||
|identifier|unknown|Captures the name or ID of each report.||||||||
|index|integer|Captures the position of each report in a report listing.|1, 2, 3, 4, 5||||0|||
|listing_context|string|Captures the name or ID associated with each conference.|Filter Added, Filter Removed, Sort Change, Pagination|||||||
|listing_driver|string|Captures the version \( i.e. JS2.14, H.26, JS4.3.1.. etc.\) of the analytics library.|Onsite Search, Curated Assortment, Navigation|||||||
|listing_filter_count|integer|Captures the time associated with an event.|0, 20, 12||||0|||
|listing_sort_order_value_merchandising|string|Captures account information gathered from account-based marketing \(ABM\) tools in order to identify unauthenticated visitors based upon data from ABM tool.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||
|number_of_items|integer|Product ID' portion of the Adobe Analytics products variable.  It populates the 'Product' report in AA.|1, 21, 111, 166||||0|||
|number_of_items_displayed|integer|Captures the number of reports displayed in a report listing.|10, 20, 30, 40||||0|||
|sort_order|unknown|Captures the selected sort value at the time a product was found to see the impact on downstream success or conversion.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||
|type|string|Captures the methods that bring users to listings \(i.e. Onsite Search, Top Nav, External Link, Category Landing Page\). Does not update if listings are sorted, filtered, or paginated.|Product, Location, Event, Room, Content|||||||




