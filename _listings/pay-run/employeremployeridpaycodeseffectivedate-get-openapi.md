---
swagger: "2.0"
x-collection-name: Pay Run
x-complete: 0
info:
  title: Pay Run.IO Gets all pay codes for specified date
  description: Gets the effective pay code revision for the specified date
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
  /Employer/{EmployerId}/NominalCodes:
    get:
      summary: Gets the nominal codes
      description: Gets the nominal code links
      operationId: GetNominalCodesFromEmployer
      x-api-path-slug: employeremployeridnominalcodes-get
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
      responses:
        200:
          description: OK
      tags:
      - Nominal
      - Codes
    post:
      summary: Insert nominal code
      description: Inserts a new nominal code
      operationId: PostNominalCode
      x-api-path-slug: employeremployeridnominalcodes-post
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
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Nominal
      - Code
  /Employer/{EmployerId}/PayCode/{PayCodeId}:
    delete:
      summary: Deletes a pay code
      description: Delete the specified pay code
      operationId: DeletePayCode
      x-api-path-slug: employeremployeridpaycodepaycodeid-delete
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
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
    get:
      summary: Gets the specified pay code from the employer
      description: Returns the specified pay code from the employer
      operationId: GetPayCodeFromEmployer
      x-api-path-slug: employeremployeridpaycodepaycodeid-get
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
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Specified
      - Pay
      - Code
      - From
      - Employer
    patch:
      summary: Patches the pay code
      description: Patches the specified pay code object with the supplied values
      operationId: PatchPayCode
      x-api-path-slug: employeremployeridpaycodepaycodeid-patch
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
        name: PayCode
        description: The pay code object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Patches
      - Pay
      - Code
    put:
      summary: Updates a pay code
      description: Updates the existing specified pay code object
      operationId: PutPayCode
      x-api-path-slug: employeremployeridpaycodepaycodeid-put
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
        name: PayCode
        description: The pay code object
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
  /Employer/{EmployerId}/PayCode/{PayCodeId}/Tag/{TagId}:
    delete:
      summary: Delete pay code tag
      description: Deletes a tag from the pay code
      operationId: DeletePayCodeTag
      x-api-path-slug: employeremployeridpaycodepaycodeidtagtagid-delete
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
        name: PayCodeId
        description: The pay code unique identifier
      - in: path
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
      - Tag
    get:
      summary: Get pay code tag
      description: Gets the tag from the pay code
      operationId: GetTagFromPayCode
      x-api-path-slug: employeremployeridpaycodepaycodeidtagtagid-get
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
        name: PayCodeId
        description: The pay code unique identifier
      - in: path
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
      - Tag
    put:
      summary: Insert pay code tag
      description: Inserts a new tag on the pay code
      operationId: PutPayCodeTag
      x-api-path-slug: employeremployeridpaycodepaycodeidtagtagid-put
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
        name: PayCodeId
        description: The pay code unique identifier
      - in: path
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Insert
      - Pay
      - Code
      - Tag
  /Employer/{EmployerId}/PayCode/{PayCodeId}/Tags:
    get:
      summary: Get all pay code tags
      description: Gets all the tags from the pay code
      operationId: GetTagsFromPayCode
      x-api-path-slug: employeremployeridpaycodepaycodeidtags-get
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
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
      - Tags
  /Employer/{EmployerId}/PayCode/{PayCodeId}/{EffectiveDate}:
    delete:
      summary: Deletes a pay code revision
      description: Delete the pay code revision for the specified date
      operationId: DeletePayCodeRevision
      x-api-path-slug: employeremployeridpaycodepaycodeideffectivedate-delete
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EffectiveDate
        description: The effective date to be applied
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
      - Revision
    get:
      summary: Gets pay code for specified date
      description: Gets the pay code revision for the specified effective date
      operationId: GetPayCodeByEffectiveDate
      x-api-path-slug: employeremployeridpaycodepaycodeideffectivedate-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EffectiveDate
        description: The effective date to be applied
      - in: path
        name: EmployerId
        description: The employers unique identifier
      - in: path
        name: PayCodeId
        description: The pay code unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Codespecified
      - Date
  /Employer/{EmployerId}/PayCodes:
    get:
      summary: Gets the pay codes from the employer
      description: Get links to all the pay codes for the specified employer
      operationId: GetPayCodesFromEmployer
      x-api-path-slug: employeremployeridpaycodes-get
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
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Codes
      - From
      - Employer
    post:
      summary: Create a new pay code
      description: Create a new pay code object
      operationId: PostPayCode
      x-api-path-slug: employeremployeridpaycodes-post
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
        name: PayCode
        description: The pay code object
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - New
      - Pay
      - Code
  /Employer/{EmployerId}/PayCodes/Tag/{TagId}:
    get:
      summary: Get pay codes with tag
      description: Gets the pay codes with the tag
      operationId: GetPayCodesWithTag
      x-api-path-slug: employeremployeridpaycodestagtagid-get
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
        name: TagId
        description: The tag unique identifier
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Codes
      - Tag
  /Employer/{EmployerId}/PayCodes/Tags:
    get:
      summary: Get all pay code tags
      description: Gets all the pay code tags
      operationId: GetAllPayCodeTags
      x-api-path-slug: employeremployeridpaycodestags-get
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
      responses:
        200:
          description: OK
      tags:
      - Pay
      - Code
      - Tags
  /Employer/{EmployerId}/PayCodes/{EffectiveDate}:
    get:
      summary: Gets all pay codes for specified date
      description: Gets the effective pay code revision for the specified date
      operationId: GetPayCodesByEffectiveDate
      x-api-path-slug: employeremployeridpaycodeseffectivedate-get
      parameters:
      - in: header
        name: Api-Version
        description: The version of the api to target
      - in: header
        name: Authorization
        description: The OAuth 1 authorization header
      - in: path
        name: EffectiveDate
        description: The effective date to be applied
      - in: path
        name: EmployerId
        description: The employers unique identifier
      responses:
        200:
          description: OK
      tags:
      - ""
      - Pay
      - Codesspecified
      - Date
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