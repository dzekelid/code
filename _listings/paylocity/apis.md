---
name: Paylocity
x-slug: paylocity
description: ""
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Code
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/apis.md
specificationVersion: "0.14"
apis:
- name: Paylocity Get Earnings by Earning Code
  x-api-slug: paylocity
  description: Get Earnings returns all earnings with the provided earning code for
    the selected employee.
  image: ""
  humanURL: http://paylocity.com
  baseURL: https://api.paylocity.com//api//v2/companies/{companyId}/employees/{employeeId}/earnings/{earningCode}
  tags: V2,Companies,CompanyId,Employees,EmployeeId,Earnings,EarningCode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/v2companiescompanyidemployeesemployeeidearningsearningcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/v2companiescompanyidemployeesemployeeidearningsearningcode-get-openapi.md
- name: Paylocity Delete Earning by Earning Code and Start Date
  x-api-slug: paylocity
  description: Delete Earning by Earning Code and Start Date
  image: ""
  humanURL: http://paylocity.com
  baseURL: https://api.paylocity.com//api//v2/companies/{companyId}/employees/{employeeId}/earnings/{earningCode}/{startDate}
  tags: V2,Companies,CompanyId,Employees,EmployeeId,Earnings,EarningCode,StartDate
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/v2companiescompanyidemployeesemployeeidearningsearningcodestartdate-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/v2companiescompanyidemployeesemployeeidearningsearningcodestartdate-delete-openapi.md
- name: Paylocity Get Earning by Earning Code and Start Date
  x-api-slug: paylocity
  description: Get Earnings returns the single earning with the provided earning code
    and start date for the selected employee.
  image: ""
  humanURL: http://paylocity.com
  baseURL: https://api.paylocity.com//api//v2/companies/{companyId}/employees/{employeeId}/earnings/{earningCode}/{startDate}
  tags: V2,Companies,CompanyId,Employees,EmployeeId,Earnings,EarningCode,StartDate
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/v2companiescompanyidemployeesemployeeidearningsearningcodestartdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/v2companiescompanyidemployeesemployeeidearningsearningcodestartdate-get-openapi.md
- name: Paylocity Delete local tax by tax code
  x-api-slug: paylocity
  description: Delete local tax by tax code
  image: ""
  humanURL: http://paylocity.com
  baseURL: https://api.paylocity.com//api//v2/companies/{companyId}/employees/{employeeId}/localTaxes/{taxCode}
  tags: V2,Companies,CompanyId,Employees,EmployeeId,LocalTaxes,TaxCode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/v2companiescompanyidemployeesemployeeidlocaltaxestaxcode-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/v2companiescompanyidemployeesemployeeidlocaltaxestaxcode-delete-openapi.md
- name: Paylocity Get local taxes by tax code
  x-api-slug: paylocity
  description: Returns all local taxes with the provided tax code for the selected
    employee.
  image: ""
  humanURL: http://paylocity.com
  baseURL: https://api.paylocity.com//api//v2/companies/{companyId}/employees/{employeeId}/localTaxes/{taxCode}
  tags: V2,Companies,CompanyId,Employees,EmployeeId,LocalTaxes,TaxCode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/v2companiescompanyidemployeesemployeeidlocaltaxestaxcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/v2companiescompanyidemployeesemployeeidlocaltaxestaxcode-get-openapi.md
- name: Paylocity
  x-api-slug: paylocity
  description: ""
  image: ""
  humanURL: http://paylocity.com
  baseURL: https://api.paylocity.com//api
  tags: Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/paylocity/openapi.md
x-common:
- type: x-blog
  url: https://www.paylocity.com/resources/blog/
- type: x-github
  url: https://github.com/Paylocity
- type: x-integrations
  url: https://www.paylocity.com/partnerships/integrations/
- type: x-twitter
  url: https://twitter.com/Paylocity
- type: x-website
  url: http://paylocity.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---