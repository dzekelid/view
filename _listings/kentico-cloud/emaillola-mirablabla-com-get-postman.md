{
  "info": {
    "name": "Kentico Cloud View data of visitor by email",
    "_postman_id": "da3d846a-68de-4ef9-88b0-c4cc59a5b9f6",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "View",
      "item": [
        {
          "id": "979b2b99-1ce0-476d-8f80-39548bdc8d9f",
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
              "id": "7a674392-f872-4b49-bca9-cfccead1e8be"
            }
          ]
        },
        {
          "id": "eb3fcae3-154f-4438-a4af-8963721be24e",
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
              "id": "df59e94f-106e-48f1-8452-c157c54b4be6"
            }
          ]
        },
        {
          "id": "5e00af12-f2c5-4b89-8e08-c67d2f2e64e6",
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
              "id": "ee3bdc29-f416-413a-b2e5-ef523305144e"
            }
          ]
        },
        {
          "id": "a94caa65-a2ee-4d39-89f4-272abe110f82",
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
              "id": "7223f394-7363-4596-9826-e1a0e196b770"
            }
          ]
        },
        {
          "id": "3cd6f7f0-9dc7-4679-abc1-aa1227736674",
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
              "id": "6f99646c-9f13-470b-836f-5ad6a0e21ea0"
            }
          ]
        },
        {
          "id": "74bb0dc9-b0c7-42c0-86c9-b89a2e84629b",
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
              "id": "acef6408-c3af-47a4-aa18-79f61a241df9"
            }
          ]
        },
        {
          "id": "2d4e0273-198e-442b-bf42-6945d80e5ee4",
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
              "id": "203a4b54-2290-4687-a8e1-dda11ca91344"
            }
          ]
        },
        {
          "id": "293be492-a8c3-444f-87f3-00fecfe311ca",
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
              "id": "27037c23-a302-4049-9369-27f51834b716"
            }
          ]
        },
        {
          "id": "5bd3fe2d-39a1-49cb-a06c-5334b9881188",
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
              "id": "fd3232c8-0fbd-4919-ad19-0beb196963cc"
            }
          ]
        },
        {
          "id": "50d349bc-41e7-4cad-8416-6b4a243b15a6",
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
              "id": "cfdb4b43-24cf-4c4c-b2e4-c57e508f8ddf"
            }
          ]
        },
        {
          "id": "482e834c-1a51-4983-8062-bc4dd58680b9",
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
              "id": "6d743696-0d35-41ac-8bfa-ba6d0d287fda"
            }
          ]
        },
        {
          "id": "0ad875ea-8019-4e6c-95f9-632d225f2296",
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
              "id": "c654e3dd-0137-421b-a96f-bdfaa1065728"
            }
          ]
        },
        {
          "id": "9871871d-3aac-477e-9871-fd2e10be8bbf",
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
              "id": "0d381d14-3cec-4d65-9356-f11cade77685"
            }
          ]
        },
        {
          "id": "e8726c95-c4d4-4e40-9632-14e4fe32698a",
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
              "id": "0b5ae2a9-b5d4-4870-8fb3-984f25cb828c"
            }
          ]
        },
        {
          "id": "47cd81d6-27a7-441b-8592-948da64875fd",
          "name": "EmailLolaMiraBlablaComGet",
          "request": {
            "url": "http://deliver.kenticocloud.com/email/lola.mira@blabla.com",
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
            "description": "View data of visitor by email"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de3b1d8f-f6f2-403b-b0fb-53e21fb0c3dc"
            }
          ]
        }
      ]
    }
  ]
}