---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 0
info:
  title: Mattermost API Create an incoming webhook
  description: |-
    Create an incoming webhook for a channel.
    ##### Permissions
    `manage_webhooks` for the channel the webhook is in.
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /hooks/incoming:
    get:
      summary: List incoming webhooks
      description: |-
        Get a page of a list of incoming webhooks. Optionally filter for a specific team using query parameters.
        ##### Permissions
        `manage_webhooks` for the system or `manage_webhooks` for the specific team.
      operationId: get-a-page-of-a-list-of-incoming-webhooks-optionally-filter-for-a-specific-team-using-query-paramete
      x-api-path-slug: hooksincoming-get
      parameters:
      - in: query
        name: page
        description: The page to select
      - in: query
        name: per_page
        description: The number of hooks per page
      - in: query
        name: team_id
        description: The ID of the team to get hooks for
      responses:
        200:
          description: OK
      tags:
      - List
      - Incoming
      - Webhooks
    post:
      summary: Create an incoming webhook
      description: |-
        Create an incoming webhook for a channel.
        ##### Permissions
        `manage_webhooks` for the channel the webhook is in.
      operationId: create-an-incoming-webhook-for-a-channel-permissionsmanage-webhooks-for-the-channel-the-webhook-is-i
      x-api-path-slug: hooksincoming-post
      parameters:
      - in: body
        name: body
        description: Incoming webhook to be created
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Incoming
      - Webhook
  /hooks/outgoing:
    get:
      summary: List outgoing webhooks
      description: |-
        Get a page of a list of outgoing webhooks. Optionally filter for a specific team or channel using query parameters.
        ##### Permissions
        `manage_webhooks` for the system or `manage_webhooks` for the specific team/channel.
      operationId: get-a-page-of-a-list-of-outgoing-webhooks-optionally-filter-for-a-specific-team-or-channel-using-que
      x-api-path-slug: hooksoutgoing-get
      parameters:
      - in: query
        name: channel_id
        description: The ID of the channel to get hooks for
      - in: query
        name: page
        description: The page to select
      - in: query
        name: per_page
        description: The number of hooks per page
      - in: query
        name: team_id
        description: The ID of the team to get hooks for
      responses:
        200:
          description: OK
      tags:
      - List
      - Outgoing
      - Webhooks
    post:
      summary: Create an outgoing webhook
      description: |-
        Create an outgoing webhook for a team.
        ##### Permissions
        `manage_webhooks` for the team the webhook is in.
      operationId: create-an-outgoing-webhook-for-a-team-permissionsmanage-webhooks-for-the-team-the-webhook-is-in
      x-api-path-slug: hooksoutgoing-post
      parameters:
      - in: body
        name: body
        description: Outgoing webhook to be created
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Outgoing
      - Webhook
  /hooks/outgoing/{hook_id}/regen_token:
    post:
      summary: Regenerate the token for the outgoing webhook.
      description: |-
        Regenerate the token for the outgoing webhook.
        ##### Permissions
        `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
      operationId: regenerate-the-token-for-the-outgoing-webhook-permissionsmanage-webhooks-for-system-or-manage-webhoo
      x-api-path-slug: hooksoutgoinghook-idregen-token-post
      parameters:
      - in: path
        name: hook_id
        description: Outgoing webhook GUID
      responses:
        200:
          description: OK
      tags:
      - Regenerate
      - Tokenthe
      - Outgoing
      - Webhook.
  /hooks/incoming/{hook_id}:
    get:
      summary: Get an incoming webhook
      description: |-
        Get an incoming webhook given the hook id.
        ##### Permissions
        `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
      operationId: get-an-incoming-webhook-given-the-hook-id-permissionsmanage-webhooks-for-system-or-manage-webhooks-f
      x-api-path-slug: hooksincominghook-id-get
      parameters:
      - in: path
        name: hook_id
        description: Incoming Webhook GUID
      responses:
        200:
          description: OK
      tags:
      - Incoming
      - Webhook
    put:
      summary: Update an incoming webhook
      description: |-
        Update an incoming webhook given the hook id.
        ##### Permissions
        `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
      operationId: update-an-incoming-webhook-given-the-hook-id-permissionsmanage-webhooks-for-system-or-manage-webhook
      x-api-path-slug: hooksincominghook-id-put
      parameters:
      - in: body
        name: body
        description: Incoming webhook to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: hook_id
        description: Incoming Webhook GUID
      responses:
        200:
          description: OK
      tags:
      - Incoming
      - Webhook
  /hooks/outgoing/{hook_id}:
    get:
      summary: Get an outgoing webhook
      description: |-
        Get an outgoing webhook given the hook id.
        ##### Permissions
        `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
      operationId: get-an-outgoing-webhook-given-the-hook-id-permissionsmanage-webhooks-for-system-or-manage-webhooks-f
      x-api-path-slug: hooksoutgoinghook-id-get
      parameters:
      - in: path
        name: hook_id
        description: Outgoing webhook GUID
      responses:
        200:
          description: OK
      tags:
      - Outgoing
      - Webhook
    delete:
      summary: Delete an outgoing webhook
      description: |-
        Delete an outgoing webhook given the hook id.
        ##### Permissions
        `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
      operationId: delete-an-outgoing-webhook-given-the-hook-id-permissionsmanage-webhooks-for-system-or-manage-webhook
      x-api-path-slug: hooksoutgoinghook-id-delete
      parameters:
      - in: path
        name: hook_id
        description: Outgoing webhook GUID
      responses:
        200:
          description: OK
      tags:
      - Outgoing
      - Webhook
    put:
      summary: Update an outgoing webhook
      description: |-
        Update an outgoing webhook given the hook id.
        ##### Permissions
        `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
      operationId: update-an-outgoing-webhook-given-the-hook-id-permissionsmanage-webhooks-for-system-or-manage-webhook
      x-api-path-slug: hooksoutgoinghook-id-put
      parameters:
      - in: body
        name: body
        description: Outgoing webhook to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: hook_id
        description: outgoing Webhook GUID
      responses:
        200:
          description: OK
      tags:
      - Outgoing
      - Webhook
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