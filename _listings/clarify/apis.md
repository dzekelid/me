---
name: Clarify
x-slug: clarify
description: The API to search, re-imagined for a world that???s moved beyond text.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3503-clarify.jpg
x-kinRank: "9"
x-alexaRank: "2476786"
tags: Me
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/clarify/apis.md
specificationVersion: "0.14"
apis:
- name: Clarify Delete bundle metadata
  x-api-slug: clarify
  description: Delete the metadata of a bundle and set data to {} (empty object.)
    This is functionally equivalent to an update metadata request with data set to
    {}.Successful response will be a HTTP code 204 with an empty body.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3503-clarify.jpg
  humanURL: http://clarify.io/
  baseURL: https://api.clarify.io////v1/bundles/{bundle_id}/metadata
  tags: Bundle,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/clarify/v1bundlesbundle-idmetadata-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/clarify/v1bundlesbundle-idmetadata-delete-openapi.md
- name: Clarify Get bundle metadata
  x-api-slug: clarify
  description: Gets the metadata for a bundle.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3503-clarify.jpg
  humanURL: http://clarify.io/
  baseURL: https://api.clarify.io////v1/bundles/{bundle_id}/metadata
  tags: Bundle,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/clarify/v1bundlesbundle-idmetadata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/clarify/v1bundlesbundle-idmetadata-get-openapi.md
- name: Clarify Update bundle metadata
  x-api-slug: clarify
  description: Update the metadata for a bundle.The metadata is a single-level JSON
    object of your own definition, containing key-values that can be searched and
    filtered on. Metadata can be used to hold text such as names, titles, descriptions
    and values for segregating bundles, for example by user, topic, folder name etc.
    The keys (property names) can be up to 64 characters and must contain only alphanumeric
    characters and underscore (but not start with underscore) and must not be a reserved
    name. Reserved names are &quot;true&quot;, &quot;false&quot;, and &quot;null&quot;.
    Values can be strings, numbers, boolean true/false, date-times represented as
    a string in ISO 8601 format (ex. &quot;2014-02-25T14:23:45.000Z&quot;), or an
    array of these primitive types. Strings can be up to 2000 characters and strings
    in arrays can be up to 128 characters each. Nested objects are not allowed. Metadata
    can contain up to 50 key-value pairs up to a total JSON size of 4000 characters.To
    clear the metadata for a bundle, send data={}.If version specified, the metadata
    will only be updated if the current version matches this parameter value. If the
    version doesn't match, a 409 Conflict will be returned. If version not specified,
    the metadata will always be updated.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3503-clarify.jpg
  humanURL: http://clarify.io/
  baseURL: https://api.clarify.io////v1/bundles/{bundle_id}/metadata
  tags: Bundle,Metadata
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/clarify/v1bundlesbundle-idmetadata-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/clarify/v1bundlesbundle-idmetadata-put-openapi.md
- name: Clarify Add media to a track
  x-api-slug: clarify
  description: 'Add media to an existing track of a bundle. This can only be called
    on a track that currently has no media set or has parts pending.Once all media
    parts have been added to a track it is immutable, meaning it cannot be modified.
    If you wish to modify a track, simply add a new one and delete the existing one.media_url
    must be a publicly accessible url to a media file. It will be fetched asynchronously
    after the REST call returns. The audio can be mono or stereo.audio_channel is
    used to specify audio channels if the media is a stereo file. A value of left
    or right signifies that only the specified channel will be used. If no value or
    an empty string is specified for audio_channel, all channels will be used in a
    single track. If your stereo channels were recorded separately with each channel
    containing distinct content (for example if 2 legs of a phone call were recorded
    separately and combined into a single stereo file), for best speech recognition,
    create two tracks with audio_channel to be left and right. If your stereo file
    is simply a recording made with a stereo microphone, audio_channel should be set
    to an empty string (or not be specified.)audio_language can be used to specify
    the language of the audio media. This is an optional parameter and if not specified
    or an empty string, the language of the track will be automatically detected.
    If specified, it must be a language code as described in RFC5646 (see http://tools.ietf.org/html/rfc5646).
    Supported languages: en-US, en-UK, es, fr.start_time a time in seconds that the
    media starts, relative to start time of the bundle. This allows you to specify
    sequential parts of media. If not specified, the default is 0.parts_pending a
    boolean flag specifying if more media parts will subsequently be added to the
    track. If true, a subsequent API call must be made to signify that the track is
    complete. If not specified, the default is false.If version specified, the track
    will only be added if the current version matches this parameter value. If the
    version doesn''t match, a 409 Conflict error will be returned. If version not
    specified, the track will always be updated.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3503-clarify.jpg
  humanURL: http://clarify.io/
  baseURL: https://api.clarify.io////v1/bundles/{bundle_id}/tracks/{track_id}
  tags: Media,To,Track
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/clarify/v1bundlesbundle-idtrackstrack-id-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/clarify/v1bundlesbundle-idtrackstrack-id-put-openapi.md
- name: Clarify
  x-api-slug: clarify
  description: The API to search, re-imagined for a world that???s moved beyond text.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/3503-clarify.jpg
  humanURL: http://clarify.io/
  baseURL: https://api.clarify.io//
  tags: Me
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/me/master/_listings/clarify/openapi.md
x-common:
- type: x-base
  url: https://api.clarify.io
- type: x-blog
  url: http://clarify.io/blog/
- type: x-crunchbase
  url: https://crunchbase.com/organization/clarify-inc
- type: x-developer
  url: http://developer.clarify.io/
- type: x-documentation
  url: http://clarify.io/docs/api/
- type: x-email
  url: contact@clarify.io
- type: x-email
  url: cfy.dmca@clarify.io
- type: x-github
  url: https://github.com/OP3Nvoice
- type: x-pricing
  url: http://clarify.io/pricing/
- type: x-twitter
  url: https://twitter.com/ClarifyAPI
- type: x-twitter
  url: https://twitter.com/clarifyio
- type: x-website
  url: http://clarify.io/
- type: x-website
  url: http://clarify.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---