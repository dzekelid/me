---
name: Zendesk
x-slug: zendesk
description: Customer service software and support ticketing system by Zendesk. Cloud-based
  help desk solution used by more than 200,000 organizations worldwide. Free 30-day
  trial.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/283-zendesk.jpg
x-kinRank: "8"
x-alexaRank: "402"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/apis.md
specificationVersion: "0.14"
apis:
- name: Sales Force Desk API Get Customers
  x-api-slug: sales-force-desk-api
  description: Get customers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/283-zendesk.jpg
  humanURL: http://www.zendesk.com/
  baseURL: https://yoursite.desk.com//api/v2//customers.{format}
  tags: Customers,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customers-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customers-format-get-openapi.md
- name: Sales Force Desk API Create Customer
  x-api-slug: sales-force-desk-api
  description: Create customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/283-zendesk.jpg
  humanURL: http://www.zendesk.com/
  baseURL: https://yoursite.desk.com//api/v2//customers.{format}
  tags: Customers,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customers-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customers-format-post-openapi.md
- name: Sales Force Desk API Create Customer Email
  x-api-slug: sales-force-desk-api
  description: Create customer email.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/283-zendesk.jpg
  humanURL: http://www.zendesk.com/
  baseURL: https://yoursite.desk.com//api/v2//customers/{customer_id}/emails.{format}
  tags: Customers,Customer,Emails,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customerscustomer-idemails-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customerscustomer-idemails-format-post-openapi.md
- name: Sales Force Desk API Update Customer Email
  x-api-slug: sales-force-desk-api
  description: Update customer email.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/283-zendesk.jpg
  humanURL: http://www.zendesk.com/
  baseURL: https://yoursite.desk.com//api/v2//customers/{customer_id}/emails/{id}.{format}
  tags: Customers,Customer,Emails,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customerscustomer-idemailsid-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customerscustomer-idemailsid-format-put-openapi.md
- name: Sales Force Desk API Create Customer Phone
  x-api-slug: sales-force-desk-api
  description: Create customer phone.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/283-zendesk.jpg
  humanURL: http://www.zendesk.com/
  baseURL: https://yoursite.desk.com//api/v2//customers/{customer_id}/phones.{format}
  tags: Customers,Customer,Phones,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customerscustomer-idphones-format-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customerscustomer-idphones-format-post-openapi.md
- name: Sales Force Desk API Update Customer Phone
  x-api-slug: sales-force-desk-api
  description: Update customer phone.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/283-zendesk.jpg
  humanURL: http://www.zendesk.com/
  baseURL: https://yoursite.desk.com//api/v2//customers/{customer_id}/phones/{id}.{format}
  tags: Customers,Customer,Phones,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customerscustomer-idphonesid-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customerscustomer-idphonesid-format-put-openapi.md
- name: Sales Force Desk API Get Customer
  x-api-slug: sales-force-desk-api
  description: Get customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/283-zendesk.jpg
  humanURL: http://www.zendesk.com/
  baseURL: https://yoursite.desk.com//api/v2//customers/{id}.{format}
  tags: Customers,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customersid-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customersid-format-get-openapi.md
- name: Sales Force Desk API Update Customer
  x-api-slug: sales-force-desk-api
  description: Update customer.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/283-zendesk.jpg
  humanURL: http://www.zendesk.com/
  baseURL: https://yoursite.desk.com//api/v2//customers/{id}.{format}
  tags: Customers,Format
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customersid-format-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/customersid-format-put-openapi.md
- name: Sales Force Desk API
  x-api-slug: sales-force-desk-api
  description: Customer service software and support ticketing system by Zendesk.
    Cloud-based help desk solution used by more than 200,000 organizations worldwide.
    Free 30-day trial.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/283-zendesk.jpg
  humanURL: http://www.zendesk.com/
  baseURL: https://yoursite.desk.com//api/v2
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/zendesk/openapi.md
x-common:
- type: x-base
  url: https://zendesk.com/api/
- type: x-blog
  url: http://www.zendesk.com/blog
- type: x-blog-rss
  url: http://www.zendesk.com/feed
- type: x-crunchbase
  url: http://www.crunchbase.com/company/zendesk
- type: x-crunchbase
  url: https://crunchbase.com/organization/zendesk
- type: x-developer
  url: https://developer.zendesk.com/
- type: x-email
  url: support@zendesk.com
- type: x-email
  url: legal@zendesk.com
- type: x-email
  url: ip@zendesk.com
- type: x-email
  url: privacy@zendesk.com
- type: x-email
  url: press@zendesk.com
- type: x-faq
  url: https://gemini24.zendesk.com/hc/en-us
- type: x-github
  url: https://github.com/zendesk
- type: x-pricing
  url: https://www.zendesk.com/product/pricing/
- type: x-support
  url: https://genexus.zendesk.com/hc/en-us
- type: x-support
  url: https://gemini24.zendesk.com/hc/en-us/requests/new
- type: x-twitter
  url: https://twitter.com/zendesk
- type: x-website
  url: http://www.zendesk.com/
- type: x-website
  url: http://desk.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---