{
  "info": {
    "name": "Digital River Shopper API Get Shoppers Me Addresses",
    "_postman_id": "288995cb-737f-4366-9fcf-e04cacaa0160",
    "description": "Get shoppers me addresses.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth20",
      "item": [
        {
          "id": "f76ba773-e190-4050-8fea-7437690e5afd",
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
              "id": "64410265-5f6b-4c07-b4ae-d10bc3a193cb"
            }
          ]
        },
        {
          "id": "031e82b1-00c5-4eeb-a21d-826aba1ab443",
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
              "id": "06aed779-d059-4e82-afe7-bbd9a81d820e"
            }
          ]
        }
      ]
    },
    {
      "name": "Shoppers",
      "item": [
        {
          "id": "4efda335-53ba-40c1-8392-aed80e964387",
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
              "id": "ee655a78-0a17-4c47-bf1d-e8ae65e4479b"
            }
          ]
        },
        {
          "id": "38ec2ecc-da14-48e0-8b28-b2c8e6a4170b",
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
              "id": "3132801e-a6d2-42ef-ae4c-52eb870a3951"
            }
          ]
        },
        {
          "id": "16c4cb50-5a31-4661-ac11-29bfa7e377b9",
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
              "id": "4b3a3c9f-161d-4861-b773-16d44e5e0f10"
            }
          ]
        },
        {
          "id": "8559d4c3-4143-4e48-a80d-12201571f09e",
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
              "id": "3a0d5f7c-ae0a-4ce2-a501-b986274b2b1c"
            }
          ]
        },
        {
          "id": "a1d324b5-a6b9-4eba-b5a8-219e5dfd3f75",
          "name": "getV1ShoppersMeAccount",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/account",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d38824c-9f8e-4430-964a-4a8d466d5552"
            }
          ]
        },
        {
          "id": "843ef363-0ab5-4369-97a8-514a4baffc8b",
          "name": "getV1ShoppersMeAddresses",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/addresses",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b28157a-88aa-454a-a5fc-f1b288d1096c"
            }
          ]
        },
        {
          "id": "c827bf86-4872-4b4e-8932-55ab9c020b28",
          "name": "getV1ShoppersMeAddresses",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/addresses/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "644dbe2e-2060-4bd9-80e8-2a20575cd7ac"
            }
          ]
        }
      ]
    }
  ]
}