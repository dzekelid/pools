---
swagger: "2.0"
x-collection-name: Blockchain
x-complete: 1
info:
  title: Blockchain Info
  description: use-blockchains-apis-at-no-cost-to-help-you-start-building-bitcoin-apps-
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
  /blocks/{pool_name}:
    get:
      summary: Blocks by Pool
      description: Returns the blocks for one pool.
      operationId: getPoolBlocks
      x-api-path-slug: blockspool-name-get
      parameters:
      - in: query
        name: format
        description: The format to return (json,html)
        type: string
        format: string
      - in: path
        name: pool_name
        description: The pool name
        type: string
        format: string
      responses:
        200:
          description: OK
      tags:
      - Blockchain
      - Pools
---