---
swagger: "2.0"
x-collection-name: AWS Internet of Things
x-complete: 0
info:
  title: AWS Internet of Things API Get Registration Code
  version: 1.0.0
  description: Gets a registration code used to register a CA certificate with AWS
    IoT.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteRegistrationCode:
    get:
      summary: Delete Registration Code
      description: Deletes a CA certificate registration code.
      operationId: deleteRegistrationCode
      x-api-path-slug: actiondeleteregistrationcode-get
      responses:
        200:
          description: OK
      tags:
      - Registration Codes
  /?Action=GetRegistrationCode:
    get:
      summary: Get Registration Code
      description: Gets a registration code used to register a CA certificate with
        AWS IoT.
      operationId: getRegistrationCode
      x-api-path-slug: actiongetregistrationcode-get
      parameters:
      - in: query
        name: registrationCode
        description: The CA certificate registration code
        type: string
      responses:
        200:
          description: OK
      tags:
      - Registration Codes
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