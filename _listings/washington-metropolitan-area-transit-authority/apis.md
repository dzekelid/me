---
name: Washington Metropolitan Area Transit Authority
x-slug: washington-metropolitan-area-transit-authority
description: Official feed of Metro/WMATA, not monitored 24/7. Report emergencies
  to Transit Police at (202) 962-2121. Service updates @metrorailinfo & @metrobusinfo.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1214-washington-metropolitan-area-transit-authority.jpg
x-kinRank: "8"
x-alexaRank: "24927"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/washington-metropolitan-area-transit-authority/apis.md
specificationVersion: "0.14"
apis:
- name: WMATA Rail Station Information JSON - Station Timings
  x-api-slug: wmata-rail-station-information
  description: "Description\r\n\r\nReturns opening and scheduled first/last train
    times based on a given\r\nStationCode. Omit the StationCode to return timing information
    for all\r\nstations.\r\n\r\nNote that for stations with multiple platforms (e.g.:
    Metro Center, L'Enfant\r\nPlaza, etc.), a distinct call is required for each StationCode
    to retrieve the\r\nfull set of train times at such stations.\r\n\r\nResponse Elements\r\n\r\n\r\n\r\n\r\nElement\r\n\r\nDescription\r\n\r\n\r\n\r\n\r\n\r\nStationTimes\r\n\r\n\r\nArray
    containing station timing information (StationTime).\r\n\r\n\r\n\r\n\r\n\r\n\r\nStationTime\r\nElements\r\n\r\n\r\n\r\n\r\n\r\nCode\r\n\r\nStation
    code for this station. Use this value in other\r\nrail-related APIs to retrieve
    data about a station.\r\n\r\n\r\n\r\nStationName\r\n\r\nFull name of the station.\r\n\r\n\r\n\r\n*Day
    Elements\r\n\r\n\r\nContainer elements containing timing information based on\r\nday
    of the week.\r\n\r\n\r\n\r\n\r\n\r\n\r\nMonday/Tuesday/Wednesday/etc.\r\nElements\r\n\r\n\r\n\r\n\r\n\r\nOpeningTime\r\n\r\nStation
    opening time. Format is HH:mm.\r\n\r\n\r\n\r\nFirstTrains\r\n\r\n\r\nStructure
    containing first train\r\ninformation.\r\n\r\n\r\n\r\n\r\nLastTrains\r\n\r\n\r\nStructure
    containing last train\r\ninformation.\r\n\r\n\r\n\r\n\r\n\r\n\r\nFirstTrains Elements\r\n\r\n\r\n\r\n\r\n\r\nTime\r\n\r\nFirst
    train leaves the station at this time. Format is\r\nHH:mm.\r\n\r\n\r\n\r\nDestinationStation\r\n\r\nStation
    code for the train's destination. Use this value in\r\nother rail-related APIs
    to retrieve data about a station.\r\n\r\n\r\n\r\n\r\n\r\nLastTrains Elements\r\n\r\n\r\n\r\n\r\n\r\nTime\r\n\r\nLast
    train leaves the station at this time. Format is HH:mm.\r\nNote that when the
    time is AM, it signifies the next day. For\r\nexample, a value of 02:30 under
    a Saturday element means the last\r\ntrain leaves on Sunday at 2:30 AM.\r\n\r\n\r\n\r\nDestinationStation\r\n\r\nStation
    code for the train's destination. Use this value in\r\nother rail-related APIs
    to retrieve data about a station."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1214-washington-metropolitan-area-transit-authority.jpg
  humanURL: http://wmata.com/
  baseURL: https://api.wmata.com//Rail.svc//json/jStationTimes
  tags: Transit,Stations,Times
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/washington-metropolitan-area-transit-authority/jsonjstationtimes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/washington-metropolitan-area-transit-authority/jsonjstationtimes-get-openapi.md
- name: WMATA Rail Station Information XML - Station Timings
  x-api-slug: wmata-rail-station-information
  description: "Description\r\n\r\nReturns opening and scheduled first/last train
    times based on a given\r\nStationCode. Omit the StationCode to return timing information
    for all\r\nstations.\r\n\r\nNote that for stations with multiple platforms (e.g.:
    Metro Center, L'Enfant\r\nPlaza, etc.), a distinct call is required for each StationCode
    to retrieve the\r\nfull set of train times at such stations.\r\n\r\nResponse Elements\r\n\r\n\r\n\r\n\r\nElement\r\n\r\nDescription\r\n\r\n\r\n\r\n\r\n\r\nStationTimes\r\n\r\n\r\nArray
    containing station timing information (StationTime).\r\n\r\n\r\n\r\n\r\n\r\n\r\nStationTime\r\nElements\r\n\r\n\r\n\r\n\r\n\r\nCode\r\n\r\nStation
    code for this station. Use this value in other\r\nrail-related APIs to retrieve
    data about a station.\r\n\r\n\r\n\r\nStationName\r\n\r\nFull name of the station.\r\n\r\n\r\n\r\n*Day
    Elements\r\n\r\n\r\nContainer elements containing timing information based on\r\nday
    of the week.\r\n\r\n\r\n\r\n\r\n\r\n\r\nMonday/Tuesday/Wednesday/etc.\r\nElements\r\n\r\n\r\n\r\n\r\n\r\nOpeningTime\r\n\r\nStation
    opening time. Format is HH:mm.\r\n\r\n\r\n\r\nFirstTrains\r\n\r\n\r\nStructure
    containing first train\r\ninformation.\r\n\r\n\r\n\r\n\r\nLastTrains\r\n\r\n\r\nStructure
    containing last train\r\ninformation.\r\n\r\n\r\n\r\n\r\n\r\n\r\nFirstTrains Elements\r\n\r\n\r\n\r\n\r\n\r\nTime\r\n\r\nFirst
    train leaves the station at this time. Format is\r\nHH:mm.\r\n\r\n\r\n\r\nDestinationStation\r\n\r\nStation
    code for the train's destination. Use this value in\r\nother rail-related APIs
    to retrieve data about a station.\r\n\r\n\r\n\r\n\r\n\r\nLastTrains Elements\r\n\r\n\r\n\r\n\r\n\r\nTime\r\n\r\nLast
    train leaves the station at this time. Format is HH:mm.\r\nNote that when the
    time is AM, it signifies the next day. For\r\nexample, a value of 02:30 under
    a Saturday element means the last\r\ntrain leaves on Sunday at 2:30 AM.\r\n\r\n\r\n\r\nDestinationStation\r\n\r\nStation
    code for the train's destination. Use this value in\r\nother rail-related APIs
    to retrieve data about a station."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1214-washington-metropolitan-area-transit-authority.jpg
  humanURL: http://wmata.com/
  baseURL: https://api.wmata.com//Rail.svc//StationTimes
  tags: Transit,Stations,Times
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/washington-metropolitan-area-transit-authority/stationtimes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/washington-metropolitan-area-transit-authority/stationtimes-get-openapi.md
- name: WMATA Rail Station Information
  x-api-slug: wmata-rail-station-information
  description: Official feed of Metro/WMATA, not monitored 24/7. Report emergencies
    to Transit Police at (202) 962-2121. Service updates @metrorailinfo & @metrobusinfo.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1214-washington-metropolitan-area-transit-authority.jpg
  humanURL: http://wmata.com/
  baseURL: https://api.wmata.com//Rail.svc
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/washington-metropolitan-area-transit-authority/openapi.md
x-common:
- type: x-base
  url: http://api.wmata.com/
- type: x-crunchbase
  url: https://crunchbase.com/organization/wmata
- type: x-developer
  url: http://developer.wmata.com/
- type: x-email
  url: boardofdirectors@wmata.com
- type: x-email
  url: metrotransit@wmata.com
- type: x-email
  url: adaassist@wmata.com
- type: x-email
  url: access@wmata.com
- type: x-email
  url: cjachles@wmata.com
- type: x-email
  url: writtentestimony@wmata.com
- type: x-email
  url: speak@wmata.com
- type: x-email
  url: SEBusMove@wmata.com
- type: x-email
  url: PARP@wmata.com
- type: x-email
  url: raccomments@wmata.com
- type: x-signup
  url: https://developer.wmata.com/signup/
- type: x-twitter
  url: https://twitter.com/wmata
- type: x-website
  url: http://wmata.com/
- type: x-website
  url: http://wmata.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---