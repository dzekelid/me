---
swagger: "2.0"
x-collection-name: DataAtWork
x-complete: 0
info:
  title: Open Skills API Skill Name Autocomplete
  description: Retrieves the names, descriptions, and UUIDs of all skills matching
    a given search criteria.
  contact:
    name: Work Data Initiative
    url: http://www.dataatwork.org
  version: "1.0"
host: api.dataatwork.org
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /skills:
    get:
      summary: Skill Names and Descriptions
      description: Retrieve the names, descriptions, and UUIDs of all skills.
      operationId: retrieve-the-names-descriptions-and-uuids-of-all-skills
      x-api-path-slug: skills-get
      parameters:
      - in: query
        name: limit
        description: Maximum number of items per page
      - in: query
        name: offset
        description: Pagination offset
      responses:
        "":
          description: ""
        400:
          description: Bad input parameter
        401:
          description: Bad or expired token
        403:
          description: Bad OAuth request (wrong consumer key, bad nonce, expired timestamp
        404:
          description: File or folder not found at the specified path
        405:
          description: Request method not expected (generally should be GET or POST)
        429:
          description: Your app is making too many requests and is being rate limited
        503:
          description: If the response includes the Retry-After header, this means
            your OAuth 1
        507:
          description: User is over Dropbox storage quota
        5xx:
          description: Server error
        '400: for badly-formed requests, e.g. missing or invalid parameters':
          description: ""
        '403: for authentication issues':
          description: ""
        '409: for issues where the request is well-formed but cannot be completed':
          description: ""
        200:
          description: OK
      tags:
      - Skill
      - Names
      - Descriptions
  /skills/{id}:
    get:
      summary: Skill Name and Description
      description: Retrieves the name, description, and UUID of a job by specifying
        its UUID.
      operationId: retrieves-the-name-description-and-uuid-of-a-job-by-specifying-its-uuid
      x-api-path-slug: skillsid-get
      parameters:
      - in: path
        name: id
        description: The UUID of the skill name to retrieve
      responses:
        200:
          description: OK
      tags:
      - Skill
      - Name
      - Description
  /skills/autocomplete:
    get:
      summary: Skill Name Autocomplete
      description: Retrieves the names, descriptions, and UUIDs of all skills matching
        a given search criteria.
      operationId: retrieves-the-names-descriptions-and-uuids-of-all-skills-matching-a-given-search-criteria
      x-api-path-slug: skillsautocomplete-get
      parameters:
      - in: query
        name: begins_with
        description: Find skill names beginning with the given text fragment
      - in: query
        name: contains
        description: Find skill names containing the given text fragment
      - in: query
        name: ends_with
        description: Find skill names ending with the given text fragment
      responses:
        200:
          description: OK
      tags:
      - Skill
      - Name
      - Autocomplete
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