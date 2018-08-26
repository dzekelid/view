{
  "info": {
    "name": "Kentico Cloud View a language variant by language codename",
    "_postman_id": "362454ed-ac6b-4d6e-8d38-3bbfb09b751d",
    "description": "Retrieve content of a variant of a content item. The content item is specified by its external ID and the project language is specified by its codename.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "View",
      "item": [
        {
          "id": "dd1f5486-1070-4b71-85df-377b574c85a9",
          "name": "Items3120ec15A4a247ec8ccdC85ac8ac5ba5Get",
          "request": {
            "url": "http://deliver.kenticocloud.com/items/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve metadata information about a content item specified by its internal ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "096813d6-6bb2-42f5-8537-c04686ce77ce"
            }
          ]
        },
        {
          "id": "c11a8241-aea3-4aea-bd68-c90040aec93f",
          "name": "ItemsCodenameOnRoastsGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/items/codename/on_roasts",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve metadata information about a content item specified by its codename."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d5baf358-fa13-4926-98d1-41702b1d6906"
            }
          ]
        },
        {
          "id": "a4568e14-afff-4203-b74d-4394416eb3d2",
          "name": "Items3120ec15A4a247ec8ccdC85ac8ac5ba5VariantsCodenameEnUSGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/items/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5/variants/codename/en-US",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve content of a variant of a content item. The content item is specified by its internal ID and the project language is specified by its codename."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87440bb9-08f3-4610-bec8-97f8ffa70e9a"
            }
          ]
        },
        {
          "id": "06a52d5e-f80f-443c-9fb8-ee6cb3f96882",
          "name": "Items3120ec15A4a247ec8ccdC85ac8ac5ba5Variants00000000000000000000000000000000Get",
          "request": {
            "url": "http://deliver.kenticocloud.com/items/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5/variants/00000000-0000-0000-0000-000000000000",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve content of a language variant of a content item. Both the content item and the project language are specified by their internal IDs."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0846ee33-e67f-40fa-8613-87218d4527d0"
            }
          ]
        },
        {
          "id": "9dad393a-289f-4db6-b738-b0e6807e809f",
          "name": "AssetsExternalIdWhichBrewingFitsYouGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/assets/external-id/which-brewing-fits-you",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve information about a single asset specified by its external ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db84f2ce-219c-41f9-ad0a-43be5af2cb72"
            }
          ]
        },
        {
          "id": "65265247-6830-435a-890f-d5f5ab66f140",
          "name": "AssetsFcbb12e666a3467285d9D502d16b8d9cGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/assets/fcbb12e6-66a3-4672-85d9-d502d16b8d9c",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Modifies properties of an asset specified by its internal ID.\r\n\r\nNote: This endpoint only allows updating of asset descriptions and title."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d5faf724-5b98-45b4-9d2e-100867fc7cf8"
            }
          ]
        },
        {
          "id": "89163360-9629-41e5-bf9c-d3f58e4614ac",
          "name": "ItemsExternalId59713Variants00000000000000000000000000000000Get",
          "request": {
            "url": "http://deliver.kenticocloud.com/items/external-id/59713/variants/00000000-0000-0000-0000-000000000000",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve content of a variant of a content item. The content item is specified by its external ID and the project language is specified by its internal ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36820bf0-72b7-4731-a3cc-90888355d40a"
            }
          ]
        },
        {
          "id": "a1c98eeb-441a-4b22-bb4f-34e81c9fa73f",
          "name": "ItemsExternalId59713VariantsCodenameEnUSGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/items/external-id/59713/variants/codename/en-US",
            "method": "GET",
            "header": [
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve content of a variant of a content item. The content item is specified by its external ID and the project language is specified by its codename."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "547f1738-0de1-4755-897d-cf703d45b798"
            }
          ]
        }
      ]
    }
  ]
}