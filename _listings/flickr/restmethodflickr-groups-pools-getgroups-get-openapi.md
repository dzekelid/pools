---
swagger: "2.0"
x-collection-name: Flickr
x-complete: 0
info:
  title: Flickr Groups Pools Get Groups
  description: Returns a list of groups to which you can add photos.
  version: 1.0.0
host: api.flickr.com
basePath: /services/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/?method=flickr.groups.pools.add:
    post:
      summary: Groups Pools Add
      description: Add a photo to a group's pool.
      operationId: postRestMethodFlickr.groups.pools.add
      x-api-path-slug: restmethodflickr-groups-pools-add-post
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: group_id
        description: The NSID of the group whose pool the photo is to be added to
      - in: query
        name: photo_id
        description: The id of the photo to add to the group pool
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Pools
      - Add
  /rest/?method=flickr.groups.pools.getContext:
    get:
      summary: Groups Pools Get Context
      description: Returns next and previous photos for a photo in a group pool.
      operationId: getRestMethodFlickr.groups.pools.getcontext
      x-api-path-slug: restmethodflickr-groups-pools-getcontext-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: group_id
        description: The NSID of the group whose pool to fetch the photos context
          for
      - in: query
        name: photo_id
        description: The id of the photo to fetch the context for
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Pools
      - GetContext
  /rest/?method=flickr.groups.pools.getGroups:
    get:
      summary: Groups Pools Get Groups
      description: Returns a list of groups to which you can add photos.
      operationId: getRestMethodFlickr.groups.pools.getgroups
      x-api-path-slug: restmethodflickr-groups-pools-getgroups-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: format
        description: Response format
      - in: query
        name: page
        description: The page of results to return
      - in: query
        name: per_page
        description: Number of groups to return per page
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Pools
      - GetGroups
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