---
name: taxamo
x-slug: taxamo
description: We understand that the world of EU VAT compliance can be quite complex.
  That is why we have created a simple solution that eases the compliance burden for
  the developers, and the owners, of e-commerce websites across the globe.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Taxamo_logo-copy.jpg
x-kinRank: "8"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apis.md
specificationVersion: "0.14"
apis:
- name: Taxamo Calculate Domestic Summary
  x-api-slug: taxamo
  description: Calculate domestic summary.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Taxamo_logo-copy.jpg
  humanURL: http://www.taxamo.com/
  baseURL: https://api.taxamo.com////api/v1/reports/domestic/summary
  tags: Calculate,Domestic,Summary
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1reportsdomesticsummary-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1reportsdomesticsummary-get-openapi.md
- name: Taxamo Fetch Settlement
  x-api-slug: taxamo
  description: Fetch settlement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Taxamo_logo-copy.jpg
  humanURL: http://www.taxamo.com/
  baseURL: https://api.taxamo.com////api/v1/settlement/{quarter}
  tags: Fetch,Settlement
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1settlementquarter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1settlementquarter-get-openapi.md
- name: Taxamo Settlement By Country
  x-api-slug: taxamo
  description: Settlement by country.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Taxamo_logo-copy.jpg
  humanURL: http://www.taxamo.com/
  baseURL: https://api.taxamo.com////api/v1/stats/settlement/by_country
  tags: Settlement,Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1statssettlementby-country-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1statssettlementby-country-get-openapi.md
- name: Taxamo Settlement By Tax Type
  x-api-slug: taxamo
  description: Settlement by tax type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Taxamo_logo-copy.jpg
  humanURL: http://www.taxamo.com/
  baseURL: https://api.taxamo.com////api/v1/stats/settlement/by_taxation_type
  tags: Settlement,Tax,Type
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1statssettlementby-taxation-type-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1statssettlementby-taxation-type-get-openapi.md
- name: Taxamo Settlement Stats Over Time
  x-api-slug: taxamo
  description: Settlement stats over time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Taxamo_logo-copy.jpg
  humanURL: http://www.taxamo.com/
  baseURL: https://api.taxamo.com////api/v1/stats/settlement/daily
  tags: Settlement,Stats,Over,Time
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1statssettlementdaily-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1statssettlementdaily-get-openapi.md
- name: Taxamo Settlement By Country
  x-api-slug: taxamo
  description: Settlement by country.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Taxamo_logo-copy.jpg
  humanURL: http://www.taxamo.com/
  baseURL: https://api.taxamo.com////api/v1/stats/transactions/by_country
  tags: Settlement,Country
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1statstransactionsby-country-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1statstransactionsby-country-get-openapi.md
- name: Taxamo List Payments
  x-api-slug: taxamo
  description: List payments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Taxamo_logo-copy.jpg
  humanURL: http://www.taxamo.com/
  baseURL: https://api.taxamo.com////api/v1/transactions/{key}/payments
  tags: List,Payments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1transactionskeypayments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1transactionskeypayments-get-openapi.md
- name: Taxamo Register A Payment
  x-api-slug: taxamo
  description: Register a payment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Taxamo_logo-copy.jpg
  humanURL: http://www.taxamo.com/
  baseURL: https://api.taxamo.com////api/v1/transactions/{key}/payments
  tags: Register,Payment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1transactionskeypayments-post-openapi.md
- name: Taxamo Capture Payment
  x-api-slug: taxamo
  description: Capture payment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Taxamo_logo-copy.jpg
  humanURL: http://www.taxamo.com/
  baseURL: https://api.taxamo.com////api/v1/transactions/{key}/payments/capture
  tags: Capture,Payment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/apiv1transactionskeypaymentscapture-post-openapi.md
- name: Taxamo
  x-api-slug: taxamo
  description: We understand that the world of EU VAT compliance can be quite complex.
    That is why we have created a simple solution that eases the compliance burden
    for the developers, and the owners, of e-commerce websites across the globe.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Taxamo_logo-copy.jpg
  humanURL: http://www.taxamo.com/
  baseURL: https://api.taxamo.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/taxamo/openapi.md
x-common:
- type: x-documentation
  url: https://api.taxamo.com/swagger/ui/index.html
- type: x-github
  url: https://github.com/taxamo
- type: x-pricing
  url: http://www.taxamo.com/pricing/
- type: x-twitter
  url: https://twitter.com/taxamo
- type: x-website
  url: http://www.taxamo.com/
- type: x-website
  url: http://taxamo.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---