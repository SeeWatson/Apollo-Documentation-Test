# Registry Created

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "create_wishlist",
  "apollo_event": "Registry Created",
    "ecommerce": {
        "gift_registry_creations": "<gift_registry_creations>",
        "identifier": "<identifier>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|gift_registry_creations|unknown|Count of gift registries created.||||||||
|identifier|string|Captures the ID associated with a gift registry.|12345, 435678, 34567, XCV456, XCV876|||||||
|type|string|Captures the type associated with a gift registry \(i.e. wedding, baby\).|Wedding, Baby, Birth Day, Anniversary|||||||




