---
swagger: "2.0"
x-collection-name: Zendesk
x-complete: 1
info:
  title: Sales Force Desk API
  description: build-deep-integrations-expose-your-service-to-influential-smb-customers-or-just-make-desk-com-work-the-way-you-want-
  version: v2
host: yoursite.desk.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /customers.{format}:
    get:
      summary: Get Customers
      description: Get customers.
      operationId: get-customers
      x-api-path-slug: customers-format-get
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Format
    post:
      summary: Create Customer
      description: Create customer.
      operationId: create-customer
      x-api-path-slug: customers-format-post
      parameters:
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Format
  /customers/{customer_id}/emails.{format}:
    post:
      summary: Create Customer Email
      description: Create customer email.
      operationId: create-customer-email
      x-api-path-slug: customerscustomer-idemails-format-post
      parameters:
      - in: path
        name: customer_id
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Customer
      - Emails
      - Format
  /customers/{customer_id}/emails/{id}.{format}:
    put:
      summary: Update Customer Email
      description: Update customer email.
      operationId: update-customer-email
      x-api-path-slug: customerscustomer-idemailsid-format-put
      parameters:
      - in: path
        name: customer_id
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Customer
      - Emails
      - Format
  /customers/{customer_id}/phones.{format}:
    post:
      summary: Create Customer Phone
      description: Create customer phone.
      operationId: create-customer-phone
      x-api-path-slug: customerscustomer-idphones-format-post
      parameters:
      - in: path
        name: customer_id
      - in: path
        name: format
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Customer
      - Phones
      - Format
  /customers/{customer_id}/phones/{id}.{format}:
    put:
      summary: Update Customer Phone
      description: Update customer phone.
      operationId: update-customer-phone
      x-api-path-slug: customerscustomer-idphonesid-format-put
      parameters:
      - in: path
        name: customer_id
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Customer
      - Phones
      - Format
  /customers/{id}.{format}:
    get:
      summary: Get Customer
      description: Get customer.
      operationId: get-customer
      x-api-path-slug: customersid-format-get
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Format
    put:
      summary: Update Customer
      description: Update customer.
      operationId: update-customer
      x-api-path-slug: customersid-format-put
      parameters:
      - in: path
        name: format
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Format
---