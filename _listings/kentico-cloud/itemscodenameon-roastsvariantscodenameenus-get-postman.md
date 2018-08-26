{
  "info": {
    "name": "Kentico Cloud View a language variant by language codename",
    "_postman_id": "e566fb48-776b-4c89-8251-a388f9d37850",
    "description": "Retrieve content of a language variant of a content item. Both the content item and the language are specified by their codenames.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "View",
      "item": [
        {
          "id": "1ebad8d1-6b47-4146-9821-a376c677dee9",
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
              "id": "6a5b65b8-52b3-4610-8908-4978e8d4ca5a"
            }
          ]
        },
        {
          "id": "66416f8e-c4af-46b3-aac9-71cffb64b2bf",
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
              "id": "d3c807f4-6413-456b-8d82-76a1b6d75313"
            }
          ]
        },
        {
          "id": "4ab090f8-74dc-4d1b-a936-c3e91d4db851",
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
              "id": "1625a439-95e2-4bfd-80d5-83abc2f6916b"
            }
          ]
        },
        {
          "id": "a1b4b8f0-912b-4248-8d1e-c65dbfc1b4ff",
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
              "id": "69fe2a40-f305-499f-a96d-5349b96732fe"
            }
          ]
        },
        {
          "id": "bd5a90f0-96c2-4efd-947d-95671f95b19c",
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
              "id": "15e115cd-7968-4a0b-926a-ea7dbcccd117"
            }
          ]
        },
        {
          "id": "5cb7971b-bb5f-4655-b361-2288201500e4",
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
              "id": "cdb9785f-6257-44a4-90cb-c1151df2ba5a"
            }
          ]
        },
        {
          "id": "557266d4-92a7-43c4-a120-2db53afb948d",
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
              "id": "eabfc072-c7f6-450a-8794-445ad02cbf6e"
            }
          ]
        },
        {
          "id": "84516802-f99b-4bf2-afff-fd4ae437fbb5",
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
              "id": "2418468f-09ec-445c-b5a6-440e66f9e006"
            }
          ]
        },
        {
          "id": "6c2ec608-941c-45e9-9d08-d94dc6b45b0d",
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
              "id": "59c5e805-981a-43f9-9dc4-00b81dad4615"
            }
          ]
        },
        {
          "id": "4c73313c-b78d-444d-8935-29784458bba3",
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
              "id": "b90a05b0-2fa7-4b1d-954f-44d958b37677"
            }
          ]
        },
        {
          "id": "ffa5a3ba-5f63-4898-8bbe-d87bd43e507f",
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
              "id": "4faa5e4b-af5e-4412-8b47-635079cc3739"
            }
          ]
        },
        {
          "id": "d6693a8a-6b3f-44f5-b03d-da9e9a069c24",
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
              "id": "859d7aaa-a110-4595-80ff-93adf099c195"
            }
          ]
        },
        {
          "id": "1c5ebb6d-dfc1-4405-b987-98df0412905f",
          "name": "ItemsCodenameOnRoastsVariants00000000000000000000000000000000Get",
          "request": {
            "url": "http://deliver.kenticocloud.com/items/codename/on_roasts/variants/00000000-0000-0000-0000-000000000000",
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
            "description": "Retrieve content of a variant of a content item. The content item is specified by codename and the project language is specified its internal ID."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "312a897a-ecee-4630-97c7-da87895856a2"
            }
          ]
        },
        {
          "id": "55287828-902a-457f-aa39-4c405eaad74a",
          "name": "ItemsCodenameOnRoastsVariantsCodenameEnUSGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/items/codename/on_roasts/variants/codename/en-US",
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
            "description": "Retrieve content of a language variant of a content item. Both the content item and the language are specified by their codenames."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0af81bf6-def4-40a2-8d30-c437e1d6786a"
            }
          ]
        }
      ]
    }
  ]
}