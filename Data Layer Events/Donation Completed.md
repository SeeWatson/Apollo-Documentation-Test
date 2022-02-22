# Donation Completed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer.push({
  "event": "purchase",
  "apollo_event": "Donation Completed",
    "ecommerce": {
        "affiliation": "<affiliation>",
        "city": "<city>",
        "coupon": "<coupon>",
        "currency": "<currency>",
        "donation_complete_counter": "<donation_complete_counter>",
        "donation_thank_you_cards_request_count": <donation_thank_you_cards_request_count>,
        "items": [
            {
                "affiliation": "<affiliation>",
                "coupon": "<coupon>",
                "currency": "<currency>",
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
                "item_variant": "<item_variant>",
                "location_id": "<location_id>",
                "price": <price>,
                "quantity": <quantity>
            }
        ],
        "payment_frequency": "<payment_frequency>",
        "payment_id": "<payment_id>",
        "payment_method": "<payment_method>",
        "postal_code": "<postal_code>",
        "sequence": <sequence>,
        "shipping": <shipping>,
        "state_province": "<state_province>",
        "tax": <tax>,
        "thank_you_card_type": "<thank_you_card_type>",
        "transaction_id": "<transaction_id>",
        "type": "<type>",
        "value": "<value>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliation|string|A order affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|affiliation|string|A product affiliation to designate a supplying company or brick and mortar store location.|Google Store|||||||
|city|string|Captures the method that was used to apply the discount \(e.g., automatic, manual entry\).|Atlanta, New York, Los Angeles, Chicago|||||||
|coupon|string|Item-level coupon code used for a purchase.|SUMMER\_FUN|||||||
|coupon|string|Order-level coupon code used for a purchase.|summer\_fun|||||||
|currency|string|Count of times a user applied a promotional offer to their order that was already in their wallet.|USD, CAD, GBP, CHF|^[A-Z]{3}$|3|3||||
|currency|string|The currency, in 3-letter ISO 4217 format.|USD|||||||
|discount|number|Monetary value of discount associated with a purchase.|2.22|||||||
|donation_complete_counter|unknown|Count of times a discount codes were applied to orders.||||||||
|donation_thank_you_cards_request_count|boolean|Captures the publish date of content items \(i.e. article or blog post\).|TRUE, FALSE|||||||
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
|item_variant|string|The variant of the item.|Black|||||||
|location_id|string|The location associated with the event. If possible, set to the Google Place ID that corresponds to the associated item. Can also be overridden to a custom location ID string.|L\_12345|||||||
|payment_frequency|string|Counts the times content was viewed.|One Time, Monthly|||||||
|payment_id|string|Captures the number of children associated with a lodging room booking.||ZPH-87698-098||||||
|payment_method|string|Captures the number of adults associated with a lodging room booking.|Credit Card, PayPal, Mastercard, Visa, Amex, Discover|||||||
|postal_code|string|Count of times that visitors encounter discount code entry failures.|53533, 30381, M1R 0E9, M3C 0C1|||||||
|price|number|The monetary price of the item, in units of the specified currency parameter.|9.99|||||||
|quantity|integer|Item quantity.|1|||||||
|sequence|integer|Total number of nights associated with a room booking.|1, 2, 3, 4, 5||||1|||
|shipping|number|Shipping cost associated with a transaction.|3.33|||||||
|state_province|string|Captures the coupon code applied.|WI, GA, NB, ON|||||||
|tax|number|Tax cost associated with a transaction.|1.11|||||||
|thank_you_card_type|string|Captures the last date that content was modified\/updated.|Electronic, Physical|||||||
|transaction_id|string|The unique identifier of a transaction.|T\_12345, 19283j2nm9jdjs|^[a-zA-Z0-9]{6,20}$|6|20||||
|type|string|Count of times that visitors successfully entered discount codes.|Tribute, General, Fundraiser|||||||
|value|string|Count of times that visitors completed the room booking process.|200, 29.99, 50, 0|^[0-9]*(\.[0-9]{1,2})?$||||||




