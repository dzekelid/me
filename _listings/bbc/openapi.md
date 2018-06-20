---
swagger: "2.0"
x-collection-name: BBC
x-complete: 1
info:
  title: BBC Nitro
  description: bbc-nitro-is-the-bbcs-application-programming-interface-api-for-bbc-programmes-metadata-
  termsOfService: http://www.bbc.co.uk/terms/
  contact:
    name: Open Nitro Project
    url: http://developer.bbc.co.uk/
    email: nitro@bbc.co.uk
  version: 1.0.0
host: programmes.api.bbc.com
basePath: /nitro/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /programme_details:
    get:
      summary: Exposes programme information for a single pid
      description: Exposes programme information for a single pid
      operationId: listProgrammeDetails
      x-api-path-slug: programme-details-get
      parameters:
      - in: query
        name: page
        description: which page of results to return
      - in: query
        name: page_size
        description: number of results in each page
      - in: query
        name: partner_pid
        description: Filter for programme information by partner PID
      - in: query
        name: pid
        description: Filter for programme information for the provided PID
      responses:
        200:
          description: OK
      tags:
      - Programme
      - Details
  /programmes:
    get:
      summary: 'Start here for programmes metadata: Brands, Series, Episodes and Clips'
      description: Fetch metadata about Programmes (brands, series, episodes, clips).
        By applying different filter restrictions this feed can be used in many ways,
        for example to retrieve all series belonging to a brand, all the episodes
        and/or clips for a specific series, or any TLEO objects for a masterbrand.
        Other filters permit restricting to specific formats and/or genres, and you
        can request specific versions (for example Signed or Audio-Described). Parameters
        may be combined in any way suitable for your application.
      operationId: listProgrammes
      x-api-path-slug: programmes-get
      parameters:
      - in: query
        name: audio_described
        description: filter for subset of programmes that are audio-described
      - in: query
        name: availability
        description: filter for subset of programmes that have availability
      - in: query
        name: availability_entity_type
        description: additional filter when availability=available
      - in: query
        name: availability_from
        description: filter for subset of programmes that are available after or at
          the specified datetime
      - in: query
        name: availability_type
        description: filter for a subset of programmes that are available for a given
          type
      - in: query
        name: children_of
        description: filter for subset of programmes that have PID as immediate parent
      - in: query
        name: descendants_of
        description: filter for subset of programmes that have PID as ancestor
      - in: query
        name: duration
        description: filter for subset of programmes that have given duration
      - in: query
        name: embargoed
        description: Control return of embargoed items (undocumented)
      - in: query
        name: entity_type
        description: filter for subset of programmes that have given entity type
      - in: query
        name: format
        description: filter for subset of programmes with format
      - in: query
        name: genre
        description: filter for subset of programmes with genre
      - in: query
        name: group
        description: filter for subset of programmes which belong to the given group
          pid
      - in: query
        name: initial_letter
        description: filter for subset of programmes with title beginning with initial
          letter librarian style (ignoring leading The, An (Welsh), etc) 0-9 a-z
      - in: query
        name: initial_letter_end
        description: Programmes with (librarian) titles whose initial letter is equal/before
          given letter
      - in: query
        name: initial_letter_start
        description: Programmes with (librarian) titles whose initial letter is equal/after
          given letter
      - in: query
        name: initial_letter_strict
        description: filter for subset of programmes with title beginning with initial
          letter
      - in: query
        name: item
        description: filter for subset of programmes with linked to versions which
          have the given item pids
      - in: query
        name: master_brand
        description: filter for subset of programmes with master_brand
      - in: query
        name: media_set
        description: filter for subset of programmes with media set
      - in: query
        name: media_type
        description: filter for subset of programmes with media type
      - in: query
        name: mixin
        description: 'Mixins:* alternate_images: mixin to return the alternate images
          for a programme* ancestor_titles: mixin to return ancestor programme titles*
          availability: mixin to return programme availability information* available_simulcasts:
          mixin to return information about programmes that are currently available
          as simulcasts* available_versions: mixin to return information about programmes
          that are currently available on demand* available_webcasts: mixin to return
          information about programmes that are currently available as webcasts* contributions:
          mixin to return information about contributors to a programme* duration:
          mixin to return original version duration in programme concept entities*
          genre_groupings: mixin to return list of genre groupings* genre_groups:
          mixin to return list of genre groups* images: mixin to add image information
          for a programme* is_embeddable: mixin to add embeddable information for
          a programme* previous_next: mixin to return the programmes which appear
          before and after a programme (as determined by the sort applied in the request)*
          related_links: mixin to return information about related links to a programme*
          titles: mixin to return ancestor programme titles* versions_availability:
          mixin to return information about programmes that are currently available'
      - in: query
        name: page
        description: which page of results to return
      - in: query
        name: page_size
        description: number of results in each page
      - in: query
        name: partner_id
        description: filter for programmes by partner ID
      - in: query
        name: partner_pid
        description: filter for programmes by partner PID
      - in: query
        name: payment_type
        description: filter for a subset of programmes that are of the given payment_type
      - in: query
        name: people
        description: filter for subset of programmes with contributions by given people
          PID
      - in: query
        name: pid
        description: filter for subset of programmes having given PID
      - in: query
        name: promoted_for
        description: filter for subset of programmes which are promoted for given
          service
      - in: query
        name: q
        description: filter for subset of programmes matching supplied keyword/phrase
          (boolean operators permitted)
      - in: query
        name: signed
        description: filter for subset of programmes that are signed
      - in: query
        name: sort
        description: 'Sorts:* group_position: sort numerically by position in group,
          ascending* pid: sort alphabetically by PID, descending* position: sort numerically
          by position, ascending* promotion: sort by promotion rank, ascending* release_date:
          sort chronologically by release date, descending* relevance: sort by weighting
          of search term (use with q parameter)* scheduled_start: sort chronologically
          by scheduled start time/date, ascending* strict_title: sort alphabetically
          by title, ascending* title: sort by title librarian style (ignoring leading
          The, A, etc), ascending* tree: sort by root pid and then preorder tree sort'
      - in: query
        name: sort_direction
        description: Sort direction
      - in: query
        name: tag_name
        description: filter for subset of programmes with tag
      - in: query
        name: tag_scheme
        description: filter for subset of programmes with a tag
      - in: query
        name: tleo
        description: filter for subset of programmes that are TLEOs
      - in: query
        name: version
        description: filter for subset of programmes with given PID as one of their
          versions
      responses:
        200:
          description: OK
      tags:
      - Programmes
---