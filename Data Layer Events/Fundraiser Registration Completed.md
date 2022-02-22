# Fundraiser Registration Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "fundraiser_registration_complete",
  "apollo_event": "Fundraiser Registration Completed",
    "event_data": {
        "count_fundraiser_registration_completed": "<count_fundraiser_registration_completed>",
        "identifier": "<identifier>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|count_fundraiser_registration_completed|unknown|Captures the lower end of a point range for an offering||||||||
|identifier|string|Captures the longitude of each location.|FT-2019-Chicago, 19-45678, 2019-01-20\_0123|||||||




