---
api_count: 4
api_specs:
- filename: npr-station-finder-openapi-original.yml
  format: yaml
  label: NPR Station Finder
  slug: station-finder
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/npr/main/openapi/npr-station-finder-openapi-original.yml
- filename: npr-identity-openapi-original.yml
  format: yaml
  label: NPR Identity
  slug: identity
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/npr/main/openapi/npr-identity-openapi-original.yml
- filename: npr-authorization-openapi-original.yml
  format: yaml
  label: NPR Authorization
  slug: authorization
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/npr/main/openapi/npr-authorization-openapi-original.yml
apis:
- description: Audio recommendations tailored to a user's preferences.
  name: NPR Listening
  slug: listening
- description: NPR member station information lookup.
  name: NPR Station Finder
  slug: station-finder
- description: User management API and entry point to user-specific information.
  name: NPR Identity
  slug: identity
- description: API authorization service.
  name: NPR Authorization
  slug: authorization
common:
- title: ''
  type: Website
  url: https://www.npr.org/
- title: ''
  type: Documentation
  url: https://dev.npr.org/
created: '2024-04-14'
description: National Public Radio (NPR) APIs. The APIs support station finding, authentication, user management, and listening with audio recommendations tailored to a user's preferences.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: NPR
skills: []
slug: npr
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: npr\nname: NPR\ndescription: >-\n  National Public Radio (NPR) APIs. The APIs support station finding,\n  authentication, user management, and listening with audio recommendations\n  tailored to a user's preferences.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Media\n  - News\n  - Radio\nurl: https://raw.githubusercontent.com/api-evangelist/npr/refs/heads/main/apis.yml\ncreated: '2024-04-14'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: npr:listening\n    name: NPR Listening\n    description: Audio recommendations tailored to a user's preferences.\n    humanURL: https://dev.npr.org/guide/services/listening\n    baseURL: https://listening.api.npr.org/\n    tags:\n      - Audio\n      - Listening\n    properties:\n      - type: Documentation\n        url: https://dev.npr.org/guide/services/listening\n      - type: Swagger\n        url: https://listening.api.npr.org/v2/swagger.json\n \
  \ - aid: npr:station-finder\n    name: NPR Station Finder\n    description: NPR member station information lookup.\n    humanURL: https://dev.npr.org/guide/services/station-finder\n    baseURL: https://station.api.npr.org/\n    tags:\n      - Stations\n    properties:\n      - type: Documentation\n        url: https://dev.npr.org/guide/services/station-finder\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/npr/main/openapi/npr-station-finder-openapi-original.yml\n  - aid: npr:identity\n    name: NPR Identity\n    description: User management API and entry point to user-specific information.\n    humanURL: https://dev.npr.org/guide/services/identity\n    baseURL: https://identity.api.npr.org/\n    tags:\n      - Identity\n      - Users\n    properties:\n      - type: Documentation\n        url: https://dev.npr.org/guide/services/identity\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/npr/main/openapi/npr-identity-openapi-original.yml\n\
  \  - aid: npr:authorization\n    name: NPR Authorization\n    description: API authorization service.\n    humanURL: https://dev.npr.org/guide/services/authorization\n    baseURL: https://authorization.api.npr.org/\n    tags:\n      - Authorization\n    properties:\n      - type: Documentation\n        url: https://dev.npr.org/guide/services/authorization\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/npr/main/openapi/npr-authorization-openapi-original.yml\ncommon:\n  - type: Website\n    url: https://www.npr.org/\n  - type: Documentation\n    url: https://dev.npr.org/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/npr/refs/heads/main/apis.yml
tags:
- Media
- News
- Radio
url: https://raw.githubusercontent.com/api-evangelist/npr/refs/heads/main/apis.yml
use_cases: []
---
