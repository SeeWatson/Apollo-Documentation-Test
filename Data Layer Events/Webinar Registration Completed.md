# Webinar Registration Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "webinar_registration_complete",
  "apollo_event": "Webinar Registration Completed",
    "event_data": {
        "identifier": "<identifier>",
        "webinar_registration_completed_counter": "<webinar_registration_completed_counter>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|identifier|string|Captures the name or ID associated with each webinar.|TK-7869, GH-98657|||||||
|webinar_registration_completed_counter|unknown|Count of times that visitors completed registering for webinars.||||||||




