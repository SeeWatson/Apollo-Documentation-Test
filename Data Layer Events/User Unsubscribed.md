# User Unsubscribed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "unsubscribe",
  "apollo_event": "User Unsubscribed",
    "event_data": {
        "method": "<method>",
        "type": "<type>"
    },
    "user_data": {
        "user_attributes": "<user_attributes>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|method|string|The platform used to share content|email, facebook, twitter|||||||
|type|string|Captures the type of subscription \(i.e. email newsletter, SMS text\).|news, updates, sales, events|||||||
|user_attributes|string|Attributes of the application user|homeStore\~234\|loyaltyTier\~gold\|memberSince\~2002|||||||




