# CTA Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "click",
  "apollo_event": "CTA Link Clicked",
    "event_data": {
        "category": "<category>",
        "component_ancestry": "<component_ancestry>",
        "identifier": "<identifier>",
        "region_ancestry": "<region_ancestry>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|category|string|Count of revenue taking place offline from internal databases for use in comparing to online revenue.||||||||
|component_ancestry|string|Total monetary amount associated witheach night of a room booking.|Best Friends - Best Jeans, Puppy Love, Sail Away, Mens, Kids, Kids : Tops|||||||
|identifier|string|Count of times that visitors began the room booking process.|act now, cancel, ok, 3456, 8765|||||||
|region_ancestry|string|Count of units taking place offline from internal databases for use in comparing to online units.|Top Nav, Footer Nav, Hero, Recommended, Also Shopped, Also Bought|||||||




