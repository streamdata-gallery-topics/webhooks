---
name: Reverb
x-slug: reverb
description: 'Reverb&#8217;s mission is to connect people with meaningful content.Reverb
  was created to find and connect the rich associations between words, ideas, content,
  and people. Through our products, we enhance broader knowledge around favorite topics
  by surfacing interesting information readers might not uncover on their own. We
  make tools for content understanding at every level from the single word on up.
  Wordnik: Get a full view of any word you???re interested in, with definitions, example
  sentences, related words, tweets from Twitter, pictures from Flickr, and much more.Reverb
  for Publishers: Reverb for Publishers brings relevant content to web audiences and
  surfaces additional content for publishers.Reverb for Developers: Reverb is committed
  to the open-source community and is proudly contributing infrastructure software
  to power applications and enterprises both small and gigantic. Our involvement with
  the Wordnik API, Scalatra, Swagger and Atmosphere is detailed on our site.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Webhooks
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/reverb/apis.md
specificationVersion: "0.14"
apis:
- name: reverb Get Webhooks Registrations
  x-api-slug: reverb
  description: Get webhooks registrations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//webhooks/registrations
  tags: Webhooks,Registrations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/reverb/webhooksregistrations-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/reverb/webhooksregistrations-get-openapi.md
- name: reverb Post Webhooks Registrations
  x-api-slug: reverb
  description: Post webhooks registrations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//webhooks/registrations
  tags: Webhooks,Registrations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/reverb/webhooksregistrations-post-openapi.md
- name: reverb Delete Webhooks Registrations
  x-api-slug: reverb
  description: Delete webhooks registrations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//webhooks/registrations/{id}
  tags: Webhooks,Registrations,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/reverb/webhooksregistrationsid-delete-openapi.md
- name: reverb Get Webhooks Registrations
  x-api-slug: reverb
  description: Get details of a webhook registration
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api//webhooks/registrations/{id}
  tags: Webhooks,Registrations,Id
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/reverb/webhooksregistrationsid-get-openapi.md
- name: reverb
  x-api-slug: reverb
  description: 'Reverb&#8217;s mission is to connect people with meaningful content.Reverb
    was created to find and connect the rich associations between words, ideas, content,
    and people. Through our products, we enhance broader knowledge around favorite
    topics by surfacing interesting information readers might not uncover on their
    own. We make tools for content understanding at every level from the single word
    on up. Wordnik: Get a full view of any word you???re interested in, with definitions,
    example sentences, related words, tweets from Twitter, pictures from Flickr, and
    much more.Reverb for Publishers: Reverb for Publishers brings relevant content
    to web audiences and surfaces additional content for publishers.Reverb for Developers:
    Reverb is committed to the open-source community and is proudly contributing infrastructure
    software to power applications and enterprises both small and gigantic. Our involvement
    with the Wordnik API, Scalatra, Swagger and Atmosphere is detailed on our site.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/145_logo.png
  humanURL: https://helloreverb.com/app
  baseURL: https://api.reverb.com//api
  tags: Webhooks
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/webhooks/master/_listings/reverb/openapi.md
x-common:
- type: x-blog
  url: http://blog.helloreverb.com/
- type: x-blog-rss
  url: http://blog.helloreverb.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/reverb-technologies
- type: x-github
  url: https://github.com/reverb
- type: x-twitter
  url: https://twitter.com/reverb
- type: x-website
  url: https://helloreverb.com/app
- type: x-website
  url: http://reverb.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---