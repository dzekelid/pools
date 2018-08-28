swagger: "2.0"
x-collection-name: Flickr
x-complete: 1
info:
  title: Flickr
  description: explore-upload-and-organize-photos-on-flickr
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
  /rest/?method=flickr.groups.pools.getPhotos:
    get:
      summary: Groups Pools Get Photos
      description: Returns a list of pool photos for a given group, based on the permissions
        of the group and the user logged in (if any).
      operationId: getRestMethodFlickr.groups.pools.getphotos
      x-api-path-slug: restmethodflickr-groups-pools-getphotos-get
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: extras
        description: A comma-delimited list of extra information to fetch for each
          returned record
      - in: query
        name: format
        description: Response format
      - in: query
        name: page
        description: The page of results to return
      - in: query
        name: per_page
        description: Number of photos to return per page
      - in: query
        name: tags
        description: A tag to filter the pool with
      - in: query
        name: user_id
        description: The nsid of a user
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Pools
      - GetPhotos
  /rest/?method=flickr.groups.pools.remove:
    post:
      summary: Groups Pools Remove
      description: Remove a photo from a group pool.
      operationId: postRestMethodFlickr.groups.pools.remove
      x-api-path-slug: restmethodflickr-groups-pools-remove-post
      parameters:
      - in: query
        name: api_key
        description: Your API application key
      - in: query
        name: group_id
        description: The NSID of the group whos pool the photo is to removed from
      - in: query
        name: photo_id
        description: The id of the photo to remove from the group pool
      responses:
        200:
          description: OK
      tags:
      - Groups
      - Pools
      - Remove