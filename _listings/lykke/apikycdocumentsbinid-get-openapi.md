---
swagger: "2.0"
x-collection-name: Lykke
x-complete: 0
info:
  title: Lykke Get API Kycdocumentsbin
  version: 1.0.0
  description: Get api kycdocumentsbin.
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/AssetDisclaimers:
    get:
      summary: Get API Asset Dsclaimers
      description: Get api asset dsclaimers.
      operationId: AssetDisclaimersGet
      x-api-path-slug: apiassetdisclaimers-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Dsclaimers
  /api/AssetDisclaimers/{disclaimerId}/approve:
    post:
      summary: Add API Asset Dsclaimers Disclaimer Approve
      description: Add api asset dsclaimers disclaimer approve.
      operationId: AssetDisclaimersApprove
      x-api-path-slug: apiassetdisclaimersdisclaimeridapprove-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: disclaimerId
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Dsclaimers
      - Disclaimer
      - Approve
  /api/AssetDisclaimers/{disclaimerId}/decline:
    post:
      summary: Add API Asset Dsclaimers Disclaimer Decline
      description: Add api asset dsclaimers disclaimer decline.
      operationId: AssetDisclaimersDecline
      x-api-path-slug: apiassetdisclaimersdisclaimeriddecline-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: path
        name: disclaimerId
      responses:
        200:
          description: OK
      tags:
      - Asset
      - Dsclaimers
      - Disclaimer
      - Decline
  /api/BankCardPaymentUrl:
    post:
      summary: Add API Bankcardpaymenturl
      description: Add api bankcardpaymenturl.
      operationId: ApiBankCardPaymentUrlPost
      x-api-path-slug: apibankcardpaymenturl-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: input
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Bankcardpaymenturl
  /api/BankCardPaymentUrlFormValues:
    get:
      summary: Get API Bankcardpaymenturlformvalues
      description: Get api bankcardpaymenturlformvalues.
      operationId: ApiBankCardPaymentUrlFormValuesGet
      x-api-path-slug: apibankcardpaymenturlformvalues-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Bankcardpaymenturlformvalues
  /api/CheckDocumentsToUpload:
    get:
      summary: Get API Checkdocumentstoupload
      description: Get api checkdocumentstoupload.
      operationId: ApiCheckDocumentsToUploadGet
      x-api-path-slug: apicheckdocumentstoupload-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Checkdocumentstoupload
  /api/ClientFirstNameLastName:
    post:
      summary: Add API Clientfirstnamelastname
      description: Add api clientfirstnamelastname.
      operationId: ApiClientFirstNameLastNamePost
      x-api-path-slug: apiclientfirstnamelastname-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Clientfirstnamelastname
  /api/ClientFullName:
    post:
      summary: Add API Clientfullname
      description: Add api clientfullname.
      operationId: ApiClientFullNamePost
      x-api-path-slug: apiclientfullname-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: fullNameModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Clientfullname
  /api/EmailMeWalletAddress:
    post:
      summary: Add API Emailmewalletaddress
      description: Add api emailmewalletaddress.
      operationId: ApiEmailMeWalletAddressPost
      x-api-path-slug: apiemailmewalletaddress-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: reqModel
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Emailmewalletaddress
  /api/KycDocuments:
    get:
      summary: Get API Kycdocuments
      description: Get api kycdocuments.
      operationId: ApiKycDocumentsGet
      x-api-path-slug: apikycdocuments-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      responses:
        200:
          description: OK
      tags:
      - Kycdocuments
    post:
      summary: Add API Kycdocuments
      description: Add api kycdocuments.
      operationId: ApiKycDocumentsPost
      x-api-path-slug: apikycdocuments-post
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: body
        name: model
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Kycdocuments
  /api/KycDocumentsBin/{id}:
    get:
      summary: Get API Kycdocumentsbin
      description: Get api kycdocumentsbin.
      operationId: ApiKycDocumentsBinByIdGet
      x-api-path-slug: apikycdocumentsbinid-get
      parameters:
      - in: header
        name: Authorization
        description: access token
      - in: query
        name: height
      - in: path
        name: id
      - in: query
        name: width
      responses:
        200:
          description: OK
      tags:
      - Kycdocumentsbin
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