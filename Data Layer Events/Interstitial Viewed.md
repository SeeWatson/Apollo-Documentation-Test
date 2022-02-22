# Interstitial Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "view_interstitial",
  "apollo_event": "Interstitial Viewed",
    "event_data": {
        "interstitial_views": "<interstitial_views>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|interstitial_views|unknown|Captures the last form field ID the user interacted with prior to abandoning a form.||||||||
|type|string|Count of times that visitors canceled website forms.|alert, offer, info required|||||||




