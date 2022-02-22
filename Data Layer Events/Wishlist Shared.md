# Wishlist Shared

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "share_wishlist",
  "apollo_event": "Wishlist Shared",
    "ecommerce": {
        "currency": "<currency>",
        "identifier": "<identifier>",
        "items": [
            {
                "item_price_type": "<item_price_type>",
                "item_sku": "<item_sku>",
                "price": "<price>"
            }
        ],
        "value": "<value>",
        "wishlist_shares": "<wishlist_shares>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|currency|string|Specifies the currency to be used for an Adobe Analytics currency events.  Enables exchange rate calucations at the time of data caputure.|USD, CAD, GBP, CHF|^[A-Z]{3}$|3|3||||
|identifier|string|Captures a unique identifier for each wishlist|12345, 435678, 34567, XCV456, XCV876|||||||
|item_price_type|string|Captures the page name within which CTA links are used.|1st mark, 2nd mark, 3rd mark, clearance, sale, doorbuster|||||||
|item_sku|string|Captures the ID associated with CTA links used.|34567890, 4567890, 00155-large-cornflower|||||||
|price|string|Amount of money associated with products shared from a wishlist.|200, 29.99, 50, 0|^[0-9]*(\.[0-9]{1,2})?$||||||
|value|string|Captures the total monetary value of each wishlist.|5, 20, 10.22|^[0-9]*(\.[0-9]{1,2})?$||||||
|wishlist_shares|string|Count of times that visitors shared wishlists.||||||||




