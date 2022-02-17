# User Detected

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "detect_user",
  "apollo_event": "User Detected",
    "page_data": {
        "user_login_state": "<user_login_state>"
    },
    "user_data": {
        "affiliate_customer_id": "<affiliate_customer_id>",
        "anonymous_user_id": "<anonymous_user_id>",
        "employee_id": "<employee_id>",
        "organization_id": "<organization_id>",
        "user_age_or_birth_year": "<user_age_or_birth_year>",
        "user_city": "<user_city>",
        "user_cookie_id": "<user_cookie_id>",
        "user_customer_lifetime_value": "<user_customer_lifetime_value>",
        "user_customer_since": "<user_customer_since>",
        "user_id": "<user_id>",
        "user_lifetime_logins": "<user_lifetime_logins>",
        "user_marital_status": "<user_marital_status>",
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
|affiliate_customer_id|string|The user ID of user who arrived at the website via a third party partner.||||||||
|anonymous_user_id|string|When a user is not logged in,, this captures an anonymous user id.||||||||
|employee_id|string|Captures the employee ID associated with website or mobile app traffic.|Gold, Bronze, Platinum, Diamond, Silver|||||||
|organization_id|string|Captures the user Organization ID associated with website or mobile app behavior.|1234, G72345, Alaska|||||||
|user_age_or_birth_year|string|Captures the birth year or current age of the user.||||||||
|user_city|string|Captures the city associated with the user.||||||||
|user_cookie_id|string|Captures the user ID based on a cookie.||||||||
|user_customer_lifetime_value|string|Captures the current customer lifetime value \(CLV\) for the user. Typically imported from back-end database.||||||||
|user_customer_since|string|Captures the date a user first became a customer. Typically imported from back-end database.||||||||
|user_id|string|The id of the user currently logged in to the site, if the site offers authentication and the user is authenticated.|123456, abc123|||||||
|user_lifetime_logins|unknown|Captures the count of times the user has authenticated in the past. Typically imported from back-end database.||||||||
|user_login_state|string|Captures the current sign in status for the user \(i.e. signed\_out, signed\_in, unknown\).|logged in, logged out, guest|||||||
|user_marital_status|string|Captures the current marital status of the visitor.||||||||
|user_original_source|string|Captures the original way that a customer was acquired. Typically imported from back-end database.||||||||
|user_past_order_count|number|Captures the current customer order count for the visitor. Typically imported from back-end database.||||||||
|user_registration_status|string|Captures the current registration status of the user.|registered|||||||
|user_segment|string|Captures the internal CRM or Data Warehouse segment associated with each user.||||||||
|user_state_or_province|string|Captures the state or province associated with a tranaction or significant user action.||||||||
|user_type|unknown|Captures the type associated with the user \(i.e. guest, registered, prime, etc\).|employee, guest, agent, customer|||||||




