---
api_count: 5
api_specs:
- filename: ghost-content-api-openapi.yml
  format: yaml
  label: Ghost Content API
  slug: content-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/openapi/ghost-content-api-openapi.yml
- filename: ghost-admin-api-openapi.yml
  format: yaml
  label: Ghost Admin API
  slug: admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/openapi/ghost-admin-api-openapi.yml
- filename: ghost-webhooks-asyncapi.yml
  format: yaml
  label: Ghost Webhooks
  slug: webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/asyncapi/ghost-webhooks-asyncapi.yml
apis:
- description: The Ghost Content API is a RESTful, read-only API that delivers published content from a Ghost site to any client. It provides access to posts, pages, tags, authors, tiers, and settings resources. Acc
  name: Ghost Content API
  slug: content-api
- description: The Ghost Admin API provides full read and write access to all content and configuration within a Ghost publication. It enables developers to create, update, and delete posts, pages, tags, members, ti
  name: Ghost Admin API
  slug: admin-api
- description: 'Ghost Webhooks allow developers to receive real-time HTTP notifications when specific events occur within a Ghost publication, such as publishing a new post, updating a page, or gaining a new member. '
  name: Ghost Webhooks
  slug: webhooks
- description: The Ghost Content API JavaScript Client is an official promise-based JavaScript library published as @tryghost/content-api on npm. It abstracts the complexity of authenticating and interacting with th
  name: Ghost Content API JavaScript Client
  slug: content-api-javascript-client
- description: The Ghost Themes API provides a Handlebars-based templating system for building custom front-end themes for Ghost publications. It includes a comprehensive set of helpers including data helpers for fe
  name: Ghost Themes API
  slug: themes-api
asyncapis:
- description: 'Ghost Webhooks allow developers to receive real-time HTTP notifications when specific events occur within a Ghost publication, such as publishing a new post, updating a page, or gaining a new member. '
  name: Ghost Webhooks
  slug: ghost-webhooks-asyncapi
common:
- title: ''
  type: JSON-LD
  url: json-ld/ghost-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/ghost-post-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/ghost-member-schema.json
created: '2025-03-01'
description: Ghost is an open-source publishing platform designed for professional publishers, with native subscription, membership, and newsletter features for content creators.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Ghost Context
  property_count: 9
  slug: ghost-context
layout: provider
modified: '2026-04-28'
name: Ghost
skills: []
slug: ghost
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: ghost\nurl: https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/apis.yml\napis:\n  - aid: ghost:content-api\n    name: Ghost Content API\n    tags:\n      - Authors\n      - Content Management\n      - Headless CMS\n      - Pages\n      - Posts\n      - Publishing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://ghost.org/docs/content-api/\n    properties:\n      - url: https://ghost.org/docs/content-api/\n        type: Documentation\n      - url: openapi/ghost-content-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Ghost Content API is a RESTful, read-only API that delivers published content\n      from a Ghost site to any client. It provides access to posts, pages, tags, authors,\n      tiers, and settings resources. Access is controlled via a Content API key, and\n      all responses are returned in JSON format.\n  - aid: ghost:admin-api\n\
  \    name: Ghost Admin API\n    tags:\n      - Administration\n      - Content Management\n      - Members\n      - Newsletters\n      - Offers\n      - Publishing\n      - Tiers\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://ghost.org/docs/admin-api/\n    properties:\n      - url: https://ghost.org/docs/admin-api/\n        type: Documentation\n      - url: openapi/ghost-admin-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Ghost Admin API provides full read and write access to all content and configuration\n      within a Ghost publication. It enables developers to create, update, and delete\n      posts, pages, tags, members, tiers, newsletters, and offers programmatically.\n      Authentication is handled via JSON Web Tokens generated from an Admin API key,\n      integration tokens, or staff access tokens.\n  - aid: ghost:webhooks\n    name: Ghost Webhooks\n \
  \   tags:\n      - Automation\n      - Events\n      - Integrations\n      - Notifications\n      - Webhooks\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://ghost.org/docs/webhooks/\n    properties:\n      - url: https://ghost.org/docs/webhooks/\n        type: Documentation\n      - url: asyncapi/ghost-webhooks-asyncapi.yml\n        type: AsyncAPI\n    description: >-\n      Ghost Webhooks allow developers to receive real-time HTTP notifications when\n      specific events occur within a Ghost publication, such as publishing a new post,\n      updating a page, or gaining a new member. Webhooks can be configured through\n      the Ghost Admin interface under custom integrations or created programmatically\n      via the Admin API.\n  - aid: ghost:content-api-javascript-client\n    name: Ghost Content API JavaScript Client\n    tags:\n      - Client Library\n      - Content Management\n  \
  \    - JavaScript\n      - Node.js\n      - SDK\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://ghost.org/docs/content-api/javascript/\n    properties:\n      - url: https://ghost.org/docs/content-api/javascript/\n        type: Documentation\n    description: >-\n      The Ghost Content API JavaScript Client is an official promise-based JavaScript\n      library published as @tryghost/content-api on npm. It abstracts the complexity\n      of authenticating and interacting with the Ghost Content API, providing a clean\n      interface for fetching posts, pages, tags, authors, and settings. The library\n      works in both client-side and server-side JavaScript environments and supports\n      the full NQL filtering syntax.\n  - aid: ghost:themes-api\n    name: Ghost Themes API\n    tags:\n      - Customization\n      - Frontend\n      - Handlebars\n      - Templates\n      - Themes\n    image:\
  \ https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.example.com\n    humanURL: https://ghost.org/docs/themes/\n    properties:\n      - url: https://ghost.org/docs/themes/\n        type: Documentation\n    description: >-\n      The Ghost Themes API provides a Handlebars-based templating system for building\n      custom front-end themes for Ghost publications. It includes a comprehensive\n      set of helpers including data helpers for fetching content, functional helpers\n      for logic and formatting, and utility helpers for common tasks. Themes have\n      access to all Ghost content through template variables and the get helper, which\n      queries the Content API internally.\ncommon:\n  - type: JSON-LD\n    url: json-ld/ghost-context.jsonld\n  - type: JSONSchema\n    url: json-schema/ghost-post-schema.json\n  - type: JSONSchema\n    url: json-schema/ghost-member-schema.json\nname: Ghost\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-28'\nposition: Consumer\nspecificationVersion: '0.19'\ntags:\n  - Content Management\n  - Publishing\n  - Headless CMS\n  - Blogging\n  - Newsletters\n  - Memberships\ndescription: >-\n  Ghost is an open-source publishing platform designed for professional publishers,\n  with native subscription, membership, and newsletter features for content creators.\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/apis.yml
tags:
- Content Management
- Publishing
- Headless CMS
- Blogging
- Newsletters
- Memberships
url: https://raw.githubusercontent.com/api-evangelist/ghost/refs/heads/main/apis.yml
use_cases: []
---
