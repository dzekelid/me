---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 1
info:
  title: Eventbrite
  description: create-manage--promote-events--add-eventmanagement-features-to-your-site--show-the-world-what-exciting-things-are-happening-around-them-
  version: 1.0.0
host: www.eventbrite.com
basePath: /%7Bdata-type%7D/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /checkout_settings/methods/:
    get:
      summary: Get Checkout Settings Methods
      description: Get the available checkout methods to do payments given a country
        and a currency.
      operationId: getCheckoutSettingsMethods
      x-api-path-slug: checkout-settingsmethods-get
      parameters:
      - in: query
        name: country
        description: Expected methods for Country
        type: query
      - in: query
        name: currency
        description: Expected methods for Currency
        type: query
      responses:
        200:
          description: OK
      tags:
      - Checkout
      - Settings
      - Methods
  /media/{id}/:
    get:
      summary: Get Media
      description: Return an image for a given id.
      operationId: getMedia
      x-api-path-slug: mediaid-get
      parameters:
      - in: query
        name: height
        description: Optional thumbnail height (you can specify only this value or
          also width)
        type: query
      - in: query
        name: width
        description: Optional thumbnail width (you can specify only this value or
          also height)
        type: query
      responses:
        200:
          description: OK
      tags:
      - Media
  /media/upload/:
    get:
      summary: Get Media Upload
      description: See Media Uploads.
      operationId: getMediaUpload
      x-api-path-slug: mediaupload-get
      parameters:
      - in: query
        name: type
        description: 'The type of image to upload (Valid choices are: image-event-logo,
          image-event-logo-preserve-quality, image-event-view-from-seat, image-organizer-logo,
          image-user-photo, or image-structured-content)'
        type: query
      responses:
        200:
          description: OK
      tags:
      - Media
      - Upload
  /users/me/notifications/:
    get:
      summary: Get Users Me Notifications
      description: Gets a paginated response of notification objects for a determined
        user.
      operationId: getUsersMeNotifications
      x-api-path-slug: usersmenotifications-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - Me
      - Notifications
  /system/timezones/:
    get:
      summary: Get System Timezones
      description: |-
        Returns a paginated response with a key of timezones,
        containing a list of timezones.
      operationId: getSystemTimezones
      x-api-path-slug: systemtimezones-get
      responses:
        200:
          description: OK
      tags:
      - System
      - Timezones
  /users/{id}/assortment/:
    get:
      summary: Get Users Assortment
      description: Retrieve the assortment for the user.
      operationId: getUsersAssortment
      x-api-path-slug: usersidassortment-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - Assortment
    post:
      summary: Post Users Assortment
      description: |-
        Set a user&#8217;s assortment and returns the assortment for the specified
        user.
      operationId: postUsersAssortment
      x-api-path-slug: usersidassortment-post
      parameters:
      - in: query
        name: plan
        description: The assortments package to upgrade/downgrade to
        type: query
      responses:
        200:
          description: OK
      tags:
      - Users
      - Assortment
  /payment_update:
    get:
      summary: Get Payment Update
      description: This method creates or updates the payment options for this event.
        Only the fields passed as arguments will be modified.
      operationId: Get_payment_update_
      x-api-path-slug: payment-update-get
      parameters:
      - in: query
        name: accept_cash
        description: Accept Pay by Cash payments (1 or 0)
      - in: query
        name: accept_check
        description: Accept Pay by Check payments (1 or 0)
      - in: query
        name: accept_google
        description: Accept Google Checkout payments (1 or 0)
      - in: query
        name: accept_invoice
        description: Accept Send an Invoice payments (1 or 0)
      - in: query
        name: accept_paypal
        description: Accept PayPal payments (1 or 0)
      - in: query
        name: data-type
        description: xml or json data-types are supported
      - in: query
        name: event_id
        description: The event ID
      - in: query
        name: google_merchant_id
        description: Google Checkout Merchant ID
      - in: query
        name: google_merchant_key
        description: Google Checkout Merchant Key
      - in: query
        name: instructions_cash
        description: Instructions to attendees who want to pay by cash
      - in: query
        name: instructions_check
        description: Instructions to attendees who want to pay by check
      - in: query
        name: instructions_invoice
        description: Instructions to attendees who need to be sent an invoice
      - in: query
        name: paypal_email
        description: Your PayPal email
      responses:
        200:
          description: OK
      tags:
      - Payment
      - Update
---