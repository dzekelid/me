---
name: Flickr
x-slug: flickr
description: Flickr (pronounced flicker) is an image hosting and video hosting website,
  and web services suite that was created by Ludicorp in 2004 and acquired by Yahoo
  in 2005. In addition to being a popular website for users to share and embed personal
  photographs, and effectively an online community, the service is widely used by
  photo researchers and by bloggers to host images that they embed in blogs and social
  media.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/apis.md
specificationVersion: "0.14"
apis:
- name: Flickr Activity User Comments
  x-api-slug: flickr
  description: Returns a list of recent activity on photos commented on by the calling
    user. Do not poll this method more than once an hour.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.activity.userComments
  tags: Activity,UserComments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-activity-usercomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-activity-usercomments-get-openapi.md
- name: Flickr Galleries Edit Meta
  x-api-slug: flickr
  description: Modify the metadata for a gallery.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.galleries.editMeta
  tags: Galleries,EditMeta
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-galleries-editmeta-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-galleries-editmeta-post-openapi.md
- name: Flickr Groups Members Get List
  x-api-slug: flickr
  description: Get a list of the members of a group. The call must be signed on behalf
    of a Flickr member, and the ability to see the group membership will be determined
    by the Flickr member's group privileges.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.groups.members.getList
  tags: Groups,Members,GetList
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-groups-members-getlist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-groups-members-getlist-get-openapi.md
- name: Flickr Machinetags Get Namespaces
  x-api-slug: flickr
  description: Return a list of unique namespaces, optionally limited by a given predicate,
    in alphabetical order.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.machinetags.getNamespaces
  tags: Machinetags,GetNamespaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-machinetags-getnamespaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-machinetags-getnamespaces-get-openapi.md
- name: Flickr People Find By Username
  x-api-slug: flickr
  description: Return a user's NSID, given their username.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.people.findByUsername
  tags: People,FindByUsername
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-people-findbyusername-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-people-findbyusername-get-openapi.md
- name: Flickr Photos Set Meta
  x-api-slug: flickr
  description: Set the meta information for a photo.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photos.setMeta
  tags: Photos,SetMeta
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-setmeta-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-setmeta-post-openapi.md
- name: Flickr Photos Comments Add Comment
  x-api-slug: flickr
  description: Add comment to a photo as the currently authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photos.comments.addComment
  tags: Photos,Comments,AddComment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-comments-addcomment-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-comments-addcomment-post-openapi.md
- name: Flickr Photos Comments Delete Comment
  x-api-slug: flickr
  description: Delete comment as the currently authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photos.comments.deleteComment
  tags: Photos,Comments,DeleteComment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-comments-deletecomment-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-comments-deletecomment-post-openapi.md
- name: Flickr Photos Comments Edit Comment
  x-api-slug: flickr
  description: Edit the text of a comment as the currently authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photos.comments.editComment
  tags: Photos,Comments,EditComment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-comments-editcomment-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-comments-editcomment-post-openapi.md
- name: Flickr Photos Comments Get List
  x-api-slug: flickr
  description: Returns the comments for a photo.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photos.comments.getList
  tags: Photos,Comments,GetList
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-comments-getlist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-comments-getlist-get-openapi.md
- name: Flickr Photos Comments Get Recent For Contacts
  x-api-slug: flickr
  description: Return the list of photos belonging to your contacts that have been
    commented on recently.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photos.comments.getRecentForContacts
  tags: Photos,Comments,GetRecentForContacts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-comments-getrecentforcontacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photos-comments-getrecentforcontacts-get-openapi.md
- name: Flickr Photosets Edit Meta
  x-api-slug: flickr
  description: Modify the meta-data for a photoset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photosets.editMeta
  tags: Photosets,EditMeta
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photosets-editmeta-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photosets-editmeta-post-openapi.md
- name: Flickr Photosets Comments Add Comment
  x-api-slug: flickr
  description: Add a comment to a photoset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photosets.comments.addComment
  tags: Photosets,Comments,AddComment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photosets-comments-addcomment-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photosets-comments-addcomment-post-openapi.md
- name: Flickr Photosets Comments Delete Comment
  x-api-slug: flickr
  description: Delete a photoset comment as the currently authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photosets.comments.deleteComment
  tags: Photosets,Comments,DeleteComment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photosets-comments-deletecomment-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photosets-comments-deletecomment-post-openapi.md
- name: Flickr Photosets Comments Edit Comment
  x-api-slug: flickr
  description: Edit the text of a comment as the currently authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photosets.comments.editComment
  tags: Photosets,Comments,EditComment
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photosets-comments-editcomment-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photosets-comments-editcomment-post-openapi.md
- name: Flickr Photosets Comments Get List
  x-api-slug: flickr
  description: Returns the comments for a photoset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.photosets.comments.getList
  tags: Photosets,Comments,GetList
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photosets-comments-getlist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-photosets-comments-getlist-get-openapi.md
- name: Flickr Reflection Get Method Info
  x-api-slug: flickr
  description: Returns information for a given Flickr API method.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.reflection.getMethodInfo
  tags: Reflection,GetMethodInfo
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-reflection-getmethodinfo-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-reflection-getmethodinfo-get-openapi.md
- name: Flickr Reflection Get Methods
  x-api-slug: flickr
  description: Returns a list of available Flickr API methods.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.reflection.getMethods
  tags: Reflection,GetMethods
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-reflection-getmethods-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/restmethodflickr-reflection-getmethods-get-openapi.md
- name: Flickr
  x-api-slug: flickr
  description: The Flickr API consists of a set of callable methods, and some API
    endpoints.  To perform an action using the Flickr API, you need to select a calling
    convention, send a request to its endpoint specifying a method and some arguments,
    and will receive a formatted response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services/
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flickr/openapi.md
x-common:
- type: x-authentication
  url: https://www.flickr.com/services/api/auth.oauth.html
- type: x-base
  url: https://api.flickr.com/services/
- type: x-developer
  url: https://www.flickr.com/services/api/
- type: x-getting-started
  url: https://www.flickr.com/services/developer/
- type: x-privacy
  url: https://info.yahoo.com/privacy/us/yahoo/flickr/details.html
- type: x-support
  url: https://help.yahoo.com/kb/flickr-for-desktop
- type: x-terms-of-service
  url: https://www.flickr.com/services/api/tos/
- type: x-twitter
  url: https://twitter.com/flickr
- type: x-website
  url: http://www.flickr.com/
- type: x-website
  url: http://flickr.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---