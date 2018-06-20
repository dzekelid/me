{
  "info": {
    "name": "Messages API Retrieve a list of messages in a bucket",
    "_postman_id": "0b1f7080-b294-4094-9d18-da5737478916",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Messages",
      "item": [
        {
          "id": "3a1c932b-729a-4e40-966e-0153857c6d80",
          "name": "Retrieve a list of messages in a bucket",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
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
                  "key": "since",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "bucketKey",
                  "value": "{}",
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
              "id": "c2832acf-e98a-4640-b1c3-3ad52718191d"
            }
          ]
        },
        {
          "id": "24260439-0c67-456e-a4ae-35e6afac13d5",
          "name": "Clear a bucket (remove all messages).",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "api",
                "buckets/:bucketKey/messages"
              ],
              "variable": [
                {
                  "id": "bucketKey",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Clear a bucket (remove all messages)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65de8365-357d-4b81-8aa9-0ecf5940617b"
            }
          ]
        }
      ]
    }
  ]
}