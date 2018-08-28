---
swagger: "2.0"
x-collection-name: Constant Contact
x-complete: 1
info:
  title: Constant Contact
  description: make-constant-contacts-leading-email-and-event-marketing-services-accessible-directly-from-your-app-
  version: 1.0.0
host: api.constantcontact.com
basePath: /ws/customers/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{username}/events/{event-id}/registrants/{registrant-id}/paymentstatus:
    get:
      summary: Get Payment Status
      description: Get Payment Status
      operationId: get-payment-status
      x-api-path-slug: usernameeventseventidregistrantsregistrantidpaymentstatus-get
      parameters:
      - in: path
        name: event-id
      - in: path
        name: registrant-id
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - Payment
      - Status
    put:
      summary: Update Payment Status
      description: Update Payment Status
      operationId: update-payment-status
      x-api-path-slug: usernameeventseventidregistrantsregistrantidpaymentstatus-put
      parameters:
      - in: query
        name: Content-Type
        description: Specifies Content Type
      - in: path
        name: event-id
      - in: path
        name: registrant-id
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - Payment
      - Status
---