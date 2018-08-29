swagger: "2.0"
x-collection-name: PayJunction
x-complete: 1
info:
  title: PayJunction API Basic
  description: todo-add-description
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
      summary: Get Webhooks
      description: Gets a list of webhooks
      operationId: WebhooksGet
      x-api-path-slug: webhooks-get
      parameters:
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Webhooks
    post:
      summary: Post Webhooks
      description: /webhooks/{webhooks}.
      operationId: WebhooksPost
      x-api-path-slug: webhooks-post
      parameters:
      - in: query
        name: event
      - in: formData
        name: secret
        description: Text, max length 255
      - in: formData
        name: url
        description: Text, URL with max length 255
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Webhooks
  /webhooks/{webhookId}:
    put:
      summary: Put Webhooks
      description: /webhooks/{webhookid}.
      operationId: WebhooksByWebhookIdPut
      x-api-path-slug: webhookswebhookid-put
      parameters:
      - in: formData
        name: secret
        description: Text, max length 255
      - in: formData
        name: url
        description: Text, URL with max length 255
      - in: path
        name: webhookId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Webhooks
    delete:
      summary: Delete Webhooks
      description: /webhooks/{webhookid}.
      operationId: WebhooksByWebhookIdDelete
      x-api-path-slug: webhookswebhookid-delete
      parameters:
      - in: path
        name: webhookId
      - in: header
        name: X-PJ-Application-Key
      responses:
        200:
          description: OK
      tags:
      - Webhooks