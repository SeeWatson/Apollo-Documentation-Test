# Content Loaded

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "view_content",
  "apollo_event": "Content Loaded",
    "ecommerce": {
        "items": [
            {
                "content_date": "<content_date>",
                "content_id": "<content_id>",
                "content_title": "<content_title>"
            }
        ]
    },
    "event_data": {
        "content_author": "<content_author>",
        "date_modified": "<date_modified>",
        "date_published": "<date_published>",
        "identifier": "<identifier>",
        "licensor": "<licensor>",
        "title": "<title>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|content_author|string|The context in which the listing is displayed \(Onsite Search, Curated Assortment,  Navigation\)|Betsy Ross, Ben Franklin, Howard Hughes, Tipper Gore|||||||
|content_date|string|The sort value selected by default on listings.|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|content_id|string|Captures the optimization test IDs as concatenated list for active tests.||||||||
|content_title|string|Count of times when visitors began a contact request flow.|50 ways to use jello, Another look at pandas, Year end giving|||||||
|date_modified|string|Captures the number of content items displayed in a content listing.|1-1-2020, 2-2-2019|||||||
|date_published|string|Captures the author associated with website or mobile app content \(i.e. article, blog post\).|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|identifier|string|Captures the unique ID of content items \(i.e. article or blog post\).||||||||
|licensor|string|Count of content listings displayed in content listings.|HBO, Disney|||||||
|title|string|Count of times that visitors viewed content listings.|50 ways to use jello, Another look at pandas, Year end giving|||||||




