---
name: Intrinio
x-slug: intrinio
description: Intelligent Data, On Demand. The financial data platform for developers,
  investors, students, and educators, with over 200 feeds including real-time, intraday,
  EOD, and international financial data available via REST API, WebSocket, CSV, Excel,
  and Goo...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28077-intrinio.jpg
x-kinRank: "8"
x-alexaRank: "303229"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/intrinio/apis.md
specificationVersion: "0.14"
apis:
- name: Intrinio API Standardized Fundamentals
  x-api-slug: intrinio-api
  description: Returns a list of available standardized fundamentals (fiscal year
    and fiscal period) for a given ticker and statement.  Also, you may add a date
    and type parameter to specify the fundamentals you wish to be returned in the
    response.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28077-intrinio.jpg
  humanURL: https://intrinio.com
  baseURL: https://api.intrinio.com////fundamentals/standardized
  tags: Market Data,Fundamentals
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/intrinio/fundamentalsstandardized-get-openapi.md
- name: Intrinio API Sector News Sentiments
  x-api-slug: intrinio-api
  description: Returns daily summaries of news sentiments by sector and date.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28077-intrinio.jpg
  humanURL: https://intrinio.com
  baseURL: https://api.intrinio.com////news_sector_sentiments
  tags: Market Data,News,Sector, Sentiments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/intrinio/news-sector-sentiments-get-openapi.md
- name: Intrinio API
  x-api-slug: intrinio-api
  description: Intelligent Data, On Demand. The financial data platform for developers,
    investors, students, and educators, with over 200 feeds including real-time, intraday,
    EOD, and international financial data available via REST API, WebSocket, CSV,
    Excel, and Goo...
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28077-intrinio.jpg
  humanURL: https://intrinio.com
  baseURL: https://api.intrinio.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/intrinio/openapi.md
x-common:
- type: x-applications-showcase
  url: https://intrinio.com/marketplace/apps
- type: x-authentication
  url: http://docs.intrinio.com/#authentication
- type: x-blog
  url: http://blog.intrinio.com/
- type: x-blog-rss
  url: http://blog.intrinio.com/feed/
- type: x-code
  url: http://docs.intrinio.com/#sdks
- type: x-crunchbase
  url: https://crunchbase.com/organization/tribunat
- type: x-developer
  url: https://intrinio.com/we-love-developers
- type: x-documentation
  url: https://intrinio.com/marketplace/data
- type: x-email
  url: cfarley@intrinio.com
- type: x-email
  url: admin@intrinio.com
- type: x-email
  url: support@intrinio.com
- type: x-email
  url: acarpenter@intrinio.com
- type: x-login
  url: https://intrinio.com/login
- type: x-partners
  url: https://intrinio.com/partners
- type: x-press
  url: https://intrinio.com/press
- type: x-rate-limits
  url: http://docs.intrinio.com/#limits
- type: x-selfservice-registration
  url: https://intrinio.com/signup
- type: x-spreadsheets
  url: http://docs.intrinio.com/#spreadsheet-add-ins
- type: x-support
  url: https://intrinio.com/help
- type: x-tutorial
  url: https://intrinio.com/tutorial/web_api
- type: x-twitter
  url: https://twitter.com/intrinio
- type: x-website
  url: https://intrinio.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---