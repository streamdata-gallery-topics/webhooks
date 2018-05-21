---
swagger: "2.0"
x-collection-name: Eventbrite
x-complete: 0
info:
  title: Eventbrite Get Webhooks
  description: Returns a webhook for the specified webhook as webhook.
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