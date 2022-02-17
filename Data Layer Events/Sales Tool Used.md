# Sales Tool Used

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "sales_tool_interaction",
  "apollo_event": "Sales Tool Used",
    "ecommerce": {
        "items": [
            {
                "item_finding_method": "<item_finding_method>"
            }
        ]
    },
    "event_data": {
        "identifier": "<identifier>",
        "sales_tool_used_counter": "<sales_tool_used_counter>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|identifier|unknown|Captures the sales tool used.|Swim Finder, Accessory Genie, Search, My Gold Box|||||||
|item_finding_method|string|Captures the ID associated with exit links used.||||||||
|sales_tool_used_counter|unknown|Count of times that visitors engaged with a sales tool \(i.e. product video\).||||||||




