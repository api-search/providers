---
api_count: 18
apis:
- description: 'Figma allows designers to create and prototype their digital experiences - together in real-time and in one place - helping them turn their ideas and visions into products, faster. Figma''s mission is '
  name: Figma API
  slug: figma-api
- description: The Figma REST API provides programmatic access to Figma files, comments, components, and related resources. It enables developers to read and interact with design data, export assets, manage comments
  name: Figma REST API
  slug: figma-rest-api
- description: Figma Files API provides access to design file data including document trees, nodes, images, version history, and file metadata. Read and export design data from Figma files programmatically.
  name: Figma Files API
  slug: figma-files-api
- description: Figma Images API provides endpoints for rendering and exporting images from Figma files in various formats including PNG, JPG, SVG, and PDF.
  name: Figma Images API
  slug: figma-images-api
- description: Figma Teams API provides endpoints for managing team-level resources including webhooks, projects, and team configuration.
  name: Figma Teams API
  slug: figma-teams-api
- description: Figma Projects API provides endpoints for listing team projects and retrieving project files.
  name: Figma Projects API
  slug: figma-projects-api
- description: Figma Me API provides the endpoint for retrieving information about the currently authenticated user.
  name: Figma Me API
  slug: figma-me-api
- description: Figma Components API provides access to published components, component sets, and styles from team libraries. Query component metadata, retrieve thumbnails, and access documentation links for reusable
  name: Figma Components API
  slug: figma-components-api
- description: Figma Component Sets API provides endpoints for retrieving published component set metadata from team libraries.
  name: Figma Component Sets API
  slug: figma-component-sets-api
- description: Figma Styles API provides endpoints for retrieving published style metadata including colors, text styles, and effects from team libraries.
  name: Figma Styles API
  slug: figma-styles-api
- description: Figma Activity Logs API provides endpoints for retrieving activity log events for an organization, enabling audit trail and compliance monitoring.
  name: Figma Activity Logs API
  slug: figma-activity-logs-api
- description: Figma Payments API provides endpoints for querying user payment information on plugins, widgets, and Community files.
  name: Figma Payments API
  slug: figma-payments-api
- description: Figma Dev Resources API provides endpoints for creating, updating, and deleting dev resources attached to design nodes, enabling design-to-code workflows.
  name: Figma Dev Resources API
  slug: figma-dev-resources-api
- description: Figma Analytics API provides endpoints for tracking component, style, and variable usage across team libraries, enabling design system adoption measurement.
  name: Figma Analytics API
  slug: figma-analytics-api
- description: Figma Commenting mode allows users to leave comments directly on layers or objects on the canvas. You can use the Figma API to post comments and reactions to a Figma file, view existing comments and r
  name: Figma Comments API
  slug: figma-comments-api
- description: Figma allows you to distinguish different stages or versions of a file as it evolves over time. The Version History API provides endpoints to view, track, and restore previous versions of a file, reco
  name: Figma Version History API
  slug: figma-version-history-api
- description: The Variables REST API includes endpoints for querying, creating, updating, and deleting variables. Variables store reusable values that can be applied to design properties and prototyping actions. To
  name: Figma Variables API
  slug: figma-variables-api
- description: The Library Analytics REST API provides six methods for tracking component, style, and variable usage. Each resource type has an actions endpoint and a usages endpoint, allowing you to get time series
  name: Figma Library Analytics API
  slug: figma-library-analytics-api
asyncapis:
- description: Figma Webhooks allow applications to receive real-time notifications when events occur in Figma files and projects. Webhooks are configured at the team level and send HTTP POST requests with JSON payl
  name: Figma Webhooks
  slug: figma-webhooks-asyncapi
capabilities:
- description: Unified workflow for managing design files, components, styles, projects, comments, and asset export. Combines the Figma REST API endpoints into a cohesive design system management experience. Used by
  name: Figma Design System Management
  slug: design-system-management
common:
- title: ''
  type: Portal
  url: https://www.figma.com/developers
- title: ''
  type: Authentication
  url: https://developers.figma.com/docs/rest-api/authentication/
- title: ''
  type: ChangeLog
  url: https://developers.figma.com/docs/rest-api/changelog/
- title: ''
  type: RateLimits
  url: https://developers.figma.com/docs/rest-api/rate-limits/
- title: Figma REST API OpenAPI Specification
  type: OpenAPI
  url: https://github.com/figma/rest-api-spec
- title: ''
  type: GettingStarted
  url: https://developers.figma.com/docs/code-connect/quickstart-guide/
- title: ''
  type: SignUp
  url: https://www.figma.com/signup?cont=/developers/embed
- title: ''
  type: Login
  url: https://www.figma.com/login?cont=/developers/embed
- title: ''
  type: Pricing
  url: https://www.figma.com/pricing/
- title: ''
  type: Blog
  url: https://www.figma.com/blog/
- title: ''
  type: Security
  url: https://www.figma.com/security/
- title: ''
  type: StatusPage
  url: https://status.figma.com/
- title: ''
  type: TermsOfService
  url: https://www.figma.com/legal/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.figma.com/legal/privacy/
- title: ''
  type: Partners
  url: https://www.figma.com/partners/
- title: ''
  type: Events
  url: https://www.figma.com/events/
- title: ''
  type: Support
  url: https://help.figma.com/hc/en-us/
- title: ''
  type: Contact
  url: https://www.figma.com/contact/
- title: Forum
  type: Support
  url: https://forum.figma.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/figma
- title: REST API OpenAPI Specification
  type: GitHubRepository
  url: https://github.com/figma/rest-api-spec
- title: Code Connect
  type: GitHubRepository
  url: https://github.com/figma/code-connect
- title: Plugin API Typings
  type: GitHubRepository
  url: https://github.com/figma/plugin-typings
- title: Community Resources
  type: GitHubRepository
  url: https://github.com/figma/community-resources
- title: MCP Server Guide
  type: GitHubRepository
  url: https://github.com/figma/mcp-server-guide
- title: ''
  type: SpectralRules
  url: rules/figma-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/figma-vocabulary.yaml
- title: REST API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/rest-api.yaml
- title: Design System Management Workflow
  type: NaftikoCapability
  url: capabilities/design-system-management.yaml
created: '2023-11-22'
description: Figma is a collaborative interface design tool with a comprehensive REST API for accessing and manipulating design files, projects, and teams.
features:
- description: Multiple designers and stakeholders can work on the same file simultaneously with live cursors and instant updates.
  name: Real-Time Collaboration
- description: Create and maintain component libraries, styles, and variables that teams can share and reuse across projects.
  name: Design Systems
- description: Build interactive prototypes with transitions, animations, and smart animate to demonstrate user flows.
  name: Prototyping
- description: Developers can inspect designs, copy CSS/code snippets, and access design tokens directly from Figma files.
  name: Dev Mode
- description: Receive real-time notifications when files are updated, comments are added, or library components are published.
  name: Webhooks
- description: Export design assets in PNG, JPG, SVG, and PDF formats at multiple scales via the API.
  name: Asset Export
- description: Define and manage design tokens as variables that can be applied across components and exported for development.
  name: Variables and Design Tokens
- description: Enterprise organizations can track and audit user activity across files, projects, and teams.
  name: Activity Logging
- description: Track component, style, and variable adoption across teams to measure design system usage.
  name: Library Analytics
image: https://www.figma.com/favicon.ico
integrations:
- description: Receive Figma file update notifications and preview designs directly in Slack channels.
  name: Slack
- description: Embed Figma designs in Jira issues and link design tasks to development tickets.
  name: Jira
- description: Link Figma designs to pull requests and track design-to-code implementation.
  name: GitHub
- description: Connect Figma components to Storybook stories using Code Connect for design-code parity.
  name: Storybook
- description: Export designs from Figma to Zeplin for detailed developer handoff and style guides.
  name: Zeplin
- description: Version control and branching for Figma design files with Abstract integration.
  name: Abstract
- description: Share and preview Figma designs within Microsoft Teams conversations and channels.
  name: Microsoft Teams
jsonld:
- class_count: 0
  name: Figma Activity Logs Context
  property_count: 0
  slug: figma-activity-logs-context
- class_count: 0
  name: Figma Analytics Context
  property_count: 0
  slug: figma-analytics-context
- class_count: 0
  name: Figma Component Sets Context
  property_count: 0
  slug: figma-component-sets-context
- class_count: 0
  name: Figma Context
  property_count: 0
  slug: figma-context
- class_count: 0
  name: Figma Dev Resources Context
  property_count: 0
  slug: figma-dev-resources-context
- class_count: 0
  name: Figma Files Context
  property_count: 0
  slug: figma-files-context
- class_count: 0
  name: Figma Images Context
  property_count: 0
  slug: figma-images-context
- class_count: 0
  name: Figma Me Context
  property_count: 0
  slug: figma-me-context
- class_count: 0
  name: Figma Payments Context
  property_count: 0
  slug: figma-payments-context
- class_count: 0
  name: Figma Projects Context
  property_count: 0
  slug: figma-projects-context
- class_count: 0
  name: Figma Rest Context
  property_count: 0
  slug: figma-rest-context
- class_count: 0
  name: Figma Styles Context
  property_count: 0
  slug: figma-styles-context
- class_count: 0
  name: Figma Teams Context
  property_count: 0
  slug: figma-teams-context
layout: provider
modified: '2026-04-18'
name: Figma
rules:
- name: Figma API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: figma-spectral-rules
skills: []
slug: figma
solutions: []
source_yaml: "aid: figma\nname: Figma\ndescription: Figma is a collaborative interface design tool with a comprehensive REST API for accessing and manipulating design files, projects, and teams.\nurl: https://raw.githubusercontent.com/api-evangelist/figma/refs/heads/main/apis.yml\nimage: https://www.figma.com/favicon.ico\ntags:\n  - Collaboration\n  - Design\n  - Graphics\n  - Interfaces\n  - Prototypes\n  - Prototyping\n  - UI/UX\ncreated: '2023-11-22'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\napis:\n  - aid: figma:figma-api\n    name: Figma API\n    description: >-\n      Figma allows designers to create and prototype their digital experiences - together\n      in real-time and in one place - helping them turn their ideas and visions into\n      products, faster. Figma's mission is to make design accessible to everyone.\n      The Figma API is one of the ways we aim to do that.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n\
  \    humanURL: https://www.figma.com/developers\n    tags:\n      - Design\n      - Users\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-api-openapi.yml\n      - type: OpenAPI\n        url: openapi/figma-rest-api-openapi.yml\n        title: Figma REST API\n      - type: AsyncAPI\n        url: asyncapi/figma-webhooks-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/figma-file-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-component-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-user-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-error-response-payload-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-get-me-response-body-schema.json\n      - type: JSONStructure\n        url: json-structure/figma-get-me-response-body-structure.json\n      - type: JSONStructure\n        url: json-structure/figma-error-response-payload-structure.json\n      - type: JSONStructure\n \
  \       url: json-structure/figma-user-structure.json\n      - type: JSONLD\n        url: json-ld/figma-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/\n  - aid: figma:figma-rest-api\n    name: Figma REST API\n    description: >-\n      The Figma REST API provides programmatic access to Figma files, comments,\n      components, and related resources. It enables developers to read and interact\n      with design data, export assets, manage comments and reactions, and query\n      published components and styles from team libraries.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/\n    tags:\n      - Comments\n      - Components\n      - Files\n      - Projects\n      - Users\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-rest-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-file-response-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/figma-rest-get-file-nodes-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-images-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-image-fills-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-file-versions-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-comments-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-post-comment-request-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-reactions-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-team-components-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-file-components-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-component-response-schema.json\n     \
  \ - type: JSONSchema\n        url: json-schema/figma-rest-get-team-component-sets-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-team-styles-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-team-projects-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-get-project-files-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-error-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-branch-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-canvas-node-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-client-meta-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-color-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-comment-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-component-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/figma-rest-component-set-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-document-node-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-documentation-link-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-frame-info-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-pagination-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-project-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-project-file-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-published-component-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-published-component-set-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-published-style-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-reaction-schema.json\n      - type: JSONSchema\n\
  \        url: json-schema/figma-rest-style-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-success-response-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-user-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-rest-version-schema.json\n      - type: JSONLD\n        url: json-ld/figma-rest-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/\n  - aid: figma:figma-files-api\n    name: Figma Files API\n    description: Figma Files API provides access to design file data including document trees, nodes, images, version history, and file metadata. Read and export design data from Figma files programmatically.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/file-endpoints/\n    tags:\n      - Dev Resources\n      - Files\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-files-api-openapi.yml\n\
  \      - type: JSONSchema\n        url: json-schema/figma-files-get-file-response-body-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-branch-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-canvas-node-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-color-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-comment-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-component-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-component-set-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-delete-dev-resource-response-body-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-dev-resource-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-document-node-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-documentation-link-schema.json\n  \
  \    - type: JSONSchema\n        url: json-schema/figma-files-error-response-payload-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-frame-info-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-get-dev-resources-response-body-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-published-component-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-published-component-set-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-reaction-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-style-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-style-type-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-user-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-files-version-schema.json\n      - type: JSONLD\n        url: json-ld/figma-files-context.jsonld\n      - type: Documentation\n\
  \        url: https://developers.figma.com/docs/rest-api/file-endpoints/\n  - aid: figma:figma-images-api\n    name: Figma Images API\n    description: Figma Images API provides endpoints for rendering and exporting images from Figma files in various formats including PNG, JPG, SVG, and PDF.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/file-endpoints/\n    tags:\n      - Export\n      - Images\n      - Rendering\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-images-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/figma-images-get-images-response-body-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-images-bad-request-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-images-error-response-payload-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-images-forbidden-error-schema.json\n      -\
  \ type: JSONSchema\n        url: json-schema/figma-images-internal-server-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-images-not-found-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-images-too-many-requests-error-schema.json\n      - type: JSONLD\n        url: json-ld/figma-images-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/file-endpoints/\n  - aid: figma:figma-teams-api\n    name: Figma Teams API\n    description: Figma Teams API provides endpoints for managing team-level resources including webhooks, projects, and team configuration.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/file-endpoints/\n    tags:\n      - Teams\n      - Webhooks\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-teams-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/figma-teams-get-team-webhooks-response-body-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/figma-teams-webhook-v2-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-teams-webhook-v2-event-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-teams-webhook-v2-status-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-teams-error-response-payload-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-teams-forbidden-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-teams-internal-server-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-teams-not-found-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-teams-too-many-requests-error-schema.json\n      - type: JSONLD\n        url: json-ld/figma-teams-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/file-endpoints/\n  - aid: figma:figma-projects-api\n    name: Figma Projects API\n    description:\
  \ Figma Projects API provides endpoints for listing team projects and retrieving project files.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/projects-types/\n    tags:\n      - Files\n      - Projects\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-projects-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/figma-projects-get-project-files-response-body-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-projects-project-file-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-projects-bad-request-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-projects-error-response-payload-with-err-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-projects-error-response-payload-with-message-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-projects-forbidden-error-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/figma-projects-internal-server-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-projects-too-many-requests-error-schema.json\n      - type: JSONLD\n        url: json-ld/figma-projects-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/projects-types/\n  - aid: figma:figma-me-api\n    name: Figma Me API\n    description: Figma Me API provides the endpoint for retrieving information about the currently authenticated user.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/users-endpoints/\n    tags:\n      - Authentication\n      - Users\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-me-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/figma-me-user-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-me-user-with-email-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/figma-me-error-response-payload-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-me-forbidden-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-me-internal-server-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-me-too-many-requests-error-schema.json\n      - type: JSONLD\n        url: json-ld/figma-me-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/users-endpoints/\n  - aid: figma:figma-components-api\n    name: Figma Components API\n    description: Figma Components API provides access to published components, component sets, and styles from team libraries. Query component metadata, retrieve thumbnails, and access documentation links for reusable design elements.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/component-types/\n\
  \    tags:\n      - Components\n      - Design Systems\n      - Libraries\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-rest-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/figma-component-schema.json\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/component-types/\n  - aid: figma:figma-component-sets-api\n    name: Figma Component Sets API\n    description: Figma Component Sets API provides endpoints for retrieving published component set metadata from team libraries.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/component-types/\n    tags:\n      - Component Sets\n      - Design Systems\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-component-sets-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/figma-component-sets-get-component-set-response-body-schema.json\n      - type:\
  \ JSONSchema\n        url: json-schema/figma-component-sets-published-component-set-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-component-sets-frame-info-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-component-sets-user-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-component-sets-error-response-payload-with-err-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-component-sets-error-response-payload-with-error-schema.json\n      - type: JSONLD\n        url: json-ld/figma-component-sets-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/component-types/\n  - aid: figma:figma-styles-api\n    name: Figma Styles API\n    description: Figma Styles API provides endpoints for retrieving published style metadata including colors, text styles, and effects from team libraries.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n\
  \    humanURL: https://developers.figma.com/docs/rest-api/component-types/\n    tags:\n      - Design Systems\n      - Styles\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-styles-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/figma-styles-get-style-response-body-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-styles-published-style-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-styles-style-type-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-styles-user-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-styles-bad-request-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-styles-error-response-payload-with-err-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-styles-error-response-payload-with-message-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-styles-forbidden-error-schema.json\n      -\
  \ type: JSONSchema\n        url: json-schema/figma-styles-internal-server-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-styles-not-found-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-styles-too-many-requests-error-schema.json\n      - type: JSONLD\n        url: json-ld/figma-styles-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/component-types/\n  - aid: figma:figma-activity-logs-api\n    name: Figma Activity Logs API\n    description: Figma Activity Logs API provides endpoints for retrieving activity log events for an organization, enabling audit trail and compliance monitoring.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/activity-logs/\n    tags:\n      - Activity Logs\n      - Audit\n      - Compliance\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-activity-logs-api-openapi.yml\n\
  \      - type: JSONSchema\n        url: json-schema/figma-activity-logs-get-activity-logs-response-body-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-activity-logs-activity-log-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-activity-logs-activity-log-action-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-activity-logs-activity-log-actor-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-activity-logs-activity-log-context-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-activity-logs-activity-log-entity-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-activity-logs-activity-log-file-entity-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-activity-logs-activity-log-org-entity-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-activity-logs-activity-log-project-entity-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-activity-logs-activity-log-team-entity-schema.json\n\
  \      - type: JSONSchema\n        url: json-schema/figma-activity-logs-activity-log-user-entity-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-activity-logs-activity-logs-meta-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-activity-logs-error-response-payload-schema.json\n      - type: JSONLD\n        url: json-ld/figma-activity-logs-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/activity-logs/\n  - aid: figma:figma-payments-api\n    name: Figma Payments API\n    description: Figma Payments API provides endpoints for querying user payment information on plugins, widgets, and Community files.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/plugins/api/figma-payments/\n    tags:\n      - Monetization\n      - Payments\n      - Plugins\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-payments-api-openapi.yml\n\
  \      - type: JSONSchema\n        url: json-schema/figma-payments-get-payments-response-body-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-payments-payment-information-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-payments-payment-status-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-payments-error-response-payload-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-payments-internal-server-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-payments-too-many-requests-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-payments-unauthorized-error-schema.json\n      - type: JSONLD\n        url: json-ld/figma-payments-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/plugins/api/figma-payments/\n  - aid: figma:figma-dev-resources-api\n    name: Figma Dev Resources API\n    description: Figma Dev Resources API provides\
  \ endpoints for creating, updating, and deleting dev resources attached to design nodes, enabling design-to-code workflows.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/dev-resources/\n    tags:\n      - Design to Code\n      - Dev Resources\n      - Development\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-dev-resources-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/figma-dev-resources-create-dev-resource-item-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-dev-resources-create-dev-resources-request-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-dev-resources-dev-resource-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-dev-resources-dev-resource-create-error-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-dev-resources-dev-resource-update-error-schema.json\n   \
  \   - type: JSONSchema\n        url: json-schema/figma-dev-resources-error-response-payload-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-dev-resources-post-dev-resources-response-body-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-dev-resources-put-dev-resources-response-body-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-dev-resources-update-dev-resource-item-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-dev-resources-update-dev-resources-request-schema.json\n      - type: JSONLD\n        url: json-ld/figma-dev-resources-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/dev-resources/\n  - aid: figma:figma-analytics-api\n    name: Figma Analytics API\n    description: Figma Analytics API provides endpoints for tracking component, style, and variable usage across team libraries, enabling design system adoption measurement.\n    image: https://www.figma.com/favicon.ico\n\
  \    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/library-analytics-intro/\n    tags:\n      - Analytics\n      - Design Systems\n      - Libraries\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-analytics-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/figma-analytics-get-library-analytics-usages-response-body-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-analytics-library-analytics-usages-by-component-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-analytics-library-analytics-usages-by-file-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-analytics-library-analytics-actions-by-component-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-analytics-library-analytics-actions-by-team-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-analytics-library-analytics-style-usages-by-asset-schema.json\n     \
  \ - type: JSONSchema\n        url: json-schema/figma-analytics-library-analytics-style-usages-by-file-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-analytics-library-analytics-variable-usages-by-asset-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-analytics-library-analytics-variable-usages-by-file-schema.json\n      - type: JSONSchema\n        url: json-schema/figma-analytics-error-response-payload-schema.json\n      - type: JSONLD\n        url: json-ld/figma-analytics-context.jsonld\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/library-analytics-intro/\n  - aid: figma:figma-comments-api\n    name: Figma Comments API\n    description: Figma Commenting mode allows users to leave comments directly on layers or objects on the canvas. You can use the Figma API to post comments and reactions to a Figma file, view existing comments and reactions, and access information about a comment including when it was\
  \ made, by whom, and its exact location on the canvas.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/comments-endpoints/\n    tags:\n      - Annotations\n      - Collaboration\n      - Comments\n      - Reactions\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-rest-api-openapi.yml\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/comments-endpoints/\n  - aid: figma:figma-version-history-api\n    name: Figma Version History API\n    description: Figma allows you to distinguish different stages or versions of a file as it evolves over time. The Version History API provides endpoints to view, track, and restore previous versions of a file, recorded in the version history.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/version-history-endpoints/\n   \
  \ tags:\n      - Files\n      - History\n      - Versions\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-rest-api-openapi.yml\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/version-history-endpoints/\n  - aid: figma:figma-variables-api\n    name: Figma Variables API\n    description: The Variables REST API includes endpoints for querying, creating, updating, and deleting variables. Variables store reusable values that can be applied to design properties and prototyping actions. To use this API, you must have a Full seat in an Enterprise org.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/variables-endpoints/\n    tags:\n      - Collections\n      - Design Tokens\n      - Variables\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-rest-api-openapi.yml\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/variables-endpoints/\n\
  \  - aid: figma:figma-library-analytics-api\n    name: Figma Library Analytics API\n    description: The Library Analytics REST API provides six methods for tracking component, style, and variable usage. Each resource type has an actions endpoint and a usages endpoint, allowing you to get time series data about user actions and usage data for your library assets.\n    image: https://www.figma.com/favicon.ico\n    baseURL: https://api.figma.com\n    humanURL: https://developers.figma.com/docs/rest-api/library-analytics-endpoints/\n    tags:\n      - Analytics\n      - Components\n      - Libraries\n      - Styles\n      - Usages\n      - Variables\n    properties:\n      - type: OpenAPI\n        url: openapi/figma-rest-api-openapi.yml\n      - type: Documentation\n        url: https://developers.figma.com/docs/rest-api/library-analytics-endpoints/\ncommon:\n  - type: Portal\n    url: https://www.figma.com/developers\n  - type: Authentication\n    url: https://developers.figma.com/docs/rest-api/authentication/\n\
  \  - type: ChangeLog\n    url: https://developers.figma.com/docs/rest-api/changelog/\n  - type: RateLimits\n    url: https://developers.figma.com/docs/rest-api/rate-limits/\n  - type: OpenAPI\n    url: https://github.com/figma/rest-api-spec\n    title: Figma REST API OpenAPI Specification\n  - type: GettingStarted\n    url: https://developers.figma.com/docs/code-connect/quickstart-guide/\n  - type: SignUp\n    url: https://www.figma.com/signup?cont=/developers/embed\n  - type: Login\n    url: https://www.figma.com/login?cont=/developers/embed\n  - type: Pricing\n    url: https://www.figma.com/pricing/\n  - type: Blog\n    url: https://www.figma.com/blog/\n  - type: Security\n    url: https://www.figma.com/security/\n  - type: StatusPage\n    url: https://status.figma.com/\n  - type: TermsOfService\n    url: https://www.figma.com/legal/tos/\n  - type: PrivacyPolicy\n    url: https://www.figma.com/legal/privacy/\n  - type: Partners\n    url: https://www.figma.com/partners/\n  - type: Events\n\
  \    url: https://www.figma.com/events/\n  - type: Support\n    url: https://help.figma.com/hc/en-us/\n  - type: Contact\n    url: https://www.figma.com/contact/\n  - type: Support\n    url: https://forum.figma.com/\n    title: Forum\n  - type: GitHubOrganization\n    url: https://github.com/figma\n  - type: GitHubRepository\n    url: https://github.com/figma/rest-api-spec\n    title: REST API OpenAPI Specification\n  - type: GitHubRepository\n    url: https://github.com/figma/code-connect\n    title: Code Connect\n  - type: GitHubRepository\n    url: https://github.com/figma/plugin-typings\n    title: Plugin API Typings\n  - type: GitHubRepository\n    url: https://github.com/figma/community-resources\n    title: Community Resources\n  - type: GitHubRepository\n    url: https://github.com/figma/mcp-server-guide\n    title: MCP Server Guide\n  - type: SpectralRules\n    url: rules/figma-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/figma-vocabulary.yaml\n  - type: NaftikoCapability\n\
  \    url: capabilities/shared/rest-api.yaml\n    title: REST API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/design-system-management.yaml\n    title: Design System Management Workflow\n  - type: Features\n    data:\n      - name: Real-Time Collaboration\n        description: Multiple designers and stakeholders can work on the same file simultaneously with live cursors and instant updates.\n      - name: Design Systems\n        description: Create and maintain component libraries, styles, and variables that teams can share and reuse across projects.\n      - name: Prototyping\n        description: Build interactive prototypes with transitions, animations, and smart animate to demonstrate user flows.\n      - name: Dev Mode\n        description: Developers can inspect designs, copy CSS/code snippets, and access design tokens directly from Figma files.\n      - name: Webhooks\n        description: Receive real-time notifications when files are updated, comments\
  \ are added, or library components are published.\n      - name: Asset Export\n        description: Export design assets in PNG, JPG, SVG, and PDF formats at multiple scales via the API.\n      - name: Variables and Design Tokens\n        description: Define and manage design tokens as variables that can be applied across components and exported for development.\n      - name: Activity Logging\n        description: Enterprise organizations can track and audit user activity across files, projects, and teams.\n      - name: Library Analytics\n        description: Track component, style, and variable adoption across teams to measure design system usage.\n  - type: UseCases\n    data:\n      - name: Design System Management\n        description: Build, publish, and track adoption of shared component libraries across product teams.\n      - name: Automated Asset Export\n        description: Programmatically export design assets for build pipelines and content delivery workflows.\n      - name:\
  \ Design-to-Code Handoff\n        description: Attach code references to design nodes using dev resources for seamless developer handoff.\n \n\n# --- truncated at 32 KB (33 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/figma/refs/heads/main/apis.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/figma/refs/heads/main/apis.yml
tags:
- Collaboration
- Design
- Graphics
- Interfaces
- Prototypes
- Prototyping
- UI/UX
url: https://raw.githubusercontent.com/api-evangelist/figma/refs/heads/main/apis.yml
use_cases:
- description: Build, publish, and track adoption of shared component libraries across product teams.
  name: Design System Management
- description: Programmatically export design assets for build pipelines and content delivery workflows.
  name: Automated Asset Export
- description: Attach code references to design nodes using dev resources for seamless developer handoff.
  name: Design-to-Code Handoff
- description: Extend Figma with custom plugins and widgets using the Plugin API and Widget API.
  name: Plugin and Widget Development
- description: Monitor organization activity logs for security compliance and access auditing.
  name: Compliance and Audit
- description: Programmatically back up file data and version history for disaster recovery.
  name: Design File Backup
---
