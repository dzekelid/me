---
name: Azure SQL Database
x-slug: azure-sql-database
description: Make building and maintaining applications easier and more productive.
  With built-in intelligence that learns app patterns and adapts to maximize performance,
  reliability, and data protection, SQL Database is a cloud database built for developers.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/apis.md
specificationVersion: "0.14"
apis:
- name: Azure SQL Database API Databases Resume
  x-api-slug: azure-sql-database-api
  description: Resumes a data warehouse.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/databases/{databaseName}/resume
  tags: Databases Resume
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenameresume-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamedatabasesdatabasenameresume-post-openapi.md
- name: Azure SQL Database API Recommended Elastic Pools Get
  x-api-slug: azure-sql-database-api
  description: Gets a recommented elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}
  tags: Recommended Elastic Pools
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolname-get-openapi.md
- name: Azure SQL Database API Recommended Elastic Pools Get Databases
  x-api-slug: azure-sql-database-api
  description: Gets a database inside of a recommented elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}/databases/{databaseName}
  tags: Recommended Elastic Pools Databases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamedatabasesdatabasename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamedatabasesdatabasename-get-openapi.md
- name: Azure SQL Database API Recommended Elastic Pools List By Server
  x-api-slug: azure-sql-database-api
  description: Returns recommended elastic pools.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools
  tags: Recommended Elastic Pools Server
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpools-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpools-get-openapi.md
- name: Azure SQL Database API Recommended Elastic Pools List Databases
  x-api-slug: azure-sql-database-api
  description: Returns a list of databases inside a recommented elastic pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}/databases
  tags: Recommended Elastic Pools Databases
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamedatabases-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamedatabases-get-openapi.md
- name: Azure SQL Database API Recommended Elastic Pools List Metrics
  x-api-slug: azure-sql-database-api
  description: Returns a recommented elastic pool metrics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/recommendedElasticPools/{recommendedElasticPoolName}/metrics
  tags: Recommended Elastic Pools Metrics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamemetrics-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-sqlserversservernamerecommendedelasticpoolsrecommendedelasticpoolnamemetrics-get-openapi.md
- name: Azure SQL Database API
  x-api-slug: azure-sql-database-api
  description: Make building and maintaining applications easier and more productive.
    With built-in intelligence that learns app patterns and adapts to maximize performance,
    reliability, and data protection, SQL Database is a cloud database built for developers.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-sql-01-stop-worrying.png
  humanURL: https://azure.microsoft.com/en-us/services/sql-database/
  baseURL: ://management.azure.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-sql-database/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/sql-database/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/sql-database/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/sql-database/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/sql-database/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---