{
  "info": {
    "name": "Buffer Post Updates Destroy Mediatypeextension",
    "_postman_id": "f12b4c3d-34b3-4e2b-ab01-5a84f03c9a1a",
    "description": "Permanently delete an existing status update.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Info",
      "item": [
        {
          "id": "10cc6850-04c5-4b5b-bfdd-0957190b71ac",
          "name": "returns-an-object-with-the-current-configuration-that-buffer-is-using-including-supported-services-t",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "info/configuration:mediaTypeExtension"
              ],
              "variable": [
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns an object with the current configuration that Buffer is using, including supported services, their icons and the varying limits of character and schedules."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2e91af7-5617-434f-b78e-08cf23d7c34d"
            }
          ]
        }
      ]
    },
    {
      "name": "Links",
      "item": [
        {
          "id": "d1d15d89-cda0-445b-b2c6-2e7d91ed6a96",
          "name": "returns-an-object-with-a-the-numbers-of-shares-a-link-has-had-using-buffer-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "links/shares:mediaTypeExtension"
              ],
              "query": [
                {
                  "key": "url",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns an object with a the numbers of shares a link has had using Buffer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95fac160-db5e-42f1-bb96-4ec117a54c6e"
            }
          ]
        }
      ]
    },
    {
      "name": "Profiles",
      "item": [
        {
          "id": "e021a227-621b-4209-8644-946580184a7c",
          "name": "set-the-posting-schedules-for-the-specified-social-media-profile-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "profiles/:id/schedules/update:mediaTypeExtension"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post Profiles Schedules Update Mediatypeextension"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "850344ca-2d7b-4828-9d6c-d5095a8bc529"
            }
          ]
        },
        {
          "id": "fe9a7f7a-8104-4df7-abbb-99ac66641b06",
          "name": "returns-details-of-the-posting-schedules-associated-with-a-social-media-profile-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "profiles/:id/schedules:mediaTypeExtension"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns details of the posting schedules associated with a social media profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e4a2a215-2470-436d-b574-06bbb6b9a2e5"
            }
          ]
        },
        {
          "id": "56cb86da-fab7-4fb0-aadb-b869e9cfb23d",
          "name": "returns-an-array-of-updates-that-are-currently-in-the-buffer-for-an-individual-social-media-profile-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "profiles/:id/updates/pending:mediaTypeExtension"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "since",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "utc",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Profiles Updates Pending Mediatypeextension"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5e2e60dc-73e6-492e-baad-61fa1f407092"
            }
          ]
        },
        {
          "id": "c9b3cda2-5a3c-4161-9b40-6e4679167abc",
          "name": "edit-the-order-at-which-statuses-for-the-specified-social-media-profile-will-be-sent-out-of-the-buff",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "profiles/:id/updates/reorder:mediaTypeExtension"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Edit the order at which statuses for the specified social media profile will be sent out of the buffer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce015f16-0232-4080-a3da-ab0a1478db1c"
            }
          ]
        },
        {
          "id": "9c0696b8-907b-4c1f-9660-9465b7c7aede",
          "name": "returns-an-array-of-updates-that-have-been-sent-from-the-buffer-for-an-individual-social-media-profi",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "profiles/:id/updates/sent:mediaTypeExtension"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "since",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "utc",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns an array of updates that have been sent from the buffer for an individual social media profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5891d64d-46f6-4873-be1f-a3aaad00809f"
            }
          ]
        },
        {
          "id": "78f29553-9149-4520-b43f-32152a34c0b7",
          "name": "randomize-the-order-at-which-statuses-for-the-specified-social-media-profile-will-be-sent-out-of-the",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "profiles/:id/updates/shuffle:mediaTypeExtension"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Randomize the order at which statuses for the specified social media profile will be sent out of the buffer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c8fa86e4-4f7d-4727-9b96-0383c6ff112f"
            }
          ]
        },
        {
          "id": "03dedc5a-b46f-4917-8492-024f447f894b",
          "name": "returns-details-of-the-single-specified-social-media-profile-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "profiles/:id:mediaTypeExtension"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns details of the single specified social media profile."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "031bcff4-a55e-49f0-92e6-b7bbc676c577"
            }
          ]
        }
      ]
    },
    {
      "name": "ProfilesmediaTypeExtension",
      "item": [
        {
          "id": "9900dd9f-b0e2-4420-849b-b70a3acaa15e",
          "name": "returns-an-array-of-social-media-profiles-connected-to-a-users-account-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "profiles:mediaTypeExtension"
              ],
              "variable": [
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns an array of social media profiles connected to a users account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca1b1e2e-ab51-4427-9671-635f39d69661"
            }
          ]
        }
      ]
    },
    {
      "name": "Updates",
      "item": [
        {
          "id": "e1506a69-eff5-4e84-9eeb-e924126cdcd0",
          "name": "create-one-or-more-new-status-updates-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "updates/create:mediaTypeExtension"
              ],
              "variable": [
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Create one or more new status updates."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e2cac620-7154-400f-a959-55522dfa1192"
            }
          ]
        },
        {
          "id": "025b48cd-4de5-41e0-b841-9b7020e87cae",
          "name": "permanently-delete-an-existing-status-update-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "updates/:id/destroy:mediaTypeExtension"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "mediaTypeExtension",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Permanently delete an existing status update."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5da30356-da6b-489c-95e8-ae1089cb5a6a"
            }
          ]
        }
      ]
    }
  ]
}