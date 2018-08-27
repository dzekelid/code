---
name: Azure Blockchain Workbench
x-slug: azure-blockchain-workbench
description: Azure Blockchain Workbench helps organizations build rich, integrated
  multi-party blockchain applications quickly and easily. Azure Blockchain Workbench
  REST API provides developers and information workers a way to integrate to blockchain
  applications. For example, a developer can use the REST API to enable IoT devices
  to send data to a blockchain application. Or, an information worker can use the
  REST API and Power BI to create visualization of blockchain data.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
x-kinRank: "7"
x-alexaRank: ""
tags: Code
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/azure-blockchain-workbench/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Blockchain Workbench REST API - Get Applications Contract Code
  x-api-slug: apiv1applicationscontractcodecontractcodeid-get
  description: |-
    Get the blockchain smart contract implementation matching a specific
                 contract code id. Users who are Workbench administrators get the specified smart contract implementation.
                 Non-Workbench administrators get the smart contract implementation if they have at least one associated application
                 role or is associated with a smart contract instance role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/azure-blockchain-workbench/apiv1applicationscontractcodecontractcodeid-get-openapi.md
- name: Azure Blockchain Workbench REST API - Delete Applications Contract Code
  x-api-slug: apiv1applicationscontractcodecontractcodeid-delete
  description: |-
    Deletes the specified blockchain smart contract implementation of a specific blockchain application.
                 This method can only be performed by users who are Workbench administrators.
                 NOTE: not currently implemented
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/azure-blockchain-workbench/apiv1applicationscontractcodecontractcodeid-delete-openapi.md
- name: Azure Blockchain Workbench REST API - Get Applications Contract Code
  x-api-slug: apiv1applicationsapplicationidcontractcode-get
  description: |-
    List all blockchain smart contract implementations of the specified blockchain application.
                 Users who are Workbench administrators get all smart contract implementations. Non-Workbench administrators get all
                 smart contract implementations for which they have at least one associated application role or is associated with a
                 smart contract instance role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidcontractcode-get-openapi.md
- name: Azure Blockchain Workbench REST API - Post Applications Contract Code
  x-api-slug: apiv1applicationsapplicationidcontractcode-post
  description: |-
    Uploads one or more smart contracts (ex. .sol or .zip), representing the implementation of the specified blockchain
                 application. This method can only be performed by users who are Workbench administrators.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/azure-blockchain-workbench/apiv1applicationsapplicationidcontractcode-post-openapi.md
- name: Azure Blockchain Workbench REST API - Post Checkers Check Contract Node
  x-api-slug: apiv1checkerscheckcontractcode-post
  description: Check if the application smart contract implementation file is valid
    for Workbench.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-blockchain.png
  humanURL: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
  baseURL: https:////
  tags: Blockchain, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/azure-blockchain-workbench/apiv1checkerscheckcontractcode-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/azure-blockchain-workbench/apiv1checkerscheckcontractcode-post-openapi.md
x-common:
- type: x-blog
  url: https://azure.microsoft.com/en-us/blog/topics/blockchain/
- type: x-blog-rss
  url: https://azurecomcdn.azureedge.net/en-us/blog/topics/blockchain/feed/
- type: x-openapi
  url: https://raw.githubusercontent.com/Azure-Samples/blockchain/master/blockchain-workbench/rest-api-samples/swagger/swagger.json
- type: x-website
  url: https://docs.microsoft.com/en-us/rest/api/azure-blockchain-workbench/
- type: x-api-gallery
  url: http://azure.billing.api.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.blockchain.workbench.stack.network
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---