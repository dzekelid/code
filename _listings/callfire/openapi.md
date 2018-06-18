---
swagger: "2.0"
x-collection-name: CallFire
x-complete: 1
info:
  title: CallFire
  description: callfire
  termsOfService: https://www.callfire.com/legal/terms
  contact:
    name: CallFire
    url: https://www.callfire.com
    email: support@callfire.com
  version: 1.0.0
host: www.callfire.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /me/callerids/{callerid}/verification-code:
    post:
      summary: Verify a caller id
      description: With the verification code received from the Create caller id endpoint,
        a call to this endpoint is required to finish verification
      operationId: verifyCallerId
      x-api-path-slug: mecalleridscalleridverificationcode-post
      parameters:
      - in: body
        name: body
        description: request
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: callerid
        description: A phone number in E
      responses:
        200:
          description: OK
      tags:
      - Me
      - Callerids
      - Callerid
      - Verification-code
---