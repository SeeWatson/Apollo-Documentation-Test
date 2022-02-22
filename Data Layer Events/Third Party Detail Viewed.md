# Third Party Detail Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "view_third_party_detail",
  "apollo_event": "Third Party Detail Viewed",
    "event_data": {
        "third_party_detail_views": "<third_party_detail_views>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|third_party_detail_views|string|Count of times a user clicked to view details about a third party \(e.g., marketplace vendors\).||||||||




