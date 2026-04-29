---
api_count: 7
api_specs:
- filename: jira-cloud-platform-rest-api-openapi.yml
  format: yaml
  label: Jira Cloud Platform REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jira/refs/heads/main/openapi/jira-cloud-platform-rest-api-openapi.yml
apis:
- description: The Jira Cloud platform REST API for building apps and integrations.
  name: Jira Cloud Platform REST API
  slug: ''
- description: Version 2 of the Jira Cloud platform REST API, offering the same operations as v3 but without Atlassian Document Format support.
  name: Jira Cloud Platform REST API v2
  slug: ''
- description: REST API for Jira Software features including boards, sprints, and backlogs.
  name: Jira Software Cloud REST API
  slug: ''
- description: REST API for Jira Service Management features including queues, customers, requests, and SLAs.
  name: Jira Service Management REST API
  slug: ''
- description: Operations APIs for Jira Service Management covering schedules, on-call rotations, alerts, escalations, and incident management.
  name: Jira Service Management Operations REST API
  slug: ''
- description: REST API for Jira Align enterprise agile planning platform, providing access to portfolios, epics, features, and program management data.
  name: Jira Align REST API
  slug: ''
- description: REST API for Atlassian Customer Service Management providing access to customers, organizations, products, and entitlements data.
  name: Jira Customer Service Management REST API
  slug: ''
asyncapis:
- description: Jira Cloud webhooks deliver HTTP POST payloads to a configured URL whenever specified events occur in your Jira instance. Webhooks can be registered via the Jira REST API or through the Jira administr
  name: Jira Cloud Webhooks
  slug: jira-webhooks-asyncapi
capabilities:
- description: Unified project management workflow combining issue tracking, workflow transitions, JQL search, and project management. Used by project managers, developers, and team leads to manage agile software de
  name: Jira Project Management
  slug: project-management
common:
- title: ''
  type: Portal
  url: https://developer.atlassian.com/cloud/jira/platform/
- title: ''
  type: GettingStarted
  url: https://developer.atlassian.com/cloud/jira/platform/getting-started/
- title: ''
  type: SDK
  url: https://developer.atlassian.com/cloud/jira/platform/libraries/
- title: OAuth 2.0
  type: Authentication
  url: https://developer.atlassian.com/cloud/jira/platform/oauth-2-3lo-apps/
- title: ''
  type: Support
  url: https://support.atlassian.com/
- title: ''
  type: StatusPage
  url: https://status.atlassian.com/
- title: ''
  type: TermsOfService
  url: https://www.atlassian.com/legal/cloud-terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.atlassian.com/legal/privacy-policy
- title: ''
  type: ChangeLog
  url: https://developer.atlassian.com/changelog/
- title: ''
  type: Blog
  url: https://www.atlassian.com/blog/developer
- title: ''
  type: Marketplace
  url: https://developer.atlassian.com/platform/marketplace/getting-started/
- title: ''
  type: RateLimits
  url: https://developer.atlassian.com/cloud/jira/platform/rate-limiting/
- title: ''
  type: Security
  url: https://developer.atlassian.com/cloud/jira/platform/security-overview/
- title: ''
  type: JSONSchema
  url: json-schema/jira-issue-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/jira-project-schema.json
- title: ''
  type: JSONLD
  url: json-ld/jira-context.jsonld
created: '2024'
description: APIs for Atlassian Jira project management and issue tracking platform.
features:
- description: Powerful Jira Query Language enabling complex issue searches with field-based filtering, functions, and operators.
  name: JQL Search
- description: Configurable workflow transitions with validators, conditions, and post-functions for automated issue lifecycle management.
  name: Workflow Automation
- description: Scrum and Kanban boards with sprint planning, backlog management, and velocity tracking for agile teams.
  name: Agile Boards
- description: SLA management with configurable goals, time tracking, and breach notifications for service management.
  name: Service Level Agreements
- description: Real-time event notifications for issue changes, sprint events, and board updates via configurable webhook endpoints.
  name: Webhooks
- description: Rich text document format supporting structured content in issue descriptions and comments via the v3 API.
  name: Atlassian Document Format
image: https://www.atlassian.com/dam/jcr:e33efd9e-e0b8-4d61-a24d-68a48ef9bbe4/jira-icon-blue.svg
integrations:
- description: Link Jira issues to Confluence pages for seamless knowledge management and documentation alongside project tracking.
  name: Confluence
- description: Connect code repositories to Jira issues for automated status updates, smart commits, and development tracking.
  name: Bitbucket
- description: Link GitHub pull requests, branches, and commits to Jira issues for end-to-end development visibility.
  name: GitHub
- description: Create and manage Jira issues from Slack channels with bi-directional notifications and status updates.
  name: Slack
- description: Receive Jira notifications and manage issues directly from Microsoft Teams conversations.
  name: Microsoft Teams
jsonld:
- class_count: 0
  name: Jira Cloud Platform Rest Context
  property_count: 0
  slug: jira-cloud-platform-rest-context
- class_count: 0
  name: Jira Context
  property_count: 15
  slug: jira-context
layout: provider
modified: '2026-04-18'
name: Jira
rules:
- name: Jira API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: jira-spectral-rules
skills: []
slug: jira
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Jira\ndescription: >-\n  APIs for Atlassian Jira project management and issue tracking platform.\nimage: https://www.atlassian.com/dam/jcr:e33efd9e-e0b8-4d61-a24d-68a48ef9bbe4/jira-icon-blue.svg\nurl: https://www.atlassian.com/software/jira\ncreated: '2024'\nmodified: '2026-04-18'\nspecificationVersion: '0.18'\ntags:\n  - Agile\n  - Issue Tracking\n  - ITSM\n  - Project Management\n  - Service Management\napis:\n  - name: Jira Cloud Platform REST API\n    description: >-\n      The Jira Cloud platform REST API for building apps and integrations.\n    image: https://www.atlassian.com/dam/jcr:e33efd9e-e0b8-4d61-a24d-68a48ef9bbe4/jira-icon-blue.svg\n    humanURL: https://developer.atlassian.com/cloud/jira/platform/\n    baseURL: https://your-domain.atlassian.net/rest/api/3\n    tags:\n      - Agile\n      - Issues\n      - Project Management\n      - Projects\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://developer.atlassian.com/cloud/jira/platform/rest/v3/intro/\n\
  \      - type: OpenAPI\n        url: https://dac-static.atlassian.com/cloud/jira/platform/swagger-v3.v3.json\n      - type: OpenAPI\n        url: openapi/jira-cloud-platform-rest-api-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/jira-webhooks-asyncapi.yml\n      - type: Authentication\n        url: https://developer.atlassian.com/cloud/jira/platform/rest/v3/intro/#authentication\n      - type: RateLimits\n        url: https://developer.atlassian.com/cloud/jira/platform/rate-limiting/\n      - type: ChangeLog\n        url: https://developer.atlassian.com/cloud/jira/platform/changelog/\n      - type: Security\n        url: https://developer.atlassian.com/cloud/jira/platform/security-overview/\n      - type: GettingStarted\n        url: https://developer.atlassian.com/cloud/jira/platform/getting-started/\n  - name: Jira Cloud Platform REST API v2\n    description: >-\n      Version 2 of the Jira Cloud platform REST API, offering the same operations\n      as v3 but without Atlassian\
  \ Document Format support.\n    image: https://www.atlassian.com/dam/jcr:e33efd9e-e0b8-4d61-a24d-68a48ef9bbe4/jira-icon-blue.svg\n    humanURL: https://developer.atlassian.com/cloud/jira/platform/rest/v2/intro/\n    baseURL: https://your-domain.atlassian.net/rest/api/2\n    tags:\n      - Issues\n      - Legacy\n      - Project Management\n      - Projects\n      - Workflows\n    properties:\n      - type: Documentation\n        url: https://developer.atlassian.com/cloud/jira/platform/rest/v2/intro/\n      - type: Authentication\n        url: https://developer.atlassian.com/cloud/jira/platform/rest/v3/intro/#authentication\n      - type: ChangeLog\n        url: https://developer.atlassian.com/cloud/jira/platform/changelog/\n      - type: Security\n        url: https://developer.atlassian.com/cloud/jira/platform/security-overview/\n  - name: Jira Software Cloud REST API\n    description: >-\n      REST API for Jira Software features including boards, sprints, and backlogs.\n    image: https://www.atlassian.com/dam/jcr:e33efd9e-e0b8-4d61-a24d-68a48ef9bbe4/jira-icon-blue.svg\n\
  \    humanURL: https://developer.atlassian.com/cloud/jira/software/\n    baseURL: https://your-domain.atlassian.net/rest/agile/1.0\n    tags:\n      - Agile\n      - Boards\n      - Kanban\n      - Scrum\n      - Sprints\n    properties:\n      - type: Documentation\n        url: https://developer.atlassian.com/cloud/jira/software/rest/intro/\n      - type: OpenAPI\n        url: https://dac-static.atlassian.com/cloud/jira/software/swagger.v3.json\n      - type: CodeExamples\n        url: https://developer.atlassian.com/cloud/jira/software/rest/intro/#examples\n      - type: ChangeLog\n        url: https://developer.atlassian.com/cloud/jira/software/changelog/\n      - type: Security\n        url: https://developer.atlassian.com/cloud/jira/software/security-overview/\n      - type: GettingStarted\n        url: https://developer.atlassian.com/cloud/jira/software/getting-started-with-forge/\n      - type: Authentication\n        url: https://developer.atlassian.com/cloud/jira/software/security-overview/\n\
  \  - name: Jira Service Management REST API\n    description: >-\n      REST API for Jira Service Management features including queues, customers, requests,\n      and SLAs.\n    image: https://www.atlassian.com/dam/jcr:e33efd9e-e0b8-4d61-a24d-68a48ef9bbe4/jira-icon-blue.svg\n    humanURL: https://developer.atlassian.com/cloud/jira/service-desk/\n    baseURL: https://your-domain.atlassian.net/rest/servicedeskapi\n    tags:\n      - Customers\n      - ITSM\n      - Requests\n      - Service Desk\n      - SLA\n    properties:\n      - type: Documentation\n        url: https://developer.atlassian.com/cloud/jira/service-desk/rest/intro/\n      - type: OpenAPI\n        url: https://dac-static.atlassian.com/cloud/jira/service-desk/swagger.v3.json\n      - type: ChangeLog\n        url: https://developer.atlassian.com/cloud/jira/service-desk/changelog/\n      - type: Security\n        url: https://developer.atlassian.com/cloud/jira/service-desk/security-overview/\n  - name: Jira Service Management\
  \ Operations REST API\n    description: >-\n      Operations APIs for Jira Service Management covering schedules, on-call rotations,\n      alerts, escalations, and incident management.\n    image: https://www.atlassian.com/dam/jcr:e33efd9e-e0b8-4d61-a24d-68a48ef9bbe4/jira-icon-blue.svg\n    humanURL: https://developer.atlassian.com/cloud/jira/service-desk-ops/introduction/introduction/\n    baseURL: https://api.atlassian.com/jsm/ops/api/{cloudId}\n    tags:\n      - Alerts\n      - Escalations\n      - Incidents\n      - On-Call\n      - Operations\n      - Schedules\n    properties:\n      - type: Documentation\n        url: https://developer.atlassian.com/cloud/jira/service-desk-ops/rest/v2/intro/\n      - type: Authentication\n        url: https://developer.atlassian.com/cloud/jira/service-desk-ops/security/basic-auth-for-rest-apis/\n  - name: Jira Align REST API\n    description: >-\n      REST API for Jira Align enterprise agile planning platform, providing access\n      to portfolios,\
  \ epics, features, and program management data.\n    image: https://www.atlassian.com/dam/jcr:e33efd9e-e0b8-4d61-a24d-68a48ef9bbe4/jira-icon-blue.svg\n    humanURL: https://help.jiraalign.com/hc/en-us/articles/360045371954-Getting-started-with-the-REST-API-2-0\n    baseURL: https://your-domain.jiraalign.com/rest/align/api/2\n    tags:\n      - Enterprise Agile\n      - Planning\n      - Portfolios\n      - Program Management\n      - SAFe\n    properties:\n      - type: Documentation\n        url: https://help.jiraalign.com/hc/en-us/sections/360008049974-API-2-0\n      - type: GettingStarted\n        url: https://help.jiraalign.com/hc/en-us/articles/360045371954-Getting-started-with-the-REST-API-2-0\n      - type: RateLimits\n        url: https://help.jiraalign.com/hc/en-us/articles/360045371954-Getting-started-with-the-REST-API-2-0\n      - type: Authentication\n        url: https://help.jiraalign.com/hc/en-us/articles/360045371954-Getting-started-with-the-REST-API-2-0\n  - name: Jira\
  \ Customer Service Management REST API\n    description: >-\n      REST API for Atlassian Customer Service Management providing access to customers,\n      organizations, products, and entitlements data.\n    image: https://www.atlassian.com/dam/jcr:e33efd9e-e0b8-4d61-a24d-68a48ef9bbe4/jira-icon-blue.svg\n    humanURL: https://developer.atlassian.com/cloud/customer-service-management/\n    baseURL: https://your-domain.atlassian.net\n    tags:\n      - Customer Service\n      - Customers\n      - Entitlements\n      - Organizations\n    properties:\n      - type: Documentation\n        url: https://developer.atlassian.com/cloud/customer-service-management/rest/v1/api-group-customer/\n      - type: Authentication\n        url: https://developer.atlassian.com/cloud/customer-service-management/apis/narratives/authentication/\n      - type: GettingStarted\n        url: https://developer.atlassian.com/cloud/customer-service-management/\nmaintainers:\n  - name: Atlassian\n    email: ecosystem@atlassian.com\n\
  \    url: https://www.atlassian.com\n  - name: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://developer.atlassian.com/cloud/jira/platform/\n  - type: GettingStarted\n    url: https://developer.atlassian.com/cloud/jira/platform/getting-started/\n  - type: SDK\n    url: https://developer.atlassian.com/cloud/jira/platform/libraries/\n  - type: Authentication\n    url: https://developer.atlassian.com/cloud/jira/platform/oauth-2-3lo-apps/\n    title: OAuth 2.0\n  - type: Support\n    url: https://support.atlassian.com/\n  - type: StatusPage\n    url: https://status.atlassian.com/\n  - type: TermsOfService\n    url: https://www.atlassian.com/legal/cloud-terms-of-service\n  - type: PrivacyPolicy\n    url: https://www.atlassian.com/legal/privacy-policy\n  - type: ChangeLog\n    url: https://developer.atlassian.com/changelog/\n  - type: Blog\n    url: https://www.atlassian.com/blog/developer\n  - type: Marketplace\n    url: https://developer.atlassian.com/platform/marketplace/getting-started/\n\
  \  - type: RateLimits\n    url: https://developer.atlassian.com/cloud/jira/platform/rate-limiting/\n  - type: Security\n    url: https://developer.atlassian.com/cloud/jira/platform/security-overview/\n  - type: JSONSchema\n    url: json-schema/jira-issue-schema.json\n    name: Jira Issue Schema\n  - type: JSONSchema\n    url: json-schema/jira-project-schema.json\n    name: Jira Project Schema\n  - type: JSONLD\n    url: json-ld/jira-context.jsonld\n    name: Jira JSON-LD Context\n  - type: Features\n    data:\n      - name: JQL Search\n        description: Powerful Jira Query Language enabling complex issue searches with field-based filtering, functions, and operators.\n      - name: Workflow Automation\n        description: Configurable workflow transitions with validators, conditions, and post-functions for automated issue lifecycle management.\n      - name: Agile Boards\n        description: Scrum and Kanban boards with sprint planning, backlog management, and velocity tracking for\
  \ agile teams.\n      - name: Service Level Agreements\n        description: SLA management with configurable goals, time tracking, and breach notifications for service management.\n      - name: Webhooks\n        description: Real-time event notifications for issue changes, sprint events, and board updates via configurable webhook endpoints.\n      - name: Atlassian Document Format\n        description: Rich text document format supporting structured content in issue descriptions and comments via the v3 API.\n  - type: UseCases\n    data:\n      - name: Issue Tracking Automation\n        description: Automate issue creation, assignment, and transitions based on external events from CI/CD pipelines, monitoring tools, or customer feedback systems.\n      - name: Sprint Management\n        description: Programmatically manage sprints, backlogs, and board configurations for automated agile workflow orchestration.\n      - name: Service Desk Integration\n        description: Integrate customer\
  \ support channels with Jira Service Management for automated ticket creation and SLA tracking.\n      - name: Incident Management\n        description: Automate incident response workflows with on-call scheduling, alert routing, and escalation management.\n      - name: Enterprise Agile Planning\n        description: Connect portfolio planning tools with Jira Align for cross-team dependency tracking and program-level reporting.\n  - type: Integrations\n    data:\n      - name: Confluence\n        description: Link Jira issues to Confluence pages for seamless knowledge management and documentation alongside project tracking.\n      - name: Bitbucket\n        description: Connect code repositories to Jira issues for automated status updates, smart commits, and development tracking.\n      - name: GitHub\n        description: Link GitHub pull requests, branches, and commits to Jira issues for end-to-end development visibility.\n      - name: Slack\n        description: Create and manage\
  \ Jira issues from Slack channels with bi-directional notifications and status updates.\n      - name: Microsoft Teams\n        description: Receive Jira notifications and manage issues directly from Microsoft Teams conversations.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/jira/refs/heads/main/apis.yml
tags:
- Agile
- Issue Tracking
- ITSM
- Project Management
- Service Management
url: https://www.atlassian.com/software/jira
use_cases:
- description: Automate issue creation, assignment, and transitions based on external events from CI/CD pipelines, monitoring tools, or customer feedback systems.
  name: Issue Tracking Automation
- description: Programmatically manage sprints, backlogs, and board configurations for automated agile workflow orchestration.
  name: Sprint Management
- description: Integrate customer support channels with Jira Service Management for automated ticket creation and SLA tracking.
  name: Service Desk Integration
- description: Automate incident response workflows with on-call scheduling, alert routing, and escalation management.
  name: Incident Management
- description: Connect portfolio planning tools with Jira Align for cross-team dependency tracking and program-level reporting.
  name: Enterprise Agile Planning
---
