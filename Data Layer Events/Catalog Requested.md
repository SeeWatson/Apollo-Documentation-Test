# Catalog Requested

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "request_catalog",
  "apollo_event": "Catalog Requested",
    "event_data": {
        "catalog_requests": "<catalog_requests>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|catalog_requests|string|Count of time the user clicked to accept a cart promotion \(e.g., smart shopping cart\).||||||||




