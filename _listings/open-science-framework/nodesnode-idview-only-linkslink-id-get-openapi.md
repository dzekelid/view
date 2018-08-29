---
swagger: "2.0"
x-collection-name: Open Science Framework
x-complete: 0
info:
  title: Open Science Framework Retrieve a view only link
  description: |-
    Retrieves the details of a view only link on a node.
    ####Returns
    Returns a JSON object with a `data` key containing the representation of the requested view only link, if the request is successful.

    If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
    ####Permissions

    View only links on a node, public or private, are readable and writeable only by users that are administrators on the node.
  contact:
    name: OSF
    url: https://osf.io/support
    email: support@osf.io
  version: "2.0"
host: test-api.osf.io
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /nodes/{node_id}/view_only_links/:
    get:
      summary: List all view only links
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
      operationId: nodes_view_only_links_list
      x-api-path-slug: nodesnode-idview-only-links-get
      parameters:
      - in: path
        name: node_id
        description: The unique identifier of the node
      responses:
        200:
          description: OK
      tags:
      - Nodes
      - Node
      - View
      - Only
      - Links
  /nodes/{node_id}/view_only_links/{link_id}/:
    get:
      summary: Retrieve a view only link
      description: |-
        Retrieves the details of a view only link on a node.
        ####Returns
        Returns a JSON object with a `data` key containing the representation of the requested view only link, if the request is successful.

        If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
        ####Permissions

        View only links on a node, public or private, are readable and writeable only by users that are administrators on the node.
      operationId: nodes_view_only_links_read
      x-api-path-slug: nodesnode-idview-only-linkslink-id-get
      parameters:
      - in: path
        name: link_id
        description: The unique identifier of the view only link
      - in: path
        name: node_id
        description: The unique identifier of the node
      responses:
        200:
          description: OK
      tags:
      - Nodes
      - Node
      - View
      - Only
      - Links
      - Link
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