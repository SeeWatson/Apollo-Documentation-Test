# Exit Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "click",
  "apollo_event": "Exit Link Clicked",
    "event_data": {
        "component_ancestry": "<component_ancestry>",
        "identifier": "<identifier>",
        "link_url": "<link_url>",
        "outbound": "<outbound>",
        "region_ancestry": "<region_ancestry>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|component_ancestry|string|Count of times that event detail pages were viewed.|Best Friends - Best Jeans, Puppy Love, Sail Away, Mens, Kids, Kids : Tops|||||||
|identifier|string|Amount of money associated with an event booking at the time of booking start.|act now, cancel, ok, 3456, 8765|||||||
|link_url|string|Count of times that event detail options were selected|https:\/\/www.usda.gov. https:\/\/msnbc.com|||||||
|outbound|string|Count of times that each event detail option is displayed||||||||
|region_ancestry|string|Captures the total number of event detail options returned.|Top Nav, Footer Nav, Hero, Recommended, Also Shopped, Also Bought|||||||




