---
swagger: "2.0"
x-collection-name: Cisco WebEx
x-complete: 0
info:
  title: WebEx Teams API Get webhook details1
  description: "Shows details for a webhook, by ID.\r\n\r\nSpecify the webhook ID
    in the webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-webhookId-get.html"
  version: 1.0.0
host: api.ciscospark.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /webhooks:
    get:
      summary: List webhooks
      description: |-
        Lists all of your webhooks.

        https://developer.webex.com/endpoint-webhooks-get.html
      operationId: WebhooksGet
      x-api-path-slug: webhooks-get
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - List
      - Webhooks
    post:
      summary: Create a webhook (all events, all rooms)
      description: |-
        Creates a webhook for messages/created event.

        Note that you'll need to change the requestb.in URI to your own to see the webhook in action.

        https://developer.webex.com/endpoint-webhooks-post.html
      operationId: WebhooksPost
      x-api-path-slug: webhooks-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Webhook
      - (all
      - Events
      - ""
      - ""
      - Rooms)
  /webhooks/{_webhook}:
    delete:
      summary: Delete a webhook1
      description: "Deletes a webhook, by ID.\r\n\r\nSpecify the webhook ID in the
        webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-delete.html"
      operationId: WebhooksByWebhookDelete2
      x-api-path-slug: webhooks-webhook-delete
      parameters:
      - in: path
        name: _webhook
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Webhook1
    get:
      summary: Get webhook details1
      description: "Shows details for a webhook, by ID.\r\n\r\nSpecify the webhook
        ID in the webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-webhookId-get.html"
      operationId: WebhooksByWebhookGet2
      x-api-path-slug: webhooks-webhook-get
      parameters:
      - in: path
        name: _webhook
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Webhook
      - Details1
    put:
      summary: Update a webhook
      description: "Updates a webhook, by ID.\r\n\r\nSpecify the webhook ID in the
        webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-webhookId-put.html"
      operationId: WebhooksByWebhookPut
      x-api-path-slug: webhooks-webhook-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: _webhook
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Webhook
  /webhooks/:
    post:
      summary: Create a webhook (messages/created)
      description: |-
        Creates a webhook for messages/created event.

        Note that you'll need to change the requestb.in URI to your own to see the webhook in action.

        https://developer.webex.com/endpoint-webhooks-post.html
      operationId: WebhooksPost2
      x-api-path-slug: webhooks-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Webhook
      - (messages
      - Created)
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