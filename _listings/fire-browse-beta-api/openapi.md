---
swagger: "2.0"
x-collection-name: Fire Browse Beta API
x-complete: 1
info:
  title: Fire Browse Beta API
  description: a-simple-and-elegant-way-to-explore-cancer-data
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
  /Metadata/SampleType/ShortLetterCode/{short_letter_code}:
    get:
      summary: Translate from symbolic to numeric TCGA sample codes.
      description: Convert a TCGA sample type code in symbolic form (or 'short letter
        code' like TP, TR) to its corresponding numeric form (e.g. 01, 02).
      operationId: getMetadataSampletypeShortlettercodeShortLetterCode
      x-api-path-slug: metadatasampletypeshortlettercodeshort-letter-code-get
      parameters:
      - in: query
        name: format
        description: Format of result
      - in: path
        name: short_letter_code
        description: TCGA sample type short letter code(s) (e
      responses:
        200:
          description: OK
      tags:
      - Metadata
      - SampleType
      - ShortLetterCode
      - Short
      - Letter
      - Code
---