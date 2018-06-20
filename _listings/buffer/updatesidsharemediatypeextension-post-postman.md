{
  "info": {
    "name": "Buffer Post Updates Share Mediatypeextension",
    "_postman_id": "a74a6b3d-1e9c-449a-bdb0-679e38394e14",
    "description": "Immediately shares a single pending update and recalculates times for updates remaining in the queue.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Info",
      "item": [
        {
          "id": "d74722aa-a609-400d-a49e-2a2788aec1c8",
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
              "id": "3b66b178-5c18-4627-963c-0cff23261b7b"
            }
          ]
        }
      ]
    },
    {
      "name": "Links",
      "item": [
        {
          "id": "e2d203dc-b4c2-4854-9cf5-14387d61ddf3",
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
              "id": "af5cc2bb-5167-4dee-bdc8-1e5e2f854ed1"
            }
          ]
        }
      ]
    },
    {
      "name": "Profiles",
      "item": [
        {
          "id": "fdb7231e-f014-46d3-b1af-f77dcb2deffe",
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
              "id": "91edb0a7-26ca-4cd4-9364-3fe8a586b9b4"
            }
          ]
        },
        {
          "id": "78a3ee37-7573-49fb-9594-706d4eb78ff1",
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
              "id": "a201a8c7-18c6-4d98-8c97-b79300ea4d4a"
            }
          ]
        },
        {
          "id": "c09101a7-90e6-4c9f-95d7-55faf08a846d",
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
              "id": "bfe5c3e1-219c-4d4d-83b4-c34399787877"
            }
          ]
        },
        {
          "id": "c7cd3e68-e680-42ab-8d20-b1af070909cd",
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
              "id": "50482b14-221e-4082-bc28-64ff9b0f77ac"
            }
          ]
        },
        {
          "id": "3bbff849-0c42-40d4-8d0f-6cbc759b1be7",
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
              "id": "a3a3450c-42c1-45cd-bb86-99afdfe72a34"
            }
          ]
        },
        {
          "id": "29d517cb-3045-4741-ac70-285b336cef02",
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
              "id": "067bee2f-59c6-4e1c-bf31-76ba958a31a5"
            }
          ]
        },
        {
          "id": "bd96a2aa-b91f-4b4e-bf31-701ff730297a",
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
              "id": "071fb12f-f961-4abd-8b97-16f8fe7f99e5"
            }
          ]
        }
      ]
    },
    {
      "name": "ProfilesmediaTypeExtension",
      "item": [
        {
          "id": "eb41f8cc-86a4-424b-b46a-0b2c600f1fc0",
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
              "id": "2967c3a5-a13e-498a-b100-e57dfc2bc35d"
            }
          ]
        }
      ]
    },
    {
      "name": "Updates",
      "item": [
        {
          "id": "a446cd6a-6863-4599-9ab1-c8f0f55fd80c",
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
              "id": "af042408-4d1a-451b-863a-6b0b259bd0d7"
            }
          ]
        },
        {
          "id": "980fb488-7d04-47fa-86f5-96bd407a1587",
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
              "id": "3200d620-e706-4232-b5e5-1b0cc4388fbf"
            }
          ]
        },
        {
          "id": "cfb2bfb3-cd76-47ac-a72b-feffbda5f634",
          "name": "returns-the-detailed-information-on-individual-interactions-with-the-social-media-update-such-as-fav",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "updates/:id/interactions:mediaTypeExtension"
              ],
              "query": [
                {
                  "key": "count",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "event",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "page",
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
            "description": "Returns the detailed information on individual interactions with the social media update such as favorites, retweets and likes."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8857318f-ea64-4309-9fcb-12ca991adb8c"
            }
          ]
        },
        {
          "id": "8deeefaf-9d3d-4dfc-a14c-d95c3ab511a4",
          "name": "move-an-existing-status-update-to-the-top-of-the-queue-and-recalculate-times-for-all-updates-in-the-",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "updates/:id/move_to_top:mediaTypeExtension"
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
            "description": "Move an existing status update to the top of the queue and recalculate times for all updates in the queue. Returns the update with its new posting time."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1b7bec5-1622-4e48-bd71-a4335b3e13bd"
            }
          ]
        },
        {
          "id": "a8657d66-d2f9-41c9-b0ca-b2fed4df3375",
          "name": "immediately-shares-a-single-pending-update-and-recalculates-times-for-updates-remaining-in-the-queue",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.bufferapp.com",
              "path": [
                "1",
                "updates/:id/share:mediaTypeExtension"
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
            "description": "Immediately shares a single pending update and recalculates times for updates remaining in the queue."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a1a3b7f-dcd7-4082-8d47-255f7291d538"
            }
          ]
        }
      ]
    }
  ]
}