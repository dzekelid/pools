---
swagger: "2.0"
x-collection-name: AWS Device Farm
x-complete: 0
info:
  title: AWS Device Farm API Delete Device Pool
  version: 1.0.0
  description: Deletes a device pool given the pool ARN.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListDevicePools:
    get:
      summary: List Device Pools
      description: Gets information about device pools.
      operationId: listDevicePools
      x-api-path-slug: actionlistdevicepools-get
      parameters:
      - in: query
        name: arn
        description: The project ARN
        type: string
      - in: query
        name: nextToken
        description: An identifier that was returned from the previous call to this
          operation, which can be used to return the next set of items in the list
        type: string
      - in: query
        name: type
        description: The device pools type
        type: string
      responses:
        200:
          description: OK
      tags:
      - Device Pool
  /?Action=CreateDevicePool:
    get:
      summary: Create Device Pool
      description: Creates a device pool.
      operationId: createDevicePool
      x-api-path-slug: actioncreatedevicepool-get
      parameters:
      - in: query
        name: description
        description: The device pools description
        type: string
      - in: query
        name: name
        description: The device pools name
        type: string
      - in: query
        name: projectArn
        description: The ARN of the project for the device pool
        type: string
      - in: query
        name: rules
        description: The device pools rules
        type: string
      responses:
        200:
          description: OK
      tags:
      - Device Pool
  /?Action=DeleteDevicePool:
    get:
      summary: Delete Device Pool
      description: Deletes a device pool given the pool ARN.
      operationId: deleteDevicePool
      x-api-path-slug: actiondeletedevicepool-get
      parameters:
      - in: query
        name: arn
        description: Represents the Amazon Resource Name (ARN) of the Device Farm
          device pool you wish to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Device Pool
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