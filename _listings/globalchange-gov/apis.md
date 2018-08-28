---
name: GlobalChange.gov
x-slug: globalchange-gov
description: The U.S. Global Change Research Program (USGCRP) was established by Presidential
  Initiative in 1989 and mandated by Congress in the Global Change Research Act (GCRA)
  of 1990 to &ldquo;assist the Nation and the world to understand, assess, predict,
  and respond to human-induced and natural processes of global change.&rdquo;
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/apis.md
specificationVersion: "0.14"
apis:
- name: Global Change Information System API List instruments.
  x-api-slug: global-change-information-system-api
  description: List the instruments, 20 per page.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
  humanURL: http://globalchange.gov/
  baseURL: https://data.globalchange.gov////instrument
  tags: Instruments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/instrument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/instrument-get-openapi.md
- name: Global Change Information System API Get a representation of an instrument.
  x-api-slug: global-change-information-system-api
  description: Get JSON which represents the structure of an instrument.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
  humanURL: http://globalchange.gov/
  baseURL: https://data.globalchange.gov////instrument/{instrument_identifier}
  tags: Representation,Instrument
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/instrumentinstrument-identifier-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/instrumentinstrument-identifier-get-openapi.md
- name: Global Change Information System API Get overall metrics about GCIS data
  x-api-slug: global-change-information-system-api
  description: Get overall metrics about GCIS data
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
  humanURL: http://globalchange.gov/
  baseURL: https://data.globalchange.gov////metrics
  tags: Overall,Metrics,About,GCIS,Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/metrics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/metrics-get-openapi.md
- name: Global Change Information System API Redirect to a person based on a name
  x-api-slug: global-change-information-system-api
  description: Given a name (case sensitive, concatenated by dashes), redirect if
    there is a single match.  The first and last names can be in either order.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
  humanURL: http://globalchange.gov/
  baseURL: https://data.globalchange.gov////person/{name}
  tags: Redirect,To,Person,Based,On,Name
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/personname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/personname-get-openapi.md
- name: Global Change Information System API List instruments on a platform.
  x-api-slug: global-change-information-system-api
  description: List the instruments on a platform, 20 per page.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
  humanURL: http://globalchange.gov/
  baseURL: https://data.globalchange.gov////platform/{platform_identifier}/instrument
  tags: Instruments,On,Platform
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/platformplatform-identifierinstrument-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/platformplatform-identifierinstrument-get-openapi.md
- name: Global Change Information System API Get a representation of an instrument
    on a platform.
  x-api-slug: global-change-information-system-api
  description: Get JSON which represents the structure of an instrument on a platform.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
  humanURL: http://globalchange.gov/
  baseURL: https://data.globalchange.gov////platform/{platform_identifier}/instrument/{instrument_identifier}
  tags: Representation,Instrument,On,Platform
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/platformplatform-identifierinstrumentinstrument-identifier-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/platformplatform-identifierinstrumentinstrument-identifier-get-openapi.md
- name: Global Change Information System API
  x-api-slug: global-change-information-system-api
  description: The U.S. Global Change Research Program (USGCRP) was established by
    Presidential Initiative in 1989 and mandated by Congress in the Global Change
    Research Act (GCRA) of 1990 to &ldquo;assist the Nation and the world to understand,
    assess, predict, and respond to human-induced and natural processes of global
    change.&rdquo;
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-change-gov.png
  humanURL: http://globalchange.gov/
  baseURL: https://data.globalchange.gov//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/globalchange-gov/openapi.md
x-common:
- type: x-developer
  url: http://data.globalchange.gov/
- type: x-website
  url: http://globalchange.gov/
- type: x-website
  url: http://globalchange.gov
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---