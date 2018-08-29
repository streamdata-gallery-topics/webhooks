swagger: "2.0"
x-collection-name: Logicbroker
x-complete: 1
info:
  title: CommerceAPI
  version: 1.0.0
host: stage.commerceapi.io
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/v1/Webhooks:
    get:
      summary: Get list of webhooks
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Webhook_GetWebHooks
      x-api-path-slug: apiv1webhooks-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Of
      - Webhooks
    post:
      summary: Create a new webhook
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Webhook_CreateWebhook
      x-api-path-slug: apiv1webhooks-post
      parameters:
      - in: body
        name: Webhook
        description: The new webhook
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - New
      - Webhook
  /api/v1/Webhooks/{WebhookId}/Test:
    get:
      summary: Test a webhook endpoint.
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Webhook_TestWebhook
      x-api-path-slug: apiv1webhookswebhookidtest-get
      parameters:
      - in: query
        name: LogicbrokerKey
        description: The key for a test document
      - in: path
        name: WebhookId
        description: The webhook id
      responses:
        200:
          description: OK
      tags:
      - Test
      - Webhook
      - Endpoint
  /api/v1/Webhooks/{WebhookId}:
    delete:
      summary: Delete a webhook.
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Webhook_DeleteWebhook
      x-api-path-slug: apiv1webhookswebhookid-delete
      parameters:
      - in: path
        name: WebhookId
        description: The webhook id
      responses:
        200:
          description: OK
      tags:
      - Webhook
    put:
      summary: Update a webhook
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Webhook_UpdateWebhook
      x-api-path-slug: apiv1webhookswebhookid-put
      parameters:
      - in: body
        name: Webhook
        description: The webhook
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: WebhookId
        description: The webhook id
      responses:
        200:
          description: OK
      tags:
      - Webhook
    get:
      summary: Get webhook details
      description: Request rate limited to 10 requests per second with bursts up to
        100 requests.
      operationId: Webhook_GetWebhook
      x-api-path-slug: apiv1webhookswebhookid-get
      parameters:
      - in: path
        name: WebhookId
        description: The webhook id
      responses:
        200:
          description: OK
      tags:
      - Webhook
      - Details