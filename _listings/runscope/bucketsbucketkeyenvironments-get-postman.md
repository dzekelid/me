{
  "info": {
    "name": "Runscope Get Buckets Environments",
    "_postman_id": "acec95dd-cbd3-4f54-b2de-2c2fced07c28",
    "description": "Returns list of shared environments for a specified bucket.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "buckets",
      "item": [
        {
          "id": "ea6d648a-1c16-45c9-8afb-cbf2b26856ff",
          "name": "buckets.bucketKey.environments.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.runscope.com",
              "path": [
                "buckets/:bucketKey/environments"
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
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns list of shared environments for a specified bucket"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7bda98e9-9cb0-434e-a29d-a51f24fc920a"
            }
          ]
        }
      ]
    }
  ]
}