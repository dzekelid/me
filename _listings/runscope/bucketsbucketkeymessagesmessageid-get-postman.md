{
  "info": {
    "name": "Runscope Get Buckets Messages Message",
    "_postman_id": "747cc8c8-b7b6-4a97-9a85-56957539af15",
    "description": "Retrieve the details for a single message.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "buckets",
      "item": [
        {
          "id": "3bd75d15-69ff-4fb4-a446-b9c1e41c2477",
          "name": "buckets.bucketKey.messages.messageId.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.runscope.com",
              "path": [
                "buckets/:bucketKey/messages/:messageId"
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
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "bucketKey",
                  "value": "bucketKey",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve the details for a single message"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7c998025-6743-44c5-84fb-8781daa79555"
            }
          ]
        }
      ]
    }
  ]
}