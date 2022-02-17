# Donation Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "begin_checkout",
  "apollo_event": "Donation Started",
    "ecommerce": {
        "donation_started_counter": "<donation_started_counter>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|donation_started_counter|unknown|Captures the type of card requested with a donation \(i.e. email, physical, e-card1, e-card2\).||||||||
|type|string|Count of times that visitors successfully entered discount codes.|Tribute, General, Fundraiser|||||||




