swagger: "2.0"
x-collection-name: Bookeo
x-complete: 1
info:
  title: Bookeo
  version: 1.0.0
host: api.bookeo.com
basePath: /v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /webhooks:
    get:
      summary: List all webhooks
      description: Retrieve all the webhooks for this api key
      operationId: getWebhooks
      x-api-path-slug: webhooks-get
      responses:
        200:
          description: OK
      tags:
      - Webhooks
    post:
      summary: Create a new webhook
      description: |-
        Note that if an existing webhook for the same domain and type was already set for this api key, it will be automatically replaced by this new webhook.
         In other words, there can be only one webhook for each combination of domain and type, for an API key.
         So to upgrade an existing webhook URL, simply create a new one with the same domain and type, but a different URL.

         For webhook with domain "bookings" and type "deleted", the notification will be sent whether the booking is canceled or completely deleted.
         Users can delete bookings by, for example, deleting their associated customer.
         Also note that these "bookings" "deleted" notifications are sent even for bookings in the past.
      operationId: postWebhooks
      x-api-path-slug: webhooks-post
      parameters:
      - in: body
        name: webhook
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Webhooks
  /webhooks/{webhookId}:
    get:
      summary: Retrieve a webhook
      description: Retrieve a webhook.
      operationId: getWebhooksWebhook
      x-api-path-slug: webhookswebhookid-get
      parameters:
      - in: path
        name: webhookId
      responses:
        200:
          description: OK
      tags:
      - Webhooks
      - WebhookId
    delete:
      summary: Delete a webhook
      description: Delete a webhook.
      operationId: deleteWebhooksWebhook
      x-api-path-slug: webhookswebhookid-delete
      parameters:
      - in: path
        name: webhookId
      responses:
        200:
          description: OK
      tags:
      - Webhooks
      - WebhookId