---
swagger: "2.0"
x-collection-name: Jumpseller
x-complete: 1
info:
  title: Jumpseller
  description: explore-all-our-endpoints-with-your-own-set-of-of-access-tokens--all-changes-affect-your-production-jumpseller-store-
  version: "1"
host: api.jumpseller.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /customer_categories.json:
    get:
      summary: Get Customer Categories
      description: Retrieve all customer categories..
      operationId: getCustomerCategories.json
      x-api-path-slug: customer-categories-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Json
    post:
      summary: Post Customer Categories
      description: Create a new customercategory..
      operationId: postCustomerCategories.json
      x-api-path-slug: customer-categories-json-post
      parameters:
      - in: body
        name: body
        description: CustomerCategory parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Json
  /customer_categories/{id}.json:
    delete:
      summary: Delete Customer Categories
      description: Delete an existing customercategory..
      operationId: deleteCustomerCategories.json
      x-api-path-slug: customer-categoriesid-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Json
    get:
      summary: Get Customer Categories
      description: Retrieve a single customercategory..
      operationId: getCustomerCategories.json
      x-api-path-slug: customer-categoriesid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Json
    put:
      summary: Put Customer Categories
      description: Update a customercategory..
      operationId: putCustomerCategories.json
      x-api-path-slug: customer-categoriesid-json-put
      parameters:
      - in: body
        name: body
        description: CustomerCategory parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Json
  /customer_categories/{id}/customers.json:
    delete:
      summary: Delete Customer Categories Customers
      description: Delete customers from an existing customercategory..
      operationId: deleteCustomerCategoriesCustomers.json
      x-api-path-slug: customer-categoriesidcustomers-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Customers
      - Json
    get:
      summary: Get Customer Categories Customers
      description: Retrieves the customers in a customercategory..
      operationId: getCustomerCategoriesCustomers.json
      x-api-path-slug: customer-categoriesidcustomers-json-get
      parameters:
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Customers
      - Json
    post:
      summary: Post Customer Categories Customers
      description: Adds customers to a customercategory..
      operationId: postCustomerCategoriesCustomers.json
      x-api-path-slug: customer-categoriesidcustomers-json-post
      parameters:
      - in: body
        name: body
        description: Customer parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the CustomerCategory
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customer
      - Categories
      - Id
      - Customers
      - Json
  /customers.json:
    get:
      summary: Get Customers
      description: Retrieve all customers..
      operationId: getCustomers.json
      x-api-path-slug: customers-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Json
    post:
      summary: Post Customers
      description: Create a new customer..
      operationId: postCustomers.json
      x-api-path-slug: customers-json-post
      parameters:
      - in: body
        name: body
        description: Customer parameters
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Json
  /customers/email/{email}.json:
    get:
      summary: Get Customers Email Email
      description: Retrieve a single customer..
      operationId: getCustomersEmailEmail.json
      x-api-path-slug: customersemailemail-json-get
      parameters:
      - in: path
        name: email
        description: Email of the Customer
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Email
      - Email
      - Json
  /customers/{id}.json:
    delete:
      summary: Delete Customers
      description: Delete an existing category..
      operationId: deleteCustomers.json
      x-api-path-slug: customersid-json-delete
      parameters:
      - in: path
        name: id
        description: Id of the Customer
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Id
      - Json
    get:
      summary: Get Customers
      description: Retrieve a single customer..
      operationId: getCustomers.json
      x-api-path-slug: customersid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the Customer
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Id
      - Json
    put:
      summary: Put Customers
      description: Update a new customer..
      operationId: putCustomers.json
      x-api-path-slug: customersid-json-put
      parameters:
      - in: body
        name: body
        description: Customer parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of the Customer
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Customers
      - Id
      - Json
  /payment_methods.json:
    get:
      summary: Get Payment Methods
      description: ""
      operationId: getPaymentMethods.json
      x-api-path-slug: payment-methods-json-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Payment
      - Methods
      - Json
  /payment_methods/{id}.json:
    get:
      summary: Get Payment Methods
      description: ""
      operationId: getPaymentMethods.json
      x-api-path-slug: payment-methodsid-json-get
      parameters:
      - in: path
        name: id
        description: Id of the Payment Method
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Payment
      - Methods
      - Id
      - Json
  /settings/{name}.json:
    get:
      summary: Get Settings Name
      description: ""
      operationId: getSettingsName.json
      x-api-path-slug: settingsname-json-get
      parameters:
      - in: path
        name: name
        description: Name of the Store Setting
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Name
      - Json
    put:
      summary: Put Settings Name
      description: ""
      operationId: putSettingsName.json
      x-api-path-slug: settingsname-json-put
      parameters:
      - in: body
        name: body
        description: Store Setting parameters to change
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: Name of the Store Setting
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Settings
      - Name
      - Json
---