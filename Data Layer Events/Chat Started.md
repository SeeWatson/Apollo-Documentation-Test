# Chat Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "start_chat",
  "apollo_event": "Chat Started",
    "event_data": {
        "chat_started_counter": "<chat_started_counter>",
        "identifier": "<identifier>",
        "method": "<method>",
        "service_line": "<service_line>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|chat_started_counter|unknown|Count of times that a user requested a physical product catalog.||||||||
|identifier|string|Count of times that visitors encountered a product that was back-ordered.||||||||
|method|string|Count of times the price of a product was hidden in the cart due to MAP \(Minimum Advertised Pricing\) requirements.
  Set in the product string for only those products where it is applicable, with a value of 1||||||||
|service_line|string|Count of times a product was out of stock at the time of cart view.||||||||




