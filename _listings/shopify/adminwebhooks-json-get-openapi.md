---
swagger: "2.0"
x-collection-name: Shopify
x-complete: 0
info:
  title: Shopify Get a list of all webhooks for your shop.
  description: Get a list of all webhooks for your shop..
  version: 1.0.0
host: DefaultParameterValue:DefaultParameterValue@DefaultParameterValue.myshopify.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /admin/webhooks.json:
    get:
      summary: Get a list of all webhooks for your shop.
      description: Get a list of all webhooks for your shop..
      operationId: getAdminWebhooks.json
      x-api-path-slug: adminwebhooks-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - List
      - Webhooksyour
      - Shop
    post:
      summary: Create a webhook
      description: Create a webhook.
      operationId: postAdminWebhooks.json
      x-api-path-slug: adminwebhooks-json-post
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
      - Commerce
      - Webhook
  /admin/webhooks/count.json:
    get:
      summary: Get a count of all webhooks for your shop.
      description: Get a count of all webhooks for your shop..
      operationId: getAdminWebhooksCount.json
      x-api-path-slug: adminwebhookscount-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Count
      - Webhooksyour
      - Shop
  /admin/webhooks/503738446.json:
    put:
      summary: Update a Webhook
      description: Update a webhook.
      operationId: putAdminWebhooks503738446.json
      x-api-path-slug: adminwebhooks503738446-json-put
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
      - Commerce
      - Webhook
    delete:
      summary: Delete a Webhook
      description: Delete a webhook.
      operationId: deleteAdminWebhooks503738446.json
      x-api-path-slug: adminwebhooks503738446-json-delete
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Webhook
  /admin/webhooks/93838927.json:
    get:
      summary: Get a single webhook by its id.
      description: Get a single webhook by its id..
      operationId: getAdminWebhooks93838927.json
      x-api-path-slug: adminwebhooks93838927-json-get
      parameters:
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Commerce
      - Single
      - Webhook
      - By
      - Its
      - Id
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