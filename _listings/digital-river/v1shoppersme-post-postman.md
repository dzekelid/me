{
  "info": {
    "name": "Digital River Shopper API Post Shoppers Me",
    "_postman_id": "e6f969b5-a0ac-4ddc-ab1e-ec9127e33074",
    "description": "Post shoppers me.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth20",
      "item": [
        {
          "id": "0a904aa4-3322-462f-a7eb-3b02a35cd4b4",
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
              "id": "73a603b6-5e3d-4385-a11b-4b7838d0c7f7"
            }
          ]
        },
        {
          "id": "2bf9bf08-6a2b-44ae-ba08-e8a98c64d350",
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
              "id": "8ae96cb2-b7d3-4e91-aeef-77df7a5311aa"
            }
          ]
        }
      ]
    },
    {
      "name": "Shoppers",
      "item": [
        {
          "id": "e83b7891-4177-46a2-baf3-0c6699466bad",
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
              "id": "9fc23fb3-556e-4393-b92b-5d0234bd543a"
            }
          ]
        },
        {
          "id": "35d54d81-2e69-4fae-a679-3dcf1bf6b52a",
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
              "id": "44542960-af96-473b-8fb8-536991b60af1"
            }
          ]
        },
        {
          "id": "029aaa66-ca99-4bab-9d38-c41a492ea9c6",
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
              "id": "bb91db82-4b71-49ea-acb0-fa34e964bc59"
            }
          ]
        },
        {
          "id": "ca19e728-57b2-4cc1-8694-93e813312493",
          "name": "postV1ShoppersMe",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "99ffa9b4-af79-49b8-bf95-0439d9285c82"
            }
          ]
        }
      ]
    }
  ]
}