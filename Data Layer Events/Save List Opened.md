# Save List Opened

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "select_wishlist",
  "apollo_event": "Save List Opened",
    "event_data": {
        "save_list_opens": "<save_list_opens>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|save_list_opens|unknown|Count of times users clicked to open the Save for Later list.||||||||




