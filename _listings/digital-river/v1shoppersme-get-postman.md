{
  "info": {
    "name": "Digital River Shopper API Get Shoppers Me",
    "_postman_id": "7634912a-1f23-4590-8704-e5b1affdc7d0",
    "description": "Get shoppers me.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth20",
      "item": [
        {
          "id": "fb04deb0-7193-4704-a327-e8a856e8c6db",
          "name": "getOauth20Authorize",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../oauth20/authorize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get oauth20 authorize."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e59e109d-6aef-49f7-ae05-90f9a1b28445"
            }
          ]
        },
        {
          "id": "611717e5-b963-4c80-8ff6-eb6f18a0440e",
          "name": "postOauth20Token",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../oauth20/token",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post oauth20 token."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5a18dc6-270f-43d2-843d-03e28f4db87c"
            }
          ]
        }
      ]
    },
    {
      "name": "Shoppers",
      "item": [
        {
          "id": "85acafb8-2472-4707-9865-8d8ef444d088",
          "name": "postV1Shoppers",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4692d2a9-4a4f-4499-83d7-5e04d6e4b5c8"
            }
          ]
        },
        {
          "id": "58e814c4-608d-4284-af64-3bfcc8ec8722",
          "name": "getV1ShoppersApi",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers-api",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "72127956-457b-47f7-88dc-62d1271aa5ae"
            }
          ]
        },
        {
          "id": "27d985e7-5a23-4bae-bcc7-ea4ac12a124f",
          "name": "getV1ShoppersMe",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "74f3d2f7-a81b-49c5-8b75-5395a82726d3"
            }
          ]
        }
      ]
    }
  ]
}