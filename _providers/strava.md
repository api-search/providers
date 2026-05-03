---
api_count: 1
api_specs:
- filename: strava-openapi.yml
  format: yaml
  label: Strava API
  slug: strava
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/openapi/strava-openapi.yml
apis:
- description: The Strava API provides access to athlete profiles, activities (workouts), segments, routes, clubs, gear, and time-series data streams. Supports OAuth 2.0 with fine-grained scopes for reading activiti
  name: Strava API
  slug: strava
capabilities:
- description: Unified capability for fitness tracking and athletic performance analysis using the Strava API. Designed for fitness app developers, coaches, and training platforms to access athlete data, workout his
  name: Strava Fitness Tracking
  slug: fitness-tracking
common:
- title: ''
  type: Website
  url: https://www.strava.com
- title: ''
  type: Developer Portal
  url: https://developers.strava.com/
- title: ''
  type: Documentation
  url: https://developers.strava.com/docs/
- title: ''
  type: Authentication
  url: https://developers.strava.com/docs/authentication/
- title: ''
  type: Terms of Service
  url: https://www.strava.com/legal/api
- title: ''
  type: Privacy Policy
  url: https://www.strava.com/legal/privacy
- title: ''
  type: Status
  url: https://status.strava.com
- title: ''
  type: Blog
  url: https://blog.strava.com
- title: ''
  type: Forum
  url: https://communityhub.strava.com/developers
- title: ''
  type: Sign Up
  url: https://www.strava.com/register
- title: ''
  type: Login
  url: https://www.strava.com/login
- title: ''
  type: App Registration
  url: https://www.strava.com/settings/api
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/openapi/strava-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/json-schema/strava-activity-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/json-ld/strava-context.jsonld
created: '2025-03-01'
description: 'Strava is a popular fitness tracking app and social network that allows athletes to track and analyze workouts including running, cycling, swimming, and 200+ other sport types. The Strava API enables developers to access athlete profiles, activities, segments, routes, clubs, gear, and time-series data streams. OAuth 2.0 is used for authentication with granular scope control. Rate limits apply: 100 requests per 15 minutes, 1000 per day.'
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Strava Context
  property_count: 5
  slug: strava-context
layout: provider
modified: '2026-05-02'
name: Strava
rules:
- name: Strava API Rules
  rule_count: 10
  severity_counts:
    error: 1
    hint: 0
    info: 5
    warn: 4
  slug: strava-rules
skills: []
slug: strava
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: strava\nname: Strava\ndescription: >-\n  Strava is a popular fitness tracking app and social network that allows\n  athletes to track and analyze workouts including running, cycling, swimming,\n  and 200+ other sport types. The Strava API enables developers to access\n  athlete profiles, activities, segments, routes, clubs, gear, and time-series\n  data streams. OAuth 2.0 is used for authentication with granular scope\n  control. Rate limits apply: 100 requests per 15 minutes, 1000 per day.\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/apis.yml\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cycling\n  - Fitness\n  - Fitness Tracking\n  - Running\n  - Sports\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ncreated: '2025-03-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: strava:strava\n    name: Strava API\n    description: >-\n      The Strava API provides\
  \ access to athlete profiles, activities (workouts),\n      segments, routes, clubs, gear, and time-series data streams. Supports\n      OAuth 2.0 with fine-grained scopes for reading activities, accessing\n      private data, and writing updates. Rate limited to 100 requests/15 min\n      and 1000 requests/day for default applications.\n    humanURL: https://developers.strava.com/\n    baseURL: https://www.strava.com/api/v3\n    tags:\n      - Cycling\n      - Fitness\n      - Fitness Tracking\n      - Running\n      - Sports\n    properties:\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/openapi/strava-openapi.yml\n      - type: Documentation\n        url: https://developers.strava.com/docs/reference/\n      - type: Authentication\n        url: https://developers.strava.com/docs/authentication/\n      - type: Getting Started\n        url: https://developers.strava.com/docs/getting-started/\n      - type: RateLimits\n\
  \        url: https://developers.strava.com/docs/rate-limits/\n      - type: Webhooks\n        url: https://developers.strava.com/docs/webhooks/\ncommon:\n  - type: Website\n    url: https://www.strava.com\n  - type: Developer Portal\n    url: https://developers.strava.com/\n  - type: Documentation\n    url: https://developers.strava.com/docs/\n  - type: Authentication\n    url: https://developers.strava.com/docs/authentication/\n  - type: Terms of Service\n    url: https://www.strava.com/legal/api\n  - type: Privacy Policy\n    url: https://www.strava.com/legal/privacy\n  - type: Status\n    url: https://status.strava.com\n  - type: Blog\n    url: https://blog.strava.com\n  - type: Forum\n    url: https://communityhub.strava.com/developers\n  - type: Sign Up\n    url: https://www.strava.com/register\n  - type: Login\n    url: https://www.strava.com/login\n  - type: App Registration\n    url: https://www.strava.com/settings/api\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/openapi/strava-openapi.yml\n\
  \  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/json-schema/strava-activity-schema.json\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/json-ld/strava-context.jsonld\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/apis.yml
tags:
- Cycling
- Fitness
- Fitness Tracking
- Running
- Sports
url: https://raw.githubusercontent.com/api-evangelist/strava/refs/heads/main/apis.yml
use_cases: []
---
