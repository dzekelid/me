---
swagger: "2.0"
x-collection-name: Azure Resource Manager
x-complete: 0
info:
  title: Azure Resource Manager API Management Locks Get At Resource Group Level
  description: Gets a management lock at the resource group level.
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
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Authorization/locks/{lockName}:
    put:
      summary: Creates or updates a management lock at the resource group level.
      description: When you apply a lock at a parent scope, all child resources inherit
        the same lock. To create management locks, you must have access to Microsoft.Authorization/*
        or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
        and User Access Administrator are granted those actions.
      operationId: ManagementLocks_CreateOrUpdateAtResourceGroupLevel
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationlockslockname-put
      parameters:
      - in: path
        name: lockName
        description: The lock name
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The management lock parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group to lock
      responses:
        200:
          description: OK
      tags:
      - Ss A Management Lock At Resource Group Level.
    delete:
      summary: Deletes a management lock at the resource group level.
      description: To delete management locks, you must have access to Microsoft.Authorization/*
        or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
        and User Access Administrator are granted those actions.
      operationId: ManagementLocks_DeleteAtResourceGroupLevel
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationlockslockname-delete
      parameters:
      - in: path
        name: lockName
        description: The name of lock to delete
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group containing the lock
      responses:
        200:
          description: OK
      tags:
      - S A Management Lock At Resource Group Level.
    get:
      summary: Management Locks Get At Resource Group Level
      description: Gets a management lock at the resource group level.
      operationId: ManagementLocks_GetAtResourceGroupLevel
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationlockslockname-get
      parameters:
      - in: path
        name: lockName
        description: The name of the lock to get
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the locked resource group
      responses:
        200:
          description: OK
      tags:
      - Management Locks At Resource Group Level
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