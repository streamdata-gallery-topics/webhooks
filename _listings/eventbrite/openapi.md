---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 1
info:
  title: Eventbrite
  description: the-eventbrite-api-is-the-best-way-to-integrate-and-extend-eventbrite-for-your-event-or-organising-needs-version-3-of-the-api-brings-you-faster-responses-consistent-data-types-more-endpoints-and-easier-debugging-and-testing
  version: 1.0.0
host: www.eventbriteapi.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /webhooks/{id}/:
    get:
      summary: Get Webhooks
      description: Returns a webhook for the specified webhook as webhook.
      operationId: getWebhooks
      x-api-path-slug: webhooksid-get
      responses:
        200:
          description: OK
      tags:
      - Webhooks
    delete:
      summary: Delete Webhooks
      description: Deletes the specified webhook object.
      operationId: deleteWebhooks
      x-api-path-slug: webhooksid-delete
      responses:
        200:
          description: OK
      tags:
      - Webhooks
  /webhooks/:
    get:
      summary: Get Webhooks
      description: Returns the list of webhook objects that belong to the authenticated
        user.
      operationId: getWebhooks
      x-api-path-slug: webhooks-get
      responses:
        200:
          description: OK
      tags:
      - Webhooks
    post:
      summary: Add Webhooks
      description: Creates a webhook for the authenticated user.
      operationId: postWebhooks
      x-api-path-slug: webhooks-post
      parameters:
      - in: query
        name: actions
        description: Determines what actions will trigger the webhook
        type: query
      - in: query
        name: endpoint_url
        description: The target URL of the Webhook subscription
        type: query
      - in: query
        name: event_id
        description: The ID of the event that triggers this webhook
        type: query
      responses:
        200:
          description: OK
      tags:
      - Webhooks
---