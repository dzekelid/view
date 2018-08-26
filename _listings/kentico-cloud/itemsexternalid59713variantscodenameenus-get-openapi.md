---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 0
info:
  title: Kentico Cloud View a language variant by language codename
  description: Retrieve content of a variant of a content item. The content item is
    specified by its external ID and the project language is specified by its codename.
  version: 1.0.0
host: deliver.kenticocloud.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /items/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5:
    get:
      summary: View a content item by ID
      description: Retrieve metadata information about a content item specified by
        its internal ID.
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5Get
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Content
      - Item
      - By
      - ID
  /items/codename/on_roasts:
    get:
      summary: View a content item by codename
      description: Retrieve metadata information about a content item specified by
        its codename.
      operationId: ItemsCodenameOnRoastsGet
      x-api-path-slug: itemscodenameon-roasts-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Content
      - Item
      - By
      - Codename
  /items/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5/variants/codename/en-US:
    get:
      summary: View a language variant by language codename
      description: Retrieve content of a variant of a content item. The content item
        is specified by its internal ID and the project language is specified by its
        codename.
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5VariantsCodenameEnUSGet
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5variantscodenameenus-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Language
      - Variant
      - By
      - Language
      - Codename
  /items/3120ec15-a4a2-47ec-8ccd-c85ac8ac5ba5/variants/00000000-0000-0000-0000-000000000000:
    get:
      summary: View a language variant by language ID
      description: Retrieve content of a language variant of a content item. Both
        the content item and the project language are specified by their internal
        IDs.
      operationId: Items3120ec15A4a247ec8ccdC85ac8ac5ba5Variants00000000000000000000000000000000Get
      x-api-path-slug: items3120ec15a4a247ec8ccdc85ac8ac5ba5variants00000000000000000000000000000000-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Language
      - Variant
      - By
      - Language
      - ID
  /assets/external-id/which-brewing-fits-you:
    get:
      summary: View an asset by external ID
      description: Retrieve information about a single asset specified by its external
        ID.
      operationId: AssetsExternalIdWhichBrewingFitsYouGet
      x-api-path-slug: assetsexternalidwhichbrewingfitsyou-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Asset
      - By
      - External
      - ID
  /assets/fcbb12e6-66a3-4672-85d9-d502d16b8d9c:
    get:
      summary: View an asset by ID
      description: "Modifies properties of an asset specified by its internal ID.\r\n\r\nNote:
        This endpoint only allows updating of asset descriptions and title."
      operationId: AssetsFcbb12e666a3467285d9D502d16b8d9cGet
      x-api-path-slug: assetsfcbb12e666a3467285d9d502d16b8d9c-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Asset
      - By
      - ID
  /items/external-id/59713/variants/00000000-0000-0000-0000-000000000000:
    get:
      summary: View a language variant by language ID
      description: Retrieve content of a variant of a content item. The content item
        is specified by its external ID and the project language is specified by its
        internal ID.
      operationId: ItemsExternalId59713Variants00000000000000000000000000000000Get
      x-api-path-slug: itemsexternalid59713variants00000000000000000000000000000000-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Language
      - Variant
      - By
      - Language
      - ID
  /items/external-id/59713/variants/codename/en-US:
    get:
      summary: View a language variant by language codename
      description: Retrieve content of a variant of a content item. The content item
        is specified by its external ID and the project language is specified by its
        codename.
      operationId: ItemsExternalId59713VariantsCodenameEnUSGet
      x-api-path-slug: itemsexternalid59713variantscodenameenus-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Language
      - Variant
      - By
      - Language
      - Codename
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---