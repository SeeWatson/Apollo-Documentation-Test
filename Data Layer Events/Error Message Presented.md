# Error Message Presented

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "site_error",
  "apollo_event": "Error Message Presented",
    "event_data": {
        "error_counter": "<error_counter>",
        "error_message": "<error_message>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|error_counter|string|Captures the ID associated with download links used.||||||||
|error_message|string|Counts the number of files that visitors have downloaded since first visiting the website. Note that this is dependent on cookies and starts over for new cookies.|Credit Card Authorization Failed, EC345, Form is incomplete|||||||
|type|string|Count of times that visitors clicked on a file download link.|Payment, System, Form|||||||




