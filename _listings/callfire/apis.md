---
name: CallFire
x-slug: callfire
description: Grow your business with virtual phone numbers, IVR, voice broadcasting,
  mass text messaging services and power dialing. Try CallFire for FREE!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
x-kinRank: "9"
x-alexaRank: "129466"
tags: Webhooks
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/callfire/apis.md
specificationVersion: "0.14"
apis:
- name: CallFire - Find webhooks
  x-api-slug: webhooks-get
  description: Searches all webhooks available for a current user. Searches by name,
    resource, event, callback URL, or whether they are enabled. Returns a paged list
    of Webhooks
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/callfire/webhooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/callfire/webhooks-get-openapi.md
- name: CallFire - Create a webhook
  x-api-slug: webhooks-post
  description: 'Create a Webhook for notification in the CallFire system. Use the
    webhooks API to receive notifications of important CallFire events. Select the
    resource to listen to, and then choose the resource events to receive notifications
    on. When an event triggers, a POST will be made to the callback URL with a payload
    of notification information. Available resources and their events include ''CccCampaign'':
    [''started'', ''stopped'', ''finished''], ''CallBroadcast'': [''started'', ''stopped'',
    ''finished''], ''TextBroadcast'': [''started'', ''stopped'', ''finished''], ''OutboundCall'':
    [''finished''], ''InboundCall'': [''finished''], ''OutboundText'': [''finished''],
    ''InboundText'': [''finished''], ''ContactList'': [''validationFinished'', ''validationFailed''].
    Webhooks support secret token which is used as signing key to HmacSHA1 hash of
    json payload which is returned in ''X-CallFire-Signature'' header. This header
    can be used to verify callback POST is coming from CallFire. See [security guide](https://developers.callfire.com/security-guide.html)'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/callfire/webhooks-post-openapi.md
- name: CallFire - Find webhook resources
  x-api-slug: webhooksresources-get
  description: 'Searches for webhook resources. Available resources include ''CccCampaign'':
    [''started'', ''stopped'', ''finished''], ''CallBroadcast'': [''started'', ''stopped'',
    ''finished''], ''TextBroadcast'': [''started'', ''stopped'', ''finished''], ''OutboundCall'':
    [''finished''], ''InboundCall'': [''finished''], ''OutboundText'': [''finished''],
    ''InboundText'': [''finished''], ''ContactList'': [''validationFinished'', ''validationFailed'']'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/callfire/webhooksresources-get-openapi.md
- name: CallFire - Find specific webhook resource
  x-api-slug: webhooksresourcesresource-get
  description: Returns information about supported events for a given webhook resource
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/callfire/webhooksresourcesresource-get-openapi.md
- name: CallFire - Delete a webhook
  x-api-slug: webhooksid-delete
  description: Deletes a webhook instance. Will be removed permanently
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/callfire/webhooksid-delete-openapi.md
- name: CallFire - Find a specific webhook
  x-api-slug: webhooksid-get
  description: Returns a single Webhook instance for a given webhook id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/callfire/webhooksid-get-openapi.md
- name: CallFire - Update a webhook
  x-api-slug: webhooksid-put
  description: Updates the information in existing webhook
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11768-callfire.jpg
  humanURL: http://www.callfire.com
  baseURL: https://www.callfire.com//v2
  tags: SMS, Voice, Stack Network, Getting Started Example, Telecommunications, Technology,
    SaaS, API Provider, Telecommunications, Messages, Profiles, Service API, Relative
    Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/callfire/webhooksid-put-openapi.md
x-common:
- type: x--net-sdk
  url: https://github.com/CallFire/CallFire-CSharp-SDK
- type: x-account-billing
  url: https://answers.callfire.com/hc/en-us/sections/200166268-Billing
- type: x-account-settings
  url: https://answers.callfire.com/hc/en-us/sections/200187056-Account-Settings
- type: x-api-gallery
  url: http://bureau.of.justice.statistics.api.gallery.streamdata.io
- type: x-api-stack
  url: http://callfire.stack.network
- type: x-authentication
  url: https://www.callfire.com/api-documentation/how-do-i-enable-api-on-my-account
- type: x-blog
  url: https://www.callfire.com/blog
- type: x-blog-rss
  url: https://www.callfire.com/blog/feed
- type: x-twitter
  url: https://twitter.com/CallFire
- type: x-case-studies
  url: https://www.callfire.com/case-studies
- type: x-compliance
  url: https://www.callfire.com/legal/compliance
- type: x-contact-form
  url: https://www.callfire.com/contact
- type: x-crunchbase
  url: https://www.crunchbase.com/organization/callfire
- type: x-crunchbase
  url: https://crunchbase.com/organization/callfire
- type: x-developer
  url: https://www.callfire.com/api-documentation
- type: x-documentation
  url: https://www.callfire.com/api-documentation/rest/version/1.1
- type: x-drupal-plugin
  url: https://github.com/CallFire/CallFire-Drupal-Integration
- type: x-email
  url: answers@callfire.com
- type: x-email
  url: support@callfire.com
- type: x-facebook
  url: https://www.facebook.com/callfire
- type: x-faq
  url: https://answers.callfire.com/hc/en-us/sections/200193833-FAQs
- type: x-getting-started
  url: https://www.callfire.com/help/docs/getting-started
- type: x-github
  url: https://github.com/callfire
- type: x-glossary
  url: https://www.callfire.com/help/glossary/communications
- type: x-google-plus
  url: https://plus.google.com/100142045997033051154
- type: x-messages
  url: https://www.callfire.com/ui/number/messages?6
- type: x-partners
  url: https://www.callfire.com/partners
- type: x-phone
  url: 1.877.897.3473
- type: x-php-sdk
  url: https://github.com/CallFire/CallFire-PHP-SDK
- type: x-pricing
  url: https://www.callfire.com/pricing
- type: x-privacy
  url: https://www.callfire.com/legal/privacy
- type: x-selfservice-registration
  url: https://www.callfire.com/ui/register?1
- type: x-terms-of-service
  url: https://www.callfire.com/legal/terms
- type: x-tickets
  url: https://answers.callfire.com/hc/en-us/requests/new
- type: x-tour
  url: javascript:;
- type: x-videos
  url: https://answers.callfire.com/hc/en-us/articles/200849247-Videos
- type: x-webinars
  url: https://answers.callfire.com/hc/en-us/articles/202174798-Webinars
- type: x-website
  url: http://www.callfire.com
- type: x-wordpress-plugin
  url: https://github.com/CallFire/CallFire-WordPress-Integration
- type: x-youtube
  url: https://www.youtube.com/user/CallFireTelephony
- type: x-zapier
  url: https://zapier.com/zapbook/callfire/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---