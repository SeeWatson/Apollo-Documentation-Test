# Wallet Item Added

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "add_to_wallet",
  "apollo_event": "Wallet Item Added",
    "event_data": {
        "wallet_item_adds": "<wallet_item_adds>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|wallet_item_adds|unknown|Count of times the user added itmes \(e.g., gift cards, discount codes, payment credentials\) to their wallet.||||||||




