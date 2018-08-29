---
swagger: "2.0"
x-collection-name: Bookeo
x-complete: 0
info:
  title: Bookeo List all webhooks
  version: 1.0.0
  description: Retrieve all the webhooks for this api key
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