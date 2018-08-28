{
  "info": {
    "name": "AT&T API Get SMS Messaging Outbox Messageid",
    "_postman_id": "2788b1c6-1bb6-4d42-b7dd-3aef468a36b9",
    "description": "/sms/v3/messaging/outbox/{messageId}",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Devicecapabilities",
      "item": [
        {
          "id": "f725ff91-6d91-4662-bace-7e69f1be5944",
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
              "id": "a7012706-2db9-4701-8e64-9e9a301811b0"
            }
          ]
        }
      ]
    },
    {
      "name": "Messaging",
      "item": [
        {
          "id": "8a1a09cf-1d53-40b8-b9d5-e6af76768b13",
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
              "id": "7dc10a3e-bfcb-41e2-b478-6e8b1d5d6416"
            }
          ]
        },
        {
          "id": "c0dbfc1a-7243-4aee-835e-bb10acc3feea",
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
              "id": "1e35337b-eaaa-4bad-a62c-cb40b3d5adea"
            }
          ]
        }
      ]
    },
    {
      "name": "Smsmessaging",
      "item": [
        {
          "id": "76315da1-d6a5-4e13-bf22-f3e7ec8c9dea",
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
              "id": "2118b44c-33d3-4c97-a2b1-4175d6c30a7c"
            }
          ]
        },
        {
          "id": "2cf02dc7-2ae4-443f-acd1-3c802e8219f8",
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
              "id": "129ce90b-2718-4eed-8b41-77f856c30723"
            }
          ]
        },
        {
          "id": "bad98fc0-0ea8-4cd4-be02-963756aa6967",
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
              "id": "5f61d75b-2d5a-4e37-b23b-36bc4ecf71c3"
            }
          ]
        }
      ]
    },
    {
      "name": "Mms",
      "item": [
        {
          "id": "87f33bbe-87c7-4574-817d-4f8e0f44d242",
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
              "id": "a02a32ef-a8cc-41b1-8279-dceb84f0349e"
            }
          ]
        },
        {
          "id": "a6b47118-1920-4248-ae39-e43978f7cbc9",
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
              "id": "b075ea46-d69c-4c7a-83e6-7cdeaa39419d"
            }
          ]
        }
      ]
    },
    {
      "name": "MyMessages",
      "item": [
        {
          "id": "68460427-16cd-48d4-b6d3-8ecb1972d80c",
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
              "id": "83cd6aa8-9a71-4aaa-9c64-f216962163be"
            }
          ]
        },
        {
          "id": "b1597cb3-32fc-45a7-bd1a-49a5c018a43d",
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
              "id": "a04f9c63-a020-4b37-8777-79f36554e407"
            }
          ]
        },
        {
          "id": "9cbcda82-b1e4-4370-a70c-e235179ab8f3",
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
              "id": "3cadd573-5d9e-4893-a46a-3020ec7b9f06"
            }
          ]
        },
        {
          "id": "d349eb99-b1d9-46bc-8dd2-bd8f8ee8667a",
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
              "id": "09b010bb-b315-461f-a21d-0265be406c79"
            }
          ]
        },
        {
          "id": "16c86248-0088-458a-a39a-682d0f8b15fe",
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
              "id": "c0d83ba6-1355-4cc7-9d23-a87bd7a1cd95"
            }
          ]
        },
        {
          "id": "76ea0ab8-1fbb-4fc0-b96f-860c3c9a3cf8",
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
              "id": "a694b3f0-6ef8-4d18-a93c-bac146b02287"
            }
          ]
        },
        {
          "id": "831d342f-9b69-4509-ac36-2597b0700d59",
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
              "id": "fd2e95d6-994d-4886-8f6b-e2d05f267286"
            }
          ]
        },
        {
          "id": "b7860a4a-b722-4f7f-8fc1-3e17a5fd4d2d",
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
              "id": "58e77c40-374d-4de6-a073-91e48ca04995"
            }
          ]
        },
        {
          "id": "9e88f964-fcb5-42d6-956a-af4a94440a32",
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
              "id": "7624d489-780d-47e9-8656-8063914a4bba"
            }
          ]
        },
        {
          "id": "d2683366-bd5b-4ba9-a933-964a1f9e5db3",
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
              "id": "0849a643-7663-491f-bacd-e56b15e1d116"
            }
          ]
        }
      ]
    },
    {
      "name": "Rest",
      "item": [
        {
          "id": "28d36ea0-d8e9-4283-af25-047de7cb7e08",
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
              "id": "418663da-c276-439d-98bc-873e9ade25c7"
            }
          ]
        },
        {
          "id": "5e557eb9-dfd5-49eb-b7c8-1c3c7302d806",
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
              "id": "3515f38f-34c4-4427-a669-82f2c8adcfda"
            }
          ]
        }
      ]
    },
    {
      "name": "Sms",
      "item": [
        {
          "id": "47779533-ac0c-425f-b175-5657a3e45429",
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
              "id": "74cb261a-8ada-4196-8a5d-50cd461b19ef"
            }
          ]
        },
        {
          "id": "f398f8f4-3160-4493-9345-f241769f60a2",
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
              "id": "74b42b64-6071-4fe9-8e0f-e05678d850bc"
            }
          ]
        },
        {
          "id": "abc36ebc-9457-43d8-8e26-8c76d213384a",
          "name": "smsv3messagingoutboxmessageid",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.att.com",
              "path": [
                "sms/v3/messaging/outbox/:messageId"
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
            "description": "/sms/v3/messaging/outbox/{messageId}"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53db1d07-102d-453a-9d9f-c20a46f72f46"
            }
          ]
        }
      ]
    }
  ]
}