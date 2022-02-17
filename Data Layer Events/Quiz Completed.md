# Quiz Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "survey_complete",
  "apollo_event": "Quiz Completed",
    "ecommerce": {
        "items": [
            {
                "item_finding_method": "<item_finding_method>"
            }
        ]
    },
    "event_data": {
        "name": "<name>",
        "quiz_completes": "<quiz_completes>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|item_finding_method|string|Captures the ID associated with exit links used.||||||||
|name|string|Captures the human-friendly quiz name.|Floor Chooser, Swim Finder, Movie Decider, My Next Book|||||||
|quiz_completes|unknown|Count of times that visitors completed quizzes.||||||||




