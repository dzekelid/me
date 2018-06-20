---
swagger: "2.0"
x-collection-name: Microsoft Office 365
x-complete: 0
info:
  title: Microsoft Office 365 Parameters Messages Message Reply
  description: Parameters messages message  reply
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
    parameters:
      summary: Parameters Folders Folder Messages
      description: Parameters folders folder  messages
      operationId: parametersFoldersFolderMessages
      x-api-path-slug: foldersfolder-idmessages-parameters
      responses:
        200:
          description: OK
      tags:
      - Folders
      - Folder
      - ""
      - Messages
  /Messages{event_id}/Send:
    post:
      summary: Add Messages Event Send
      description: You can send an existing email that has the IsDraft property...
      operationId: postMessagesEventSend
      x-api-path-slug: messagesevent-idsend-post
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Event
      - ""
      - Send
    parameters:
      summary: Parameters Messages Event Send
      description: Parameters messages event  send
      operationId: parametersMessagesEventSend
      x-api-path-slug: messagesevent-idsend-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Event
      - ""
      - Send
  /Messages{message_id}:
    get:
      summary: Get Messages Message
      description: You can request information about a specific email or meetin...
      operationId: getMessagesMessage
      x-api-path-slug: messagesmessage-id-get
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
    delete:
      summary: Delete Messages Message
      description: You can delete email by simply sending a DELETE request to t...
      operationId: deleteMessagesMessage
      x-api-path-slug: messagesmessage-id-delete
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
    patch:
      summary: Patch Messages Message
      description: You can update an existing email by sending a PATCH request ...
      operationId: patchMessagesMessage
      x-api-path-slug: messagesmessage-id-patch
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
      - Messages
      - Message
    parameters:
      summary: Parameters Messages Message
      description: Parameters messages message
      operationId: parametersMessagesMessage
      x-api-path-slug: messagesmessage-id-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
  /Messages{message_id}/Copy:
    post:
      summary: Add Messages Message Copy
      description: Post messages message  copy
      operationId: postMessagesMessageCopy
      x-api-path-slug: messagesmessage-idcopy-post
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
      - Messages
      - Message
      - ""
      - Copy
    parameters:
      summary: Parameters Messages Message Copy
      description: Parameters messages message  copy
      operationId: parametersMessagesMessageCopy
      x-api-path-slug: messagesmessage-idcopy-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Copy
  /Messages{message_id}/CreateForward:
    post:
      summary: Add Messages Message Createforward
      description: Post messages message  createforward
      operationId: postMessagesMessageCreateforward
      x-api-path-slug: messagesmessage-idcreateforward-post
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Createforward
    parameters:
      summary: Parameters Messages Message Createforward
      description: Parameters messages message  createforward
      operationId: parametersMessagesMessageCreateforward
      x-api-path-slug: messagesmessage-idcreateforward-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Createforward
  /Messages{message_id}/CreateReply:
    post:
      summary: Add Messages Message Createreply
      description: Post messages message  createreply
      operationId: postMessagesMessageCreatereply
      x-api-path-slug: messagesmessage-idcreatereply-post
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Createreply
    parameters:
      summary: Parameters Messages Message Createreply
      description: Parameters messages message  createreply
      operationId: parametersMessagesMessageCreatereply
      x-api-path-slug: messagesmessage-idcreatereply-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Createreply
  /Messages{message_id}/CreateReplyAll:
    post:
      summary: Add Messages Message Create Reply All
      description: Post messages message  createreplyall
      operationId: postMessagesMessageCreatereplyall
      x-api-path-slug: messagesmessage-idcreatereplyall-post
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Createreplyall
    parameters:
      summary: Parameters Messages Message Create Reply All
      description: Parameters messages message  createreplyall
      operationId: parametersMessagesMessageCreatereplyall
      x-api-path-slug: messagesmessage-idcreatereplyall-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Createreplyall
  /Messages{message_id}/Forward:
    post:
      summary: Add Messages Message Forward
      description: You can forward an email by using the Forward action on the ...
      operationId: postMessagesMessageForward
      x-api-path-slug: messagesmessage-idforward-post
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
      - Messages
      - Message
      - ""
      - Forward
    parameters:
      summary: Parameters Messages Message Forward
      description: Parameters messages message  forward
      operationId: parametersMessagesMessageForward
      x-api-path-slug: messagesmessage-idforward-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Forward
  /Messages{message_id}/Move:
    post:
      summary: Add Messages Message Move
      description: Post messages message  move
      operationId: postMessagesMessageMove
      x-api-path-slug: messagesmessage-idmove-post
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
      - Messages
      - Message
      - ""
      - Move
    parameters:
      summary: Parameters Messages Message Move
      description: Parameters messages message  move
      operationId: parametersMessagesMessageMove
      x-api-path-slug: messagesmessage-idmove-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Move
  /Messages{message_id}/Reply:
    post:
      summary: Add Messages Message Reply
      description: Post messages message  reply
      operationId: postMessagesMessageReply
      x-api-path-slug: messagesmessage-idreply-post
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
      - Messages
      - Message
      - ""
      - Reply
    parameters:
      summary: Parameters Messages Message Reply
      description: Parameters messages message  reply
      operationId: parametersMessagesMessageReply
      x-api-path-slug: messagesmessage-idreply-parameters
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Message
      - ""
      - Reply
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