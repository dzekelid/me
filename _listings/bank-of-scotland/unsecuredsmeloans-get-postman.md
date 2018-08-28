{
  "info": {
    "name": "Bank of Scotland Get Unsecured SME Loans",
    "_postman_id": "9dc0e0ce-b545-4573-b0fb-132315256ba5",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple SME Unsecured Loan products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "unsecured",
      "item": [
        {
          "id": "d2eb2eb3-7928-4efd-96bf-4612caf226ed",
          "name": "pathOperation",
          "request": {
            "url": "http://api.bankofscotland.co.uk/open-banking/v2.1/unsecured-sme-loans/",
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
              "id": "6e2e1447-bb75-4130-ad5e-67cab7095f79"
            }
          ]
        }
      ]
    }
  ]
}