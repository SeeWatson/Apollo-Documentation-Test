# User Signed In

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "login",
  "apollo_event": "User Signed In",
    "event_data": {
        "login_persist_clicks": <login_persist_clicks>,
        "loyalty_points": "<loyalty_points>",
        "loyalty_status": "<loyalty_status>",
        "method": "<method>",
        "persisted_cart_counter": <persisted_cart_counter>,
        "persisted_cart_value": "<persisted_cart_value>"
    },
    "page_data": {
        "user_login_state": "<user_login_state>"
    },
    "user_data": {
        "employee_id": "<employee_id>",
        "organization_id": "<organization_id>",
        "user_age_or_birth_year": "<user_age_or_birth_year>",
        "user_attributes": "<user_attributes>",
        "user_city": "<user_city>",
        "user_country": "<user_country>",
        "user_customer_lifetime_value": "<user_customer_lifetime_value>",
        "user_customer_since": "<user_customer_since>",
        "user_id": "<user_id>",
        "user_lifetime_logins": "<user_lifetime_logins>",
        "user_marital_status": "<user_marital_status>",
        "user_number_of_children": <user_number_of_children>,
        "user_original_source": "<user_original_source>",
        "user_past_order_count": <user_past_order_count>,
        "user_registration_status": "<user_registration_status>",
        "user_segment": "<user_segment>",
        "user_state_or_province": "<user_state_or_province>",
        "user_type": "<user_type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|employee_id|string|Captures the employee ID associated with website or mobile app traffic.|Gold, Bronze, Platinum, Diamond, Silver|||||||
|login_persist_clicks|integer|Count of times users selected the option to persist their login \(i.e.,"keep me logged in"\) when signing in.||||||||
|loyalty_points|string|Captures the total loyalty points the user had at the time of the visit.|Gold, Bronze, Platinum, Diamond, Silver|||||||
|loyalty_status|string|Captures the current loyalty status of the user.|Gold, Bronze, Platinum, Diamond, Silver|||||||
|method|string|The platform used to share content|email, facebook, twitter|||||||
|organization_id|string|Captures the user Organization ID associated with website or mobile app behavior.|1234, G72345, Alaska|||||||
|persisted_cart_counter|boolean|Count of times that visitors had products in a shopping cart at the time they signed-in.|TRUE, FALSE|||||||
|persisted_cart_value|string|Amount of money associated with persistent shopping carts at the time visitors signed-in.|125.05, 432.21, 90.22, 12.05|^[0-9]*(\.[0-9]{1,2})?$||||||
|user_age_or_birth_year|string|Captures the birth year or current age of the user.||||||||
|user_attributes|string|Attributes of the application user|homeStore\~234\|loyaltyTier\~gold\|memberSince\~2002|||||||
|user_city|string|Captures the city associated with the user.||||||||
|user_country|string|Captures the country associated with the user.|USA, Canada|||||||
|user_customer_lifetime_value|string|Captures the current customer lifetime value \(CLV\) for the user. Typically imported from back-end database.||||||||
|user_customer_since|string|Captures the date a user first became a customer. Typically imported from back-end database.||||||||
|user_id|string|Captures the loyalty ID associated with each user.|abc1234, def876, 87987659|||||||
|user_lifetime_logins|unknown|Captures the count of times the user has authenticated in the past. Typically imported from back-end database.||||||||
|user_login_state|string|Captures the current sign in status for the user \(i.e. signed\_out, signed\_in, unknown\).|logged in, logged out, guest|||||||
|user_marital_status|string|Captures the current marital status of the visitor.||||||||
|user_number_of_children|integer|Captures the number of children associated with the visitor.||||||||
|user_original_source|string|Captures the original way that a customer was acquired. Typically imported from back-end database.||||||||
|user_past_order_count|number|Captures the current customer order count for the visitor. Typically imported from back-end database.||||||||
|user_registration_status|string|Captures the current registration status of the user.|registered|||||||
|user_segment|string|Captures the internal CRM or Data Warehouse segment associated with each user.||||||||
|user_state_or_province|string|Captures the state or province associated with a tranaction or significant user action.||||||||
|user_type|unknown|Captures the type associated with the user \(i.e. guest, registered, prime, etc\).|employee, guest, agent, customer|||||||




