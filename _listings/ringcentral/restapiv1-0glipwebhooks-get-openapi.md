---
swagger: "2.0"
x-collection-name: RingCentral
x-complete: 0
info:
  title: RingCentral Get Webhooks
  description: |-
    Returns all webhooks.
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