# Save List Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "view_wishlist",
  "apollo_event": "Save List Viewed",
    "event_data": {
        "save_list_views": "<save_list_views>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|save_list_views|unknown|Count of times users received an impression of one or more products in the "save for later" list.||||||||




