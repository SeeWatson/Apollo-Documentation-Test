# Social Content Shared

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "share",
  "apollo_event": "Social Content Shared",
    "event_data": {
        "identifier": "<identifier>",
        "method": "<method>",
        "social_content_shared_event": "<social_content_shared_event>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|identifier|string|Captures the unique ID of content items \(i.e. article or blog post\).||||||||
|method|string|Captures the name of the social network associated with social network activity \(i.e. follow, share\).|facebook, linkedIn, instrgram, twitter|||||||
|social_content_shared_event|string|Count of times that visitors shared content on social networks.||||||||




