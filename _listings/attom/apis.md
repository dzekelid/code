---
name: ATTOM
x-slug: attom
description: 'Search public property records including real estate data: sale, ownership,
  tax, and more - for more than 150 million U.S. properties. ATTOM Data Solutions
  is the curator of ATTOM, a multi-sourced national property data warehouse that contains
  tax, deed, mortgage, foreclosure, environmental risk, natural hazard, health hazard,
  neighborhood characteristic and property characteristic data for over 155 million
  U.S. properties, delivering actionable data to clients and powering consumer websites
  owned by ATTOM Data Solutions: RealtyTrac.com, Homefacts.com, and HomeDisclosure.com.'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28881-api-developer-attomdata-com.jpg
x-kinRank: "7"
x-alexaRank: "359677"
tags: Code
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/attom/apis.md
specificationVersion: "0.14"
apis:
- name: Attom Data Solutions API - Returns properties within a zip code.
  x-api-slug: propertyaddress-get
  description: Get a list of properties within a zip code. Use propertytype and order
    by to narrow down your results.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28881-api-developer-attomdata-com.jpg
  humanURL: https://api.developer.attomdata.com
  baseURL: https://search.onboard-apis.com//communityapi/v2.0.0
  tags: SaaS, Technology, Enterprise, Real Estate, Places, Schools, Properties, General
    Data, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/attom/propertyaddress-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/attom/propertyaddress-get-openapi.md
- name: Attom Data Solutions API - Returns assessment details for properties within
    a zip code.
  x-api-slug: assessmentdetail-get
  description: Get assessment details for properties within a zip code. Use propertytpe
    to select a specific property type for your search.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28881-api-developer-attomdata-com.jpg
  humanURL: https://api.developer.attomdata.com
  baseURL: https://search.onboard-apis.com//communityapi/v2.0.0
  tags: SaaS, Technology, Enterprise, Real Estate, Places, Schools, Properties, General
    Data, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/attom/assessmentdetail-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/attom/assessmentdetail-get-openapi.md
- name: Attom Data Solutions API - Returns sales trends for a given zip code in yearly
    intervals
  x-api-slug: salestrendsnapshot-get
  description: Get the average sale price, median sale price, and count of sales for
    the past 2 years in yearly intervals.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28881-api-developer-attomdata-com.jpg
  humanURL: https://api.developer.attomdata.com
  baseURL: https://search.onboard-apis.com//communityapi/v2.0.0
  tags: SaaS, Technology, Enterprise, Real Estate, Places, Schools, Properties, General
    Data, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/attom/salestrendsnapshot-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/attom/salestrendsnapshot-get-openapi.md
- name: Attom Data Solutions API - Returns POIs based on zip code.
  x-api-slug: poigeography-get
  description: This search returns a list of Points of Interest in proximity to the
    centroid of a zip code.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28881-api-developer-attomdata-com.jpg
  humanURL: https://api.developer.attomdata.com
  baseURL: https://search.onboard-apis.com//communityapi/v2.0.0
  tags: SaaS, Technology, Enterprise, Real Estate, Places, Schools, Properties, General
    Data, Historical Data API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/attom/poigeography-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/attom/poigeography-get-openapi.md
x-common:
- type: x-openapi
  url: https://api.developer.attomdata.com/swagger/spec/propertyapi_property.json
- type: x-api-gallery
  url: http://atlassian.api.gallery.streamdata.io
- type: x-api-stack
  url: http://attom.stack.network
- type: x-email
  url: privacy@attomdata.com
- type: x-twitter
  url: https://twitter.com/Attomdata
- type: x-website
  url: https://api.developer.attomdata.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---