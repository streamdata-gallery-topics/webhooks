---
swagger: "2.0"
x-collection-name: Quovo
x-complete: 0
info:
  title: Quovo Update an existing webhook
  description: Used to update an existing webhook.
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /webhooks:
    get:
      summary: Get all registered webhooks
      description: "Retrieve your registered webhooks. \n\nNote: secret is intentionally
        omitted from all GET requests. It is only returned after being updated or
        after a new webhook is created."
      operationId: WebhooksGet
      x-api-path-slug: webhooks-get
      responses:
        200:
          description: OK
      tags:
      - Registered
      - Webhooks
    put:
      summary: Update an existing webhook
      description: Used to update an existing webhook.
      operationId: WebhooksPut
      x-api-path-slug: webhooks-put
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
      - Existing
      - Webhook
    post:
      summary: Register a new webhook
      description: Used to register new webhooks.
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
      - Register
      - New
      - Webhook
    delete:
      summary: Delete a webhook
      description: Deletes an existing webhook.
      operationId: WebhooksDelete
      x-api-path-slug: webhooks-delete
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