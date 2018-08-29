swagger: "2.0"
x-collection-name: Cisco WebEx
x-complete: 1
info:
  title: Webex Teams API
  description: hey-there-thanks-for-checking-out-cisco-webex-for-developers--if-youve-used-cisco-webex-meetings-or-cisco-webex-teams-formerly-cisco-spark-you-know-how-easy-it-is-to-meet-and-collaborate-with-your-team-members-and-customers-the-webex-for-developers-program-opens-up-the-power-behind-the-webex-platform-to-anyone-seeking-to-extend-the-webex-experience-webex-meetings-is-a-powerful-conferencing-solution-that-lets-you-connect-with-anyone-anywhere-in-real-time--by-combining-video-audio-and-content-sharing-webex-meetings-creates-an-effective-conferencing-environment-leading-to-more-productive-meetings-and-increased-productivity--developer-information-for-webex-meetings-will-soon-be-available-on-this-site--in-the-meantime-to-get-started-with-developing-for-webex-meetings-please-see-the-getting-started-guides-over-on-cisco-devnet--keep-reading-for-information-about-webex-teams-webex-teams-makes-staying-in-sync-with-your-teammates-and-customers-easy-conversations-in-webex-teams-take-place-in-virtual-meeting-rooms--some-rooms-live-for-a-few-hours-while-others-become-permanent-fixtures-of-your-teams-workflow-with-titles-like-daily-standup-or-build-status--webex-teams-allows-conversations-to-flow-seamlessly-between-messages-video-calls-and-realtime-whiteboarding-sessions--no-other-solution-brings-together-so-many-facets-of-collaboration-into-a-single-unified-platform-httpsdeveloper-webex-comgettingstarted-html
  version: 1.0.0
host: api.ciscospark.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /webhooks:
    get:
      summary: List webhooks
      description: |-
        Lists all of your webhooks.

        https://developer.webex.com/endpoint-webhooks-get.html
      operationId: WebhooksGet
      x-api-path-slug: webhooks-get
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - List
      - Webhooks
    post:
      summary: Create a webhook (all events, all rooms)
      description: |-
        Creates a webhook for messages/created event.

        Note that you'll need to change the requestb.in URI to your own to see the webhook in action.

        https://developer.webex.com/endpoint-webhooks-post.html
      operationId: WebhooksPost
      x-api-path-slug: webhooks-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Webhook
      - (all
      - Events
      - ""
      - ""
      - Rooms)
  /webhooks/{_webhook}:
    delete:
      summary: Delete a webhook1
      description: "Deletes a webhook, by ID.\r\n\r\nSpecify the webhook ID in the
        webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-delete.html"
      operationId: WebhooksByWebhookDelete2
      x-api-path-slug: webhooks-webhook-delete
      parameters:
      - in: path
        name: _webhook
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Webhook1
    get:
      summary: Get webhook details1
      description: "Shows details for a webhook, by ID.\r\n\r\nSpecify the webhook
        ID in the webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-webhookId-get.html"
      operationId: WebhooksByWebhookGet2
      x-api-path-slug: webhooks-webhook-get
      parameters:
      - in: path
        name: _webhook
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Webhook
      - Details1
    put:
      summary: Update a webhook
      description: "Updates a webhook, by ID.\r\n\r\nSpecify the webhook ID in the
        webhookId parameter in the URI.\r\n\r\nhttps://developer.webex.com/endpoint-webhooks-webhookId-put.html"
      operationId: WebhooksByWebhookPut
      x-api-path-slug: webhooks-webhook-put
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      - in: path
        name: _webhook
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Webhook
  /webhooks/:
    post:
      summary: Create a webhook (messages/created)
      description: |-
        Creates a webhook for messages/created event.

        Note that you'll need to change the requestb.in URI to your own to see the webhook in action.

        https://developer.webex.com/endpoint-webhooks-post.html
      operationId: WebhooksPost2
      x-api-path-slug: webhooks-post
      parameters:
      - in: body
        name: Body
        schema:
          $ref: '#/definitions/holder'
      - in: header
        name: Content-Type
      responses:
        200:
          description: OK
      tags:
      - Video Conferencing
      - Webhook
      - (messages
      - Created)