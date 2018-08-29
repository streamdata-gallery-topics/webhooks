---
name: Docsmore
x-slug: docsmore
description: FORM.FILL.SIGN - With Docsmore, the process of setting up a form and
  sending to users to complete or sign is simplified.  Use our platform to easily
  upload a document, specify form fields/signage, and send to users for completion.  Present
  forms to you...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
x-kinRank: "7"
x-alexaRank: "7238418"
tags: Webhooks
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apis.md
specificationVersion: "0.14"
apis:
- name: Docsmore API 2.1 - List all Webhooks
  x-api-slug: apigetwebhooks-get
  description: List Webhooks that are both active and inactive. Inactive webhooks
    with webhook type of 'static' will be automatically removed during the nightly
    job process.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
  humanURL: http://api.docsmore.com
  baseURL: https://api.docsmore.com//
  tags: SaaS, Technology, Documents, Forms
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apigetwebhooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apigetwebhooks-get-openapi.md
- name: Docsmore API 2.1 - List all Webhooks
  x-api-slug: apigetwebhooks-get
  description: List Webhooks that are both active and inactive. Inactive webhooks
    with webhook type of 'static' will be automatically removed during the nightly
    job process.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
  humanURL: http://api.docsmore.com
  baseURL: https://api.docsmore.com//
  tags: SaaS, Technology, Documents, Forms
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apigetwebhooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apigetwebhooks-get-openapi.md
- name: Docsmore API 2.1 - Get Details of Single Webhook
  x-api-slug: apigetwebhooksid-get
  description: Details of Single Webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
  humanURL: http://api.docsmore.com
  baseURL: https://api.docsmore.com//
  tags: SaaS, Technology, Documents, Forms
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apigetwebhooksid-get-openapi.md
- name: Docsmore API 2.1 - Subscribe To Webhook
  x-api-slug: apiwebhooksubscribe-post
  description: |-
    Make sure you have a unique payload URL every time you use this api call to register your webhook. Unable to do so will result in webhook registration denial.


    For multiple events subscription, just use it comma separated values. Here are the available list of register events.



    documentUploadComplete
    workflowProgressEvent
    workflowCompleteEvent
    documentflowProgressEvent
    documentflowCompleteEvent
    documentSelfSigninCompleteEvent
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
  humanURL: http://api.docsmore.com
  baseURL: https://api.docsmore.com//
  tags: SaaS, Technology, Documents, Forms
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apiwebhooksubscribe-post-openapi.md
- name: Docsmore API 2.1 - Unsubscribe Webhook
  x-api-slug: apiwebhookunsubscribeid-delete
  description: It is important that you call this event to unsubscribe otherwise it
    will automatically be removed in 10 minutes. If not unsubscribed manually, it
    can also lead to the problem of duplication and create further issues.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
  humanURL: http://api.docsmore.com
  baseURL: https://api.docsmore.com//
  tags: SaaS, Technology, Documents, Forms
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apiwebhookunsubscribeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apiwebhookunsubscribeid-delete-openapi.md
- name: Docsmore API 2.1 - Get Details of Single Webhook
  x-api-slug: apigetwebhooksid-get
  description: Details of Single Webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
  humanURL: http://api.docsmore.com
  baseURL: https://api.docsmore.com//
  tags: SaaS, Technology, Documents, Forms
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apigetwebhooksid-get-openapi.md
- name: Docsmore API 2.1 - Unsubscribe Webhook
  x-api-slug: apiwebhookunsubscribeid-delete
  description: It is important that you call this event to unsubscribe otherwise it
    will automatically be removed in 10 minutes. If not unsubscribed manually, it
    can also lead to the problem of duplication and create further issues.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
  humanURL: http://api.docsmore.com
  baseURL: https://api.docsmore.com//
  tags: SaaS, Technology, Documents, Forms
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apiwebhookunsubscribeid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apiwebhookunsubscribeid-delete-openapi.md
- name: Docsmore API 2.1 - Subscribe To Webhook
  x-api-slug: apiwebhooksubscribe-post
  description: |-
    Make sure you have a unique payload URL every time you use this api call to register your webhook. Unable to do so will result in webhook registration denial.


    For multiple events subscription, just use it comma separated values. Here are the available list of register events.



    documentUploadComplete
    workflowProgressEvent
    workflowCompleteEvent
    documentflowProgressEvent
    documentflowCompleteEvent
    documentSelfSigninCompleteEvent
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
  humanURL: http://api.docsmore.com
  baseURL: https://api.docsmore.com//
  tags: SaaS, Technology, Documents, Forms
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apiwebhooksubscribe-post-openapi.md
- name: Docsmore API 2.1 - Get Details of Single Webhook
  x-api-slug: apigetwebhooksid-get
  description: Details of Single Webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28946-api-docsmore-com.jpg
  humanURL: http://api.docsmore.com
  baseURL: https://api.docsmore.com//
  tags: SaaS, Technology, Documents, Forms
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/docsmore/apigetwebhooksid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://digitalocean.api.gallery.streamdata.io
- type: x-email
  url: contact@docsmore.com
- type: x-twitter
  url: https://twitter.com/docsmore
- type: x-website
  url: http://api.docsmore.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---