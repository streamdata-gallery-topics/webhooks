---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Suspend Webhook
  description: |-
    Suspends webhooks by ID.
    Usage Plan Group
    Medium
  version: 1.0.0
host: platform.ringcentral.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /restapi/v1.0/glip/groups/{groupId}/webhooks:
    get:
      summary: Get Webhooks in Group
      description: |-
        Returns webhooks which are available for the current user (by group ID).
        Usage Plan Group
        Medium
      operationId: listGlipGroupWebhooks
      x-api-path-slug: restapiv1-0glipgroupsgroupidwebhooks-get
      parameters:
      - in: path
        name: groupId
        description: Internal identifier of a group
      responses:
        200:
          description: OK
      tags:
      - Webhooks
      - In
      - Group
    post:
      summary: Create Webhook in Group
      description: |-
        Create new Webhook
        Usage Plan Group
        Medium
      operationId: createGlipGroupWebhook
      x-api-path-slug: restapiv1-0glipgroupsgroupidwebhooks-post
      parameters:
      - in: path
        name: groupId
        description: Group id
      responses:
        200:
          description: OK
      tags:
      - Webhook
      - In
      - Group
  /restapi/v1.0/glip/webhooks:
    get:
      summary: Get Webhooks
      description: |-
        Returns all webhooks.
        Usage Plan Group
        Medium
      operationId: listGlipWebhooks
      x-api-path-slug: restapiv1-0glipwebhooks-get
      responses:
        200:
          description: OK
      tags:
      - Webhooks
  /restapi/v1.0/glip/webhooks/{webhookId}:
    get:
      summary: Get Webhook
      description: |-
        Returns webhooks(s) with the specified id(s).
        Usage Plan Group
        Medium
      operationId: loadGlipWebhook
      x-api-path-slug: restapiv1-0glipwebhookswebhookid-get
      parameters:
      - in: path
        name: webhookId
        description: Internal identifier of a webhook or comma separated list of webhooks
          IDs
      responses:
        200:
          description: OK
      tags:
      - Webhook
    delete:
      summary: Delete Webhook
      description: |-
        Deletes the webhook by ID.
        Usage Plan Group
        Medium
      operationId: deleteGlipWebhook
      x-api-path-slug: restapiv1-0glipwebhookswebhookid-delete
      parameters:
      - in: path
        name: webhookId
        description: Internal identifier of a webhook
      responses:
        200:
          description: OK
      tags:
      - Webhook
  /restapi/v1.0/glip/webhooks/{webhookId}/activate:
    post:
      summary: Activate Webhook
      description: |-
        Activates webhooks by ID.
        Usage Plan Group
        Medium
      operationId: activateGlipWebhook
      x-api-path-slug: restapiv1-0glipwebhookswebhookidactivate-post
      parameters:
      - in: path
        name: webhookId
        description: Internal identifier of a webhook
      responses:
        200:
          description: OK
      tags:
      - Activate
      - Webhook
  /restapi/v1.0/glip/webhooks/{webhookId}/suspend:
    post:
      summary: Suspend Webhook
      description: |-
        Suspends webhooks by ID.
        Usage Plan Group
        Medium
      operationId: suspendGlipWebhook
      x-api-path-slug: restapiv1-0glipwebhookswebhookidsuspend-post
      parameters:
      - in: path
        name: webhookId
        description: Internal identifier of a webhook
      responses:
        200:
          description: OK
      tags:
      - Suspend
      - Webhook
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