# Order Confirmation Interaction Occurred

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "order_confirmation_interaction",
  "apollo_event": "Order Confirmation Interaction Occurred",
    "event_data": {
        "order_confirmation_interactions": <order_confirmation_interactions>,
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|order_confirmation_interactions|number|Captures the number of rooms available for each location in a location listing.||||||||
|type|string|Count of locations returned in location listings.||||||||




