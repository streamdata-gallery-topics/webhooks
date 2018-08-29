---
swagger: "2.0"
x-collection-name: Trello
x-complete: 0
info:
  title: Trello Get Webhooks
  description: Get webhooks.
  termsOfService: https://trello.com/legal
  contact:
    name: Trello
    url: https://trello.com/home
  version: "1.0"
host: trello.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tokens/{token}/webhooks:
    get:
      summary: Get Tokens Webhooks
      description: Get tokens webhooks.
      operationId: getTokensWebhooksByToken
      x-api-path-slug: tokenstokenwebhooks-get
      parameters:
      - in: query
        name: key
        description: Generate your application key
      - in: path
        name: token
        description: token
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Tokens
      - Webhooks
    post:
      summary: Post Tokens Webhooks
      description: Post tokens webhooks.
      operationId: addTokensWebhooksByToken
      x-api-path-slug: tokenstokenwebhooks-post
      parameters:
      - in: body
        name: body
        description: Attributes of Tokens Webhooks to be added
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: key
        description: Generate your application key
      - in: path
        name: token
        description: token
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Tokens
      - Webhooks
    put:
      summary: Put Tokens Webhooks
      description: Put tokens webhooks.
      operationId: updateTokensWebhooksByToken
      x-api-path-slug: tokenstokenwebhooks-put
      parameters:
      - in: body
        name: body
        description: Attributes of Tokens Webhooks to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: key
        description: Generate your application key
      - in: path
        name: token
        description: token
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Tokens
      - Webhooks
  /tokens/{token}/webhooks/{idWebhook}:
    delete:
      summary: Delete Tokens Webhooks
      description: Delete tokens webhooks.
      operationId: deleteTokensWebhooksByTokenByIdWebhook
      x-api-path-slug: tokenstokenwebhooksidwebhook-delete
      parameters:
      - in: path
        name: idWebhook
        description: idWebhook
      - in: query
        name: key
        description: Generate your application key
      - in: path
        name: token
        description: token
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Tokens
      - Webhooks
    get:
      summary: Get Tokens Webhooks
      description: Get tokens webhooks.
      operationId: getTokensWebhooksByTokenByIdWebhook
      x-api-path-slug: tokenstokenwebhooksidwebhook-get
      parameters:
      - in: path
        name: idWebhook
        description: idWebhook
      - in: query
        name: key
        description: Generate your application key
      - in: path
        name: token
        description: token
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Tokens
      - Webhooks
  /webhooks:
    post:
      summary: Post Webhooks
      description: Post webhooks.
      operationId: addWebhooks
      x-api-path-slug: webhooks-post
      parameters:
      - in: body
        name: body
        description: Attributes of Webhooks to be added
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Webhooks
  /webhooks/:
    put:
      summary: Put Webhooks
      description: Put webhooks.
      operationId: updateWebhooks
      x-api-path-slug: webhooks-put
      parameters:
      - in: body
        name: body
        description: Attributes of Webhooks to be updated
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Webhooks
  /webhooks/{idWebhook}:
    delete:
      summary: Delete Webhooks
      description: Delete webhooks.
      operationId: deleteWebhooksByIdWebhook
      x-api-path-slug: webhooksidwebhook-delete
      parameters:
      - in: path
        name: idWebhook
        description: idWebhook
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
      responses:
        200:
          description: OK
      tags:
      - Webhooks
    get:
      summary: Get Webhooks
      description: Get webhooks.
      operationId: getWebhooksByIdWebhook
      x-api-path-slug: webhooksidwebhook-get
      parameters:
      - in: path
        name: idWebhook
        description: idWebhook
      - in: query
        name: key
        description: Generate your application key
      - in: query
        name: token
        description: Getting a token from a user
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