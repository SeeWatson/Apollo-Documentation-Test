# Product Category Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "select_item_category",
  "apollo_event": "Product Category Clicked",
    "ecommerce": {
        "product_category_clicks": "<product_category_clicks>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|product_category_clicks|unknown|Count of times the user clicked a product category.||||||||




