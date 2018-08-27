---
swagger: "2.0"
x-collection-name: Azure Blockchain Workbench
x-complete: 0
info:
  title: Azure Blockchain Workbench Get Applications Contract Code
  description: |-
    Get the blockchain smart contract implementation matching a specific
                 contract code id. Users who are Workbench administrators get the specified smart contract implementation.
                 Non-Workbench administrators get the smart contract implementation if they have at least one associated application
                 role or is associated with a smart contract instance role.
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/applications/{applicationId}/contractCode:
    get:
      summary: Get Applications Contract Code
      description: |-
        List all blockchain smart contract implementations of the specified blockchain application.
                     Users who are Workbench administrators get all smart contract implementations. Non-Workbench administrators get all
                     smart contract implementations for which they have at least one associated application role or is associated with a
                     smart contract instance role.
      operationId: ContractCodesGet
      x-api-path-slug: apiv1applicationsapplicationidcontractcode-get
      parameters:
      - in: path
        name: applicationId
        description: The id of the application
      - in: query
        name: ledgerId
        description: The index of the chain type
      - in: query
        name: skip
        description: The number of items to skip before returning
      - in: query
        name: top
        description: The maximum number of items to return
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Contract
      - Code
    post:
      summary: Post Applications Contract Code
      description: |-
        Uploads one or more smart contracts (ex. .sol or .zip), representing the implementation of the specified blockchain
                     application. This method can only be performed by users who are Workbench administrators.
      operationId: ContractCodePost
      x-api-path-slug: apiv1applicationsapplicationidcontractcode-post
      parameters:
      - in: path
        name: applicationId
        description: The id of the application
      - in: formData
        name: contractFile
        description: Upload ContractCode File
      - in: query
        name: ledgerId
        description: The index of the ledger
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Contract
      - Code
  /api/v1/applications/contractCode/{contractCodeId}:
    get:
      summary: Get Applications Contract Code
      description: |-
        Get the blockchain smart contract implementation matching a specific
                     contract code id. Users who are Workbench administrators get the specified smart contract implementation.
                     Non-Workbench administrators get the smart contract implementation if they have at least one associated application
                     role or is associated with a smart contract instance role.
      operationId: ContractCodeGet
      x-api-path-slug: apiv1applicationscontractcodecontractcodeid-get
      parameters:
      - in: path
        name: contractCodeId
        description: The id of the contract code
      responses:
        200:
          description: OK
      tags:
      - Applications
      - Contract
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