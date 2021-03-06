---
swagger: "2.0"
x-collection-name: Azure Resource Manager
x-complete: 0
info:
  title: Azure Resource Manager API Deployments Get
  description: Gets a deployment.
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
  /{scope}/providers/Microsoft.Authorization/policyassignments/{policyAssignmentName}:
    delete:
      summary: Policy Assignments Delete
      description: Deletes a policy assignment.
      operationId: PolicyAssignments_Delete
      x-api-path-slug: scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: policyAssignmentName
        description: The name of the policy assignment to delete
      - in: path
        name: scope
        description: The scope of the policy assignment
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments
    put:
      summary: Creates a policy assignment.
      description: Policy assignments are inherited by child resources. For example,
        when you apply a policy to a resource group that policy is assigned to all
        resources in the group.
      operationId: PolicyAssignments_Create
      x-api-path-slug: scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters for the policy assignment
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: policyAssignmentName
        description: The name of the policy assignment
      - in: path
        name: scope
        description: The scope of the policy assignment
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments
    get:
      summary: Policy Assignments Get
      description: Gets a policy assignment.
      operationId: PolicyAssignments_Get
      x-api-path-slug: scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: policyAssignmentName
        description: The name of the policy assignment to get
      - in: path
        name: scope
        description: The scope of the policy assignment
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Authorization/policyAssignments:
    get:
      summary: Policy Assignments List For Resource Group
      description: Gets policy assignments for the resource group.
      operationId: PolicyAssignments_ListForResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationpolicyassignments-get
      parameters:
      - in: query
        name: $filter
        description: The filter to apply on the operation
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group that contains policy assignments
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments For Resource Group
  ? /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePath}/{resourceType}/{resourceName}/providers/Microsoft.Authorization/policyassignments
  : get:
      summary: Policy Assignments List For Resource
      description: Gets policy assignments for a resource.
      operationId: PolicyAssignments_ListForResource
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationpolicyassignments-get
      parameters:
      - in: query
        name: $filter
        description: The filter to apply on the operation
      - in: query
        name: No Name
      - in: path
        name: parentResourcePath
        description: The parent resource path
      - in: path
        name: resourceGroupName
        description: The name of the resource group containing the resource
      - in: path
        name: resourceName
        description: The name of the resource with policy assignments
      - in: path
        name: resourceProviderNamespace
        description: The namespace of the resource provider
      - in: path
        name: resourceType
        description: The resource type
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments
  /subscriptions/{subscriptionId}/providers/Microsoft.Authorization/policyassignments:
    get:
      summary: Policy Assignments List
      description: Gets all the policy assignments for a subscription.
      operationId: PolicyAssignments_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-authorizationpolicyassignments-get
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
      - Policy Assignments
  /{policyAssignmentId}:
    delete:
      summary: Deletes a policy assignment by ID.
      description: When providing a scope for the assigment, use '/subscriptions/{subscription-id}/'
        for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}'
        for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}'
        for resources.
      operationId: PolicyAssignments_DeleteById
      x-api-path-slug: policyassignmentid-delete
      parameters:
      - in: query
        name: No Name
      - in: path
        name: policyAssignmentId
        description: The ID of the policy assignment to delete
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments
    put:
      summary: Creates a policy assignment by ID.
      description: Policy assignments are inherited by child resources. For example,
        when you apply a policy to a resource group that policy is assigned to all
        resources in the group. When providing a scope for the assigment, use '/subscriptions/{subscription-id}/'
        for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}'
        for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}'
        for resources.
      operationId: PolicyAssignments_CreateById
      x-api-path-slug: policyassignmentid-put
      parameters:
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Parameters for policy assignment
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: policyAssignmentId
        description: The ID of the policy assignment to create
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments
    get:
      summary: Gets a policy assignment by ID.
      description: When providing a scope for the assigment, use '/subscriptions/{subscription-id}/'
        for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}'
        for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}'
        for resources.
      operationId: PolicyAssignments_GetById
      x-api-path-slug: policyassignmentid-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: policyAssignmentId
        description: The ID of the policy assignment to get
      responses:
        200:
          description: OK
      tags:
      - Policy Assignments
  /subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/Microsoft.Resources/deployments/{deploymentName}:
    delete:
      summary: Deletes a deployment from the deployment history.
      description: A template deployment that is currently running cannot be deleted.
        Deleting a template deployment removes the associated deployment operations.
        Deleting a template deployment does not affect the state of the resource group.
        This is an asynchronous operation that returns a status of 202 until the template
        deployment is successfully deleted. The Location response header contains
        the URI that is used to obtain the status of the process. While the process
        is running, a call to the URI in the Location header returns a status of 202.
        When the process finishes, the URI in the Location header returns a status
        of 204 on success. If the asynchronous request failed, the URI in the Location
        header returns an error-level status code.
      operationId: Deployments_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentname-delete
      parameters:
      - in: path
        name: deploymentName
        description: The name of the deployment to delete
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group with the deployment to delete
      responses:
        200:
          description: OK
      tags:
      - Deployments
    head:
      summary: Deployments Check Existence
      description: Checks whether the deployment exists.
      operationId: Deployments_CheckExistence
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentname-head
      parameters:
      - in: path
        name: deploymentName
        description: The name of the deployment to check
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group with the deployment to check
      responses:
        200:
          description: OK
      tags:
      - Deployments
    put:
      summary: Deploys resources to a resource group.
      description: You can provide the template and parameters directly in the request
        or link to JSON files.
      operationId: Deployments_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentname-put
      parameters:
      - in: path
        name: deploymentName
        description: The name of the deployment
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: Additional parameters supplied to the operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: resourceGroupName
        description: The name of the resource group to deploy the resources to
      responses:
        200:
          description: OK
      tags:
      - Deployments
    get:
      summary: Deployments Get
      description: Gets a deployment.
      operationId: Deployments_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentname-get
      parameters:
      - in: path
        name: deploymentName
        description: The name of the deployment to get
      - in: query
        name: No Name
      - in: path
        name: resourceGroupName
        description: The name of the resource group
      responses:
        200:
          description: OK
      tags:
      - Deployments
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