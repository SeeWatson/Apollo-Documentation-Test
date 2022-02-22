# User Visit Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "custom_session_start",
  "apollo_event": "User Visit Started",
    "ecommerce": {
        "price": "<price>"
    },
    "event_data": {
        "persisted_cart_counter": <persisted_cart_counter>,
        "persisted_cart_value": "<persisted_cart_value>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|persisted_cart_counter|boolean|Count of times that visitors had products in a shopping cart at the time they signed-in.|TRUE, FALSE|||||||
|persisted_cart_value|string|Amount of money associated with persistent shopping carts at the time visitors signed-in.|125.05, 432.21, 90.22, 12.05|^[0-9]*(\.[0-9]{1,2})?$||||||
|price|string|Amount of money associated with products in persistent shopping carts at the time visitors began their visit.|200, 29.99, 50, 0|^[0-9]*(\.[0-9]{1,2})?$||||||




