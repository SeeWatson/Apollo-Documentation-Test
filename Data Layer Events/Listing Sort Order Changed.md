# Listing Sort Order Changed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "sort_list",
  "apollo_event": "Listing Sort Order Changed",
    "ecommerce": {
        "facets": "<facets>",
        "listing_sort_order_value_merchandising": "<listing_sort_order_value_merchandising>",
        "sort_order": "<sort_order>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|facets|string|Number of points associated with an event booking at the time of booking completion.|sort\~price ascending\|color\~green\|size\~medium|||||||
|listing_sort_order_value_merchandising|string|Captures account information gathered from account-based marketing \(ABM\) tools in order to identify unauthenticated visitors based upon data from ABM tool.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||
|sort_order|unknown|Captures the selected sort value at the time a product was found to see the impact on downstream success or conversion.|high-low, low-high, nearest-farthest, a-z, newest-oldest|||||||
|type|string|Captures the methods that bring users to listings \(i.e. Onsite Search, Top Nav, External Link, Category Landing Page\). Does not update if listings are sorted, filtered, or paginated.|Product, Location, Event, Room, Content|||||||




