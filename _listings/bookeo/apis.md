---
name: Bookeo
x-slug: bookeo
description: Bookeo provides a leading online booking and scheduling system for tours,
  classes, and appointments, to help you save money and time. Click to learn more!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
x-kinRank: "7"
x-alexaRank: "23042"
tags: Webhooks
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/apis.md
specificationVersion: "0.14"
apis:
- name: Bookeo - List all webhooks
  x-api-slug: webhooks-get
  description: Retrieve all the webhooks for this api key
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhooks-get-openapi.md
- name: Bookeo - Create a new webhook
  x-api-slug: webhooks-post
  description: |-
    Note that if an existing webhook for the same domain and type was already set for this api key, it will be automatically replaced by this new webhook.
     In other words, there can be only one webhook for each combination of domain and type, for an API key.
     So to upgrade an existing webhook URL, simply create a new one with the same domain and type, but a different URL.

     For webhook with domain "bookings" and type "deleted", the notification will be sent whether the booking is canceled or completely deleted.
     Users can delete bookings by, for example, deleting their associated customer.
     Also note that these "bookings" "deleted" notifications are sent even for bookings in the past.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhooks-post-openapi.md
- name: Bookeo - Retrieve a webhook
  x-api-slug: webhookswebhookid-get
  description: Retrieve a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhookswebhookid-get-openapi.md
- name: Bookeo - Delete a webhook
  x-api-slug: webhookswebhookid-delete
  description: Delete a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhookswebhookid-delete-openapi.md
- name: Bookeo - Retrieve a webhook
  x-api-slug: webhookswebhookid-get
  description: Retrieve a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhookswebhookid-get-openapi.md
- name: Bookeo - Delete a webhook
  x-api-slug: webhookswebhookid-delete
  description: Delete a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhookswebhookid-delete-openapi.md
- name: Bookeo - Retrieve a webhook
  x-api-slug: webhookswebhookid-get
  description: Retrieve a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhookswebhookid-get-openapi.md
- name: Bookeo - Delete a webhook
  x-api-slug: webhookswebhookid-delete
  description: Delete a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhookswebhookid-delete-openapi.md
- name: Bookeo - Delete a webhook
  x-api-slug: webhookswebhookid-delete
  description: Delete a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhookswebhookid-delete-openapi.md
- name: Bookeo - Delete a webhook
  x-api-slug: webhookswebhookid-delete
  description: Delete a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhookswebhookid-delete-openapi.md
- name: Bookeo - Retrieve a webhook
  x-api-slug: webhookswebhookid-get
  description: Retrieve a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhookswebhookid-get-openapi.md
- name: Bookeo - Retrieve a webhook
  x-api-slug: webhookswebhookid-get
  description: Retrieve a webhook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28769-www-bookeo-com.jpg
  humanURL: https://www.bookeo.com
  baseURL: https://api.bookeo.com//v2
  tags: Bookings, Schedules, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/bookeo/webhookswebhookid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://bmc.software.api.gallery.streamdata.io
- type: x-api-stack
  url: http://bookeo.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/bookeo
- type: x-developer
  url: https://www.bookeo.com/api/
- type: x-documentation
  url: https://www.bookeo.com/apiref/index.html
- type: x-partners
  url: https://www.bookeo.com/affiliate/
- type: x-privacy-policy
  url: https://www.bookeo.com/privacy/
- type: x-terms-of-service
  url: https://www.bookeo.com/termsofservice/
- type: x-twitter
  url: https://twitter.com/bookeo
- type: x-webhook
  url: https://www.bookeo.com/api/webhooks/
- type: x-website
  url: https://www.bookeo.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---