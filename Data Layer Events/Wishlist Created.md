# Wishlist Created

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "create_wishlist",
  "apollo_event": "Wishlist Created",
    "ecommerce": {
        "identifier": "<identifier>",
        "wishlist_creations": "<wishlist_creations>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|identifier|string|Captures a unique identifier for each wishlist|12345, 435678, 34567, XCV456, XCV876|||||||
|wishlist_creations|unknown|Count of times that visitors created new wishlists.||||||||




