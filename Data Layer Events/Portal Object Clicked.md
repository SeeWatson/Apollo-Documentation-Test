# Portal Object Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "select_component",
  "apollo_event": "Portal Object Clicked",
    "event_data": {
        "identifier": "<identifier>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|identifier|string|Captures the name or ID of portal \(intranet\) objects. Objects are typically tiles or boxes.|My Accounts, Transactions, Messages, My Reports|||||||




