# Report Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "view_report",
  "apollo_event": "Report Viewed",
    "ecommerce": {
        "identifier": "<identifier>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|identifier|unknown|Captures the name or ID of each report.||||||||
|type|string|Captures the type associated with each report.|Transactions, Financial|||||||




