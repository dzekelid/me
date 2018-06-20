---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph List Attachments
  description: List attachments Retrieve a list of attachment objects attached to
    an event.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: meeventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnameeventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /groups/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: groupsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/calendar/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: mecalendarideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendar/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamecalendareventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /groups/{id}/calendar/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: groupsidcalendareventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: mecalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamecalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/calendargroup/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: mecalendargroupcalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamecalendargroupcalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/calendargroups/{id}/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: mecalendargroupsidcalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamecalendargroupsidcalendarsideventsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/messages/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: memessagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/messages/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamemessagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/mailFolders/{id}/messages/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: memailfoldersidmessagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /users/{id | userPrincipalName}/mailFolders/{id}/messages/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: usersid--userprincipalnamemailfoldersidmessagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/mailFolders/{id}/childFolders/{id}/.../messages/{id}/attachments/{id}:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to a message.
      operationId: ListAttachments
      x-api-path-slug: memailfoldersidchildfoldersid---messagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Attachments
  /users/{id | userPrincipalName}/mailFolders/{id}/childFolders/{id}/messages/{id}/attachments/{id}:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to a message.
      operationId: ListAttachments
      x-api-path-slug: usersid--userprincipalnamemailfoldersidchildfoldersidmessagesidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Attachments
  /groups/{id}/threads/{id}/posts/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: groupsidthreadsidpostsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /groups/{id}/conversations/{id}/threads/{id}/posts/{id}/attachments/{id}:
    get:
      summary: Get Attachment
      description: |-
        Get attachment
        Read the properties and relationships of an attachment, attached to an event,
        message, or post.
      operationId: GetAttachment
      x-api-path-slug: groupsidconversationsidthreadsidpostsidattachmentsid-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Attachment
  /me/checkMemberGroups:
    post:
      summary: Check Member Groups
      description: Check member groups Check for membership in a specified list of
        groups, and returns from that list those groups of which the specified user,
        group, or directory object is a member. This function is transitive.
      operationId: CheckMemberGroups
      x-api-path-slug: mecheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Member
      - Groups
  /users/{id | userPrincipalName}/checkMemberGroups:
    post:
      summary: Check Member Groups
      description: Check member groups Check for membership in a specified list of
        groups, and returns from that list those groups of which the specified user,
        group, or directory object is a member. This function is transitive.
      operationId: CheckMemberGroups
      x-api-path-slug: usersid--userprincipalnamecheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Member
      - Groups
  /groups/{id}/checkMemberGroups:
    post:
      summary: Group Check Member Groups
      description: 'group: checkMemberGroups Check for membership in the specified
        list of groups. Returns from the list those groups of which the specified
        group has a direct or transitive membership.'
      operationId: Group:CheckMemberGroups
      x-api-path-slug: groupsidcheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - Checks
      - Member
      - Groups
  /directoryObjects/{id}/checkMemberGroups:
    post:
      summary: Check Member Groups
      description: Check member groups Check for membership in a specified list of
        groups, and returns from that list those groups of which the specified user,
        group, or directory object is a member. This function is transitive.
      operationId: CheckMemberGroups
      x-api-path-slug: directoryobjectsidcheckmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Checks
      - Member
      - Groups
  /me/getMemberGroups:
    post:
      summary: Get Member Groups
      description: Get member groups Return all the groups that the specified user,
        group, or directory object is a member of. This function is transitive.
      operationId: GetMemberGroups
      x-api-path-slug: megetmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      responses:
        200:
          description: OK
      tags:
      - Member
      - Groups
  /users/{id | userPrincipalName}/getMemberGroups:
    post:
      summary: Get Member Groups
      description: Get member groups Return all the groups that the specified user,
        group, or directory object is a member of. This function is transitive.
      operationId: GetMemberGroups
      x-api-path-slug: usersid--userprincipalnamegetmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Member
      - Groups
  /groups/{id}/getMemberGroups:
    post:
      summary: Group Get Member Groups
      description: 'group: getMemberGroups Return all the groups that the specified
        group is a member of. The check is transitive, unlike reading the memberOf
        navigation property, which returns only the groups that the group is a direct
        member of.'
      operationId: Group:GetMemberGroups
      x-api-path-slug: groupsidgetmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Group
      - ""
      - Member
      - Groups
  /directoryObjects/{id}/getMemberGroups:
    post:
      summary: Get Member Groups
      description: Get member groups Return all the groups that the specified user,
        group, or directory object is a member of. This function is transitive.
      operationId: GetMemberGroups
      x-api-path-slug: directoryobjectsidgetmembergroups-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Member
      - Groups
  /me/getMemberObjects:
    post:
      summary: Get Member Objects
      description: Get member objects Returns all the groups and directory roles that
        a user, group, or directory object is a member of. This function is transitive.
      operationId: GetMemberObjects
      x-api-path-slug: megetmemberobjects-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      responses:
        200:
          description: OK
      tags:
      - Member
      - Objects
  /users/{id | userPrincipalName}/getMemberObjects:
    post:
      summary: Get Member Objects
      description: Get member objects Returns all the groups and directory roles that
        a user, group, or directory object is a member of. This function is transitive.
      operationId: GetMemberObjects
      x-api-path-slug: usersid--userprincipalnamegetmemberobjects-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
      - in: header
        name: Content-Type
        description: application/json
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Member
      - Objects
  /directoryObjects/{id}/getMemberObjects:
    post:
      summary: Get Member Objects
      description: Get member objects Returns all the groups and directory roles that
        a user, group, or directory object is a member of. This function is transitive.
      operationId: GetMemberObjects
      x-api-path-slug: directoryobjectsidgetmemberobjects-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Member
      - Objects
  /directoryRoles/{id}/members:
    get:
      summary: List Members
      description: List members Retrieve a list of the users that are assigned to
        the directory role.  Only users can be assigned to a directory role.
      operationId: ListMembers
      x-api-path-slug: directoryrolesidmembers-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Members
  /directoryRoles/{id}/members/$ref:
    post:
      summary: Add Directory Role Member
      description: Add directory role member Use this API to create a new directory
        role member.
      operationId: AddDirectoryRoleMember
      x-api-path-slug: directoryrolesidmembersref-post
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: header
        name: Content-Type
        type: application/json
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - Directory
      - Role
      - Member
  /me/drive/special/{name}:
    get:
      summary: Get A Special Folder By Name
      description: Get a special folder by name Use the special collection to access
        a special folder by name.
      operationId: GetASpecialFolderByName
      x-api-path-slug: medrivespecialname-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: name
        type: string
      responses:
        200:
          description: OK
      tags:
      - Special
      - FolderName
  /me/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: meeventsidattachments-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Attachments
  /users/{id | userPrincipalName}/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: usersid--userprincipalnameeventsidattachments-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id | userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Attachments
  /groups/{id}/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: groupsideventsidattachments-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Attachments
  /me/calendar/events/{id}/attachments:
    get:
      summary: List Attachments
      description: List attachments Retrieve a list of attachment objects attached
        to an event.
      operationId: ListAttachments
      x-api-path-slug: mecalendareventsidattachments-get
      parameters:
      - in: header
        name: Authorization
        description: 'Bearer '
        type: string
      - in: path
        name: id
        type: string
      responses:
        200:
          description: OK
      tags:
      - List
      - Attachments
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