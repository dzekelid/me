{
  "info": {
    "name": "Runscope Get Buckets Messages",
    "_postman_id": "fd22744e-0520-4eeb-8ce9-1d30491e1f5e",
    "description": "Retrieve a list of messages in a bucket",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "buckets",
      "item": [
        {
          "id": "67b8397b-22bf-47d8-a44a-9f0229a1b50f",
          "name": "buckets.bucketKey.messages.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.runscope.com",
              "path": [
                "buckets/:bucketKey/messages"
              ],
              "query": [
                {
                  "key": "before",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "since",
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a list of messages in a bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f7aa6437-b5a3-4452-bcce-04fcf53702fd"
            }
          ]
        }
      ]
    }
  ]
}