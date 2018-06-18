---
swagger: "2.0"
x-collection-name: Pay Run
x-complete: 0
info:
  title: Pay Run.IO Insert nominal code
  description: Inserts a new nominal code at the specified resource location
  version: 17.18.6.206
host: api.test.payrun.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Employer/{EmployerId}/NominalCode/{NominalCodeId}:
    delete:
      summary: Deletes the nominal codes
      description: Deletes the nominal code
      operationId: DeleteNominalCode
      x-api-path-slug: employeremployeridnominalcodenominalcodeid-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: NominalCodeId
        description: The nominal code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Nominal
      - Codes
    get:
      summary: Gets the nominal code
      description: Gets the nominal code
      operationId: GetNominalCodeFromEmployer
      x-api-path-slug: employeremployeridnominalcodenominalcodeid-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: NominalCodeId
        description: The nominal code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Nominal
      - Code
    put:
      summary: Insert nominal code
      description: Inserts a new nominal code at the specified resource location
      operationId: PutNominalCode
      x-api-path-slug: employeremployeridnominalcodenominalcodeid-put
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: body
        name: NominalCode
        description: The nominal code object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: NominalCodeId
        description: The nominal code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Nominal
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