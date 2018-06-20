---
swagger: "2.0"
x-collection-name: AWS Service Catalog
x-complete: 0
info:
  title: AWS Service Catalog API Describe Provisioning Parameters
  version: 1.0.0
  description: |-
    Provides information about parameters required to provision a specified product in a
             specified manner.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeProvisioningParameters:
    get:
      summary: Describe Provisioning Parameters
      description: |-
        Provides information about parameters required to provision a specified product in a
                 specified manner.
      operationId: describeProvisioningParameters
      x-api-path-slug: actiondescribeprovisioningparameters-get
      parameters:
      - in: query
        name: AcceptLanguage
        description: The language code to use for this operation
        type: string
      - in: query
        name: PathId
        description: The identifier of the path for this products provisioning
        type: string
      - in: query
        name: ProductId
        description: The product identifier
        type: string
      - in: query
        name: ProvisioningArtifactId
        description: The provisioning artifact identifier for this product
        type: string
      responses:
        200:
          description: OK
      tags:
      - Provisioning Parameters
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