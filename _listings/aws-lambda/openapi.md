---
swagger: "2.0"
x-collection-name: AWS Lambda
x-complete: 1
info:
  title: AWS Lambda API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=UpdateFunctionCode:
    get:
      summary: Update Function Code
      description: Updates the code for the specified Lambda function.
      operationId: updateFunctionCode
      x-api-path-slug: actionupdatefunctioncode-get
      parameters:
      - in: query
        name: FunctionName
        description: The existing Lambda function name whose code you want to replace
        type: string
      responses:
        200:
          description: OK
      tags:
      - Functions
---