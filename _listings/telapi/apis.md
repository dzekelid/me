---
name: TelAPI
x-slug: telapi
description: Zang offers business communications tools & voice app development platforms
  that bring innovation and ease to unified communications & collaboration solutions.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
x-kinRank: "9"
x-alexaRank: "1071695"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/telapi/apis.md
specificationVersion: "0.14"
apis:
- name: hetras Hotel API Version 0 Get the setup of the daily rates for a specific
    rateplan and a defined timeperiod.
  x-api-slug: hetras-hotel-api-version-0
  description: "With this call you can read the daily rates setup including the cancellation
    policy and minimum guarantee per day for the\r\n            specified rateplan.
    You can specify a timeperiod to read the daily rates for. The rateplan needs to
    be active for at least\r\n            one business day in the defined time period
    and have rates loaded."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
  humanURL: http://www.telapi.com
  baseURL: https://api.hetras-certification.net////api/hotel/v0/hotels/{hotelId}/rateplans/{rateplanCode}/rates
  tags: Setup,Of,Daily,Ratesa,Specific,Rateplan,Defined,Timeperiod
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/telapi/apihotelv0hotelshotelidrateplansrateplancoderates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/telapi/apihotelv0hotelshotelidrateplansrateplancoderates-get-openapi.md
- name: hetras Hotel API Version 0 Partially update a rate of the specified rateplan
    for the defined time period.
  x-api-slug: hetras-hotel-api-version-0
  description: "The hetras API is using this Patch Specification\r\n            to
    partially update an existing resource. Currently this call only allows to set
    the base price for non-derived rateplans if the rateplan\r\n            is active
    and already loaded for the specified time period.\r\n            \r\n            A
    request example:\r\n            [\r\n              {\r\n                \"op\":
    \"replace\", \"path\": \"/base_price\", \"value\": 120.00\r\n              }\r\n
    \           ]\r\n            \r\n            For more details on how the API responds
    to errors please check our documentation on \r\n            Error Handling."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
  humanURL: http://www.telapi.com
  baseURL: https://api.hetras-certification.net////api/hotel/v0/hotels/{hotelId}/rateplans/{rateplanCode}/rates
  tags: Partially,Update,Rate,Of,Specified,Rateplanthe,Defined,Time,Period
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/telapi/apihotelv0hotelshotelidrateplansrateplancoderates-patch-openapi.md
- name: hetras Hotel API Version 0 Get the count of all active and loaded daily rates
    for the defined rateplan in a specified time period.
  x-api-slug: hetras-hotel-api-version-0
  description: Get the count of all active and loaded daily rates for the defined
    rateplan in a specified time period..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
  humanURL: http://www.telapi.com
  baseURL: https://api.hetras-certification.net////api/hotel/v0/hotels/{hotelId}/rateplans/{rateplanCode}/rates/$count
  tags: Count,Of,,Active,Loaded,Daily,Ratesthe,Defined,Rateplan,In,Specified,Time,Period
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/telapi/apihotelv0hotelshotelidrateplansrateplancoderatescount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/telapi/apihotelv0hotelshotelidrateplansrateplancoderatescount-get-openapi.md
- name: hetras Hotel API Version 0
  x-api-slug: hetras-hotel-api-version-0
  description: Zang offers business communications tools & voice app development platforms
    that bring innovation and ease to unified communications & collaboration solutions.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1176-telapi.jpg
  humanURL: http://www.telapi.com
  baseURL: https://api.hetras-certification.net//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/telapi/openapi.md
x-common:
- type: x-base
  url: https://api.telapi.com
- type: x-blog
  url: http://www.TelAPI.com/blog/
- type: x-blog-rss
  url: http://www.telapi.com/blog/feed/
- type: x-contact-form
  url: http://www.telapi.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/telapi
- type: x-crunchbase
  url: https://crunchbase.com/organization/zang-io
- type: x-developer
  url: http://www.telapi.com/docs/
- type: x-email
  url: support@telapi.com
- type: x-github
  url: https://github.com/TelAPI
- type: x-pricing
  url: http://www.telapi.com/pricing
- type: x-privacy
  url: https://www.telapi.com/legal/privacy-policy
- type: x-selfservice-registration
  url: https://www.telapi.com/signup
- type: x-status
  url: http://status.telapi.com/
- type: x-terms-of-service
  url: https://www.telapi.com/legal/tos
- type: x-twitter
  url: https://twitter.com/TelAPI
- type: x-twitter
  url: https://twitter.com/Zang_io
- type: x-website
  url: http://www.telapi.com
- type: x-website
  url: http://telapi.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---