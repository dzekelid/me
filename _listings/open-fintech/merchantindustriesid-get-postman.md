{
  "info": {
    "name": "Open FinTech Merchant industry by ID",
    "_postman_id": "d5282134-5d7c-4d8c-ad8b-b16465d4e3f4",
    "description": "Returns merchant industry with specific ID.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Merchant-industries",
      "item": [
        {
          "id": "1475bfa4-edc6-468c-b21f-9fcef6f2eba5",
          "name": "merchant_industries.get",
          "request": {
            "url": "http://api.openfintech.io/v1/merchant-industries?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all available merchant fields of activity."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4c02e9ad-5fa7-4865-931f-7b40368e90d5"
            }
          ]
        },
        {
          "id": "c927446d-06fb-4375-b647-412ed3748723",
          "name": "merchant_industries.id.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.openfintech.io",
              "path": [
                "v1",
                "merchant-industries/:id"
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
                  "id": "id",
                  "value": "id",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns merchant industry with specific ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59129cf4-fb76-4db8-ba5c-b3e15724f2c8"
            }
          ]
        }
      ]
    }
  ]
}