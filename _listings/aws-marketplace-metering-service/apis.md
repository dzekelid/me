---
name: AWS Marketplace Metering Service
x-slug: aws-marketplace-metering-service
description: AWS Marketplace provides a new sales channel for ISVs and Consulting
  Partners to sell their solutions to AWS customers. We make it easy for customers
  to find, buy, deploy and manage software solutions, including SaaS, in a matter
  of minutes. AWS Marketplace sellers can use this API to submit usage data for custom
  usage dimensions.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-marketplace-icon.jpg
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-marketplace-metering-service/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Marketplace Metering Service API Meter Usage
  x-api-slug: aws-marketplace-metering-service-api
  description: API to emit metering records.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-marketplace-icon.jpg
  humanURL: https://aws.amazon.com/marketplace/
  baseURL: ://///?Action=MeterUsage
  tags: Meter Usage
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-marketplace-metering-service/actionmeterusage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-marketplace-metering-service/actionmeterusage-get-openapi.md
- name: AWS Marketplace Metering Service API
  x-api-slug: aws-marketplace-metering-service-api
  description: AWS Marketplace provides a new sales channel for ISVs and Consulting
    Partners to sell their solutions to AWS customers. We make it easy for customers
    to find, buy, deploy and manage software solutions, including SaaS, in a matter
    of minutes. AWS Marketplace sellers can use this API to submit usage data for
    custom usage dimensions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/aws-marketplace-icon.jpg
  humanURL: https://aws.amazon.com/marketplace/
  baseURL: :///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-marketplace-metering-service/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/marketplacemetering/latest/APIReference/API_MeterUsage.html
- type: x-website
  url: https://aws.amazon.com/marketplace/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---