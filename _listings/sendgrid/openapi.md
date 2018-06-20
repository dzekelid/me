---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 1
info:
  title: SendGrid
  description: the-sendgrid-web-api-v3-documentation--this-is-the-entirety-of-the-documented-v3-endpoints--we-have-updated-all-the-descriptions-parameters-requests-and-responses--authentication-every-endpoint-requires-authentication-in-the-form-of-an-authorization-header-authorization-bearer-api-key
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /contactdb/segments:
    get:
      summary: Get Contactdb Segments
      description: |-
        **This endpoint allows you to retrieve all of your segments.**

        The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

        For more information about segments in Marketing Campaigns, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment).
      operationId: contactdb.segments.get
      x-api-path-slug: contactdbsegments-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Segments
    post:
      summary: Add Contactdb Segments
      description: "**This endpoint allows you to create a segment.**\n\nAll recipients
        in your contactdb will be added or removed automatically depending on whether
        they match the criteria for this segment.\n\nList Id:\n\n* Send this to segment
        from an existing list\n* Don't send this in order to segment from your entire
        contactdb.\n\nValid operators for create and update depend on the type of
        the field you are segmenting: \n\n* **Dates:** \"eq\", \"ne\", \"lt\" (before),
        \"gt\" (after) \n* **Text:** \"contains\", \"eq\" (is - matches the full field),
        \"ne\" (is not - matches any field where the entire field is not the condition
        value) \n* **Numbers:** \"eq\", \"lt\", \"gt\" \n* **Email Clicks and Opens:**
        \"eq\" (opened), \"ne\" (not opened) \n\nSegment conditions using \"eq\" or
        \"ne\" for email clicks and opens should provide a \"field\" of either *clicks.campaign_identifier*
        or *opens.campaign_identifier*. The condition value should be a string containing
        the id of a completed campaign. \n\nSegments may contain multiple condtions,
        joined by an \"and\" or \"or\" in the \"and_or\" field. The first condition
        in the conditions list must have an empty \"and_or\", and subsequent conditions
        must all specify an \"and_or\".\n\nThe Contacts API helps you manage your
        [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)
        recipients.\n\nFor more information about segments in Marketing Campaigns,
        please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment)."
      operationId: contactdb.segments.post
      x-api-path-slug: contactdbsegments-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Segments
  /contactdb/segments/{segment_id}:
    delete:
      summary: Delete Contactdb Segments Segment
      description: |-
        **This endpoint allows you to delete a segment from your recipients database.**

        You also have the option to delete all the contacts from your Marketing Campaigns recipient database who were in this segment.

        The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

        For more information about segments in Marketing Campaigns, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment).
      operationId: contactdb.segments.segment_id.delete
      x-api-path-slug: contactdbsegmentssegment-id-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: delete_contacts
        description: True to delete all contacts matching the segment in addition
          to deleting the segment
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Segments
      - Segment
    get:
      summary: Get Contactdb Segments Segment
      description: |-
        **This endpoint allows you to retrieve a single segment with the given ID.**

        The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

        For more information about segments in Marketing Campaigns, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment).
      operationId: contactdb.segments.segment_id.get
      x-api-path-slug: contactdbsegmentssegment-id-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: segment_id
        description: The ID of the segment you want to request
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Segments
      - Segment
    patch:
      summary: Patch Contactdb Segments Segment
      description: |-
        **This endpoint allows you to update a segment.**

        The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

        For more information about segments in Marketing Campaigns, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment).
      operationId: contactdb.segments.segment_id.patch
      x-api-path-slug: contactdbsegmentssegment-id-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      - in: query
        name: segment_id
        description: The ID of the segment you are updating
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Segments
      - Segment
  /contactdb/segments/{segment_id}/recipients:
    get:
      summary: Get Contactdb Segments Segment  Recipients
      description: |-
        **This endpoint allows you to retrieve all of the recipients in a segment with the given ID.**

        The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

        For more information about segments in Marketing Campaigns, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment).
      operationId: contactdb.segments.segment_id.recipients.get
      x-api-path-slug: contactdbsegmentssegment-idrecipients-get
      parameters:
      - in: query
        name: No Name
      - in: query
        name: page
      - in: query
        name: page_size
      responses:
        200:
          description: OK
      tags:
      - Email
      - Contactdb
      - Segments
      - Segment
      - ""
      - Recipients
  /ips/pools/{pool_name}:
    delete:
      summary: Delete Ips Pools Pool Name
      description: |-
        **This endpoint allows you to delete an IP pool.**

        IP Pools allow you to group your dedicated SendGrid IP addresses together. For example, you could create separate pools for your transactional and marketing email. When sending marketing emails, specify that you want to use the marketing IP pool. This allows you to maintain separate reputations for your different email traffic.

        IP pools can only be used with whitelabeled IP addresses.

        If an IP pool is NOT specified for an email, it will use any IP available, including ones in pools.
      operationId: ips.pools.pool_name.delete
      x-api-path-slug: ipspoolspool-name-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Ips
      - Pools
      - Pool
      - Name
    get:
      summary: Get Ips Pools Pool Name
      description: |-
        **This endpoint allows you to list all of the IP addresses that are in a specific IP pool.**

        IP Pools allow you to group your dedicated SendGrid IP addresses together. For example, you could create separate pools for your transactional and marketing email. When sending marketing emails, specify that you want to use the marketing IP pool. This allows you to maintain separate reputations for your different email traffic.

        IP pools can only be used with whitelabeled IP addresses.

        If an IP pool is NOT specified for an email, it will use any IP available, including ones in pools.
      operationId: ips.pools.pool_name.get
      x-api-path-slug: ipspoolspool-name-get
      responses:
        200:
          description: OK
      tags:
      - Email
      - Ips
      - Pools
      - Pool
      - Name
    put:
      summary: Put Ips Pools Pool Name
      description: |-
        **This endpoint allows you to update the name of an IP pool.**

        IP Pools allow you to group your dedicated SendGrid IP addresses together. For example, you could create separate pools for your transactional and marketing email. When sending marketing emails, specify that you want to use the marketing IP pool. This allows you to maintain separate reputations for your different email traffic.

        IP pools can only be used with whitelabeled IP addresses.

        If an IP pool is NOT specified for an email, it will use any IP available, including ones in pools.
      operationId: ips.pools.pool_name.put
      x-api-path-slug: ipspoolspool-name-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Ips
      - Pools
      - Pool
      - Name
  /ips/pools/{pool_name}/ips:
    post:
      summary: Add Ips Pools Pool Name Ips
      description: |-
        **This endpoint allows you to add an IP address to an IP pool.**

        You can add the same IP address to multiple pools. It may take up to 60 seconds for your IP address to be added to a pool after your request is made.

        A single IP address or a range of IP addresses may be dedicated to an account in order to send email for multiple domains. The reputation of this IP is based on the aggregate performance of all the senders who use it.
      operationId: ips.pools.pool_name.ips.post
      x-api-path-slug: ipspoolspool-nameips-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Ips
      - Pools
      - Pool
      - Name
      - Ips
  /ips/pools/{pool_name}/ips/{ip}:
    delete:
      summary: Delete Ips Pools Pool Name Ips Ip
      description: |-
        **This endpoint allows you to remove an IP address from an IP pool.**

        The same IP address can be added to multiple IP pools.

        A single IP address or a range of IP addresses may be dedicated to an account in order to send email for multiple domains. The reputation of this IP is based on the aggregate performance of all the senders who use it.
      operationId: ips.pools.pool_name.ips.ip.delete
      x-api-path-slug: ipspoolspool-nameipsip-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Ips
      - Pools
      - Pool
      - Name
      - Ips
      - Ip
  /subusers/{subuser_name}:
    delete:
      summary: Delete Subusers Subuser Name
      description: |-
        This endpoint allows you to delete a subuser. This is a permanent action, once deleted a subuser cannot be retrieved.

        For more information about Subusers:

        * [User Guide > Subusers](https://sendgrid.com/docs/User_Guide/Settings/Subusers/index.html)
        * [Classroom > How do I add more subusers to my account?](https://sendgrid.com/docs/Classroom/Basics/Account/how_do_i_add_more_subusers_to_my_account.html)
      operationId: subusers.subuser_name.delete
      x-api-path-slug: subuserssubuser-name-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Subusers
      - Subuser
      - Name
    patch:
      summary: Patch Subusers Subuser Name
      description: |-
        This endpoint allows you to enable or disable a subuser.

        For more information about Subusers:

        * [User Guide > Subusers](https://sendgrid.com/docs/User_Guide/Settings/Subusers/index.html)
        * [Classroom > How do I add more subusers to my account?](https://sendgrid.com/docs/Classroom/Basics/Account/how_do_i_add_more_subusers_to_my_account.html)
      operationId: subusers.subuser_name.patch
      x-api-path-slug: subuserssubuser-name-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Subusers
      - Subuser
      - Name
  /subusers/{subuser_name}/ips:
    put:
      summary: Put Subusers Subuser Name Ips
      description: "Each subuser should be assigned to an IP address, from which all
        of this subuser's mail will be sent. Often, this is the same IP as the parent
        account, but each subuser can have their own, or multiple, IP addresses as
        well. \n\nMore information:\n\n* [How to request more IPs](https://sendgrid.com/docs/Classroom/Basics/Account/adding_an_additional_dedicated_ip_to_your_account.html)\n*
        [IPs can be whitelabeled](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/ips.html)"
      operationId: subusers.subuser_name.ips.put
      x-api-path-slug: subuserssubuser-nameips-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Subusers
      - Subuser
      - Name
      - Ips
  /subusers/{subuser_name}/monitor:
    delete:
      summary: Delete Subusers Subuser Name Monitor
      description: Subuser monitor settings allow you to receive a sample of an outgoing
        message by a specific customer at a specific frequency of emails.
      operationId: subusers.subuser_name.monitor.delete
      x-api-path-slug: subuserssubuser-namemonitor-delete
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Subusers
      - Subuser
      - Name
      - Monitor
    get:
      summary: Get Subusers Subuser Name Monitor
      description: Subuser monitor settings allow you to receive a sample of an outgoing
        message by a specific customer at a specific frequency of emails.
      operationId: subusers.subuser_name.monitor.get
      x-api-path-slug: subuserssubuser-namemonitor-get
      responses:
        200:
          description: OK
      tags:
      - Email
      - Subusers
      - Subuser
      - Name
      - Monitor
    post:
      summary: Add Subusers Subuser Name Monitor
      description: Subuser monitor settings allow you to receive a sample of an outgoing
        message by a specific customer at a specific frequency of emails.
      operationId: subusers.subuser_name.monitor.post
      x-api-path-slug: subuserssubuser-namemonitor-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Subusers
      - Subuser
      - Name
      - Monitor
    put:
      summary: Put Subusers Subuser Name Monitor
      description: Subuser monitor settings allow you to receive a sample of an outgoing
        message by a specific customer at a specific frequency of emails.
      operationId: subusers.subuser_name.monitor.put
      x-api-path-slug: subuserssubuser-namemonitor-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Subusers
      - Subuser
      - Name
      - Monitor
  /subusers/{subuser_name}/stats/monthly:
    get:
      summary: Get Subusers Subuser Name Stats Monthly
      description: |-
        **This endpoint allows you to retrive the monthly email statistics for a specific subuser.**

        While you can always view the statistics for all email activity on your account, subuser statistics enable you to view specific segments of your stats for your subusers. Emails sent, bounces, and spam reports are always tracked for subusers. Unsubscribes, clicks, and opens are tracked if you have enabled the required settings.

        When using the `sort_by_metric` to sort your stats by a specific metric, you can not sort by the following metrics:
        `bounce_drops`, `deferred`, `invalid_emails`, `processed`, `spam_report_drops`, `spam_reports`, or `unsubscribe_drops`.

        For more information, see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/subuser.html).
      operationId: subusers.subuser_name.stats.monthly.get
      x-api-path-slug: subuserssubuser-namestatsmonthly-get
      parameters:
      - in: query
        name: date
        description: The date of the month to retrieve statistics for
      - in: query
        name: limit
        description: Optional field to limit the number of results returned
      - in: query
        name: offset
        description: Optional beginning point in the list to retrieve from
      - in: query
        name: sort_by_direction
        description: The direction you want to sort
      - in: query
        name: sort_by_metric
        description: The metric that you want to sort by
      responses:
        200:
          description: OK
      tags:
      - Email
      - Subusers
      - Subuser
      - Name
      - Stats
      - Monthly
  /teammates/{username}:
    delete:
      summary: Delete Teammates Username
      description: |-
        This endpoint allows you to delete a teammate.

        **Only the parent user or an admin teammate can delete another teammate.**
      operationId: teammates.username.delete
      x-api-path-slug: teammatesusername-delete
      responses:
        200:
          description: OK
      tags:
      - Email
      - Teammates
      - Username
    get:
      summary: Get Teammates Username
      description: This endpoint allows you to retrieve a specific teammate by username.
      operationId: teammates.username.get
      x-api-path-slug: teammatesusername-get
      responses:
        200:
          description: OK
      tags:
      - Email
      - Teammates
      - Username
    patch:
      summary: Patch Teammates Username
      description: "This endpoint allows you to update a teammate\u2019s permissions.\n\nTo
        turn a teammate into an admin, the request body should contain an `is_admin`
        set to `true`. Otherwise, set `is_admin` to `false` and pass in all the scopes
        that a teammate should have.\n\n**Only the parent user or other admin teammates
        can update another teammate\u2019s permissions.**\n\n**Admin users can only
        update permissions.**"
      operationId: teammates.username.patch
      x-api-path-slug: teammatesusername-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Email
      - Teammates
      - Username
  /user/username:
    get:
      summary: Get User Username
      description: |-
        **This endpoint allows you to retrieve your current account username.**

        Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.

        For more information about your user profile:

        * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)
      operationId: user.username.get
      x-api-path-slug: userusername-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - User
      - Username
    put:
      summary: Put User Username
      description: |-
        **This endpoint allows you to update the username for your account.**

        Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.

        For more information about your user profile:

        * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)
      operationId: user.username.put
      x-api-path-slug: userusername-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - User
      - Username
  /user/webhooks/parse/settings/{hostname}:
    delete:
      summary: Delete User Webhooks Parse Settings Hostname
      description: |-
        **This endpoint allows you to delete a specific inbound parse setting.**

        The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
      operationId: user.webhooks.parse.settings.hostname.delete
      x-api-path-slug: userwebhooksparsesettingshostname-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - User
      - Webhooks
      - Parse
      - Settings
      - Hostname
    get:
      summary: Get User Webhooks Parse Settings Hostname
      description: |-
        **This endpoint allows you to retrieve a specific inbound parse setting.**

        The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
      operationId: user.webhooks.parse.settings.hostname.get
      x-api-path-slug: userwebhooksparsesettingshostname-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - User
      - Webhooks
      - Parse
      - Settings
      - Hostname
    patch:
      summary: Patch User Webhooks Parse Settings Hostname
      description: |-
        **This endpoint allows you to update a specific inbound parse setting.**

        The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
      operationId: user.webhooks.parse.settings.hostname.patch
      x-api-path-slug: userwebhooksparsesettingshostname-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - User
      - Webhooks
      - Parse
      - Settings
      - Hostname
---