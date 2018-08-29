---
name: LiveChat
x-slug: livechat
description: LiveChat is an offline customer service software with live support, help
  desk software, and web analytics capabilities.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28877-developers-livechatinc-com.jpg
x-kinRank: "7"
x-alexaRank: "4371"
tags: Webhooks
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/livechat/apis.md
specificationVersion: "0.14"
apis:
- name: LiveChat REST API - Display configured webhooks
  x-api-slug: webhooks-get
  description: Returns a list of webhooks that have been created in a LiveChat account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28877-developers-livechatinc-com.jpg
  humanURL: https://www.livechatinc.com/
  baseURL: https://api.livechatinc.com//
  tags: SaaS, Technology, Support, Chats
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/livechat/webhooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/livechat/webhooks-get-openapi.md
- name: LiveChat REST API - Create a new webhook
  x-api-slug: webhooks-post
  description: Creates a new webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28877-developers-livechatinc-com.jpg
  humanURL: https://www.livechatinc.com/
  baseURL: https://api.livechatinc.com//
  tags: SaaS, Technology, Support, Chats
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/livechat/webhooks-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/livechat/webhooks-post-openapi.md
- name: LiveChat REST API - Delete a webhook
  x-api-slug: webhooks12345-delete
  description: Deletes a webhook with the given ID.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28877-developers-livechatinc-com.jpg
  humanURL: https://www.livechatinc.com/
  baseURL: https://api.livechatinc.com//
  tags: SaaS, Technology, Support, Chats
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/livechat/webhooks12345-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/livechat/webhooks12345-delete-openapi.md
x-common:
- type: x-website
  url: https://www.livechatinc.com/
- type: x-api-gallery
  url: http://lisk.api.gallery.streamdata.io
- type: x-crunchbase
  url: https://crunchbase.com/organization/livechatsoftware
- type: x-email
  url: support@livechatinc.com
- type: x-twitter
  url: https://twitter.com/LiveChat
- type: x-developer
  url: https://developers.livechatinc.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---