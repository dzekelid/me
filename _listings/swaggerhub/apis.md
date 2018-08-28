---
name: SwaggerHub
x-slug: swaggerhub
description: The place for teams to collaborate and coordinate the entire workflow
  of an APIs lifecycle. SwaggerHub&rsquo;s built-in editors let you rapidly create
  the Swagger definition that everything else is based on, in an intuitive interface
  that lets you write, visualize and validate all at the same time.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apis.md
specificationVersion: "0.14"
apis:
- name: Swagger Hub Registry Renames API
  x-api-slug: swagger-hub-registry
  description: Renames api.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////apis/{owner}/{api}/.newname
  tags: APIs,Owner,,Newname
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapi-newname-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapi-newname-post-openapi.md
- name: Swagger Hub Registry Returns the list of comments for the specified API
  x-api-slug: swagger-hub-registry
  description: Returns the list of comments for the specified api.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////apis/{owner}/{api}/{version}/.comment
  tags: APIs,Owner,Version,,Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapiversion-comment-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapiversion-comment-get-openapi.md
- name: Swagger Hub Registry Adds a new comment to the specified API
  x-api-slug: swagger-hub-registry
  description: Adds a new comment to the specified api.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////apis/{owner}/{api}/{version}/.comment
  tags: APIs,Owner,Version,,Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapiversion-comment-post-openapi.md
- name: Swagger Hub Registry Updates passed batch of comments
  x-api-slug: swagger-hub-registry
  description: Updates passed batch of comments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////apis/{owner}/{api}/{version}/.comment/batch
  tags: APIs,Owner,Version,,Comment,Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapiversion-commentbatch-post-openapi.md
- name: Swagger Hub Registry Deletes specified comment
  x-api-slug: swagger-hub-registry
  description: Deletes specified comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////apis/{owner}/{api}/{version}/.comment/{comment}
  tags: APIs,Owner,Version,,Comment,Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapiversion-commentcomment-delete-openapi.md
- name: Swagger Hub Registry Updates specified comment
  x-api-slug: swagger-hub-registry
  description: Updates specified comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////apis/{owner}/{api}/{version}/.comment/{comment}
  tags: APIs,Owner,Version,,Comment,Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapiversion-commentcomment-patch-openapi.md
- name: Swagger Hub Registry Adds a new reply to the specified comment
  x-api-slug: swagger-hub-registry
  description: Adds a new reply to the specified comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////apis/{owner}/{api}/{version}/.comment/{comment}/reply
  tags: APIs,Owner,Version,,Comment,Comment,Reply
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapiversion-commentcommentreply-post-openapi.md
- name: Swagger Hub Registry Deletes specified comment reply
  x-api-slug: swagger-hub-registry
  description: Deletes specified comment reply.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////apis/{owner}/{api}/{version}/.comment/{comment}/reply/{reply}
  tags: APIs,Owner,Version,,Comment,Comment,Reply,Reply
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapiversion-commentcommentreplyreply-delete-openapi.md
- name: Swagger Hub Registry Updates specified comment reply
  x-api-slug: swagger-hub-registry
  description: Updates specified comment reply.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////apis/{owner}/{api}/{version}/.comment/{comment}/reply/{reply}
  tags: APIs,Owner,Version,,Comment,Comment,Reply,Reply
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapiversion-commentcommentreplyreply-patch-openapi.md
- name: Swagger Hub Registry Updates status to the specified comment
  x-api-slug: swagger-hub-registry
  description: Updates status to the specified comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////apis/{owner}/{api}/{version}/.comment/{comment}/status/{status}
  tags: APIs,Owner,Version,,Comment,Comment,Status,Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/apisownerapiversion-commentcommentstatusstatus-put-openapi.md
- name: Swagger Hub Registry Renames domain
  x-api-slug: swagger-hub-registry
  description: Renames domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////domains/{owner}/{domain}/.newname
  tags: Domains,Owner,Domain,,Newname
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/domainsownerdomain-newname-post-openapi.md
- name: Swagger Hub Registry Returns the list of comments for the specified domain
  x-api-slug: swagger-hub-registry
  description: Returns the list of comments for the specified domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////domains/{owner}/{domain}/{version}/.comment
  tags: Domains,Owner,Domain,Version,,Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/domainsownerdomainversion-comment-get-openapi.md
- name: Swagger Hub Registry Adds a new comment to the specified domain
  x-api-slug: swagger-hub-registry
  description: Adds a new comment to the specified domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////domains/{owner}/{domain}/{version}/.comment
  tags: Domains,Owner,Domain,Version,,Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/domainsownerdomainversion-comment-post-openapi.md
- name: Swagger Hub Registry Updates passed batch of comments
  x-api-slug: swagger-hub-registry
  description: Updates passed batch of comments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////domains/{owner}/{domain}/{version}/.comment/batch
  tags: Domains,Owner,Domain,Version,,Comment,Batch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/domainsownerdomainversion-commentbatch-post-openapi.md
- name: Swagger Hub Registry Deletes specified comment
  x-api-slug: swagger-hub-registry
  description: Deletes specified comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////domains/{owner}/{domain}/{version}/.comment/{comment}
  tags: Domains,Owner,Domain,Version,,Comment,Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/domainsownerdomainversion-commentcomment-delete-openapi.md
- name: Swagger Hub Registry Updates specified comment
  x-api-slug: swagger-hub-registry
  description: Updates specified comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////domains/{owner}/{domain}/{version}/.comment/{comment}
  tags: Domains,Owner,Domain,Version,,Comment,Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/domainsownerdomainversion-commentcomment-patch-openapi.md
- name: Swagger Hub Registry Adds a new reply to the specified comment
  x-api-slug: swagger-hub-registry
  description: Adds a new reply to the specified comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////domains/{owner}/{domain}/{version}/.comment/{comment}/reply
  tags: Domains,Owner,Domain,Version,,Comment,Comment,Reply
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/domainsownerdomainversion-commentcommentreply-post-openapi.md
- name: Swagger Hub Registry Deletes specified comment reply
  x-api-slug: swagger-hub-registry
  description: Deletes specified comment reply.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////domains/{owner}/{domain}/{version}/.comment/{comment}/reply/{reply}
  tags: Domains,Owner,Domain,Version,,Comment,Comment,Reply,Reply
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/domainsownerdomainversion-commentcommentreplyreply-delete-openapi.md
- name: Swagger Hub Registry Updates specified comment reply
  x-api-slug: swagger-hub-registry
  description: Updates specified comment reply.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////domains/{owner}/{domain}/{version}/.comment/{comment}/reply/{reply}
  tags: Domains,Owner,Domain,Version,,Comment,Comment,Reply,Reply
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/domainsownerdomainversion-commentcommentreplyreply-patch-openapi.md
- name: Swagger Hub Registry Updates status to the specified comment
  x-api-slug: swagger-hub-registry
  description: Updates status to the specified comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com////domains/{owner}/{domain}/{version}/.comment/{comment}/status/{status}
  tags: Domains,Owner,Domain,Version,,Comment,Comment,Status,Status
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/domainsownerdomainversion-commentcommentstatusstatus-put-openapi.md
- name: Swagger Hub Registry
  x-api-slug: swagger-hub-registry
  description: The place for teams to collaborate and coordinate the entire workflow
    of an APIs lifecycle. SwaggerHub&rsquo;s built-in editors let you rapidly create
    the Swagger definition that everything else is based on, in an intuitive interface
    that lets you write, visualize and validate all at the same time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SwaggerHub_Logo_Horizontal_Color.png
  humanURL: http://swaggerhub.com
  baseURL: https://api.swaggerhub.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/swaggerhub/openapi.md
x-common:
- type: x-github
  url: https://github.com/swagger-hub
- type: x-twitter
  url: https://twitter.com/swaggerhub
- type: x-website
  url: http://swaggerhub.com
- type: x-website
  url: https://swaggerhub.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---