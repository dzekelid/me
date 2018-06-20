{
  "info": {
    "name": "Santander Bank Get Unsecured SME Loans",
    "_postman_id": "147bf9a9-ef68-4f95-9fa4-fe4cd1156d52",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple SME Unsecured Loan products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "unsecured",
      "item": [
        {
          "id": "f6875e7a-c8f7-4258-bab6-105a43348c89",
          "name": "pathOperation",
          "request": {
            "url": "http://openapi.santander.co.uk/open-banking/v2.1/unsecured-sme-loans/",
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
              "id": "fe1bff2f-a772-4f13-9142-955c66143c10"
            }
          ]
        }
      ]
    }
  ]
}