# Fundraiser Registration Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "start_fundraiser_registration",
  "apollo_event": "Fundraiser Registration Started",
    "event_data": {
        "fundraiser_registration_started_counter": "<fundraiser_registration_started_counter>",
        "identifier": "<identifier>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|fundraiser_registration_started_counter|unknown|Count of times that an event in an event listing was clicked.||||||||
|identifier|string|Captures the longitude of each location.|FT-2019-Chicago, 19-45678, 2019-01-20\_0123|||||||




