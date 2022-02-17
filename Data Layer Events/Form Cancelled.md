# Form Cancelled

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "cancel_form",
  "apollo_event": "Form Cancelled",
    "event_data": {
        "identifier": "<identifier>",
        "name": "<name>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|identifier|string|Captures the point-to-point distance from map POI \(point-of-interest\).|F-0113, 2543, CU001, PI-0988|||||||
|name|string|Captures the upper end of a price range for an offering|Payment Info, Mailing Address, Payment Address, Contact Us|||||||
|type|string|Captures the currency code of a specific item in a listing.|Address, Contact, Comment, Review, Payment|||||||




