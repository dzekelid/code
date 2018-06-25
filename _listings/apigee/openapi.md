---
swagger: "2.0"
x-collection-name: Apigee
x-complete: 1
info:
  title: Apigee Edge
  description: restful-management-api-to-create-configure-and-manage-api-proxies-and-api-products-create-and-manage-apps-and-app-developers-and-more-
  version: 1.0.0
host: api.enterprise.apigee.com
basePath: /v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /organizations/{org_name}/oauth1/verifiers/{verifier_code}:
    get:
      summary: Get Organizations Name Oauth1 Verifiers Verifier Code
      description: Gets the detail of given verifier code.
      operationId: getOrganizationsOrgNameOauth1VerifiersVerifierCode
      x-api-path-slug: organizationsorg-nameoauth1verifiersverifier-code-get
      parameters:
      - in: path
        name: org_name
        description: Mention the organization name
      - in: path
        name: verifier_code
        description: Mention the verifier code
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Oauth1
      - Verifiers
      - Verifier
      - Code
    delete:
      summary: Delete Organizations Name Oauth1 Verifiers Verifier Code
      description: Deletes the specified verifier code, which is the verifier code
        given by the provider.
      operationId: deleteOrganizationsOrgNameOauth1VerifiersVerifierCode
      x-api-path-slug: organizationsorg-nameoauth1verifiersverifier-code-delete
      parameters:
      - in: path
        name: org_name
        description: Mention the organization name
      - in: path
        name: verifier_code
        description: Mention the verifier code
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Oauth1
      - Verifiers
      - Verifier
      - Code
  /organizations/{org_name}/oauth2/authorizationcodes/{authorization_code}:
    get:
      summary: Get Organizations Name Oauth2 Authorizationcodes Authorization Code
      description: Get a specific Authorization Code.
      operationId: getOrganizationsOrgNameOauth2AuthorizationcodesAuthorizationCode
      x-api-path-slug: organizationsorg-nameoauth2authorizationcodesauthorization-code-get
      parameters:
      - in: path
        name: authorization_code
        description: Mention the auth code
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Oauth2
      - Authorizationcodes
      - Authorization
      - Code
    delete:
      summary: Delete Organizations Name Oauth2 Authorizationcodes Authorization Code
      description: Deletes the given authorization Code.
      operationId: deleteOrganizationsOrgNameOauth2AuthorizationcodesAuthorizationCode
      x-api-path-slug: organizationsorg-nameoauth2authorizationcodesauthorization-code-delete
      parameters:
      - in: path
        name: authorization_code
        description: Mention the auth code
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Oauth2
      - Authorizationcodes
      - Authorization
      - Code
  /organizations/{org_name}/oauth2/authorizationcodes:
    get:
      summary: Get Organizations Name Oauth2 Authorizationcodes
      description: Lists all authorization codes in an organization.
      operationId: getOrganizationsOrgNameOauth2Authorizationcodes
      x-api-path-slug: organizationsorg-nameoauth2authorizationcodes-get
      parameters:
      - in: path
        name: org_name
        description: Mention the organization name
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Oauth2
      - Authorizationcodes
---