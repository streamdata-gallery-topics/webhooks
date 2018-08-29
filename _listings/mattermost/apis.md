---
name: Mattermost
x-slug: mattermost
description: Open source, private cloud Slack-alternative, Workplace messaging for
  web, PCs and phones. MIT-licensed. Hundreds of contributors. 14 languages. Secure,
  configurable, and scalable from teams to the enterprise.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
x-kinRank: "8"
x-alexaRank: "95684"
tags: Webhooks
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/apis.md
specificationVersion: "0.14"
apis:
- name: Mattermost API Reference - List incoming webhooks
  x-api-slug: hooksincoming-get
  description: |-
    Get a page of a list of incoming webhooks. Optionally filter for a specific team using query parameters.
    ##### Permissions
    `manage_webhooks` for the system or `manage_webhooks` for the specific team.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksincoming-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksincoming-get-openapi.md
- name: Mattermost API Reference - List outgoing webhooks
  x-api-slug: hooksoutgoing-get
  description: |-
    Get a page of a list of outgoing webhooks. Optionally filter for a specific team or channel using query parameters.
    ##### Permissions
    `manage_webhooks` for the system or `manage_webhooks` for the specific team/channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoing-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoing-get-openapi.md
- name: Mattermost API Reference - Regenerate the token for the outgoing webhook.
  x-api-slug: hooksoutgoinghook-idregen-token-post
  description: |-
    Regenerate the token for the outgoing webhook.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-idregen-token-post-openapi.md
- name: Mattermost API Reference - Create an incoming webhook
  x-api-slug: hooksincoming-post
  description: |-
    Create an incoming webhook for a channel.
    ##### Permissions
    `manage_webhooks` for the channel the webhook is in.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksincoming-post-openapi.md
- name: Mattermost API Reference - Get an incoming webhook
  x-api-slug: hooksincominghook-id-get
  description: |-
    Get an incoming webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksincominghook-id-get-openapi.md
- name: Mattermost API Reference - Update an incoming webhook
  x-api-slug: hooksincominghook-id-put
  description: |-
    Update an incoming webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksincominghook-id-put-openapi.md
- name: Mattermost API Reference - Create an outgoing webhook
  x-api-slug: hooksoutgoing-post
  description: |-
    Create an outgoing webhook for a team.
    ##### Permissions
    `manage_webhooks` for the team the webhook is in.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoing-post-openapi.md
- name: Mattermost API Reference - Get an outgoing webhook
  x-api-slug: hooksoutgoinghook-id-get
  description: |-
    Get an outgoing webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-id-get-openapi.md
- name: Mattermost API Reference - Delete an outgoing webhook
  x-api-slug: hooksoutgoinghook-id-delete
  description: |-
    Delete an outgoing webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-id-delete-openapi.md
- name: Mattermost API Reference - Update an outgoing webhook
  x-api-slug: hooksoutgoinghook-id-put
  description: |-
    Update an outgoing webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-id-put-openapi.md
- name: Mattermost API Reference - Create an incoming webhook
  x-api-slug: hooksincoming-post
  description: |-
    Create an incoming webhook for a channel.
    ##### Permissions
    `manage_webhooks` for the channel the webhook is in.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksincoming-post-openapi.md
- name: Mattermost API Reference - Get an incoming webhook
  x-api-slug: hooksincominghook-id-get
  description: |-
    Get an incoming webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksincominghook-id-get-openapi.md
- name: Mattermost API Reference - Update an incoming webhook
  x-api-slug: hooksincominghook-id-put
  description: |-
    Update an incoming webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksincominghook-id-put-openapi.md
- name: Mattermost API Reference - Create an outgoing webhook
  x-api-slug: hooksoutgoing-post
  description: |-
    Create an outgoing webhook for a team.
    ##### Permissions
    `manage_webhooks` for the team the webhook is in.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoing-post-openapi.md
- name: Mattermost API Reference - Get an outgoing webhook
  x-api-slug: hooksoutgoinghook-id-get
  description: |-
    Get an outgoing webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-id-get-openapi.md
- name: Mattermost API Reference - Delete an outgoing webhook
  x-api-slug: hooksoutgoinghook-id-delete
  description: |-
    Delete an outgoing webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-id-delete-openapi.md
- name: Mattermost API Reference - Update an outgoing webhook
  x-api-slug: hooksoutgoinghook-id-put
  description: |-
    Update an outgoing webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-id-put-openapi.md
- name: Mattermost API Reference - Regenerate the token for the outgoing webhook.
  x-api-slug: hooksoutgoinghook-idregen-token-post
  description: |-
    Regenerate the token for the outgoing webhook.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-idregen-token-post-openapi.md
- name: Mattermost API Reference - Update an outgoing webhook
  x-api-slug: hooksoutgoinghook-id-put
  description: |-
    Update an outgoing webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-id-put-openapi.md
- name: Mattermost API Reference - Delete an outgoing webhook
  x-api-slug: hooksoutgoinghook-id-delete
  description: |-
    Delete an outgoing webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-id-delete-openapi.md
- name: Mattermost API Reference - Get an outgoing webhook
  x-api-slug: hooksoutgoinghook-id-get
  description: |-
    Get an outgoing webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-id-get-openapi.md
- name: Mattermost API Reference - Create an outgoing webhook
  x-api-slug: hooksoutgoing-post
  description: |-
    Create an outgoing webhook for a team.
    ##### Permissions
    `manage_webhooks` for the team the webhook is in.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoing-post-openapi.md
- name: Mattermost API Reference - Update an incoming webhook
  x-api-slug: hooksincominghook-id-put
  description: |-
    Update an incoming webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksincominghook-id-put-openapi.md
- name: Mattermost API Reference - Get an incoming webhook
  x-api-slug: hooksincominghook-id-get
  description: |-
    Get an incoming webhook given the hook id.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksincominghook-id-get-openapi.md
- name: Mattermost API Reference - Create an incoming webhook
  x-api-slug: hooksincoming-post
  description: |-
    Create an incoming webhook for a channel.
    ##### Permissions
    `manage_webhooks` for the channel the webhook is in.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksincoming-post-openapi.md
- name: Mattermost API Reference - Regenerate the token for the outgoing webhook.
  x-api-slug: hooksoutgoinghook-idregen-token-post
  description: |-
    Regenerate the token for the outgoing webhook.
    ##### Permissions
    `manage_webhooks` for system or `manage_webhooks` for the specific team or `manage_webhooks` for the channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/mattermost-logo.png
  humanURL: https://mattermost.com
  baseURL: https://your-mattermost-url.com//api/v4
  tags: Enterprise, SaaS, Technology, Cloud, API Provider, API Service Provider, Profiles,
    Relative Data, Service API, Networks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/mattermost/hooksoutgoinghook-idregen-token-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://matrix.api.gallery.streamdata.io
- type: x-api-stack
  url: http://mattermost.stack.network
- type: x-blog
  url: https://about.mattermost.com/blog/
- type: x-blog-rss
  url: https://about.mattermost.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/mattermost
- type: x-developer
  url: https://api.mattermost.com/
- type: x-github
  url: https://github.com/mattermost
- type: x-pricing
  url: https://about.mattermost.com/pricing/
- type: x-security
  url: https://docs.mattermost.com/overview/security.html
- type: x-twitter
  url: https://twitter.com/mattermosthq
- type: x-website
  url: https://mattermost.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---