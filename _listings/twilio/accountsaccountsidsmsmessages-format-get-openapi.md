---
swagger: "2.0"
x-collection-name: Twilio
x-complete: 0
info:
  title: Twilio GetSMSList
  description: GetSMSList
  termsOfService: https://www.twilio.com/legal/tos
  version: v1
host: api.twilio.com
basePath: /2010-04-01/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Accounts/{AccountSid}/Messages/{MessageSid}/Media/{MediaSid}:
    get:
      summary: Get Message Media
      description: Without an extension, the media is returned using the mime-type
        provided when the media was generated.
      operationId: without-an-extension-the-media-is-returned-using-the-mimetype-provided-when-the-media-was-generated
      x-api-path-slug: accountsaccountsidmessagesmessagesidmediamediasid-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: MediaSid
        description: A 34 character string that uniquely identifies the media object
      - in: path
        name: MessageSid
        description: A 34 character string that uniquely identifies the message
      responses:
        200:
          description: OK
      tags:
      - Messages
  /Accounts/{AccountSid}/Messages/{MessageSid}/Media:
    get:
      summary: Get Message Media
      description: Returns a list of media associated with your message.
      operationId: returns-a-list-of-media-associated-with-your-message
      x-api-path-slug: accountsaccountsidmessagesmessagesidmedia-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: MessageSid
        description: A 34 character string that uniquely identifies the message
      responses:
        200:
          description: OK
      tags:
      - Messages
  /Accounts/{AccountSid}/Messages/{MessageSid}:
    get:
      summary: Get Message Media
      description: Returns a single message specified by the provided {MessageSid}.n
      operationId: returns-a-single-message-specified-by-the-provided-messagesid
      x-api-path-slug: accountsaccountsidmessagesmessagesid-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: MessageSid
        description: A 34 character string that uniquely identifies the message
      responses:
        200:
          description: OK
      tags:
      - Messages
  /Accounts/{AccountSid}/Messages.{format}:
    get:
      summary: Get Message Media
      description: Returns a list of messages associated with your account. The list
        includes paging information.
      operationId: returns-a-list-of-messages-associated-with-your-account-the-list-includes-paging-information
      x-api-path-slug: accountsaccountsidmessages-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Messages
    post:
      summary: Add Message
      description: To send a new outgoing message, make an HTTP POST to your Messages
        list resource URI
      operationId: to-send-a-new-outgoing-message-make-an-http-post-to-your-messages-list-resource-uri
      x-api-path-slug: accountsaccountsidmessages-format-post
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Messages
  /Accounts/{AccountSid}/SMS/Messages.{format}:
    get:
      summary: GetSMSList
      description: GetSMSList
      operationId: getsmslist
      x-api-path-slug: accountsaccountsidsmsmessages-format-get
      parameters:
      - in: path
        name: AccountSid
        description: The ID for the Twilio account
      - in: path
        name: format
        description: By default, Twilios REST API returns XML
      responses:
        200:
          description: OK
      tags:
      - SMS Messages
x-streamrank:
  polling_total_time_average: "0"
  polling_size_download_average: "0"
  streaming_total_time_average: "0"
  streaming_size_download_average: "0"
  change_yes: "0"
  change_no: "0"
  time_percentage: "0"
  size_percentage: "0"
  change_percentage: "200"
  last_run: ~
  days_run: "0"
  minute_run: "0"
---