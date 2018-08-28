{
  "info": {
    "name": "Digital River Shopper API Get Shoppers Me Products",
    "_postman_id": "3694c040-4972-473c-91e6-789e603b077d",
    "description": "Get shoppers me products.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth20",
      "item": [
        {
          "id": "eef3d8b3-65a7-4183-92d7-fb64c756b7e4",
          "name": "getOauth20Authorize",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../oauth20/authorize",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get oauth20 authorize."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09668fb7-3622-4fec-8263-b0bd8f896fa9"
            }
          ]
        },
        {
          "id": "0268a64c-7fff-45b0-943f-42045772a1fe",
          "name": "postOauth20Token",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../oauth20/token",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post oauth20 token."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b797b59-92e4-402f-b089-b95e3af9695d"
            }
          ]
        }
      ]
    },
    {
      "name": "Shoppers",
      "item": [
        {
          "id": "4243f1f0-a245-45bb-bc2a-73723808cf38",
          "name": "postV1Shoppers",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a31ef7a1-5de6-4c2e-b19b-ae1fc2bca31c"
            }
          ]
        },
        {
          "id": "22f8aa61-f78d-4291-9200-98fe6d375436",
          "name": "getV1ShoppersApi",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers-api",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers api."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a9efd9ed-3581-4f98-985e-98551b848d71"
            }
          ]
        },
        {
          "id": "f38d320e-d89d-4403-a458-3dd6fb71ed76",
          "name": "getV1ShoppersMe",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ede0aabe-61c0-4a39-b146-e088a5505a0e"
            }
          ]
        },
        {
          "id": "e08bacd4-23c5-49ed-8081-65b0928dfaf2",
          "name": "postV1ShoppersMe",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "80189724-a6aa-4aa2-b08e-657dea092d5e"
            }
          ]
        },
        {
          "id": "c0978f18-785f-468a-88c7-a52676a76bd4",
          "name": "getV1ShoppersMeAccount",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/account",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "67f95ad5-6721-4eb4-bca1-5c550c942a9d"
            }
          ]
        },
        {
          "id": "f25f19aa-dbc6-477b-9d2e-3b88aefb5058",
          "name": "getV1ShoppersMeAddresses",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/addresses",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e14a481-4192-4a9a-9060-03d7c008c93d"
            }
          ]
        },
        {
          "id": "be3cd64e-3958-4842-b6c9-591f67f2b21d",
          "name": "getV1ShoppersMeAddresses",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/addresses/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me addresses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d2b5fea-9bae-4f56-9b35-b04016c02007"
            }
          ]
        },
        {
          "id": "6bad8335-35f2-4222-b424-1271c6733890",
          "name": "getV1ShoppersMeCartsActive",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bdd25474-57be-4a39-805b-f29655877d88"
            }
          ]
        },
        {
          "id": "d612ab25-9efb-4cae-b826-1cd60b71cc8e",
          "name": "postV1ShoppersMeCartsActive",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "abe3c568-0ea6-4176-8f47-41e014cc30b7"
            }
          ]
        },
        {
          "id": "28edcad1-d59a-42ad-b66f-47f4576f672c",
          "name": "postV1ShoppersMeCartsActiveApplyShippingOption",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/apply-shipping-option",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active apply shipping option."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9fa1e046-7693-4faa-acef-d827e8dfd35f"
            }
          ]
        },
        {
          "id": "1ff39a4c-09d9-4031-b180-a015c787795c",
          "name": "postV1ShoppersMeCartsActiveApplyShopper",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/apply-shopper",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active apply shopper."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "beab2427-81de-4062-94a3-3b840a00f6cd"
            }
          ]
        },
        {
          "id": "a100604b-84fe-4f81-b182-575360697c7e",
          "name": "getV1ShoppersMeCartsActiveBillingAddress",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/billing-address",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active billing address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c62ba2b7-c249-4ee7-b6c8-eda220e93057"
            }
          ]
        },
        {
          "id": "d0adb262-ff63-4bee-9678-71cb1f98a465",
          "name": "putV1ShoppersMeCartsActiveBillingAddress",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/billing-address",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Put shoppers me carts active billing address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c62b9b0d-b1ec-4d04-9062-a221b9c8093d"
            }
          ]
        },
        {
          "id": "dde14d7d-4bfe-4eff-805e-0ca7d27e48ed",
          "name": "getV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/line-items",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9a2ec403-8f74-47e2-9d61-771f107790c5"
            }
          ]
        },
        {
          "id": "903831b5-426d-42e4-b16b-9c85133d36a8",
          "name": "postV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/line-items",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05bc5b09-7cec-4ce3-b6c3-b2646ff01d6d"
            }
          ]
        },
        {
          "id": "4732e618-91a3-40d9-8f88-178ecde394eb",
          "name": "deleteV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/line-items",
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "414a06fd-de54-4ce5-a523-eb6e90418d7e"
            }
          ]
        },
        {
          "id": "8805d95b-2986-4dc9-bece-afa403c81c81",
          "name": "getV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/carts/active/line-items/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c6eab7cf-2621-463f-975e-200fe26b9afd"
            }
          ]
        },
        {
          "id": "8992119f-1e63-4fcb-8ec8-558d7c99413e",
          "name": "postV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/carts/active/line-items/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9dd5044f-5dd9-4c5f-9b76-d9d70ce6b724"
            }
          ]
        },
        {
          "id": "d4927011-3ac0-4917-8178-ef00032c06a5",
          "name": "deleteV1ShoppersMeCartsActiveLineItems",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/carts/active/line-items/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete shoppers me carts active line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04751da8-d686-42d8-8bdc-98545304dd95"
            }
          ]
        },
        {
          "id": "8a25a2ab-fa92-4f0d-9196-40e7982d2a99",
          "name": "getV1ShoppersMeCartsActivePointOfPromotionsOffers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/carts/active/point-of-promotions/:id/offers"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active point of promotions offers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6fddfd08-a007-4e5a-a38b-af1807655475"
            }
          ]
        },
        {
          "id": "ee77b200-f407-44b2-bc84-7d4d3ff19a88",
          "name": "getV1ShoppersMeCartsActiveShippingAddress",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/shipping-address",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active shipping address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af95567a-b1f7-4292-a2f2-65971fabb4a9"
            }
          ]
        },
        {
          "id": "20861a3d-27de-4d11-991f-202f00b53158",
          "name": "putV1ShoppersMeCartsActiveShippingAddress",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/shipping-address",
            "method": "PUT",
            "body": {
              "mode": "raw"
            },
            "description": "Put shoppers me carts active shipping address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8440b035-0632-4ca4-b7d4-1ef20bb4ed48"
            }
          ]
        },
        {
          "id": "d59c1a0e-b300-428e-a254-3beaaa72c434",
          "name": "getV1ShoppersMeCartsActiveShippingOptions",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/shipping-options",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active shipping options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b264f59-e517-476a-ab6e-253044da0644"
            }
          ]
        },
        {
          "id": "b555fd83-36d6-4cb0-ab0c-73cc215e0e3a",
          "name": "getV1ShoppersMeCartsActiveShippingOptions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/carts/active/shipping-options/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active shipping options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f070c01e-19a0-45e0-92e5-d186ebd93cee"
            }
          ]
        },
        {
          "id": "3139fee1-fd19-4b69-89d3-1791641a741f",
          "name": "postV1ShoppersMeCartsActiveSubmitCart",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/submit-cart",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active submit cart."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21918373-c9f8-49db-9da0-2a787cbb8882"
            }
          ]
        },
        {
          "id": "aed79950-abe2-4229-8181-ce7036de0020",
          "name": "getV1ShoppersMeCartsActiveWebCheckout",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/web-checkout",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me carts active web checkout."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cede6469-7d04-4526-aedf-9e5c19a13e20"
            }
          ]
        },
        {
          "id": "a3554bfd-5c32-4636-9113-8fd61a85610f",
          "name": "postV1ShoppersMeCartsActiveWebCheckout",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/carts/active/web-checkout",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me carts active web checkout."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60dc2e74-a225-409f-85d4-a2c2038f47c1"
            }
          ]
        },
        {
          "id": "f22497b4-4b80-4da9-bf3b-9c164b81e198",
          "name": "getV1ShoppersMeCategories",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/categories",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fc5a42b0-1b08-4ae5-a686-1a23fe3f10a8"
            }
          ]
        },
        {
          "id": "994b6f0c-f2a2-45e3-8a2f-7dd7ee33e595",
          "name": "getV1ShoppersMeCategories",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/categories/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me categories."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30d7e4f6-0051-428e-ac33-851a7abfc618"
            }
          ]
        },
        {
          "id": "26e6d265-b509-4f95-ad70-2bdfc784fd87",
          "name": "getV1ShoppersMeCategoriesProducts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/categories/:id/products"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me categories products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ec581420-8e4e-48c3-b5f6-ae4c9e5e7d35"
            }
          ]
        },
        {
          "id": "eb7da374-23b5-44a8-9158-74665be77871",
          "name": "getV1ShoppersMeOrders",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/orders",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb399323-16bd-4fa3-9d95-dde5a2a95d69"
            }
          ]
        },
        {
          "id": "c1420006-a556-4ef9-ad32-41a8bd8c4c94",
          "name": "postV1ShoppersMeOrders",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/orders",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "Post shoppers me orders."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a49197f-9a26-4346-aa53-fb789aaac03c"
            }
          ]
        },
        {
          "id": "bbc46ca3-6b50-4da3-ac80-0d4b182b2ea0",
          "name": "getV1ShoppersMeOrders",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/orders/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c16d00a7-124c-43e5-90d3-ddd1dfe65fa0"
            }
          ]
        },
        {
          "id": "c1a17cc6-adf1-45f5-b778-404fa9aa853e",
          "name": "getV1ShoppersMeOrdersBillingAddress",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/orders/:id/billing-address"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders billing address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4e1a0ebc-26aa-4123-a966-452d6fec29a2"
            }
          ]
        },
        {
          "id": "a30103d9-fb9a-42b1-b04a-b4f92e9540f9",
          "name": "getV1ShoppersMeOrdersLineItems",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/orders/:id/line-items"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders line items."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c2b24ac9-1c90-4272-aaf6-c25e6f6ee834"
            }
          ]
        },
        {
          "id": "b7802503-16a9-4b0c-ad45-f48df525680a",
          "name": "getV1ShoppersMeOrdersLineItemsLineitem",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/orders/:id/line-items/:lineItemId"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "lineItemId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders line items lineitemid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19f2e0d7-71e9-4b42-9172-b54cf615cfa1"
            }
          ]
        },
        {
          "id": "dab650ed-3241-458e-b8ef-8d152cab3700",
          "name": "getV1ShoppersMeOrdersShippingAddress",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/orders/:id/shipping-address"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me orders shipping address."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "217f96a0-9344-43d6-b671-c7d7e6539f19"
            }
          ]
        },
        {
          "id": "fcbaaaf6-5cf2-4e87-8c1d-20c1ee11f4ce",
          "name": "getV1ShoppersMePaymentOptions",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/payment-options",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me payment options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "baf3aedf-4d7a-46c5-a750-7eb6762fb578"
            }
          ]
        },
        {
          "id": "62ec0c60-c48e-4002-b556-1071d4a1f6a1",
          "name": "getV1ShoppersMePaymentOptions",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/payment-options/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me payment options."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f450f6a9-7609-466b-b2d8-253bf46ebf2f"
            }
          ]
        },
        {
          "id": "4b641854-efce-459d-a75e-132b29c39a6d",
          "name": "getV1ShoppersMePointOfPromotionsOffers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/point-of-promotions/:id/offers"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me point of promotions offers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3bcf194b-a673-459c-b946-79b76fe5df03"
            }
          ]
        },
        {
          "id": "b05dfc0a-8705-4109-9b9c-5c4412f23371",
          "name": "getV1ShoppersMePointOfPromotionsOffersOffer",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/point-of-promotions/:id/offers/:offerId"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "offerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me point of promotions offers offerid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "72b38521-e046-48fd-9f70-ec4905064af7"
            }
          ]
        },
        {
          "id": "499ddcc5-2126-415c-8e53-1c15948473a0",
          "name": "getV1ShoppersMePointOfPromotionsOffersOfferProductOffers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/point-of-promotions/:id/offers/:offerId/product-offers"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "offerId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me point of promotions offers offerid product offers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "631004ed-434e-42ee-abf9-076b84744957"
            }
          ]
        },
        {
          "id": "56818e1a-f87d-4883-8d93-91490fbfaa7b",
          "name": "getV1ShoppersMePointOfPromotionsOffersOfferProductOffersProduct",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/point-of-promotions/:id/offers/:offerId/product-offers/:productId"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "offerId",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "productId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me point of promotions offers offerid product offers productid."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0eda08a8-c84c-43aa-8794-46e2a06f2c5c"
            }
          ]
        },
        {
          "id": "e4b5536d-24f0-4f31-93ab-8dfe59f7ea82",
          "name": "getV1ShoppersMeProductSearch",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/product-search",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me product search."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31987927-bab7-44a1-ba85-176bb98e95e0"
            }
          ]
        },
        {
          "id": "cc716dea-06ab-4481-9e4f-54296297d445",
          "name": "getV1ShoppersMeProducts",
          "request": {
            "url": "http://store.digitalriver.com/store/TODO Add Value for parameter.../v1/shoppers/me/products",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "72300e80-ad22-4c4d-88e6-d9f5ec19d88d"
            }
          ]
        },
        {
          "id": "a611e001-ccc7-4c57-94b5-4336aa8ecf02",
          "name": "getV1ShoppersMeProducts",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/products/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me products."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ca502b8-0ec3-4590-bdee-47f8e9e3ada3"
            }
          ]
        }
      ]
    }
  ]
}