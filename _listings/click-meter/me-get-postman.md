{
  "info": {
    "name": "Click Meter Retrieve current account data",
    "_postman_id": "a53edf1e-1a61-4b7a-8d84-517a6ba7815b",
    "description": "Retrieve current account data.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Me",
      "item": [
        {
          "id": "41b439a2-1391-47fa-a5a8-8df42364e2f0",
          "name": "getMe",
          "request": {
            "url": "http://apiv2.clickmeter.com:80/me",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve current account data."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa30e570-611d-4ddf-acbf-4924e4e8d786"
            }
          ]
        }
      ]
    }
  ]
}