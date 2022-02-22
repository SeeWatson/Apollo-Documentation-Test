# Tool Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "tool_complete",
  "apollo_event": "Tool Completed",
    "ecommerce": {
        "items": [
            {
                "item_finding_method": "<item_finding_method>"
            }
        ]
    },
    "event_data": {
        "identifier": "<identifier>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|identifier|string|Captures the name or ID of the website or mobile app tools \(i.e. mortgage calculator\) used by visitors.|Mortgage Calculator|||||||
|item_finding_method|string|Captures the name or ID of the container within which exit links are used.||||||||




