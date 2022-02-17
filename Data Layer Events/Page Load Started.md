# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_view",
  "apollo_event": "Page Load Started",
    "page_data": {
        "affiliate_id": "<affiliate_id>",
        "breadcrumb": "<breadcrumb>",
        "country": "<country>",
        "day_of_week": "<day_of_week>",
        "email_message_id": "<email_message_id>",
        "email_message_link_id": "<email_message_link_id>",
        "email_recipient_id": "<email_recipient_id>",
        "hour": "<hour>",
        "incognito_mode_page_views": <incognito_mode_page_views>,
        "language": "<language>",
        "name": "<name>",
        "owner": "<owner>",
        "page_hash": "<page_hash>",
        "page_location": "<page_location>",
        "page_name_detailed": "<page_name_detailed>",
        "page_path": "<page_path>",
        "page_query_string": "<page_query_string>",
        "page_title": "<page_title>",
        "page_type_merchandising": "<page_type_merchandising>",
        "page_variant": "<page_variant>",
        "page_view_custom_event": "<page_view_custom_event>",
        "pages_viewed_num_visit": "<pages_viewed_num_visit>",
        "platform_version": "<platform_version>",
        "release_version": "<release_version>",
        "site_country": "<site_country>",
        "site_language": "<site_language>",
        "site_name": "<site_name>",
        "site_section": "<site_section>",
        "site_section2": "<site_section2>",
        "site_section3": "<site_section3>",
        "site_section4": "<site_section4>",
        "site_type": "<site_type>",
        "site_variant": "<site_variant>",
        "type": "<type>",
        "weekday_or_weekend": "<weekday_or_weekend>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliate_id|unknown|Captures the accuracy of the method that determined the coordinates of the POI \(point of interest\).||||||||
|breadcrumb|string|Captures the postal code for shipping.|Home&gt;Women&gt;Tops&gt;Sweaters, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Checkout &gt; Order Thank You|||||||
|country|string|The country the site is associated with.||||||||
|day_of_week|string|Captures a concatenated list of product SKU's that are present in the same purchase.||||||||
|email_message_id|unknown|Counts the times that successful onsite searches occurred.||||||||
|email_message_link_id|string|Captures the country associated with payments used for a transaction \(i.e. order, booking, dontation, etc.\).||||||||
|email_recipient_id|string|Captures the shipping method for each product \(i.e. UPS Ground, FedEx Next Day, RedEx Ground, etc\).||||||||
|hour|string|The time of activity at the top of the hour.||||||||
|incognito_mode_page_views|integer|This parameter is already configured by Google Tag Manager and Googel Analytics.||||||||
|language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|name|string|Amount of money discounted for the entire order.|product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|owner|string|Counts of times the user performed an interaction on the order confirmation page.|XX product management, marketing, vendor name|||||||
|page_hash|string|Captures the coupon code associated with product level discounts for a transaction.||||||||
|page_location|string|The url of the page currently being viewed.||||||||
|page_name_detailed|string|Captures the filter applied to the product listings or search results.|product - XYZ123 - super cotton neck scarf, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Order Confirmation - 098fghjkl|||||||
|page_path|string|Captures the path portion of the page URL.||||||||
|page_query_string|string|This parameter is already configured by Google Tag Manager and Google Analytics.||||||||
|page_title|string|The title of the page currently being viewed, generally available in &lt;title&gt;.||||||||
|page_type_merchandising|string|Captures the revenue dollar amount of the order for use in bucketing orders into specific revenue bands \(i.e. $0-$50, $51-$100\).|Home, Event Detail, Property Detail, Product Listing, Blog Post, Shopping Cart|||||||
|page_variant|string|Amount of money associated with base prices for products that reached the order confirmation step of the shopping cart.||||||||
|page_view_custom_event|string|Type of click event engaged with by the user on the order confirmaton page.||||||||
|pages_viewed_num_visit|string|Running total of how many pages or screens a visitor had viewed at the time they took a website or mobile app action. Count re-starts with each visit.||||||||
|platform_version|string|Captures a boolean flag indicating whether or not products were samples.||||||||
|release_version|string|Collects the number of payment methods used for an order at order confirmaton||||||||
|site_country|string|Captures the country associated with website or mobile app activity.|US, CA, FR, UK|^[A-Z]{2}$||||||
|site_language|string|Captures the language associated with website or mobile app activity.|en-us, en-gb, ch-cn, fr-ca, fr-fr, da|^[a-z]{2}([-]{1}[a-z]{2}){0,1}$||||||
|site_name|string|Captures the business unit associated with each product.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|site_section|string|The section of the site that the current page resides in. site\_section2 through site\_section5can also be used if the site has many sections.||||||||
|site_section2|string|When a user has put in the information of an alternate pick up person during the checkout process.|Shop &gt; Kids, Shop &gt; Mens, Shop &gt; Womens|||||||
|site_section3|string|Captures the website or mobile app sub-sub-section \(two levels below main section\) associated with the page or screen viewed.|Shop &gt; Kids &gt; Tops, Shop &gt; Mens &gt; Shoes|||||||
|site_section4|string|Captures the website or mobile app sub-sub-sub-section \(three levels below main section\) associated with the page or screen viewed.|Shop &gt; Kids &gt; Tops &gt; Tees, Shop &gt; Mens &gt; Shoes &gt; Oxfords|||||||
|site_type|string|Amount of money associated with markdown prices for products reached the order confirmation step of the shopping cart.|Prospecting, Shop, Members, Brand|||||||
|site_variant|string|This parameter is already configured by Google Tag Manager and Googel Analytics.|Responsive, Mobile, Desktop|||||||
|type|string|The type of page currently viewed.|home, pdp, article|||||||
|weekday_or_weekend|string|Whether it was a week day or weekend when activity is occurred.||||||||




