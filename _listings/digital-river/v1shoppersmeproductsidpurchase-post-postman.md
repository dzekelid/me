{
  "info": {
    "name": "Digital River Shopper API Post Shoppers Me Products Purchase",
    "_postman_id": "8ca4d5bb-dada-45bd-bc3b-a7ce9638e9bd",
    "description": "Post shoppers me products purchase.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Oauth20",
      "item": [
        {
          "id": "16e03d38-3953-468e-ab2e-c28f3dde0f55",
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
              "id": "13a27dfe-ff16-45e9-b587-8538bf27064c"
            }
          ]
        },
        {
          "id": "66193b97-0588-4a36-a65c-27c0d55bd541",
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
              "id": "80988126-3035-44a8-84bf-5963fcaec117"
            }
          ]
        }
      ]
    },
    {
      "name": "Shoppers",
      "item": [
        {
          "id": "bed493d2-5347-4bf4-9059-a324399fea3a",
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
              "id": "547dc0f7-b9ae-44b5-9b0e-eaa9506ebc82"
            }
          ]
        },
        {
          "id": "3ede23c1-6162-4bd9-98e7-7cbc3111f3e9",
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
              "id": "ff127d4a-e002-4713-be24-5f6a2d658223"
            }
          ]
        },
        {
          "id": "3e53089f-591c-448b-9928-5ad8f6cd32c3",
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
              "id": "38cc92e5-5ee6-4f22-8933-a21d842f3921"
            }
          ]
        },
        {
          "id": "efa73429-fb77-43c4-b6f2-c66a02511c71",
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
              "id": "4934bf33-e23f-4d65-94cc-07ff7effe6b7"
            }
          ]
        },
        {
          "id": "1623b4a6-f89a-43dc-8781-00e602947d2c",
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
              "id": "e600c5b3-96a5-4392-ad64-c143f4e8aac8"
            }
          ]
        },
        {
          "id": "47e1334a-53fe-447e-9102-fdb54b643e7e",
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
              "id": "5f4a5e08-c8e8-4e1e-a170-f9d134cecbeb"
            }
          ]
        },
        {
          "id": "64e1eb70-f94e-43ef-935a-a93561b8fb0c",
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
              "id": "1500f03a-9343-4b88-bef6-7057f64ad90a"
            }
          ]
        },
        {
          "id": "4bc79a5b-b240-4210-8506-5895ecad3918",
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
              "id": "1a20a8f3-072d-4fd9-9a45-cce5da87b88e"
            }
          ]
        },
        {
          "id": "e9a6a23e-032b-4256-9d5b-cc1fcbc5c2f1",
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
              "id": "8d33ecc2-b1ed-4051-beb8-6846b6d92cc5"
            }
          ]
        },
        {
          "id": "0befce7a-e394-40d7-8b7f-e3f2c13c3a24",
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
              "id": "f347f535-a3f7-435f-aae8-5bfde6cde4ff"
            }
          ]
        },
        {
          "id": "c2132e67-8377-4f95-86eb-e5b28e5e8512",
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
              "id": "98246ae6-8016-444a-92d0-2a5fa54e075a"
            }
          ]
        },
        {
          "id": "d8730d55-f46e-4f36-8db6-ef4d796d32b5",
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
              "id": "ced99474-bbf9-481c-9753-5a92a3b39d3f"
            }
          ]
        },
        {
          "id": "967c2dff-2dbb-4b54-92a2-91f8a2e186a7",
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
              "id": "e61e5633-409f-4ea6-a874-dee124c71a52"
            }
          ]
        },
        {
          "id": "bdd5b0ad-0fa1-4e7e-80dd-55974a6fcaa5",
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
              "id": "e36e0729-223a-4910-9aff-c1cc5de83e63"
            }
          ]
        },
        {
          "id": "e7375d8b-4b7f-405a-af09-0bdf99eb137e",
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
              "id": "787111ce-3299-4a4b-b4b2-7219853ec4e6"
            }
          ]
        },
        {
          "id": "175973eb-20fe-437e-a716-c8bf98ca32bf",
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
              "id": "c4f7f84b-9ad9-49e4-aa94-ebbe02c7ec2d"
            }
          ]
        },
        {
          "id": "5ff68ab9-9b2d-4686-af2f-ed720aa86702",
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
              "id": "e9669093-ec07-4963-8e36-90624cc04722"
            }
          ]
        },
        {
          "id": "43fa8529-3d07-4348-9fcf-4ad60ce421ca",
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
              "id": "2c087012-55e8-404f-bf8b-590a9198de81"
            }
          ]
        },
        {
          "id": "ca2bc786-ba1b-425c-b442-57c2ac115219",
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
              "id": "4ab9a250-b478-4110-9a73-42df8c3a21e2"
            }
          ]
        },
        {
          "id": "dbe7dc28-b71a-431b-b90f-d80df111366e",
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
              "id": "39240093-d60d-4423-88c3-064b70dcfe43"
            }
          ]
        },
        {
          "id": "86424de9-a03c-49aa-bd91-46c4e7847071",
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
              "id": "ade5085f-4d88-480d-93aa-35c5ec1296fd"
            }
          ]
        },
        {
          "id": "09731a4c-a6cd-4835-8a10-918b58378587",
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
              "id": "40ed5bf4-8eab-47da-8006-fa0e26fcaa3f"
            }
          ]
        },
        {
          "id": "2e11e34a-d7d4-47d5-98e7-16a48d8a574f",
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
              "id": "f69bf2e9-6cc1-4464-b98f-e7c6c59f44ef"
            }
          ]
        },
        {
          "id": "8696d90d-07d2-4fff-bbe1-3362ee10204a",
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
              "id": "4eeebd5a-32d0-483f-91e8-ea355f02064c"
            }
          ]
        },
        {
          "id": "758c6016-47fe-455e-bf60-502f53ceb02f",
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
              "id": "50766254-cafd-4593-94e3-5cd5479fa459"
            }
          ]
        },
        {
          "id": "947bafa8-2a05-413f-8e91-19e7067426bc",
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
              "id": "467d9672-5675-4eb2-af37-45453a9f9ba9"
            }
          ]
        },
        {
          "id": "83725d7c-2256-4e3d-a51e-fc74943c879e",
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
              "id": "74ea2f84-d426-4532-ac79-ebb53e9da715"
            }
          ]
        },
        {
          "id": "2eb51029-5bb9-46e7-a523-c905c5ae62f0",
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
              "id": "7fcbdcc6-af55-4a0b-9696-8857108291d3"
            }
          ]
        },
        {
          "id": "637a1121-dc21-41e4-aabc-d33c726bd683",
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
              "id": "da2bc8ab-64c5-4249-9a26-3e4db05e6eea"
            }
          ]
        },
        {
          "id": "289d4208-b041-48ab-b05a-adb9b0660e40",
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
              "id": "4b827d2e-5de9-4235-b00b-a282fc191360"
            }
          ]
        },
        {
          "id": "173f1a03-7e2e-4429-9027-18ef817e430c",
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
              "id": "3f493ce1-e3df-4d9c-8dab-6629ba05c584"
            }
          ]
        },
        {
          "id": "57e63846-1a5e-4f8e-8e42-3872399baba0",
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
              "id": "37cb543a-5b32-472a-a625-38b36200f62f"
            }
          ]
        },
        {
          "id": "fcbfaa76-149e-4122-95c4-bcdc2544bcd7",
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
              "id": "6e78b0a8-912f-47dd-b9e9-95eb4c13a305"
            }
          ]
        },
        {
          "id": "4a43d398-e046-4320-aff7-0a09ad871a7b",
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
              "id": "33231708-1435-4ef9-be11-ef3fddcd1e9c"
            }
          ]
        },
        {
          "id": "1df500c8-4fd3-41b8-a864-5adc42c37bbb",
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
              "id": "462f1770-ad78-4055-9cc7-2c6e7f804c7f"
            }
          ]
        },
        {
          "id": "24b94a85-9657-46cd-be1a-d415933d4236",
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
              "id": "9ca5f628-f697-471f-bb46-45b411465258"
            }
          ]
        },
        {
          "id": "1b715686-1a6a-4911-97f7-8789dbc6e01c",
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
              "id": "5e59a13c-f53a-48df-97ef-9ab430d2eb00"
            }
          ]
        },
        {
          "id": "ff10e919-2cd6-4318-a141-a58f39f1aa15",
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
              "id": "d20415ab-a390-44e0-8668-e89942d02c48"
            }
          ]
        },
        {
          "id": "bb02b508-06b6-4be8-8f24-00f51a173f1b",
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
              "id": "16d92c6f-aa9e-4128-95f8-17b5aee1a30d"
            }
          ]
        },
        {
          "id": "3eb73718-f86c-4a04-ab66-1c8e959859b0",
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
              "id": "2b6228db-80ed-4716-806a-b2817e8ab77a"
            }
          ]
        },
        {
          "id": "814e2567-1380-4fe0-8d61-d5b60277c201",
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
              "id": "610cee23-7bf4-4177-b51d-2b3191ea449c"
            }
          ]
        },
        {
          "id": "466106ff-b40d-4012-8732-481ccbdb582b",
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
              "id": "b5a3642a-b4eb-4c80-9d5a-4b010e55f60f"
            }
          ]
        },
        {
          "id": "51d0dfbc-cc7a-430b-b7b5-b39b9deab4cc",
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
              "id": "ba73e63d-922d-4c07-ae23-9e2a0f6bac07"
            }
          ]
        },
        {
          "id": "d444e1e8-dbe0-4a47-a08a-af35e0d32ef9",
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
              "id": "b0fbb3dd-fa8f-4758-9d32-3bb66d7f2e6a"
            }
          ]
        },
        {
          "id": "4dff9a56-d5aa-4302-8719-6d2032d30a18",
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
              "id": "c80365fb-15c3-4d3f-8287-f38ee3a5b16d"
            }
          ]
        },
        {
          "id": "5d973904-843a-4946-b95d-b10a9d15dfe0",
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
              "id": "dac86b7f-b662-4a23-a743-01b7ecbd0775"
            }
          ]
        },
        {
          "id": "20fda22b-1031-48ab-bf93-8e5363f7c682",
          "name": "getV1ShoppersMeProductsPointOfPromotionsPopOffers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/products/:id/point-of-promotions/:popId/offers"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "popId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get shoppers me products point of promotions popid offers."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b73a9e46-13e9-474d-a9b6-8db8a1f5a84f"
            }
          ]
        },
        {
          "id": "889a7dfc-45e6-4a16-a087-20654f6c6252",
          "name": "postV1ShoppersMeProductsPurchase",
          "request": {
            "url": {
              "protocol": "http",
              "host": "store.digitalriver.com",
              "path": [
                "store",
                "TODO%20Add%20Value%20for%20parameter...",
                "v1/shoppers/me/products/:id/purchase"
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
            "description": "Post shoppers me products purchase."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b58d1544-235a-4dbd-a15d-8e80eea8640b"
            }
          ]
        }
      ]
    }
  ]
}