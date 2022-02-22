# Conference Registration Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "start_conference_registration",
  "apollo_event": "Conference Registration Started",
    "event_data": {
        "conference_registration_started_counter": "<conference_registration_started_counter>",
        "identifier": "<identifier>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|conference_registration_started_counter|string|The checkout method associated with checkout activity.||||||||
|identifier|string|Captures the name of the checkout step \(i.e. start, shipping, billing, review\).||||||||




