---
name: Facebook
x-slug: facebook
description: Create an account or log into Facebook. Connect with friends, family
  and other people you know. Share photos and videos, send messages and get updates.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
x-kinRank: "9"
x-alexaRank: "3"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/apis.md
specificationVersion: "0.14"
apis:
- name: Facebook Get Album Comments
  x-api-slug: facebook
  description: The comments made on this album
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{album}/comments
  tags: Album,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/albumcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/albumcomments-get-openapi.md
- name: Facebook Post Album Comments
  x-api-slug: facebook
  description: Posts a comment on the album
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{album}/comments
  tags: Album,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/albumcomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/albumcomments-post-openapi.md
- name: Facebook Post Application Achievements
  x-api-slug: facebook
  description: Registers an achievement for the application
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{application}/achievements
  tags: Application,Achievements
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/applicationachievements-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/applicationachievements-post-openapi.md
- name: Facebook Delete Application Achievements
  x-api-slug: facebook
  description: Unregisters an achievement for the application
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{application}/achievements
  tags: Application,Achievements
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/applicationachievements-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/applicationachievements-delete-openapi.md
- name: Facebook Get Checkin Comments
  x-api-slug: facebook
  description: All of the comments on this checkin.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{checkin}/comments
  tags: Checkin,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/checkincomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/checkincomments-get-openapi.md
- name: Facebook Post Checkin Comments
  x-api-slug: facebook
  description: Posts a comment to this checkin.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{checkin}/comments
  tags: Checkin,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/checkincomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/checkincomments-post-openapi.md
- name: Facebook Get Comment
  x-api-slug: facebook
  description: Returns a comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{comment}
  tags: Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/comment-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/comment-get-openapi.md
- name: Facebook Delete Comment
  x-api-slug: facebook
  description: Deletes a comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{comment}
  tags: Comment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/comment-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/comment-delete-openapi.md
- name: Facebook Get Comment Likes
  x-api-slug: facebook
  description: All the likes on this comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{comment}/likes
  tags: Comment,Likes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/commentlikes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/commentlikes-get-openapi.md
- name: Facebook Post Comment Likes
  x-api-slug: facebook
  description: Likes the comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{comment}/likes
  tags: Comment,Likes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/commentlikes-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/commentlikes-post-openapi.md
- name: Facebook Delete Comment Likes
  x-api-slug: facebook
  description: Unlikes the comment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{comment}/likes
  tags: Comment,Likes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/commentlikes-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/commentlikes-delete-openapi.md
- name: Facebook Get Friendlist Members
  x-api-slug: facebook
  description: All of the users who are members of this list.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{friendlist}/members
  tags: Friendlist,Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/friendlistmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/friendlistmembers-get-openapi.md
- name: Facebook Post Friendlist Members User
  x-api-slug: facebook
  description: Adds a user to the friend list
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{friendlist}/members/{user}
  tags: Friendlist,Members,User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/friendlistmembersuser-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/friendlistmembersuser-post-openapi.md
- name: Facebook Delete Friendlist Members User
  x-api-slug: facebook
  description: Removes a user from the friend list
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{friendlist}/members/{user}
  tags: Friendlist,Members,User
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/friendlistmembersuser-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/friendlistmembersuser-delete-openapi.md
- name: Facebook Get Group Members
  x-api-slug: facebook
  description: All of the users who are members of this group
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{group}/members
  tags: Group,Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/groupmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/groupmembers-get-openapi.md
- name: Facebook Get Link Comments
  x-api-slug: facebook
  description: All of the comments on this link.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{link}/comments
  tags: Link,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/linkcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/linkcomments-get-openapi.md
- name: Facebook Post Link Comments
  x-api-slug: facebook
  description: Posts a comment to this link.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{link}/comments
  tags: Link,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/linkcomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/linkcomments-post-openapi.md
- name: Facebook Get Note Comments
  x-api-slug: facebook
  description: All of the comments on this note.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{note}/comments
  tags: Note,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/notecomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/notecomments-get-openapi.md
- name: Facebook Post Note Comments
  x-api-slug: facebook
  description: Posts a comment to this note.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{note}/comments
  tags: Note,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/notecomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/notecomments-post-openapi.md
- name: Facebook Get Photo Comments
  x-api-slug: facebook
  description: All of the comments on this photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{photo}/comments
  tags: Photo,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/photocomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/photocomments-get-openapi.md
- name: Facebook Post Photo Comments
  x-api-slug: facebook
  description: Posts a comment to this photo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{photo}/comments
  tags: Photo,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/photocomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/photocomments-post-openapi.md
- name: Facebook Get Add Comments
  x-api-slug: facebook
  description: All of the comments on this post.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{post}/comments
  tags: Post,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/postcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/postcomments-get-openapi.md
- name: Facebook Post Add Comments
  x-api-slug: facebook
  description: Posts a comment to this post.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{post}/comments
  tags: Post,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/postcomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/postcomments-post-openapi.md
- name: Facebook Get Status Comments
  x-api-slug: facebook
  description: All of the comments on this status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{status}/comments
  tags: Status,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/statuscomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/statuscomments-get-openapi.md
- name: Facebook Post Status Comments
  x-api-slug: facebook
  description: Posts a comment to this status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{status}/comments
  tags: Status,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/statuscomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/statuscomments-post-openapi.md
- name: Facebook Post User Achievements
  x-api-slug: facebook
  description: Posts an achievement for the user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{user}/achievements
  tags: User,Achievements
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/userachievements-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/userachievements-post-openapi.md
- name: Facebook Delete User Achievements
  x-api-slug: facebook
  description: Deletes an achievement for the user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{user}/achievements
  tags: User,Achievements
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/userachievements-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/userachievements-delete-openapi.md
- name: Facebook Get User Games
  x-api-slug: facebook
  description: Games the user has added to the Arts and Entertainment section of their
    profile.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{user}/games
  tags: User,Games
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/usergames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/usergames-get-openapi.md
- name: Facebook Get User Home
  x-api-slug: facebook
  description: The user's news feed
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{user}/home
  tags: User,Home
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/userhome-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/userhome-get-openapi.md
- name: Facebook Get User Payments
  x-api-slug: facebook
  description: The transactions the user placed with an application.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{user}/payments
  tags: User,Payments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/userpayments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/userpayments-get-openapi.md
- name: Facebook Get Veo Comments
  x-api-slug: facebook
  description: All of the comments on this video.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{video}/comments
  tags: Video,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/videocomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/videocomments-get-openapi.md
- name: Facebook Post Veo Comments
  x-api-slug: facebook
  description: Posts a comment to this video.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com////{video}/comments
  tags: Video,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/videocomments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/videocomments-post-openapi.md
- name: Facebook
  x-api-slug: facebook
  description: Create an account or log into Facebook. Connect with friends, family
    and other people you know. Share photos and videos, send messages and get updates.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/196-facebook.jpg
  humanURL: http:///business
  baseURL: https://graph.facebook.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/facebook/openapi.md
x-common:
- type: x-android-sdk
  url: https://developers.facebook.com/docs/android/share
- type: x-apigee-console
  url: https://api.apigee.com/v1/consoles/facebook/apidescription?format=internal&ver=1386216190000
- type: x-application-gallery
  url: https://developers.facebook.com/docs/showcase/
- type: x-base
  url: https://graph.facebook.com
- type: x-best-practices
  url: https://developers.facebook.com/docs/sharing/best-practices
- type: x-blog
  url: http://blog.facebook.com
- type: x-blog-rss
  url: https://www.facebook.com/business/news/rss/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/facebook
- type: x-crunchbase
  url: https://crunchbase.com/organization/facebook
- type: x-developer
  url: https://developers.facebook.com/
- type: x-forum
  url: https://www.facebook.com/groups/fbdevelopers
- type: x-github
  url: https://github.com/facebook
- type: x-ios-sdk
  url: https://developers.facebook.com/docs/ios/share
- type: x-issues
  url: https://developers.facebook.com/status/issues/
- type: x-javascript-library
  url: https://developers.facebook.com/docs/reference/javascript/
- type: x-partners
  url: https://facebookmarketingpartners.com/
- type: x-php-sdk
  url: https://developers.facebook.com/docs/reference/php/
- type: x-plugins
  url: https://developers.facebook.com/docs/plugins/
- type: x-privacy
  url: https://www.facebook.com/settings?tab=privacy
- type: x-road-map
  url: https://developers.facebook.com/docs/apps/migrations
- type: x-status
  url: https://developers.facebook.com/status/
- type: x-terms-of-service
  url: https://www.facebook.com/terms
- type: x-terms-of-service
  url: https://developers.facebook.com/policy
- type: x-transparency-report
  url: https://www.facebook.com/about/government_requests
- type: x-twitter
  url: https://twitter.com/facebook
- type: x-website
  url: http:///business
- type: x-website
  url: http://facebook.com
- type: x-website
  url: https://facebook.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---