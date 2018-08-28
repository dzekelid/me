---
swagger: "2.0"
x-collection-name: GitHub
x-complete: 0
info:
  title: Github Get Users Username
  description: Get a single user.
  termsOfService: https://help.github.com/articles/github-terms-of-service/#b-api-terms
  version: 1.0.0
host: api.github.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /gists/{id}/comments:
    get:
      summary: Get Gists  Comments
      description: List comments on a gist.
      operationId: list-comments-on-a-gist
      x-api-path-slug: gistsidcomments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Comments
    post:
      summary: Add Gists  Comments
      description: Create a commen
      operationId: create-a-commen
      x-api-path-slug: gistsidcomments-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Comments
  /gists/{id}/comments/{commentId}:
    delete:
      summary: Delete Gists  Comments Comment
      description: Delete a comment.
      operationId: delete-a-comment
      x-api-path-slug: gistsidcommentscommentid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Comments
      - Comment
    get:
      summary: Get Gists  Comments Comment
      description: Get a single comment.
      operationId: get-a-single-comment
      x-api-path-slug: gistsidcommentscommentid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Comments
      - Comment
    patch:
      summary: Patch Gists  Comments Comment
      description: Edit a comment.
      operationId: edit-a-comment
      x-api-path-slug: gistsidcommentscommentid-patch
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: id
        description: Id of gist
      responses:
        200:
          description: OK
      tags:
      - Gists
      - ""
      - Comments
      - Comment
  /meta:
    get:
      summary: Get Meta
      description: This gives some information about GitHub.com, the service.
      operationId: this-gives-some-information-about-githubcom-the-service
      x-api-path-slug: meta-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      responses:
        200:
          description: OK
      tags:
      - Meta
  /orgs/{org}/members:
    get:
      summary: Get Orgs Org Members
      description: |-
        Members list.
        List all users who are members of an organization. A member is a user tha
        belongs to at least 1 team in the organization. If the authenticated user
        is also an owner of this organization then both concealed and public members
        will be returned. If the requester is not an owner of the organization the
        query will be redirected to the public members list.
      operationId: members-listlist-all-users-who-are-members-of-an-organization-a-member-is-a-user-thabelongs-to-at-le
      x-api-path-slug: orgsorgmembers-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: org
        description: Name of organisation
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Members
  /orgs/{org}/members/{username}:
    delete:
      summary: Delete Orgs Org Members Username
      description: |-
        Remove a member.
        Removing a user from this list will remove them from all teams and they
        will no longer have any access to the organization's repositories.
      operationId: remove-a-memberremoving-a-user-from-this-list-will-remove-them-from-all-teams-and-theywill-no-longer
      x-api-path-slug: orgsorgmembersusername-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: org
        description: Name of organisation
      - in: path
        name: username
        description: Name of the user
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Members
      - Username
    get:
      summary: Get Orgs Org Members Username
      description: Check if a user is, publicly or privately, a member of the organization.
      operationId: check-if-a-user-is-publicly-or-privately-a-member-of-the-organization
      x-api-path-slug: orgsorgmembersusername-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: org
        description: Name of organisation
      - in: path
        name: username
        description: Name of the user
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Members
      - Username
  /orgs/{org}/public_members:
    get:
      summary: Get Orgs Org Public Members
      description: |-
        Public members list.
        Members of an organization can choose to have their membership publicized
        or not.
      operationId: public-members-listmembers-of-an-organization-can-choose-to-have-their-membership-publicizedor-not
      x-api-path-slug: orgsorgpublic-members-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: org
        description: Name of organisation
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Public
      - Members
  /orgs/{org}/public_members/{username}:
    delete:
      summary: Delete Orgs Org Public Members Username
      description: Conceal a user's membership.
      operationId: conceal-a-users-membership
      x-api-path-slug: orgsorgpublic-membersusername-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: org
        description: Name of organisation
      - in: path
        name: username
        description: Name of the user
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Public
      - Members
      - Username
    get:
      summary: Get Orgs Org Public Members Username
      description: Check public membership.
      operationId: check-public-membership
      x-api-path-slug: orgsorgpublic-membersusername-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: org
        description: Name of organisation
      - in: path
        name: username
        description: Name of the user
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Public
      - Members
      - Username
    put:
      summary: Put Orgs Org Public Members Username
      description: Publicize a user's membership.
      operationId: publicize-a-users-membership
      x-api-path-slug: orgsorgpublic-membersusername-put
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: org
        description: Name of organisation
      - in: path
        name: username
        description: Name of the user
      responses:
        200:
          description: OK
      tags:
      - Orgs
      - Org
      - Public
      - Members
      - Username
  /repos/{owner}/{repo}/comments:
    get:
      summary: Get Repos Owner Repo Comments
      description: |-
        List commit comments for a repository.
        Comments are ordered by ascending ID.
      operationId: list-commit-comments-for-a-repositorycomments-are-ordered-by-ascending-id
      x-api-path-slug: reposownerrepocomments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Comments
  /repos/{owner}/{repo}/comments/{commentId}:
    delete:
      summary: Delete Repos Owner Repo Comments Comment
      description: Delete a commit comment
      operationId: delete-a-commit-comment
      x-api-path-slug: reposownerrepocommentscommentid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Comments
      - Comment
    get:
      summary: Get Repos Owner Repo Comments Comment
      description: Get a single commit comment.
      operationId: get-a-single-commit-comment
      x-api-path-slug: reposownerrepocommentscommentid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Comments
      - Comment
    patch:
      summary: Patch Repos Owner Repo Comments Comment
      description: Update a commit comment.
      operationId: update-a-commit-comment
      x-api-path-slug: reposownerrepocommentscommentid-patch
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Comments
      - Comment
  /repos/{owner}/{repo}/commits/{shaCode}/comments:
    get:
      summary: Get Repos Owner Repo Commits Shacode Comments
      description: List comments for a single commitList comments for a single commit.
      operationId: list-comments-for-a-single-commitlist-comments-for-a-single-commit
      x-api-path-slug: reposownerrepocommitsshacodecomments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: path
        name: shaCode
        description: SHA-1 code of the commit
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Commits
      - Shacode
      - Comments
    post:
      summary: Add Repos Owner Repo Commits Shacode Comments
      description: Create a commit comment.
      operationId: create-a-commit-comment
      x-api-path-slug: reposownerrepocommitsshacodecomments-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: path
        name: shaCode
        description: SHA-1 code of the commit
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Commits
      - Shacode
      - Comments
  /repos/{owner}/{repo}/deployments:
    get:
      summary: Get Repos Owner Repo Deployments
      description: Users with pull access can view deployments for a repository
      operationId: users-with-pull-access-can-view-deployments-for-a-repository
      x-api-path-slug: reposownerrepodeployments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Deployments
    post:
      summary: Add Repos Owner Repo Deployments
      description: Users with push access can create a deployment for a given ref
      operationId: users-with-push-access-can-create-a-deployment-for-a-given-ref
      x-api-path-slug: reposownerrepodeployments-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Deployments
  /repos/{owner}/{repo}/deployments/{id}/statuses:
    get:
      summary: Get Repos Owner Repo Deployments  Statuses
      description: Users with pull access can view deployment statuses for a deployment
      operationId: users-with-pull-access-can-view-deployment-statuses-for-a-deployment
      x-api-path-slug: reposownerrepodeploymentsidstatuses-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: id
        description: The Deployment ID to list the statuses from
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Deployments
      - ""
      - Statuses
    post:
      summary: Add Repos Owner Repo Deployments  Statuses
      description: |-
        Create a Deployment Status
        Users with push access can create deployment statuses for a given deployment:
      operationId: create-a-deployment-statususers-with-push-access-can-create-deployment-statuses-for-a-given-deployme
      x-api-path-slug: reposownerrepodeploymentsidstatuses-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The Deployment ID to list the statuses from
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Deployments
      - ""
      - Statuses
  /repos/{owner}/{repo}/issues/comments:
    get:
      summary: Get Repos Owner Repo Issues Comments
      description: List comments in a repository.
      operationId: list-comments-in-a-repository
      x-api-path-slug: reposownerrepoissuescomments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: direction
        description: Ignored without sort parameter
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: query
        name: since
        description: 'The time should be passed in as UTC in the ISO 8601 format:
          YYYY-MM-DDTHH:MM:SSZ'
      - in: query
        name: sort
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Comments
  /repos/{owner}/{repo}/issues/comments/{commentId}:
    delete:
      summary: Delete Repos Owner Repo Issues Comments Comment
      description: Delete a comment.
      operationId: delete-a-comment
      x-api-path-slug: reposownerrepoissuescommentscommentid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: ID of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Comments
      - Comment
    get:
      summary: Get Repos Owner Repo Issues Comments Comment
      description: Get a single comment.
      operationId: get-a-single-comment
      x-api-path-slug: reposownerrepoissuescommentscommentid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: ID of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Comments
      - Comment
    patch:
      summary: Patch Repos Owner Repo Issues Comments Comment
      description: Edit a comment.
      operationId: edit-a-comment
      x-api-path-slug: reposownerrepoissuescommentscommentid-patch
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: commentId
        description: ID of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Comments
      - Comment
  /repos/{owner}/{repo}/issues/{number}/comments:
    get:
      summary: Get Repos Owner Repo Issues Number Comments
      description: List comments on an issue.
      operationId: list-comments-on-an-issue
      x-api-path-slug: reposownerrepoissuesnumbercomments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: number
        description: Number of issue
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Number
      - Comments
    post:
      summary: Add Repos Owner Repo Issues Number Comments
      description: Create a comment.
      operationId: create-a-comment
      x-api-path-slug: reposownerrepoissuesnumbercomments-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: number
        description: Number of issue
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Number
      - Comments
  /repos/{owner}/{repo}/issues/{number}/labels/{name}:
    delete:
      summary: Delete Repos Owner Repo Issues Number Labels Name
      description: Remove a label from an issue.
      operationId: remove-a-label-from-an-issue
      x-api-path-slug: reposownerrepoissuesnumberlabelsname-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: name
        description: Name of the label
      - in: path
        name: number
        description: Number of issue
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Issues
      - Number
      - Labels
      - Name
  /repos/{owner}/{repo}/labels/{name}:
    delete:
      summary: Delete Repos Owner Repo Labels Name
      description: Delete a label.
      operationId: delete-a-label
      x-api-path-slug: reposownerrepolabelsname-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: name
        description: Name of the label
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Labels
      - Name
    get:
      summary: Get Repos Owner Repo Labels Name
      description: Get a single label.
      operationId: get-a-single-label
      x-api-path-slug: reposownerrepolabelsname-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: name
        description: Name of the label
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Labels
      - Name
    patch:
      summary: Patch Repos Owner Repo Labels Name
      description: Update a label.
      operationId: update-a-label
      x-api-path-slug: reposownerrepolabelsname-patch
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: Name of the label
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Labels
      - Name
  /repos/{owner}/{repo}/merges:
    post:
      summary: Add Repos Owner Repo Merges
      description: Perform a merge.
      operationId: perform-a-merge
      x-api-path-slug: reposownerrepomerges-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Merges
  /repos/{owner}/{repo}/pulls/comments:
    get:
      summary: Get Repos Owner Repo Pulls Comments
      description: |-
        List comments in a repository.
        By default, Review Comments are ordered by ascending ID.
      operationId: list-comments-in-a-repositoryby-default-review-comments-are-ordered-by-ascending-id
      x-api-path-slug: reposownerrepopullscomments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: query
        name: direction
        description: Ignored without sort parameter
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      - in: query
        name: since
        description: 'The time should be passed in as UTC in the ISO 8601 format:
          YYYY-MM-DDTHH:MM:SSZ'
      - in: query
        name: sort
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Pulls
      - Comments
  /repos/{owner}/{repo}/pulls/comments/{commentId}:
    delete:
      summary: Delete Repos Owner Repo Pulls Comments Comment
      description: Delete a comment.
      operationId: delete-a-comment
      x-api-path-slug: reposownerrepopullscommentscommentid-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Pulls
      - Comments
      - Comment
    get:
      summary: Get Repos Owner Repo Pulls Comments Comment
      description: Get a single comment.
      operationId: get-a-single-comment
      x-api-path-slug: reposownerrepopullscommentscommentid-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Pulls
      - Comments
      - Comment
    patch:
      summary: Patch Repos Owner Repo Pulls Comments Comment
      description: Edit a comment.
      operationId: edit-a-comment
      x-api-path-slug: reposownerrepopullscommentscommentid-patch
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: commentId
        description: Id of comment
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Pulls
      - Comments
      - Comment
  /repos/{owner}/{repo}/pulls/{number}/comments:
    get:
      summary: Get Repos Owner Repo Pulls Number Comments
      description: List comments on a pull request.
      operationId: list-comments-on-a-pull-request
      x-api-path-slug: reposownerrepopullsnumbercomments-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: number
        description: Id of pull
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Pulls
      - Number
      - Comments
    post:
      summary: Add Repos Owner Repo Pulls Number Comments
      description: |-
        Create a comment.
          #TODO Alternative input ( http://developer.github.com/v3/pulls/comments/ )
          description: |
            Alternative Input.
            Instead of passing commit_id, path, and position you can reply to an
            existing Pull Request Comment like this:

                body
                   Required string
                in_reply_to
                   Required number - Comment id to reply to.
      operationId: create-a-comment--todo-alternative-input--httpdevelopergithubcomv3pullscomments---description-----al
      x-api-path-slug: reposownerrepopullsnumbercomments-post
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: number
        description: Id of pull
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Pulls
      - Number
      - Comments
  /repos/{owner}/{repo}/pulls/{number}/merge:
    get:
      summary: Get Repos Owner Repo Pulls Number Merge
      description: Get if a pull request has been merged.
      operationId: get-if-a-pull-request-has-been-merged
      x-api-path-slug: reposownerrepopullsnumbermerge-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: number
        description: Id of pull
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Pulls
      - Number
      - Merge
    put:
      summary: Put Repos Owner Repo Pulls Number Merge
      description: Merge a pull request (Merge Button's)
      operationId: merge-a-pull-request-merge-buttons
      x-api-path-slug: reposownerrepopullsnumbermerge-put
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: number
        description: Id of pull
      - in: path
        name: owner
        description: Name of repository owner
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Pulls
      - Number
      - Merge
  /repos/{owner}/{repo}/readme:
    get:
      summary: Get Repos Owner Repo Readme
      description: |-
        Get the README.
        This method returns the preferred README for a repository.
      operationId: get-the-readmethis-method-returns-the-preferred-readme-for-a-repository
      x-api-path-slug: reposownerreporeadme-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: owner
        description: Name of repository owner
      - in: query
        name: ref
        description: The String name of the Commit/Branch/Tag
      - in: path
        name: repo
        description: Name of repository
      responses:
        200:
          description: OK
      tags:
      - Repos
      - Owner
      - Repo
      - Readme
  /teams/{teamId}/members:
    get:
      summary: Get Teams Team Members
      description: |-
        List team members.
        In order to list members in a team, the authenticated user must be a member
        of the team.
      operationId: list-team-membersin-order-to-list-members-in-a-team-the-authenticated-user-must-be-a-memberof-the-te
      x-api-path-slug: teamsteamidmembers-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: teamId
        description: Id of team
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Team
      - Members
  /teams/{teamId}/members/{username}:
    delete:
      summary: Delete Teams Team Members Username
      description: |-
        The "Remove team member" API is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Remove team membership API instead. It allows you to remove both active and pending memberships.

        Remove team member.
        In order to remove a user from a team, the authenticated user must have 'admin'
        permissions to the team or be an owner of the org that the team is associated
        with.
        NOTE This does not delete the user, it just remove them from the team.
      operationId: the-remove-team-member-api-is-deprecated-and-is-scheduled-for-removal-in-the-next-major-version-of-t
      x-api-path-slug: teamsteamidmembersusername-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: teamId
        description: Id of team
      - in: path
        name: username
        description: Name of a member
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Team
      - Members
      - Username
    get:
      summary: Get Teams Team Members Username
      description: |-
        The "Get team member" API is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Get team membership API instead. It allows you to get both active and pending memberships.

        Get team member.
        In order to get if a user is a member of a team, the authenticated user mus
        be a member of the team.
      operationId: the-get-team-member-api-is-deprecated-and-is-scheduled-for-removal-in-the-next-major-version-of-the-
      x-api-path-slug: teamsteamidmembersusername-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: teamId
        description: Id of team
      - in: path
        name: username
        description: Name of a member
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Team
      - Members
      - Username
    put:
      summary: Put Teams Team Members Username
      description: |-
        The API (described below) is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Add team membership API instead. It allows you to invite new organization members to your teams.

        Add team member.
        In order to add a user to a team, the authenticated user must have 'admin'
        permissions to the team or be an owner of the org that the team is associated
        with.
      operationId: the-api-described-below-is-deprecated-and-is-scheduled-for-removal-in-the-next-major-version-of-the-
      x-api-path-slug: teamsteamidmembersusername-put
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: teamId
        description: Id of team
      - in: path
        name: username
        description: Name of a member
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Team
      - Members
      - Username
  /teams/{teamId}/memberships/{username}:
    delete:
      summary: Delete Teams Team Memberships Username
      description: |-
        Remove team membership.
        In order to remove a membership between a user and a team, the authenticated user must have 'admin' permissions to the team or be an owner of the organization that the team is associated with. NOTE: This does not delete the user, it just removes their membership from the team.
      operationId: remove-team-membershipin-order-to-remove-a-membership-between-a-user-and-a-team-the-authenticated-us
      x-api-path-slug: teamsteamidmembershipsusername-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: teamId
        description: Id of team
      - in: path
        name: username
        description: Name of a member
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Team
      - Memberships
      - Username
    get:
      summary: Get Teams Team Memberships Username
      description: |-
        Get team membership.
        In order to get a user's membership with a team, the authenticated user must be a member of the team or an owner of the team's organization.
      operationId: get-team-membershipin-order-to-get-a-users-membership-with-a-team-the-authenticated-user-must-be-a-m
      x-api-path-slug: teamsteamidmembershipsusername-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: teamId
        description: Id of team
      - in: path
        name: username
        description: Name of a member
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Team
      - Memberships
      - Username
    put:
      summary: Put Teams Team Memberships Username
      description: |-
        Add team membership.
        In order to add a membership between a user and a team, the authenticated user must have 'admin' permissions to the team or be an owner of the organization that the team is associated with.

        If the user is already a part of the team's organization (meaning they're on at least one other team in the organization), this endpoint will add the user to the team.

        If the user is completely unaffiliated with the team's organization (meaning they're on none of the organization's teams), this endpoint will send an invitation to the user via email. This newly-created membership will be in the 'pending' state until the user accepts the invitation, at which point the membership will transition to the 'active' state and the user will be added as a member of the team.
      operationId: add-team-membershipin-order-to-add-a-membership-between-a-user-and-a-team-the-authenticated-user-mus
      x-api-path-slug: teamsteamidmembershipsusername-put
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: teamId
        description: Id of team
      - in: path
        name: username
        description: Name of a member
      responses:
        200:
          description: OK
      tags:
      - Teams
      - Team
      - Memberships
      - Username
  /user/following/{username}:
    delete:
      summary: Delete User Following Username
      description: |-
        Unfollow a user.
        Unfollowing a user requires the user to be logged in and authenticated with
        basic auth or OAuth with the user:follow scope.
      operationId: unfollow-a-userunfollowing-a-user-requires-the-user-to-be-logged-in-and-authenticated-withbasic-auth
      x-api-path-slug: userfollowingusername-delete
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: username
        description: Name of user
      responses:
        200:
          description: OK
      tags:
      - User
      - Following
      - Username
    get:
      summary: Get User Following Username
      description: Check if you are following a user.
      operationId: check-if-you-are-following-a-user
      x-api-path-slug: userfollowingusername-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: username
        description: Name of user
      responses:
        200:
          description: OK
      tags:
      - User
      - Following
      - Username
    put:
      summary: Put User Following Username
      description: |-
        Follow a user.
        Following a user requires the user to be logged in and authenticated with
        basic auth or OAuth with the user:follow scope.
      operationId: follow-a-userfollowing-a-user-requires-the-user-to-be-logged-in-and-authenticated-withbasic-auth-or-
      x-api-path-slug: userfollowingusername-put
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: username
        description: Name of user
      responses:
        200:
          description: OK
      tags:
      - User
      - Following
      - Username
  /users/{username}:
    get:
      summary: Get Users Username
      description: Get a single user.
      operationId: get-a-single-user
      x-api-path-slug: usersusername-get
      parameters:
      - in: header
        name: Accept
        description: Is used to set specified media type
      - in: query
        name: access_token
        description: Your Github OAuth token
      - in: path
        name: username
        description: Name of user
      responses:
        200:
          description: OK
      tags:
      - Users
      - Username
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