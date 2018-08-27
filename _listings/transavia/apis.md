---
name: Transavia
x-slug: transavia
description: Want to fly affordably to more than 100 destinations in Europe? Book
  a flight with Transavia!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28522-airports-api-v2.jpg
x-kinRank: "7"
x-alexaRank: "12365"
tags: Airlines
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/transavia/apis.md
specificationVersion: "0.14"
apis:
- name: Flight Offers API v1 - Flight offers
  x-api-slug: get
  description: Retrieve flight offers by query string parameters.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28522-airports-api-v2.jpg
  humanURL: http://transavia.com
  baseURL: https://tst.api.transavia.com//v1/flightoffers
  tags: Airlines, Travel, General Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/transavia/get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/airlines/master/_listings/transavia/get-openapi.md
x-common:
- type: x-api-gallery
  url: http://tradestation.api.gallery.streamdata.io
- type: x-api-stack
  url: http://transavia.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/transavia-airlines
- type: x-developer
  url: https://developer.transavia.com/
- type: x-documentation
  url: https://tst.developer.transavia.com/docs/services/
- type: x-twitter
  url: https://twitter.com/transavia
- type: x-website
  url: http://transavia.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---