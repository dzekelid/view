---
swagger: "2.0"
x-collection-name: Entertainment Express
x-complete: 1
info:
  title: Entertainment Express
  description: your-gateway-to-building-incredible-movie-tv-and-game-content-discovery-experiences-
  version: "2.0"
host: ee.iva-api.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Analytics/City/:
    get:
      summary: Get Viewers by City.
      description: No required parameters, DateValue defaults to Today..
      operationId: GetAnalyticsViewersByCity
      x-api-path-slug: analyticscity-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: End
        description: Report end date
      - in: query
        name: Limit
        description: Number of records returned from top of response
      - in: query
        name: ReportTag
        description: Report Tag filter
      - in: query
        name: Start
        description: Report start date
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - City
  /Analytics/Country/:
    get:
      summary: Get Viewers by Country.
      description: No required parameters, DateValue defaults to Today.
      operationId: GetAnalyticsViewersByCountry
      x-api-path-slug: analyticscountry-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: End
        description: Report end date
      - in: query
        name: Limit
        description: Number of records returned from top of response
      - in: query
        name: ReportTag
        description: Report Tag filter
      - in: query
        name: Start
        description: Report start date
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - Country
  /Analytics/EngagementTimes/:
    get:
      summary: Get View count by Frequency.
      description: No required parameters, DateValue defaults to Today.
      operationId: GetAnalyticsEngagementTimes
      x-api-path-slug: analyticsengagementtimes-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: End
        description: Report end date
      - in: query
        name: Limit
        description: Number of records returned from top of response
      - in: query
        name: ReportTag
        description: Report Tag filter
      - in: query
        name: Start
        description: Report start date
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - EngagementTimes
  /Analytics/PlatformHardware/:
    get:
      summary: Get Viewers by Platform Hardware.
      description: No required parameters, DateValue defaults to Today.
      operationId: GetAnalyticsViewersByPlatformHardware
      x-api-path-slug: analyticsplatformhardware-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: End
        description: Report end date
      - in: query
        name: Limit
        description: Number of records returned from top of response
      - in: query
        name: ReportTag
        description: Report Tag filter
      - in: query
        name: Start
        description: Report start date
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - PlatformHardware
  /Analytics/PlatformOS/:
    get:
      summary: Get Viewers by Platform OS.
      description: No required parameters, DateValue defaults to Today.
      operationId: GetAnalyticsViewersByPlatformOS
      x-api-path-slug: analyticsplatformos-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: End
        description: Report end date
      - in: query
        name: Limit
        description: Number of records returned from top of response
      - in: query
        name: ReportTag
        description: Report Tag filter
      - in: query
        name: Start
        description: Report start date
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - PlatformOS
  /Analytics/VideoLog/:
    get:
      summary: Get Views by Video.
      description: No required parameters, DateValue defaults to Today.
      operationId: GetAnalyticsViewsByVideoLog
      x-api-path-slug: analyticsvideolog-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: End
        description: Report end date
      - in: query
        name: Limit
        description: Number of records returned from top of response
      - in: query
        name: ReportTag
        description: Report Tag filter
      - in: query
        name: Start
        description: Report start date
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - VideoLog
  /Analytics/Viewers/:
    get:
      summary: Get viewers by Day.
      description: Optional DateValue for length of report.
      operationId: GetAnalyticsViewers
      x-api-path-slug: analyticsviewers-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: ReportTag
        description: Report Tag filter
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - Viewers
  /Analytics/Views/:
    get:
      summary: Get views by Day.
      description: Optional DateValue for length of report.
      operationId: GetAnalyticsViews
      x-api-path-slug: analyticsviews-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: ReportTag
        description: Report Tag filter
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - Views
  /Analytics/WebBrowsers/:
    get:
      summary: Get Viewers by Web Browser.
      description: No required parameters, DateValue defaults to Today.
      operationId: GetAnalyticsViewersByWebBrowsers
      x-api-path-slug: analyticswebbrowsers-get
      parameters:
      - in: query
        name: DateValue
        description: Days spanned by report
      - in: query
        name: End
        description: Report end date
      - in: query
        name: Limit
        description: Number of records returned from top of response
      - in: query
        name: ReportTag
        description: Report Tag filter
      - in: query
        name: Start
        description: Report start date
      responses:
        200:
          description: OK
      tags:
      - Analytics
      - WebBrowsers
---