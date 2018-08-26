---
swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 0
info:
  title: Kentico Cloud View an asset by external ID
  description: Retrieve information about a single asset specified by its external
    ID.
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