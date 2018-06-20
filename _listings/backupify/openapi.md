---
swagger: "2.0"
x-collection-name: Backupify
x-complete: 1
info:
  title: Backupify
  description: the-backupify-api-allows-you-to-integrate-the-leading-saas-backup-solution-into-your-software-making-it-easy-to-give-your-customers-the-data-protection-they-need--
  version: 1.0.0
host: api.backupify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/authenticate_customer:
    get:
      summary: A simple method to test authentication of a customer access token.
      description: A simple method to test authentication of a customer access token..
      operationId: getV1AuthenticateCustomer
      x-api-path-slug: v1authenticate-customer-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted for customer
      responses:
        200:
          description: OK
      tags:
      - V1
      - Authenticate
      - Customer
  /v1/backup_instances/{backup_instance_id}/endpoints/{endpoint_name}:
    get:
      summary: Retrieve a specific endpoint by name for the specified backup_instance
      description: You can only retrieve endpoints for backup_instances you have access
        to
      operationId: getV1BackupInstancesBackupInstanceEndpointsEndpointName
      x-api-path-slug: v1backup-instancesbackup-instance-idendpointsendpoint-name-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: backup_instance_id
        description: ID of the backup_instance to retrieve an endpoint for
      - in: path
        name: endpoint_name
        description: The name of the endpoint to retrieve as defined by the backup_definition
          of the specified backup_instance
      responses:
        200:
          description: OK
      tags:
      - V1
      - Backup
      - Instances
      - Backup
      - Instance
      - Id
      - Endpoints
      - Endpoint
      - Name
  /v1/backup_instances/{backup_instance_id}/endpoints/{endpoint_name}/records:
    get:
      summary: Retrieve a list of records stored for the specified endpoint and backup_instance
      description: You can only retrieve records for endpoints that belong to backup_instances
        you have access to. Records are returned in ascending order (by id), with
        a default of 20 per page. Links to the next, previous, first, and last pages
        can be found in the response headers.
      operationId: getV1BackupInstancesBackupInstanceEndpointsEndpointNameRecords
      x-api-path-slug: v1backup-instancesbackup-instance-idendpointsendpoint-namerecords-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: backup_instance_id
        description: ID of the backup_instance to retrieve an endpoint for
      - in: path
        name: endpoint_name
        description: ID of the endpoint to retrieve records for
      responses:
        200:
          description: OK
      tags:
      - V1
      - Backup
      - Instances
      - Backup
      - Instance
      - Id
      - Endpoints
      - Endpoint
      - Name
      - Records
  /v1/backup_instances/{backup_instance_id}/endpoints/{endpoint_name}/records/{record_id}:
    get:
      summary: Retrieve a specific record by id for the specified endpoint and backup_instance
      description: You can only retrieve records for endpoints of backup_instances
        you have access to
      operationId: getV1BackupInstancesBackupInstanceEndpointsEndpointNameRecordsRecord
      x-api-path-slug: v1backup-instancesbackup-instance-idendpointsendpoint-namerecordsrecord-id-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: backup_instance_id
        description: ID of the backup_instance to retrieve an endpoint for
      - in: path
        name: endpoint_name
        description: The name of the endpoint to retrieve the record from
      - in: path
        name: record_id
        description: The id of the endpoint record to retrieve
      responses:
        200:
          description: OK
      tags:
      - V1
      - Backup
      - Instances
      - Backup
      - Instance
      - Id
      - Endpoints
      - Endpoint
      - Name
      - Records
      - Record
      - Id
  /v1/backup_instances/{backup_instance_id}/endpoints/{endpoint_name}/records/{record_id}/blob:
    get:
      summary: Retrieve the blob associated with the specified record for the specified
        endpoint and backup_instance
      description: Retrieve the blob associated with the specified record for the
        specified endpoint and backup_instance.
      operationId: getV1BackupInstancesBackupInstanceEndpointsEndpointNameRecordsRecordBlob
      x-api-path-slug: v1backup-instancesbackup-instance-idendpointsendpoint-namerecordsrecord-idblob-get
      parameters:
      - in: header
        name: Access-Token
        description: Access Token granted from client credentials authorizing vendor
          to perform action
      - in: path
        name: backup_instance_id
        description: ID of the backup_instance to retrieve an endpoint for
      - in: path
        name: endpoint_name
        description: The name of the endpoint to retrieve the record from
      - in: path
        name: record_id
        description: The id of the endpoint record the blob belongs to
      responses:
        200:
          description: OK
      tags:
      - V1
      - Backup
      - Instances
      - Backup
      - Instance
      - Id
      - Endpoints
      - Endpoint
      - Name
      - Records
      - Record
      - Id
      - Blob
  /v1/customers:
    get:
      summary: Retrieve a list of customers associated with the authenticated vendor
      description: Requires Access Token granted from client credentials. Records
        are returned in ascending order (by id), with a default of 20 per page. Links
        to the next, previous, first, and last pages can be found in the response
        headers.
      operationId: getV1Customers
      x-api-path-slug: v1customers-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      responses:
        200:
          description: OK
      tags:
      - V1
      - Customers
    post:
      summary: Create a new customer instance identified by the given {name} identifier
      description: Create a new customer instance identified by the given {name} identifier.
      operationId: postV1Customers
      x-api-path-slug: v1customers-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: formData
        name: customer[email]
        description: Email address associated with the customer
      - in: formData
        name: customer[name]
        description: Vendor provided ID uniquely identifying customer
      responses:
        200:
          description: OK
      tags:
      - V1
      - Customers
  /v1/customers/{customer_id}:
    get:
      summary: Retrieves the customer identified by customer_id
      description: Requires Access Token granted from client credentials.
      operationId: getV1CustomersCustomer
      x-api-path-slug: v1customerscustomer-id-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: customer_id
        description: ID of the customer to retrieve
      responses:
        200:
          description: OK
      tags:
      - V1
      - Customers
      - Customer
      - Id
    put:
      summary: Update a customer instance identified by the given customer_id
      description: Update a customer instance identified by the given customer_id.
      operationId: putV1CustomersCustomer
      x-api-path-slug: v1customerscustomer-id-put
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: formData
        name: customer[name]
        description: Vendor provided ID uniquely identifying customer
      - in: path
        name: customer_id
        description: ID of the customer to modify
      responses:
        200:
          description: OK
      tags:
      - V1
      - Customers
      - Customer
      - Id
  /v1/customers/{customer_id}/backup_instances:
    get:
      summary: Retrieves a list of backup_instances associated with the specified
        customer
      description: It is only possible to retrieve backup_instances for customers
        you are authorized to access. Records are returned in ascending order (by
        id), with a default of 20 per page. Links to the next, previous, first, and
        last pages can be found in the response headers.
      operationId: getV1CustomersCustomerBackupInstances
      x-api-path-slug: v1customerscustomer-idbackup-instances-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      - in: path
        name: customer_id
        description: ID of the customer to retrieve backup_instances for
      responses:
        200:
          description: OK
      tags:
      - V1
      - Customers
      - Customer
      - Id
      - Backup
      - Instances
  /v1/vendors/me:
    get:
      summary: Provides information about the currently authenticated vendor user
      description: Provides information about the currently authenticated vendor user.
      operationId: getV1VendorsMe
      x-api-path-slug: v1vendorsme-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer Access Token granted from client credentials authorizing
          vendor to perform action
      responses:
        200:
          description: OK
      tags:
      - V1
      - Vendors
      - Me
---