---
name: Ship Station
x-slug: ship-station
description: ShipStation is a web-based shipping solution that streamlines the order
  fulfillment process for your online business. ShipStation consolidates orders from
  over 70 ecommerce channels, creates shipping labels, packing slips, and pick lists
  in batch, communicates tracking information to your customers, provides endless
  automation, filters, and views, wireless printing, a mobile app, and a lot more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
x-kinRank: "7"
x-alexaRank: "0"
tags: Webhooks
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/ship-station/apis.md
specificationVersion: "0.14"
apis:
- name: Ship Station Developer Portal - List Webhooks
  x-api-slug: webhooks-get
  description: Retrieves a list of registered webhooks for the account
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/ship-station/webhooks-get-openapi.md
- name: Ship Station Developer Portal - Subscribe to Webhook
  x-api-slug: webhookssubscribe-post
  description: |-
    Subscribes to a specific type of webhook. If a ``store_id`` is passed in, the webhooks will only be triggered for that specific ``store_id``.
    The ``event`` type that is passed in will determine what type of webhooks will be sent.

    NOTE: Webhooks will be sent to the URL specified in the ``target_url``. The HTTP request will be sent via POST and will contain a [**webhook JSON object**](https://www.shipstation.com/developer-api/#/reference/model-webhook) in the body.

    The body of this request to subscribe has the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
    ``target_url``  | string, required | The URL to send the webhooks to
    ``event`` | string, required | The type of webhook to subscribe to. Must contain one of the following values: ORDER_NOTIFY, ITEM_ORDER_NOTIFY, SHIP_NOTIFY, ITEM_SHIP_NOTIFY
    ``store_id`` | int, optional | If passed in, the webhooks will only be triggered for this ``store_id``
    ``friendly_name`` | string, optional | Display name for the webhook
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/ship-station/webhookssubscribe-post-openapi.md
- name: Ship Station Developer Portal - Unsubscribe to Webhook
  x-api-slug: webhookswebhookid-delete
  description: Unsubscribes from a certain webhook.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/ship-station/webhookswebhookid-delete-openapi.md
- name: Ship Station Developer Portal - Subscribe to Webhook
  x-api-slug: webhookssubscribe-post
  description: |-
    Subscribes to a specific type of webhook. If a ``store_id`` is passed in, the webhooks will only be triggered for that specific ``store_id``.
    The ``event`` type that is passed in will determine what type of webhooks will be sent.

    NOTE: Webhooks will be sent to the URL specified in the ``target_url``. The HTTP request will be sent via POST and will contain a [**webhook JSON object**](https://www.shipstation.com/developer-api/#/reference/model-webhook) in the body.

    The body of this request to subscribe has the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
    ``target_url``  | string, required | The URL to send the webhooks to
    ``event`` | string, required | The type of webhook to subscribe to. Must contain one of the following values: ORDER_NOTIFY, ITEM_ORDER_NOTIFY, SHIP_NOTIFY, ITEM_SHIP_NOTIFY
    ``store_id`` | int, optional | If passed in, the webhooks will only be triggered for this ``store_id``
    ``friendly_name`` | string, optional | Display name for the webhook
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/ship-station/webhookssubscribe-post-openapi.md
- name: Ship Station Developer Portal - Unsubscribe to Webhook
  x-api-slug: webhookswebhookid-delete
  description: Unsubscribes from a certain webhook.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/ship-station/webhookswebhookid-delete-openapi.md
- name: Ship Station Developer Portal - Unsubscribe to Webhook
  x-api-slug: webhookswebhookid-delete
  description: Unsubscribes from a certain webhook.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/ship-station/webhookswebhookid-delete-openapi.md
- name: Ship Station Developer Portal - Subscribe to Webhook
  x-api-slug: webhookssubscribe-post
  description: |-
    Subscribes to a specific type of webhook. If a ``store_id`` is passed in, the webhooks will only be triggered for that specific ``store_id``.
    The ``event`` type that is passed in will determine what type of webhooks will be sent.

    NOTE: Webhooks will be sent to the URL specified in the ``target_url``. The HTTP request will be sent via POST and will contain a [**webhook JSON object**](https://www.shipstation.com/developer-api/#/reference/model-webhook) in the body.

    The body of this request to subscribe has the following attributes:

    Name               |Data Type          |Description
    -------------------|-------------------|-------------------
    ``target_url``  | string, required | The URL to send the webhooks to
    ``event`` | string, required | The type of webhook to subscribe to. Must contain one of the following values: ORDER_NOTIFY, ITEM_ORDER_NOTIFY, SHIP_NOTIFY, ITEM_SHIP_NOTIFY
    ``store_id`` | int, optional | If passed in, the webhooks will only be triggered for this ``store_id``
    ``friendly_name`` | string, optional | Display name for the webhook
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/ShipStation-stacked-blue.png
  humanURL: http://bit.ly/_ShipStation
  baseURL: https://ssapi.shipstation.com//
  tags: Shipping, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/ship-station/webhookssubscribe-post-openapi.md
x-common:
- type: x-website
  url: http://bit.ly/_ShipStation
- type: x-api-gallery
  url: http://server.density.api.gallery.streamdata.io
- type: x-api-stack
  url: http://ship.station.stack.network
- type: x-blog
  url: https://www.shipstation.com/blog/
- type: x-developer
  url: https://shipstation.docs.apiary.io/#
- type: x-github
  url: https://github.com/shipstation
- type: x-partners
  url: https://www.shipstation.com/partners/
- type: x-pricing
  url: https://www.shipstation.com/pricing/
- type: x-twitter
  url: https://twitter.com/ShipStation
- type: x-website
  url: http://shipstation.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---