# Registry Deleted

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "delete_wishlist",
  "apollo_event": "Registry Deleted",
    "ecommerce": {
        "gift_registry_deletions": "<gift_registry_deletions>",
        "identifier": "<identifier>",
        "type": "<type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|gift_registry_deletions|unknown|Count of gift registries removed.||||||||
|identifier|string|Captures the ID associated with a gift registry.|12345, 435678, 34567, XCV456, XCV876|||||||
|type|string|Captures the type associated with a gift registry \(i.e. wedding, baby\).|Wedding, Baby, Birth Day, Anniversary|||||||




