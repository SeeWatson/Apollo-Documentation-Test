# Gift Card Applied From Wallet

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "apply_gift_card",
  "apollo_event": "Gift Card Applied From Wallet",
    "event_data": {
        "gift_card_applications_from_wallet": "<gift_card_applications_from_wallet>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|gift_card_applications_from_wallet|string|Position of the event clicked within an event listing view.||||||||




