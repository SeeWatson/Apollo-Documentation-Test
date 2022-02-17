# Form Field Engaged

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "form_field_interaction",
  "apollo_event": "Form Field Engaged",
    "event_data": {
        "count_form_field_engagements": "<count_form_field_engagements>",
        "form_field_id": "<form_field_id>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|count_form_field_engagements|string|Details filters used to refine a listing||||||||
|form_field_id|string|Captures the upper end of a point range for an offering||||||||




