---
swagger: "2.0"
x-collection-name: Rebilly
x-complete: 0
info:
  title: Rebilly Delete a webhook
  description: Delete a webhook that belongs to a website with predefined ID
  termsOfService: https://www.rebilly.com/terms/
  contact:
    name: Rebilly API Support
    url: https://www.rebilly.com/contact/
    email: integrations@rebilly.com
  version: "2.1"
host: api.rebilly.com
basePath: /v2.1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /webhooks:
    get:
      summary: Retrieve a list of webhooks
      description: Retrieve a list of webhooks
      operationId: retrieve-a-list-of-webhooks
      x-api-path-slug: webhooks-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Webhooks
    post:
      summary: Create a webhook
      description: Create a webhook
      operationId: create-a-webhook
      x-api-path-slug: webhooks-post
      parameters:
      - in: body
        name: body
        description: Webhook resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Webhook
  /websites/{id}/webhook:
    get:
      summary: Retrieve a webhook for website
      description: Retrieve a webhook for website with specified identifier string
      operationId: retrieve-a-webhook-for-website-with-specified-identifier-string
      x-api-path-slug: websitesidwebhook-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Webhookwebsite
    put:
      summary: Create or update a webhook for website with predefined ID
      description: Create or update a webhook for website with predefined identifier
        string
      operationId: create-or-update-a-webhook-for-website-with-predefined-identifier-string
      x-api-path-slug: websitesidwebhook-put
      parameters:
      - in: body
        name: body
        description: Webhook resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Update
      - Webhookwebsite
      - Predefined
      - ID
    delete:
      summary: Delete a webhook
      description: Delete a webhook that belongs to a website with predefined ID
      operationId: delete-a-webhook-that-belongs-to-a-website-with-predefined-id
      x-api-path-slug: websitesidwebhook-delete
      responses:
        200:
          description: OK
      tags:
      - Webhook
  /credential-hashes/webhooks:
    post:
      summary: Create a webhook credential
      description: Create a webhook credential
      operationId: create-a-webhook-credential
      x-api-path-slug: credentialhasheswebhooks-post
      parameters:
      - in: body
        name: body
        description: Credential resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Webhook
      - Credential
  /credential-hashes/webhooks/{hash}:
    get:
      summary: Retrieve a webhook credential
      description: Retrieve a webhook credential with specified token identifier string
      operationId: retrieve-a-webhook-credential-with-specified-token-identifier-string
      x-api-path-slug: credentialhasheswebhookshash-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Webhook
      - Credential
  /previews/rule-actions/trigger-webhook:
    post:
      summary: Trigger a test webhook
      description: Trigger a test webhook
      operationId: trigger-a-test-webhook
      x-api-path-slug: previewsruleactionstriggerwebhook-post
      parameters:
      - in: body
        name: body
        description: Test webhook resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Trigger
      - Test
      - Webhook
  /previews/webhooks:
    post:
      summary: Trigger a test webhook
      description: Trigger a test webhook
      operationId: trigger-a-test-webhook
      x-api-path-slug: previewswebhooks-post
      parameters:
      - in: body
        name: body
        description: Webhook resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Trigger
      - Test
      - Webhook
  /tracking/website-webhooks:
    get:
      summary: Retrieve a list of tracking webhook notifications
      description: ""
      operationId: ""
      x-api-path-slug: trackingwebsitewebhooks-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - List
      - Of
      - Tracking
      - Webhook
      - Notifications
  /tracking/website-webhooks/{id}:
    get:
      summary: Retrieve a tracking webhook notification with specified identifier
        string
      description: ""
      operationId: ""
      x-api-path-slug: trackingwebsitewebhooksid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Tracking
      - Webhook
      - Notification
      - Specified
      - Identifier
      - String
  /webhooks/{id}:
    get:
      summary: Retrieve a webhook
      description: Retrieve a webhook with specified identifier string
      operationId: retrieve-a-webhook-with-specified-identifier-string
      x-api-path-slug: webhooksid-get
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Webhook
    put:
      summary: Create or update a webhook with predefined ID
      description: Create or update a webhook with predefined identifier string
      operationId: create-or-update-a-webhook-with-predefined-identifier-string
      x-api-path-slug: webhooksid-put
      parameters:
      - in: body
        name: body
        description: Webhook resource
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Update
      - Webhook
      - Predefined
      - ID
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