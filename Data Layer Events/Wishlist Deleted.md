# Wishlist Deleted

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "delete_wishlist",
  "apollo_event": "Wishlist Deleted",
    "ecommerce": {
        "identifier": "<identifier>"
    },
    "event_data": {
        "wishlist_deletions": "<wishlist_deletions>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|identifier|string|Captures a unique identifier for each wishlist|12345, 435678, 34567, XCV456, XCV876|||||||
|wishlist_deletions|unknown|Count of times that visitors deleted wishlists.||||||||




