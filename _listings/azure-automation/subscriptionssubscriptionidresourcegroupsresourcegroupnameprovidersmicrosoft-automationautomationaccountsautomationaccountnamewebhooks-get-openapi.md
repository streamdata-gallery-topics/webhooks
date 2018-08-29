---
swagger: "2.0"
x-collection-name: Azure Automation
x-complete: 0
info:
  title: Azure Automation API Webhook List By Automation Account
  version: 1.0.0
  description: Retrieve a list of webhooks.
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/webhooks/generateUri
  : post:
      summary: Webhook Generate Uri
      description: Generates a Uri for use in creating a webhook.
      operationId: Webhook_GenerateUri
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamewebhooksgenerateuri-post
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Webhook
      - Generate
      - Uri
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/webhooks/{webhookName}
  : delete:
      summary: Webhook Delete
      description: Delete the webhook by name.
      operationId: Webhook_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamewebhookswebhookname-delete
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      - in: path
        name: webhookName
        description: The webhook name
      responses:
        200:
          description: OK
      tags:
      - Webhook
    get:
      summary: Webhook Get
      description: Retrieve the webhook identified by webhook name.
      operationId: Webhook_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamewebhookswebhookname-get
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      - in: path
        name: webhookName
        description: The webhook name
      responses:
        200:
          description: OK
      tags:
      - Webhook
    put:
      summary: Webhook Create Or Update
      description: Create the webhook identified by webhook name.
      operationId: Webhook_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamewebhookswebhookname-put
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The create or update parameters for webhook
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: webhookName
        description: The webhook name
      responses:
        200:
          description: OK
      tags:
      - Webhook
      - Or
    patch:
      summary: Webhook Update
      description: Update the webhook identified by webhook name.
      operationId: Webhook_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamewebhookswebhookname-patch
      parameters:
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      - in: body
        name: parameters
        description: The update parameters for webhook
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: webhookName
        description: The webhook name
      responses:
        200:
          description: OK
      tags:
      - Webhook
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Automation/automationAccounts/{automationAccountName}/webhooks
  : get:
      summary: Webhook List By Automation Account
      description: Retrieve a list of webhooks.
      operationId: Webhook_ListByAutomationAccount
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-automationautomationaccountsautomationaccountnamewebhooks-get
      parameters:
      - in: query
        name: $filter
        description: The filter to apply on the operation
      - in: path
        name: automationAccountName
        description: The automation account name
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Webhook
      - List
      - Automation
      - Account
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