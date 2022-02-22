# Checkout Interaction Occurred

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "checkout_interaction",
  "apollo_event": "Checkout Interaction Occurred",
    "event_data": {
        "checkout_interactions": "<checkout_interactions>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|checkout_interactions|string|Count of times that a user was proactively shown online chat. This represents cases in which a user did not request chat, but was shown chat based upon business rules.||||||||
|type|string|Count of times that a user manually requested to view online chat.||||||||




