---
swagger: "2.0"
x-collection-name: CallFire
x-complete: 0
info:
  title: Callfire Verify a caller id
  description: With the verification code received from the Create caller id endpoint,
    a call to this endpoint is required to finish verification
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