---
swagger: "2.0"
x-collection-name: 3scale
x-complete: 0
info:
  title: 3Scale Account Management API Pricing Rules List per Metric
  description: Pricing rules list per metric.
  termsOfService: http://www.3scale.net/terms-and-conditions/
  contact:
    name: 3Scale
    url: https://support.3scale.net/
  version: "1"
host: su1.3scale.net
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/api/accounts/{account_id}/applications/{id}/resume.xml:
    put:
      summary: Application Resume
      description: Application resume.
      operationId: application
      x-api-path-slug: adminapiaccountsaccount-idapplicationsidresume-xml-put
      parameters:
      - in: path
        name: account_id
        description: id of the account
      - in: path
        name: id
        description: id of the application
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      responses:
        200:
          description: OK
      tags:
      - Application
      - Resume
  /admin/api/accounts/{account_id}/messages.xml:
    post:
      summary: Account Message
      description: Account message.
      operationId: account
      x-api-path-slug: adminapiaccountsaccount-idmessages-xml-post
      parameters:
      - in: path
        name: account_id
        description: id of the account
      - in: query
        name: body
        description: Text to send
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      responses:
        200:
          description: OK
      tags:
      - Account
      - Message
  /admin/api/accounts/{account_id}/users/{id}/member.xml:
    put:
      summary: User change Role to Member
      description: User change role to member.
      operationId: user
      x-api-path-slug: adminapiaccountsaccount-idusersidmember-xml-put
      parameters:
      - in: path
        name: account_id
        description: id of the account
      - in: path
        name: id
        description: id of the user
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      responses:
        200:
          description: OK
      tags:
      - User
      - Change
      - Role
      - To
      - Member
  /admin/api/application_plans/{application_plan_id}/metrics/{metric_id}/limits.xml:
    get:
      summary: Limit List per Metric
      description: Limit list per metric.
      operationId: application_plan_limit
      x-api-path-slug: adminapiapplication-plansapplication-plan-idmetricsmetric-idlimits-xml-get
      parameters:
      - in: path
        name: application_plan_id
        description: id of the application plan
      - in: path
        name: metric_id
        description: id of the metric
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      responses:
        200:
          description: OK
      tags:
      - Limit
      - List
      - Per
      - Metric
  /admin/api/application_plans/{application_plan_id}/metrics/{metric_id}/pricing_rules.xml:
    get:
      summary: Pricing Rules List per Metric
      description: Pricing rules list per metric.
      operationId: application_plan_pricing_rules
      x-api-path-slug: adminapiapplication-plansapplication-plan-idmetricsmetric-idpricing-rules-xml-get
      parameters:
      - in: path
        name: application_plan_id
        description: id of the application plan
      - in: path
        name: metric_id
        description: id of the metric
      - in: query
        name: provider_key
        description: Your api key with 3scale (also known as provider key)
      responses:
        200:
          description: OK
      tags:
      - Pricing
      - Rules
      - List
      - Per
      - Metric
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---