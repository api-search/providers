---
api_count: 4
api_specs:
- filename: hotjar-rest-api-openapi.yml
  format: yaml
  label: Hotjar REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hotjar/refs/heads/main/openapi/hotjar-rest-api-openapi.yml
apis:
- description: The Hotjar REST API provides programmatic access to Hotjar data and functionality. It allows developers to export survey responses, automate user lookup and deletion requests, and integrate Hotjar dat
  name: Hotjar REST API
  slug: rest-api
- description: The Hotjar Events API is a client-side JavaScript API that allows developers to send custom events to Hotjar when specific actions take place on a website. These events can be used to filter collected
  name: Hotjar Events API
  slug: events-api
- description: The Hotjar Identify API is a client-side JavaScript API that allows developers to pass user data to Hotjar, saving it as User Attributes. These attributes enable advanced filtering and segmentation of
  name: Hotjar Identify API
  slug: identify-api
- description: The Hotjar JavaScript SDK (@hotjar/browser) is an npm package that provides a programmatic interface for integrating Hotjar directly into JavaScript applications. It allows developers to initialize Ho
  name: Hotjar JavaScript SDK
  slug: javascript-sdk
common:
- title: ''
  type: JSON-LD
  url: json-ld/hotjar-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/hotjar-survey-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/hotjar-survey-response-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/hotjar-user-lookup-schema.json
created: ''
description: Hotjar is a behavior analytics and user feedback platform that helps businesses understand how users interact with their website through heatmaps, session recordings, surveys, and feedback widgets.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Hotjar Context
  property_count: 7
  slug: hotjar-context
layout: provider
modified: '2026-03-20'
name: hotjar
skills: []
slug: hotjar
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: hotjar\nurl: https://raw.githubusercontent.com/api-evangelist/hotjar/refs/heads/main/apis.yml\napis:\n  - aid: hotjar:rest-api\n    name: Hotjar REST API\n    tags:\n      - Analytics\n      - Behavior\n      - Heatmaps\n      - Surveys\n      - User Feedback\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.hotjar.com\n    humanURL: https://help.hotjar.com/hc/en-us/articles/36820005914001-Hotjar-API-Reference\n    properties:\n      - url: https://help.hotjar.com/hc/en-us/articles/36820005914001-Hotjar-API-Reference\n        type: Documentation\n      - url: openapi/hotjar-rest-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Hotjar REST API provides programmatic access to Hotjar data and\n      functionality. It allows developers to export survey responses, automate\n      user lookup and deletion requests, and integrate Hotjar data into\n      external tools and workflows. The API uses\
  \ OAuth client credentials\n      authentication, returns JSON responses, supports cursor-based pagination,\n      and is rate limited to 3000 requests per minute. It is available on\n      Observe and Ask Scale plans.\n  - aid: hotjar:events-api\n    name: Hotjar Events API\n    tags:\n      - Analytics\n      - Events\n      - Heatmaps\n      - Recordings\n      - Surveys\n      - Tracking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://help.hotjar.com/hc/en-us/articles/36819965075473-Events-API-Reference\n    properties:\n      - url: https://help.hotjar.com/hc/en-us/articles/36819965075473-Events-API-Reference\n        type: Documentation\n    description: >-\n      The Hotjar Events API is a client-side JavaScript API that allows\n      developers to send custom events to Hotjar when specific actions take\n      place on a website. These events can be used to filter collected\n    \
  \  Recordings and Heatmap data, trigger session capture, and target Surveys\n      to appear based on user behavior. Events are sent using the Hotjar\n      tracking code and are available on all pages where the tracking snippet\n      is installed.\n  - aid: hotjar:identify-api\n    name: Hotjar Identify API\n    tags:\n      - Analytics\n      - Attributes\n      - Personalization\n      - Segmentation\n      - Users\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://help.hotjar.com/hc/en-us/articles/36820006120721-Identify-API-Reference\n    properties:\n      - url: https://help.hotjar.com/hc/en-us/articles/36820006120721-Identify-API-Reference\n        type: Documentation\n    description: >-\n      The Hotjar Identify API is a client-side JavaScript API that allows\n      developers to pass user data to Hotjar, saving it as User Attributes.\n      These attributes enable advanced filtering\
  \ and segmentation of Hotjar\n      data such as Recordings, Heatmaps, and Surveys. The Identify API must\n      be called before the Events API in the execution order. It is used via\n      the Hotjar tracking code on pages where the JavaScript snippet is\n      installed.\n  - aid: hotjar:javascript-sdk\n    name: Hotjar JavaScript SDK\n    tags:\n      - Analytics\n      - Browser\n      - JavaScript\n      - SDK\n      - Tracking\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://github.com/hotjar/hotjar-js\n    properties:\n      - url: https://github.com/hotjar/hotjar-js\n        type: Documentation\n    description: >-\n      The Hotjar JavaScript SDK (@hotjar/browser) is an npm package that\n      provides a programmatic interface for integrating Hotjar directly into\n      JavaScript applications. It allows developers to initialize Hotjar with\n      a site ID, identify users, and\
  \ send custom events without manually\n      embedding the tracking script. The SDK supports modern JavaScript\n      frameworks including React, Vue, and Angular, and provides methods for\n      all Hotjar client-side APIs including identify and event tracking.\nmodified: '2026-03-20'\ncommon:\n  - type: JSON-LD\n    url: json-ld/hotjar-context.jsonld\n  - type: JSONSchema\n    url: json-schema/hotjar-survey-schema.json\n  - type: JSONSchema\n    url: json-schema/hotjar-survey-response-schema.json\n  - type: JSONSchema\n    url: json-schema/hotjar-user-lookup-schema.json\ndescription: >-\n  Hotjar is a behavior analytics and user feedback platform that helps businesses\n  understand how users interact with their website through heatmaps, session recordings,\n  surveys, and feedback widgets.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hotjar/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/hotjar/refs/heads/main/apis.yml
use_cases: []
---
