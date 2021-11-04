# Video Milestone Reached

### 

## Javascript Code
```js
window.dataLayer1104 = window.dataLayer1104 || [];
dataLayer1104.push({
  "event": "video_milestone_reached",
  "apollo_event": "Video Milestone Reached",
    "video_id": "<video_id>",
    "video_length": <video_length>,
    "video_milestone": "<video_milestone>",
    "video_milestones": "<video_milestones>",
    "video_name": "<video_name>",
    "video_player": "<video_player>",
    "video_type": "<video_type>"
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|video_id|string|Captures the ID of video content viewed by visitor.|YT456789, BC4567890, 876546789|||||||
|video_length|integer|Captures the length of the video viewed by the visitor.|36, 67, 178, 600||||0|||
|video_milestone|string|Captures the milestone \(25%, 50%, 75%\) reached when viewing a video.|25, 50, 77, 99|||||||
|video_milestones|unknown|Count of video milestones reached \(25%, 50%, 75%\).||||||||
|video_name|string|Captures the Name of video content viewed by visitor.|Twitch\_FPS, Age of Empires, Halo|||||||
|video_player|string|Captures the video player used by the visitor for each video.|youTube, bright cove, JW Player, vimeo|||||||
|video_type|string|Captures the type of video viewed.||||||||




