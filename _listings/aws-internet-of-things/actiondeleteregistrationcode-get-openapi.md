---
swagger: "2.0"
x-collection-name: AWS Internet of Things
x-complete: 0
info:
  title: AWS Internet of Things API Delete Registration Code
  version: 1.0.0
  description: Deletes a CA certificate registration code.
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