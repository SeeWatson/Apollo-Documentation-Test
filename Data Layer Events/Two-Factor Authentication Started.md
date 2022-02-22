# Two-Factor Authentication Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "start_two_factor_authentication",
  "apollo_event": "Two-Factor Authentication Started",
    "event_data": {
        "two_factor_authentication_started": "<two_factor_authentication_started>"
    },
    "user_data": {
        "user_id": "<user_id>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|two_factor_authentication_started|string|Count of times that visitors initiated the 2FA process \(i.e. change password\).||||||||
|user_id|string|The id of the user currently logged in to the site, if the site offers authentication and the user is authenticated.|123456, abc123|||||||




