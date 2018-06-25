---
name: MotaWord
x-slug: motaword
description: MotaWord is the world&rsquo;s fastest, lowest cost, cloud-based, collaborative
  business translation platform.MotaWord combines the efforts of talented human translators
  through the use of a cloud based translation platform. Our translators are able
  to login simultaneously into projects that fit their language combination and provide
  translation service collaboratively - while also seeing the whole content for contextual
  purposes. This ability to simultaneously utilize multiple translators makes MotaWord
  exceptionally fast and highly accurate.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/apis.md
specificationVersion: "0.14"
apis:
- name: Mota Word Get your account information and summary.
  x-api-slug: mota-word
  description: Get your account information and summary..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////me
  tags: Me
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/me-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/me-get-openapi.md
- name: Mota Word Get a list of comments belonging to this activity.
  x-api-slug: mota-word
  description: Get a list of comments belonging to this activity..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/activities/{activityId}/comments
  tags: Projects,ProjectId,Activities,ActivityId,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectidactivitiesactivityidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectidactivitiesactivityidcomments-get-openapi.md
- name: Mota Word Get a list of activity comments throughout the whole project.
  x-api-slug: mota-word
  description: Get a list of activity comments throughout the whole project..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/comments
  tags: Projects,ProjectId,Comments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectidcomments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectidcomments-get-openapi.md
- name: Mota Word Get a list of documents
  x-api-slug: mota-word
  description: Get a list of documents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents
  tags: Projects,ProjectId,Documents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocuments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocuments-get-openapi.md
- name: Mota Word Upload a new document
  x-api-slug: mota-word
  description: Upload a new document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents
  tags: Projects,ProjectId,Documents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocuments-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocuments-post-openapi.md
- name: Mota Word Delete the document
  x-api-slug: mota-word
  description: Delete the document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents/{documentId}
  tags: Projects,ProjectId,Documents,DocumentId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocumentsdocumentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocumentsdocumentid-delete-openapi.md
- name: Mota Word Get single document
  x-api-slug: mota-word
  description: Get single document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents/{documentId}
  tags: Projects,ProjectId,Documents,DocumentId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocumentsdocumentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocumentsdocumentid-get-openapi.md
- name: Mota Word Update the document.
  x-api-slug: mota-word
  description: Update the document. File name and contents will replaced with the
    new one.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents/{documentId}
  tags: Projects,ProjectId,Documents,DocumentId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocumentsdocumentid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocumentsdocumentid-put-openapi.md
- name: Mota Word Download a document
  x-api-slug: mota-word
  description: Download a document.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com////projects/{projectId}/documents/{documentId}/download
  tags: Projects,ProjectId,Documents,DocumentId,Download
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocumentsdocumentiddownload-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/projectsprojectiddocumentsdocumentiddownload-get-openapi.md
- name: Mota Word
  x-api-slug: mota-word
  description: MotaWord is the world&rsquo;s fastest, lowest cost, cloud-based, collaborative
    business translation platform.MotaWord combines the efforts of talented human
    translators through the use of a cloud based translation platform. Our translators
    are able to login simultaneously into projects that fit their language combination
    and provide translation service collaboratively - while also seeing the whole
    content for contextual purposes. This ability to simultaneously utilize multiple
    translators makes MotaWord exceptionally fast and highly accurate.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/motaword-logo.png
  humanURL: http://www.motaword.com
  baseURL: https://api.motaword.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/motaword/openapi.md
x-common:
- type: x-website
  url: http://www.motaword.com
- type: x-blog
  url: https://www.motaword.com/developer/blog
- type: x-developer
  url: https://www.motaword.com/developer
- type: x-github
  url: https://github.com/motaword
- type: x-pricing
  url: https://www.motaword.com/pricing
- type: x-twitter
  url: https://twitter.com/motaword
- type: x-website
  url: http://motaword.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---