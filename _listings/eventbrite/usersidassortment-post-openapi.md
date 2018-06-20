---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Post Users Assortment
  description: |-
    Set a user&#8217;s assortment and returns the assortment for the specified
    user.
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---