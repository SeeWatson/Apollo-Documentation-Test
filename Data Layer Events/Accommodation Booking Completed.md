# Accommodation Booking Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "purchase",
  "apollo_event": "Accommodation Booking Completed",
    "ecommerce": {
        "affiliation": "<affiliation>",
        "coupon": "<coupon>",
        "currency": "<currency>",
        "items": [
            {
                "affiliation": "<affiliation>",
                "coupon": "<coupon>",
                "currency": "<currency>",
                "date": "<date>",
                "discount": <discount>,
                "index": <index>,
                "item_brand": "<item_brand>",
                "item_category": "<item_category>",
                "item_category2": "<item_category2>",
                "item_category3": "<item_category3>",
                "item_category4": "<item_category4>",
                "item_category5": "<item_category5>",
                "item_id": "<item_id>",
                "item_list_id": "<item_list_id>",
                "item_list_name": "<item_list_name>",
                "item_name": "<item_name>",
                "item_revenue": "<item_revenue>",
                "item_type": "<item_type>",
                "item_variant": "<item_variant>",
                "location_id": "<location_id>",
                "lodging_location_id": "<lodging_location_id>",
                "loyalty_points_used": "<loyalty_points_used>",
                "number_of_adults": <number_of_adults>,
                "number_of_children": "<number_of_children>",
                "number_of_rooms": "<number_of_rooms>",
                "price": "<price>",
                "quantity": <quantity>,
                "rate_code": "<rate_code>"
            }
        ],
        "payment_id": "<payment_id>",
        "payment_method": "<payment_method>",
        "reservation_id": "<reservation_id>",
        "sequence": <sequence>,
        "shipping": <shipping>,
        "tax": <tax>,
        "transaction_id": "<transaction_id>",
        "value": <value>
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A order affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|coupon|string|Order-level coupon code used for a purchase.|summer\_fun|||||||
|currency|string|The currency, in 3-letter ISO 4217 format.||||||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|date|string|Captures the confirmation number associated with each booking cancellation.|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|index|number|The index\/position of the item in a list.|1, 2, 3, 4|||||||
|item_brand|string|Item brand|Gucci|||||||
|item_category|string|Item Category \(context-specific\). item\_category2 through item\_category5 can also be used if the item has many categories.|pants|||||||
|item_category2|string|The second category of an item.||||||||
|item_category3|string|The third category of an item.||||||||
|item_category4|string|The fourth category of an item.||||||||
|item_category5|string|The fifth category of an item.||||||||
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\)|SKU\_12345|||||||
|item_list_id|string|The computer-readible machine name of the list the item showed up in \(if sent with a view\_item\_list event\). Use UUID provided by the component if no more specific ID is available.|12345abcde12345|||||||
|item_list_name|string|The human-readible name of the item list the item showed up in \(if sent with a view\_item\_list event\). If one is not available, populate with numerical index of which list this is on the page \(1-indexed\). For filter\_by\_group component, use that value.|filter\_by\_group, recommended\_products, recently\_viewed\_products|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||
|item_revenue|string|Total amount of loyalty program points used as part of a purchase or for some other redemption activity.|200, 75.29, 150, 89.2|^[0-9]*(\.[0-9]{1,2})?$||||||
|item_type|string|Captures the room type code associated with a lodging room booking.|1-K-NS, 2-Q-S, S-K-NS-City|||||||
|item_variant|string|The variant of the item.|Black|||||||
|location_id|string|The location associated with the event. If possible, set to the Google Place ID that corresponds to the associated item. Can also be overridden to a custom location ID string.|L\_12345|||||||
|lodging_location_id|string|Captures a unique ID of a physical location such as a store, banking branch, atm, hotel, office, or other.|155, 65588, 987764448|||||||
|loyalty_points_used|string|Captures whether each room being booked was the first, second, third, etc. being booked in a multi-room booking.|100, 101, 1000|||||0||
|number_of_adults|integer|Count of times that visitors canceled a room booking.|1, 2, 3, 4, 5||||1|||
|number_of_children|string|Captures the number of children associated with a lodging room booking.|1, 2, 3, 4, 5||||0|||
|number_of_rooms|string|Captures the room rate associated with each night of a lodging room booking.|1, 2, 3||||1|||
|payment_id|string|Captures the number of children associated with a lodging room booking.||ZPH-87698-098||||||
|payment_method|string|Captures the number of adults associated with a lodging room booking.|Credit Card, PayPal, Mastercard, Visa, Amex, Discover|||||||
|price|string|Captures the calendar date associated with each night of a lodging room booking.|200, 75.29, 150, 89.2|^[0-9]*(\.[0-9]{1,2})?$||||||
|quantity|integer|Item quantity.|1|||||||
|rate_code|string|Captures the room rate code associated with a lodging room booking.|AAA, MILITARY, CORP-567, CORP-345|||||||
|reservation_id|string|Captures the reservation ID associated with each booking.||^[a-zA-Z0-9]{6,20}$|6|20||||
|sequence|integer|Total number of nights associated with a room booking.|1, 2, 3, 4, 5||||1|||
|shipping|number|Shipping cost associated with a transaction.|3.33|||||||
|tax|number|Tax cost associated with a transaction.|1.11|||||||
|transaction_id|string|The unique identifier of a transaction.|T\_12345, 19283j2nm9jdjs|^[a-zA-Z0-9]{6,20}$|6|20||||
|value|number|The monetary value of the event.|7.77, 239.55, 659|||||||




