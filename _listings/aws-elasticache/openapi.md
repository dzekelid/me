---
swagger: "2.0"
x-collection-name: AWS ElastiCache
x-complete: 1
info:
  title: AWS ElastiCache API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CreateCacheParameterGroup:
    get:
      summary: Create Cache Parameter Group
      description: Creates a new cache parameter group.
      operationId: createCacheParameterGroup
      x-api-path-slug: actioncreatecacheparametergroup-get
      parameters:
      - in: query
        name: CacheParameterGroupFamily
        description: The name of the cache parameter group family that the cache parameter
          group can be used with
        type: string
      - in: query
        name: CacheParameterGroupName
        description: A user-specified name for the cache parameter group
        type: string
      - in: query
        name: Description
        description: A user-specified description for the cache parameter group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Parameter Groups
  /?Action=DeleteCacheParameterGroup:
    get:
      summary: Delete Cache Parameter Group
      description: |-
        Deletes the specified cache parameter
                    group.
      operationId: deleteCacheParameterGroup
      x-api-path-slug: actiondeletecacheparametergroup-get
      parameters:
      - in: query
        name: CacheParameterGroupName
        description: The name of the cache parameter group to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Parameter Groups
  /?Action=DescribeCacheParameterGroups:
    get:
      summary: Describe Cache Parameter Groups
      description: |-
        Returns a list of cache parameter group
                    descriptions.
      operationId: describeCacheParameterGroups
      x-api-path-slug: actiondescribecacheparametergroups-get
      parameters:
      - in: query
        name: CacheParameterGroupName
        description: The name of a specific cache parameter group to return details
          for
        type: string
      - in: query
        name: Marker
        description: An optional marker returned from a prior request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Parameter Groups
  /?Action=DescribeCacheParameters:
    get:
      summary: Describe Cache Parameters
      description: |-
        Returns the detailed parameter list for a
                    particular cache parameter group.
      operationId: describeCacheParameters
      x-api-path-slug: actiondescribecacheparameters-get
      parameters:
      - in: query
        name: CacheParameterGroupName
        description: The name of a specific cache parameter group to return details
          for
        type: string
      - in: query
        name: Marker
        description: An optional marker returned from a prior request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: Source
        description: The parameter types to return
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Parameters
  /?Action=DescribeEngineDefaultParameters:
    get:
      summary: Describe Engine Default Parameters
      description: |-
        Returns the default engine and
                    system parameter information for the specified cache engine.
      operationId: describeEngineDefaultParameters
      x-api-path-slug: actiondescribeenginedefaultparameters-get
      parameters:
      - in: query
        name: CacheParameterGroupFamily
        description: The name of the cache parameter group family
        type: string
      - in: query
        name: Marker
        description: An optional marker returned from a prior request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Engine Default Parameters
  /?Action=ModifyCacheParameterGroup:
    get:
      summary: Modify Cache Parameter Group
      description: |-
        Modifies the parameters of a cache
                    parameter group.
      operationId: modifyCacheParameterGroup
      x-api-path-slug: actionmodifycacheparametergroup-get
      parameters:
      - in: query
        name: CacheParameterGroupName
        description: The name of the cache parameter group to modify
        type: string
      - in: query
        name: ParameterNameValues.ParameterNameValue.N
        description: An array of parameter names and values for the parameter update
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Parameter Groups
  /?Action=ResetCacheParameterGroup:
    get:
      summary: Reset Cache Parameter Group
      description: |-
        Modifies the parameters of a cache
                    parameter group to the engine or system default value.
      operationId: resetCacheParameterGroup
      x-api-path-slug: actionresetcacheparametergroup-get
      parameters:
      - in: query
        name: CacheParameterGroupName
        description: The name of the cache parameter group to reset
        type: string
      - in: query
        name: ParameterNameValues.ParameterNameValue.N
        description: An array of parameter names to reset to their default values
        type: string
      - in: query
        name: ResetAllParameters
        description: If true,             all parameters in the cache parameter group
          are reset to their default values
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cache Parameter Groups
---