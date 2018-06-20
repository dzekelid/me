{
  "info": {
    "name": "Digital River Shopper API Get Shoppers Me Addresses",
    "_postman_id": "3f61c28d-3649-4c45-8680-440839087f13",
    "description": "Get shoppers me addresses.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth20",
      "item": [
        {
          "id": "1282969c-ad63-4347-889e-8ff9c6bee294",
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
              "id": "13129a1a-7b0e-48f4-9a4b-13e6ad39202f"
            }
          ]
        },
        {
          "id": "9155a1e8-aa9b-4ab5-b639-1641c3dcedb2",
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
              "id": "472e5986-8149-4a90-90c0-c062a24831f3"
            }
          ]
        }
      ]
    },
    {
      "name": "Shoppers",
      "item": [
        {
          "id": "6a40c218-bdc2-4859-93df-63e012e7efaf",
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
              "id": "a14b091c-67ba-462e-ae2d-74cbfab283a8"
            }
          ]
        },
        {
          "id": "b6bba196-7cfc-4a4b-b7d7-a09682b82835",
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
              "id": "158850a7-5301-440b-a922-ebe51bb467ff"
            }
          ]
        },
        {
          "id": "b111388a-ce6f-4db8-8185-9635df2f5a01",
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
              "id": "2bc3cac0-3bf3-49b7-a6d1-f6c3c0c6f91b"
            }
          ]
        },
        {
          "id": "4951d484-42e5-4b67-9dba-8c2211002abe",
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
              "id": "6b7c2fd5-4374-4f04-b4e9-19a8ea776006"
            }
          ]
        },
        {
          "id": "53821b84-9d8d-47cf-b4f3-f11dcc6f0652",
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
              "id": "501be9d3-ba77-470a-a049-7fabd68b849e"
            }
          ]
        },
        {
          "id": "a063b92f-e91f-44b4-bbf3-06b16e2833bb",
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
              "id": "71def0d8-64be-41c6-b0a6-394c8d84bc96"
            }
          ]
        }
      ]
    }
  ]
}