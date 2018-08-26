---
swagger: "2.0"
x-collection-name: Okta
x-complete: 1
info:
  title: Users (Okta API)
  description: the-okta-user-apidocsapirestusers-html-provides-operations-to-manage-users-in-your-organization-
  version: 1.0.0
host: example.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{userId}/credentials/forgot_password:
    post:
      summary: Forgot Password (One Time Code)
      description: Forgot password (one time code).
      operationId: postUsersUserCredentialsForgotPassword
      x-api-path-slug: usersuseridcredentialsforgot-password-post
      parameters:
      - in: header
        name: Accept
      - in: header
        name: Content-Type
      - in: query
        name: sendEmail
      - in: path
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Forgot
      - Password
      - (One
      - Time
      - Code)
---