# Onsite Search Performed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "search",
  "apollo_event": "Onsite Search Performed",
    "event_data": {
        "accuracy": "<accuracy>",
        "corrected_term": "<corrected_term>",
        "days_to_start_date": "<days_to_start_date>",
        "end_date": "<end_date>",
        "facets": "<facets>",
        "item_id": "<item_id>",
        "latitude": <latitude>,
        "location_id": "<location_id>",
        "longitude": <longitude>,
        "map_vendor": "<map_vendor>",
        "multi_search_entries": "<multi_search_entries>",
        "number_of_adults": <number_of_adults>,
        "number_of_children": <number_of_children>,
        "onsite_search_date_count": <onsite_search_date_count>,
        "people": "<people>",
        "postal_code": "<postal_code>",
        "radius": <radius>,
        "related_search_term_searches": <related_search_term_searches>,
        "search_term": "<search_term>",
        "start_date": "<start_date>",
        "type": "<type>",
        "unit_of_measure": "<unit_of_measure>",
        "zoom_level": "<zoom_level>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|accuracy|string|Captures the number of ratings for each location.|high, medium, low|||||||
|corrected_term|string|Captures the average rating for each location.|bluth:blu, blue:blu, red lobster:rd lbstr|||||||
|days_to_start_date|unknown|Captures the objective \(A\/B Test, sale promo\) associated with each internal campaign click and the impact on downstream success or conversion.|1, 2, 3, 4, 5||||0|||
|end_date|string|Captures the type of interstitial that was shown to visitors.|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|facets|string|The type of location associated with activity and conversion.||||||||
|item_id|string|Count of times that visitors clicked on internal \(onsite\) campaigns.|155, 65588, 987764448|||||||
|latitude|number|Captures the internal campaign creative associated with internal campaigns. Used for internal campaign impressions and clicks only.|-90, 90, 48.858093|||||||
|location_id|string|Captures the name associated with internal campaigns. Used for internal campaign impressions and clicks only.|155, 65588, 987764448|||||||
|longitude|number|Captures the brand associated with each location.|-180, 180, 2.294694|||||||
|map_vendor|string|Count of times that visitors added filters to listing results.|Google, Bing, Mapquest, ESRI|||||||
|multi_search_entries|string|Captures the method that was used to determine the location associated with visitor activity.|fieldName\~phrase, sku\~12345, product name\~oak\|sku\~12345\|color\~green|||||||
|number_of_adults|integer|Captures the position of an internal campaign on a website page or mobile app screen. Used for internal campaign impressions and clicks only.|1, 2, 3, 4, 5||||1|||
|number_of_children|integer|Count of times that visitors changed the sorting of listings.|1, 2, 3, 4, 5||||0|||
|onsite_search_date_count|integer|Count of times that visitors viewed location listings.|8, 1, 5, 6, 7, 10||||1|||
|people|string|Count of times visitors were shown an interstitial page or screen.|1, 2, 3, 4, 5||||1|||
|postal_code|string|Captures the ID associated with internal campaigns. Used for internal campaign impressions and clicks only.|53533, 30381, M1R 0E9, M3C 0C1|||||||
|radius|number|Count of times that visitors were presented with an internal \(onsite\) campaign.|2.294694||||0|||
|related_search_term_searches|integer|Captures the position of an internal campaign on a website page or mobile app screen. Used for internal campaign impressions and clicks only.||||||||
|search_term|string|Captures the website method \(i.e. search, top nav\) used to find each product.|bluth, blue, red lobster|||||||
|start_date|string|Count of times that visitors removed filters from listing results.|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|type|string|Captures the website method \(i.e. search, top nav\) used to find each product at the time of cart addition|products, properties, articles, authors, coupons, publications|||||||
|unit_of_measure|string|Captures the ID associated with internal campaigns clicks and see the impact on downstream success or conversion.|miles, kilometers, meters|||||||
|zoom_level|string|Captures the number of locations displayed in a location listing.|1, 2, 3, 4, 5, 6|||||||




