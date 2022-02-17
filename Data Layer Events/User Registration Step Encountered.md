# User Registration Step Encountered

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "view_registration_step",
  "apollo_event": "User Registration Step Encountered",
    "event_data": {
        "step_name": "<step_name>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|step_name|string|Captures the name \/ id of each user registration step encountered.||||||||




