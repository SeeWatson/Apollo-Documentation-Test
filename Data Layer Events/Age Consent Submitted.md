# Age Consent Submitted

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "age_consent_complete",
  "apollo_event": "Age Consent Submitted",
    "event_data": {
        "age_consent_submitted": "<age_consent_submitted>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|age_consent_submitted|string|The total monetary amount associated with each payment method.||||||||




