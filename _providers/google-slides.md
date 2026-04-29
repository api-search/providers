---
api_count: 1
api_specs:
- filename: google-slides-api-openapi.yml
  format: yaml
  label: Google Slides API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-slides/refs/heads/main/openapi/google-slides-api-openapi.yml
apis:
- description: Create and edit presentations programmatically.
  name: Google Slides API
  slug: ''
capabilities:
- description: Unified presentation management workflow for creating, reading, editing, and generating thumbnails of Google Slides presentations for content creators and automation engineers.
  name: Google Slides Presentation Management
  slug: presentation-management
common:
- title: ''
  type: Portal
  url: https://console.cloud.google.com/
- title: ''
  type: Authentication
  url: https://developers.google.com/identity/protocols/oauth2
- title: ''
  type: GettingStarted
  url: https://developers.google.com/slides/api/quickstart/python
- title: ''
  type: StatusPage
  url: https://status.cloud.google.com/
- title: ''
  type: PrivacyPolicy
  url: https://policies.google.com/privacy
- title: ''
  type: TermsOfService
  url: https://policies.google.com/terms
- title: Developer Products
  type: Documentation
  url: https://developers.google.com/workspace/products
- title: Credentials
  type: Documentation
  url: https://developers.google.com/workspace/guides/create-credentials
- title: Enable APIs
  type: Documentation
  url: https://developers.google.com/workspace/guides/enable-apis
- title: OAuth Consent Screen
  type: Documentation
  url: https://developers.google.com/workspace/guides/configure-oauth-consent
- title: OAuth Scopes
  type: Authentication
  url: https://developers.google.com/identity/protocols/oauth2/scopes
- title: Issue Tracker
  type: Support
  url: https://issuetracker.google.com/bookmark-groups/78025
- title: Workspace Release Notes
  type: ReleaseNotes
  url: https://developers.google.com/workspace/release-notes
- title: ''
  type: Blog
  url: https://cloud.google.com/blog/products/application-development/introducing-google-slides-api
- title: ''
  type: SpectralRules
  url: rules/google-slides-spectral-rules.yml
- title: Google Slides API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/slides-api.yaml
- title: Presentation Management Workflow
  type: NaftikoCapability
  url: capabilities/presentation-management.yaml
created: '2024-01-01'
description: An API for creating, reading, and editing Google Slides presentations.
features:
- description: Create blank or pre-configured presentations programmatically with custom titles and layouts.
  name: Presentation Creation
- description: Apply multiple changes to a presentation in a single atomic request for efficient editing.
  name: Batch Updates
- description: Add, reorder, duplicate, and delete slides within presentations.
  name: Slide Management
- description: Insert and format text, shapes, images, videos, tables, and charts on slides.
  name: Text and Shape Editing
- description: Generate thumbnail images of individual slides for previews and exports.
  name: Page Thumbnails
- description: Use existing presentations as templates and populate them with dynamic content.
  name: Template Support
image: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png
integrations:
- description: Embed live charts and data from Google Sheets into presentations for dynamic data visualization.
  name: Google Sheets
- description: Store, organize, and share presentations through Google Drive with collaboration permissions.
  name: Google Drive
- description: Part of the Google Workspace suite with seamless integration across Docs, Sheets, and other apps.
  name: Google Workspace
- description: Automate Slides workflows using Apps Script for custom macros and triggers.
  name: Google Apps Script
- description: Deploy Slides API integrations on Google Cloud Platform infrastructure.
  name: Google Cloud
jsonld:
- class_count: 0
  name: Google Slides Context
  property_count: 0
  slug: google-slides-context
layout: provider
modified: '2026-04-18'
name: Google Slides
rules:
- name: Google Slides API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: google-slides-spectral-rules
skills: []
slug: google-slides
solutions: []
source_filename: apis.yml
source_yaml: "aid: google-slides\nname: Google Slides\ndescription: >-\n  An API for creating, reading, and editing Google Slides presentations.\nimage: https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png\nurl: https://developers.google.com/slides\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Collaboration\n  - Google Workspace\n  - Presentations\n  - Productivity\n  - Slides\napis:\n  - name: Google Slides API\n    description: >-\n      Create and edit presentations programmatically.\n    image: https://www.gstatic.com/images/branding/product/2x/slides_2020q4_48dp.png\n    humanURL: https://developers.google.com/slides\n    baseURL: https://slides.googleapis.com\n    tags:\n      - Presentations\n      - REST\n      - Slides\n    properties:\n      - type: Documentation\n        url: https://developers.google.com/slides/api/reference/rest\n      - type: OpenAPI\n        url: https://slides.googleapis.com/$discovery/rest?version=v1\n\
  \        title: Discovery Document\n      - type: OpenAPI\n        url: openapi/google-slides-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/google-slides-presentation-schema.json\n      - type: JSONLD\n        url: json-ld/google-slides-context.jsonld\n      - type: Authentication\n        url: https://developers.google.com/slides/api/guides/authorizing\n      - type: Quickstart\n        url: https://developers.google.com/slides/api/quickstart/python\n        title: Python Quickstart\n      - type: Documentation\n        url: https://developers.google.com/slides/api/guides/concepts\n        title: Concepts Guide\n      - type: CodeExamples\n        url: https://developers.google.com/slides/api/samples\n      - type: Pricing\n        url: https://developers.google.com/slides/api/limits\n      - type: TermsOfService\n        url: https://developers.google.com/terms\n      - type: Support\n        url: https://developers.google.com/slides/api/support\n      - type: Documentation\n\
  \        url: https://developers.google.com/workspace/slides/api/guides/overview\n        title: Overview\n      - type: SDK\n        url: https://developers.google.com/workspace/slides/api/guides/libraries\n        title: Client Libraries\n      - type: ReleaseNotes\n        url: https://developers.google.com/workspace/slides/release-notes\n      - type: Documentation\n        url: https://developers.google.com/workspace/slides/api/scopes\n        title: Scopes\n      - type: Troubleshooting\n        url: https://developers.google.com/workspace/slides/api/troubleshoot-authentication-authorization\n      - type: Quickstart\n        url: https://developers.google.com/slides/api/quickstart/java\n        title: Java Quickstart\n      - type: Quickstart\n        url: https://developers.google.com/workspace/slides/api/quickstart/nodejs\n        title: Node.js Quickstart\n      - type: Quickstart\n        url: https://developers.google.com/workspace/slides/api/quickstart/javascript\n       \
  \ title: JavaScript Quickstart\n      - type: Quickstart\n        url: https://developers.google.com/workspace/slides/api/quickstart/go\n        title: Go Quickstart\n      - type: Quickstart\n        url: https://developers.google.com/workspace/slides/api/quickstart/apps-script\n        title: Apps Script Quickstart\n      - type: YouTube\n        url: https://developers.google.com/workspace/slides/api/videos\n      - type: GitHubRepository\n        url: https://github.com/googleworkspace/slides-api\ncommon:\n  - type: Portal\n    url: https://console.cloud.google.com/\n  - type: Authentication\n    url: https://developers.google.com/identity/protocols/oauth2\n  - type: GettingStarted\n    url: https://developers.google.com/slides/api/quickstart/python\n  - type: StatusPage\n    url: https://status.cloud.google.com/\n  - type: PrivacyPolicy\n    url: https://policies.google.com/privacy\n  - type: TermsOfService\n    url: https://policies.google.com/terms\n  - type: Documentation\n   \
  \ url: https://developers.google.com/workspace/products\n    title: Developer Products\n  - type: Documentation\n    url: https://developers.google.com/workspace/guides/create-credentials\n    title: Credentials\n  - type: Documentation\n    url: https://developers.google.com/workspace/guides/enable-apis\n    title: Enable APIs\n  - type: Documentation\n    url: https://developers.google.com/workspace/guides/configure-oauth-consent\n    title: OAuth Consent Screen\n  - type: Authentication\n    url: https://developers.google.com/identity/protocols/oauth2/scopes\n    title: OAuth Scopes\n  - type: Support\n    url: https://issuetracker.google.com/bookmark-groups/78025\n    title: Issue Tracker\n  - type: ReleaseNotes\n    url: https://developers.google.com/workspace/release-notes\n    title: Workspace Release Notes\n  - type: Blog\n    url: https://cloud.google.com/blog/products/application-development/introducing-google-slides-api\n  - type: SpectralRules\n    url: rules/google-slides-spectral-rules.yml\n\
  \  - type: NaftikoCapability\n    url: capabilities/shared/slides-api.yaml\n    title: Google Slides API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/presentation-management.yaml\n    title: Presentation Management Workflow\n  - type: Features\n    url: https://developers.google.com/slides\n    data:\n      - name: Presentation Creation\n        description: Create blank or pre-configured presentations programmatically with custom titles and layouts.\n      - name: Batch Updates\n        description: Apply multiple changes to a presentation in a single atomic request for efficient editing.\n      - name: Slide Management\n        description: Add, reorder, duplicate, and delete slides within presentations.\n      - name: Text and Shape Editing\n        description: Insert and format text, shapes, images, videos, tables, and charts on slides.\n      - name: Page Thumbnails\n        description: Generate thumbnail images of individual slides for previews and exports.\n\
  \      - name: Template Support\n        description: Use existing presentations as templates and populate them with dynamic content.\n  - type: UseCases\n    url: https://developers.google.com/slides\n    data:\n      - name: Automated Report Generation\n        description: Generate presentation reports from data sources, populating charts, tables, and text automatically.\n      - name: Dynamic Presentation Templates\n        description: Create branded presentations from templates, filling in customer-specific data for sales or marketing decks.\n      - name: Educational Content Creation\n        description: Build educational slide decks programmatically from lesson plans, quizzes, or course materials.\n      - name: Meeting Preparation\n        description: Automatically compile meeting agendas, status updates, and metrics into presentation format.\n  - type: Integrations\n    url: https://developers.google.com/slides\n    data:\n      - name: Google Sheets\n        description: Embed\
  \ live charts and data from Google Sheets into presentations for dynamic data visualization.\n      - name: Google Drive\n        description: Store, organize, and share presentations through Google Drive with collaboration permissions.\n      - name: Google Workspace\n        description: Part of the Google Workspace suite with seamless integration across Docs, Sheets, and other apps.\n      - name: Google Apps Script\n        description: Automate Slides workflows using Apps Script for custom macros and triggers.\n      - name: Google Cloud\n        description: Deploy Slides API integrations on Google Cloud Platform infrastructure.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/google-slides/refs/heads/main/apis.yml
tags:
- Collaboration
- Google Workspace
- Presentations
- Productivity
- Slides
url: https://developers.google.com/slides
use_cases:
- description: Generate presentation reports from data sources, populating charts, tables, and text automatically.
  name: Automated Report Generation
- description: Create branded presentations from templates, filling in customer-specific data for sales or marketing decks.
  name: Dynamic Presentation Templates
- description: Build educational slide decks programmatically from lesson plans, quizzes, or course materials.
  name: Educational Content Creation
- description: Automatically compile meeting agendas, status updates, and metrics into presentation format.
  name: Meeting Preparation
---
