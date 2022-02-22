# Video Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "video_complete",
  "apollo_event": "Video Completed",
    "event_data": {
        "identifier": "<identifier>",
        "type": "<type>",
        "video_completions": "<video_completions>",
        "video_duration": <video_duration>,
        "video_provider": "<video_provider>",
        "video_title": "<video_title>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|identifier|string|Captures the ID of video content viewed by visitor.|YT456789, BC4567890, 876546789|||||||
|type|string|Captures the type of video viewed.||||||||
|video_completions|unknown|Count of video plays that reached 100% completion.||||||||
|video_duration|integer|Captures the length of the video viewed by the visitor.|36, 67, 178, 600||||0|||
|video_provider|string|Captures the video player used by the visitor for each video.|youTube, bright cove, JW Player, vimeo|||||||
|video_title|string|Captures the Name of video content viewed by visitor.|Twitch\_FPS, Age of Empires, Halo|||||||




