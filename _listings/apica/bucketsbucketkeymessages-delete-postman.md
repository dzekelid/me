{
  "info": {
    "name": "Messages API Clear a bucket (remove all messages).",
    "_postman_id": "937612cd-1cb8-4ceb-a493-a80c669c60ef",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Messages",
      "item": [
        {
          "id": "0d03d005-a0bb-40bd-90fb-b00abf62af1c",
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
              "id": "2f03b5c5-512a-4bd2-9823-899e5ec64f0e"
            }
          ]
        }
      ]
    }
  ]
}