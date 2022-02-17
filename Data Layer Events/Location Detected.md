# Location Detected

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "location_detected",
  "apollo_event": "Location Detected",
    "ecommerce": {
        "items": [
            {
                "item_type": "<item_type>",
                "location_id": "<location_id>",
                "location_name": "<location_name>"
            }
        ]
    },
    "event_data": {
        "determination_method": "<determination_method>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|determination_method|string|Captures the human-friendly name of the form.|Automatic - IP based, Automatic - Device Based, Customer Selected|||||||
|item_type|string|Captures the unique ID of the form.|Retail Store, Lodging, ATM, Banking Branch|||||||
|location_id|string|Captures a unique ID of a physical location such as a store, banking branch, atm, hotel, office, or other.|155, 65588, 987764448|||||||
|location_name|string|Captures the number of events displayed in an event listing.|Deerefiled Outlet, Old Orchard, Manhatten Midtown|||||||




