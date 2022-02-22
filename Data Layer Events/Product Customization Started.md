# Product Customization Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "start_item_customization",
  "apollo_event": "Product Customization Started",
    "ecommerce": {
        "product_customization_starts": "<product_customization_starts>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|product_customization_starts|string|Count of times visitors started the product customization process.||||||||
|type|string|Captures the type of customations visitors made to products.|Monogram, Cold Weather Package, Team Logo|||||||




