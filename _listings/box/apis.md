---
name: Box
x-slug: box
description: Box Inc. (formerly Box.net) is an online file sharing and Cloud content
  management service for enterprise companies. The company has adopted a freemium
  business model, and provides 5 GB of free storage [3] for personal accounts. A mobile
  version of the service is available for Android, BlackBerry, iOS, WebOS, and Windows
  Phone devices. The company is based in Los Altos, California.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/box1200x630.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: Webhooks
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/box/apis.md
specificationVersion: "0.14"
apis:
- name: Box Create Webhook
  x-api-slug: box
  description: Create Webhook
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/box1200x630.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//webhooks
  tags: Documents,Webhooks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/box/webhooks-post-openapi.md
- name: Box Get Webhooks
  x-api-slug: box
  description: |-
    Returns all defined webhooks for the requesting application and user, up to the limit. If no limit is supplied then Box uses the default limit of 100.
    If more than limit webhooks are defined then Box returns the webhooks in batches. When the results are batched, Box sends limit webhooks along with a next_marker field in the response object. The value of the next_marker field is a marker string that you can use in later requests to tell Box which batch to send next.
    When you send a request that includes a marker string, Box sends the next batch of webhooks, beginning after the last webhook of the previous batch. When the response contains the last of the defined webhooks, Box omits the next_marker field from its response.
    You can use limit and marker together with the marker string returned in the next_marker field to paginate lists of webhooks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/box1200x630.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//webhooks
  tags: Documents,Webhooks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/box/webhooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/box/webhooks-get-openapi.md
- name: Box Get Webhook
  x-api-slug: box
  description: Get a Webhook
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/box1200x630.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//webhooks/{WEBHOOK_ID}
  tags: Documents,Webhooks, Webhook
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/box/webhookswebhook-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/box/webhookswebhook-id-get-openapi.md
- name: Box Update Webhook
  x-api-slug: box
  description: Update a Webhook
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/box1200x630.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//webhooks/{WEBHOOK_ID}
  tags: Documents,Webhooks, Webhook
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/box/webhookswebhook-id-put-openapi.md
- name: Box Delete Webhook
  x-api-slug: box
  description: Permanently deletes a webhook
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/box1200x630.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0//webhooks/{WEBHOOK_ID}
  tags: Documents,Webhooks, Webhook
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/box/webhookswebhook-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/box/webhookswebhook-id-delete-openapi.md
- name: Box
  x-api-slug: box
  description: Box.net provides a sophisticated API for their online document sharing
    and collaboration web application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/box1200x630.jpg
  humanURL: http://box.com
  baseURL: https://api.box.com//2.0
  tags: Webhooks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/box/openapi.md
x-common:
- type: x-base
  url: https://api.box.com/
- type: x-blog
  url: http://blog.box.com/
- type: x-blog-rss
  url: http://blog.box.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/box
- type: x-developer
  url: http://developers.box.com
- type: x-github
  url: https://github.com/boxdotnet
- type: x-pricing
  url: https://developers.box.com/box-platform-pricing/
- type: x-road-map
  url: https://developers.box.com/roadmap/
- type: x-twitter
  url: https://twitter.com/BoxPlatform
- type: x-website
  url: http://box.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---