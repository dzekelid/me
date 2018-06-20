---
name: Google Cloud Deployment Manager
x-slug: google-cloud-deployment-manager
description: Google Cloud Deployment Manager allows you to specify all the resources
  needed for your application in a declarative format using yaml. You can also use
  Python or Jinja2 templates to parameterize the configuration and allow reuse of
  common deployment paradigms such as a load balanced, auto-scaled instance group.
  Treat your configuration as code and perform repeatable deployments.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-cloud-deployment-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Deployment Manager Get Deployments
  x-api-slug: google-cloud-deployment-manager
  description: Lists all deployments for a given project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments
  tags: Deployment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-cloud-deployment-manager/projectglobaldeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-cloud-deployment-manager/projectglobaldeployments-get-openapi.md
- name: Google Cloud Deployment Manager Create Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Creates a deployment and all of the resources described by the deployment
    manifest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-cloud-deployment-manager/projectglobaldeployments-post-openapi.md
- name: Google Cloud Deployment Manager Delete Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Deletes a deployment and all of the resources in the deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeployment-delete-openapi.md
- name: Google Cloud Deployment Manager Get Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Gets information about a specific deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeployment-get-openapi.md
- name: Google Cloud Deployment Manager update Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Updates a deployment and all of the resources described by the deployment
    manifest. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeployment-patch-openapi.md
- name: Google Cloud Deployment Manager update Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Updates a deployment and all of the resources described by the deployment
    manifest.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeployment-put-openapi.md
- name: Google Cloud Deployment Manager Cancel Preview
  x-api-slug: google-cloud-deployment-manager
  description: Cancels and removes the preview currently associated with the deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}/cancelPreview
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeploymentcancelpreview-post-openapi.md
- name: Google Cloud Deployment Manager Stop Deployment
  x-api-slug: google-cloud-deployment-manager
  description: Stops an ongoing operation. This does not roll back any work that has
    already been completed, but prevents any new work from being started.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https://///{project}/global/deployments/{deployment}/stop
  tags: Deployment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-cloud-deployment-manager/projectglobaldeploymentsdeploymentstop-post-openapi.md
- name: Google Cloud Deployment Manager
  x-api-slug: google-cloud-deployment-manager
  description: Google Cloud Deployment Manager allows you to specify all the resources
    needed for your application in a declarative format using yaml. You can also use
    Python or Jinja2 templates to parameterize the configuration and allow reuse of
    common deployment paradigms such as a load balanced, auto-scaled instance group.
    Treat your configuration as code and perform repeatable deployments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/repeatable-deployment-process.png
  humanURL: https://cloud.google.com/deployment-manager/
  baseURL: https:///
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-cloud-deployment-manager/openapi.md
x-common:
- type: x-authentication
  url: https://cloud.google.com/deployment-manager/docs/reference/latest/authorization
- type: x-change-log
  url: https://cloud.google.com/deployment-manager/docs/release-notes
- type: x-code
  url: https://cloud.google.com/deployment-manager/docs/reference/latest/libraries
- type: x-concepts
  url: https://cloud.google.com/deployment-manager/docs/concepts
- type: x-documentation
  url: https://cloud.google.com/deployment-manager/docs/
- type: x-getting-started
  url: https://cloud.google.com/deployment-manager/docs/quickstart
- type: x-guides
  url: https://cloud.google.com/deployment-manager/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/deployment-manager/pricing-and-quotas
- type: x-tutorials
  url: https://cloud.google.com/deployment-manager/docs/tutorials
- type: x-website
  url: https://cloud.google.com/deployment-manager/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---