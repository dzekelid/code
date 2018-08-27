---
swagger: "2.0"
x-collection-name: EPA Envirofacts
x-complete: 0
info:
  title: U.S. EPA Enforcement and Compliance History Online (ECHO) - Detailed Facility
    Report (DFR) Detailed Facility Report NAICS Code Service
  description: This procedure obtains data for the Facility NAICS Codes section in
    Facility/System Characteristics of the Detailed Facility Report.
  contact:
    name: US EPA, OECA Integration, Targeting and Access Branch
  version: 0.0.0
host: ofmpub.epa.gov
basePath: /echo
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest_lookups.wbd_code_lu:
    get:
      summary: ECHO WBD Code Lookup Service
      description: USGS Watershed Boundary Dataset (WBD) Name lookup based on a supplied
        WBD Code and Watershed Level
      operationId: usgs-watershed-boundary-dataset-wbd-name-lookup-based-on-a-supplied-wbd-code-and-watershed-level
      x-api-path-slug: rest-lookups-wbd-code-lu-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: output
        description: Output Format Flag
      responses:
        200:
          description: OK
      tags:
      - Environment
      - ECHO
      - WBD
      - Code
      - Lookup
      - Service
  /dfr_rest_services.get_sic_codes:
    get:
      summary: Detailed Facility Report SIC Code Service
      description: This procedure obtains data for the Facility SIC Codes section
        in Facility/System Characteristics of the Detailed Facility Report.
      operationId: this-procedure-obtains-data-for-the-facility-sic-codes-section-in-facilitysystem-characteristics-of-
      x-api-path-slug: dfr-rest-services-get-sic-codes-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - SIC
      - Code
      - Service
  /dfr_rest_services.get_naics:
    get:
      summary: Detailed Facility Report NAICS Code Service
      description: This procedure obtains data for the Facility NAICS Codes section
        in Facility/System Characteristics of the Detailed Facility Report.
      operationId: this-procedure-obtains-data-for-the-facility-naics-codes-section-in-facilitysystem-characteristics-o
      x-api-path-slug: dfr-rest-services-get-naics-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Environment
      - Detailed
      - Facility
      - Report
      - NAICS
      - Code
      - Service
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