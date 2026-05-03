---
api_count: 4
api_specs:
- filename: zesty-auth-api-openapi.yml
  format: yaml
  label: Zesty Auth API
  slug: auth-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/openapi/zesty-auth-api-openapi.yml
- filename: zesty-accounts-api-openapi.yml
  format: yaml
  label: Zesty Accounts API
  slug: accounts-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/openapi/zesty-accounts-api-openapi.yml
- filename: zesty-instances-api-openapi.yml
  format: yaml
  label: Zesty Instances API
  slug: instances-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/openapi/zesty-instances-api-openapi.yml
- filename: zesty-media-api-openapi.yml
  format: yaml
  label: Zesty Media API
  slug: media-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/openapi/zesty-media-api-openapi.yml
apis:
- description: The Zesty.io Auth API is used to authenticate users with the platform. It returns a session token that grants access to the Instances API, Accounts API, and Media API. User authentication is done by p
  name: Zesty Auth API
  slug: auth-api
- description: The Zesty.io Accounts API is used to manage users, roles, instances, teams, tokens, ecosystems, webhooks, and apps. It provides administrative control over the organizational structure of a Zesty.io a
  name: Zesty Accounts API
  slug: accounts-api
- description: The Zesty.io Instances API is a REST API that allows CRUD operations on Zesty.io instances. It provides access to content models, content items, fields, views, stylesheets, scripts, settings, head tag
  name: Zesty Instances API
  slug: instances-api
- description: 'The Zesty.io Media API is a collection of services for managing media files. It consists of four services: Media Manager, Media Storage, Media Modify, and Media Resolver. It handles bins, groups (fold'
  name: Zesty Media API
  slug: media-api
common:
- title: ''
  type: Documentation
  url: https://www.zesty.io/docs/
- title: ''
  type: Documentation
  url: https://docs.zesty.io/
- title: ''
  type: Blog
  url: https://www.zesty.io/mindshare/
- title: ''
  type: Support
  url: https://www.zesty.io/contact/
- title: ''
  type: GitHub
  url: https://github.com/zesty-io
- title: ''
  type: SDKs
  url: https://github.com/zesty-io/node-sdk
- title: ''
  type: SDKs
  url: https://github.com/zesty-io/fetch-wrapper
created: '2025-02-17'
description: Zesty.io is a composable, data-driven, headless CMS platform that provides REST APIs for authentication, account management, instance content management, and media file management. All resources are identified by ZUIDs (Zesty Universal Identifiers). The platform supports WebEngine for traditional CMS, headless API architecture, GraphQL, and JamStack implementations. Built on Google Cloud Platform with Fastly edge caching.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Zesty Context
  property_count: 11
  slug: zesty-context
layout: provider
modified: '2026-05-03'
name: Zesty
skills: []
slug: zesty
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zesty\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/apis.yml\nname: Zesty\ndescription: >-\n  Zesty.io is a composable, data-driven, headless CMS platform that provides\n  REST APIs for authentication, account management, instance content\n  management, and media file management. All resources are identified by\n  ZUIDs (Zesty Universal Identifiers). The platform supports WebEngine\n  for traditional CMS, headless API architecture, GraphQL, and JamStack\n  implementations. Built on Google Cloud Platform with Fastly edge caching.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CMS\n  - Composable\n  - Content Management\n  - GraphQL\n  - Headless CMS\n  - Media\ncreated: '2025-02-17'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: zesty:auth-api\n    name: Zesty Auth API\n    tags:\n      - Authentication\n      -\
  \ Sessions\n      - Tokens\n    humanURL: https://docs.zesty.io/docs/auth-api\n    properties:\n      - url: https://docs.zesty.io/docs/auth-api\n        type: Documentation\n      - url: openapi/zesty-auth-api-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Zesty.io Auth API is used to authenticate users with the platform.\n      It returns a session token that grants access to the Instances API,\n      Accounts API, and Media API. User authentication is done by providing\n      an email and password combination, which issues a short-lived 30-minute\n      session token. Also supports Microsoft SSO, Okta SSO, and Azure SSO.\n  - aid: zesty:accounts-api\n    name: Zesty Accounts API\n    tags:\n      - Accounts\n      - Instances\n      - Roles\n      - Teams\n      - Users\n    humanURL: https://docs.zesty.io/docs/accounts\n    properties:\n      - url: https://docs.zesty.io/docs/accounts\n        type: Documentation\n      - url: openapi/zesty-accounts-api-openapi.yml\n\
  \        type: OpenAPI\n      - url: json-schema/instance.json\n        type: JSONSchema\n      - url: json-schema/user.json\n        type: JSONSchema\n      - url: json-schema/role.json\n        type: JSONSchema\n      - url: json-schema/team.json\n        type: JSONSchema\n      - url: json-schema/token.json\n        type: JSONSchema\n    description: >-\n      The Zesty.io Accounts API is used to manage users, roles, instances,\n      teams, tokens, ecosystems, webhooks, and apps. It provides\n      administrative control over the organizational structure of a Zesty.io\n      account.\n  - aid: zesty:instances-api\n    name: Zesty Instances API\n    tags:\n      - CMS\n      - Content Items\n      - Content Models\n      - Publishing\n      - Views\n    humanURL: https://docs.zesty.io/docs/instances-api\n    properties:\n      - url: https://docs.zesty.io/docs/instances-api\n        type: Documentation\n      - url: openapi/zesty-instances-api-openapi.yml\n        type: OpenAPI\n  \
  \    - url: json-schema/content-model.json\n        type: JSONSchema\n      - url: json-schema/content-item.json\n        type: JSONSchema\n      - url: json-schema/field.json\n        type: JSONSchema\n    description: >-\n      The Zesty.io Instances API is a REST API that allows CRUD operations on\n      Zesty.io instances. It provides access to content models, content\n      items, fields, views, stylesheets, scripts, settings, head tags,\n      navigation, audits, and publishing operations. Each instance is\n      identified by a unique ZUID.\n  - aid: zesty:media-api\n    name: Zesty Media API\n    tags:\n      - CDN\n      - Files\n      - Images\n      - Media\n      - Storage\n    humanURL: https://docs.zesty.io/docs/media\n    properties:\n      - url: https://docs.zesty.io/docs/media\n        type: Documentation\n      - url: openapi/zesty-media-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/media-bin.json\n        type: JSONSchema\n      - url: json-schema/media-group.json\n\
  \        type: JSONSchema\n      - url: json-schema/media-file.json\n        type: JSONSchema\n      - url: json-ld/zesty-context.jsonld\n        type: JSONLD\n    description: >-\n      The Zesty.io Media API is a collection of services for managing media\n      files. It consists of four services: Media Manager, Media Storage,\n      Media Modify, and Media Resolver. It handles bins, groups (folders),\n      file uploads, and CDN URL resolution.\ncommon:\n  - url: https://www.zesty.io/docs/\n    name: Documentation\n    type: Documentation\n    description: Official Zesty.io platform documentation.\n  - url: https://docs.zesty.io/\n    name: API Reference\n    type: Documentation\n    description: Zesty.io API reference documentation.\n  - url: https://www.zesty.io/mindshare/\n    name: Blog\n    type: Blog\n    description: Zesty.io blog and thought leadership.\n  - url: https://www.zesty.io/contact/\n    name: Contact\n    type: Support\n    description: Zesty.io support contact.\n\
  \  - url: https://github.com/zesty-io\n    name: GitHub Organization\n    type: GitHub\n    description: Zesty.io GitHub organization with SDKs, templates, and tools.\n  - url: https://github.com/zesty-io/node-sdk\n    name: Node.js SDK\n    type: SDKs\n    description: Zesty.io software development kit for Node.js runtime.\n  - url: https://github.com/zesty-io/fetch-wrapper\n    name: Fetch Wrapper\n    type: SDKs\n    description: Zesty.io HTTP fetch wrapper utility.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/apis.yml
tags:
- CMS
- Composable
- Content Management
- GraphQL
- Headless CMS
- Media
url: https://raw.githubusercontent.com/api-evangelist/zesty/refs/heads/main/apis.yml
use_cases: []
---
