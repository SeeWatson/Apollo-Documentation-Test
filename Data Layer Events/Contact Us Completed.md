# Contact Us Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "contact_us_complete",
  "apollo_event": "Contact Us Completed",
    "event_data": {
        "contact_purpose": "<contact_purpose>",
        "contact_us_completed_counter": "<contact_us_completed_counter>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|contact_purpose|string|Captures the unique ID associated with session replays. Typically set by a 3rd party session replay vendor.|General Inquiry, Order Status, Legal, Other|||||||
|contact_us_completed_counter|string|Total engagement points earned based upon a pre-defined engagement scoring system \(i.e. cart add = 25 points\).||||||||




