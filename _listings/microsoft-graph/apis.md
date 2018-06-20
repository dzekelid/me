---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/meeventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/meeventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendarideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendarideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidcalendareventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidcalendareventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidattachmentsid-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/childFolders/{id}/.../messages/{id}/attachments/{id}
  tags: List, Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidchildfoldersid---messagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidchildfoldersid---messagesidattachmentsid-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/childFolders/{id}/messages/{id}/attachments/{id}
  tags: List, Attachments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfoldersidmessagesidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfoldersidmessagesidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidthreadsidpostsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidthreadsidpostsidattachmentsid-get-openapi.md
- name: Microsoft Graph Get Attachment
  x-api-slug: microsoft-graph
  description: |-
    Get attachment
    Read the properties and relationships of an attachment, attached to an event,
    message, or post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/posts/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidattachmentsid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidattachmentsid-get-openapi.md
- name: Microsoft Graph Check Member Groups
  x-api-slug: microsoft-graph
  description: Check member groups Check for membership in a specified list of groups,
    and returns from that list those groups of which the specified user, group, or
    directory object is a member. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/checkMemberGroups
  tags: Checks, Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecheckmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecheckmembergroups-post-openapi.md
- name: Microsoft Graph Check Member Groups
  x-api-slug: microsoft-graph
  description: Check member groups Check for membership in a specified list of groups,
    and returns from that list those groups of which the specified user, group, or
    directory object is a member. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/checkMemberGroups
  tags: Checks, Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecheckmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecheckmembergroups-post-openapi.md
- name: Microsoft Graph Group Check Member Groups
  x-api-slug: microsoft-graph
  description: 'group: checkMemberGroups Check for membership in the specified list
    of groups. Returns from the list those groups of which the specified group has
    a direct or transitive membership.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/checkMemberGroups
  tags: Group, Checks, Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidcheckmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidcheckmembergroups-post-openapi.md
- name: Microsoft Graph Check Member Groups
  x-api-slug: microsoft-graph
  description: Check member groups Check for membership in a specified list of groups,
    and returns from that list those groups of which the specified user, group, or
    directory object is a member. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryObjects/{id}/checkMemberGroups
  tags: Checks, Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/directoryobjectsidcheckmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/directoryobjectsidcheckmembergroups-post-openapi.md
- name: Microsoft Graph Get Member Groups
  x-api-slug: microsoft-graph
  description: Get member groups Return all the groups that the specified user, group,
    or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/getMemberGroups
  tags: Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/megetmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/megetmembergroups-post-openapi.md
- name: Microsoft Graph Get Member Groups
  x-api-slug: microsoft-graph
  description: Get member groups Return all the groups that the specified user, group,
    or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/getMemberGroups
  tags: Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamegetmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamegetmembergroups-post-openapi.md
- name: Microsoft Graph Group Get Member Groups
  x-api-slug: microsoft-graph
  description: 'group: getMemberGroups Return all the groups that the specified group
    is a member of. The check is transitive, unlike reading the memberOf navigation
    property, which returns only the groups that the group is a direct member of.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/getMemberGroups
  tags: Group, , Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidgetmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidgetmembergroups-post-openapi.md
- name: Microsoft Graph Get Member Groups
  x-api-slug: microsoft-graph
  description: Get member groups Return all the groups that the specified user, group,
    or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryObjects/{id}/getMemberGroups
  tags: Member, Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/directoryobjectsidgetmembergroups-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/directoryobjectsidgetmembergroups-post-openapi.md
- name: Microsoft Graph Get Member Objects
  x-api-slug: microsoft-graph
  description: Get member objects Returns all the groups and directory roles that
    a user, group, or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/getMemberObjects
  tags: Member, Objects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/megetmemberobjects-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/megetmemberobjects-post-openapi.md
- name: Microsoft Graph Get Member Objects
  x-api-slug: microsoft-graph
  description: Get member objects Returns all the groups and directory roles that
    a user, group, or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/getMemberObjects
  tags: Member, Objects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamegetmemberobjects-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamegetmemberobjects-post-openapi.md
- name: Microsoft Graph Get Member Objects
  x-api-slug: microsoft-graph
  description: Get member objects Returns all the groups and directory roles that
    a user, group, or directory object is a member of. This function is transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryObjects/{id}/getMemberObjects
  tags: Member, Objects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/directoryobjectsidgetmemberobjects-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/directoryobjectsidgetmemberobjects-post-openapi.md
- name: Microsoft Graph List Members
  x-api-slug: microsoft-graph
  description: List members Retrieve a list of the users that are assigned to the
    directory role.  Only users can be assigned to a directory role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryRoles/{id}/members
  tags: List, Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/directoryrolesidmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/directoryrolesidmembers-get-openapi.md
- name: Microsoft Graph Add Directory Role Member
  x-api-slug: microsoft-graph
  description: Add directory role member Use this API to create a new directory role
    member.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////directoryRoles/{id}/members/$ref
  tags: Directory, Role, Member
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/directoryrolesidmembersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/directoryrolesidmembersref-post-openapi.md
- name: Microsoft Graph Get A Special Folder By Name
  x-api-slug: microsoft-graph
  description: Get a special folder by name Use the special collection to access a
    special folder by name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/drive/special/{name}
  tags: Special, FolderName
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/medrivespecialname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/medrivespecialname-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/meeventsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsideventsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendareventsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidcalendareventsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachments-get-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/meeventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/meeventsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsideventsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendareventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendareventsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidcalendareventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidcalendareventsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to an event. Since
    there is currently a limit of 4MB on the total size of each REST request, this
    limits the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachments-post-openapi.md
- name: Microsoft Graph Delete Message
  x-api-slug: microsoft-graph
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesid-delete-openapi.md
- name: Microsoft Graph Delete Message
  x-api-slug: microsoft-graph
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-delete-openapi.md
- name: Microsoft Graph Delete Message
  x-api-slug: microsoft-graph
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph Delete Message
  x-api-slug: microsoft-graph
  description: Delete message Delete message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-delete-openapi.md
- name: Microsoft Graph Get Message
  x-api-slug: microsoft-graph
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesid-get-openapi.md
- name: Microsoft Graph Get Message
  x-api-slug: microsoft-graph
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-get-openapi.md
- name: Microsoft Graph Get Message
  x-api-slug: microsoft-graph
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph Get Message
  x-api-slug: microsoft-graph
  description: Get message Retrieve the properties and relationships of a message
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidattachments-get-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidattachments-post-openapi.md
- name: Microsoft Graph Update Message
  x-api-slug: microsoft-graph
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesid-patch-openapi.md
- name: Microsoft Graph Update Message
  x-api-slug: microsoft-graph
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesid-patch-openapi.md
- name: Microsoft Graph Update Message
  x-api-slug: microsoft-graph
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph Update Message
  x-api-slug: microsoft-graph
  description: Update message Update the properties of message object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesid-patch-openapi.md
- name: Microsoft Graph Remove Member
  x-api-slug: microsoft-graph
  description: Remove member Use this API to remove a member from an Office 365 group,
    a security group or a mail-enabled security group through the members navigation
    property. You can remove users or other groups.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/members/{id}/$ref
  tags: Remove, Member
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidmembersidref-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidmembersidref-delete-openapi.md
- name: Microsoft Graph Group Get Member Objects
  x-api-slug: microsoft-graph
  description: 'group: getMemberObjects Return all of the groups that this group is
    a member of. The check is transitive. Note: Groups cannot be members of directory
    roles, so no directory roles will be returned.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/getMemberObjects
  tags: Group, , Member, Objects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidgetmemberobjects-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidgetmemberobjects-post-openapi.md
- name: Microsoft Graph List Member Of
  x-api-slug: microsoft-graph
  description: List memberOf Get groups that the group is a direct member of.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/memberOf
  tags: List, Member, Of
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidmemberof-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidmemberof-get-openapi.md
- name: Microsoft Graph List Members
  x-api-slug: microsoft-graph
  description: List members Get a list of the group's direct members. A group can
    have users, contacts, and other groups as members. This operation is not transitive.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/members
  tags: List, Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidmembers-get-openapi.md
- name: Microsoft Graph Add Member
  x-api-slug: microsoft-graph
  description: 'Add member Use this API to add a member to an Office 365 group, a
    security group or a mail-enabled security group through the members navigation
    property. You can add users or other groups. Important: You can add only users
    to Office 365 groups.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/members/$ref
  tags: Member
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidmembersref-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidmembersref-post-openapi.md
- name: Microsoft Graph List Messages
  x-api-slug: microsoft-graph
  description: List messages Get all the messages in the signed-in user's mailbox,
    or those messages in a specified folder in the mailbox.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages
  tags: List, Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessages-get-openapi.md
- name: Microsoft Graph List Messages
  x-api-slug: microsoft-graph
  description: List messages Get all the messages in the signed-in user's mailbox,
    or those messages in a specified folder in the mailbox.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages
  tags: List, Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-get-openapi.md
- name: Microsoft Graph Create Message
  x-api-slug: microsoft-graph
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessages-post-openapi.md
- name: Microsoft Graph Create Message
  x-api-slug: microsoft-graph
  description: Create Message Use this API to create a new Message in a mailfolder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages
  tags: Message
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessages-post-openapi.md
- name: Microsoft Graph Message Copy
  x-api-slug: microsoft-graph
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/copy
  tags: Message, Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidcopy-post-openapi.md
- name: Microsoft Graph Message Copy
  x-api-slug: microsoft-graph
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/copy
  tags: Message, Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcopy-post-openapi.md
- name: Microsoft Graph Message Copy
  x-api-slug: microsoft-graph
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/copy
  tags: Message, Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph Message Copy
  x-api-slug: microsoft-graph
  description: 'message: copy Copy a message to a folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/copy
  tags: Message, Copy
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcopy-post-openapi.md
- name: Microsoft Graph Message Create Forward
  x-api-slug: microsoft-graph
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidcreateforward-post-openapi.md
- name: Microsoft Graph Message Create Forward
  x-api-slug: microsoft-graph
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreateforward-post-openapi.md
- name: Microsoft Graph Message Create Forward
  x-api-slug: microsoft-graph
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph Message Create Forward
  x-api-slug: microsoft-graph
  description: 'message: createForward Create a draft of the Forward message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createForward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreateforward-post-openapi.md
- name: Microsoft Graph Message Create Reply
  x-api-slug: microsoft-graph
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/createReply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidcreatereply-post-openapi.md
- name: Microsoft Graph Message Create Reply
  x-api-slug: microsoft-graph
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/createReply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereply-post-openapi.md
- name: Microsoft Graph Message Create Reply
  x-api-slug: microsoft-graph
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/createReply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph Message Create Reply
  x-api-slug: microsoft-graph
  description: 'message: createReply Create a draft of the Reply message. You can
    then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createReply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereply-post-openapi.md
- name: Microsoft Graph Message Create Reply All
  x-api-slug: microsoft-graph
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/createReplyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph Message Create Reply All
  x-api-slug: microsoft-graph
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/createReplyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph Message Create Reply All
  x-api-slug: microsoft-graph
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/createReplyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph Message Create Reply All
  x-api-slug: microsoft-graph
  description: 'message: createReplyAll Create a draft of the Reply All message. You
    can then update or send the draft.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/createReplyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidcreatereplyall-post-openapi.md
- name: Microsoft Graph Message Forward
  x-api-slug: microsoft-graph
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidforward-post-openapi.md
- name: Microsoft Graph Message Forward
  x-api-slug: microsoft-graph
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidforward-post-openapi.md
- name: Microsoft Graph Message Forward
  x-api-slug: microsoft-graph
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph Message Forward
  x-api-slug: microsoft-graph
  description: 'message: forward Forward a message. The message is saved in the Sent
    Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/forward
  tags: Message, Forward
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidforward-post-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidattachments-get-openapi.md
- name: Microsoft Graph Message Move
  x-api-slug: microsoft-graph
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/move
  tags: Message, Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidmove-post-openapi.md
- name: Microsoft Graph Message Move
  x-api-slug: microsoft-graph
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/move
  tags: Message, Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidmove-post-openapi.md
- name: Microsoft Graph Message Move
  x-api-slug: microsoft-graph
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/move
  tags: Message, Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph Message Move
  x-api-slug: microsoft-graph
  description: 'message: move Move a message to a folder. This creates a new copy
    of the message in the destination folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/move
  tags: Message, Move
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidmove-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/childFolders/{id}/.../messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidchildfoldersid---messagesidattachmentsid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidchildfoldersid---messagesidattachmentsid-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to a message.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/childFolders/{id}/messages/{id}/attachments/{id}
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfoldersidmessagesidattachmentsid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidchildfoldersidmessagesidattachmentsid-post-openapi.md
- name: Microsoft Graph Message Reply
  x-api-slug: microsoft-graph
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/reply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidreply-post-openapi.md
- name: Microsoft Graph Message Reply
  x-api-slug: microsoft-graph
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/reply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreply-post-openapi.md
- name: Microsoft Graph Message Reply
  x-api-slug: microsoft-graph
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/reply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph Message Reply
  x-api-slug: microsoft-graph
  description: 'message: reply Reply to the sender of a message. The message is then
    saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/reply
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreply-post-openapi.md
- name: Microsoft Graph Message Reply All
  x-api-slug: microsoft-graph
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/me/messages/{id}/replyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersmemessagesidreplyall-post-openapi.md
- name: Microsoft Graph Message Reply All
  x-api-slug: microsoft-graph
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/replyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidreplyall-post-openapi.md
- name: Microsoft Graph Message Reply All
  x-api-slug: microsoft-graph
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/mailFolders/{id}/messages/{id}/replyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph Message Reply All
  x-api-slug: microsoft-graph
  description: 'message: replyAll Reply to all recipients of a message. The message
    is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/replyAll
  tags: Message, Reply
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemailfoldersidmessagesidreplyall-post-openapi.md
- name: Microsoft Graph Message Send
  x-api-slug: microsoft-graph
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/messages/{id}/send
  tags: Message, Send
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/memessagesidsend-post-openapi.md
- name: Microsoft Graph Message Send
  x-api-slug: microsoft-graph
  description: 'message: send Send a message in the draft folder. The draft message
    can be a new message draft, reply draft, reply-all draft, or a forward draft.
    The message is then saved in the Sent Items folder.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages/{id}/send
  tags: Message, Send
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessagesidsend-post-openapi.md
- name: Microsoft Graph Add Named Item
  x-api-slug: microsoft-graph
  description: Add Named Item Adds a new name to the collection of the given scope
    using the user's locale for the formula.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names/add
  tags: Named, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknamesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknamesadd-post-openapi.md
- name: Microsoft Graph Add Named Item
  x-api-slug: microsoft-graph
  description: Add Named Item Adds a new name to the collection of the given scope
    using the user's locale for the formula.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets({id|name})/names/add
  tags: Named, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbookworksheetsidnamenamesadd-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbookworksheetsidnamenamesadd-post-openapi.md
- name: Microsoft Graph Get Named Item
  x-api-slug: microsoft-graph
  description: Get NamedItem Retrieve the properties and relationships of nameditem
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)
  tags: Named, Item
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknamesltnamegt-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknamesltnamegt-get-openapi.md
- name: Microsoft Graph List Named Item Collection
  x-api-slug: microsoft-graph
  description: List NamedItemCollection Retrieve a list of nameditem objects.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names
  tags: List, Named, Item, Collection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknames-get-openapi.md
- name: Microsoft Graph Named Item Range
  x-api-slug: microsoft-graph
  description: 'NamedItem: Range Returns the range object that is associated with
    the name. Throws an exception if the named item''s type is not a range.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/Range
  tags: Named, Item, Range
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknamesltnamegtrange-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknamesltnamegtrange-post-openapi.md
- name: Microsoft Graph Update Nameditem
  x-api-slug: microsoft-graph
  description: Update nameditem Update the properties of nameditem object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)
  tags: Nameditem
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknamesltnamegt-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknamesltnamegt-patch-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    a post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidthreadsidpostsidattachments-get-openapi.md
- name: Microsoft Graph List Attachments
  x-api-slug: microsoft-graph
  description: List attachments Retrieve a list of attachment objects attached to
    a post.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/posts/{id}/attachments
  tags: List, Attachments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidattachments-get-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to a post. Since there
    is currently a limit of 4MB on the total size of each REST request, this limits
    the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/threads/{id}/posts/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidthreadsidpostsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidthreadsidpostsidattachments-post-openapi.md
- name: Microsoft Graph Add Attachment
  x-api-slug: microsoft-graph
  description: Add attachment Use this API to add an attachment to a post. Since there
    is currently a limit of 4MB on the total size of each REST request, this limits
    the size of the attachment you can add to under 4MB.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/conversations/{id}/threads/{id}/posts/{id}/attachments
  tags: Attachment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidattachments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/groupsidconversationsidthreadsidpostsidattachments-post-openapi.md
- name: Microsoft Graph Range Unmerge
  x-api-slug: microsoft-graph
  description: 'Range: unmerge Unmerge the range cells into separate cells.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/unmerge
  tags: Range, Unmerge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknamesltnamegtrangeunmerge-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooknamesltnamegtrangeunmerge-post-openapi.md
- name: Microsoft Graph Range Unmerge
  x-api-slug: microsoft-graph
  description: 'Range: unmerge Unmerge the range cells into separate cells.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/unmerge
  tags: Range, Unmerge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtunmerge-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtunmerge-post-openapi.md
- name: Microsoft Graph Range Unmerge
  x-api-slug: microsoft-graph
  description: 'Range: unmerge Unmerge the range cells into separate cells.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/unmerge
  tags: Range, Unmerge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeunmerge-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeunmerge-post-openapi.md
- name: Microsoft Graph User Find Meeting Times
  x-api-slug: microsoft-graph
  description: 'user: findMeetingTimes Find meeting time suggestions based on organizer
    and attendee availability, and time or location constraints specified as parameters.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/findMeetingTimes
  tags: User, Find, Meeting, Times
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mefindmeetingtimes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/mefindmeetingtimes-post-openapi.md
- name: Microsoft Graph User Find Meeting Times
  x-api-slug: microsoft-graph
  description: 'user: findMeetingTimes Find meeting time suggestions based on organizer
    and attendee availability, and time or location constraints specified as parameters.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id|userPrincipalName}/findMeetingTimes
  tags: User, Find, Meeting, Times
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersiduserprincipalnamefindmeetingtimes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersiduserprincipalnamefindmeetingtimes-post-openapi.md
- name: Microsoft Graph List Member Of
  x-api-slug: microsoft-graph
  description: List memberOf Get groups and directory roles that the user is a direct
    member of.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/memberOf
  tags: List, Member, Of
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamememberof-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamememberof-get-openapi.md
- name: Microsoft Graph List Messages
  x-api-slug: microsoft-graph
  description: List messages Get the messages in the signed-in user's mailbox (including
    the Deleted Items and Clutter folders).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/messages
  tags: List, Messages
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/usersid--userprincipalnamemessages-get-openapi.md
- name: Microsoft Graph List Names
  x-api-slug: microsoft-graph
  description: List names Retrieve a list of named item associated with the worksheet.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets({id|name})/names
  tags: List, Names
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbookworksheetsidnamenames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/workbookworksheetsidnamenames-get-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---