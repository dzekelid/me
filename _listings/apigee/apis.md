---
name: Apigee
x-slug: apigee
description: Apigee Edge is a platform for developing and managing API proxies. Think
  of a proxy as an abstraction layer that fronts for your backend service APIs and
  provides value-added features like security, rate limiting, quotas, analytics, and
  more. The primary consumers of Edge API proxies are app developers who want to use
  your backend services.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/apis.md
specificationVersion: "0.14"
apis:
- name: Apigee Edge Get Organizations Name Deployments
  x-api-slug: apigee-edge
  description: Gets all deployments of an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/deployments
  tags: Organizations,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedeployments-get-openapi.md
- name: Apigee Edge Get Organizations Name Environments
  x-api-slug: apigee-edge
  description: Lists all the environments in an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments
  tags: Organizations,Environments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironments-get-openapi.md
- name: Apigee Edge Post Organizations Name Environments
  x-api-slug: apigee-edge
  description: Creates an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments
  tags: Organizations,Environments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironments-post-openapi.md
- name: Apigee Edge Get Organizations Name Environments Env Name
  x-api-slug: apigee-edge
  description: Gets details for an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}
  tags: Organizations,Environments,Env
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-name-get-openapi.md
- name: Apigee Edge Post Organizations Name Environments Env Name
  x-api-slug: apigee-edge
  description: Updates an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}
  tags: Organizations,Environments,Env
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Environments Env Name
  x-api-slug: apigee-edge
  description: Deletes a specific environment in an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}
  tags: Organizations,Environments,Env
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-name-delete-openapi.md
- name: Apigee Edge Get Organizations Name Environments Env Name Deployments
  x-api-slug: apigee-edge
  description: Gets the deployments for an environment in an organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/deployments
  tags: Organizations,Environments,Env,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namedeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namedeployments-get-openapi.md
- name: Apigee Edge Get Organizations Name Environments Env Name API Name Deployments
  x-api-slug: apigee-edge
  description: Gets the deployments for an API Proxy in the given environment in an
    organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/apis/{api_name}/deployments
  tags: Organizations,Environments,Envs,APIs,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-nameapisapi-namedeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-nameapisapi-namedeployments-get-openapi.md
- name: Apigee Edge Get Organizations Name Environments Env Name API Name Revisions
    Revision Number Deployments
  x-api-slug: apigee-edge
  description: "Gets the deployments for an API Proxy\xE2\x80\x99s revision for an
    environment in an organization."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/apis/{api_name}/revisions/{revision_number}/deployments
  tags: Organizations,Environments,Envs,APIs,Revisions,Revision,Number,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-nameapisapi-namerevisionsrevision-numberdeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-nameapisapi-namerevisionsrevision-numberdeployments-get-openapi.md
- name: Apigee Edge Get Organizations Name Environments Env Name Servers
  x-api-slug: apigee-edge
  description: Gets the servers that are bound to an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/servers
  tags: Organizations,Environments,Env,Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-nameservers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-nameservers-get-openapi.md
- name: Apigee Edge Post Organizations Name Environments Env Name Servers
  x-api-slug: apigee-edge
  description: Add servers into the environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/servers
  tags: Organizations,Environments,Env,Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-nameservers-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-nameservers-post-openapi.md
- name: Apigee Edge Delete Organizations Name Environments Env Name Servers
  x-api-slug: apigee-edge
  description: Deletes servers from the environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/servers
  tags: Organizations,Environments,Env,Servers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-nameservers-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-nameservers-delete-openapi.md
- name: Apigee Edge Get Organizations Name Environments Env Name Virtualhosts
  x-api-slug: apigee-edge
  description: Lists all virtual hosts in an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/virtualhosts
  tags: Organizations,Environments,Env,Virtualhosts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhosts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhosts-get-openapi.md
- name: Apigee Edge Post Organizations Name Environments Env Name Virtualhosts
  x-api-slug: apigee-edge
  description: Creates a virtual host.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/virtualhosts
  tags: Organizations,Environments,Env,Virtualhosts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhosts-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhosts-post-openapi.md
- name: Apigee Edge Get Organizations Name Environments Env Name Virtualhosts Virtualhost
    Name
  x-api-slug: apigee-edge
  description: Gets details for a named virtual host .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/virtualhosts/{virtualhost_name}
  tags: Organizations,Environments,Env,Virtualhosts,Virtualhost
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-get-openapi.md
- name: Apigee Edge Post Organizations Name Environments Env Name Virtualhosts Virtualhost
    Name
  x-api-slug: apigee-edge
  description: Updates a specific virtual host in an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/virtualhosts/{virtualhost_name}
  tags: Organizations,Environments,Env,Virtualhosts,Virtualhost
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Environments Env Name Virtualhosts Virtualhost
    Name
  x-api-slug: apigee-edge
  description: Deletes a specific virtual host in an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/environments/{env_name}/virtualhosts/{virtualhost_name}
  tags: Organizations,Environments,Env,Virtualhosts,Virtualhost
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameenvironmentsenv-namevirtualhostsvirtualhost-name-delete-openapi.md
- name: Apigee Edge Post Organizations Name API Name Revisions Revision Number Deployments
  x-api-slug: apigee-edge
  description: Undeploys an API proxy revision from an environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/apis/{api_name}/revisions/{revision_number}/deployments
  tags: Organizationss,APIs,Revisions,Revision,Number,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameapisapi-namerevisionsrevision-numberdeployments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameapisapi-namerevisionsrevision-numberdeployments-post-openapi.md
- name: Apigee Edge Get Organizations Name API Name Deployments
  x-api-slug: apigee-edge
  description: Returns detail on deployments of the API specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/apis/{api_name}/deployments
  tags: Organizationss,APIs,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameapisapi-namedeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameapisapi-namedeployments-get-openapi.md
- name: Apigee Edge Get Organizations Name API Name Revisions Revision Name Deployments
  x-api-slug: apigee-edge
  description: Get deployments for a revision of an API proxy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/apis/{api_name}/revisions/{revision_name}/deployments
  tags: Organizationss,APIs,Revisions,Revision,Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameapisapi-namerevisionsrevision-namedeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-nameapisapi-namerevisionsrevision-namedeployments-get-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key
  x-api-slug: apigee-edge
  description: Returns details for a consumer key for a developer app .
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-get-openapi.md
- name: Apigee Edge Post Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key
  x-api-slug: apigee-edge
  description: Revokes a developer app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-post-openapi.md
- name: Apigee Edge Delete Organizations Name Developers Developer Email Apps App
    Name Keys Consumer Key
  x-api-slug: apigee-edge
  description: Deletes a consumer key that belongs to an app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-key-delete-openapi.md
- name: Apigee Edge Post Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key Apiproducts Apiproduct Name
  x-api-slug: apigee-edge
  description: Revokes the association of an API Product with a Developer App's consumer
    key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/apiproducts/{apiproduct_name}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,API,Products,API,Productss
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-post-openapi.md
- name: Apigee Edge Delete Organizations Name Developers Developer Email Apps App
    Name Keys Consumer Key Apiproducts Apiproduct Name
  x-api-slug: apigee-edge
  description: Removes an API product from a developer app key profile, and thereby
    renders the developer app unable to access the URIs defined in the API product
    specified.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/apiproducts/{apiproduct_name}
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,API,Products,API,Productss
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyapiproductsapiproduct-name-delete-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key Oauth1accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 1.0 access tokens for a developer's app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/oauth1accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,Oauth1accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth1accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth1accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Developers Developer Email Apps App Name
    Keys Consumer Key Oauth2accesstokens
  x-api-slug: apigee-edge
  description: Get count of OAuth 2.0 access tokens for a developer's app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/developers/{developer_email}/apps/{app_name}/keys/{consumer_key}/oauth2accesstokens
  tags: Organizations,Developers,Developer,Email,Applications,,Keys,Consumer,Key,Oauth2accesstokens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth2accesstokens-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namedevelopersdeveloper-emailappsapp-namekeysconsumer-keyoauth2accesstokens-get-openapi.md
- name: Apigee Edge Get Organizations Name Companies Company Name Apps App Name Keys
    Consumer Key
  x-api-slug: apigee-edge
  description: Gets the consumer key issued to a company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Companies,Companies,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-get-openapi.md
- name: Apigee Edge Post Organizations Name Companies Company Name Apps App Name Keys
    Consumer Key
  x-api-slug: apigee-edge
  description: Revokes the specific key of a company app.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Companies,Companies,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-post-openapi.md
- name: Apigee Edge Delete Organizations Name Companies Company Name Apps App Name
    Keys Consumer Key
  x-api-slug: apigee-edge
  description: Deletes a company app key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1///organizations/{org_name}/companies/{company_name}/apps/{app_name}/keys/{consumer_key}
  tags: Organizations,Companies,Companies,Applications,,Keys,Consumer,Key
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/organizationsorg-namecompaniescompany-nameappsapp-namekeysconsumer-key-delete-openapi.md
- name: Apigee Edge
  x-api-slug: apigee-edge
  description: Apigee Edge is a platform for developing and managing API proxies.
    Think of a proxy as an abstraction layer that fronts for your backend service
    APIs and provides value-added features like security, rate limiting, quotas, analytics,
    and more. The primary consumers of Edge API proxies are app developers who want
    to use your backend services.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/apigee-edge.png
  humanURL: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
  baseURL: https://api.enterprise.apigee.com//v1/
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/apigee/openapi.md
x-common:
- type: x-website
  url: https://docs.apigee.com/api-platform/get-started/what-apigee-edge
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---