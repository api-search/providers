---
api_count: 2
api_specs:
- filename: thought-industries-openapi.yml
  format: yaml
  label: Thought Industries REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thought-industries/refs/heads/main/openapi/thought-industries-openapi.yml
apis:
- description: The Thought Industries REST API v1 provides programmatic access to users, enrollments, courses, groups, content, categories, bundles, reports, and learning paths. Authentication uses API key via X-API
  name: Thought Industries REST API
  slug: rest-api
- description: The Thought Industries GraphQL API provides flexible querying of platform data including courses, users, content, and enrollments. Available at /incoming/api/graphql with schema introspection supporte
  name: Thought Industries GraphQL API
  slug: graphql-api
capabilities:
- description: Unified learning management capability combining user lifecycle, course administration, enrollment management, and reporting for B2B learning platforms. Used by L&D teams, platform administrators, and
  name: Thought Industries Learning Management
  slug: learning-management
common:
- title: ''
  type: Website
  url: https://www.thoughtindustries.com/
- title: ''
  type: DeveloperPortal
  url: https://developer.thoughtindustries.com/
- title: ''
  type: Documentation
  url: https://api.thoughtindustries.com/
- title: ''
  type: GettingStarted
  url: https://developer.thoughtindustries.com/api-tutorials/
- title: ''
  type: Authentication
  url: https://academy.thoughtindustries.com/courses/api-keys
- title: ''
  type: GitHubOrganization
  url: https://github.com/thoughtindustries
- title: ''
  type: Webhooks
  url: https://developer.thoughtindustries.com/
- title: ''
  type: Support
  url: https://support.thoughtindustries.com/
created: '2025-03-01'
description: Thought Industries is a B2B learning platform (LMS/LXP) providing REST and GraphQL APIs for programmatic access to courses, users, enrollments, content management, and reporting. Their developer portal enables integration of learning experiences into enterprise workflows with webhook support and comprehensive API coverage for user lifecycle, content, and analytics.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 20
  name: Thought Industries Context
  property_count: 0
  slug: thought-industries-context
layout: provider
modified: '2026-05-03'
name: Thought Industries
rules:
- name: Thought Industries API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: thought-industries-rules
skills: []
slug: thought-industries
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: thought-industries\nname: Thought Industries\ndescription: >-\n  Thought Industries is a B2B learning platform (LMS/LXP) providing REST and\n  GraphQL APIs for programmatic access to courses, users, enrollments, content\n  management, and reporting. Their developer portal enables integration of\n  learning experiences into enterprise workflows with webhook support and\n  comprehensive API coverage for user lifecycle, content, and analytics.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Education\n  - Learning\n  - LMS\n  - LXP\n  - E-Learning\n  - Training\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/thought-industries/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: thought-industries:rest-api\n    name: Thought Industries REST API\n    description: >-\n      The Thought Industries REST\
  \ API v1 provides programmatic access to users,\n      enrollments, courses, groups, content, categories, bundles, reports, and\n      learning paths. Authentication uses API key via X-API-Key header or apiKey\n      query parameter. Base URL is tenant-scoped at\n      https://{subdomain}.thoughtindustries.com/incoming/api/v1/.\n    humanURL: https://developer.thoughtindustries.com/\n    baseURL: https://{subdomain}.thoughtindustries.com/incoming/api/v1\n    tags:\n      - Education\n      - Learning\n      - LMS\n      - REST\n      - Users\n      - Courses\n      - Enrollments\n    properties:\n      - type: Documentation\n        url: https://api.thoughtindustries.com/\n      - type: GettingStarted\n        url: https://developer.thoughtindustries.com/api-tutorials/\n      - type: Authentication\n        url: https://developer.thoughtindustries.com/api-tutorials/\n      - type: OpenAPI\n        url: openapi/thought-industries-openapi.yml\n      - type: JSONSchema\n        url: json-schema/thought-industries-user-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/thought-industries-enrollment-schema.json\n  - aid: thought-industries:graphql-api\n    name: Thought Industries GraphQL API\n    description: >-\n      The Thought Industries GraphQL API provides flexible querying of\n      platform data including courses, users, content, and enrollments. Available\n      at /incoming/api/graphql with schema introspection supported. Complements\n      the REST API for complex queries and mutations.\n    humanURL: https://developer.thoughtindustries.com/graphql/\n    baseURL: https://{subdomain}.thoughtindustries.com/incoming/api\n    tags:\n      - GraphQL\n      - Learning\n      - Education\n      - LMS\n    properties:\n      - type: Documentation\n        url: https://developer.thoughtindustries.com/graphql/\n      - type: GettingStarted\n        url: https://developer.thoughtindustries.com/api-tutorials/\ncommon:\n  - type: Website\n    url: https://www.thoughtindustries.com/\n  - type: DeveloperPortal\n\
  \    url: https://developer.thoughtindustries.com/\n  - type: Documentation\n    url: https://api.thoughtindustries.com/\n  - type: GettingStarted\n    url: https://developer.thoughtindustries.com/api-tutorials/\n  - type: Authentication\n    url: https://academy.thoughtindustries.com/courses/api-keys\n  - type: GitHubOrganization\n    url: https://github.com/thoughtindustries\n  - type: Webhooks\n    url: https://developer.thoughtindustries.com/\n  - type: Support\n    url: https://support.thoughtindustries.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/thought-industries/refs/heads/main/apis.yml
tags:
- Education
- Learning
- LMS
- LXP
- E-Learning
- Training
url: https://raw.githubusercontent.com/api-evangelist/thought-industries/refs/heads/main/apis.yml
use_cases: []
---
