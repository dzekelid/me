---
swagger: "2.0"
x-collection-name: Clarify
x-complete: 0
info:
  title: Clarify Add media to a track
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
  version: 1.3.4
host: api.clarify.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/bundles/{bundle_id}/metadata:
    delete:
      summary: Delete bundle metadata
      description: Delete the metadata of a bundle and set data to {} (empty object.)
        This is functionally equivalent to an update metadata request with data set
        to {}.Successful response will be a HTTP code 204 with an empty body.
      operationId: deleteV1BundlesBundleMetadata
      x-api-path-slug: v1bundlesbundle-idmetadata-delete
      parameters:
      - in: path
        name: bundle_id
        description: id of a bundle
      responses:
        200:
          description: OK
      tags:
      - Bundle
      - Metadata
    get:
      summary: Get bundle metadata
      description: Gets the metadata for a bundle.
      operationId: getV1BundlesBundleMetadata
      x-api-path-slug: v1bundlesbundle-idmetadata-get
      parameters:
      - in: path
        name: bundle_id
        description: id of a bundle
      responses:
        200:
          description: OK
      tags:
      - Bundle
      - Metadata
    put:
      summary: Update bundle metadata
      description: Update the metadata for a bundle.The metadata is a single-level
        JSON object of your own definition, containing key-values that can be searched
        and filtered on. Metadata can be used to hold text such as names, titles,
        descriptions and values for segregating bundles, for example by user, topic,
        folder name etc. The keys (property names) can be up to 64 characters and
        must contain only alphanumeric characters and underscore (but not start with
        underscore) and must not be a reserved name. Reserved names are &quot;true&quot;,
        &quot;false&quot;, and &quot;null&quot;. Values can be strings, numbers, boolean
        true/false, date-times represented as a string in ISO 8601 format (ex. &quot;2014-02-25T14:23:45.000Z&quot;),
        or an array of these primitive types. Strings can be up to 2000 characters
        and strings in arrays can be up to 128 characters each. Nested objects are
        not allowed. Metadata can contain up to 50 key-value pairs up to a total JSON
        size of 4000 characters.To clear the metadata for a bundle, send data={}.If
        version specified, the metadata will only be updated if the current version
        matches this parameter value. If the version doesn't match, a 409 Conflict
        will be returned. If version not specified, the metadata will always be updated.
      operationId: putV1BundlesBundleMetadata
      x-api-path-slug: v1bundlesbundle-idmetadata-put
      parameters:
      - in: path
        name: bundle_id
        description: id of a bundle
      - in: formData
        name: data
        description: User-defined JSON data associated with the bundle
      - in: formData
        name: version
        description: Object version
      responses:
        200:
          description: OK
      tags:
      - Bundle
      - Metadata
  /v1/bundles/{bundle_id}/tracks/{track_id}:
    put:
      summary: Add media to a track
      description: 'Add media to an existing track of a bundle. This can only be called
        on a track that currently has no media set or has parts pending.Once all media
        parts have been added to a track it is immutable, meaning it cannot be modified.
        If you wish to modify a track, simply add a new one and delete the existing
        one.media_url must be a publicly accessible url to a media file. It will be
        fetched asynchronously after the REST call returns. The audio can be mono
        or stereo.audio_channel is used to specify audio channels if the media is
        a stereo file. A value of left or right signifies that only the specified
        channel will be used. If no value or an empty string is specified for audio_channel,
        all channels will be used in a single track. If your stereo channels were
        recorded separately with each channel containing distinct content (for example
        if 2 legs of a phone call were recorded separately and combined into a single
        stereo file), for best speech recognition, create two tracks with audio_channel
        to be left and right. If your stereo file is simply a recording made with
        a stereo microphone, audio_channel should be set to an empty string (or not
        be specified.)audio_language can be used to specify the language of the audio
        media. This is an optional parameter and if not specified or an empty string,
        the language of the track will be automatically detected. If specified, it
        must be a language code as described in RFC5646 (see http://tools.ietf.org/html/rfc5646).
        Supported languages: en-US, en-UK, es, fr.start_time a time in seconds that
        the media starts, relative to start time of the bundle. This allows you to
        specify sequential parts of media. If not specified, the default is 0.parts_pending
        a boolean flag specifying if more media parts will subsequently be added to
        the track. If true, a subsequent API call must be made to signify that the
        track is complete. If not specified, the default is false.If version specified,
        the track will only be added if the current version matches this parameter
        value. If the version doesn''t match, a 409 Conflict error will be returned.
        If version not specified, the track will always be updated.'
      operationId: putV1BundlesBundleTracksTrack
      x-api-path-slug: v1bundlesbundle-idtrackstrack-id-put
      parameters:
      - in: formData
        name: audio_channel
        description: The audio channel to use for the track (  | left | right )
      - in: formData
        name: audio_language
        description: Language of the audio in the track, specified with an RFC5646
          code
      - in: path
        name: bundle_id
        description: id of a bundle
      - in: formData
        name: media_url
        description: URL of a media file for this bundle
      - in: formData
        name: parts_pending
        description: Set to true if more media parts will be added to the track
      - in: formData
        name: start_time
        description: Time offset in seconds that the media starts relative to the
          bundle
      - in: path
        name: track_id
        description: id of a track
      - in: formData
        name: version
        description: Object version
      responses:
        200:
          description: OK
      tags:
      - Media
      - To
      - Track
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