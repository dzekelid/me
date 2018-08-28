{
  "info": {
    "name": "Runscope Delete Buckets Messages",
    "_postman_id": "badcdccb-916e-4c5f-99eb-9ff7d14908d2",
    "description": "Clear a bucket (remove all messages).",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "buckets",
      "item": [
        {
          "id": "c1d1ad94-1edc-469a-8b23-50c133c503a6",
          "name": "buckets.bucketKey.messages.delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.runscope.com",
              "path": [
                "buckets/:bucketKey/messages"
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
                  "id": "bucketKey",
                  "value": "bucketKey",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Clear a bucket (remove all messages)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2439f95-0f35-47ff-983a-502bfb7cbdda"
            }
          ]
        }
      ]
    }
  ]
}