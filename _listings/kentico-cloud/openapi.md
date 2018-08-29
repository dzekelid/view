swagger: "2.0"
x-collection-name: Kentico Cloud
x-complete: 1
info:
  title: Kentico Cloud
  description: this-is-a-collection-of-resources-you-can-find-within-the-kentico-cloud-developer-hubhttpsdeveloper-kenticocloud-com--kentico-cloudhttpskenticocloud-com-is-a-cloudfirst-headless-cms-that-allows-you-to-distribute-content-to-any-channel-and-device-websites-mobile-devices-mixed-reality-devices-presentation-kiosks-etc--through-an-api-certain-apis-require-that-you-include-the-authorization-header--find-more-in-httpsdeveloper-kenticocloud-comreferenceauthentication-
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
  /items/external-id/59713:
    get:
      summary: View a content Item by external ID
      description: Retrieve metadata information about a content item specified by
        its external ID.
      operationId: ItemsExternalId59713Get
      x-api-path-slug: itemsexternalid59713-get
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
      - External
      - ID
  /975bf280-fd91-488c-994c-2f04416e5ee3/taxonomies/personas:
    get:
      summary: View a taxonomy group
      description: |-
        Retrieve a specific taxonomy group from your project by specifying its codename.

        See <https://developer.kenticocloud.com/v1/reference#view-a-taxonomy-group> for more details.
      operationId: 975bf280Fd91488c994c2f04416e5ee3TaxonomiesPersonasGet
      x-api-path-slug: 975bf280fd91488c994c2f04416e5ee3taxonomiespersonas-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Taxonomy
      - Group
  /uid/7888c9a3824a11f1:
    get:
      summary: View data of visitor by ID
      description: ""
      operationId: Uid7888c9a3824a11f1Get
      x-api-path-slug: uid7888c9a3824a11f1-get
      responses:
        200:
          description: OK
      tags:
      - View
      - Data
      - Of
      - Visitor
      - By
      - ID
  /975bf280-fd91-488c-994c-2f04416e5ee3/types/coffee:
    get:
      summary: View a content type
      description: |-
        Retrieve a specific content type from your project by specifying its codename.

        See <https://developer.kenticocloud.com/v1/reference#view-a-content-type> for more details.
      operationId: 975bf280Fd91488c994c2f04416e5ee3TypesCoffeeGet
      x-api-path-slug: 975bf280fd91488c994c2f04416e5ee3typescoffee-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Content
      - Type
  /items/codename/on_roasts/variants/00000000-0000-0000-0000-000000000000:
    get:
      summary: View a language variant by language ID
      description: Retrieve content of a variant of a content item. The content item
        is specified by codename and the project language is specified its internal
        ID.
      operationId: ItemsCodenameOnRoastsVariants00000000000000000000000000000000Get
      x-api-path-slug: itemscodenameon-roastsvariants00000000000000000000000000000000-get
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
  /items/codename/on_roasts/variants/codename/en-US:
    get:
      summary: View a language variant by language codename
      description: Retrieve content of a language variant of a content item. Both
        the content item and the language are specified by their codenames.
      operationId: ItemsCodenameOnRoastsVariantsCodenameEnUSGet
      x-api-path-slug: itemscodenameon-roastsvariantscodenameenus-get
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
  /email/lola.mira@blabla.com:
    get:
      summary: View data of visitor by email
      description: ""
      operationId: EmailLolaMiraBlablaComGet
      x-api-path-slug: emaillola-mirablabla-com-get
      responses:
        200:
          description: OK
      tags:
      - View
      - Data
      - Of
      - Visitor
      - By
      - Email
  /975bf280-fd91-488c-994c-2f04416e5ee3/types/coffee/elements/processing:
    get:
      summary: View a content type element
      description: |-
        Retrieve a specific content type element by specifying its codename and its parent content type.

        See <https://developer.kenticocloud.com/v1/reference#view-a-content-type-element> for more details.
      operationId: 975bf280Fd91488c994c2f04416e5ee3TypesCoffeeElementsProcessingGet
      x-api-path-slug: 975bf280fd91488c994c2f04416e5ee3typescoffeeelementsprocessing-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - View
      - Content
      - Type
      - Element