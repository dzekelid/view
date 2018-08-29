swagger: "2.0"
x-collection-name: Reviewshake
x-complete: 1
info:
  title: Reviewshake API
  description: welcome-to-the-reviewshake-api-documentation-where-you-will-find-all-details-required-to-interact-with-our-api-in-order-to-make-calls-you-will-need-two-pieces-of-information1--your-reviewshake-subdomain-eg--demo-reviewshake-com2--your-api-key-see-the-authentication-section-below--authenticationyour-account-will-have-a-unique-api-key-associated-with-it-which-can-be-found-under--configurations----general-settings--in-your-dashboard-
  version: "1.0"
host: subdomain.reviewshake.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /widgets/1:
    get:
      summary: View widget
      description: View widget.
      operationId: Widgets1Get
      x-api-path-slug: widgets1-get
      parameters:
      - in: header
        name: Content-Type
      - in: header
        name: X-Spree-Token
      responses:
        200:
          description: OK
      tags:
      - View
      - Widget