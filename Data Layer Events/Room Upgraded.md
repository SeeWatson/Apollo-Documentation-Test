# Room Upgraded

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "upgrade_room",
  "apollo_event": "Room Upgraded",
    "event_data": {
        "room_booking_upgrade_initiated": "<room_booking_upgrade_initiated>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|room_booking_upgrade_initiated|string|Count of times when visitors began the process of upgrading a room booking.||||||||




