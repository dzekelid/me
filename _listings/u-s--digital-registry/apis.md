---
name: U.S. Digital Registry
x-slug: u-s--digital-registry
description: Whether for access to emergency, financial or education public services,
  users need to trust they are engaging with official U.S. government digital accounts.
  The U.S. Digital Registry serves as the authoritative resource for agencies, citizens
  and developers to confirm the official status of social media and public-facing
  collaboration accounts, mobile apps and mobile websites, and help prevent exploitation
  from unofficial sources, phishing scams or malicious entities.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/digital-gov-logo.jpeg
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/u-s--digital-registry/apis.md
specificationVersion: "0.14"
apis:
- name: U.S. Digital Registry Social Media API Social Media Verify
  x-api-slug: u-s--digital-registry-social-media-api
  description: This returns an agency based on an URL. If not found, it will return
    a 404
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/digital-gov-logo.jpeg
  humanURL: https://usdigitalregistry.digitalgov.gov
  baseURL: https://usdigitalregistry.digitalgov.gov//api/v1//social_media/verify.json
  tags: Social Media
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/u-s--digital-registry/social-mediaverify-json-get-openapi.md
- name: U.S. Digital Registry Social Media API Social Media Services
  x-api-slug: u-s--digital-registry-social-media-api
  description: This returns a list of services along with the number of accounts registered
    with them
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/digital-gov-logo.jpeg
  humanURL: https://usdigitalregistry.digitalgov.gov
  baseURL: https://usdigitalregistry.digitalgov.gov//api/v1//social_media/services.json
  tags: Social Media
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/u-s--digital-registry/social-mediaservices-json-get-openapi.md
- name: U.S. Digital Registry Social Media API Social Media Token
  x-api-slug: u-s--digital-registry-social-media-api
  description: This returns tokens representing services, agencies, tags, and a basic
    text search token for the purpose of building search dialogs
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/digital-gov-logo.jpeg
  humanURL: https://usdigitalregistry.digitalgov.gov
  baseURL: https://usdigitalregistry.digitalgov.gov//api/v1//social_media/tokeninput.json
  tags: Social Media
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/u-s--digital-registry/social-mediatokeninput-json-get-openapi.md
- name: U.S. Digital Registry Social Media API Social Media
  x-api-slug: u-s--digital-registry-social-media-api
  description: This lists all active accounts. It accepts parameters to perform basic
    search as well as search by service, agency, or tags.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/digital-gov-logo.jpeg
  humanURL: https://usdigitalregistry.digitalgov.gov
  baseURL: https://usdigitalregistry.digitalgov.gov//api/v1//social_media.json
  tags: Social Media
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/u-s--digital-registry/social-media-json-get-openapi.md
- name: U.S. Digital Registry Social Media API Social Media
  x-api-slug: u-s--digital-registry-social-media-api
  description: This returns an agency based on an ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/digital-gov-logo.jpeg
  humanURL: https://usdigitalregistry.digitalgov.gov
  baseURL: https://usdigitalregistry.digitalgov.gov//api/v1//social_media/{id}.json
  tags: Social Media
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/u-s--digital-registry/social-mediaid-json-get-openapi.md
- name: U.S. Digital Registry Social Media API
  x-api-slug: u-s--digital-registry-social-media-api
  description: Whether for access to emergency, financial or education public services,
    users need to trust they are engaging with official U.S. government digital accounts.
    The U.S. Digital Registry serves as the authoritative resource for agencies, citizens
    and developers to confirm the official status of social media and public-facing
    collaboration accounts, mobile apps and mobile websites, and help prevent exploitation
    from unofficial sources, phishing scams or malicious entities.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/digital-gov-logo.jpeg
  humanURL: https://usdigitalregistry.digitalgov.gov
  baseURL: https://usdigitalregistry.digitalgov.gov//api/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/u-s--digital-registry/openapi.md
x-common:
- type: x-website
  url: https://usdigitalregistry.digitalgov.gov
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---