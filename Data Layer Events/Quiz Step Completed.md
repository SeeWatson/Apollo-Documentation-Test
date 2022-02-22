# Quiz Step Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "survey_step_complete",
  "apollo_event": "Quiz Step Completed",
    "event_data": {
        "name": "<name>",
        "quiz_step_completes": "<quiz_step_completes>",
        "step_name": "<step_name>",
        "step_number": <step_number>,
        "step_value": "<step_value>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|name|string|Captures the human-friendly quiz name.|Floor Chooser, Swim Finder, Movie Decider, My Next Book|||||||
|quiz_step_completes|unknown|Count of times that visitors completed quiz steps.||||||||
|step_name|string|Captures the name of the quiz step.|Indoor \/ Outdoor, Durability, Mood|||||||
|step_number|integer|Captures the number or sequence of quiz steps.|1, 2, 3, 4||||1|||
|step_value|string|Captures the visitor entry at the time of quiz step completion.|Hardwood, High Traffic, Happy, Fiction|||||||




