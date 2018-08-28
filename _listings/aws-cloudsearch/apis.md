---
name: AWS CloudSearch
x-slug: aws-cloudsearch
description: Amazon CloudSearch is a managed service in the AWS Cloud that makes it
  simple and cost-effective to set up, manage, and scale a search solution for your
  website or application.Amazon CloudSearch supports 34 languages and popular search
  features such as highlighting, autocomplete, and geospatial search. For more information,
  see Benefits.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CloudSearch Define Analysis Scheme
  x-api-slug: aws-cloudsearch
  description: Configures an analysis scheme that can be applied to a text or text-array
    field to define language-specific text processing options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DefineAnalysisScheme
  tags: Analysis Scheme
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actiondefineanalysisscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actiondefineanalysisscheme-get-openapi.md
- name: AWS CloudSearch Delete Analysis Scheme
  x-api-slug: aws-cloudsearch
  description: Deletes an analysis scheme.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DeleteAnalysisScheme
  tags: Analysis Scheme
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actiondeleteanalysisscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actiondeleteanalysisscheme-get-openapi.md
- name: AWS CloudSearch Describe Analysis Schemes
  x-api-slug: aws-cloudsearch
  description: Gets the analysis schemes configured for a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DescribeAnalysisSchemes
  tags: Analysis Scheme
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actiondescribeanalysisschemes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actiondescribeanalysisschemes-get-openapi.md
- name: AWS CloudSearch Describe Scaling Parameters
  x-api-slug: aws-cloudsearch
  description: Gets the scaling parameters configured for a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DescribeScalingParameters
  tags: Scaling Parameters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actiondescribescalingparameters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actiondescribescalingparameters-get-openapi.md
- name: AWS CloudSearch Index Documents
  x-api-slug: aws-cloudsearch
  description: Tells the search domain to start indexing its documents using the latest
    indexing options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=IndexDocuments
  tags: Index Documents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actionindexdocuments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actionindexdocuments-get-openapi.md
- name: AWS CloudSearch Update Scaling Parameters
  x-api-slug: aws-cloudsearch
  description: Configures scaling parameters for a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=UpdateScalingParameters
  tags: Scaling Parameters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actionupdatescalingparameters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/actionupdatescalingparameters-get-openapi.md
- name: AWS CloudSearch
  x-api-slug: aws-cloudsearch
  description: Amazon CloudSearch is a managed service in the AWS Cloud that makes
    it simple and cost-effective to set up, manage, and scale a search solution for
    your website or application.Amazon CloudSearch supports 34 languages and popular
    search features such as highlighting, autocomplete, and geospatial search. For
    more information, see Benefits.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https:///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/aws-cloudsearch/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cloudsearch/latest/developerguide/cloudsearch-command-line-tools.html
- type: x-console
  url: https://console.aws.amazon.com/cloudsearch
- type: x-documentation
  url: http://docs.aws.amazon.com/cloudsearch/latest/developerguide/api-ref.html *
    hard to find
- type: x-faq
  url: https://aws.amazon.com/cloudsearch/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/cloudsearch/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/cloudsearch/pricing/
- type: x-testimonials
  url: https://aws.amazon.com/cloudsearch/testimonials/
- type: x-website
  url: https://aws.amazon.com/cloudsearch/
- type: x-whats-new
  url: https://aws.amazon.com/cloudsearch/whats-new/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---