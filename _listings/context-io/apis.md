---
name: Context.IO
x-slug: context-io
description: Create simple email webhooks and code against a free, RESTful, IMAP API.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
x-kinRank: "9"
x-alexaRank: "569975"
tags: Webhooks
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/apis.md
specificationVersion: "0.14"
apis:
- name: Context.IO - Get Accounts Webhooks
  x-api-slug: accountsidwebhooks-get
  description: List WebHooks configured for an account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhooks-get-openapi.md
- name: Context.IO - Post Accounts Webhooks
  x-api-slug: accountsidwebhooks-post
  description: Creates a new WebHook on an account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhooks-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhooks-post-openapi.md
- name: Context.IO - Get Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-get
  description: Gets properties of a given WebHook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-get-openapi.md
- name: Context.IO - Post Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-post
  description: |-
    Changes properties of a given WebHook. The only property of a WebHook that can be changed is it's active property. If you want to change the filters or callback urls, delete it and create a new one.
    Changing the active property can be useful in two cases:
    - Pause/resume WebHooks: If your application needs up-to-date information when users are logged in the best option is to keep a WebHook with no filters on that account that will be resumed (setting active to 1) when the user logs in and paused (setting active to 0) when the user logs out of your app.
    - Acting upon a failure notification: If a WebHook fails, your failure_notif_url is called (see creating a WebHook) an its active property becomes 0. Set the active property back to 1 to get it working again.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-post-openapi.md
- name: Context.IO - Delete Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-delete
  description: Cancels a WebHook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-delete-openapi.md
- name: Context.IO - Get Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-get
  description: Gets properties of a given WebHook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-get-openapi.md
- name: Context.IO - Post Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-post
  description: |-
    Changes properties of a given WebHook. The only property of a WebHook that can be changed is it's active property. If you want to change the filters or callback urls, delete it and create a new one.
    Changing the active property can be useful in two cases:
    - Pause/resume WebHooks: If your application needs up-to-date information when users are logged in the best option is to keep a WebHook with no filters on that account that will be resumed (setting active to 1) when the user logs in and paused (setting active to 0) when the user logs out of your app.
    - Acting upon a failure notification: If a WebHook fails, your failure_notif_url is called (see creating a WebHook) an its active property becomes 0. Set the active property back to 1 to get it working again.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-post-openapi.md
- name: Context.IO - Delete Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-delete
  description: Cancels a WebHook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-delete-openapi.md
- name: Context.IO - Get Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-get
  description: Gets properties of a given WebHook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-get-openapi.md
- name: Context.IO - Post Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-post
  description: |-
    Changes properties of a given WebHook. The only property of a WebHook that can be changed is it's active property. If you want to change the filters or callback urls, delete it and create a new one.
    Changing the active property can be useful in two cases:
    - Pause/resume WebHooks: If your application needs up-to-date information when users are logged in the best option is to keep a WebHook with no filters on that account that will be resumed (setting active to 1) when the user logs in and paused (setting active to 0) when the user logs out of your app.
    - Acting upon a failure notification: If a WebHook fails, your failure_notif_url is called (see creating a WebHook) an its active property becomes 0. Set the active property back to 1 to get it working again.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-post-openapi.md
- name: Context.IO - Delete Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-delete
  description: Cancels a WebHook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-delete-openapi.md
- name: Context.IO - Get Accounts Webhooks
  x-api-slug: accountsidwebhooks-get
  description: List WebHooks configured for an account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhooks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhooks-get-openapi.md
- name: Context.IO - Post Accounts Webhooks
  x-api-slug: accountsidwebhooks-post
  description: Creates a new WebHook on an account.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhooks-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhooks-post-openapi.md
- name: Context.IO - Delete Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-delete
  description: Cancels a WebHook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-delete-openapi.md
- name: Context.IO - Post Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-post
  description: |-
    Changes properties of a given WebHook. The only property of a WebHook that can be changed is it's active property. If you want to change the filters or callback urls, delete it and create a new one.
    Changing the active property can be useful in two cases:
    - Pause/resume WebHooks: If your application needs up-to-date information when users are logged in the best option is to keep a WebHook with no filters on that account that will be resumed (setting active to 1) when the user logs in and paused (setting active to 0) when the user logs out of your app.
    - Acting upon a failure notification: If a WebHook fails, your failure_notif_url is called (see creating a WebHook) an its active property becomes 0. Set the active property back to 1 to get it working again.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-post-openapi.md
- name: Context.IO - Get Accounts Webhooks Webhook
  x-api-slug: accountsidwebhookswebhook-id-get
  description: Gets properties of a given WebHook.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/172-context-io.jpg
  humanURL: http://context.io/
  baseURL: https://api.context.io//2.0/
  tags: API LIfeyclessss, Stack Network, Technology, SaaS, Mobile, API Provider, Emails,
    Messages, Profiles, Emails, Service API, Relative Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/context-io/accountsidwebhookswebhook-id-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://constant.contact.api.gallery.streamdata.io
- type: x-api-stack
  url: http://context.io.stack.network
- type: x-base
  url: https://api.context.io/
- type: x-blog
  url: http://blog.context.io/
- type: x-blog-rss
  url: http://blog.context.io/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/product/context-io
- type: x-crunchbase
  url: https://crunchbase.com/organization/context-io
- type: x-documentation
  url: http://context.io/docs/2.0
- type: x-email
  url: hello@context.io
- type: x-email
  url: support@context.io
- type: x-email
  url: business@context.io
- type: x-faq
  url: http://context.io/privacy-faq
- type: x-github
  url: https://github.com/contextio
- type: x-ios-library
  url: https://github.com/contextio/contextio-ios
- type: x-node-js-library
  url: https://github.com/contextio/ContextIO-node
- type: x-php-library
  url: https://github.com/contextio/PHP-ContextIO
- type: x-pricing
  url: http://context.io/pricing
- type: x-privacy
  url: http://www.returnpath.com/privacy-policy-data
- type: x-python-library
  url: https://github.com/contextio/Python-ContextIO
- type: x-ruby-library
  url: https://github.com/contextio/contextio-ruby
- type: x-selfservice-registration
  url: http://context.io/#signup
- type: x-terms-of-service
  url: http://context.io/terms-of-service
- type: x-twitter
  url: https://twitter.com/contextio
- type: x-website
  url: http://context.io/
- type: x-website
  url: http://context.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---