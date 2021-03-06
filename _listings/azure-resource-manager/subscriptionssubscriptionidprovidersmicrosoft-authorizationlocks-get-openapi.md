---
swagger: "2.0"
x-collection-name: Azure Resource Manager
x-complete: 0
info:
  title: Azure Resource Manager API Management Locks List At Subscription Level
  description: Gets all the management locks for a subscription.
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
  /{scope}/providers/Microsoft.Authorization/locks/{lockName}:
    put:
      summary: Management Locks Create Or Update By Scope
      description: Create or update a management lock by scope.
      operationId: ManagementLocks_CreateOrUpdateByScope
      x-api-path-slug: scopeprovidersmicrosoft-authorizationlockslockname-put
      parameters:
      - in: path
        name: lockName
        description: The name of lock
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Create or update management lock parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: scope
        description: The scope for the lock
      responses:
        200:
          description: OK
      tags:
      - Management Locks Scope
    delete:
      summary: Management Locks Delete By Scope
      description: Delete a management lock by scope.
      operationId: ManagementLocks_DeleteByScope
      x-api-path-slug: scopeprovidersmicrosoft-authorizationlockslockname-delete
      parameters:
      - in: path
        name: lockName
        description: The name of lock
      - in: query
        name: No Name
      - in: path
        name: scope
        description: The scope for the lock
      responses:
        200:
          description: OK
      tags:
      - Management Locks Scope
    get:
      summary: Management Locks Get By Scope
      description: Get a management lock by scope.
      operationId: ManagementLocks_GetByScope
      x-api-path-slug: scopeprovidersmicrosoft-authorizationlockslockname-get
      parameters:
      - in: path
        name: lockName
        description: The name of lock
      - in: query
        name: No Name
      - in: path
        name: scope
        description: The scope for the lock
      responses:
        200:
          description: OK
      tags:
      - Management Locks Scope
  ? /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePath}/{resourceType}/{resourceName}/providers/Microsoft.Authorization/locks/{lockName}
  : put:
      summary: Creates or updates a management lock at the resource level or any level
        below the resource.
      description: When you apply a lock at a parent scope, all child resources inherit
        the same lock. To create management locks, you must have access to Microsoft.Authorization/*
        or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
        and User Access Administrator are granted those actions.
      operationId: ManagementLocks_CreateOrUpdateAtResourceLevel
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationlockslockname-put
      parameters:
      - in: path
        name: lockName
        description: The name of lock
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters for creating or updating a  management lock
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: parentResourcePath
        description: The parent resource identity
      - in: path
        name: resourceGroupName
        description: The name of the resource group containing the resource to lock
      - in: path
        name: resourceName
        description: The name of the resource to lock
      - in: path
        name: resourceProviderNamespace
        description: The resource provider namespace of the resource to lock
      - in: path
        name: resourceType
        description: The resource type of the resource to lock
      responses:
        200:
          description: OK
      tags:
      - Management Locks
    delete:
      summary: Deletes the management lock of a resource or any level below the resource.
      description: To delete management locks, you must have access to Microsoft.Authorization/*
        or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
        and User Access Administrator are granted those actions.
      operationId: ManagementLocks_DeleteAtResourceLevel
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationlockslockname-delete
      parameters:
      - in: path
        name: lockName
        description: The name of the lock to delete
      - in: query
        name: No Name
      - in: path
        name: parentResourcePath
        description: The parent resource identity
      - in: path
        name: resourceGroupName
        description: The name of the resource group containing the resource with the
          lock to delete
      - in: path
        name: resourceName
        description: The name of the resource with the lock to delete
      - in: path
        name: resourceProviderNamespace
        description: The resource provider namespace of the resource with the lock
          to delete
      - in: path
        name: resourceType
        description: The resource type of the resource with the lock to delete
      responses:
        200:
          description: OK
      tags:
      - Management Locks
    get:
      summary: Management Locks Get At Resource Level
      description: Get the management lock of a resource or any level below resource.
      operationId: ManagementLocks_GetAtResourceLevel
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationlockslockname-get
      parameters:
      - in: path
        name: lockName
        description: The name of lock
      - in: query
        name: No Name
      - in: path
        name: parentResourcePath
        description: An extra path parameter needed in some services, like SQL Databases
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      - in: path
        name: resourceName
        description: The name of the resource
      - in: path
        name: resourceProviderNamespace
        description: The namespace of the resource provider
      - in: path
        name: resourceType
        description: The type of the resource
      responses:
        200:
          description: OK
      tags:
      - Management Locks
  /subscriptions/{subscriptionId}/providers/Microsoft.Authorization/locks/{lockName}:
    put:
      summary: Creates or updates a management lock at the subscription level.
      description: When you apply a lock at a parent scope, all child resources inherit
        the same lock. To create management locks, you must have access to Microsoft.Authorization/*
        or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
        and User Access Administrator are granted those actions.
      operationId: ManagementLocks_CreateOrUpdateAtSubscriptionLevel
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-authorizationlockslockname-put
      parameters:
      - in: path
        name: lockName
        description: The name of lock
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The management lock parameters
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Ss A Management Lock At Subscription Level.
    delete:
      summary: Deletes the management lock at the subscription level.
      description: To delete management locks, you must have access to Microsoft.Authorization/*
        or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
        and User Access Administrator are granted those actions.
      operationId: ManagementLocks_DeleteAtSubscriptionLevel
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-authorizationlockslockname-delete
      parameters:
      - in: path
        name: lockName
        description: The name of lock to delete
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - S Management Lock At Subscription Level.
    get:
      summary: Management Locks Get At Subscription Level
      description: Gets a management lock at the subscription level.
      operationId: ManagementLocks_GetAtSubscriptionLevel
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-authorizationlockslockname-get
      parameters:
      - in: path
        name: lockName
        description: The name of the lock to get
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Management Locks At Subscription Level
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Authorization/locks:
    get:
      summary: Management Locks List At Resource Group Level
      description: Gets all the management locks for a resource group.
      operationId: ManagementLocks_ListAtResourceGroupLevel
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationlocks-get
      parameters:
      - in: query
        name: $filter
        description: The filter to apply on the operation
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group containing the locks to get
      responses:
        200:
          description: OK
      tags:
      - Management Locks At Resource Group Level
  ? /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePath}/{resourceType}/{resourceName}/providers/Microsoft.Authorization/locks
  : get:
      summary: Management Locks List At Resource Level
      description: Gets all the management locks for a resource or any level below
        resource.
      operationId: ManagementLocks_ListAtResourceLevel
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationlocks-get
      parameters:
      - in: query
        name: $filter
        description: The filter to apply on the operation
      - in: query
        name: No Name
      - in: path
        name: parentResourcePath
        description: The parent resource identity
      - in: path
        name: resourceGroupName
        description: The name of the resource group containing the locked resource
      - in: path
        name: resourceName
        description: The name of the locked resource
      - in: path
        name: resourceProviderNamespace
        description: The namespace of the resource provider
      - in: path
        name: resourceType
        description: The resource type of the locked resource
      responses:
        200:
          description: OK
      tags:
      - Management Locks
  /subscriptions/{subscriptionId}/providers/Microsoft.Authorization/locks:
    get:
      summary: Management Locks List At Subscription Level
      description: Gets all the management locks for a subscription.
      operationId: ManagementLocks_ListAtSubscriptionLevel
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-authorizationlocks-get
      parameters:
      - in: query
        name: $filter
        description: The filter to apply on the operation
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Management Locks At Subscription Level
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