# Conference Registration Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "conference_registration_complete",
  "apollo_event": "Conference Registration Completed",
    "event_data": {
        "conference_registration_completed_counter": "<conference_registration_completed_counter>",
        "identifier": "<identifier>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|conference_registration_completed_counter|string|Amount of money associated with products reaching the checkout step of the shopping cart.||||||||
|identifier|string|Captures the name of the checkout step \(i.e. start, shipping, billing, review\).||||||||




