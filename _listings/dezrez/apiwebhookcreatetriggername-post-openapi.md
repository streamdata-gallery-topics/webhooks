---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Creates a new webhook in the system (scoped to agency)
  version: 1.0.0
  description: Creates a new webhook in the system (scoped to agency).
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/webhook/list:
    get:
      summary: Lists all of the webhooks currently set up.
      description: Lists all of the webhooks currently set up..
      operationId: Webhook_ListWebhooksBytriggerFilterName
      x-api-path-slug: apiwebhooklist-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: query
        name: triggerFilterName
        description: Optionally, filter results that match this trigger
      responses:
        200:
          description: OK
      tags:
      - Lists
      - ""
      - Of
      - Webhooks
      - Currently
      - Set
      - Up
  /api/webhook/create/{triggerName}:
    post:
      summary: Creates a new webhook in the system (scoped to agency)
      description: Creates a new webhook in the system (scoped to agency).
      operationId: Webhook_CreateWebhookBytriggerNameBycreateWebhookRequest
      x-api-path-slug: apiwebhookcreatetriggername-post
      parameters:
      - in: body
        name: createWebhookRequest
        description: Webhook callback details
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: triggerName
        description: Name of the trigger
      responses:
        200:
          description: OK
      tags:
      - Creates
      - New
      - Webhook
      - In
      - System
      - (scoped
      - To
      - Agency)
  /api/webhook/{webhookId}:
    get:
      summary: Gets a webhook by its ID
      description: Gets a webhook by its id.
      operationId: Webhook_GetWebhookBywebhookId
      x-api-path-slug: apiwebhookwebhookid-get
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: webhookId
        description: The webhook identifier
      responses:
        200:
          description: OK
      tags:
      - S
      - Webhook
      - By
      - Its
      - ID
    delete:
      summary: Deletes an existing webhook.
      description: Deletes an existing webhook..
      operationId: Webhook_DeleteWebhookBywebhookId
      x-api-path-slug: apiwebhookwebhookid-delete
      parameters:
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      - in: path
        name: webhookId
        description: The webhook identifier
      responses:
        200:
          description: OK
      tags:
      - S
      - Existing
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