---
api_count: 2
api_specs:
- filename: medium-rest-api-openapi.yml
  format: yaml
  label: Medium REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/medium/refs/heads/main/openapi/medium-rest-api-openapi.yml
- filename: medium-oauth2-openapi.yml
  format: yaml
  label: Medium OAuth2 API
  slug: oauth2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/medium/refs/heads/main/openapi/medium-oauth2-openapi.yml
apis:
- description: The Medium REST API provides programmatic access to the Medium online publishing platform. Developers can authenticate users via OAuth2, retrieve user profile details, list publications a user is asso
  name: Medium REST API
  slug: rest-api
- description: The Medium OAuth2 API enables third-party applications to authenticate and authorize users to act on their behalf on the Medium platform. Applications redirect users to Medium's authorization endpoint
  name: Medium OAuth2 API
  slug: oauth2
common:
- title: ''
  type: JSON-LD
  url: json-ld/medium-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/medium-post-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/medium-user-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/medium-publication-schema.json
created: ''
description: Documentation for Medium's OAuth2 API. Contribute to Medium/medium-api-docs development by creating an account on GitHub.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Medium Context
  property_count: 5
  slug: medium-context
layout: provider
modified: '2026-03-20'
name: medium
skills: []
slug: medium
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: medium\nurl: https://raw.githubusercontent.com/api-evangelist/medium/refs/heads/main/apis.yml\napis:\n  - aid: medium:rest-api\n    name: Medium REST API\n    tags:\n      - Blogging\n      - Content\n      - Posts\n      - Publications\n      - Publishing\n      - Social Media\n      - Writing\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.medium.com/v1\n    humanURL: https://github.com/Medium/medium-api-docs\n    properties:\n      - url: https://github.com/Medium/medium-api-docs\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/medium-rest-api-openapi.yml\n    description: >-\n      The Medium REST API provides programmatic access to the Medium online\n      publishing platform. Developers can authenticate users via OAuth2,\n      retrieve user profile details, list publications a user is associated\n      with, create posts on a user's profile or within a publication, and\n  \
  \    upload images. The API is JSON-based with all requests made over HTTPS\n      to endpoints under api.medium.com/v1, enabling integrations that\n      automate content publishing workflows on Medium.\n  - aid: medium:oauth2\n    name: Medium OAuth2 API\n    tags:\n      - Authentication\n      - Authorization\n      - Identity\n      - OAuth\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://medium.com/m/oauth\n    humanURL: https://github.com/Medium/medium-api-docs#2-authentication\n    properties:\n      - url: https://github.com/Medium/medium-api-docs#2-authentication\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/medium-oauth2-openapi.yml\n    description: >-\n      The Medium OAuth2 API enables third-party applications to authenticate\n      and authorize users to act on their behalf on the Medium platform.\n      Applications redirect users to Medium's authorization endpoint to\n      obtain\
  \ an authorization code, which is then exchanged for an access\n      token and refresh token. The OAuth2 flow supports scoped permissions\n      including basicProfile, publishPost, and listPublications, allowing\n      developers to request only the level of access their application\n      requires.\ncommon:\n  - type: JSON-LD\n    url: json-ld/medium-context.jsonld\n  - type: JSONSchema\n    url: json-schema/medium-post-schema.json\n  - type: JSONSchema\n    url: json-schema/medium-user-schema.json\n  - type: JSONSchema\n    url: json-schema/medium-publication-schema.json\nmodified: '2026-03-20'\ndescription: >-\n  Documentation for Medium's OAuth2 API. Contribute to Medium/medium-api-docs development\n  by creating an account on GitHub.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/medium/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/medium/refs/heads/main/apis.yml
use_cases: []
---
