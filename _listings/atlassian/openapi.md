swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/2/filter/{id}/columns:
    get:
      summary: Get columns
      description: Returns the columns configured for a filter. The column configuration
        is used when the filter's results are viewed in _List View_ with the _Columns_
        set to _Filter_. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** None, however the calling user must have permission to view the
        filter.
      operationId: com.atlassian.jira.rest.v2.search.FilterResource.getColumns_get
      x-api-path-slug: api2filteridcolumns-get
      parameters:
      - in: path
        name: id
        description: The ID of the filter
      responses:
        200:
          description: OK
      tags:
      - Columns
  /api/2/worklog/list:
    post:
      summary: Get worklogs
      description: "Returns worklog details for a list of worklog IDs.  \n  \nWorklogs
        can be set as viewable by:\n\n*   all users\n*   members of a project role
        or group\n\nFor a worklog to be returned, it must be set as _Viewable by All
        Users_ or the calling user must be a member of the project role or group with
        permission to view the worklog.  \n  \nThe returned list of worklogs is limited
        to 1000 items. **[Permissions](https://confluence.atlassian.com/x/FQiiLQ)
        required:** Permission to access Jira."
      operationId: com.atlassian.jira.rest.v2.issue.worklog.WorklogResource.getWorklogsForIds_post
      x-api-path-slug: api2workloglist-post
      parameters:
      - in: query
        name: expand
        description: Use [expand](https://developer
      responses:
        200:
          description: OK
      tags:
      - Worklogs