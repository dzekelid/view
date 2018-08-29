---
name: Open Science Framework
x-slug: open-science-framework
description: OSF provides free and open source project management support for researchers
  across the entire research lifecycle. As a collaboration tool, OSF helps researchers
  work on projects privately with a limited number of collaborators and make parts
  of their projects public, or make all the project publicly accessible for broader
  dissemination. As a workflow system, OSF enables connections to the many services
  researchers already use to streamline their process and increase efficiency. As
  a flexible repository, it can store and archive research data, protocols, and materials.
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: View
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/apis.md
specificationVersion: "0.14"
apis:
- name: Open Science Framework - List all view only links
  x-api-slug: nodesnode-idview-only-links-get
  description: |-
    List of view only links on a node.
    ####Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of up to 10 view only links. Each resource in the array is a view only link object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    ####Permissions

    View only links on a node, public or private, are readable and writeable only by users that are administrators on the node.

    ####Filtering

    You can optionally request that the response only include view only links that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/nodes/ezcuj/view_only_links/?filter[anonymous]=true.

    View Only Links may be filtered based on their `name`, `anonymous` and `date_created` fields. Possible comparison operators include 'gt' (greater than), 'gte'(greater than or equal to), 'lt' (less than) and 'lte' (less than or equal to). The date must be in the format YYYY-MM-DD and the time is optional.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/nodesnode-idview-only-links-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/nodesnode-idview-only-links-get-openapi.md
- name: Open Science Framework - Retrieve a view only link
  x-api-slug: nodesnode-idview-only-linkslink-id-get
  description: |-
    Retrieves the details of a view only link on a node.
    ####Returns
    Returns a JSON object with a `data` key containing the representation of the requested view only link, if the request is successful.

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    ####Permissions

    View only links on a node, public or private, are readable and writeable only by users that are administrators on the node.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/nodesnode-idview-only-linkslink-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/nodesnode-idview-only-linkslink-id-get-openapi.md
- name: Open Science Framework - List all view only links
  x-api-slug: registrationsregistration-idview-only-links-get
  description: |-
    A paginated list of view only links created for this registration.
    ####Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of up to 10 view only links. Each resource in the array is a view only link object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    ####Permissions

    View only links on a registration, public or private, are readable and writeable only by users that are administrators on the registration.

    ####Filtering

    You can optionally request that the response only include view only links that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/registrations/wu3a4/view_only_links/?filter[anonymous]=true.

    View Only Links may be filtered based on their `name`, `anonymous` and `date_created` fields. Possible comparison operators include 'gt' (greater than), 'gte'(greater than or equal to), 'lt' (less than) and 'lte' (less than or equal to). The date must be in the format YYYY-MM-DD and the time is optional.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/registrationsregistration-idview-only-links-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/registrationsregistration-idview-only-links-get-openapi.md
- name: Open Science Framework - Retrieve a view only link
  x-api-slug: registrationsregistration-idview-only-linkslink-id-get
  description: |-
    Retrieves the details of a view only link created from this registration.
    ####Returns
    Returns a JSON object with a `data` key containing the representation of the requested view only link, if the request is successful.

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    ####Permissions

    View only links on a registration, public or private, are readable and writeable only by users that are administrators on the registration.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/registrationsregistration-idview-only-linkslink-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/registrationsregistration-idview-only-linkslink-id-get-openapi.md
- name: Open Science Framework - Retrieve a view only link
  x-api-slug: view-only-linkslink-id-get
  description: |-
    Retrieves details about a specific view only link.
    ####Permissions
    Only project administrators may retrieve the details of a view only link. Attempting to retrieve a view only link without appropriate permissions will result in a 403 Forbidden response.
    #### Returns
    Returns a JSON object with a `data` key containing the representation of the requested view only link, if the request is successful.
    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/view-only-linkslink-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/view-only-linkslink-id-get-openapi.md
- name: Open Science Framework - List all nodes
  x-api-slug: view-only-linkslink-idnodes-get
  description: |-
    The list of nodes which this view only link gives read-only access to.
    #### Permissions
    Only project administrators may retrieve the nodes of a view only link. Attempting to retrieve a view only link without appropriate permissions will result in a 403 Forbidden response.
    #### Returns
    Returns a JSON object containing `data` and `links` keys.
    The `data` key contains an array of up to 10 nodes. Each resource in the array is a separate node object and contains the full representation of the node, meaning additional requests to a node's detail view are not necessary.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
  image: ""
  humanURL: https://cos.io
  baseURL: https://test-api.osf.io//v2
  tags: Research, Science, API Provider, Profiles, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/view-only-linkslink-idnodes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/view/master/_listings/open-science-framework/view-only-linkslink-idnodes-get-openapi.md
x-common:
- type: x-website
  url: https://cos.io
- type: x-api-gallery
  url: http://open.fintech.api.gallery.streamdata.io
- type: x-api-stack
  url: http://open.science.framework.stack.network
- type: x-github
  url: https://github.com/OSFramework
- type: x-twitter
  url: https://twitter.com/OSFramework
- type: x-website
  url: http://osf.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---