---
swagger: "2.0"
x-collection-name: Gmail
x-complete: 1
info:
  title: Gmail
  description: access-gmail-mailboxes-including-sending-user-email-
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
    get:
      summary: Get S/MIME Configuration
      description: Gets the specified S/MIME config for the specified send-as alias.
      operationId: gmail.users.settings.sendAs.smimeInfo.get
      x-api-path-slug: useridsettingssendassendasemailsmimeinfoid-get
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
  /{userId}/settings/sendAs/{sendAsEmail}/smimeInfo/{id}/setDefault:
    post:
      summary: Create Default S/MIME Configurations
      description: Sets the default S/MIME config for the specified send-as alias.
      operationId: gmail.users.settings.sendAs.smimeInfo.setDefault
      x-api-path-slug: useridsettingssendassendasemailsmimeinfoidsetdefault-post
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
---