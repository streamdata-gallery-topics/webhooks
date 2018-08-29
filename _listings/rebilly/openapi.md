swagger: "2.0"
x-collection-name: Rebilly
x-complete: 1
info:
  title: Rebilly
  description: -introductionthe-rebilly-api-is-built-on-http---our-api-is-restful---it-has-predictableresource-urls---it-returns-http-response-codes-to-indicate-errors---it-alsoaccepts-and-returns-json-in-the-http-body---you-can-use-your-favoritehttprest-library-for-your-programming-language-to-use-rebillys-api-oryou-can-use-one-of-our-sdks-currently-available-in-phphttpsgithub-comrebillyrebillyphpand-chttpsgithub-comrebillyrebillydotnetclient--authenticationwhen-you-sign-up-for-an-account-you-are-given-your-first-api-key-you-can-generate-additional-api-keys-and-delete-api-keys-as-you-mayneed-to-rotate-your-keys-in-the-future--you-authenticate-to-therebilly-api-by-providing-your-secret-key-in-the-request-header-rebilly-offers-three-forms-of-authentication--private-key-json-web-tokens-andpublic-key--private-key-authenticates-each-request-by-searching-for-the-presenceof-an-http-header-rebapikey--jwt-authenticates-each-request-by-the-http-header-authorization--public-key-authenticates-by-the-http-header-rebauth-read-more-on-this-below-rebilly-also-offers-json-web-tokens-jwt-authentication-where-you-can-controlthe-specific-granular-permissions-and-expiration-for-that-jwt---we-call-our-resourcefor-generating-jwt-sessionstagsessions-rebilly-also-has-a-clientside-authentication-scheme-that-uses-anapiuser-and-hmacsha1-signature-only-for-the-tokens-resource-sothat-you-may-safely-create-tokens-from-the-clientside-without-compromisingyour-secret-keys-never-share-your-secret-keys--keep-them-guarded-and-secure-the-clientside-authentication-scheme-uses-one-http-header-named-rebauth--redocinject-securitydefinitions--php-sdkfor-all-php-sdk-examples-provided-in-this-spec-you-will-need-to-configure-client-you-may-do-it-like-thisphpclient--new-rebillyclient----apikey--yourapikeyhere----baseurl--httpsapi-rebilly-com
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