---
name: Datadog
x-slug: datadog
description: See inside any stack, any app, at any scale, anywhere.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
x-kinRank: "8"
x-alexaRank: "13593"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/apis.md
specificationVersion: "0.14"
apis:
- name: DataDog API Get Metrics
  x-api-slug: datadog-api
  description: Get the list of actively reporting metrics from a given time until
    now. This endpoint is not available in the Python and Ruby libraries.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1///metrics
  tags: Monitoring,Metrics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/metrics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/metrics-get-openapi.md
- name: DataDog API Add Downtime
  x-api-slug: datadog-api
  description: Schedule monitor downtime
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1///downtime
  tags: Monitoring,Downtime
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/downtime-post-openapi.md
- name: DataDog API Put Downtime Downtime
  x-api-slug: datadog-api
  description: Update monitor downtime
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1///downtime/:downtime_id
  tags: Monitoring,Downtime, Downtime
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/downtimedowntime-id-put-openapi.md
- name: DataDog API Delete Downtime Downtime
  x-api-slug: datadog-api
  description: DELETE downtime downtime
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1///downtime/:downtime_id
  tags: Monitoring,Downtime, Downtime
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/downtimedowntime-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/downtimedowntime-id-delete-openapi.md
- name: DataDog API Get Downtime Downtime
  x-api-slug: datadog-api
  description: Get a monitor downtime
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1///downtime/:downtime_id
  tags: Monitoring,Downtime, Downtime
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/downtimedowntime-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/downtimedowntime-id-get-openapi.md
- name: DataDog API Get Downtime
  x-api-slug: datadog-api
  description: Get all monitor downtimes
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1///downtime
  tags: Monitoring,Downtime
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/downtime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/downtime-get-openapi.md
- name: DataDog API Get Tags Hosts Host Name
  x-api-slug: datadog-api
  description: Return the list of tags that apply to a given host.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1///tags/hosts/:host_name
  tags: Monitoring,Tags, Hosts, Host, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/tagshostshost-name-get-openapi.md
- name: DataDog API Add Tags Hosts Host Name
  x-api-slug: datadog-api
  description: This end point allows you to add tags to a host.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1///tags/hosts/:host_name
  tags: Monitoring,Tags, Hosts, Host, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/tagshostshost-name-post-openapi.md
- name: DataDog API Put Tags Hosts Host Name
  x-api-slug: datadog-api
  description: This end point allows you to update all tags for a given host.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1///tags/hosts/:host_name
  tags: Monitoring,Tags, Hosts, Host, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/tagshostshost-name-put-openapi.md
- name: DataDog API Delete Tags Hosts Host Name
  x-api-slug: datadog-api
  description: This end point allows you to remove all tags for a given host.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1///tags/hosts/:host_name
  tags: Monitoring,Tags, Hosts, Host, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/tagshostshost-name-delete-openapi.md
- name: DataDog API Add Comments
  x-api-slug: datadog-api
  description: |-
    Comments are essentially special forms of events that
              appear in the stream. They can start a new discussion thread or
              optionally, reply in another thread.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1//comments
  tags: Monitoring,Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/comments-post-openapi.md
- name: DataDog API Put Comments Comment
  x-api-slug: datadog-api
  description: PUT comments comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1//comments/:comment_id
  tags: Monitoring,Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/commentscomment-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/commentscomment-id-put-openapi.md
- name: DataDog API Delete Comments Comment
  x-api-slug: datadog-api
  description: DELETE comments comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1//comments/:comment_id
  tags: Monitoring,Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/commentscomment-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/commentscomment-id-delete-openapi.md
- name: DataDog API
  x-api-slug: datadog-api
  description: See inside any stack, any app, at any scale, anywhere.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/22961-datadog.jpg
  humanURL: https://www.datadoghq.com/
  baseURL: https:///api/v1/
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/datadog/openapi.md
x-common:
- type: x-blog
  url: https://www.datadoghq.com/blog/
- type: x-blog-rss
  url: https://www.datadoghq.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/datadog
- type: x-email
  url: info@datadoghq.com
- type: x-email
  url: help@datadoghq.com
- type: x-email
  url: legalcompliance@datadoghq.com
- type: x-email
  url: legal@datadoghq.com
- type: x-email
  url: iwant@datadoghq.com
- type: x-github
  url: https://github.com/datadog
- type: x-twitter
  url: https://twitter.com/datadoghq
- type: x-integrations
  url: https://www.datadoghq.com/product/integrations/
- type: x-pricing
  url: https://www.datadoghq.com/pricing/
- type: x-security
  url: https://www.datadoghq.com/security/
- type: x-website
  url: https://www.datadoghq.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---