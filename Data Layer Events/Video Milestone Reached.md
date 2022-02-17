# Video Milestone Reached

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "video_progress",
  "apollo_event": "Video Milestone Reached",
    "event_data": {
        "identifier": "<identifier>",
        "type": "<type>",
        "video_duration": <video_duration>,
        "video_milestones_reached": "<video_milestones_reached>",
        "video_percent": "<video_percent>",
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
|video_duration|integer|Captures the length of the video viewed by the visitor.|36, 67, 178, 600||||0|||
|video_milestones_reached|unknown|Count of video milestones reached \(25%, 50%, 75%\).||||||||
|video_percent|string|Captures the milestone \(25%, 50%, 75%\) reached when viewing a video.|25, 50, 77, 99|||||||
|video_provider|string|Captures the video player used by the visitor for each video.|youTube, bright cove, JW Player, vimeo|||||||
|video_title|string|Captures the Name of video content viewed by visitor.|Twitch\_FPS, Age of Empires, Halo|||||||




