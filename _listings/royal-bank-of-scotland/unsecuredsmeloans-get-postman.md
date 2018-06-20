{
  "info": {
    "name": "Royal Bank of Scotland Get Unsecured SME Loans",
    "_postman_id": "a1a1eb3e-197e-40c9-964d-491df47da44c",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple SME Unsecured Loan products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "910a2038-8acd-4ed2-8127-ece9fd25a715",
      "name": "getATMS",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/atms/",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can provide multiple ATMs."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "d348c5e6-9888-4a12-967c-0309f82bd145"
        }
      ]
    },
    {
      "id": "54571eef-31fe-42b1-833f-9cd807cb329e",
      "name": "getBranches",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/branches/",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple branches."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "a26cb1d6-e632-4a3f-b027-a4f6e2cf5c52"
        }
      ]
    },
    {
      "id": "37ae10c8-fad8-4610-a0e0-274dfa576a11",
      "name": "getCurrentPersonalAccounts",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/personal-current-accounts/",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple PCA products."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "3822801c-0767-4d00-a6c9-19b6e47b9aeb"
        }
      ]
    },
    {
      "id": "6d5a91ba-d916-4353-a9f3-c5642f8db99e",
      "name": "getCurentBusinessAccounts",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/business-current-accounts/",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple BCA products."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "12ebd6ba-f0ec-44f2-b80f-a248b7a24b54"
        }
      ]
    },
    {
      "id": "cd3d2434-5fee-477d-8aa4-788e3e409ec3",
      "name": "pathOperation",
      "request": {
        "url": "http://openapi.rbs.co.uk/open-banking/v2.1/unsecured-sme-loans/",
        "method": "GET",
        "body": {
          "mode": "raw"
        },
        "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple SME Unsecured Loan products."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "67df194e-6cfc-470c-b1f4-513f9c2b6e11"
        }
      ]
    }
  ]
}