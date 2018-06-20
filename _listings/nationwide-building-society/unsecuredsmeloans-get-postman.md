{
  "info": {
    "name": "Nationwide Building Society Get Unsecured SME Loans",
    "_postman_id": "199369a8-affa-4e32-87fb-5f6931310bb6",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple SME Unsecured Loan products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "unsecured",
      "item": [
        {
          "id": "4bd531fe-d7e7-479d-84f2-6af6535597e3",
          "name": "pathOperation",
          "request": {
            "url": "http://openapi.nationwide.co.uk/open-banking/v2.1/unsecured-sme-loans/",
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
              "id": "45cfb3e6-3b75-4417-ad7a-d520607228b8"
            }
          ]
        }
      ]
    }
  ]
}