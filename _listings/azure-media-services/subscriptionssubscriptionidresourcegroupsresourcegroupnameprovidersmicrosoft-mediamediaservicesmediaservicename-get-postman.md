{
  "info": {
    "name": "Azure Media Services API Media Service Get",
    "_postman_id": "a48ac302-8081-4105-8ab6-7cb8179d2f5e",
    "description": "Gets a Media Service.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "media service",
      "item": [
        {
          "id": "47821ef1-e1d1-4bdc-be9b-ba1132c8fbb2",
          "name": "MediaService_Get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.Media/mediaservices/:mediaServiceName"
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
                  "id": "mediaServiceName",
                  "value": "mediaServiceName",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets a Media Service"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "734786b5-c997-4fd6-b654-dd76ce5cd3c0"
            }
          ]
        }
      ]
    }
  ]
}