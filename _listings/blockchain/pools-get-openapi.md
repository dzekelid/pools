---
swagger: "2.0"
x-collection-name: Blockchain
x-complete: 0
info:
  title: Blockchain Info Pools
  description: This method can be used to get the data behind Blockchain.info's pools
    information.
  version: 1.0.0
host: blockchain.info
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /pools:
    get:
      summary: Pools
      description: This method can be used to get the data behind Blockchain.info's
        pools information.
      operationId: getPools
      x-api-path-slug: pools-get
      parameters:
      - in: query
        name: timespan
        description: Duration over which the data is computed, maximum 10 days, default
          is 4 days (ie
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Pools
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