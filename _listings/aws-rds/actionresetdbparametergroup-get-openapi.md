---
swagger: "2.0"
x-collection-name: AWS RDS
x-complete: 0
info:
  title: Amazon RDS API Reset D B Parameter Group
  version: 1.0.0
  description: Modifies the parameters of a DB parameter group to the engine/system
    default value.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=CopyDBClusterParameterGroup:
    get:
      summary: Copy D B Cluster Parameter Group
      description: Copies the specified DB cluster parameter group.
      operationId: copydbclusterparametergroup
      x-api-path-slug: actioncopydbclusterparametergroup-get
      parameters:
      - in: query
        name: SourceDBClusterParameterGroupIdentifier
        description: The identifier or Amazon Resource Name (ARN) for the source DB
          cluster parameter group
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: TargetDBClusterParameterGroupDescription
        description: A description for the copied DB cluster parameter group
        type: string
      - in: query
        name: TargetDBClusterParameterGroupIdentifier
        description: The identifier for the copied DB cluster parameter group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameter Groups
  /?Action=CopyDBParameterGroup:
    get:
      summary: Copy D B Parameter Group
      description: Copies the specified DB parameter group.
      operationId: copydbparametergroup
      x-api-path-slug: actioncopydbparametergroup-get
      parameters:
      - in: query
        name: SourceDBParameterGroupIdentifier
        description: The identifier or ARN for the source DB parameter group
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      - in: query
        name: TargetDBParameterGroupDescription
        description: A description for the copied DB parameter group
        type: string
      - in: query
        name: TargetDBParameterGroupIdentifier
        description: The identifier for the copied DB parameter group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter Groups
  /?Action=CreateDBClusterParameterGroup:
    get:
      summary: Create D B Cluster Parameter Group
      description: Creates a new DB cluster parameter group.
      operationId: createdbclusterparametergroup
      x-api-path-slug: actioncreatedbclusterparametergroup-get
      parameters:
      - in: query
        name: DBClusterParameterGroupName
        description: The name of the DB cluster parameter group
        type: string
      - in: query
        name: DBParameterGroupFamily
        description: The DB cluster parameter group family name
        type: string
      - in: query
        name: Description
        description: The description for the DB cluster parameter group
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameter Groups
  /?Action=CreateDBParameterGroup:
    get:
      summary: Create D B Parameter Group
      description: Creates a new DB parameter group.
      operationId: createdbparametergroup
      x-api-path-slug: actioncreatedbparametergroup-get
      parameters:
      - in: query
        name: DBParameterGroupFamily
        description: The DB parameter group family name
        type: string
      - in: query
        name: DBParameterGroupName
        description: The name of the DB parameter group
        type: string
      - in: query
        name: Description
        description: The description for the DB parameter group
        type: string
      - in: query
        name: Tags.Tag.N
        description: A list of tags
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter Groups
  /?Action=DeleteDBClusterParameterGroup:
    get:
      summary: Delete D B Cluster Parameter Group
      description: Deletes a specified DB cluster parameter group.
      operationId: deletedbclusterparametergroup
      x-api-path-slug: actiondeletedbclusterparametergroup-get
      parameters:
      - in: query
        name: DBClusterParameterGroupName
        description: The name of the DB cluster parameter group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameter Groups
  /?Action=DeleteDBParameterGroup:
    get:
      summary: Delete D B Parameter Group
      description: Deletes a specified DBParameterGroup.
      operationId: deletedbparametergroup
      x-api-path-slug: actiondeletedbparametergroup-get
      parameters:
      - in: query
        name: DBParameterGroupName
        description: The name of the DB parameter group
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter Groups
  /?Action=DescribeDBClusterParameterGroups:
    get:
      summary: Describe D B Cluster Parameter Groups
      description: Returns a list of DBClusterParameterGroup descriptions.
      operationId: describedbclusterparametergroups
      x-api-path-slug: actiondescribedbclusterparametergroups-get
      parameters:
      - in: query
        name: DBClusterParameterGroupName
        description: The name of a specific DB cluster parameter group to return details
          for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeDBClusterParameterGroups
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameter Groups
  /?Action=DescribeDBClusterParameters:
    get:
      summary: Describe D B Cluster Parameters
      description: Returns the detailed parameter list for a particular DB cluster
        parameter group.
      operationId: describedbclusterparameters
      x-api-path-slug: actiondescribedbclusterparameters-get
      parameters:
      - in: query
        name: DBClusterParameterGroupName
        description: The name of a specific DB cluster parameter group to return parameter
          details for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous      DescribeDBClusterParameters
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      - in: query
        name: Source
        description: A value that indicates to return only parameters for a specific
          source
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameters
  /?Action=DescribeDBParameterGroups:
    get:
      summary: Describe D B Parameter Groups
      description: Returns a list of DBParameterGroup descriptions.
      operationId: describedbparametergroups
      x-api-path-slug: actiondescribedbparametergroups-get
      parameters:
      - in: query
        name: DBParameterGroupName
        description: The name of a specific DB parameter group to return details for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeDBParameterGroups
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter Groups
  /?Action=DescribeDBParameters:
    get:
      summary: Describe D B Parameters
      description: Returns the detailed parameter list for a particular DB parameter
        group.
      operationId: describedbparameters
      x-api-path-slug: actiondescribedbparameters-get
      parameters:
      - in: query
        name: DBParameterGroupName
        description: The name of a specific DB parameter group to return details for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeDBParameters
          request
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
      - Parameters
  /?Action=DescribeEngineDefaultClusterParameters:
    get:
      summary: Describe Engine Default Cluster Parameters
      description: Returns the default engine and system parameter information for
        the cluster database engine.
      operationId: describeenginedefaultclusterparameters
      x-api-path-slug: actiondescribeenginedefaultclusterparameters-get
      parameters:
      - in: query
        name: DBParameterGroupFamily
        description: The name of the DB cluster parameter group family to return engine
          parameter information for
        type: string
      - in: query
        name: Filters.Filter.N
        description: This parameter is not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous      DescribeEngineDefaultClusterParameters
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Default Cluster Parameters
  /?Action=DescribeEngineDefaultParameters:
    get:
      summary: Describe Engine Default Parameters
      description: Returns the default engine and system parameter information for
        the specified database engine.
      operationId: describeenginedefaultparameters
      x-api-path-slug: actiondescribeenginedefaultparameters-get
      parameters:
      - in: query
        name: DBParameterGroupFamily
        description: The name of the DB parameter group family
        type: string
      - in: query
        name: Filters.Filter.N
        description: Not currently supported
        type: string
      - in: query
        name: Marker
        description: An optional pagination token provided by a previous        DescribeEngineDefaultParameters
          request
        type: string
      - in: query
        name: MaxRecords
        description: The maximum number of records to include in the response
        type: string
      responses:
        200:
          description: OK
      tags:
      - Default Parameters
  /?Action=ModifyDBClusterParameterGroup:
    get:
      summary: Modify D B Cluster Parameter Group
      description: Modifies the parameters of a DB cluster parameter group.
      operationId: modifydbclusterparametergroup
      x-api-path-slug: actionmodifydbclusterparametergroup-get
      parameters:
      - in: query
        name: DBClusterParameterGroupName
        description: The name of the DB cluster parameter group to modify
        type: string
      - in: query
        name: Parameters.Parameter.N
        description: A list of parameters in the DB cluster parameter group to modify
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameter Groups
  /?Action=ModifyDBParameterGroup:
    get:
      summary: Modify D B Parameter Group
      description: Modifies the parameters of a DB parameter group.
      operationId: modifydbparametergroup
      x-api-path-slug: actionmodifydbparametergroup-get
      parameters:
      - in: query
        name: DBParameterGroupName
        description: The name of the DB parameter group
        type: string
      - in: query
        name: Parameters.Parameter.N
        description: An array of parameter names, values, and the apply method for
          the parameter update
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter Groups
  /?Action=ResetDBClusterParameterGroup:
    get:
      summary: Reset D B Cluster Parameter Group
      description: Modifies the parameters of a DB cluster parameter group to the
        default value.
      operationId: resetdbclusterparametergroup
      x-api-path-slug: actionresetdbclusterparametergroup-get
      parameters:
      - in: query
        name: DBClusterParameterGroupName
        description: The name of the DB cluster parameter group to reset
        type: string
      - in: query
        name: Parameters.Parameter.N
        description: A list of parameter names in the DB cluster parameter group to
          reset to the default values
        type: string
      - in: query
        name: ResetAllParameters
        description: A value that is set to true to reset all parameters in the DB
          cluster parameter group       to their default values, and false otherwise
        type: string
      responses:
        200:
          description: OK
      tags:
      - Cluster Parameter Groups
  /?Action=ResetDBParameterGroup:
    get:
      summary: Reset D B Parameter Group
      description: Modifies the parameters of a DB parameter group to the engine/system
        default value.
      operationId: resetdbparametergroup
      x-api-path-slug: actionresetdbparametergroup-get
      parameters:
      - in: query
        name: DBParameterGroupName
        description: The name of the DB parameter group
        type: string
      - in: query
        name: Parameters.Parameter.N
        description: An array of parameter names, values, and the apply method for
          the parameter update
        type: string
      - in: query
        name: ResetAllParameters
        description: Specifies whether (true) or not (false) to reset all parameters        in
          the DB parameter group to default values
        type: string
      responses:
        200:
          description: OK
      tags:
      - Parameter Groups
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