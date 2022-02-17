# Report Listing Item Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "select_item",
  "apollo_event": "Report Listing Item Clicked",
    "ecommerce": {
        "facets": "<facets>",
        "identifier": "<identifier>",
        "items": [
            {
                "index": <index>
            }
        ],
        "listing_context": "<listing_context>",
        "listing_driver": "<listing_driver>",
        "sort_order": "<sort_order>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|facets|string|Number of points associated with an event booking at the time of booking completion.|sort\~price ascending\|color\~green\|size\~medium|||||||
|identifier|unknown|Captures the name or ID of each report.||||||||
|index|integer|Captures the position of each report in a report listing.|1, 2, 3, 4, 5||||0|||
|listing_context|string|Captures the name or ID associated with each conference.|Filter Added, Filter Removed, Sort Change, Pagination|||||||
|listing_driver|string|Captures the version \( i.e. JS2.14, H.26, JS4.3.1.. etc.\) of the analytics library.|Onsite Search, Curated Assortment, Navigation|||||||
|sort_order|unknown|Captures the selected sort value at the time a product was found to see the impact on downstream success or conversion.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||
|type|string|Captures the type associated with each report.|Transactions, Financial|||||||




