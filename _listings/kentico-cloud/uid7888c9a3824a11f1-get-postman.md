{
  "info": {
    "name": "Kentico Cloud View data of visitor by ID",
    "_postman_id": "4d7bca2c-b78a-4aba-8a58-e2a0eb40ab81",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "View",
      "item": [
        {
          "id": "c324a445-ab59-4b54-b761-9bd8917fbc34",
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
              "id": "14d3b1fc-6aa1-465a-a1cb-e8e928cb5c9a"
            }
          ]
        },
        {
          "id": "2bfb98c0-94c6-4a3d-a53c-da067f681ee8",
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
              "id": "67aa25c4-a862-42ff-8850-298624409204"
            }
          ]
        },
        {
          "id": "bb7e76c2-a895-49f5-b16f-9c1386d45143",
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
              "id": "c4c21f90-0c6f-4e28-a545-0d952130cfcb"
            }
          ]
        },
        {
          "id": "66fea514-2d8a-48af-9bb7-4f22c21c31a5",
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
              "id": "7c01294b-49e3-45d3-9b9b-3e32676436f8"
            }
          ]
        },
        {
          "id": "5e50541a-6ad2-4a5f-bb2c-f2aa684eae4e",
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
              "id": "014389ff-3998-48bd-b308-d184775648e5"
            }
          ]
        },
        {
          "id": "8dd2c0a5-eba5-4a30-92f8-49bdd3e598e0",
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
              "id": "f73d52a5-49bf-4b5a-96ed-8fec9c0218f8"
            }
          ]
        },
        {
          "id": "665dfc38-8732-41cb-a5f9-635d7e5ec16b",
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
              "id": "d8cfdff7-1e0f-4023-abf6-1c130783e4ab"
            }
          ]
        },
        {
          "id": "dca53fd9-46ca-4f4c-9d89-6828701e2e77",
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
              "id": "c1edf7ae-7d6f-4dbb-ac8e-60b45390067c"
            }
          ]
        },
        {
          "id": "6203246c-a8e9-4df9-a1c7-cbdb28e020bf",
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
              "id": "39ce9896-73bd-46e4-a58a-72616ec78edb"
            }
          ]
        },
        {
          "id": "cf1ce802-f52e-44b8-8d4a-4282b25e9ed6",
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
              "id": "ec6a7213-b257-4ebc-bc18-710079d0a8c1"
            }
          ]
        },
        {
          "id": "53a2f6ad-7e8f-46bf-8f4a-964f7a2e6a77",
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
              "id": "a1e8f7a9-9e5f-49f2-ba54-4b18d644a2aa"
            }
          ]
        }
      ]
    }
  ]
}