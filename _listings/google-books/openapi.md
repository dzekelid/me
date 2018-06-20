---
swagger: "2.0"
x-collection-name: Google Books
x-complete: 1
info:
  title: Books
  description: searches-for-books-and-manages-your-google-books-library-
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /books/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /myconfig/syncVolumeLicenses:
    post:
      summary: Sync Volume Licenses
      description: Request downloaded content access for specified volumes on the
        My eBooks shelf.
      operationId: books.myconfig.syncVolumeLicenses
      x-api-path-slug: myconfigsyncvolumelicenses-post
      parameters:
      - in: query
        name: cpksver
        description: The device/version ID from which to release the restriction
      - in: query
        name: features
        description: List of features supported by the client, i
      - in: query
        name: includeNonComicsSeries
        description: Set to true to include non-comics series
      - in: query
        name: locale
        description: ISO-639-1, ISO-3166-1 codes for message localization, i
      - in: query
        name: nonce
        description: The client nonce value
      - in: query
        name: showPreorders
        description: Set to true to show pre-ordered books
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: volumeIds
        description: The volume(s) to request download restrictions for
      responses:
        200:
          description: OK
      tags:
      - Volume License
  /mylibrary/bookshelves/{shelf}/addVolume:
    post:
      summary: Add Volume
      description: Adds a volume to a bookshelf.
      operationId: books.mylibrary.bookshelves.addVolume
      x-api-path-slug: mylibrarybookshelvesshelfaddvolume-post
      parameters:
      - in: query
        name: reason
        description: The reason for which the book is added to the library
      - in: path
        name: shelf
        description: ID of bookshelf to which to add a volume
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: volumeId
        description: ID of volume to add
      responses:
        200:
          description: OK
      tags:
      - Volume
  /mylibrary/bookshelves/{shelf}/clearVolumes:
    post:
      summary: Clear Volumes
      description: Clears all volumes from a bookshelf.
      operationId: books.mylibrary.bookshelves.clearVolumes
      x-api-path-slug: mylibrarybookshelvesshelfclearvolumes-post
      parameters:
      - in: path
        name: shelf
        description: ID of bookshelf from which to remove a volume
      - in: query
        name: source
        description: String to identify the originator of this request
      responses:
        200:
          description: OK
      tags:
      - Volume
  /mylibrary/bookshelves/{shelf}/moveVolume:
    post:
      summary: Move Voume
      description: Moves a volume within a bookshelf.
      operationId: books.mylibrary.bookshelves.moveVolume
      x-api-path-slug: mylibrarybookshelvesshelfmovevolume-post
      parameters:
      - in: path
        name: shelf
        description: ID of bookshelf with the volume
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: volumeId
        description: ID of volume to move
      - in: query
        name: volumePosition
        description: Position on shelf to move the item (0 puts the item before the
          current first item, 1 puts it between the first and the second and so on
      responses:
        200:
          description: OK
      tags:
      - Volume
  /mylibrary/bookshelves/{shelf}/removeVolume:
    post:
      summary: Remove Volume
      description: Removes a volume from a bookshelf.
      operationId: books.mylibrary.bookshelves.removeVolume
      x-api-path-slug: mylibrarybookshelvesshelfremovevolume-post
      parameters:
      - in: query
        name: reason
        description: The reason for which the book is removed from the library
      - in: path
        name: shelf
        description: ID of bookshelf from which to remove a volume
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: volumeId
        description: ID of volume to remove
      responses:
        200:
          description: OK
      tags:
      - Volume
  /mylibrary/bookshelves/{shelf}/volumes:
    get:
      summary: Get Volume
      description: Gets volume information for volumes on a bookshelf.
      operationId: books.mylibrary.bookshelves.volumes.list
      x-api-path-slug: mylibrarybookshelvesshelfvolumes-get
      parameters:
      - in: query
        name: country
        description: ISO-3166-1 code to override the IP-based location
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: projection
        description: Restrict information returned to a set of selected fields
      - in: query
        name: q
        description: Full-text search query string in this bookshelf
      - in: path
        name: shelf
        description: The bookshelf ID or name retrieve volumes for
      - in: query
        name: showPreorders
        description: Set to true to show pre-ordered books
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: startIndex
        description: Index of the first element to return (starts at 0)
      responses:
        200:
          description: OK
      tags:
      - Volume
  /users/{userId}/bookshelves/{shelf}/volumes:
    get:
      summary: Get Public Volumes
      description: Retrieves volumes in a specific bookshelf for the specified user.
      operationId: books.bookshelves.volumes.list
      x-api-path-slug: usersuseridbookshelvesshelfvolumes-get
      parameters:
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: path
        name: shelf
        description: ID of bookshelf to retrieve volumes
      - in: query
        name: showPreorders
        description: Set to true to show pre-ordered books
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: startIndex
        description: Index of the first element to return (starts at 0)
      - in: path
        name: userId
        description: ID of user for whom to retrieve bookshelf volumes
      responses:
        200:
          description: OK
      tags:
      - Volume
  /volumes/recommended:
    get:
      summary: Get Recommend
      description: Return a list of recommended books for the current user.
      operationId: books.volumes.recommended.list
      x-api-path-slug: volumesrecommended-get
      parameters:
      - in: query
        name: locale
        description: ISO-639-1 language and ISO-3166-1 country code
      - in: query
        name: maxAllowedMaturityRating
        description: The maximum allowed maturity rating of returned recommendations
      - in: query
        name: source
        description: String to identify the originator of this request
      responses:
        200:
          description: OK
      tags:
      - Recommended
  /volumes/recommended/rate:
    post:
      summary: Rate Recommend
      description: Rate a recommended book for the current user.
      operationId: books.volumes.recommended.rate
      x-api-path-slug: volumesrecommendedrate-post
      parameters:
      - in: query
        name: locale
        description: ISO-639-1 language and ISO-3166-1 country code
      - in: query
        name: rating
        description: Rating to be given to the volume
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: volumeId
        description: ID of the source volume
      responses:
        200:
          description: OK
      tags:
      - Recommended
  /volumes/{volumeId}:
    get:
      summary: Get Volume
      description: Gets volume information for a single volume.
      operationId: books.volumes.get
      x-api-path-slug: volumesvolumeid-get
      parameters:
      - in: query
        name: country
        description: ISO-3166-1 code to override the IP-based location
      - in: query
        name: includeNonComicsSeries
        description: Set to true to include non-comics series
      - in: query
        name: partner
        description: Brand results for partner ID
      - in: query
        name: projection
        description: Restrict information returned to a set of selected fields
      - in: query
        name: source
        description: String to identify the originator of this request
      - in: query
        name: user_library_consistent_read
      - in: path
        name: volumeId
        description: ID of volume to retrieve
      responses:
        200:
          description: OK
      tags:
      - Volume
---