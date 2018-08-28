{
  "info": {
    "name": "HSBC Get Unsecured SME Loans",
    "_postman_id": "27e81958-be4b-4fa1-bbfb-e564d3253e39",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple SME Unsecured Loan products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "unsecured",
      "item": [
        {
          "id": "f407868e-fef0-473d-8ef4-865602dfdd09",
          "name": "pathOperation",
          "request": {
            "url": "http://api.hsbc.com/open-banking/v2.1/unsecured-sme-loans/",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "This endpoint can contain multiple brands owned by a particular banking group"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ea023917-a2b7-491c-9f18-4c6a507c9aeb"
            }
          ]
        }
      ]
    }
  ]
}