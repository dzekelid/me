---
swagger: "2.0"
x-collection-name: Open Science Framework
x-complete: 0
info:
  title: Open Science Framework List all comments
  description: |-
    A paginated list of comments related to a given node.

    The returned comments are sorted by their creation date, with the most recent comments appearing first.
    ####Permissions
    Comments on public nodes are given read-only access to everyone.

    If the node comment-level is `private`, only contributors have permission to comment.

    If the comment-level is `public`, any logged-in OSF user can comment.

    Comments on private nodes are only visible to contributors and administrators on the parent node.
    ####Returns
    Returns a JSON object containing `data` and `links` keys.

    The `data` key contains an array of comment objects. Each resource in the array is a separate comment object.

    The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).
    #### Filtering
    You can optionally request that the response only include comments that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/nodes/ezcuj/comments/?filter[target_id]=jg7sezmdnt93

    Nodes may be filtered by their `deleted`, `target_id`, `date_created`, `date_modified`.

    Most fields are string fields and will be filtered using simple substring matching. Public and preprint are boolean fields, and can be filtered using truthy values, such as **true**, **false**, **0** or **1**. Note that quoting `true` or `false` in the query will cause the match to fail.
  contact:
    name: OSF
    url: https://osf.io/support
    email: support@osf.io
  version: "2.0"
host: test-api.osf.io
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /comments/{comment_id}/:
    delete:
      summary: Delete a comment
      description: |-
        Deletes a comment. This action can be undone by setting deleted to False in a comment update request.
        #### Returns
        If the request is successful, no content is returned.

        If the request is unsuccessful, a JSON object with an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
      operationId: comments_delete
      x-api-path-slug: commentscomment-id-delete
      parameters:
      - in: path
        name: comment_id
        description: The unique identifier of the comment you wish to delete
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Comment
    get:
      summary: Retrieve a comment
      description: |-
        Retrieves the details of a comment
        ####Returns
        Returns a JSON object with a `data` key containing the representation of the requested comment, if the request was successful.

        If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
      operationId: comments_read
      x-api-path-slug: commentscomment-id-get
      parameters:
      - in: path
        name: comment_id
        description: The unique identifier of the comment you wish to retrieve
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Comment
    put:
      summary: Update a comment
      description: |-
        Updates the specified comment by setting the values of the parameters passed. Any parameters not provided will be left unchanged.
        #### Returns
        Returns JSON with a `data` key containing the new representation of the updated comment, if the request is successful.

        If the request is unsuccessful, JSON with an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
      operationId: comments_put
      x-api-path-slug: commentscomment-id-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: comment_id
        description: The unique identifier of the comment you wish to update
      responses:
        200:
          description: OK
      tags:
      - Comments
      - Comment
  /metaschemas/:
    get:
      summary: List all metaschemas
      description: |-
        A paginated list of all active metaschemas.
        Metaschemas describe the supplemental questions that accompany a registration.
        #### Returns
        Returns a JSON object containing `data` and `links` keys.

        The `data` key contains an array of 10 metaschemas. Each resource in the array is a separate metaschema object.

        The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).

        This request should never return an error.
      operationId: metaschemas_list
      x-api-path-slug: metaschemas-get
      responses:
        200:
          description: OK
      tags:
      - Metaschemas
  /metaschemas/{metaschema_id}:
    get:
      summary: Retrieve a metaschema
      description: |-
        Retrieves the details of a given metaschema.

        Metaschemas describe the supplemental questions that accompany a registration.

        #### Returns
        Returns a JSON object with a `data` key containing the representation of the requested metaschema, if the request is successful.

        If the request is unsuccessful, an `errors` key containing information about the failure will be returned. Refer to the [list of error codes](#Introduction_error_codes) to understand why this request may have failed.
      operationId: metaschemas_read
      x-api-path-slug: metaschemasmetaschema-id-get
      parameters:
      - in: path
        name: metaschema_id
        description: The unique identifier of the metaschema
      responses:
        200:
          description: OK
      tags:
      - Metaschemas
      - Metaschema
  /nodes/{node_id}/comments/:
    get:
      summary: List all comments
      description: |-
        A paginated list of comments related to a given node.

        The returned comments are sorted by their creation date, with the most recent comments appearing first.
        ####Permissions
        Comments on public nodes are given read-only access to everyone.

        If the node comment-level is `private`, only contributors have permission to comment.

        If the comment-level is `public`, any logged-in OSF user can comment.

        Comments on private nodes are only visible to contributors and administrators on the parent node.
        ####Returns
        Returns a JSON object containing `data` and `links` keys.

        The `data` key contains an array of comment objects. Each resource in the array is a separate comment object.

        The `links` key contains a dictionary of links that can be used for [pagination](#Introduction_pagination).
        #### Filtering
        You can optionally request that the response only include comments that match your filters by utilizing the `filter` query parameter, e.g. https://api.osf.io/v2/nodes/ezcuj/comments/?filter[target_id]=jg7sezmdnt93

        Nodes may be filtered by their `deleted`, `target_id`, `date_created`, `date_modified`.

        Most fields are string fields and will be filtered using simple substring matching. Public and preprint are boolean fields, and can be filtered using truthy values, such as **true**, **false**, **0** or **1**. Note that quoting `true` or `false` in the query will cause the match to fail.
      operationId: nodes_comments_list
      x-api-path-slug: nodesnode-idcomments-get
      parameters:
      - in: path
        name: node_id
        description: The unique identifier of the node
      responses:
        200:
          description: OK
      tags:
      - Nodes
      - Node
      - Comments
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