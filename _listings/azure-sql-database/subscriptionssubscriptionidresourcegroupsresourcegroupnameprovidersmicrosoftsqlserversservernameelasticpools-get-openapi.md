---
swagger: "2.0"
x-collection-name: Azure SQL Database
x-complete: 0
info:
  title: Azure SQL Database API Elastic Pools List By Server
  description: Returns a list of elastic pools in a server.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/elasticPools/{elasticPoolName}
  : put:
      summary: Elastic Pools Create Or Update
      description: Creates a new elastic pool or updates an existing elastic pool.
      operationId: ElasticPools_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolname-put
      parameters:
      - in: path
        name: elasticPoolName
        description: The name of the elastic pool to be operated on (updated or created)
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The required parameters for creating or updating an elastic pool
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Elastic Pools
    delete:
      summary: Elastic Pools Delete
      description: Deletes the elastic pool.
      operationId: ElasticPools_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolname-delete
      parameters:
      - in: path
        name: elasticPoolName
        description: The name of the elastic pool to be deleted
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Elastic Pools
    get:
      summary: Elastic Pools Get
      description: Gets an elastic pool.
      operationId: ElasticPools_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpoolselasticpoolname-get
      parameters:
      - in: path
        name: elasticPoolName
        description: The name of the elastic pool to be retrieved
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Elastic Pools
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Sql/servers/{serverName}/elasticPools:
    get:
      summary: Elastic Pools List By Server
      description: Returns a list of elastic pools in a server.
      operationId: ElasticPools_ListByServer
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftsqlserversservernameelasticpools-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Elastic Pools Server
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