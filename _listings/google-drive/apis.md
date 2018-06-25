---
name: Google Drive
x-slug: google-drive
description: Google Drive is a file storage and synchronization service operated by
  Google. It allows users to store files in the cloud, synchronize files across devices,
  and share files. Google Drive encompasses Google Docs, Sheets and Slides, an office
  suite that permits collaborative editing of documents, spreadsheets, presentations,
  drawings, forms, and more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/apis.md
specificationVersion: "0.14"
apis:
- name: Google Drive Get File Comments
  x-api-slug: google-drive
  description: Lists a file's comments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
  humanURL: https://developers.google.com/drive/
  baseURL: https://www.googleapis.com//drive/v3//files/{fileId}/comments
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/filesfileidcomments-get-openapi.md
- name: Google Drive Create File Comment
  x-api-slug: google-drive
  description: Creates a new comment on a file.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
  humanURL: https://developers.google.com/drive/
  baseURL: https://www.googleapis.com//drive/v3//files/{fileId}/comments
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/filesfileidcomments-post-openapi.md
- name: Google Drive Delete File Comment
  x-api-slug: google-drive
  description: Deletes a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
  humanURL: https://developers.google.com/drive/
  baseURL: https://www.googleapis.com//drive/v3//files/{fileId}/comments/{commentId}
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/filesfileidcommentscommentid-delete-openapi.md
- name: Google Drive Get File Comment
  x-api-slug: google-drive
  description: Gets a comment by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
  humanURL: https://developers.google.com/drive/
  baseURL: https://www.googleapis.com//drive/v3//files/{fileId}/comments/{commentId}
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/filesfileidcommentscommentid-get-openapi.md
- name: Google Drive Update File Comment
  x-api-slug: google-drive
  description: Updates a comment with patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
  humanURL: https://developers.google.com/drive/
  baseURL: https://www.googleapis.com//drive/v3//files/{fileId}/comments/{commentId}
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/filesfileidcommentscommentid-patch-openapi.md
- name: Google Drive Get File Comment Replies
  x-api-slug: google-drive
  description: Lists a comment's replies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
  humanURL: https://developers.google.com/drive/
  baseURL: https://www.googleapis.com//drive/v3//files/{fileId}/comments/{commentId}/replies
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/filesfileidcommentscommentidreplies-get-openapi.md
- name: Google Drive Create File Comment Reply
  x-api-slug: google-drive
  description: Creates a new reply to a comment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
  humanURL: https://developers.google.com/drive/
  baseURL: https://www.googleapis.com//drive/v3//files/{fileId}/comments/{commentId}/replies
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/filesfileidcommentscommentidreplies-post-openapi.md
- name: Google Drive Delete File Comment Reply
  x-api-slug: google-drive
  description: Deletes a reply.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
  humanURL: https://developers.google.com/drive/
  baseURL: https://www.googleapis.com//drive/v3//files/{fileId}/comments/{commentId}/replies/{replyId}
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/filesfileidcommentscommentidrepliesreplyid-delete-openapi.md
- name: Google Drive Get File Comment Reply
  x-api-slug: google-drive
  description: Gets a reply by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
  humanURL: https://developers.google.com/drive/
  baseURL: https://www.googleapis.com//drive/v3//files/{fileId}/comments/{commentId}/replies/{replyId}
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/filesfileidcommentscommentidrepliesreplyid-get-openapi.md
- name: Google Drive Update File Comment Reply
  x-api-slug: google-drive
  description: Updates a reply with patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
  humanURL: https://developers.google.com/drive/
  baseURL: https://www.googleapis.com//drive/v3//files/{fileId}/comments/{commentId}/replies/{replyId}
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/filesfileidcommentscommentidrepliesreplyid-patch-openapi.md
- name: Google Drive
  x-api-slug: google-drive
  description: Google Drive is a file storage and synchronization service operated
    by Google. It allows users to store files in the cloud, synchronize files across
    devices, and share files. Google Drive encompasses Google Docs, Sheets and Slides,
    an office suite that permits collaborative editing of documents, spreadsheets,
    presentations, drawings, forms, and more.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-drive-logo-new.png
  humanURL: https://developers.google.com/drive/
  baseURL: https://www.googleapis.com//drive/v3
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-drive/openapi.md
x-common:
- type: x-best-practices
  url: https://developers.google.com/drive/v3/web/practices
- type: x-branding-guidelines
  url: https://developers.google.com/drive/v3/web/marketing
- type: x-change-log
  url: https://developers.google.com/drive/release-notes
- type: x-code
  url: https://developers.google.com/drive/v3/web/downloads
- type: x-documentation
  url: https://developers.google.com/drive/v3/web/about-sdk
- type: x-github
  url: https://github.com/googledrive
- type: x-issues
  url: https://code.google.com/a/google.com/p/apps-api-issues/issues/list?q=API%3DDrive
- type: x-performance
  url: https://developers.google.com/drive/v3/web/performance
- type: x-support
  url: https://developers.google.com/drive/v3/web/support
- type: x-website
  url: https://developers.google.com/drive/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---