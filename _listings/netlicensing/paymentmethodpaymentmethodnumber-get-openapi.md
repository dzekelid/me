---
swagger: "2.0"
x-collection-name: NetLicensing
x-complete: 0
info:
  title: NetLicensing Get payment method
  description: Return a payment method info by paymentMethodNumber
  termsOfService: https://www.labs64.com/legal/terms-of-service/netlicensing
  version: 2.x
host: go.netlicensing.io
basePath: /core/v2/rest
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /paymentmethod:
    get:
      summary: Payment Methods list
      description: Return a list of all payment methods for the current vendor
      operationId: listPaymentMethods
      x-api-path-slug: paymentmethod-get
      responses:
        200:
          description: OK
      tags:
      - Paymentmethod
  /paymentmethod/{paymentMethodNumber}:
    get:
      summary: Get payment method
      description: Return a payment method info by paymentMethodNumber
      operationId: getPaymentMethod
      x-api-path-slug: paymentmethodpaymentmethodnumber-get
      parameters:
      - in: path
        name: paymentMethodNumber
        description: Payment method number
      responses:
        200:
          description: OK
      tags:
      - Paymentmethod
      - PaymentMethodNumber
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