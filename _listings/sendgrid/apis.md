---
name: SendGrid
x-slug: sendgrid
description: Delivering your transactional and marketing emails through the worlds
  largest cloud-based email delivery platform. Send with confidence.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
x-kinRank: "9"
x-alexaRank: "10000"
tags: Webhooks
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/apis.md
specificationVersion: "0.14"
apis:
- name: SendGrid - Get User Webhooks Event Settings
  x-api-slug: userwebhookseventsettings-get
  description: |-
    **This endpoint allows you to retrieve your current event webhook settings.**

    If an event type is marked as `true`, then the event webhook will include information about that event.

    SendGrid???s Event Webhook will notify a URL of your choice via HTTP POST with information about events that occur as SendGrid processes your email.

    Common uses of this data are to remove unsubscribes, react to spam reports, determine unengaged recipients, identify bounced email addresses, or create advanced analytics of your email program.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhookseventsettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhookseventsettings-get-openapi.md
- name: SendGrid - Patch User Webhooks Event Settings
  x-api-slug: userwebhookseventsettings-patch
  description: |-
    **This endpoint allows you to update your current event webhook settings.**

    If an event type is marked as `true`, then the event webhook will include information about that event.

    SendGrid???s Event Webhook will notify a URL of your choice via HTTP POST with information about events that occur as SendGrid processes your email.

    Common uses of this data are to remove unsubscribes, react to spam reports, determine unengaged recipients, identify bounced email addresses, or create advanced analytics of your email program.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhookseventsettings-patch-openapi.md
- name: SendGrid - Add User Webhooks Event Test
  x-api-slug: userwebhookseventtest-post
  description: |-
    **This endpoint allows you to test your event webhook by sending a fake event notification post to the provided URL.**

    SendGrid???s Event Webhook will notify a URL of your choice via HTTP POST with information about events that occur as SendGrid processes your email.

    Common uses of this data are to remove unsubscribes, react to spam reports, determine unengaged recipients, identify bounced email addresses, or create advanced analytics of your email program.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhookseventtest-post-openapi.md
- name: SendGrid - Get User Webhooks Parse Settings
  x-api-slug: userwebhooksparsesettings-get
  description: |-
    **This endpoint allows you to retrieve all of your current inbound parse settings.**

    The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhooksparsesettings-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhooksparsesettings-get-openapi.md
- name: SendGrid - Add User Webhooks Parse Settings
  x-api-slug: userwebhooksparsesettings-post
  description: |-
    **This endpoint allows you to create a new inbound parse setting.**

    The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the content, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhooksparsesettings-post-openapi.md
- name: SendGrid - Delete User Webhooks Parse Settings Hostname
  x-api-slug: userwebhooksparsesettingshostname-delete
  description: |-
    **This endpoint allows you to delete a specific inbound parse setting.**

    The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhooksparsesettingshostname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhooksparsesettingshostname-delete-openapi.md
- name: SendGrid - Get User Webhooks Parse Settings Hostname
  x-api-slug: userwebhooksparsesettingshostname-get
  description: |-
    **This endpoint allows you to retrieve a specific inbound parse setting.**

    The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhooksparsesettingshostname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhooksparsesettingshostname-get-openapi.md
- name: SendGrid - Patch User Webhooks Parse Settings Hostname
  x-api-slug: userwebhooksparsesettingshostname-patch
  description: |-
    **This endpoint allows you to update a specific inbound parse setting.**

    The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhooksparsesettingshostname-patch-openapi.md
- name: SendGrid - Get User Webhooks Parse Stats
  x-api-slug: userwebhooksparsestats-get
  description: |-
    **This endpoint allows you to retrieve the statistics for your Parse Webhook useage.**

    SendGrid's Inbound Parse Webhook allows you to parse the contents and attachments of incomming emails. The Parse API can then POST the parsed emails to a URL that you specify. The Inbound Parse Webhook cannot parse messages greater than 20MB in size, including all attachments.

    There are a number of pre-made integrations for the SendGrid Parse Webhook which make processing events easy. You can find these integrations in the [Library Index](https://sendgrid.com/docs/Integrate/libraries.html#-Webhook-Libraries).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/142-sendgrid.jpg
  humanURL: http://sendgrid.com
  baseURL: https://api.sendgrid.com//v3
  tags: API LIfeyclessss, Imports, Stack Network, Stack, Technology, SaaS, Emails,
    Emails, Messages, Messages, Relative Data, Service API, Relative StreamRank, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhooksparsestats-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/sendgrid/userwebhooksparsestats-get-openapi.md
x-common:
- type: x--net-library
  url: https://sendgrid.com/docs/Code_Examples/csharp.html
- type: x-api-gallery
  url: http://school.digger.api.gallery.streamdata.io
- type: x-api-stack
  url: http://sendgrid.stack.network
- type: x-base
  url: https://api.sendgrid.com
- type: x-blog
  url: http://blog.sendgrid.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/sendgrid/CDXr
- type: x-contact-form
  url: https://sendgrid.com/contact
- type: x-crunchbase
  url: http://www.crunchbase.com/company/sendgrid
- type: x-crunchbase
  url: https://crunchbase.com/organization/sendgrid
- type: x-developer
  url: https://sendgrid.com/developers
- type: x-documentation
  url: https://sendgrid.com/docs/index.html
- type: x-email
  url: privacy@sendgrid.com
- type: x-email
  url: legal@sendgrid.com
- type: x-email
  url: dpo@sendgrid.com
- type: x-forum
  url: http://support.sendgrid.com/forums
- type: x-github
  url: https://github.com/sendgrid
- type: x-go-library
  url: https://sendgrid.com/docs/Code_Examples/go.html
- type: x-ios-library
  url: https://sendgrid.com/docs/Code_Examples/ios.html
- type: x-java-library
  url: https://sendgrid.com/docs/Code_Examples/java.html
- type: x-labs
  url: http://labs.sendgrid.com/
- type: x-linkedin
  url: https://www.linkedin.com/company/sendgrid
- type: x-node-js-library
  url: https://sendgrid.com/docs/Code_Examples/nodejs.html
- type: x-partners
  url: https://sendgrid.com/partners
- type: x-perl-library
  url: https://sendgrid.com/docs/Code_Examples/perl.html
- type: x-php-library
  url: https://sendgrid.com/docs/Code_Examples/php.html
- type: x-pricing
  url: https://sendgrid.com/transactional-email/pricing
- type: x-privacy
  url: https://sendgrid.com/privacy
- type: x-python-library
  url: https://sendgrid.com/docs/Code_Examples/python.html
- type: x-ruby-library
  url: https://sendgrid.com/docs/Code_Examples/ruby.html
- type: x-security
  url: https://sendgrid.com/security
- type: x-selfservice-registration
  url: https://sendgrid.com/user/signup
- type: x-terms-of-service
  url: https://sendgrid.com/tos
- type: x-twitter
  url: https://twitter.com/SendGrid
- type: x-website
  url: http://sendgrid.com
- type: x-website
  url: https://sendgrid.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---