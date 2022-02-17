# Social Product Shared

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "share",
  "apollo_event": "Social Product Shared",
    "event_data": {
        "method": "<method>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|method|string|Captures the name of the social network associated with social network activity \(i.e. follow, share\).|facebook, linkedIn, instrgram, twitter|||||||




