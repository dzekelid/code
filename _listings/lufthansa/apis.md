---
name: Lufthansa
x-slug: lufthansa
description: Book your flights to Germany, Italy, UK or France online at attractive
  low fares. Fly via Frankfurt, Munich or Zurich - Lufthansa United States of America
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
x-kinRank: "7"
x-alexaRank: "3886"
tags: Code
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/apis.md
specificationVersion: "0.14"
apis:
- name: LH Public Retrieve all flights
  x-api-slug: lh-public
  description: Retrieve a list of all possible flights (both direct and connecting)
    between two airports on a given date. Routes are available for today and up to
    days in the future.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1//cargo/getRoute/{origin}-{destination}/{fromDate}/{productCode}
  tags: Cargo,GetRoute,Origin,Destination,FromDate,ProductCode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/cargogetrouteorigindestinationfromdateproductcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/cargogetrouteorigindestinationfromdateproductcode-get-openapi.md
- name: LH Public Flight Status at Arrival Airport
  x-api-slug: lh-public
  description: Status of all arrivals at a given airport up to 4 hours from the provided
    date time.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1//operations/flightstatus/arrivals/{airportCode}/{fromDateTime}
  tags: Operations,Flightstatus,Arrivals,AirportCode,FromDateTime
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/operationsflightstatusarrivalsairportcodefromdatetime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/operationsflightstatusarrivalsairportcodefromdatetime-get-openapi.md
- name: LH Public Flight Status at Departure Airport
  x-api-slug: lh-public
  description: Status of all departures from a given airport up to 4 hours from the
    provided date time.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1//operations/flightstatus/departures/{airportCode}/{fromDateTime}
  tags: Operations,Flightstatus,Departures,AirportCode,FromDateTime
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/operationsflightstatusdeparturesairportcodefromdatetime-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/operationsflightstatusdeparturesairportcodefromdatetime-get-openapi.md
- name: LH Public Aircraft
  x-api-slug: lh-public
  description: List all aircraft types or one specific aircraft type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1//references/aircraft/{aircraftCode}
  tags: References,Aircraft,AircraftCode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/referencesaircraftaircraftcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/referencesaircraftaircraftcode-get-openapi.md
- name: LH Public Airlines
  x-api-slug: lh-public
  description: List all airlines or one specific airline.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1//references/airlines/{airlineCode}
  tags: References,Airlines,AirlineCode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/referencesairlinesairlinecode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/referencesairlinesairlinecode-get-openapi.md
- name: LH Public Airports
  x-api-slug: lh-public
  description: List all airports or one specific airport. All airports response is
    very large. It is possible to request the response in a specific language.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1//references/airports/{airportCode}
  tags: References,Airports,AirportCode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/referencesairportsairportcode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/referencesairportsairportcode-get-openapi.md
- name: LH Public Cities
  x-api-slug: lh-public
  description: List all cities or one specific city. It is possible to request the
    response in a specific language.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1//references/cities/{cityCode}
  tags: References,Cities,CityCode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/referencescitiescitycode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/referencescitiescitycode-get-openapi.md
- name: LH Public Countries
  x-api-slug: lh-public
  description: List all countries or one specific country. It is possible to request
    the response in a specific language.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1//references/countries/{countryCode}
  tags: References,Countries,CountryCode
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/referencescountriescountrycode-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/referencescountriescountrycode-get-openapi.md
- name: LH Public
  x-api-slug: lh-public
  description: Book your flights to Germany, Italy, UK or France online at attractive
    low fares. Fly via Frankfurt, Munich or Zurich - Lufthansa United States of America
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28453-lh-partner.jpg
  humanURL: http://lufthansa.com
  baseURL: https://api.lufthansa.com//v1
  tags: Code
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/code/master/_listings/lufthansa/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/lufthansa
- type: x-twitter
  url: https://twitter.com/lufthansa
- type: x-website
  url: http://lufthansa.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---