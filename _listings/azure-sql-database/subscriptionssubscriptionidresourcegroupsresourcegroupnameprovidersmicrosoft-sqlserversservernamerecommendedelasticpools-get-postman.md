{
  "info": {
    "name": "Azure SQL Database API Recommended Elastic Pools List By Server",
    "_postman_id": "71e8f8cb-8a85-4d4d-8756-22344aa5fe15",
    "description": "Returns recommended elastic pools.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "recommended elastic pools server",
      "item": [
        {
          "id": "5563b297-a04b-4b45-9792-89198552a467",
          "name": "RecommendedElasticPools_ListByServer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Sql/servers/:serverName/recommendedElasticPools"
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
                  "id": "serverName",
                  "value": "serverName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns recommended elastic pools"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f76c6dc1-ef8c-4030-bfe7-0db98a698af0"
            }
          ]
        }
      ]
    }
  ]
}