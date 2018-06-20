{
  "info": {
    "name": "App Veyor Get Environments",
    "_postman_id": "6015facd-5b7f-48ca-84f5-8d4c77a2e217",
    "description": "Get environments.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Environments",
      "item": [
        {
          "id": "b2885cba-30aa-4fd8-bc96-e9969919b821",
          "name": "getEnvironments",
          "request": {
            "url": "http://ci.appveyor.com/api/environments",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get environments."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3401d22d-2c92-48a5-b4e5-a06ffc85ae2d"
            }
          ]
        }
      ]
    }
  ]
}