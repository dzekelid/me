---
name: 3scale
x-slug: 3scale
description: 3scales API Management platform gives you the tools you need to take
  control of your API. Trusted by more customers than any other vendor.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
x-kinRank: "10"
x-alexaRank: "345437"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/apis.md
specificationVersion: "0.14"
apis:
- name: 3Scale Account Management API Application Resume
  x-api-slug: 3scale-account-management-api
  description: Application resume.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{account_id}/applications/{id}/resume.xml
  tags: Application,Resume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiaccountsaccount-idapplicationsidresume-xml-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiaccountsaccount-idapplicationsidresume-xml-put-openapi.md
- name: 3Scale Account Management API Account Message
  x-api-slug: 3scale-account-management-api
  description: Account message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{account_id}/messages.xml
  tags: Account,Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiaccountsaccount-idmessages-xml-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiaccountsaccount-idmessages-xml-post-openapi.md
- name: 3Scale Account Management API User change Role to Member
  x-api-slug: 3scale-account-management-api
  description: User change role to member.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/accounts/{account_id}/users/{id}/member.xml
  tags: User,Change,Role,To,Member
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiaccountsaccount-idusersidmember-xml-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiaccountsaccount-idusersidmember-xml-put-openapi.md
- name: 3Scale Account Management API Limit List per Metric
  x-api-slug: 3scale-account-management-api
  description: Limit list per metric.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/application_plans/{application_plan_id}/metrics/{metric_id}/limits.xml
  tags: Limit,List,Per,Metric
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiapplication-plansapplication-plan-idmetricsmetric-idlimits-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiapplication-plansapplication-plan-idmetricsmetric-idlimits-xml-get-openapi.md
- name: 3Scale Account Management API Pricing Rules List per Metric
  x-api-slug: 3scale-account-management-api
  description: Pricing rules list per metric.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/application_plans/{application_plan_id}/metrics/{metric_id}/pricing_rules.xml
  tags: Pricing,Rules,List,Per,Metric
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiapplication-plansapplication-plan-idmetricsmetric-idpricing-rules-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiapplication-plansapplication-plan-idmetricsmetric-idpricing-rules-xml-get-openapi.md
- name: 3Scale Account Management API Metric List
  x-api-slug: 3scale-account-management-api
  description: Metric list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/services/{service_id}/metrics.xml
  tags: Metric,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiservicesservice-idmetrics-xml-get-openapi.md
- name: 3Scale Account Management API Metric Create
  x-api-slug: 3scale-account-management-api
  description: Metric create.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/services/{service_id}/metrics.xml
  tags: Metric,Create
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiservicesservice-idmetrics-xml-post-openapi.md
- name: 3Scale Account Management API Metric Delete
  x-api-slug: 3scale-account-management-api
  description: Metric delete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/services/{service_id}/metrics/{id}.xml
  tags: Metric
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiservicesservice-idmetricsid-xml-delete-openapi.md
- name: 3Scale Account Management API Metric Read
  x-api-slug: 3scale-account-management-api
  description: Metric read.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/services/{service_id}/metrics/{id}.xml
  tags: Metric,Read
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiservicesservice-idmetricsid-xml-get-openapi.md
- name: 3Scale Account Management API Metric Update
  x-api-slug: 3scale-account-management-api
  description: Metric update.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/services/{service_id}/metrics/{id}.xml
  tags: Metric
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiservicesservice-idmetricsid-xml-put-openapi.md
- name: 3Scale Account Management API Method List
  x-api-slug: 3scale-account-management-api
  description: Method list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/services/{service_id}/metrics/{metric_id}/methods.xml
  tags: Method,List
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiservicesservice-idmetricsmetric-idmethods-xml-get-openapi.md
- name: 3Scale Account Management API Method Create
  x-api-slug: 3scale-account-management-api
  description: Method create.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/services/{service_id}/metrics/{metric_id}/methods.xml
  tags: Method,Create
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiservicesservice-idmetricsmetric-idmethods-xml-post-openapi.md
- name: 3Scale Account Management API Method Delete
  x-api-slug: 3scale-account-management-api
  description: Method delete.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/services/{service_id}/metrics/{metric_id}/methods/{id}.xml
  tags: Method
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiservicesservice-idmetricsmetric-idmethodsid-xml-delete-openapi.md
- name: 3Scale Account Management API Method Read
  x-api-slug: 3scale-account-management-api
  description: Method read.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/services/{service_id}/metrics/{metric_id}/methods/{id}.xml
  tags: Method,Read
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiservicesservice-idmetricsmetric-idmethodsid-xml-get-openapi.md
- name: 3Scale Account Management API Method Update
  x-api-slug: 3scale-account-management-api
  description: Method update.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/services/{service_id}/metrics/{metric_id}/methods/{id}.xml
  tags: Method
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiservicesservice-idmetricsmetric-idmethodsid-xml-put-openapi.md
- name: 3Scale Account Management API User change Role to Member (provider account)
  x-api-slug: 3scale-account-management-api
  description: User change role to member (provider account).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////admin/api/users/{id}/member.xml
  tags: User,Change,Role,To,Member,(provider,Account)
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/adminapiusersidmember-xml-put-openapi.md
- name: 3Scale Account Management API
  x-api-slug: 3scale-account-management-api
  description: 3scales API Management platform gives you the tools you need to take
    control of your API. Trusted by more customers than any other vendor.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/openapi.md
- name: 3Scale Analytics API Application Usage by Metric
  x-api-slug: 3scale-analytics-api
  description: Application usage by metric.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////stats/applications/{application_id}/usage.{format}
  tags: Application,Usage,By,Metric
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/statsapplicationsapplication-idusage-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/statsapplicationsapplication-idusage-format-get-openapi.md
- name: 3Scale Analytics API Service Usage by Metric
  x-api-slug: 3scale-analytics-api
  description: Service usage by metric.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////stats/services/{service_id}/usage.{format}
  tags: Service,Usage,By,Metric
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/statsservicesservice-idusage-format-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/statsservicesservice-idusage-format-get-openapi.md
- name: 3Scale Analytics API
  x-api-slug: 3scale-analytics-api
  description: 3scales API Management platform gives you the tools you need to take
    control of your API. Trusted by more customers than any other vendor.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/openapi.md
- name: 3Scale Billing API Invoice Payment Transactions List
  x-api-slug: 3scale-billing-api
  description: Invoice payment transactions list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net////api/invoices/{invoice_id}/payment_transactions.xml
  tags: Invoice,Payment,Transactions,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/apiinvoicesinvoice-idpayment-transactions-xml-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/apiinvoicesinvoice-idpayment-transactions-xml-get-openapi.md
- name: 3Scale Billing API
  x-api-slug: 3scale-billing-api
  description: 3scales API Management platform gives you the tools you need to take
    control of your API. Trusted by more customers than any other vendor.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/4-3scale.jpg
  humanURL: http://3scale.net
  baseURL: https://su1.3scale.net//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/3scale/openapi.md
x-common:
- type: x-blog
  url: http://www.3scale.net/blog/
- type: x-blog-rss
  url: http://www.3scale.net/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/3scale
- type: x-crunchbase
  url: https://crunchbase.com/organization/3scale
- type: x-email
  url: sales@3scale.net
- type: x-email
  url: info@3scale.net
- type: x-github
  url: https://github.com/3scale
- type: x-pricing
  url: https://www.3scale.net/pricing/
- type: x-privacy
  url: https://www.3scale.net/privacy-policy/
- type: x-support
  url: https://support.3scale.net
- type: x-openapi-spec
  url: https://support.3scale.net/reference/active-docs
- type: x-terms-of-service
  url: https://www.3scale.net/terms-and-conditions/
- type: x-twitter
  url: https://twitter.com/3scale
- type: x-website
  url: http://3scale.net
- type: x-website
  url: http://
- type: x-website
  url: http://www.3scale.net
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---