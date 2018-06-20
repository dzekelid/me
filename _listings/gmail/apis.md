---
name: Gmail
x-slug: gmail
description: The Gmail API is a RESTful API that can be used to access Gmail mailboxes
  and send mail. For most web applications (including mobile apps), the Gmail API
  is the best choice for authorized access to a users Gmail data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gmail/apis.md
specificationVersion: "0.14"
apis:
- name: Gmail Get S/MIME Configurations
  x-api-slug: gmail
  description: Lists S/MIME configs for the specified send-as alias.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/sendAs/{sendAsEmail}/smimeInfo
  tags: S/MIME Configuration
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gmail/useridsettingssendassendasemailsmimeinfo-get-openapi.md
- name: Gmail Create S/MIME Configurations
  x-api-slug: gmail
  description: Insert (upload) the given S/MIME config for the specified send-as alias.
    Note that pkcs12 format is required for the key.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/sendAs/{sendAsEmail}/smimeInfo
  tags: S/MIME Configuration
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gmail/useridsettingssendassendasemailsmimeinfo-post-openapi.md
- name: Gmail Delete S/MIME Configurations
  x-api-slug: gmail
  description: Deletes the specified S/MIME config for the specified send-as alias.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/sendAs/{sendAsEmail}/smimeInfo/{id}
  tags: S/MIME Configuration
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gmail/useridsettingssendassendasemailsmimeinfoid-delete-openapi.md
- name: Gmail Get S/MIME Configuration
  x-api-slug: gmail
  description: Gets the specified S/MIME config for the specified send-as alias.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/sendAs/{sendAsEmail}/smimeInfo/{id}
  tags: S/MIME Configuration
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gmail/useridsettingssendassendasemailsmimeinfoid-get-openapi.md
- name: Gmail Create Default S/MIME Configurations
  x-api-slug: gmail
  description: Sets the default S/MIME config for the specified send-as alias.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users//{userId}/settings/sendAs/{sendAsEmail}/smimeInfo/{id}/setDefault
  tags: S/MIME Configuration
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gmail/useridsettingssendassendasemailsmimeinfoidsetdefault-post-openapi.md
- name: Gmail
  x-api-slug: gmail
  description: The Gmail API is a RESTful API that can be used to access Gmail mailboxes
    and send mail. For most web applications (including mobile apps), the Gmail API
    is the best choice for authorized access to a users Gmail data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/gmail-icon.png
  humanURL: https://www.google.com/gmail/
  baseURL: https://www.googleapis.com//gmail/v1/users
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/gmail/openapi.md
x-common:
- type: x-auth-scopes
  url: https://developers.google.com/gmail/api/auth/scopes
- type: x-authentication
  url: https://developers.google.com/gmail/api/auth/about-auth
- type: x-developer
  url: https://developers.google.com/gmail/api/
- type: x-documentation
  url: https://developers.google.com/gmail/api/v1/reference/
- type: x-twitter
  url: https://twitter.com/gmail
- type: x-website
  url: https://www.google.com/gmail/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---