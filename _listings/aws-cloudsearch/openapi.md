---
swagger: "2.0"
x-collection-name: AWS CloudSearch
x-complete: 1
info:
  title: AWS CloudSearch
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DefineAnalysisScheme:
    get:
      summary: Define Analysis Scheme
      description: Configures an analysis scheme that can be applied to a text or
        text-array field to define language-specific text processing options.
      operationId: DefineAnalysisScheme
      x-api-path-slug: actiondefineanalysisscheme-get
      parameters:
      - in: query
        name: AnalysisScheme
        description: Configuration information for an analysis scheme
        type: string
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Analysis Scheme
  /?Action=DeleteAnalysisScheme:
    get:
      summary: Delete Analysis Scheme
      description: Deletes an analysis scheme.
      operationId: DeleteAnalysisScheme
      x-api-path-slug: actiondeleteanalysisscheme-get
      parameters:
      - in: query
        name: AnalysisSchemeName
        description: The name of the analysis scheme you want to delete
        type: string
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Analysis Scheme
  /?Action=DescribeAnalysisSchemes:
    get:
      summary: Describe Analysis Schemes
      description: Gets the analysis schemes configured for a domain.
      operationId: DescribeAnalysisSchemes
      x-api-path-slug: actiondescribeanalysisschemes-get
      parameters:
      - in: query
        name: AnalysisSchemeNames.member.N
        description: The analysis schemes you want to describe
        type: string
      - in: query
        name: Deployed
        description: Whether to display the deployed configuration (true) or include
          any pending changes (false)
        type: string
      - in: query
        name: DomainName
        description: The name of the domain you want to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Analysis Scheme
  /?Action=DescribeScalingParameters:
    get:
      summary: Describe Scaling Parameters
      description: Gets the scaling parameters configured for a domain.
      operationId: DescribeScalingParameters
      x-api-path-slug: actiondescribescalingparameters-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Scaling Parameters
  /?Action=IndexDocuments:
    get:
      summary: Index Documents
      description: Tells the search domain to start indexing its documents using the
        latest indexing options.
      operationId: IndexDocuments
      x-api-path-slug: actionindexdocuments-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      responses:
        200:
          description: OK
      tags:
      - Index Documents
  /?Action=UpdateScalingParameters:
    get:
      summary: Update Scaling Parameters
      description: Configures scaling parameters for a domain.
      operationId: UpdateScalingParameters
      x-api-path-slug: actionupdatescalingparameters-get
      parameters:
      - in: query
        name: DomainName
        description: A string that represents the name of a domain
        type: string
      - in: query
        name: ScalingParameters
        description: The desired instance type and desired number of replicas of each
          index partition
        type: string
      responses:
        200:
          description: OK
      tags:
      - Scaling Parameters
---