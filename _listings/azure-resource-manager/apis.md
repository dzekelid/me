---
name: Azure Resource Manager
x-slug: azure-resource-manager
description: Azure Resource Manager enables you to deploy and manage the infrastructure
  for your Azure solutions. You organize related resources in resource groups, and
  deploy your resources with JSON templates. For an introduction to deploying and
  managing resources with Resource Manager, see Azure Resource Manager overview.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Resource Manager API Creates or updates a management lock at the resource
    group level.
  x-api-slug: azure-resource-manager-api
  description: When you apply a lock at a parent scope, all child resources inherit
    the same lock. To create management locks, you must have access to Microsoft.Authorization/*
    or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
    and User Access Administrator are granted those actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Authorization/locks/{lockName}
  tags: Ss A Management Lock At Resource Group Level.
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationlockslockname-put-openapi.md
- name: Azure Resource Manager API Deletes a management lock at the resource group
    level.
  x-api-slug: azure-resource-manager-api
  description: To delete management locks, you must have access to Microsoft.Authorization/*
    or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
    and User Access Administrator are granted those actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Authorization/locks/{lockName}
  tags: S A Management Lock At Resource Group Level.
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationlockslockname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationlockslockname-delete-openapi.md
- name: Azure Resource Manager API Management Locks Get At Resource Group Level
  x-api-slug: azure-resource-manager-api
  description: Gets a management lock at the resource group level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Authorization/locks/{lockName}
  tags: Management Locks At Resource Group Level
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationlockslockname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationlockslockname-get-openapi.md
- name: Azure Resource Manager API Management Locks Create Or Update By Scope
  x-api-slug: azure-resource-manager-api
  description: Create or update a management lock by scope.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////{scope}/providers/Microsoft.Authorization/locks/{lockName}
  tags: Management Locks Scope
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationlockslockname-put-openapi.md
- name: Azure Resource Manager API Management Locks Delete By Scope
  x-api-slug: azure-resource-manager-api
  description: Delete a management lock by scope.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////{scope}/providers/Microsoft.Authorization/locks/{lockName}
  tags: Management Locks Scope
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationlockslockname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationlockslockname-delete-openapi.md
- name: Azure Resource Manager API Management Locks Get By Scope
  x-api-slug: azure-resource-manager-api
  description: Get a management lock by scope.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////{scope}/providers/Microsoft.Authorization/locks/{lockName}
  tags: Management Locks Scope
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationlockslockname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationlockslockname-get-openapi.md
- name: Azure Resource Manager API Creates or updates a management lock at the resource
    level or any level below the resource.
  x-api-slug: azure-resource-manager-api
  description: When you apply a lock at a parent scope, all child resources inherit
    the same lock. To create management locks, you must have access to Microsoft.Authorization/*
    or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
    and User Access Administrator are granted those actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePath}/{resourceType}/{resourceName}/providers/Microsoft.Authorization/locks/{lockName}
  tags: Management Locks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationlockslockname-put-openapi.md
- name: Azure Resource Manager API Deletes the management lock of a resource or any
    level below the resource.
  x-api-slug: azure-resource-manager-api
  description: To delete management locks, you must have access to Microsoft.Authorization/*
    or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
    and User Access Administrator are granted those actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePath}/{resourceType}/{resourceName}/providers/Microsoft.Authorization/locks/{lockName}
  tags: Management Locks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationlockslockname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationlockslockname-delete-openapi.md
- name: Azure Resource Manager API Management Locks Get At Resource Level
  x-api-slug: azure-resource-manager-api
  description: Get the management lock of a resource or any level below resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePath}/{resourceType}/{resourceName}/providers/Microsoft.Authorization/locks/{lockName}
  tags: Management Locks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationlockslockname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationlockslockname-get-openapi.md
- name: Azure Resource Manager API Creates or updates a management lock at the subscription
    level.
  x-api-slug: azure-resource-manager-api
  description: When you apply a lock at a parent scope, all child resources inherit
    the same lock. To create management locks, you must have access to Microsoft.Authorization/*
    or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
    and User Access Administrator are granted those actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Authorization/locks/{lockName}
  tags: Ss A Management Lock At Subscription Level.
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidprovidersmicrosoft-authorizationlockslockname-put-openapi.md
- name: Azure Resource Manager API Deletes the management lock at the subscription
    level.
  x-api-slug: azure-resource-manager-api
  description: To delete management locks, you must have access to Microsoft.Authorization/*
    or Microsoft.Authorization/locks/* actions. Of the built-in roles, only Owner
    and User Access Administrator are granted those actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Authorization/locks/{lockName}
  tags: S Management Lock At Subscription Level.
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidprovidersmicrosoft-authorizationlockslockname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidprovidersmicrosoft-authorizationlockslockname-delete-openapi.md
- name: Azure Resource Manager API Management Locks Get At Subscription Level
  x-api-slug: azure-resource-manager-api
  description: Gets a management lock at the subscription level.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Authorization/locks/{lockName}
  tags: Management Locks At Subscription Level
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidprovidersmicrosoft-authorizationlockslockname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidprovidersmicrosoft-authorizationlockslockname-get-openapi.md
- name: Azure Resource Manager API Management Locks List At Resource Group Level
  x-api-slug: azure-resource-manager-api
  description: Gets all the management locks for a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Authorization/locks
  tags: Management Locks At Resource Group Level
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationlocks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationlocks-get-openapi.md
- name: Azure Resource Manager API Management Locks List At Resource Level
  x-api-slug: azure-resource-manager-api
  description: Gets all the management locks for a resource or any level below resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePath}/{resourceType}/{resourceName}/providers/Microsoft.Authorization/locks
  tags: Management Locks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationlocks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationlocks-get-openapi.md
- name: Azure Resource Manager API Management Locks List At Subscription Level
  x-api-slug: azure-resource-manager-api
  description: Gets all the management locks for a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Authorization/locks
  tags: Management Locks At Subscription Level
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidprovidersmicrosoft-authorizationlocks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidprovidersmicrosoft-authorizationlocks-get-openapi.md
- name: Azure Resource Manager API Policy Assignments Delete
  x-api-slug: azure-resource-manager-api
  description: Deletes a policy assignment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////{scope}/providers/Microsoft.Authorization/policyassignments/{policyAssignmentName}
  tags: Policy Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-delete-openapi.md
- name: Azure Resource Manager API Creates a policy assignment.
  x-api-slug: azure-resource-manager-api
  description: Policy assignments are inherited by child resources. For example, when
    you apply a policy to a resource group that policy is assigned to all resources
    in the group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////{scope}/providers/Microsoft.Authorization/policyassignments/{policyAssignmentName}
  tags: Policy Assignments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-put-openapi.md
- name: Azure Resource Manager API Policy Assignments Get
  x-api-slug: azure-resource-manager-api
  description: Gets a policy assignment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////{scope}/providers/Microsoft.Authorization/policyassignments/{policyAssignmentName}
  tags: Policy Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/scopeprovidersmicrosoft-authorizationpolicyassignmentspolicyassignmentname-get-openapi.md
- name: Azure Resource Manager API Policy Assignments List For Resource Group
  x-api-slug: azure-resource-manager-api
  description: Gets policy assignments for the resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Authorization/policyAssignments
  tags: Policy Assignments For Resource Group
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationpolicyassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-authorizationpolicyassignments-get-openapi.md
- name: Azure Resource Manager API Policy Assignments List For Resource
  x-api-slug: azure-resource-manager-api
  description: Gets policy assignments for a resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePath}/{resourceType}/{resourceName}/providers/Microsoft.Authorization/policyassignments
  tags: Policy Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationpolicyassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersresourceprovidernamespaceparentresourcepathresourcetyperesourcenameprovidersmicrosoft-authorizationpolicyassignments-get-openapi.md
- name: Azure Resource Manager API Policy Assignments List
  x-api-slug: azure-resource-manager-api
  description: Gets all the policy assignments for a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.Authorization/policyassignments
  tags: Policy Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidprovidersmicrosoft-authorizationpolicyassignments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidprovidersmicrosoft-authorizationpolicyassignments-get-openapi.md
- name: Azure Resource Manager API Deletes a policy assignment by ID.
  x-api-slug: azure-resource-manager-api
  description: When providing a scope for the assigment, use '/subscriptions/{subscription-id}/'
    for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}'
    for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}'
    for resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////{policyAssignmentId}
  tags: Policy Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/policyassignmentid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/policyassignmentid-delete-openapi.md
- name: Azure Resource Manager API Creates a policy assignment by ID.
  x-api-slug: azure-resource-manager-api
  description: Policy assignments are inherited by child resources. For example, when
    you apply a policy to a resource group that policy is assigned to all resources
    in the group. When providing a scope for the assigment, use '/subscriptions/{subscription-id}/'
    for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}'
    for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}'
    for resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////{policyAssignmentId}
  tags: Policy Assignments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/policyassignmentid-put-openapi.md
- name: Azure Resource Manager API Gets a policy assignment by ID.
  x-api-slug: azure-resource-manager-api
  description: When providing a scope for the assigment, use '/subscriptions/{subscription-id}/'
    for subscriptions, '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}'
    for resource groups, and '/subscriptions/{subscription-id}/resourceGroups/{resource-group-name}/providers/{resource-provider-namespace}/{resource-type}/{resource-name}'
    for resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////{policyAssignmentId}
  tags: Policy Assignments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/policyassignmentid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/policyassignmentid-get-openapi.md
- name: Azure Resource Manager API Deletes a deployment from the deployment history.
  x-api-slug: azure-resource-manager-api
  description: A template deployment that is currently running cannot be deleted.
    Deleting a template deployment removes the associated deployment operations. Deleting
    a template deployment does not affect the state of the resource group. This is
    an asynchronous operation that returns a status of 202 until the template deployment
    is successfully deleted. The Location response header contains the URI that is
    used to obtain the status of the process. While the process is running, a call
    to the URI in the Location header returns a status of 202. When the process finishes,
    the URI in the Location header returns a status of 204 on success. If the asynchronous
    request failed, the URI in the Location header returns an error-level status code.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/Microsoft.Resources/deployments/{deploymentName}
  tags: Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentname-delete-openapi.md
- name: Azure Resource Manager API Deployments Check Existence
  x-api-slug: azure-resource-manager-api
  description: Checks whether the deployment exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/Microsoft.Resources/deployments/{deploymentName}
  tags: Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentname-head-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentname-head-openapi.md
- name: Azure Resource Manager API Deploys resources to a resource group.
  x-api-slug: azure-resource-manager-api
  description: You can provide the template and parameters directly in the request
    or link to JSON files.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/Microsoft.Resources/deployments/{deploymentName}
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentname-put-openapi.md
- name: Azure Resource Manager API Deployments Get
  x-api-slug: azure-resource-manager-api
  description: Gets a deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/Microsoft.Resources/deployments/{deploymentName}
  tags: Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentname-get-openapi.md
- name: Azure Resource Manager API Cancels a currently running template deployment.
  x-api-slug: azure-resource-manager-api
  description: You can cancel a deployment only if the provisioningState is Accepted
    or Running. After the deployment is canceled, the provisioningState is set to
    Canceled. Canceling a template deployment stops the currently running template
    deployment and leaves the resource group partially deployed.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/Microsoft.Resources/deployments/{deploymentName}/cancel
  tags: Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentnamecancel-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentnamecancel-post-openapi.md
- name: Azure Resource Manager API Deployments Validate
  x-api-slug: azure-resource-manager-api
  description: Validates whether the specified template is syntactically correct and
    will be accepted by Azure Resource Manager..
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/Microsoft.Resources/deployments/{deploymentName}/validate
  tags: Deployments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentnamevalidate-post-openapi.md
- name: Azure Resource Manager API Deployments Export Template
  x-api-slug: azure-resource-manager-api
  description: Exports the template used for specified deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/Microsoft.Resources/deployments/{deploymentName}/exportTemplate
  tags: Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentnameexporttemplate-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeploymentsdeploymentnameexporttemplate-post-openapi.md
- name: Azure Resource Manager API Deployments List
  x-api-slug: azure-resource-manager-api
  description: Get all the deployments for a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/Microsoft.Resources/deployments/
  tags: Deployments
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeployments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-resourcesdeployments-get-openapi.md
- name: Azure Resource Manager API Deployment Operations Get
  x-api-slug: azure-resource-manager-api
  description: Gets a deployments operation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/deployments/{deploymentName}/operations/{operationId}
  tags: Deployment Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnamedeploymentsdeploymentnameoperationsoperationid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnamedeploymentsdeploymentnameoperationsoperationid-get-openapi.md
- name: Azure Resource Manager API Deployment Operations List
  x-api-slug: azure-resource-manager-api
  description: Gets all deployments operations for a deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/deployments/{deploymentName}/operations
  tags: Deployment Operations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnamedeploymentsdeploymentnameoperations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/subscriptionssubscriptionidresourcegroupsresourcegroupnamedeploymentsdeploymentnameoperations-get-openapi.md
- name: Azure Resource Manager API
  x-api-slug: azure-resource-manager-api
  description: Azure Resource Manager enables you to deploy and manage the infrastructure
    for your Azure solutions. You organize related resources in resource groups, and
    deploy your resources with JSON templates. For an introduction to deploying and
    managing resources with Resource Manager, see Azure Resource Manager overview.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-resource-manager.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/resources/
  baseURL: ://management.azure.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-resource-manager/openapi.md
x-common:
- type: x-website
  url: https://docs.microsoft.com/en-us/rest/api/resources/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---