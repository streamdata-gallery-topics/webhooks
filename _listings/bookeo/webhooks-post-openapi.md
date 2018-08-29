---
swagger: "2.0"
x-collection-name: Bookeo
x-complete: 0
info:
  title: Bookeo Create a new webhook
  version: 1.0.0
  description: |-
    Note that if an existing webhook for the same domain and type was already set for this api key, it will be automatically replaced by this new webhook.
     In other words, there can be only one webhook for each combination of domain and type, for an API key.
     So to upgrade an existing webhook URL, simply create a new one with the same domain and type, but a different URL.

     For webhook with domain "bookings" and type "deleted", the notification will be sent whether the booking is canceled or completely deleted.
     Users can delete bookings by, for example, deleting their associated customer.
     Also note that these "bookings" "deleted" notifications are sent even for bookings in the past.
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