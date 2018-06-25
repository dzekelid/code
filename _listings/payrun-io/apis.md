---
name: PayRun.io
x-slug: payrun-io
description: An open, scalable, transparent and HMRC accredited payroll API. Put the
  power of payroll into your application today.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
x-kinRank: "7"
x-alexaRank: "0"
tags: Code
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/apis.md
specificationVersion: "0.14"
apis:
- name: Pay Run.IO Deletes the nominal codes
  x-api-slug: pay-run-io
  description: Deletes the nominal code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/NominalCode/{NominalCodeId}
  tags: Nominal,Codes
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridnominalcodenominalcodeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridnominalcodenominalcodeid-delete-openapi.md
- name: Pay Run.IO Gets the nominal code
  x-api-slug: pay-run-io
  description: Gets the nominal code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/NominalCode/{NominalCodeId}
  tags: Nominal,Code
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridnominalcodenominalcodeid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridnominalcodenominalcodeid-get-openapi.md
- name: Pay Run.IO Insert nominal code
  x-api-slug: pay-run-io
  description: Inserts a new nominal code at the specified resource location
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/NominalCode/{NominalCodeId}
  tags: Insert,Nominal,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridnominalcodenominalcodeid-put-openapi.md
- name: Pay Run.IO Gets the nominal codes
  x-api-slug: pay-run-io
  description: Gets the nominal code links
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/NominalCodes
  tags: Nominal,Codes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridnominalcodes-get-openapi.md
- name: Pay Run.IO Insert nominal code
  x-api-slug: pay-run-io
  description: Inserts a new nominal code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/NominalCodes
  tags: Insert,Nominal,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridnominalcodes-post-openapi.md
- name: Pay Run.IO Deletes a pay code
  x-api-slug: pay-run-io
  description: Delete the specified pay code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}
  tags: Pay,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodepaycodeid-delete-openapi.md
- name: Pay Run.IO Gets the specified pay code from the employer
  x-api-slug: pay-run-io
  description: Returns the specified pay code from the employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}
  tags: Specified,Pay,Code,From,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodepaycodeid-get-openapi.md
- name: Pay Run.IO Patches the pay code
  x-api-slug: pay-run-io
  description: Patches the specified pay code object with the supplied values
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}
  tags: Patches,Pay,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodepaycodeid-patch-openapi.md
- name: Pay Run.IO Updates a pay code
  x-api-slug: pay-run-io
  description: Updates the existing specified pay code object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}
  tags: Pay,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodepaycodeid-put-openapi.md
- name: Pay Run.IO Delete pay code tag
  x-api-slug: pay-run-io
  description: Deletes a tag from the pay code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/Tag/{TagId}
  tags: Pay,Code,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodepaycodeidtagtagid-delete-openapi.md
- name: Pay Run.IO Get pay code tag
  x-api-slug: pay-run-io
  description: Gets the tag from the pay code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/Tag/{TagId}
  tags: Pay,Code,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodepaycodeidtagtagid-get-openapi.md
- name: Pay Run.IO Insert pay code tag
  x-api-slug: pay-run-io
  description: Inserts a new tag on the pay code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/Tag/{TagId}
  tags: Insert,Pay,Code,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodepaycodeidtagtagid-put-openapi.md
- name: Pay Run.IO Get all pay code tags
  x-api-slug: pay-run-io
  description: Gets all the tags from the pay code
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/Tags
  tags: Pay,Code,Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodepaycodeidtags-get-openapi.md
- name: Pay Run.IO Deletes a pay code revision
  x-api-slug: pay-run-io
  description: Delete the pay code revision for the specified date
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/{EffectiveDate}
  tags: Pay,Code,Revision
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodepaycodeideffectivedate-delete-openapi.md
- name: Pay Run.IO Gets pay code for specified date
  x-api-slug: pay-run-io
  description: Gets the pay code revision for the specified effective date
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCode/{PayCodeId}/{EffectiveDate}
  tags: Pay,Codespecified,Date
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodepaycodeideffectivedate-get-openapi.md
- name: Pay Run.IO Gets the pay codes from the employer
  x-api-slug: pay-run-io
  description: Get links to all the pay codes for the specified employer
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCodes
  tags: Pay,Codes,From,Employer
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodes-get-openapi.md
- name: Pay Run.IO Create a new pay code
  x-api-slug: pay-run-io
  description: Create a new pay code object
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCodes
  tags: New,Pay,Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodes-post-openapi.md
- name: Pay Run.IO Get pay codes with tag
  x-api-slug: pay-run-io
  description: Gets the pay codes with the tag
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCodes/Tag/{TagId}
  tags: Pay,Codes,Tag
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodestagtagid-get-openapi.md
- name: Pay Run.IO Get all pay code tags
  x-api-slug: pay-run-io
  description: Gets all the pay code tags
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCodes/Tags
  tags: Pay,Code,Tags
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodestags-get-openapi.md
- name: Pay Run.IO Gets all pay codes for specified date
  x-api-slug: pay-run-io
  description: Gets the effective pay code revision for the specified date
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Employer/{EmployerId}/PayCodes/{EffectiveDate}
  tags: ',Pay,Codesspecified,Date'
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/employeremployeridpaycodeseffectivedate-get-openapi.md
- name: Pay Run.IO Gets the pay code template
  x-api-slug: pay-run-io
  description: Return the pay code data object template
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io////Templates/paycode
  tags: Pay,Code,Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/templatespaycode-get-openapi.md
- name: Pay Run.IO
  x-api-slug: pay-run-io
  description: An open, scalable, transparent and HMRC accredited payroll API. Put
    the power of payroll into your application today.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28484-payrun-io.jpg
  humanURL: http://www.payrun.io
  baseURL: https://api.test.payrun.io//
  tags: Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/payrun-io/openapi.md
x-common:
- type: x-website
  url: http://www.payrun.io
- type: x-documentation
  url: https://developer.payrun.io/docs/home/index.html
- type: x-email
  url: support@payrun.io
- type: x-email
  url: info@payrun.io
- type: x-twitter
  url: https://twitter.com/PayRun_io
- type: x-website
  url: http://api.test.payrun.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---