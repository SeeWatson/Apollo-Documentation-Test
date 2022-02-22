# Event Detail Options Displayed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "view_item_list",
  "apollo_event": "Event Detail Options Displayed",
    "ecommerce": {
        "items": [
            {
                "count_option_displayed": <count_option_displayed>,
                "event_id": "<event_id>",
                "event_name": "<event_name>",
                "item_type": "<item_type>",
                "item_variant": "<item_variant>",
                "price": "<price>",
                "quantity": "<quantity>",
                "start_date": "<start_date>",
                "start_time": "<start_time>",
                "ticket_points": <ticket_points>
            }
        ],
        "number_of_options": <number_of_options>
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|count_option_displayed|boolean|Captures the type of error.|TRUE|||||||
|event_id|string|Captures the type of file that was downloaded \(i.e. PDF, EPUB, DMG\).|155, 65588, 987764448|||||||
|event_name|string|Captures the name or ID of the container within which download links are used.|Max your 401K, Structured JavaScript, Mid Day Yoga, Frosty 5K Fun Run, Whiskey Wednesday|||||||
|item_type|string|Count of deliveries of email messages.|Webinar, Class, Conference, Race, Meet Up|||||||
|item_variant|string|Captures the specific error ID or description associated with errors.|Adult, Family, Student, Senior, All Access, General Admission|||||||
|number_of_options|integer|Count of times that visitors encountered website errors.|1, 3, 5|||||||
|price|string|Captures the file name associated with file downloads.|200, 29.99, 50, 0|^[0-9]*(\.[0-9]{1,2})?$||||||
|quantity|unknown|Count of email message sends.|1, 2, 3, 4, 5||||1|||
|start_date|string|Count of email message opens.|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|start_time|string|Count of clicks on email messages.|10:30, 14:45, 23:59, 7:00|^[0-2][0-9]:[0-5][0-9]||||||
|ticket_points|integer|Captures the name or ID of the region within which download links are used.|5000, 2520, 3200|||||||




