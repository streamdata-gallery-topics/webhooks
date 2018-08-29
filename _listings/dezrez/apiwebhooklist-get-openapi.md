---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Lists all of the webhooks currently set up.
  version: 1.0.0
  description: Lists all of the webhooks currently set up..
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