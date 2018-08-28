---
swagger: "2.0"
x-collection-name: Gmail
x-complete: 0
info:
  title: Gmail Delete S/MIME Configurations
  description: Deletes the specified S/MIME config for the specified send-as alias.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /gmail/v1/users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{userId}/settings/sendAs/{sendAsEmail}/smimeInfo:
    get:
      summary: Get S/MIME Configurations
      description: Lists S/MIME configs for the specified send-as alias.
      operationId: gmail.users.settings.sendAs.smimeInfo.list
      x-api-path-slug: useridsettingssendassendasemailsmimeinfo-get
      parameters:
      - in: path
        name: sendAsEmail
        description: 'The email address that appears in the From: header for mail
          sent using this alias'
      - in: path
        name: userId
        description: The users email address
      responses:
        200:
          description: OK
      tags:
      - S/MIME Configuration
    post:
      summary: Create S/MIME Configurations
      description: Insert (upload) the given S/MIME config for the specified send-as
        alias. Note that pkcs12 format is required for the key.
      operationId: gmail.users.settings.sendAs.smimeInfo.insert
      x-api-path-slug: useridsettingssendassendasemailsmimeinfo-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: sendAsEmail
        description: 'The email address that appears in the From: header for mail
          sent using this alias'
      - in: path
        name: userId
        description: The users email address
      responses:
        200:
          description: OK
      tags:
      - S/MIME Configuration
  /{userId}/settings/sendAs/{sendAsEmail}/smimeInfo/{id}:
    delete:
      summary: Delete S/MIME Configurations
      description: Deletes the specified S/MIME config for the specified send-as alias.
      operationId: gmail.users.settings.sendAs.smimeInfo.delete
      x-api-path-slug: useridsettingssendassendasemailsmimeinfoid-delete
      parameters:
      - in: path
        name: id
        description: The immutable ID for the SmimeInfo
      - in: path
        name: sendAsEmail
        description: 'The email address that appears in the From: header for mail
          sent using this alias'
      - in: path
        name: userId
        description: The users email address
      responses:
        200:
          description: OK
      tags:
      - S/MIME Configuration
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