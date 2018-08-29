---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API View channel
  description: |-
    Perform all the actions involved in viewing a channel. This includes marking channels as read, clearing push notifications, and updating the active channel.
    ##### Permissions
    Must be logged in as user or have `edit_other_users` permission.

    __Response only includes `last_viewed_at_times` in Mattermost server 4.3 and newer.__
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /channels/members/{user_id}/view:
    post:
      summary: View channel
      description: |-
        Perform all the actions involved in viewing a channel. This includes marking channels as read, clearing push notifications, and updating the active channel.
        ##### Permissions
        Must be logged in as user or have `edit_other_users` permission.

        __Response only includes `last_viewed_at_times` in Mattermost server 4.3 and newer.__
      operationId: perform-all-the-actions-involved-in-viewing-a-channel-this-includes-marking-channels-as-read-clearin
      x-api-path-slug: channelsmembersuser-idview-post
      parameters:
      - in: body
        name: body
        description: Paremeters affecting how and which channels to view
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: user_id
        description: User ID to perform the view action for
      responses:
        200:
          description: OK
      tags:
      - View
      - Channel
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