---
name: Heroku
x-slug: heroku
description: Heroku is a platform as a service (PaaS) that enables developers to build,
  run, and operate applications entirely in the cloud.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
x-kinRank: "8"
x-alexaRank: "6044"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/apis.md
specificationVersion: "0.14"
apis:
- name: Heroku Parameters Addons
  x-api-slug: heroku
  description: Parameters addons.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////addons
  tags: Parameters, ons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/addons-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/addons-parameters-openapi.md
- name: Heroku Parameter Application Addons
  x-api-slug: heroku
  description: Parameter application addons.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/addons
  tags: Parameter, Application, ons
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappaddons-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappaddons-parameters-openapi.md
- name: Heroku Parameters Applications Addons
  x-api-slug: heroku
  description: Parameters applications addons.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/addons/{addon}
  tags: Parameters, Applications, ons
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappaddonsaddon-parameters-openapi.md
- name: Heroku Parameters Applications
  x-api-slug: heroku
  description: Parameters applications.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps
  tags: Parameters, Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/apps-parameters-openapi.md
- name: Heroku Parameters Applications Name
  x-api-slug: heroku
  description: Parameters applications name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{name}
  tags: Parameters, Applications, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsname-parameters-openapi.md
- name: Heroku Get Applications Name
  x-api-slug: heroku
  description: Get applications name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{name}
  tags: Applications, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsname-get-openapi.md
- name: Heroku Delete Applications Name
  x-api-slug: heroku
  description: Delete applications name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{name}
  tags: Applications, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsname-delete-openapi.md
- name: Heroku Parameters Application Collaborators
  x-api-slug: heroku
  description: Parameters application collaborators.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/collaborators
  tags: Parameters, Application, Collaborators
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappcollaborators-parameters-openapi.md
- name: Heroku Parameters Application Collaborators Email
  x-api-slug: heroku
  description: Parameters application collaborators email.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/collaborators/{email}
  tags: Parameters, Application, Collaborators, Email
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappcollaboratorsemail-parameters-openapi.md
- name: Heroku Parameters Application Config Variables
  x-api-slug: heroku
  description: Parameters application config variables.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/config_vars
  tags: Parameters, Application, Config, Variables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappconfig-vars-parameters-openapi.md
- name: Heroku Parameters Application Config Variables Key
  x-api-slug: heroku
  description: Parameters application config variables key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/config_vars/{key}
  tags: Parameters, Application, Config, Variables, Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappconfig-varskey-parameters-openapi.md
- name: Heroku Parameters Application Domains
  x-api-slug: heroku
  description: Parameters application domains.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/domains
  tags: Parameters, Application, Domains
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappdomains-parameters-openapi.md
- name: Heroku Parameters Application Domain Name
  x-api-slug: heroku
  description: Parameters application domain name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/domains/{domain_name}
  tags: Parameters, Application, Domain, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappdomainsdomain-name-parameters-openapi.md
- name: Heroku Delete Application Domain Name
  x-api-slug: heroku
  description: Delete application domain name.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/domains/{domain_name}
  tags: Application, Domain, Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappdomainsdomain-name-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappdomainsdomain-name-delete-openapi.md
- name: Heroku Parameters User Keys
  x-api-slug: heroku
  description: Parameters user keys.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////user/keys
  tags: Parameters, User, Keys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/userkeys-parameters-openapi.md
- name: Heroku Parameters User Keys Key
  x-api-slug: heroku
  description: Parameters user keys key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////user/keys/{key}
  tags: Parameters, User, Keys, Key
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/userkeyskey-parameters-openapi.md
- name: Heroku Parameters Application Logs
  x-api-slug: heroku
  description: Parameters application logs.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/logs
  tags: Parameters, Application, Logs
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsapplogs-parameters-openapi.md
- name: Heroku Parameters Application PS
  x-api-slug: heroku
  description: Parameters application ps.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/ps
  tags: Parameters, Application, PS
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappps-parameters-openapi.md
- name: Heroku Parameters Application PS Restart
  x-api-slug: heroku
  description: Parameters application ps restart.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/ps/restart
  tags: Parameters, Application, PS, Restart
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsapppsrestart-parameters-openapi.md
- name: Heroku Parameters Application PS Stop
  x-api-slug: heroku
  description: Parameters application ps stop.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/ps/stop
  tags: Parameters, Application, PS, Stop
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsapppsstop-parameters-openapi.md
- name: Heroku Parameters Application PS Scale
  x-api-slug: heroku
  description: Parameters application ps scale.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/ps/scale
  tags: Parameters, Application, PS, Scale
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsapppsscale-parameters-openapi.md
- name: Heroku Parameters Application Releases
  x-api-slug: heroku
  description: Parameters application releases.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/releases
  tags: Parameters, Application, Releases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappreleases-parameters-openapi.md
- name: Heroku Parameters Application Releases
  x-api-slug: heroku
  description: Parameters application releases.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/releases/{release}
  tags: Parameters, Application, Releases
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappreleasesrelease-parameters-openapi.md
- name: Heroku Parameters Application Stack
  x-api-slug: heroku
  description: Parameters application stack.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com////apps/{app}/stack
  tags: Parameters, Application, Stack
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/appsappstack-parameters-openapi.md
- name: Heroku
  x-api-slug: heroku
  description: Learn about building, deploying and managing your apps on Heroku.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/211-heroku.jpg
  humanURL: http://heroku.com
  baseURL: https://api.heroku.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/heroku/openapi.md
x-common:
- type: x-base
  url: https://api.heroku.com
- type: x-blog
  url: https://blog.heroku.com/
- type: x-blog-rss
  url: http://feeds2.feedburner.com/heroku
- type: x-command-line-interface
  url: https://devcenter.heroku.com/articles/heroku-command
- type: x-crunchbase
  url: https://crunchbase.com/organization/heroku
- type: x-crunchbase
  url: http://www.crunchbase.com/company/heroku
- type: x-developer
  url: https://devcenter.heroku.com/
- type: x-email
  url: pr@heroku.com
- type: x-email
  url: abuse@heroku.com
- type: x-email
  url: feedback@heroku.com
- type: x-getting-started
  url: https://devcenter.heroku.com/start
- type: x-github
  url: https://github.com/heroku
- type: x-issues
  url: https://status.heroku.com/incidents
- type: x-java-library
  url: https://devcenter.heroku.com/categories/java
- type: x-node-js
  url: https://devcenter.heroku.com/categories/nodejs
- type: x-php-library
  url: https://devcenter.heroku.com/categories/php
- type: x-pricing
  url: https://www.heroku.com/pricing
- type: x-privacy
  url: https://www.heroku.com/policy/privacy
- type: x-python-library
  url: https://devcenter.heroku.com/categories/python
- type: x-ruby-library
  url: https://devcenter.heroku.com/categories/ruby
- type: x-security
  url: https://www.heroku.com/policy/security
- type: x-selfservice-registration
  url: https://signup.heroku.com/dc
- type: x-support
  url: https://www.heroku.com/support
- type: x-terms-of-service
  url: https://www.heroku.com/policy/tos
- type: x-twitter
  url: https://twitter.com/heroku
- type: x-twitter
  url: https://twitter.com/HerokuDevCenter
- type: x-website
  url: http://heroku.com
- type: x-website
  url: https://www.heroku.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---