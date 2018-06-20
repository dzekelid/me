---
name: AWS Service Catalog
x-slug: aws-service-catalog
description: AWS Service Catalog allows organizations to create and manage catalogs
  of IT services that are approved for use on AWS. These IT services can include everything
  from virtual machine images, servers, software, and databases to complete multi-tier
  application architectures. AWS Service Catalog allows you to centrally manage commonly
  deployed IT services, and helps you achieve consistent governance and meet your
  compliance requirements, while enabling users to quickly deploy only the approved
  IT services they need.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-service-catalog/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Service Catalog API Describe Provisioning Parameters
  x-api-slug: aws-service-catalog-api
  description: |-
    Provides information about parameters required to provision a specified product in a
             specified manner.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: ://///?Action=DescribeProvisioningParameters
  tags: 'Provisioning Parameters '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-service-catalog/actiondescribeprovisioningparameters-get-openapi.md
- name: AWS Service Catalog API
  x-api-slug: aws-service-catalog-api
  description: AWS Service Catalog allows organizations to create and manage catalogs
    of IT services that are approved for use on AWS. These IT services can include
    everything from virtual machine images, servers, software, and databases to complete
    multi-tier application architectures. AWS Service Catalog allows you to centrally
    manage commonly deployed IT services, and helps you achieve consistent governance
    and meet your compliance requirements, while enabling users to quickly deploy
    only the approved IT services they need.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSServiceCatalog.png
  humanURL: https://aws.amazon.com/servicecatalog/
  baseURL: :///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-service-catalog/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/servicecatalog/latest/dg/service-catalog-api-overview.html
- type: x-faq
  url: https://aws.amazon.com/servicecatalog/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/servicecatalog/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/servicecatalog/pricing/
- type: x-website
  url: https://aws.amazon.com/servicecatalog/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---