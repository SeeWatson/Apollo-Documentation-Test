# Product Interaction Occurred

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "product_interaction",
  "apollo_event": "Product Interaction Occurred",
    "ecommerce": {
        "interaction_detail": "<interaction_detail>",
        "product_interactions": "<product_interactions>",
        "visualization": "<visualization>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|interaction_detail|string|Captures the interaction detail for an interaction that was performed with a product.|Added to Favorites, Removed from Favorites, Front View, Side View|||||||
|product_interactions|string|Count of time that visitors performed an interaction with a product.||||||||
|visualization|string|Captures the scene for which a product is being displayed.|Kitchen, Great Room, Bathroom, Bedroom, Custom|||||||




