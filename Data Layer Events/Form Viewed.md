# Form Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "view_form",
  "apollo_event": "Form Viewed",
    "ecommerce": {
        "items": [
            {
                "location_id": "<location_id>",
                "location_name": "<location_name>"
            }
        ]
    },
    "event_data": {
        "form_field_id": "<form_field_id>",
        "form_field_position": "<form_field_position>",
        "form_field_section": "<form_field_section>",
        "identifier": "<identifier>",
        "name": "<name>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|form_field_id|string|Captures the upper end of a point range for an offering||||||||
|form_field_position|string|Captures the position of each event in an event listing.|1, 2, 3, 4, 5||||1|||
|form_field_section|string|Captures the number of filters applied to a listing.|address1, address2, cc info, terms acceptance|||||||
|identifier|string|Captures the point-to-point distance from map POI \(point-of-interest\).|F-0113, 2543, CU001, PI-0988|||||||
|location_id|string|Captures a unique ID of a physical location such as a store, banking branch, atm, hotel, office, or other.|155, 65588, 987764448|||||||
|location_name|string|Captures the number of events displayed in an event listing.|Deerefiled Outlet, Old Orchard, Manhatten Midtown|||||||
|name|string|Captures the upper end of a price range for an offering|Payment Info, Mailing Address, Payment Address, Contact Us|||||||
|type|string|Captures the currency code of a specific item in a listing.|Address, Contact, Comment, Review, Payment|||||||




