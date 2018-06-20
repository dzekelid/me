{
  "info": {
    "name": "Azure API Management API ApiManagementServices GetSsoToken",
    "_postman_id": "bf800140-280c-4a69-8d1a-d0ede2225dba",
    "description": "Gets the Single-Sign-On token for the API Management Service which is valid for 5 Minutes.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "api management service",
      "item": [
        {
          "id": "30b132bd-9d82-49ce-8339-2c90d87d558d",
          "name": "ApiManagementServices_GetSsoToken",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.ApiManagement/service/:serviceName/getssotoken"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                },
                {
                  "id": "serviceName",
                  "value": "serviceName",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the Single-Sign-On token for the API Management Service which is valid for 5 Minutes"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "626c6e1c-d94c-4644-be41-4afd2be41502"
            }
          ]
        }
      ]
    }
  ]
}