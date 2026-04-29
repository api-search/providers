---
api_count: 1
apis:
- description: The Archbee API enables programmatic management of documentation spaces, pages, and content within the Archbee documentation platform.
  name: Archbee API
  slug: archbee-api
common:
- title: ''
  type: Portal
  url: https://www.archbee.com/
- title: ''
  type: Documentation
  url: https://docs.archbee.com/
- title: ''
  type: Blog
  url: https://www.archbee.com/blog
- title: ''
  type: SignUp
  url: https://app.archbee.com/signup
- title: ''
  type: Login
  url: https://app.archbee.com/login
- title: ''
  type: Pricing
  url: https://www.archbee.com/pricing
- title: ''
  type: GitHubOrganization
  url: https://github.com/archbee
- title: ''
  type: TermsOfService
  url: https://www.archbee.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.archbee.com/privacy
- title: ''
  type: StatusPage
  url: https://status.archbee.com/
- title: ''
  type: Support
  url: https://www.archbee.com/contact
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/rules/archbee-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/vocabulary/archbee-vocabulary.yaml
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/json-ld/archbee-api-context.jsonld
created: '2026-03-16'
description: Archbee is a documentation platform for software teams that enables creating, managing, and publishing technical documentation, API references, and knowledge bases. It provides tools for writing developer docs, API documentation, and internal wikis with collaborative editing and version control.
features:
- description: Create and publish beautiful API reference documentation with OpenAPI/Swagger support.
  name: API Documentation
- description: Real-time collaborative editing for documentation teams with version control.
  name: Collaborative Editing
- description: Build customizable developer portals with branded documentation sites.
  name: Developer Portal
- description: Internal and external knowledge base creation with powerful search.
  name: Knowledge Base
- description: Document versioning and change history for tracking documentation evolution.
  name: Version Control
- description: Integrations with GitHub, Slack, Jira, and other developer tools.
  name: Integrations
- description: AI-powered writing assistance for faster technical documentation creation.
  name: AI Writing Assistant
- description: Host documentation on custom domains with SSL included.
  name: Custom Domains
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Sync documentation with GitHub repositories for version-controlled docs-as-code workflows.
  name: GitHub
- description: Slack integration for documentation notifications and knowledge base search within Slack.
  name: Slack
- description: Link documentation pages to Jira issues for requirement traceability.
  name: Jira
- description: Embed Archbee knowledge base in Intercom for customer support.
  name: Intercom
- description: Analytics integration for tracking documentation usage and engagement.
  name: Segment
jsonld:
- class_count: 9
  name: Archbee Api Context
  property_count: 21
  slug: archbee-api-context
layout: provider
modified: '2026-04-19'
name: Archbee
rules:
- name: Archbee API Rules
  rule_count: 19
  severity_counts:
    error: 12
    hint: 0
    info: 1
    warn: 6
  slug: archbee-spectral-rules
skills: []
slug: archbee
solutions: []
source_yaml: "aid: archbee\nname: Archbee\ndescription: >-\n  Archbee is a documentation platform for software teams that enables creating,\n  managing, and publishing technical documentation, API references, and\n  knowledge bases. It provides tools for writing developer docs, API\n  documentation, and internal wikis with collaborative editing and version\n  control.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- API Documentation\n- Documentation Platform\n- Knowledge Base\n- Technical Writing\n- Developer Docs\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: archbee:archbee-api\n  name: Archbee API\n  description: >-\n    The Archbee API enables programmatic management of documentation spaces,\n    pages, and content within the Archbee documentation platform.\n  humanURL: https://www.archbee.com/\n\
  \  baseURL: https://api.archbee.com\n  tags:\n  - API Documentation\n  - Documentation Management\n  - Knowledge Base\n  - Technical Writing\n  properties:\n  - type: Documentation\n    url: https://docs.archbee.com/\n  - type: GettingStarted\n    url: https://docs.archbee.com/getting-started\n  - type: APIReference\n    url: https://docs.archbee.com/\n  - type: OpenAPI\n    url: https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/openapi/archbee-api.yaml\ncommon:\n- type: Portal\n  url: https://www.archbee.com/\n- type: Documentation\n  url: https://docs.archbee.com/\n- type: Blog\n  url: https://www.archbee.com/blog\n- type: SignUp\n  url: https://app.archbee.com/signup\n- type: Login\n  url: https://app.archbee.com/login\n- type: Pricing\n  url: https://www.archbee.com/pricing\n- type: GitHubOrganization\n  url: https://github.com/archbee\n- type: TermsOfService\n  url: https://www.archbee.com/terms\n- type: PrivacyPolicy\n  url: https://www.archbee.com/privacy\n\
  - type: StatusPage\n  url: https://status.archbee.com/\n- type: Support\n  url: https://www.archbee.com/contact\n- type: Features\n  data:\n  - name: API Documentation\n    description: Create and publish beautiful API reference documentation with OpenAPI/Swagger support.\n  - name: Collaborative Editing\n    description: Real-time collaborative editing for documentation teams with version control.\n  - name: Developer Portal\n    description: Build customizable developer portals with branded documentation sites.\n  - name: Knowledge Base\n    description: Internal and external knowledge base creation with powerful search.\n  - name: Version Control\n    description: Document versioning and change history for tracking documentation evolution.\n  - name: Integrations\n    description: Integrations with GitHub, Slack, Jira, and other developer tools.\n  - name: AI Writing Assistant\n    description: AI-powered writing assistance for faster technical documentation creation.\n  - name: Custom\
  \ Domains\n    description: Host documentation on custom domains with SSL included.\n- type: UseCases\n  data:\n  - name: API Documentation\n    description: Create comprehensive API reference docs with code samples, SDKs, and interactive API explorers.\n  - name: Developer Portal\n    description: Build a unified developer portal for all your APIs, SDKs, and developer resources.\n  - name: Internal Wiki\n    description: Create an internal knowledge base for engineering teams with runbooks, architecture docs, and processes.\n  - name: Customer Documentation\n    description: Publish customer-facing help documentation and user guides with powerful search.\n  - name: Product Documentation\n    description: Create and maintain product documentation for software products with versioning.\n- type: Integrations\n  data:\n  - name: GitHub\n    description: Sync documentation with GitHub repositories for version-controlled docs-as-code workflows.\n  - name: Slack\n    description: Slack integration\
  \ for documentation notifications and knowledge base search within Slack.\n  - name: Jira\n    description: Link documentation pages to Jira issues for requirement traceability.\n  - name: Intercom\n    description: Embed Archbee knowledge base in Intercom for customer support.\n  - name: Segment\n    description: Analytics integration for tracking documentation usage and engagement.\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/rules/archbee-spectral-rules.yml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/vocabulary/archbee-vocabulary.yaml\n- type: JSONLD\n  url: https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/json-ld/archbee-api-context.jsonld\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/apis.yml
tags:
- API Documentation
- Documentation Platform
- Knowledge Base
- Technical Writing
- Developer Docs
url: https://raw.githubusercontent.com/api-evangelist/archbee/refs/heads/main/apis.yml
use_cases:
- description: Create comprehensive API reference docs with code samples, SDKs, and interactive API explorers.
  name: API Documentation
- description: Build a unified developer portal for all your APIs, SDKs, and developer resources.
  name: Developer Portal
- description: Create an internal knowledge base for engineering teams with runbooks, architecture docs, and processes.
  name: Internal Wiki
- description: Publish customer-facing help documentation and user guides with powerful search.
  name: Customer Documentation
- description: Create and maintain product documentation for software products with versioning.
  name: Product Documentation
---
