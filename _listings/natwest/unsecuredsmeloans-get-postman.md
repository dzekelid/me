{
  "info": {
    "name": "NatWest Get Unsecured SME Loans",
    "_postman_id": "b4c5dfc4-e2f5-46f7-92a0-e33928ddb35a",
    "description": "This endpoint can contain multiple brands owned by a particular banking group. Each brand can own multiple SME Unsecured Loan products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "21f09277-4fa4-40cb-b624-fe1b265f9d78",
      "name": "getATMS",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/atms/",
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
          "id": "de36f089-82f9-4b49-801b-3aaca4e99164"
        }
      ]
    },
    {
      "id": "fd8f2290-6f24-4552-b40a-82c357f3edd9",
      "name": "getBranches",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/branches/",
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
          "id": "7409bc03-070b-4c1d-8e17-668564072dd3"
        }
      ]
    },
    {
      "id": "c6e5f078-18ae-429d-a5a3-121c94db4bd2",
      "name": "getCurrentPersonalAccounts",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/personal-current-accounts/",
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
          "id": "6461a7aa-13ec-4730-b1ca-7fbae8acd58e"
        }
      ]
    },
    {
      "id": "fdb5266c-19c1-49f2-8c28-5c8f4a213d67",
      "name": "getCurentBusinessAccounts",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/business-current-accounts/",
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
          "id": "12042a9f-8b19-4414-8ff2-408b05b30224"
        }
      ]
    },
    {
      "id": "d72e8cce-35fc-4379-986f-780c4fd73e8f",
      "name": "pathOperation",
      "request": {
        "url": "http://openapi.natwest.com/open-banking/v2.1/unsecured-sme-loans/",
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
          "id": "c6930e9a-b3f3-4a8c-b19e-158a6e42272a"
        }
      ]
    }
  ]
}