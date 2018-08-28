{
  "info": {
    "name": "Azure SQL Database API Recommended Elastic Pools Get",
    "_postman_id": "fb5b2b98-5837-44ab-a30e-3d52a3217e17",
    "description": "Gets a recommented elastic pool.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "recommended elastic pools",
      "item": [
        {
          "id": "ba39ad96-6393-40bd-a24f-c23074923b19",
          "name": "RecommendedElasticPools_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Sql/servers/:serverName/recommendedElasticPools/:recommendedElasticPoolName"
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
                  "id": "recommendedElasticPoolName",
                  "value": "{}",
                  "type": "string"
                },
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
            "description": "Gets a recommented elastic pool"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5b044e8f-901b-4bd9-9e11-629b2647c9ae"
            }
          ]
        }
      ]
    }
  ]
}