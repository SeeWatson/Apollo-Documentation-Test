# Two-Factor Authentication Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "two_factor_authentication_complete",
  "apollo_event": "Two-Factor Authentication Completed",
    "event_data": {
        "two_factor_authentication_completed": "<two_factor_authentication_completed>"
    },
    "user_data": {
        "user_id": "<user_id>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|two_factor_authentication_completed|string|Count of times that visitors completed the 2FA verification process \(i.e. entered code\).||||||||
|user_id|string|The id of the user currently logged in to the site, if the site offers authentication and the user is authenticated.|123456, abc123|||||||




