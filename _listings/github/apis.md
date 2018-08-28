---
name: GitHub
x-slug: github
description: GitHub brings together the worlds largest community of developers to
  discover, share, and build better software. From open source projects to private
  team repositories, were your all-in-one platform for collaborative development.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
x-kinRank: "10"
x-alexaRank: "64"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/apis.md
specificationVersion: "0.14"
apis:
- name: Github Get Gists  Comments
  x-api-slug: github
  description: List comments on a gist.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments
  tags: Gists, , Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/gistsidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/gistsidcomments-get-openapi.md
- name: Github Add Gists  Comments
  x-api-slug: github
  description: Create a commen
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments
  tags: Gists, , Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/gistsidcomments-post-openapi.md
- name: Github Delete Gists  Comments Comment
  x-api-slug: github
  description: Delete a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments/{commentId}
  tags: Gists, , Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/gistsidcommentscommentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/gistsidcommentscommentid-delete-openapi.md
- name: Github Get Gists  Comments Comment
  x-api-slug: github
  description: Get a single comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments/{commentId}
  tags: Gists, , Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/gistsidcommentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/gistsidcommentscommentid-get-openapi.md
- name: Github Patch Gists  Comments Comment
  x-api-slug: github
  description: Edit a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////gists/{id}/comments/{commentId}
  tags: Gists, , Comments, Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/gistsidcommentscommentid-patch-openapi.md
- name: Github Get Meta
  x-api-slug: github
  description: This gives some information about GitHub.com, the service.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////meta
  tags: Meta
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/meta-get-openapi.md
- name: Github Get Orgs Org Members
  x-api-slug: github
  description: |-
    Members list.
    List all users who are members of an organization. A member is a user tha
    belongs to at least 1 team in the organization. If the authenticated user
    is also an owner of this organization then both concealed and public members
    will be returned. If the requester is not an owner of the organization the
    query will be redirected to the public members list.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/members
  tags: Orgs, Org, Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgmembers-get-openapi.md
- name: Github Delete Orgs Org Members Username
  x-api-slug: github
  description: |-
    Remove a member.
    Removing a user from this list will remove them from all teams and they
    will no longer have any access to the organization's repositories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/members/{username}
  tags: Orgs, Org, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgmembersusername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgmembersusername-delete-openapi.md
- name: Github Get Orgs Org Members Username
  x-api-slug: github
  description: Check if a user is, publicly or privately, a member of the organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/members/{username}
  tags: Orgs, Org, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgmembersusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgmembersusername-get-openapi.md
- name: Github Get Orgs Org Public Members
  x-api-slug: github
  description: |-
    Public members list.
    Members of an organization can choose to have their membership publicized
    or not.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/public_members
  tags: Orgs, Org, Public, Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgpublic-members-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgpublic-members-get-openapi.md
- name: Github Delete Orgs Org Public Members Username
  x-api-slug: github
  description: Conceal a user's membership.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/public_members/{username}
  tags: Orgs, Org, Public, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgpublic-membersusername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgpublic-membersusername-delete-openapi.md
- name: Github Get Orgs Org Public Members Username
  x-api-slug: github
  description: Check public membership.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/public_members/{username}
  tags: Orgs, Org, Public, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgpublic-membersusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgpublic-membersusername-get-openapi.md
- name: Github Put Orgs Org Public Members Username
  x-api-slug: github
  description: Publicize a user's membership.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////orgs/{org}/public_members/{username}
  tags: Orgs, Org, Public, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgpublic-membersusername-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/orgsorgpublic-membersusername-put-openapi.md
- name: Github Get Repos Owner Repo Comments
  x-api-slug: github
  description: |-
    List commit comments for a repository.
    Comments are ordered by ascending ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/comments
  tags: Repos, Owner, Repo, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepocomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepocomments-get-openapi.md
- name: Github Delete Repos Owner Repo Comments Comment
  x-api-slug: github
  description: Delete a commit comment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/comments/{commentId}
  tags: Repos, Owner, Repo, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepocommentscommentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepocommentscommentid-delete-openapi.md
- name: Github Get Repos Owner Repo Comments Comment
  x-api-slug: github
  description: Get a single commit comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/comments/{commentId}
  tags: Repos, Owner, Repo, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepocommentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepocommentscommentid-get-openapi.md
- name: Github Patch Repos Owner Repo Comments Comment
  x-api-slug: github
  description: Update a commit comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/comments/{commentId}
  tags: Repos, Owner, Repo, Comments, Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepocommentscommentid-patch-openapi.md
- name: Github Get Repos Owner Repo Commits Shacode Comments
  x-api-slug: github
  description: List comments for a single commitList comments for a single commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/commits/{shaCode}/comments
  tags: Repos, Owner, Repo, Commits, Shacode, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepocommitsshacodecomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepocommitsshacodecomments-get-openapi.md
- name: Github Add Repos Owner Repo Commits Shacode Comments
  x-api-slug: github
  description: Create a commit comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/commits/{shaCode}/comments
  tags: Repos, Owner, Repo, Commits, Shacode, Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepocommitsshacodecomments-post-openapi.md
- name: Github Get Repos Owner Repo Deployments
  x-api-slug: github
  description: Users with pull access can view deployments for a repository
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/deployments
  tags: Repos, Owner, Repo, Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepodeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepodeployments-get-openapi.md
- name: Github Add Repos Owner Repo Deployments
  x-api-slug: github
  description: Users with push access can create a deployment for a given ref
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/deployments
  tags: Repos, Owner, Repo, Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepodeployments-post-openapi.md
- name: Github Get Repos Owner Repo Deployments  Statuses
  x-api-slug: github
  description: Users with pull access can view deployment statuses for a deployment
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/deployments/{id}/statuses
  tags: Repos, Owner, Repo, Deployments, , Statuses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepodeploymentsidstatuses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepodeploymentsidstatuses-get-openapi.md
- name: Github Add Repos Owner Repo Deployments  Statuses
  x-api-slug: github
  description: |-
    Create a Deployment Status
    Users with push access can create deployment statuses for a given deployment:
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/deployments/{id}/statuses
  tags: Repos, Owner, Repo, Deployments, , Statuses
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepodeploymentsidstatuses-post-openapi.md
- name: Github Get Repos Owner Repo Issues Comments
  x-api-slug: github
  description: List comments in a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments
  tags: Repos, Owner, Repo, Issues, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuescomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuescomments-get-openapi.md
- name: Github Delete Repos Owner Repo Issues Comments Comment
  x-api-slug: github
  description: Delete a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments/{commentId}
  tags: Repos, Owner, Repo, Issues, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuescommentscommentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuescommentscommentid-delete-openapi.md
- name: Github Get Repos Owner Repo Issues Comments Comment
  x-api-slug: github
  description: Get a single comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments/{commentId}
  tags: Repos, Owner, Repo, Issues, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuescommentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuescommentscommentid-get-openapi.md
- name: Github Patch Repos Owner Repo Issues Comments Comment
  x-api-slug: github
  description: Edit a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/comments/{commentId}
  tags: Repos, Owner, Repo, Issues, Comments, Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuescommentscommentid-patch-openapi.md
- name: Github Get Repos Owner Repo Issues Number Comments
  x-api-slug: github
  description: List comments on an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/comments
  tags: Repos, Owner, Repo, Issues, Number, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuesnumbercomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuesnumbercomments-get-openapi.md
- name: Github Add Repos Owner Repo Issues Number Comments
  x-api-slug: github
  description: Create a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/comments
  tags: Repos, Owner, Repo, Issues, Number, Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuesnumbercomments-post-openapi.md
- name: Github Delete Repos Owner Repo Issues Number Labels Name
  x-api-slug: github
  description: Remove a label from an issue.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/issues/{number}/labels/{name}
  tags: Repos, Owner, Repo, Issues, Number, Labels, Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuesnumberlabelsname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepoissuesnumberlabelsname-delete-openapi.md
- name: Github Delete Repos Owner Repo Labels Name
  x-api-slug: github
  description: Delete a label.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/labels/{name}
  tags: Repos, Owner, Repo, Labels, Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepolabelsname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepolabelsname-delete-openapi.md
- name: Github Get Repos Owner Repo Labels Name
  x-api-slug: github
  description: Get a single label.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/labels/{name}
  tags: Repos, Owner, Repo, Labels, Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepolabelsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepolabelsname-get-openapi.md
- name: Github Patch Repos Owner Repo Labels Name
  x-api-slug: github
  description: Update a label.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/labels/{name}
  tags: Repos, Owner, Repo, Labels, Name
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepolabelsname-patch-openapi.md
- name: Github Add Repos Owner Repo Merges
  x-api-slug: github
  description: Perform a merge.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/merges
  tags: Repos, Owner, Repo, Merges
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepomerges-post-openapi.md
- name: Github Get Repos Owner Repo Pulls Comments
  x-api-slug: github
  description: |-
    List comments in a repository.
    By default, Review Comments are ordered by ascending ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments
  tags: Repos, Owner, Repo, Pulls, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullscomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullscomments-get-openapi.md
- name: Github Delete Repos Owner Repo Pulls Comments Comment
  x-api-slug: github
  description: Delete a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments/{commentId}
  tags: Repos, Owner, Repo, Pulls, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullscommentscommentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullscommentscommentid-delete-openapi.md
- name: Github Get Repos Owner Repo Pulls Comments Comment
  x-api-slug: github
  description: Get a single comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments/{commentId}
  tags: Repos, Owner, Repo, Pulls, Comments, Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullscommentscommentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullscommentscommentid-get-openapi.md
- name: Github Patch Repos Owner Repo Pulls Comments Comment
  x-api-slug: github
  description: Edit a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/comments/{commentId}
  tags: Repos, Owner, Repo, Pulls, Comments, Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullscommentscommentid-patch-openapi.md
- name: Github Get Repos Owner Repo Pulls Number Comments
  x-api-slug: github
  description: List comments on a pull request.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/comments
  tags: Repos, Owner, Repo, Pulls, Number, Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullsnumbercomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullsnumbercomments-get-openapi.md
- name: Github Add Repos Owner Repo Pulls Number Comments
  x-api-slug: github
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
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/comments
  tags: Repos, Owner, Repo, Pulls, Number, Comments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullsnumbercomments-post-openapi.md
- name: Github Get Repos Owner Repo Pulls Number Merge
  x-api-slug: github
  description: Get if a pull request has been merged.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/merge
  tags: Repos, Owner, Repo, Pulls, Number, Merge
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullsnumbermerge-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullsnumbermerge-get-openapi.md
- name: Github Put Repos Owner Repo Pulls Number Merge
  x-api-slug: github
  description: Merge a pull request (Merge Button's)
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/pulls/{number}/merge
  tags: Repos, Owner, Repo, Pulls, Number, Merge
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerrepopullsnumbermerge-put-openapi.md
- name: Github Get Repos Owner Repo Readme
  x-api-slug: github
  description: |-
    Get the README.
    This method returns the preferred README for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////repos/{owner}/{repo}/readme
  tags: Repos, Owner, Repo, Readme
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerreporeadme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/reposownerreporeadme-get-openapi.md
- name: Github Get Teams Team Members
  x-api-slug: github
  description: |-
    List team members.
    In order to list members in a team, the authenticated user must be a member
    of the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/members
  tags: Teams, Team, Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembers-get-openapi.md
- name: Github Delete Teams Team Members Username
  x-api-slug: github
  description: |-
    The "Remove team member" API is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Remove team membership API instead. It allows you to remove both active and pending memberships.

    Remove team member.
    In order to remove a user from a team, the authenticated user must have 'admin'
    permissions to the team or be an owner of the org that the team is associated
    with.
    NOTE This does not delete the user, it just remove them from the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/members/{username}
  tags: Teams, Team, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembersusername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembersusername-delete-openapi.md
- name: Github Get Teams Team Members Username
  x-api-slug: github
  description: |-
    The "Get team member" API is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Get team membership API instead. It allows you to get both active and pending memberships.

    Get team member.
    In order to get if a user is a member of a team, the authenticated user mus
    be a member of the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/members/{username}
  tags: Teams, Team, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembersusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembersusername-get-openapi.md
- name: Github Put Teams Team Members Username
  x-api-slug: github
  description: |-
    The API (described below) is deprecated and is scheduled for removal in the next major version of the API. We recommend using the Add team membership API instead. It allows you to invite new organization members to your teams.

    Add team member.
    In order to add a user to a team, the authenticated user must have 'admin'
    permissions to the team or be an owner of the org that the team is associated
    with.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/members/{username}
  tags: Teams, Team, Members, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembersusername-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembersusername-put-openapi.md
- name: Github Delete Teams Team Memberships Username
  x-api-slug: github
  description: |-
    Remove team membership.
    In order to remove a membership between a user and a team, the authenticated user must have 'admin' permissions to the team or be an owner of the organization that the team is associated with. NOTE: This does not delete the user, it just removes their membership from the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/memberships/{username}
  tags: Teams, Team, Memberships, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembershipsusername-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembershipsusername-delete-openapi.md
- name: Github Get Teams Team Memberships Username
  x-api-slug: github
  description: |-
    Get team membership.
    In order to get a user's membership with a team, the authenticated user must be a member of the team or an owner of the team's organization.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/memberships/{username}
  tags: Teams, Team, Memberships, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembershipsusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembershipsusername-get-openapi.md
- name: Github Put Teams Team Memberships Username
  x-api-slug: github
  description: |-
    Add team membership.
    In order to add a membership between a user and a team, the authenticated user must have 'admin' permissions to the team or be an owner of the organization that the team is associated with.

    If the user is already a part of the team's organization (meaning they're on at least one other team in the organization), this endpoint will add the user to the team.

    If the user is completely unaffiliated with the team's organization (meaning they're on none of the organization's teams), this endpoint will send an invitation to the user via email. This newly-created membership will be in the 'pending' state until the user accepts the invitation, at which point the membership will transition to the 'active' state and the user will be added as a member of the team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////teams/{teamId}/memberships/{username}
  tags: Teams, Team, Memberships, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembershipsusername-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/teamsteamidmembershipsusername-put-openapi.md
- name: Github Delete User Following Username
  x-api-slug: github
  description: |-
    Unfollow a user.
    Unfollowing a user requires the user to be logged in and authenticated with
    basic auth or OAuth with the user:follow scope.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/following/{username}
  tags: User, Following, Username
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/userfollowingusername-delete-openapi.md
- name: Github Get User Following Username
  x-api-slug: github
  description: Check if you are following a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/following/{username}
  tags: User, Following, Username
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/userfollowingusername-get-openapi.md
- name: Github Put User Following Username
  x-api-slug: github
  description: |-
    Follow a user.
    Following a user requires the user to be logged in and authenticated with
    basic auth or OAuth with the user:follow scope.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////user/following/{username}
  tags: User, Following, Username
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/userfollowingusername-put-openapi.md
- name: Github Get Users Username
  x-api-slug: github
  description: Get a single user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}
  tags: Users, Username
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusername-get-openapi.md
- name: Github Get Users Username Events
  x-api-slug: github
  description: If you are authenticated as the given user, you will see your private
    events. Otherwise, you'll only see public events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/events
  tags: Users, Username, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernameevents-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernameevents-get-openapi.md
- name: Github Get Users Username Events Orgs Org
  x-api-slug: github
  description: This is the user's organization dashboard. You must be authenticated
    as the user to view this.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/events/orgs/{org}
  tags: Users, Username, Events, Orgs, Org
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernameeventsorgsorg-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernameeventsorgsorg-get-openapi.md
- name: Github Get Users Username Followers
  x-api-slug: github
  description: List a user's followers
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/followers
  tags: Users, Username, Followers
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamefollowers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamefollowers-get-openapi.md
- name: Github Get Users Username Following Targetuser
  x-api-slug: github
  description: Check if one user follows another.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/following/{targetUser}
  tags: Users, Username, Following, Targetuser
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamefollowingtargetuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamefollowingtargetuser-get-openapi.md
- name: Github Get Users Username Gists
  x-api-slug: github
  description: List a users gists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/gists
  tags: Users, Username, Gists
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamegists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamegists-get-openapi.md
- name: Github Get Users Username Keys
  x-api-slug: github
  description: |-
    List public keys for a user.
    Lists the verified public keys for a user. This is accessible by anyone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/keys
  tags: Users, Username, Keys
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamekeys-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamekeys-get-openapi.md
- name: Github Get Users Username Orgs
  x-api-slug: github
  description: List all public organizations for a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/orgs
  tags: Users, Username, Orgs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernameorgs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernameorgs-get-openapi.md
- name: Github Get Users Username Received Events
  x-api-slug: github
  description: These are events that you'll only see public events.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/received_events
  tags: Users, Username, Received, Events
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamereceived-events-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamereceived-events-get-openapi.md
- name: Github Get Users Username Received Events Public
  x-api-slug: github
  description: List public events that a user has received
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/received_events/public
  tags: Users, Username, Received, Events, Public
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamereceived-eventspublic-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamereceived-eventspublic-get-openapi.md
- name: Github Get Users Username Repos
  x-api-slug: github
  description: List public repositories for the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/repos
  tags: Users, Username, Repos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamerepos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamerepos-get-openapi.md
- name: Github Get Users Username Starred
  x-api-slug: github
  description: List repositories being starred by a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/starred
  tags: Users, Username, Starred
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamestarred-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamestarred-get-openapi.md
- name: Github Get Users Username Subscriptions
  x-api-slug: github
  description: List repositories being watched by a user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com////users/{username}/subscriptions
  tags: Users, Username, Subscriptions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamesubscriptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/usersusernamesubscriptions-get-openapi.md
- name: Github
  x-api-slug: github
  description: GitHub brings together the worlds largest community of developers to
    discover, share, and build better software. From open source projects to private
    team repositories, were your all-in-one platform for collaborative development.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/github-logo.png
  humanURL: https://github.com
  baseURL: https://api.github.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/github/openapi.md
x-common:
- type: x--net-library
  url: https://github.com/octokit/octokit.net
- type: x-base
  url: https://api.github.com
- type: x-blog
  url: http://github.com/blog
- type: x-blog-rss
  url: https://github.com/blog/subscribe
- type: x-change-log
  url: https://developer.github.com/changes/
- type: x-contact-form
  url: https://github.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/github
- type: x-crunchbase
  url: https://crunchbase.com/organization/github
- type: x-developer
  url: https://developer.github.com/
- type: x-github
  url: https://github.com/github
- type: x-guides
  url: https://developer.github.com/guides/
- type: x-ios-sdk
  url: https://github.com/octokit/octokit.objc
- type: x-pricing
  url: https://github.com/pricing
- type: x-privacy
  url: http://help.github.com/privacy-policy/
- type: x-ruby-library
  url: https://github.com/octokit/octokit.rb
- type: x-security
  url: http://help.github.com/security/
- type: x-status
  url: https://status.github.com/
- type: x-terms-of-service
  url: http://help.github.com/terms-of-service/
- type: x-transparency-report
  url: https://github.com/blog/1987-github-s-2014-transparency-report
- type: x-twitter
  url: https://twitter.com/github
- type: x-webhooks
  url: https://developer.github.com/webhooks/
- type: x-website
  url: https://github.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---