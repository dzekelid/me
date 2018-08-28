---
swagger: "2.0"
x-collection-name: AWS Key Management Service
x-complete: 1
info:
  title: AWS Key Management Service API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=GetParametersForImport:
    get:
      summary: Get Parameters For Import
      description: |-
        Returns the items you need in order to import key material into AWS KMS from your
              existing key management infrastructure.
      operationId: getParametersForImport
      x-api-path-slug: actiongetparametersforimport-get
      parameters:
      - in: query
        name: KeyId
        description: The identifier of the CMK into which you will import key material
        type: string
      - in: query
        name: WrappingAlgorithm
        description: The algorithm you will use to encrypt the key material before
          importing it with ImportKeyMaterial
        type: string
      - in: query
        name: WrappingKeySpec
        description: The type of wrapping key (public key) to return in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameters
---