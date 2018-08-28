---
swagger: "2.0"
x-collection-name: AXA Assistance
x-complete: 0
info:
  title: AXA Assistance Gets assignment information.
  description: Gets assignment information.
  version: 1.0.0
host: sandbox.api.axa-assistance.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /network/v1/medical_providers/availabilities:
    get:
      summary: Gets the availabilities of medical providers.
      description: Gets the availabilities of medical providers.
      operationId: getNetworkV1Medical_providersAvailabilities
      x-api-path-slug: networkv1medical-providersavailabilities-get
      parameters:
      - in: query
        name: end_date
        description: End date and time of the availability search - UTC datetime,
          RFC3339 format (YYYY-MM-DDTHH:mmZ)
      - in: query
        name: start_date
        description: Beginning date and time of the availability search - UTC datetime,
          RFC3339 format (YYYY-MM-DDTHH:mmZ)
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - the
      - availabilitieAssistance
      - of
      - medical
      - providers.
  /ondemand/v1/medical_providers/kinds:
    get:
      summary: 'Retrieve all medical provider kinds available for search (Ex: pharmacy,
        hospital ...)'
      description: 'Retrieve all medical provider kinds available for search (Ex:
        pharmacy, hospital ...)'
      operationId: getOndemandV1Medical_providersKinds
      x-api-path-slug: ondemandv1medical-providerskinds-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - all
      - medical
      - provider
      - kindAssistance
      - availablesearch
      - '(Ex:'
      - pharmacy
      - ""
      - hospital
      - '...)'
  /ondemand/v1/medical_providers/search:
    get:
      summary: Search for medical providers
      description: Search for medical providers
      operationId: getOndemandV1Medical_providersSearch
      x-api-path-slug: ondemandv1medical-providerssearch-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      - in: query
        name: kind
        description: Provider kind
      - in: query
        name: lat
        description: Latitude
      - in: query
        name: lng
        description: Longitude
      - in: query
        name: speciality
        description: Speciality
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Searchmedical
      - providers
  /ondemand/v1/medical_providers/specialities:
    get:
      summary: 'Retrieve all medical provider specialities available for search (Ex:
        cardiology, dentist ...)'
      description: 'Retrieve all medical provider specialities available for search
        (Ex: cardiology, dentist ...)'
      operationId: getOndemandV1Medical_providersSpecialities
      x-api-path-slug: ondemandv1medical-providersspecialities-get
      parameters:
      - in: header
        name: accept-language
        description: Language/Country
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Retrieve
      - all
      - medical
      - provider
      - specialitieAssistance
      - availablesearch
      - '(Ex:'
      - cardiology
      - ""
      - dentist
      - '...)'
  /service/v1/medical_consultations/{medical_consultation_id}:
    get:
      summary: Provides detail of a medical consultation
      description: Provides detail of a medical consultation
      operationId: getServiceV1Medical_consultationsMedical_consultation_id
      x-api-path-slug: servicev1medical-consultationsmedical-consultation-id-get
      parameters:
      - in: path
        name: medical_consultation_id
        description: ID of the medical consultation
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - ProvideAssistance
      - detail
      - ofmedical
      - consultation
    patch:
      summary: Updates a medical consultation
      description: Updates a medical consultation
      operationId: patchServiceV1Medical_consultationsMedical_consultation_id
      x-api-path-slug: servicev1medical-consultationsmedical-consultation-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: medical_consultation_id
        description: ID of the medical consultation
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - smedical
      - consultation
  /service/vexp/roadside/assignments/{assignment_id}:
    get:
      summary: Gets assignment information.
      description: Gets assignment information.
      operationId: getServiceVexpRoadsideAssignmentsAssignment_id
      x-api-path-slug: servicevexproadsideassignmentsassignment-id-get
      parameters:
      - in: path
        name: assignment_id
        description: Assignment unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insurance
      - Assistance
      - assignment
      - information.
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