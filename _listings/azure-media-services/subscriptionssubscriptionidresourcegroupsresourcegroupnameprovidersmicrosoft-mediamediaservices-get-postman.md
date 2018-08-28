{
  "info": {
    "name": "Azure Media Services API Media Service List By Resource Group",
    "_postman_id": "9af95250-15a7-40d6-ac6e-5a0457604773",
    "description": "Lists all of the Media Services in a resource group.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "media service resource group",
      "item": [
        {
          "id": "8fa594a4-8988-4efd-8fe2-d957f4f5b9c7",
          "name": "MediaService_ListByResourceGroup",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Media/mediaservices"
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
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the Media Services in a resource group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3ce812d-3199-403c-bad4-5aff84f88d2f"
            }
          ]
        }
      ]
    }
  ]
}