---
name: MySpace Developers
x-slug: myspace-developers
description: 'AskMyspace: http://askmyspace.com  Twitter: http://twitter.com/Myspace  Instagram:
  http://instagram.com/Myspace  Tumblr: http://myspace.tumblr.com  YouTube: http://www.youtube.com/Myspace'
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
x-kinRank: "7"
x-alexaRank: "4691"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/apis.md
specificationVersion: "0.14"
apis:
- name: My Space Post Statusmoodcomments Personid Self Statusid
  x-api-slug: my-space
  description: Posts a comment to a status.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/statusmoodcomments/{personId}/@self/{statusId}
  tags: Statusmoodcomments,People,Self,StatusId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0statusmoodcommentspersonidselfstatusid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0statusmoodcommentspersonidselfstatusid-post-openapi.md
- name: My Space Get Mediaitemcomments Personid Self Albums Mediaitemid
  x-api-slug: my-space
  description: Retrieves item comments from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaitemcomments/{personId}/@self/{albumId}/{mediaItemId}
  tags: Mediaitemcomments,People,Self,AlbumId,MediaItemId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemcommentspersonidselfalbumidmediaitemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemcommentspersonidselfalbumidmediaitemid-get-openapi.md
- name: My Space Get Mediaitems Personid Videos Supported Categories Categoryid
  x-api-slug: my-space
  description: Retrieves videos for Category.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@videos/@supportedcategories/{categoryId}
  tags: MediaItems,People,@videos,Supported,categories,CategoryId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidvideossupportedcategoriescategoryid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidvideossupportedcategoriescategoryid-get-openapi.md
- name: My Space Get Mediaitems Personid Videos Supported Categories
  x-api-slug: my-space
  description: Retrieves supported categories.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@videos/@supportedcategories
  tags: MediaItems,People,@videos,Supported,categories
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidvideossupportedcategories-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidvideossupportedcategories-get-openapi.md
- name: My Space Put Mediaitems Personid Self Videos Mediaitemid
  x-api-slug: my-space
  description: Updates an video.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/@videos/{mediaItemId}
  tags: MediaItems,People,Self,@videos,MediaItemId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideosmediaitemid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideosmediaitemid-put-openapi.md
- name: My Space Get Mediaitems Personid Self Videos Mediaitemid
  x-api-slug: my-space
  description: Retrieves a video.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/@videos/{mediaItemId}
  tags: MediaItems,People,Self,@videos,MediaItemId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideosmediaitemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideosmediaitemid-get-openapi.md
- name: My Space Post Mediaitems Personid Self Videos
  x-api-slug: my-space
  description: Adds videos from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/@videos
  tags: MediaItems,People,Self,@videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideos-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideos-post-openapi.md
- name: My Space Get Mediaitems Personid Self Videos
  x-api-slug: my-space
  description: Retrieves all the videos.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/@videos
  tags: MediaItems,People,Self,@videos
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideos-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfvideos-get-openapi.md
- name: My Space Put Mediaitems Personid Self Albums Mediaitemid
  x-api-slug: my-space
  description: Updates an item from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/{albumId}/{mediaItemId}
  tags: MediaItems,People,Self,AlbumId,MediaItemId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumidmediaitemid-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumidmediaitemid-put-openapi.md
- name: My Space Get Mediaitems Personid Self Albums Mediaitemid
  x-api-slug: my-space
  description: Retrieves an item from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/{albumId}/{mediaItemId}
  tags: MediaItems,People,Self,AlbumId,MediaItemId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumidmediaitemid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumidmediaitemid-get-openapi.md
- name: My Space Post Mediaitems Personid Self Albums
  x-api-slug: my-space
  description: Adds items from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/{albumId}
  tags: MediaItems,People,Self,AlbumId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumid-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumid-post-openapi.md
- name: My Space Get Mediaitems Personid Self Albums
  x-api-slug: my-space
  description: Retrieves items from a specified album.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/{personId}/@self/{albumId}
  tags: MediaItems,People,Self,AlbumId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemspersonidselfalbumid-get-openapi.md
- name: My Space Get Mediaitems Supported Fields
  x-api-slug: my-space
  description: Retrieves all supported fields.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/mediaItems/@supportedFields
  tags: MediaItems,Supported,Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemssupportedfields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0mediaitemssupportedfields-get-openapi.md
- name: My Space Get Profilecomments Personid Self
  x-api-slug: my-space
  description: Retrieves profile comments.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com////1.0/profilecomments/{personId}/@self
  tags: Profilecomments,People,Self
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0profilecommentspersonidself-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/1-0profilecommentspersonidself-get-openapi.md
- name: My Space
  x-api-slug: my-space
  description: 'AskMyspace: http://askmyspace.com  Twitter: http://twitter.com/Myspace  Instagram:
    http://instagram.com/Myspace  Tumblr: http://myspace.tumblr.com  YouTube: http://www.youtube.com/Myspace'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1619-myspace-developers.jpg
  humanURL: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
  baseURL: https://api.myspace.com//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/myspace-developers/openapi.md
x-common:
- type: x-website
  url: http://wiki.developer.myspace.com/index.php?title=Category:RESTful_API
- type: x-blog
  url: http://www.myspace.com/pressroom?url=/company+blog/
- type: x-blog-rss
  url: http://myspace.tekgroupweb.com/company+blog/rss.xml
- type: x-crunchbase
  url: http://www.crunchbase.com/company/myspace
- type: x-crunchbase
  url: https://crunchbase.com/organization/myspace
- type: x-github
  url: https://github.com/myspace
- type: x-twitter
  url: https://twitter.com/#!/MySpaceDevTeam
- type: x-twitter
  url: https://twitter.com/Myspace
- type: x-website
  url: http://myspace.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---