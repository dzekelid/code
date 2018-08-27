swagger: "2.0"
x-collection-name: AWS Internet of Things
x-complete: 1
info:
  title: AWS Internet of Things API
  version: 1.0.0
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