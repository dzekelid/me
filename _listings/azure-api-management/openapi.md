---
swagger: "2.0"
x-collection-name: Azure API Management
x-complete: 1
info:
  title: ApiManagementClient
  description: use-these-rest-apis-for-performing-operations-on-user-entity-in-azure-api-management-deployment--the-user-entity-in-api-management-represents-the-developers-that-call-the-apis-of-the-products-to-which-they-are-subscribed-
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
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/backup
  : post:
      summary: ApiManagementServices Backup
      description: Creates a backup of the API Management service to the given Azure
        Storage Account. This is long running operation and could take several minutes
        to complete.
      operationId: ApiManagementServices_Backup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamebackup-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the ApiManagementServices_Backup operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Management Service
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/getssotoken
  : post:
      summary: ApiManagementServices GetSsoToken
      description: Gets the Single-Sign-On token for the API Management Service which
        is valid for 5 Minutes.
      operationId: ApiManagementServices_GetSsoToken
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenamegetssotoken-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - API Management Service
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/uploadcertificate
  : post:
      summary: ApiManagementServices UploadCertificate
      description: Upload Custom Domain SSL certificate for an API Management service.
      operationId: ApiManagementServices_UploadCertificate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameuploadcertificate-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the Upload SSL certificate for an API
          Management service operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Management Services
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ApiManagement/service/{serviceName}/updatehostname
  : post:
      summary: ApiManagementServices UpdateHostname
      description: Creates, updates, or deletes the custom hostnames for an API Management
        service. The custom hostname can be applied to the Proxy and Portal endpoint.
        This is a long running operation and could take several minutes to complete.
      operationId: ApiManagementServices_UpdateHostname
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-apimanagementserviceservicenameupdatehostname-post
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters supplied to the UpdateHostname operation
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - API Management Services
---