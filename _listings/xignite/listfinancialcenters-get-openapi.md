---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 0
info:
  title: Xignite Global Holidays List Financial Centers
  description: List financial centers.
  version: 1.0.0
host: globalholidays.xignite.com
basePath: xGlobalHolidays.json/XigniteGlobalHolidays
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /ListFinancialCenters:
    get:
      summary: List Financial Centers
      description: List financial centers.
      operationId: ListFinancialCenters
      x-api-path-slug: listfinancialcenters-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - List
      - Financial
      - Centers
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