{
  "info": {
    "name": "Azure Media Services API Media Service Delete",
    "_postman_id": "960cae78-d11d-4f2b-b92a-b69fac548a4a",
    "description": "Deletes a Media Service.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "media service",
      "item": [
        {
          "id": "55fe2159-f4d9-4eea-96de-a8d4d0dcc80f",
          "name": "MediaService_Delete",
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
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a Media Service"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2106bcb-9114-4a3a-89a0-d7870a061943"
            }
          ]
        }
      ]
    }
  ]
}