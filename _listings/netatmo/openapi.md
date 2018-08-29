swagger: "2.0"
x-collection-name: Netatmo
x-complete: 1
info:
  title: Netatmo
  description: we-develop-groundbreaking-intuitive-and-beautifullydesigned-connected-consumer-electronics--truly-smart-our-innovative-products-provide-a-seamless-experience-that-helps-users-create-a-safer-healthier-and-more-comfortable-home---we-carefully-design-the-mechanics-electronics-and-embedded-software-of-all-our-products-to-the-highest-standards--our-mobile-and-web-applications-are-designed-to-be-simple-to-operate-yet-deliver-a-rich-user-experience-
  termsOfService: https://dev.netatmo.com/dev/resources/legal/introduction
  contact:
    name: Netatmo
    email: contact-api@netatmo.com
  version: 1.1.1
host: api.netatmo.net
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /addwebhook:
    get:
      summary: Get Addwebhook
      description: Links a callback url to a user.
      operationId: addwebhook
      x-api-path-slug: addwebhook-get
      parameters:
      - in: query
        name: app_type
        description: Webhooks are only available for Welcome, enter app_camera
      - in: query
        name: url
        description: Your webhook callback url
      responses:
        200:
          description: OK
      tags:
      - Web Hooks
  /dropwebhook:
    get:
      summary: Get Dropwebhook
      description: Dissociates a webhook from a user.
      operationId: dropwebhook
      x-api-path-slug: dropwebhook-get
      parameters:
      - in: query
        name: app_type
        description: For Welcome, use app_camera
      responses:
        200:
          description: OK
      tags:
      - Web Hooks