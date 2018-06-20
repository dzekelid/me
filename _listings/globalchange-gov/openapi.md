---
swagger: "2.0"
x-collection-name: GlobalChange.gov
x-complete: 1
info:
  title: Global Change Information System API
  description: who-we-are-what-the-gcis-is-and-how-we-use-identifiers-and-semantic-information-to-provide-points-of-reference-and-traceability--examples-and-tutorials-for-using-this-system-as-a-researcher-citizen-scientist-application-developer-or-information-theorist--a-description-of-how-the-information-is-structured-including-the-overlaps-between-relational-and-semantic-representations-of-the-information--complete-documentation-for-the-api-including-methods-for-browsing-and-finding-resources-
  version: v1
host: data.globalchange.gov
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /instrument:
    get:
      summary: List instruments.
      description: List the instruments, 20 per page.
      operationId: list-the-instruments-20-per-page
      x-api-path-slug: instrument-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the instruments
      - in: query
        name: page
        description: The page number (starting at 1)
      responses:
        200:
          description: OK
      tags:
      - Instruments
  /instrument/{instrument_identifier}:
    get:
      summary: Get a representation of an instrument.
      description: Get JSON which represents the structure of an instrument.
      operationId: get-json-which-represents-the-structure-of-an-instrument
      x-api-path-slug: instrumentinstrument-identifier-get
      parameters:
      - in: path
        name: instrument_identifier
        description: instrument_identifier description
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Instrument
  /metrics:
    get:
      summary: Get overall metrics about GCIS data
      description: Get overall metrics about GCIS data
      operationId: get-overall-metrics-about-gcis-data
      x-api-path-slug: metrics-get
      responses:
        200:
          description: OK
      tags:
      - Overall
      - Metrics
      - About
      - GCIS
      - Data
  /person/{name}:
    get:
      summary: Redirect to a person based on a name
      description: Given a name (case sensitive, concatenated by dashes), redirect
        if there is a single match.  The first and last names can be in either order.
      operationId: given-a-name-case-sensitive-concatenated-by-dashes-redirect-if-there-is-a-single-match--the-first-an
      x-api-path-slug: personname-get
      parameters:
      - in: path
        name: name
        description: name description
      responses:
        200:
          description: OK
      tags:
      - Redirect
      - To
      - Person
      - Based
      - "On"
      - Name
  /platform/{platform_identifier}/instrument:
    get:
      summary: List instruments on a platform.
      description: List the instruments on a platform, 20 per page.
      operationId: list-the-instruments-on-a-platform-20-per-page
      x-api-path-slug: platformplatform-identifierinstrument-get
      parameters:
      - in: query
        name: all
        description: Set to 1 to get all of the instruments
      - in: query
        name: page
        description: The page number (starting at 1)
      - in: path
        name: platform_identifier
        description: platform_identifier description
      responses:
        200:
          description: OK
      tags:
      - Instruments
      - "On"
      - Platform
  /platform/{platform_identifier}/instrument/{instrument_identifier}:
    get:
      summary: Get a representation of an instrument on a platform.
      description: Get JSON which represents the structure of an instrument on a platform.
      operationId: get-json-which-represents-the-structure-of-an-instrument-on-a-platform
      x-api-path-slug: platformplatform-identifierinstrumentinstrument-identifier-get
      parameters:
      - in: path
        name: instrument_identifier
        description: instrument_identifier description
      - in: path
        name: platform_identifier
        description: platform_identifier description
      responses:
        200:
          description: OK
      tags:
      - Representation
      - Instrument
      - "On"
      - Platform
---