---
swagger: "2.0"
x-collection-name: Plivo
x-complete: 0
info:
  title: Codenvy Account API Post Photos Comments
  description: Creates a new comment for the photo.
  version: 1.0.0
host: /account
basePath: https://codenvy.com/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account/memberships:
    get:
      summary: Get Account Memberships
      description: ID of a user should be specified as a query parameter. JSON with
        membership details is returned. For this API call system/admin or system/manager
        role is required
      operationId: getMembershipsOfSpecificUser
      x-api-path-slug: accountmemberships-get
      parameters:
      - in: query
        name: userid
        description: User ID
      responses:
        200:
          description: OK
      tags:
      - Account
      - Memberships
  /account/{id}/members:
    get:
      summary: Get Account Members
      description: Get all members for a specific account. This API call requires
        account/owner, system/admin or system/manager role.
      operationId: getMembers
      x-api-path-slug: accountidmembers-get
      parameters:
      - in: path
        name: id
        description: Account ID
      responses:
        200:
          description: OK
      tags:
      - Account
      - Id
      - Members
    post:
      summary: Post Account Members
      description: Add a new user to an account. This user will have account/member
        role. This API call requires account/owner, system/admin or system/manager
        role.
      operationId: addMember
      x-api-path-slug: accountidmembers-post
      parameters:
      - in: body
        name: body
        description: New membership
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Account ID
      responses:
        200:
          description: OK
      tags:
      - Account
      - Id
      - Members
  /account/{id}/members/{userid}:
    delete:
      summary: Delete Account Members User
      description: Remove user from a specific account. This API call requires account/owner,
        system/admin or system/manager role.
      operationId: removeMember
      x-api-path-slug: accountidmembersuserid-delete
      parameters:
      - in: path
        name: id
        description: Account ID
      - in: path
        name: userid
        description: User ID
      responses:
        200:
          description: OK
      tags:
      - Account
      - Id
      - Members
      - Userid
  /blogs/:id/comments:
    post:
      summary: Post Blogs Comments
      description: Creates a comment for the Story.
      operationId: creates-a-comment-for-the-story
      x-api-path-slug: blogsidcomments-post
      parameters:
      - in: query
        name: body (required)
        description: Content of the comment
      - in: query
        name: id (required)
        description: The Story ID to create a comment for
      responses:
        200:
          description: OK
      tags:
      - Blogs
      - :id
      - Comments
  /comments/:id/comments:
    post:
      summary: Post Comments Comments
      description: Creates a reply to an existing comment. Comments can only be nested
        one level deep, you cannot reply to a reply of a comment. If a comment has
        a non-null parent_id value then it cannot be replied to.
      operationId: creates-a-reply-to-an-existing-comment-comments-can-only-be-nested-one-level-deep-you-cannot-reply-t
      x-api-path-slug: commentsidcomments-post
      parameters:
      - in: query
        name: body (required)
        description: Content of the comment
      responses:
        200:
          description: OK
      tags:
      - Comments
      - :id
      - Comments
  /photos/:id/comments:
    post:
      summary: Post Photos Comments
      description: Creates a new comment for the photo.
      operationId: creates-a-new-comment-for-the-photo
      x-api-path-slug: photosidcomments-post
      parameters:
      - in: query
        name: body (required)
        description: Content of the comment
      - in: query
        name: id (required)
        description: The Photo ID to post comments for
      responses:
        200:
          description: OK
      tags:
      - Photos
      - :id
      - Comments
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