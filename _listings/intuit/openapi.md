swagger: "2.0"
x-collection-name: Intuit
x-complete: 1
info:
  title: QuickBooks Online V3 API
  description: the-quickbooks-online-accounting-api-is-a-restful-api-that-is-used-to-access-quickbooks-companies-docs-
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