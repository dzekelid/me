---
name: NetLicensing
x-slug: netlicensing
description: Labs64 NetLicensing is a first-class solution in the Licensing-as-a-Service
  (LaaS) sector. Based on open standards, it provides a cost effective, integrated
  and scalable platform for software vendors and developers who want to concentrate
  on their product&rsquo;s core functionality instead of spending resources on developing
  an own license management software.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28466-labs64-net-licensing-restful-api-test-center.jpg
x-kinRank: "7"
x-alexaRank: "1080577"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/netlicensing/apis.md
specificationVersion: "0.14"
apis:
- name: NetLicensing Payment Methods list
  x-api-slug: netlicensing
  description: Return a list of all payment methods for the current vendor
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28466-labs64-net-licensing-restful-api-test-center.jpg
  humanURL: http://netlicensing.io
  baseURL: https://go.netlicensing.io//core/v2/rest//paymentmethod
  tags: Paymentmethod
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/netlicensing/paymentmethod-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/netlicensing/paymentmethod-get-openapi.md
- name: NetLicensing Get payment method
  x-api-slug: netlicensing
  description: Return a payment method info by paymentMethodNumber
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28466-labs64-net-licensing-restful-api-test-center.jpg
  humanURL: http://netlicensing.io
  baseURL: https://go.netlicensing.io//core/v2/rest//paymentmethod/{paymentMethodNumber}
  tags: Paymentmethod,PaymentMethodNumber
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/netlicensing/paymentmethodpaymentmethodnumber-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/netlicensing/paymentmethodpaymentmethodnumber-get-openapi.md
- name: NetLicensing Update payment method
  x-api-slug: netlicensing
  description: Sets the provided properties to a payment method. Return an updated
    payment method
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28466-labs64-net-licensing-restful-api-test-center.jpg
  humanURL: http://netlicensing.io
  baseURL: https://go.netlicensing.io//core/v2/rest//paymentmethod/{paymentMethodNumber}
  tags: Paymentmethod,PaymentMethodNumber
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/netlicensing/paymentmethodpaymentmethodnumber-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/netlicensing/paymentmethodpaymentmethodnumber-post-openapi.md
- name: NetLicensing
  x-api-slug: netlicensing
  description: Labs64 NetLicensing is a first-class solution in the Licensing-as-a-Service
    (LaaS) sector. Based on open standards, it provides a cost effective, integrated
    and scalable platform for software vendors and developers who want to concentrate
    on their product&rsquo;s core functionality instead of spending resources on developing
    an own license management software.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28466-labs64-net-licensing-restful-api-test-center.jpg
  humanURL: http://netlicensing.io
  baseURL: https://go.netlicensing.io//core/v2/rest
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/netlicensing/openapi.md
x-common:
- type: x-getting-started
  url: https://netlicensing.io/getting-started/
- type: x-pricing
  url: https://netlicensing.io/pricing/
- type: x-twitter
  url: https://twitter.com/netlicensing
- type: x-website
  url: http://netlicensing.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---