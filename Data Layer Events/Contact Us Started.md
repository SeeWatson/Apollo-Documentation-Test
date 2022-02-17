# Contact Us Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "start_contact_us",
  "apollo_event": "Contact Us Started",
    "event_data": {
        "contact_us_started_counter": "<contact_us_started_counter>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|contact_us_started_counter|string|Numeric value that displays the total percent of the page that was viewed. This must be used with the Previous Page Name variable since percent viewed is not known until the following page.||||||||




