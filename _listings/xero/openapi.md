---
swagger: "2.0"
x-collection-name: Xero
x-complete: 1
info:
  title: Accounting
  description: -introductionthe-xero-accounting-api-is-a-restful-web-service-and-uses-the-oauth-v1-0a-protocol-to-authenticate-3rd-party-applications--the-accounting-api-exposes-accounting-and-related-functions-of-the-main-xero-application-and-can-be-used-for-a-variety-of-purposes-such-as-creating-transactions-like-invoices-and-credit-notes-right-through-to-extracting-accounting-data-via-our-reports-endpoint-
  contact:
    name: Xero Developer Team
    url: https://developer.xero.com
  version: "2.0"
host: api.xero.com
basePath: /api.xro/2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Organisation/{ShortCode}:
    get:
      summary: Get Organisation Shortcode
      description: Get organisation shortcode.
      operationId: getOrganisationShortcode
      x-api-path-slug: organisationshortcode-get
      parameters:
      - in: path
        name: ShortCode
      responses:
        200:
          description: OK
      tags:
      - Organisation
      - ShortCode
    x-related-model:
      summary: X-related-model Organisation Shortcode
      description: X-related-model organisation shortcode.
      operationId: x-related-modelOrganisationShortcode
      x-api-path-slug: organisationshortcode-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - Organisation
      - ShortCode
---