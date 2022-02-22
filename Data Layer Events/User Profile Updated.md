# User Profile Updated

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "update_profile",
  "apollo_event": "User Profile Updated",
    "event_data": {
        "type": "<type>",
        "user_profile_updates": "<user_profile_updates>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|type|string|Captures the type of profile update \(i.e. change email\) completed by the user.|email, address, phone, subscriptions|||||||
|user_profile_updates|string|Count of times that authenticated visitors updated something associated with their online profile.||||||||




