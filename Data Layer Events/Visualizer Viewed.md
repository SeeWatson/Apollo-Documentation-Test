# Visualizer Viewed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "view_visualizer",
  "apollo_event": "Visualizer Viewed",
    "event_data": {
        "visualizer_views": "<visualizer_views>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|visualizer_views|unknown|Count of time visitors viewed a product visualizers or configurators.||||||||




