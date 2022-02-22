# Chat Shown

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "view_chat",
  "apollo_event": "Chat Shown",
    "event_data": {
        "proactive": <proactive>,
        "reactive": <reactive>
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|proactive|boolean|Count of time the user earned a cart promotion \(e.g., smart shopping cart\).|TRUE, FALSE|||||||
|reactive|boolean|Count of time a cart promotion \(e.g., smart shopping cart\) is displayed to the user.|TRUE, FALSE|||||||




