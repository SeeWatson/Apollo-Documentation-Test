# Download Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "click",
  "apollo_event": "Download Link Clicked",
    "event_data": {
        "component_ancestry": "<component_ancestry>",
        "downloaded_file_count_lifetime": "<downloaded_file_count_lifetime>",
        "downloaded_file_count_visit": "<downloaded_file_count_visit>",
        "file_download": "<file_download>",
        "file_extension": "<file_extension>",
        "file_name": "<file_name>",
        "identifier": "<identifier>",
        "region_ancestry": "<region_ancestry>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|component_ancestry|string|Captures the state or province associated with payments used for a transaction \(i.e. order, booking, dontation, etc.\).|Best Friends - Best Jeans, Puppy Love, Sail Away, Mens, Kids, Kids : Tops|||||||
|downloaded_file_count_lifetime|string|Count of donations completed that incuded a card request.||||||||
|downloaded_file_count_visit|string|Captures a unique ID for each donation transaction.||||||||
|file_download|string|Captures the recurring frequency of donation \(i.e. one-time, monthly\).||||||||
|file_extension|string|Captures the city associated with a payment.|pdf, doc, csv, dmp, zip|||||||
|file_name|string|Captures the postal code associated with a transaction \(i.e. order, booking, dontation, etc.\).|Year End 2012.pdf, Operating Instructions.doc`|||||||
|identifier|string|Count of times that users completed the donation process.|act now, cancel, ok, 3456, 8765|||||||
|region_ancestry|string|Captures the currency used for currency-related actions.|Top Nav, Footer Nav, Hero, Recommended, Also Shopped, Also Bought|||||||




