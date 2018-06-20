---
name: Flat
x-slug: flat
description: Whether youre a beginner or a professional composer, our user-friendly
  music composition software gives you all the tools that you need to make your own
  sheet music. You can write, listen, share and discover music scores right in your
  web browser on any device
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/apis.md
specificationVersion: "0.14"
apis:
- name: Flat Get a score's metadata
  x-api-slug: flat
  description: |-
    Get the details of a score identified by the `score` parameter in the URL.
    The currently authenticated user must have at least a read access to the document to use this API call.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2//scores/{score}
  tags: Scores,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/scoresscore-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/scoresscore-get-openapi.md
- name: Flat Edit a score's metadata
  x-api-slug: flat
  description: |-
    This API method allows you to change the metadata of a score document (e.g. its `title` or `privacy`), all the properties are optional.

    To edit the file itself, create a new revision using the appropriate method (`POST /v2/scores/{score}/revisions/{revision}`).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2//scores/{score}
  tags: Edit,Scores,Metadata
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/scoresscore-put-openapi.md
- name: Flat List comments
  x-api-slug: flat
  description: This method lists the different comments added on a music score (documents
    and inline) sorted by their post dates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2//scores/{score}/comments
  tags: List,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/scoresscorecomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/scoresscorecomments-get-openapi.md
- name: Flat Post a new comment
  x-api-slug: flat
  description: |-
    Post a document or a contextualized comment on a document.

    Please note that this method includes an anti-spam system for public scores. We don't guarantee that your comments will be accepted and displayed to end-user. Comments are be blocked by returning a `403` HTTP error and hidden from other users when the `spam` property is `true`.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2//scores/{score}/comments
  tags: New,Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/scoresscorecomments-post-openapi.md
- name: Flat Delete a comment
  x-api-slug: flat
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2//scores/{score}/comments/{comment}
  tags: Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/scoresscorecommentscomment-delete-openapi.md
- name: Flat Update an existing comment
  x-api-slug: flat
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2//scores/{score}/comments/{comment}
  tags: Existing,Comment
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/scoresscorecommentscomment-put-openapi.md
- name: Flat Mark the comment as unresolved
  x-api-slug: flat
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2//scores/{score}/comments/{comment}/resolved
  tags: Mark,Comment,As,Unresolved
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/scoresscorecommentscommentresolved-delete-openapi.md
- name: Flat Mark the comment as resolved
  x-api-slug: flat
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2//scores/{score}/comments/{comment}/resolved
  tags: Mark,Comment,As,Resolved
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/scoresscorecommentscommentresolved-put-openapi.md
- name: Flat
  x-api-slug: flat
  description: 'The Flat API allows you to easily extend the abilities of the [Flat
    Platform](https://flat.io), with a wide range of use cases including the following:
    Creating and importing new music scores using MusicXML or MIDI files. Browsing,
    updating, copying, exporting the users scores (for example in MP3, WAV or MIDI).
    Managing educational resources with Flat for Education: creating &amp; updating
    the organization accounts, the classes, rosters and assignments. The Flat API
    is built on HTTP. Our API is RESTful It has predictable resource URLs. It returns
    HTTP response codes to indicate errors. It also accepts and returns JSON in the
    HTTP body.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flat-logo.png
  humanURL: http://flat.io
  baseURL: https://api.flat.io//v2
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/flat/openapi.md
x-common:
- type: x-developer
  url: https://flat.io/developers
- type: x-embeddable
  url: https://flat.io/developers/embed
- type: x-github
  url: https://github.com/FlatIO
- type: x-pricing
  url: https://flat.io/pricing
- type: x-privacy-policy
  url: https://flat.io/help/en/policies/#coppa-and-ferpa-compliance
- type: x-support
  url: https://flat.io/help
- type: x-twitter
  url: https://twitter.com/flat_io
- type: x-website
  url: http://flat.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---