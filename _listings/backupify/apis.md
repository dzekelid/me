---
name: Backupify
x-slug: backupify
description: ""
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/apis.md
specificationVersion: "0.14"
apis:
- name: Backupify A simple method to test authentication of a customer access token.
  x-api-slug: backupify
  description: A simple method to test authentication of a customer access token..
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/authenticate_customer
  tags: V1,Authenticate,Customer
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1authenticate-customer-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1authenticate-customer-get-openapi.md
- name: Backupify Retrieve a specific endpoint by name for the specified backup_instance
  x-api-slug: backupify
  description: You can only retrieve endpoints for backup_instances you have access
    to
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_instances/{backup_instance_id}/endpoints/{endpoint_name}
  tags: V1,Backup,Instances,Backup,Instance,Id,Endpoints,Endpoint,Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1backup-instancesbackup-instance-idendpointsendpoint-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1backup-instancesbackup-instance-idendpointsendpoint-name-get-openapi.md
- name: Backupify Retrieve a list of records stored for the specified endpoint and
    backup_instance
  x-api-slug: backupify
  description: You can only retrieve records for endpoints that belong to backup_instances
    you have access to. Records are returned in ascending order (by id), with a default
    of 20 per page. Links to the next, previous, first, and last pages can be found
    in the response headers.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_instances/{backup_instance_id}/endpoints/{endpoint_name}/records
  tags: V1,Backup,Instances,Backup,Instance,Id,Endpoints,Endpoint,Name,Records
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1backup-instancesbackup-instance-idendpointsendpoint-namerecords-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1backup-instancesbackup-instance-idendpointsendpoint-namerecords-get-openapi.md
- name: Backupify Retrieve a specific record by id for the specified endpoint and
    backup_instance
  x-api-slug: backupify
  description: You can only retrieve records for endpoints of backup_instances you
    have access to
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_instances/{backup_instance_id}/endpoints/{endpoint_name}/records/{record_id}
  tags: V1,Backup,Instances,Backup,Instance,Id,Endpoints,Endpoint,Name,Records,Record,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1backup-instancesbackup-instance-idendpointsendpoint-namerecordsrecord-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1backup-instancesbackup-instance-idendpointsendpoint-namerecordsrecord-id-get-openapi.md
- name: Backupify Retrieve the blob associated with the specified record for the specified
    endpoint and backup_instance
  x-api-slug: backupify
  description: Retrieve the blob associated with the specified record for the specified
    endpoint and backup_instance.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/backup_instances/{backup_instance_id}/endpoints/{endpoint_name}/records/{record_id}/blob
  tags: V1,Backup,Instances,Backup,Instance,Id,Endpoints,Endpoint,Name,Records,Record,Id,Blob
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1backup-instancesbackup-instance-idendpointsendpoint-namerecordsrecord-idblob-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1backup-instancesbackup-instance-idendpointsendpoint-namerecordsrecord-idblob-get-openapi.md
- name: Backupify Retrieve a list of customers associated with the authenticated vendor
  x-api-slug: backupify
  description: Requires Access Token granted from client credentials. Records are
    returned in ascending order (by id), with a default of 20 per page. Links to the
    next, previous, first, and last pages can be found in the response headers.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/customers
  tags: V1,Customers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1customers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1customers-get-openapi.md
- name: Backupify Create a new customer instance identified by the given {name} identifier
  x-api-slug: backupify
  description: Create a new customer instance identified by the given {name} identifier.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/customers
  tags: V1,Customers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1customers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1customers-post-openapi.md
- name: Backupify Retrieves the customer identified by customer_id
  x-api-slug: backupify
  description: Requires Access Token granted from client credentials.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/customers/{customer_id}
  tags: V1,Customers,Customer,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1customerscustomer-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1customerscustomer-id-get-openapi.md
- name: Backupify Update a customer instance identified by the given customer_id
  x-api-slug: backupify
  description: Update a customer instance identified by the given customer_id.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/customers/{customer_id}
  tags: V1,Customers,Customer,Id
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1customerscustomer-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1customerscustomer-id-put-openapi.md
- name: Backupify Retrieves a list of backup_instances associated with the specified
    customer
  x-api-slug: backupify
  description: It is only possible to retrieve backup_instances for customers you
    are authorized to access. Records are returned in ascending order (by id), with
    a default of 20 per page. Links to the next, previous, first, and last pages can
    be found in the response headers.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/customers/{customer_id}/backup_instances
  tags: V1,Customers,Customer,Id,Backup,Instances
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1customerscustomer-idbackup-instances-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1customerscustomer-idbackup-instances-get-openapi.md
- name: Backupify Provides information about the currently authenticated vendor user
  x-api-slug: backupify
  description: Provides information about the currently authenticated vendor user.
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com////v1/vendors/me
  tags: V1,Vendors,Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1vendorsme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/v1vendorsme-get-openapi.md
- name: Backupify
  x-api-slug: backupify
  description: 'Backupify is a backup service for SaaS accounts. Backupify can help
    users backup their SaaS accounts and restore if and when needed. Backupify offers
    a developers program for developers to access and integrate the functionality
    of Backupify with other applications. Public documentation is not available; interested
    developers should sign up here for more information on the developers program:
    https://www.backupify.com/solutions/developers or email developerprogram@backupify.com.'
  image: ""
  humanURL: http://backupify.com
  baseURL: https://api.backupify.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/backupify/openapi.md
x-common:
- type: x-blog
  url: https://www.backupify.com/blog
- type: x-website
  url: http://backupify.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---