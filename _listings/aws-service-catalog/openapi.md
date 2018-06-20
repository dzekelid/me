---
swagger: "2.0"
x-collection-name: AWS Service Catalog
x-complete: 1
info:
  title: AWS Service Catalog API
  version: 1.0.0
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
---