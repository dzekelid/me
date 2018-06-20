---
swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 0
info:
  title: Azure API Management API ApiManagementServices Restore
  description: Restores a backup of an API Management service created using the ApiManagementServices_Backup
    operation on the current service. This is a long running operation and could take
    several minutes to complete.
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/managedeployments
  : post:
      summary: ApiManagementServices ManageDeployments
      description: 'Manages deployments of an API Management service. This operation
        can be used to do the following: Change SKU, Change SKU Units, Change Service
        Tier (Developer/Standard/Premium) and Manage VPN Configuration. This is a
        long running operation and can take several minutes to complete.'
      operationId: ApiManagementServices_ManageDeployments
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamemanagedeployments-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the ManageDeployments operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Management Service
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/restore
  : post:
      summary: ApiManagementServices Restore
      description: Restores a backup of an API Management service created using the
        ApiManagementServices_Backup operation on the current service. This is a long
        running operation and could take several minutes to complete.
      operationId: ApiManagementServices_Restore
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamerestore-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the Restore API Management service from
          backup operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Management Services
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