---
swagger: "2.0"
x-collection-name: Azure SQL Database
x-complete: 1
info:
  title: Azure SQL Database
  description: provides-create-read-update-and-delete-functionality-for-azure-sql-database-resources-including-servers-databases-elastic-pools-recommendations-operations-and-usage-metrics-
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/databases/{databaseName}/resume
  : post:
      summary: Databases Resume
      description: Resumes a data warehouse.
      operationId: Databases_Resume
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenameresume-post
      parameters:
      - in: path
        name: databaseName
        description: The name of the data warehouse to resume
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Databases Resume
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}
  : get:
      summary: Recommended Elastic Pools Get
      description: Gets a recommented elastic pool.
      operationId: RecommendedElasticPools_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolname-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: recommendedElasticPoolName
        description: The name of the recommended elastic pool to be retrieved
      responses:
        200:
          description: OK
      tags:
      - Recommended Elastic Pools
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}/databases/{databaseName}
  : get:
      summary: Recommended Elastic Pools Get Databases
      description: Gets a database inside of a recommented elastic pool.
      operationId: RecommendedElasticPools_GetDatabases
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamedatabasesdatabasename-get
      parameters:
      - in: path
        name: databaseName
        description: The name of the database to be retrieved
      - in: query
        name: No Name
      - in: path
        name: recommendedElasticPoolName
        description: The name of the elastic pool to be retrieved
      responses:
        200:
          description: OK
      tags:
      - Recommended Elastic Pools Databases
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools
  : get:
      summary: Recommended Elastic Pools List By Server
      description: Returns recommended elastic pools.
      operationId: RecommendedElasticPools_ListByServer
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpools-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Recommended Elastic Pools Server
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}/databases
  : get:
      summary: Recommended Elastic Pools List Databases
      description: Returns a list of databases inside a recommented elastic pool.
      operationId: RecommendedElasticPools_ListDatabases
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamedatabases-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: recommendedElasticPoolName
        description: The name of the recommended elastic pool to be retrieved
      responses:
        200:
          description: OK
      tags:
      - Recommended Elastic Pools Databases
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}/metrics
  : get:
      summary: Recommended Elastic Pools List Metrics
      description: Returns a recommented elastic pool metrics.
      operationId: RecommendedElasticPools_ListMetrics
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamemetrics-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: recommendedElasticPoolName
        description: The name of the recommended elastic pool to be retrieved
      responses:
        200:
          description: OK
      tags:
      - Recommended Elastic Pools Metrics
---