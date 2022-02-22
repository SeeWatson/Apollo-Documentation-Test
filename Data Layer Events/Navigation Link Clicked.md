# Navigation Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "click",
  "apollo_event": "Navigation Link Clicked",
    "event_data": {
        "component_ancestry": "<component_ancestry>",
        "identifier": "<identifier>",
        "link_url": "<link_url>",
        "nav_link_click_event": "<nav_link_click_event>",
        "navigation_link_id_merchandising": "<navigation_link_id_merchandising>",
        "region_ancestry": "<region_ancestry>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|component_ancestry|string|Count of times that visitors successfully completed forms.|Best Friends - Best Jeans, Puppy Love, Sail Away, Mens, Kids, Kids : Tops|||||||
|identifier|string|Captures the name or ID associated with each fundraiser.|act now, cancel, ok, 3456, 8765|||||||
|link_url|string|Count of times that visitors started registering for fundraisers.|https:\/\/www.example.com|||||||
|nav_link_click_event|string|Count of times that visitors were presented with a form.||||||||
|navigation_link_id_merchandising|string|Count of times that visitors completed registering for fundraisers.|act now, cancel, ok, 3456, 8765|||||||
|region_ancestry|string|Count of times a user applied a gift card to an order that was already in the wallet.|Top Nav, Footer Nav, Hero, Recommended, Also Shopped, Also Bought|||||||




