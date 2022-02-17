# Social Brand Followed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "subscribe",
  "apollo_event": "Social Brand Followed",
    "event_data": {
        "method": "<method>",
        "social_brand_shared_event": "<social_brand_shared_event>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|method|string|Captures the name of the social network associated with social network activity \(i.e. follow, share\).|facebook, linkedIn, instrgram, twitter|||||||
|social_brand_shared_event|string|Count of times that visitors clicked to follow brands on social networks.||||||||




