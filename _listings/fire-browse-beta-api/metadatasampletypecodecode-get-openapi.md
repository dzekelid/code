---
swagger: "2.0"
x-collection-name: Fire Browse Beta API
x-complete: 0
info:
  title: Fire Browse Beta API Translate from numeric to symbolic TCGA sample codes.
  description: Convert a TCGA numeric sample type code (e.g. 01, 02) to its corresponding
    symbolic (short letter) code (e.g. TP, TR).
  version: 1.1.35 (2016-09-27 10:12:23 6a47e74011281b2aa
host: firebrowse.org
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Metadata/SampleType/Barcode/{TCGA_Barcode}:
    get:
      summary: Given a TCGA barcode, return its short letter sample type code.
      description: Given a tcga barcode, return its short letter sample type code..
      operationId: getMetadataSampletypeBarcodeTcgaBarcode
      x-api-path-slug: metadatasampletypebarcodetcga-barcode-get
      parameters:
      - in: query
        name: format
        description: Format of result
      - in: path
        name: TCGA_Barcode
        description: 'Enter a single TCGA barcode, of any form: e'
      responses:
        200:
          description: OK
      tags:
      - Metadata
      - SampleType
      - Barcode
      - TCGA
      - Barcode
  /Metadata/SampleType/Code/{code}:
    get:
      summary: Translate from numeric to symbolic TCGA sample codes.
      description: Convert a TCGA numeric sample type code (e.g. 01, 02) to its corresponding
        symbolic (short letter) code (e.g. TP, TR).
      operationId: getMetadataSampletypeCodeCode
      x-api-path-slug: metadatasampletypecodecode-get
      parameters:
      - in: path
        name: code
        description: Narrow search to one or more TCGA sample type codes
      - in: query
        name: format
        description: Format of result
      responses:
        200:
          description: OK
      tags:
      - Metadata
      - SampleType
      - Code
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