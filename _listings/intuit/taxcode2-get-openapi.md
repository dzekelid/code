---
swagger: "2.0"
x-collection-name: Intuit
x-complete: 0
info:
  title: QuickBooks Online V3 API Get Tax Code
  description: |-
    Read a taxcode by Id
    Method : POST
  version: 1.0.0
host: DefaultParameterValue
basePath: /v3/company/DefaultParameterValue
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /taxservice/taxcode:
    post:
      summary: Post Tax Service Tax Code
      description: |-
        Use TaxService to create taxcode and corresponding taxrates
        Method : POST
      operationId: postTaxserviceTaxcode
      x-api-path-slug: taxservicetaxcode-post
      parameters:
      - in: header
        name: Accept
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Tax
      - Service
      - Tax
      - Code
  /taxcode/2:
    get:
      summary: Get Tax Code
      description: |-
        Read a taxcode by Id
        Method : POST
      operationId: getTaxcode2
      x-api-path-slug: taxcode2-get
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: query
        name: minorversion
      - in: header
        name: User-Agent
      responses:
        200:
          description: OK
      tags:
      - Accounting
      - Accounting
      - Tax
      - Code
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