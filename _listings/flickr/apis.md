---
name: Flickr
x-slug: flickr
description: Flickr (pronounced flicker) is an image hosting and video hosting website,
  and web services suite that was created by Ludicorp in 2004 and acquired by Yahoo
  in 2005. In addition to being a popular website for users to share and embed personal
  photographs, and effectively an online community, the service is widely used by
  photo researchers and by bloggers to host images that they embed in blogs and social
  media.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Pools
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/apis.md
specificationVersion: "0.14"
apis:
- name: Flickr Groups Pools Add
  x-api-slug: flickr
  description: Add a photo to a group's pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.groups.pools.add
  tags: Groups,Pools,Add
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/restmethodflickr-groups-pools-add-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/restmethodflickr-groups-pools-add-post-openapi.md
- name: Flickr Groups Pools Get Context
  x-api-slug: flickr
  description: Returns next and previous photos for a photo in a group pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.groups.pools.getContext
  tags: Groups,Pools,GetContext
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/restmethodflickr-groups-pools-getcontext-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/restmethodflickr-groups-pools-getcontext-get-openapi.md
- name: Flickr Groups Pools Get Groups
  x-api-slug: flickr
  description: Returns a list of groups to which you can add photos.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.groups.pools.getGroups
  tags: Groups,Pools,GetGroups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/restmethodflickr-groups-pools-getgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/restmethodflickr-groups-pools-getgroups-get-openapi.md
- name: Flickr Groups Pools Get Photos
  x-api-slug: flickr
  description: Returns a list of pool photos for a given group, based on the permissions
    of the group and the user logged in (if any).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.groups.pools.getPhotos
  tags: Groups,Pools,GetPhotos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/restmethodflickr-groups-pools-getphotos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/restmethodflickr-groups-pools-getphotos-get-openapi.md
- name: Flickr Groups Pools Remove
  x-api-slug: flickr
  description: Remove a photo from a group pool.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services///rest/?method=flickr.groups.pools.remove
  tags: Groups,Pools,Remove
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/restmethodflickr-groups-pools-remove-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/restmethodflickr-groups-pools-remove-post-openapi.md
- name: Flickr
  x-api-slug: flickr
  description: The Flickr API consists of a set of callable methods, and some API
    endpoints.  To perform an action using the Flickr API, you need to select a calling
    convention, send a request to its endpoint specifying a method and some arguments,
    and will receive a formatted response.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/flickr-logo.jpg
  humanURL: http://www.flickr.com/
  baseURL: https://api.flickr.com//services/
  tags: Pools
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/pools/master/_listings/flickr/openapi.md
x-common:
- type: x-authentication
  url: https://www.flickr.com/services/api/auth.oauth.html
- type: x-base
  url: https://api.flickr.com/services/
- type: x-developer
  url: https://www.flickr.com/services/api/
- type: x-getting-started
  url: https://www.flickr.com/services/developer/
- type: x-privacy
  url: https://info.yahoo.com/privacy/us/yahoo/flickr/details.html
- type: x-support
  url: https://help.yahoo.com/kb/flickr-for-desktop
- type: x-terms-of-service
  url: https://www.flickr.com/services/api/tos/
- type: x-twitter
  url: https://twitter.com/flickr
- type: x-website
  url: http://www.flickr.com/
- type: x-website
  url: http://flickr.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---