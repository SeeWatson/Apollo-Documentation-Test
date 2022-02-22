# Product Collection Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "view_item_list",
  "apollo_event": "Product Collection Viewed",
    "ecommerce": {
        "identifier": "<identifier>",
        "product_collection_views": "<product_collection_views>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|identifier|string|Captures the product collection viewed to see the impact on downstream success or conversion.|Back to School, New Grad, Gifts for Her|||||||
|product_collection_views|unknown|Count of times visitors view product collections.||||||||




