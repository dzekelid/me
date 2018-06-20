{
  "info": {
    "name": "AT&T API Post SMS Messaging Outbox",
    "_postman_id": "0df396ad-08aa-4dea-9a94-400aabbe5787",
    "description": "/sms/v3/messaging/outbox",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devicecapabilities",
      "item": [
        {
          "id": "170c8ad6-64c8-491f-9481-0f68cd60f09b",
          "name": "1devicecapabilitiesacrauthorizationcapabilities",
          "request": {
            "url": "http://api.att.com/1/devicecapabilities/acr:authorization/capabilities",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/1/devicecapabilities/acr:authorization/capabilities"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "29bb18ed-8700-4970-ac5d-347357bdb9c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Messaging",
      "item": [
        {
          "id": "b77bc73f-ab1a-4cec-8b94-33dc23908db9",
          "name": "3messagingoutboundsenderaddressrequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/messaging/outbound/:senderAddress/requests"
              ],
              "variable": [
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/3/messaging/outbound/{senderAddress}/requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a3ab7c16-ede9-45f6-be30-54dc301f8294"
            }
          ]
        },
        {
          "id": "d1587399-23ea-4975-9f5d-0f838e07371b",
          "name": "3messagingoutboundsenderaddressrequestiddeliveryinfos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/messaging/outbound/:senderAddress/:requestId/deliveryInfos"
              ],
              "variable": [
                {
                  "id": "requestId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/messaging/outbound/{senderAddress}/{requestId}/deliveryInfos"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d13da740-bb28-41e9-addb-673496129e7a"
            }
          ]
        }
      ]
    },
    {
      "name": "Smsmessaging",
      "item": [
        {
          "id": "a4c0b6e4-a450-410a-9f5e-3148b6dbc2ec",
          "name": "3smsmessaginginboundregistrationsregistrationidmessages",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/inbound/registrations/:registrationId/messages"
              ],
              "variable": [
                {
                  "id": "registrationId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/inbound/registrations/{registrationId}/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "abced7d3-39ce-4818-8431-e65cae93a895"
            }
          ]
        },
        {
          "id": "8b8a66b0-b1ec-487b-9a30-eed1b0d57bf5",
          "name": "3smsmessagingoutboundrequestssenderaddressrequestiddeliveryinfos",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/outbound/requests/:senderAddress/:requestId/deliveryInfos"
              ],
              "variable": [
                {
                  "id": "requestId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/outbound/requests/{senderAddress}/{requestId}/deliveryInfos"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2efa3898-1d4b-4671-bae1-3a35205ed017"
            }
          ]
        },
        {
          "id": "031c324d-182e-4a8f-bc1c-5cf91500fc77",
          "name": "3smsmessagingoutboundsenderaddressrequests",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "3/smsmessaging/outbound/:senderAddress/requests"
              ],
              "variable": [
                {
                  "id": "senderAddress",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/3/smsmessaging/outbound/{senderAddress}/requests"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11b5fd7a-e137-4d59-9e94-7e178426ce7b"
            }
          ]
        }
      ]
    },
    {
      "name": "Mms",
      "item": [
        {
          "id": "955f75f5-d903-4e45-b316-9dadd5715ad3",
          "name": "mmsv3messagingoutbox",
          "request": {
            "url": "http://api.att.com/mms/v3/messaging/outbox",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/mms/v3/messaging/outbox"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d9e9e60b-ea1a-47c0-9011-5f09350af1a0"
            }
          ]
        },
        {
          "id": "c4858add-ccd1-49e3-b841-bdde7fa4b29d",
          "name": "mmsv3messagingoutboxmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "mms/v3/messaging/outbox/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/mms/v3/messaging/outbox/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "483235a1-1358-4164-8045-affb56a5a106"
            }
          ]
        }
      ]
    },
    {
      "name": "MyMessages",
      "item": [
        {
          "id": "921f0adf-b85f-47bc-b959-a432e1741f34",
          "name": "mymessagesv2delta",
          "request": {
            "url": "http://api.att.com/myMessages/v2/delta",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/delta"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa3eed7f-959e-4e80-a84d-355ba0eb5123"
            }
          ]
        },
        {
          "id": "24b91b0c-749f-4c27-8abb-02762af78832",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "acf7326a-b095-4397-8980-45d063f73292"
            }
          ]
        },
        {
          "id": "ae9bc079-e169-4967-ac16-73f45b7fd851",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1a1d57f7-ec8b-4478-81f7-b1618f3bf60e"
            }
          ]
        },
        {
          "id": "d2f374c7-f7a1-4dce-868d-1e6ea6a663ee",
          "name": "mymessagesv2messages",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b48a572f-706b-4562-9a45-059dc1047c03"
            }
          ]
        },
        {
          "id": "76a85c62-3819-49c8-8d20-f72c51c85497",
          "name": "mymessagesv2messagesindex",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages/index",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/index"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "81cafbf1-5d2a-4bed-a72b-ce351cb239a8"
            }
          ]
        },
        {
          "id": "42684968-e512-4022-bbd5-75fbc0575364",
          "name": "mymessagesv2messagesindexinfo",
          "request": {
            "url": "http://api.att.com/myMessages/v2/messages/index/info",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/index/info"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8c6f4ac8-1143-40e9-a38a-3fbd49f9c1ff"
            }
          ]
        },
        {
          "id": "6705b3d1-fc57-440e-b1b2-57f9fcc90f76",
          "name": "mymessagesv2messagesmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "myMessages/v2/messages/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53db9b53-3d2c-4091-bfd2-dee8d7485fc3"
            }
          ]
        },
        {
          "id": "36af763f-742d-42f8-a05f-317d58b0198f",
          "name": "mymessagesv2messagesmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "myMessages/v2/messages/:messageId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd24c4ba-845f-4a83-98c0-c894de44339f"
            }
          ]
        },
        {
          "id": "2e705ead-d84a-4a7b-9942-9a5f443fd0a7",
          "name": "mymessagesv2messagesmessageidpartspartid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "myMessages/v2/messages/:messageId/parts/:partId"
              ],
              "variable": [
                {
                  "id": "messageId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "partId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/messages/{messageId}/parts/{partId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "011d42bd-b047-4c35-a804-07810431b5fd"
            }
          ]
        },
        {
          "id": "a5e78f5e-3c3d-4f7e-8811-18a48352f85f",
          "name": "mymessagesv2notificationconnectiondetails",
          "request": {
            "url": "http://api.att.com/myMessages/v2/notificationConnectionDetails",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/myMessages/v2/notificationConnectionDetails"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2307a10-61a4-4b3e-84fb-07a1edd4233d"
            }
          ]
        }
      ]
    },
    {
      "name": "Rest",
      "item": [
        {
          "id": "f452ebbd-4978-4098-ae97-716dcb044297",
          "name": "rest1ads",
          "request": {
            "url": "http://api.att.com/rest/1/ads",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/rest/1/ads"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc777de2-5de8-49c4-98cd-b098303a621e"
            }
          ]
        },
        {
          "id": "63b745de-80f4-4a0a-91c5-0aec7ae567d8",
          "name": "rest2devicesinfo",
          "request": {
            "url": "http://api.att.com/rest/2/Devices/Info",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/rest/2/Devices/Info"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "626ceb48-a44a-4815-8b83-3162b370283b"
            }
          ]
        }
      ]
    },
    {
      "name": "Sms",
      "item": [
        {
          "id": "e163e634-88d8-4fdf-8a00-f85ae39a0aea",
          "name": "smsv3messaginginboxregistrationid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "sms/v3/messaging/inbox/:RegistrationID"
              ],
              "variable": [
                {
                  "id": "RegistrationID",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "/sms/v3/messaging/inbox/{RegistrationID}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9013ac3d-913d-4aff-a51a-b429200bcb25"
            }
          ]
        },
        {
          "id": "01167dca-fa8e-4728-8f4c-617adb399a78",
          "name": "smsv3messagingoutbox",
          "request": {
            "url": "http://api.att.com/sms/v3/messaging/outbox",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "/sms/v3/messaging/outbox"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "66b3e2c8-18cf-4582-9c40-8b2950c0b842"
            }
          ]
        }
      ]
    }
  ]
}