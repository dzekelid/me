---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Add Folders Folder Messages
  description: You can create an email by sending a POST request with a JSO...
  version: 1.0.0
host: outlook.office365.com
basePath: /ews/odata/Me
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Contacts{contact_id}/Attachments:
    get:
      summary: Get Contacts Contact Attachments
      description: To get attachments, send a GET request to the Attachments pr...
      operationId: getContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-get
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
    post:
      summary: Add Contacts Contact Attachments
      description: To add an attachment to an item, send a POST request to the ...
      operationId: postContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
    delete:
      summary: Delete Contacts Contact Attachments
      description: To delete an attachment, send a DELETE request to the URL of...
      operationId: deleteContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-delete
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
    parameters:
      summary: Parameters Contacts Contact Attachments
      description: Parameters contacts contact  attachments
      operationId: parametersContactsContactAttachments
      x-api-path-slug: contactscontact-idattachments-parameters
      responses:
        200:
          description: OK
      tags:
      - Contacts
      - Contact
      - ""
      - Attachments
  /Folders{folder_id}/Messages:
    get:
      summary: Get Folders Folder Messages
      description: You can request all the emails and meeting requests in a fol...
      operationId: getFoldersFolderMessages
      x-api-path-slug: foldersfolder-idmessages-get
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
      - ""
      - Messages
    post:
      summary: Add Folders Folder Messages
      description: You can create an email by sending a POST request with a JSO...
      operationId: postFoldersFolderMessages
      x-api-path-slug: foldersfolder-idmessages-post
      parameters:
      - in: body
        name: body
        description: (Untitled)
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: MessageDisposition
        description: When sending a POST request to create an email, there is an optional
          MessageDisposition query parameter that controls what happens to the message
          as it is created
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
      - ""
      - Messages
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