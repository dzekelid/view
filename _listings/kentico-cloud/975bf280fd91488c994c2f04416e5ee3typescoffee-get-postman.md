{
  "info": {
    "name": "Kentico Cloud View a content type",
    "_postman_id": "c70f4217-79ae-4bc9-ac2f-c1e62c95b664",
    "description": "Retrieve a specific content type from your project by specifying its codename.\n\nSee <https://developer.kenticocloud.com/v1/reference#view-a-content-type> for more details.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "View",
      "item": [
        {
          "id": "f2f31503-1df6-42a4-854f-4e37240f3778",
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
              "id": "e9de9611-3f00-41b3-9f91-7bc44ccd8939"
            }
          ]
        },
        {
          "id": "d6f4875b-4259-4671-b615-ca2c89eb4758",
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
              "id": "f6c29b51-d40e-44bf-9171-149561b3731f"
            }
          ]
        },
        {
          "id": "9a093ae1-9df2-49ff-86ec-40f4f3410a64",
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
              "id": "88827c39-73d5-4589-8bb2-2f0382ae5b0e"
            }
          ]
        },
        {
          "id": "831969e6-b598-49bb-a521-899775973359",
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
              "id": "253f3679-49f5-40a0-b330-064e8247a0b6"
            }
          ]
        },
        {
          "id": "1ea3394e-a281-4a98-8d3e-22d24b63d5b3",
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
              "id": "7f363ee6-db80-42a3-81de-dce9390206a1"
            }
          ]
        },
        {
          "id": "d166a8c1-151f-4b9f-99be-f013b033e74d",
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
              "id": "4843b89b-29ef-4817-ac73-e562e2a1476b"
            }
          ]
        },
        {
          "id": "80a61bc9-7424-4c6e-b266-080f465405af",
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
              "id": "dcc5a722-77d4-4c91-bf46-57bb03e81efb"
            }
          ]
        },
        {
          "id": "57ecf117-dab0-4f4b-9c5e-007f364b3eb2",
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
              "id": "13cbb93f-449e-45b9-80f7-96eb3424df3f"
            }
          ]
        },
        {
          "id": "318b0c58-3b68-48ba-8f67-fb4192110a8d",
          "name": "ItemsExternalId59713Get",
          "request": {
            "url": "http://deliver.kenticocloud.com/items/external-id/59713",
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
            "description": "Retrieve metadata information about a content item specified by its external ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aeaeb38b-fe39-4016-920e-4cce2ade4a50"
            }
          ]
        },
        {
          "id": "09b85191-e432-4d06-8016-e40435a32533",
          "name": "975bf280Fd91488c994c2f04416e5ee3TaxonomiesPersonasGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/975bf280-fd91-488c-994c-2f04416e5ee3/taxonomies/personas",
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
            "description": "Retrieve a specific taxonomy group from your project by specifying its codename.\n\nSee <https://developer.kenticocloud.com/v1/reference#view-a-taxonomy-group> for more details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd3bc072-7a89-4280-a6e7-6da2a8e5c5c9"
            }
          ]
        },
        {
          "id": "c53dd164-e297-4be4-b7ba-745ce2b48168",
          "name": "Uid7888c9a3824a11f1Get",
          "request": {
            "url": "http://deliver.kenticocloud.com/uid/7888c9a3824a11f1",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "View data of visitor by ID"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "df1725b0-a198-4316-8e14-55159e0b54ea"
            }
          ]
        },
        {
          "id": "63d11ffb-4ee3-470a-96b3-f67b825c28e5",
          "name": "975bf280Fd91488c994c2f04416e5ee3TypesCoffeeGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/975bf280-fd91-488c-994c-2f04416e5ee3/types/coffee",
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
            "description": "Retrieve a specific content type from your project by specifying its codename.\n\nSee <https://developer.kenticocloud.com/v1/reference#view-a-content-type> for more details."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "046032e5-ca9b-4e32-93ef-e5e563cc2fcf"
            }
          ]
        }
      ]
    }
  ]
}