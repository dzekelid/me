---
name: Google Books
x-slug: google-books
description: Google Books is our effort to make book content more discoverable on
  the Web. Using the Google Books API, your application can perform full-text searches
  and retrieve book information, viewability and eBook availability. You can also
  manage your personal bookshelves.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
  Shot 2017-03-16 at 4.28.26 PM.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Me
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/apis.md
specificationVersion: "0.14"
apis:
- name: Google Books API Sync Volume Licenses
  x-api-slug: google-books-api
  description: Request downloaded content access for specified volumes on the My eBooks
    shelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//myconfig/syncVolumeLicenses
  tags: Volume License
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/myconfigsyncvolumelicenses-post-openapi.md
- name: Google Books API Add Volume
  x-api-slug: google-books-api
  description: Adds a volume to a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves/{shelf}/addVolume
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/mylibrarybookshelvesshelfaddvolume-post-openapi.md
- name: Google Books API Clear Volumes
  x-api-slug: google-books-api
  description: Clears all volumes from a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves/{shelf}/clearVolumes
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/mylibrarybookshelvesshelfclearvolumes-post-openapi.md
- name: Google Books API Move Voume
  x-api-slug: google-books-api
  description: Moves a volume within a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves/{shelf}/moveVolume
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/mylibrarybookshelvesshelfmovevolume-post-openapi.md
- name: Google Books API Remove Volume
  x-api-slug: google-books-api
  description: Removes a volume from a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves/{shelf}/removeVolume
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/mylibrarybookshelvesshelfremovevolume-post-openapi.md
- name: Google Books API Get Volume
  x-api-slug: google-books-api
  description: Gets volume information for volumes on a bookshelf.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//mylibrary/bookshelves/{shelf}/volumes
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/mylibrarybookshelvesshelfvolumes-get-openapi.md
- name: Google Books API Get Public Volumes
  x-api-slug: google-books-api
  description: Retrieves volumes in a specific bookshelf for the specified user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//users/{userId}/bookshelves/{shelf}/volumes
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/usersuseridbookshelvesshelfvolumes-get-openapi.md
- name: Google Books API Get Recommend
  x-api-slug: google-books-api
  description: Return a list of recommended books for the current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/recommended
  tags: Recommended
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/volumesrecommended-get-openapi.md
- name: Google Books API Rate Recommend
  x-api-slug: google-books-api
  description: Rate a recommended book for the current user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/recommended/rate
  tags: Recommended
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/volumesrecommendedrate-post-openapi.md
- name: Google Books API Get Volume
  x-api-slug: google-books-api
  description: Gets volume information for a single volume.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1//volumes/{volumeId}
  tags: Volume
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/volumesvolumeid-get-openapi.md
- name: Google Books API
  x-api-slug: google-books-api
  description: The APIs in the Google Books API Family let you bringGoogle Booksfeatures
    to your site or application. The newGoogle Books APIlets you perform programmatically
    most of the operations that you can do interactively on the Google Books website.
    TheEmbedded Viewer APIlets you embed the content directly into your site.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Screen
    Shot 2017-03-16 at 4.28.26 PM.png
  humanURL: https://developers.google.com/books/
  baseURL: ://www.googleapis.com//books/v1
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/google-books/openapi.md
x-common:
- type: x-blog
  url: http://booksearch.blogspot.com
- type: x-blog-rss
  url: http://booksearch.blogspot.com/feeds/posts/default?alt=rss
- type: x-branding-guidelines
  url: https://developers.google.com/books/branding
- type: x-code
  url: https://developers.google.com/books/docs/v1/libraries
- type: x-documentation
  url: https://developers.google.com/books/docs/overview
- type: x-embeddable
  url: https://developers.google.com/books/docs/viewer/developers_guide
- type: x-partners
  url: https://books.google.com/intl/en/googlebooks/partners/
- type: x-privacy-policy
  url: https://books.google.com/intl/en/policies/privacy/
- type: x-terms-of-service
  url: https://developers.google.com/books/terms.html
- type: x-website
  url: https://developers.google.com/books/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---