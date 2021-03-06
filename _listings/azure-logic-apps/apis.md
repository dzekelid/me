---
name: Azure Logic Apps
x-slug: azure-logic-apps
description: You can connect apps, data, and devices anywhere&mdash;on-premises or
  in the cloud&mdash;with our large ecosystem of software as a service (SaaS) and
  cloud-based connectors that includes Salesforce, Office 365, Twitter, Dropbox, Google
  services, and more. Its never been easier to access data and keep your disparate
  systems up-to-date, in real-time. New connectors are being added to the Azure Marketplace
  all of the time.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-logic-apps-01-connectors.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-logic-apps/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Logic Apps API Agreements List By Integration Accounts
  x-api-slug: azure-logic-apps-api
  description: Gets a list of integration account agreements.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-logic-apps-01-connectors.png
  humanURL: https://azure.microsoft.com/en-us/services/logic-apps/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Logic/integrationAccounts/{integrationAccountName}/agreements
  tags: Agreements Integration Accounts
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-logic-apps/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-logicintegrationaccountsintegrationaccountnameagreements-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-logic-apps/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-logicintegrationaccountsintegrationaccountnameagreements-get-openapi.md
- name: Azure Logic Apps API Agreements Get
  x-api-slug: azure-logic-apps-api
  description: Gets an integration account agreement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-logic-apps-01-connectors.png
  humanURL: https://azure.microsoft.com/en-us/services/logic-apps/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Logic/integrationAccounts/{integrationAccountName}/agreements/{agreementName}
  tags: Agreements
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-logic-apps/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-logicintegrationaccountsintegrationaccountnameagreementsagreementname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-logic-apps/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-logicintegrationaccountsintegrationaccountnameagreementsagreementname-get-openapi.md
- name: Azure Logic Apps API Agreements Create Or Update
  x-api-slug: azure-logic-apps-api
  description: Creates or updates an integration account agreement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-logic-apps-01-connectors.png
  humanURL: https://azure.microsoft.com/en-us/services/logic-apps/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Logic/integrationAccounts/{integrationAccountName}/agreements/{agreementName}
  tags: Agreements
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-logic-apps/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-logicintegrationaccountsintegrationaccountnameagreementsagreementname-put-openapi.md
- name: Azure Logic Apps API Agreements Delete
  x-api-slug: azure-logic-apps-api
  description: Deletes an integration account agreement.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-logic-apps-01-connectors.png
  humanURL: https://azure.microsoft.com/en-us/services/logic-apps/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Logic/integrationAccounts/{integrationAccountName}/agreements/{agreementName}
  tags: Agreements
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-logic-apps/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-logicintegrationaccountsintegrationaccountnameagreementsagreementname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-logic-apps/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-logicintegrationaccountsintegrationaccountnameagreementsagreementname-delete-openapi.md
- name: Azure Logic Apps API
  x-api-slug: azure-logic-apps-api
  description: You can connect apps, data, and devices anywhere&mdash;on-premises
    or in the cloud&mdash;with our large ecosystem of software as a service (SaaS)
    and cloud-based connectors that includes Salesforce, Office 365, Twitter, Dropbox,
    Google services, and more. Its never been easier to access data and keep your
    disparate systems up-to-date, in real-time. New connectors are being added to
    the Azure Marketplace all of the time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-logic-apps-01-connectors.png
  humanURL: https://azure.microsoft.com/en-us/services/logic-apps/
  baseURL: ://management.azure.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/azure-logic-apps/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/logic-apps/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/logic-apps/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/logic-apps/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/logic-apps/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---