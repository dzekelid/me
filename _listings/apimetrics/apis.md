---
name: APImetrics
x-slug: apimetrics
description: API performance monitoring, Cloud Service, SLA monitoring and analysis
  that gives you answers, not excuses. Find out how today.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
x-kinRank: "10"
x-alexaRank: "2264063"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apimetrics/apis.md
specificationVersion: "0.14"
apis:
- name: APIMetrics List all Deployment
  x-api-slug: apimetrics
  description: List all Deployment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/
  tags: Monitoring,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apimetrics/deployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apimetrics/deployments-get-openapi.md
- name: APIMetrics Create a new Deployment
  x-api-slug: apimetrics
  description: Create a new Deployment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/
  tags: Monitoring,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apimetrics/deployments-post-openapi.md
- name: APIMetrics Get all Deployments for an API Call
  x-api-slug: apimetrics
  description: Get all Deployments for an API Call
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/call/{call_id}/
  tags: Monitoring,Deployments, Call, Call
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apimetrics/deploymentscallcall-id-get-openapi.md
- name: APIMetrics Get all Deployments for a Workflow
  x-api-slug: apimetrics
  description: Get all Deployments for a Workflow
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/workflow/{workflow_id}
  tags: Monitoring,Deployments, Workflow, Workflow
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apimetrics/deploymentsworkflowworkflow-id-get-openapi.md
- name: APIMetrics Delete a Deployment
  x-api-slug: apimetrics
  description: Delete a Deployment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/{id}/
  tags: Monitoring,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apimetrics/deploymentsid-delete-openapi.md
- name: APIMetrics Get an existing Deployment
  x-api-slug: apimetrics
  description: Get an existing Deployment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/{id}/
  tags: Monitoring,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apimetrics/deploymentsid-get-openapi.md
- name: APIMetrics Update an existing Deployment
  x-api-slug: apimetrics
  description: Update an existing Deployment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https://///deployments/{id}/
  tags: Monitoring,Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apimetrics/deploymentsid-put-openapi.md
- name: APIMetrics
  x-api-slug: apimetrics
  description: API performance monitoring, Cloud Service, SLA monitoring and analysis
    that gives you answers, not excuses. Find out how today.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1916-apimetrics.jpg
  humanURL: http://apimetrics.io
  baseURL: https:///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apimetrics/openapi.md
x-common:
- type: x-base-url
  url: https://client.apimetrics.io
- type: x-blog
  url: http://apimetrics.io/blog/
- type: x-blog-rss
  url: http://apimetrics.io/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/apimetrics
- type: x-developer
  url: https://apimetrics.readme.io/
- type: x-github
  url: https://github.com/APImetrics
- type: x-pricing
  url: http://apimetrics.io/
- type: x-privacy
  url: http://apimetrics.io/privacy
- type: x-terms-of-service
  url: http://apimetrics.io/tos
- type: x-twitter
  url: https://twitter.com/apimetricstats
- type: x-website
  url: http://apimetrics.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---