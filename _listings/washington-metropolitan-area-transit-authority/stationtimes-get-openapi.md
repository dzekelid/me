---
swagger: "2.0"
x-collection-name: Washington Metropolitan Area Transit Authority
x-complete: 0
info:
  title: WMATA Rail Station Information XML - Station Timings
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
  version: 1.0.0
host: api.wmata.com
basePath: /Rail.svc
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /json/jStationTimes:
    get:
      summary: JSON - Station Timings
      description: "Description\r\n\r\nReturns opening and scheduled first/last train
        times based on a given\r\nStationCode. Omit the StationCode to return timing
        information for all\r\nstations.\r\n\r\nNote that for stations with multiple
        platforms (e.g.: Metro Center, L'Enfant\r\nPlaza, etc.), a distinct call is
        required for each StationCode to retrieve the\r\nfull set of train times at
        such stations.\r\n\r\nResponse Elements\r\n\r\n\r\n\r\n\r\nElement\r\n\r\nDescription\r\n\r\n\r\n\r\n\r\n\r\nStationTimes\r\n\r\n\r\nArray
        containing station timing information (StationTime).\r\n\r\n\r\n\r\n\r\n\r\n\r\nStationTime\r\nElements\r\n\r\n\r\n\r\n\r\n\r\nCode\r\n\r\nStation
        code for this station. Use this value in other\r\nrail-related APIs to retrieve
        data about a station.\r\n\r\n\r\n\r\nStationName\r\n\r\nFull name of the station.\r\n\r\n\r\n\r\n*Day
        Elements\r\n\r\n\r\nContainer elements containing timing information based
        on\r\nday of the week.\r\n\r\n\r\n\r\n\r\n\r\n\r\nMonday/Tuesday/Wednesday/etc.\r\nElements\r\n\r\n\r\n\r\n\r\n\r\nOpeningTime\r\n\r\nStation
        opening time. Format is HH:mm.\r\n\r\n\r\n\r\nFirstTrains\r\n\r\n\r\nStructure
        containing first train\r\ninformation.\r\n\r\n\r\n\r\n\r\nLastTrains\r\n\r\n\r\nStructure
        containing last train\r\ninformation.\r\n\r\n\r\n\r\n\r\n\r\n\r\nFirstTrains
        Elements\r\n\r\n\r\n\r\n\r\n\r\nTime\r\n\r\nFirst train leaves the station
        at this time. Format is\r\nHH:mm.\r\n\r\n\r\n\r\nDestinationStation\r\n\r\nStation
        code for the train's destination. Use this value in\r\nother rail-related
        APIs to retrieve data about a station.\r\n\r\n\r\n\r\n\r\n\r\nLastTrains Elements\r\n\r\n\r\n\r\n\r\n\r\nTime\r\n\r\nLast
        train leaves the station at this time. Format is HH:mm.\r\nNote that when
        the time is AM, it signifies the next day. For\r\nexample, a value of 02:30
        under a Saturday element means the last\r\ntrain leaves on Sunday at 2:30
        AM.\r\n\r\n\r\n\r\nDestinationStation\r\n\r\nStation code for the train's
        destination. Use this value in\r\nother rail-related APIs to retrieve data
        about a station."
      operationId: getJsonJstationtimes
      x-api-path-slug: jsonjstationtimes-get
      parameters:
      - in: query
        name: StationCode
        description: Station code
      responses:
        200:
          description: OK
      tags:
      - Transit
      - Stations
      - Times
  /StationTimes:
    get:
      summary: XML - Station Timings
      description: "Description\r\n\r\nReturns opening and scheduled first/last train
        times based on a given\r\nStationCode. Omit the StationCode to return timing
        information for all\r\nstations.\r\n\r\nNote that for stations with multiple
        platforms (e.g.: Metro Center, L'Enfant\r\nPlaza, etc.), a distinct call is
        required for each StationCode to retrieve the\r\nfull set of train times at
        such stations.\r\n\r\nResponse Elements\r\n\r\n\r\n\r\n\r\nElement\r\n\r\nDescription\r\n\r\n\r\n\r\n\r\n\r\nStationTimes\r\n\r\n\r\nArray
        containing station timing information (StationTime).\r\n\r\n\r\n\r\n\r\n\r\n\r\nStationTime\r\nElements\r\n\r\n\r\n\r\n\r\n\r\nCode\r\n\r\nStation
        code for this station. Use this value in other\r\nrail-related APIs to retrieve
        data about a station.\r\n\r\n\r\n\r\nStationName\r\n\r\nFull name of the station.\r\n\r\n\r\n\r\n*Day
        Elements\r\n\r\n\r\nContainer elements containing timing information based
        on\r\nday of the week.\r\n\r\n\r\n\r\n\r\n\r\n\r\nMonday/Tuesday/Wednesday/etc.\r\nElements\r\n\r\n\r\n\r\n\r\n\r\nOpeningTime\r\n\r\nStation
        opening time. Format is HH:mm.\r\n\r\n\r\n\r\nFirstTrains\r\n\r\n\r\nStructure
        containing first train\r\ninformation.\r\n\r\n\r\n\r\n\r\nLastTrains\r\n\r\n\r\nStructure
        containing last train\r\ninformation.\r\n\r\n\r\n\r\n\r\n\r\n\r\nFirstTrains
        Elements\r\n\r\n\r\n\r\n\r\n\r\nTime\r\n\r\nFirst train leaves the station
        at this time. Format is\r\nHH:mm.\r\n\r\n\r\n\r\nDestinationStation\r\n\r\nStation
        code for the train's destination. Use this value in\r\nother rail-related
        APIs to retrieve data about a station.\r\n\r\n\r\n\r\n\r\n\r\nLastTrains Elements\r\n\r\n\r\n\r\n\r\n\r\nTime\r\n\r\nLast
        train leaves the station at this time. Format is HH:mm.\r\nNote that when
        the time is AM, it signifies the next day. For\r\nexample, a value of 02:30
        under a Saturday element means the last\r\ntrain leaves on Sunday at 2:30
        AM.\r\n\r\n\r\n\r\nDestinationStation\r\n\r\nStation code for the train's
        destination. Use this value in\r\nother rail-related APIs to retrieve data
        about a station."
      operationId: getStationtimes
      x-api-path-slug: stationtimes-get
      parameters:
      - in: query
        name: StationCode
        description: Station code
      responses:
        200:
          description: OK
      tags:
      - Transit
      - Stations
      - Times
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---