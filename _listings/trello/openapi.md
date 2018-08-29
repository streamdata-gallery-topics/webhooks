swagger: "2.0"
x-collection-name: Trello
x-complete: 1
info:
  title: Trello
  description: this-document-describes-the-rest-api-of-trello-as-published-by-trello-com---a-hrefhttpstrello-comdocsindex-html-target-blankofficial-documentationa--a-hrefhttpstrello-comdocsapi-target-blankthe-html-pages-that-were-scraped-in-order-to-generate-this-specification-a
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
    put:
      summary: Put Webhooks
      description: Put webhooks.
      operationId: updateWebhooksByIdWebhook
      x-api-path-slug: webhooksidwebhook-put
      parameters:
      - in: body
        name: body
        description: Attributes of Webhooks to be updated
        schema:
          $ref: '#/definitions/holder'
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
  /webhooks/{idWebhook}/active:
    put:
      summary: Put Webhooks Active
      description: Put webhooks active.
      operationId: updateWebhooksActiveByIdWebhook
      x-api-path-slug: webhooksidwebhookactive-put
      parameters:
      - in: body
        name: body
        description: Attributes of Webhooks Active to be updated
        schema:
          $ref: '#/definitions/holder'
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
      - Active
  /webhooks/{idWebhook}/callbackURL:
    put:
      summary: Put Webhooks Callbackurl
      description: Put webhooks callbackurl.
      operationId: updateWebhooksCallbackURLByIdWebhook
      x-api-path-slug: webhooksidwebhookcallbackurl-put
      parameters:
      - in: body
        name: body
        description: Attributes of Webhooks Callback Url to be updated
        schema:
          $ref: '#/definitions/holder'
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
      - Callbackurl
  /webhooks/{idWebhook}/description:
    put:
      summary: Put Webhooks Description
      description: Put webhooks description.
      operationId: updateWebhooksDescriptionByIdWebhook
      x-api-path-slug: webhooksidwebhookdescription-put
      parameters:
      - in: body
        name: body
        description: Attributes of Webhooks Description to be updated
        schema:
          $ref: '#/definitions/holder'
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
      - Description
  /webhooks/{idWebhook}/idModel:
    put:
      summary: Put Webhooks Model
      description: Put webhooks model.
      operationId: updateWebhooksIdModelByIdWebhook
      x-api-path-slug: webhooksidwebhookidmodel-put
      parameters:
      - in: body
        name: body
        description: Attributes of Webhooks Id Model to be updated
        schema:
          $ref: '#/definitions/holder'
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
      - Model
  /webhooks/{idWebhook}/{field}:
    get:
      summary: Get Webhooks Field
      description: Get webhooks field.
      operationId: getWebhooksByIdWebhookByField
      x-api-path-slug: webhooksidwebhookfield-get
      parameters:
      - in: path
        name: field
        description: field
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
      - Field