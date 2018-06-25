---
name: Square
x-slug: square
description: Square helps millions of sellers run their business- from secure credit
  card processing to point of sale solutions. Get paid faster with Square and sign
  up today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
x-kinRank: "9"
x-alexaRank: "2433"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/apis.md
specificationVersion: "0.14"
apis:
- name: Square Connect API Provides summary information for all of a business's employee
    timecards.
  x-api-slug: square-connect-api
  description: Provides summary information for all of a business's employee timecards.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/me/timecards
  tags: Provides,Summary,Information,Of,Businesss,Employee,Timecards
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1metimecards-get-openapi.md
- name: Square Connect API Creates a timecard for an employee. Each timecard corresponds
    to a single shift.
  x-api-slug: square-connect-api
  description: Creates a timecard for an employee. Each timecard corresponds to a
    single shift.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/me/timecards
  tags: Creates,Timecardan,Employee,,Each,Timecard,Corresponds,To,Single,Shift
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1metimecards-post-openapi.md
- name: Square Connect API Deletes a timecard. Deleted timecards are still accessible
    from Connect API endpoints, but the value of their deleted field is set to true.
    See Handling deleted timecards for more information.
  x-api-slug: square-connect-api
  description: Deletes a timecard. Deleted timecards are still accessible from Connect
    API endpoints, but the value of their deleted field is set to true. See Handling
    deleted timecards for more information.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/me/timecards/{timecard_id}
  tags: S,Timecard,,D,Timecards,Are,Still,Accessible,From,Connect,Endpoints,,But,Value,Of,Their,Deleted,Field,Is,Set,To,True,,See,Handling,Deleted,Timecardsmore,Information
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1metimecardstimecard-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1metimecardstimecard-id-delete-openapi.md
- name: Square Connect API Provides the details for a single timecard.
  x-api-slug: square-connect-api
  description: Provides the details for a single timecard.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/me/timecards/{timecard_id}
  tags: Provides,Detailsa,Single,Timecard
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1metimecardstimecard-id-get-openapi.md
- name: Square Connect API Modifies a timecard's details. This creates an API_EDIT
    event for the timecard. You can view a timecard's event history with the List
    Timecard Events endpoint.
  x-api-slug: square-connect-api
  description: Modifies a timecard's details. This creates an API_EDIT event for the
    timecard. You can view a timecard's event history with the List Timecard Events
    endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/me/timecards/{timecard_id}
  tags: Modifies,Timecards,Details,,This,Creates,EDIT,Eventthe,Timecard,,You,Can,View,Timecards,Event,History,List,Timecard,Events,Endpoint
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1metimecardstimecard-id-put-openapi.md
- name: Square Connect API Provides summary information for all events associated
    with a particular timecard.
  x-api-slug: square-connect-api
  description: Provides summary information for all events associated with a particular
    timecard.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/me/timecards/{timecard_id}/events
  tags: Provides,Summary,Information,Events,Associated,Particular,Timecard
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1metimecardstimecard-idevents-get-openapi.md
- name: Square Connect API Provides non-confidential details for a merchant's associated
    bank account. This endpoint does not provide full bank account numbers, and there
    is no way to obtain a full bank account number with the Connect API.
  x-api-slug: square-connect-api
  description: Provides non-confidential details for a merchant's associated bank
    account. This endpoint does not provide full bank account numbers, and there is
    no way to obtain a full bank account number with the Connect API.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/bank-accounts/{bank_account_id}
  tags: Provides,Non-confidential,Detailsa,Merchants,Associated,Bank,Account,,This,Endpoint,Does,Not,Provide,Full,Bank,Account,Numbers,,There,Is,No,Way,To,Obtain,Full,Bank,Account,Number,Connect
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-idbankaccountsbank-account-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-idbankaccountsbank-account-id-get-openapi.md
- name: Square Connect API Provides inventory information for all of a merchant's
    inventory-enabled item variations.
  x-api-slug: square-connect-api
  description: Provides inventory information for all of a merchant's inventory-enabled
    item variations.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/inventory
  tags: Provides,Inventory,Information,Of,Merchants,Inventory-enabled,Item,Variations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-idinventory-get-openapi.md
- name: Square Connect API Removes a fee assocation from an item, meaning the fee
    is no longer automatically applied to the item in Square Register.
  x-api-slug: square-connect-api
  description: Removes a fee assocation from an item, meaning the fee is no longer
    automatically applied to the item in Square Register.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/items/{item_id}/fees/{fee_id}
  tags: Removes,Fee,Assocation,From,Item,,Meaning,Fee,Is,No,Longer,Automatically,Applied,To,Item,In,Square,Register
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-iditemsitem-idfeesfee-id-delete-openapi.md
- name: Square Connect API Associates a fee with an item, meaning the fee is automatically
    applied to the item in Square Register.
  x-api-slug: square-connect-api
  description: Associates a fee with an item, meaning the fee is automatically applied
    to the item in Square Register.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/items/{item_id}/fees/{fee_id}
  tags: Associates,Fee,Item,,Meaning,Fee,Is,Automatically,Applied,To,Item,In,Square,Register
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-iditemsitem-idfeesfee-id-put-openapi.md
- name: Square Connect API Removes a modifier list association from an item, meaning
    modifier options from the list can no longer be applied to the item.
  x-api-slug: square-connect-api
  description: Removes a modifier list association from an item, meaning modifier
    options from the list can no longer be applied to the item.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/items/{item_id}/modifier-lists/{modifier_list_id}
  tags: Removes,Modifier,List,Association,From,Item,,Meaning,Modifier,Options,From,List,Can,No,Longer,Be,Applied,To,Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-iditemsitem-idmodifierlistsmodifier-list-id-delete-openapi.md
- name: Square Connect API Associates a modifier list with an item, meaning modifier
    options from the list can be applied to the item.
  x-api-slug: square-connect-api
  description: Associates a modifier list with an item, meaning modifier options from
    the list can be applied to the item.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/items/{item_id}/modifier-lists/{modifier_list_id}
  tags: Associates,Modifier,List,Item,,Meaning,Modifier,Options,From,List,Can,Be,Applied,To,Item
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-iditemsitem-idmodifierlistsmodifier-list-id-put-openapi.md
- name: Square Connect API Provides summary information for a merchant's online store
    orders.
  x-api-slug: square-connect-api
  description: Provides summary information for a merchant's online store orders.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/orders
  tags: Provides,Summary,Informationa,Merchants,Online,Store,Orders
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-idorders-get-openapi.md
- name: Square Connect API Provides summary information for all payments taken by
    a merchant or any of the merchant's mobile staff during a date range. Date ranges
    cannot exceed one year in length. See Date ranges for details of inclusive and
    exclusive dates.
  x-api-slug: square-connect-api
  description: Provides summary information for all payments taken by a merchant or
    any of the merchant's mobile staff during a date range. Date ranges cannot exceed
    one year in length. See Date ranges for details of inclusive and exclusive dates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/payments
  tags: Provides,Summary,Information,Payments,Taken,By,Merchant,Any,Of,Merchants,Mobile,Staff,During,Date,Range,,Date,Ranges,Cannot,Exceed,Year,In,Length,,See,Date,Rangesdetails,Of,Inclusive,Exclusive,Dates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-idpayments-get-openapi.md
- name: Square Connect API Provides comprehensive information for a single payment.
  x-api-slug: square-connect-api
  description: Provides comprehensive information for a single payment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/payments/{payment_id}
  tags: Provides,Comprehensive,Informationa,Single,Payment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-idpaymentspayment-id-get-openapi.md
- name: Square Connect API Provides the details for all refunds initiated by a merchant
    or any of the merchant's mobile staff during a date range. Date ranges cannot
    exceed one year in length.
  x-api-slug: square-connect-api
  description: Provides the details for all refunds initiated by a merchant or any
    of the merchant's mobile staff during a date range. Date ranges cannot exceed
    one year in length.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/refunds
  tags: Provides,Details,Refunds,Initiated,By,Merchant,Any,Of,Merchants,Mobile,Staff,During,Date,Range,,Date,Ranges,Cannot,Exceed,Year,In,Length
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-idrefunds-get-openapi.md
- name: Square Connect API Issues a refund for a previously processed payment. You
    must issue a refund within 60 days of the associated payment.
  x-api-slug: square-connect-api
  description: Issues a refund for a previously processed payment. You must issue
    a refund within 60 days of the associated payment.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/refunds
  tags: Issues,Refunda,Previously,Processed,Payment,,You,Must,Issue,Refund,Within,60,Days,Of,Associated,Payment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-idrefunds-post-openapi.md
- name: Square Connect API Provides summary information for all deposits and withdrawals
    initiated by Square to a merchant's bank account during a date range. Date ranges
    cannot exceed one year in length.
  x-api-slug: square-connect-api
  description: Provides summary information for all deposits and withdrawals initiated
    by Square to a merchant's bank account during a date range. Date ranges cannot
    exceed one year in length.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/settlements
  tags: Provides,Summary,Information,Deposits,Withdrawals,Initiated,By,Square,To,Merchants,Bank,Account,During,Date,Range,,Date,Ranges,Cannot,Exceed,Year,In,Length
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-idsettlements-get-openapi.md
- name: Square Connect API Provides comprehensive information for a single settlement,
    including the entries that contribute to the settlement's total.
  x-api-slug: square-connect-api
  description: Provides comprehensive information for a single settlement, including
    the entries that contribute to the settlement's total.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v1/{location_id}/settlements/{settlement_id}
  tags: Provides,Comprehensive,Informationa,Single,Settlement,,Including,Entries,That,Contribute,To,Settlements,Total
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v1location-idsettlementssettlement-id-get-openapi.md
- name: Square Connect API ListCustomers
  x-api-slug: square-connect-api
  description: Lists a business's customers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v2/customers
  tags: ListCustomers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v2customers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v2customers-get-openapi.md
- name: Square Connect API CreateCustomer
  x-api-slug: square-connect-api
  description: |-
    Creates a new customer for a business, which can have associated cards on file.

    You must provide __at least one__ of the following values in your request to this
    endpoint:

    - `given_name`
    - `family_name`
    - `company_name`
    - `email_address`
    - `phone_number`

    This endpoint does not accept an idempotency key. If you accidentally create
    a duplicate customer, you can delete it with the
    [DeleteCustomer](#endpoint-deletecustomer) endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v2/customers
  tags: CreateCustomer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v2customers-post-openapi.md
- name: Square Connect API DeleteCustomer
  x-api-slug: square-connect-api
  description: Deletes a customer from a business, along with any linked cards on
    file.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v2/customers/{customer_id}
  tags: Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v2customerscustomer-id-delete-openapi.md
- name: Square Connect API RetrieveCustomer
  x-api-slug: square-connect-api
  description: Returns details for a single customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v2/customers/{customer_id}
  tags: RetrieveCustomer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v2customerscustomer-id-get-openapi.md
- name: Square Connect API UpdateCustomer
  x-api-slug: square-connect-api
  description: |-
    Updates the details of an existing customer.
    The ID of the customer may change if the customer has been merged into another customer.

    You cannot edit a customer's cards on file with this endpoint. To make changes
    to a card on file, you must delete the existing card on file with the
    [DeleteCustomerCard](#endpoint-deletecustomercard) endpoint, then create a new one with the
    [CreateCustomerCard](#endpoint-createcustomercard) endpoint.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v2/customers/{customer_id}
  tags: Customer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v2customerscustomer-id-put-openapi.md
- name: Square Connect API CreateCustomerCard
  x-api-slug: square-connect-api
  description: |-
    Adds a card on file to an existing customer. In the United States
    Square takes care of automatically updating any cards on file that might
    have expired since you first attached them to a customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v2/customers/{customer_id}/cards
  tags: CreateCustomerCard
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v2customerscustomer-idcards-post-openapi.md
- name: Square Connect API DeleteCustomerCard
  x-api-slug: square-connect-api
  description: Removes a card on file from a customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com////v2/customers/{customer_id}/cards/{card_id}
  tags: CustomerCard
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/v2customerscustomer-idcardscard-id-delete-openapi.md
- name: Square Connect API
  x-api-slug: square-connect-api
  description: Square helps millions of sellers run their business- from secure credit
    card processing to point of sale solutions. Get paid faster with Square and sign
    up today!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2176-square.jpg
  humanURL: http://square.com
  baseURL: https://connect.squareup.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/square/openapi.md
x-common:
- type: x-website
  url: http://square.com
- type: x-base
  url: https://connect.squareup.com
- type: x-crunchbase
  url: http://www.crunchbase.com/company/square
- type: x-crunchbase
  url: https://crunchbase.com/organization/square
- type: x-developer
  url: https://connect.squareup.com/
- type: x-email
  url: press@squareup.com
- type: x-email
  url: security@squareup.com
- type: x-email
  url: lawenforcement@squareup.com
- type: x-email
  url: redemption@squareup.com
- type: x-email
  url: privacy@squareup.com
- type: x-email
  url: community@squareup.com
- type: x-email
  url: noreply@messaging.squareup.com
- type: x-email
  url: ir@squareup.com
- type: x-email
  url: takedowns@squareup.com
- type: x-github
  url: https://github.com/square
- type: x-linkedin
  url: https://www.linkedin.com/company/square--/
- type: x-twitter
  url: https://twitter.com/Square
- type: x-website
  url: http://squareup.com
- type: x-website
  url: https://squareup.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---