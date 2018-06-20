---
swagger: "2.0"
x-collection-name: Sustainable Facilities Tool API
x-complete: 1
info:
  title: Sustainable Facilities Tool API
  description: our-core-api-allows-developers-to-interact-with-the-sustainable-facilities-tool-programmatically--its-designed-for-public-use-and-to-be-easily-integrated-into-other-applications-
  termsOfService: https://sftool.gov/developer/terms-of-use
  version: 1.0.0
host: api.data.gov
basePath: /sftool/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /procurementclauses/psc/{parameter}:
    get:
      summary: Procurement Clause
      description: Returns any FAR clause number(s) and sample procurement language
        associated with the given PSC parameter.
      operationId: returnFederalAcquisitionRegulationClause
      x-api-path-slug: procurementclausespscparameter-get
      responses:
        200:
          description: OK
      tags:
      - Procurement Clause
---