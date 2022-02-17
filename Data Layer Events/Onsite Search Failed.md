# Onsite Search Failed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "view_search_results",
  "apollo_event": "Onsite Search Failed",
    "event_data": {
        "search_term": "<search_term>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|search_term|string|Captures the website method \(i.e. search, top nav\) used to find each product.|bluth, blue, red lobster|||||||
|type|string|Captures the website method \(i.e. search, top nav\) used to find each product at the time of cart addition|products, properties, articles, authors, coupons, publications|||||||




