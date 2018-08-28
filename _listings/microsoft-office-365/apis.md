---
name: Microsoft Office 365
x-slug: microsoft-office-365
description: Integrate Office 365 REST APIs powered by Microsoft Graph into your own
  app to connect to files, calendars, mail and more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Office 365 Get Contacts Contact Attachments
  x-api-slug: microsoft-office-365
  description: To get attachments, send a GET request to the Attachments pr...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}/Attachments
  tags: Contacts, Contact, , Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/contactscontact-idattachments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/contactscontact-idattachments-get-openapi.md
- name: Microsoft Office 365 Add Contacts Contact Attachments
  x-api-slug: microsoft-office-365
  description: To add an attachment to an item, send a POST request to the ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}/Attachments
  tags: Contacts, Contact, , Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/contactscontact-idattachments-post-openapi.md
- name: Microsoft Office 365 Delete Contacts Contact Attachments
  x-api-slug: microsoft-office-365
  description: To delete an attachment, send a DELETE request to the URL of...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}/Attachments
  tags: Contacts, Contact, , Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/contactscontact-idattachments-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/contactscontact-idattachments-delete-openapi.md
- name: Microsoft Office 365 Parameters Contacts Contact Attachments
  x-api-slug: microsoft-office-365
  description: Parameters contacts contact  attachments
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Contacts{contact_id}/Attachments
  tags: Contacts, Contact, , Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/contactscontact-idattachments-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/contactscontact-idattachments-parameters-openapi.md
- name: Microsoft Office 365 Get Folders Folder Messages
  x-api-slug: microsoft-office-365
  description: You can request all the emails and meeting requests in a fol...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}/Messages
  tags: Folders, Folder, , Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/foldersfolder-idmessages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/foldersfolder-idmessages-get-openapi.md
- name: Microsoft Office 365 Add Folders Folder Messages
  x-api-slug: microsoft-office-365
  description: You can create an email by sending a POST request with a JSO...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}/Messages
  tags: Folders, Folder, , Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/foldersfolder-idmessages-post-openapi.md
- name: Microsoft Office 365 Parameters Folders Folder Messages
  x-api-slug: microsoft-office-365
  description: Parameters folders folder  messages
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Folders{folder_id}/Messages
  tags: Folders, Folder, , Messages
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/foldersfolder-idmessages-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/foldersfolder-idmessages-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Event Send
  x-api-slug: microsoft-office-365
  description: You can send an existing email that has the IsDraft property...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{event_id}/Send
  tags: Messages, Event, , Send
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesevent-idsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesevent-idsend-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Event Send
  x-api-slug: microsoft-office-365
  description: Parameters messages event  send
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{event_id}/Send
  tags: Messages, Event, , Send
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesevent-idsend-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesevent-idsend-parameters-openapi.md
- name: Microsoft Office 365 Get Messages Message
  x-api-slug: microsoft-office-365
  description: You can request information about a specific email or meetin...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}
  tags: Messages, Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-id-get-openapi.md
- name: Microsoft Office 365 Delete Messages Message
  x-api-slug: microsoft-office-365
  description: You can delete email by simply sending a DELETE request to t...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}
  tags: Messages, Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-id-delete-openapi.md
- name: Microsoft Office 365 Patch Messages Message
  x-api-slug: microsoft-office-365
  description: You can update an existing email by sending a PATCH request ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}
  tags: Messages, Message
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-id-patch-openapi.md
- name: Microsoft Office 365 Parameters Messages Message
  x-api-slug: microsoft-office-365
  description: Parameters messages message
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}
  tags: Messages, Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-id-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-id-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Copy
  x-api-slug: microsoft-office-365
  description: Post messages message  copy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Copy
  tags: Messages, Message, , Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcopy-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Copy
  x-api-slug: microsoft-office-365
  description: Parameters messages message  copy
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Copy
  tags: Messages, Message, , Copy
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcopy-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcopy-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Createforward
  x-api-slug: microsoft-office-365
  description: Post messages message  createforward
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateForward
  tags: Messages, Message, , Createforward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreateforward-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Createforward
  x-api-slug: microsoft-office-365
  description: Parameters messages message  createforward
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateForward
  tags: Messages, Message, , Createforward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreateforward-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreateforward-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Createreply
  x-api-slug: microsoft-office-365
  description: Post messages message  createreply
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateReply
  tags: Messages, Message, , Createreply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreatereply-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Createreply
  x-api-slug: microsoft-office-365
  description: Parameters messages message  createreply
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateReply
  tags: Messages, Message, , Createreply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreatereply-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreatereply-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Create Reply All
  x-api-slug: microsoft-office-365
  description: Post messages message  createreplyall
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateReplyAll
  tags: Messages, Message, , Createreplyall
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreatereplyall-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Create Reply All
  x-api-slug: microsoft-office-365
  description: Parameters messages message  createreplyall
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/CreateReplyAll
  tags: Messages, Message, , Createreplyall
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreatereplyall-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idcreatereplyall-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Forward
  x-api-slug: microsoft-office-365
  description: You can forward an email by using the Forward action on the ...
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Forward
  tags: Messages, Message, , Forward
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idforward-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Forward
  x-api-slug: microsoft-office-365
  description: Parameters messages message  forward
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Forward
  tags: Messages, Message, , Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idforward-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idforward-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Move
  x-api-slug: microsoft-office-365
  description: Post messages message  move
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Move
  tags: Messages, Message, , Move
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idmove-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Move
  x-api-slug: microsoft-office-365
  description: Parameters messages message  move
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Move
  tags: Messages, Message, , Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idmove-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idmove-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Reply
  x-api-slug: microsoft-office-365
  description: Post messages message  reply
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Reply
  tags: Messages, Message, , Reply
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idreply-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Reply
  x-api-slug: microsoft-office-365
  description: Parameters messages message  reply
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/Reply
  tags: Messages, Message, , Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idreply-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idreply-parameters-openapi.md
- name: Microsoft Office 365 Add Messages Message Replyall
  x-api-slug: microsoft-office-365
  description: Post messages message  replyall
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/ReplyAll
  tags: Messages, Message, , Replyall
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idreplyall-post-openapi.md
- name: Microsoft Office 365 Parameters Messages Message Replyall
  x-api-slug: microsoft-office-365
  description: Parameters messages message  replyall
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me//Messages{message_id}/ReplyAll
  tags: Messages, Message, , Replyall
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idreplyall-parameters-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/messagesmessage-idreplyall-parameters-openapi.md
- name: Microsoft Office 365
  x-api-slug: microsoft-office-365
  description: Integrate Office 365 REST APIs powered by Microsoft Graph into your
    own app to connect to files, calendars, mail and more.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-office.png
  humanURL: http://office.com
  baseURL: https://outlook.office365.com//ews/odata/Me
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-office-365/openapi.md
x-common:
- type: x-developer
  url: http://dev.office.com
- type: x-github
  url: https://github.com/OfficeDev
- type: x-twitter
  url: https://twitter.com/OfficeDev
- type: x-website
  url: http://office.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---