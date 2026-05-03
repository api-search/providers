---
api_count: 2
api_specs:
- filename: tray-ai-embedded-api-openapi.yml
  format: yaml
  label: Tray.ai Embedded API
  slug: embedded-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tray-ai/refs/heads/main/openapi/tray-ai-embedded-api-openapi.yml
- filename: tray-ai-platform-api-openapi.yml
  format: yaml
  label: Tray.ai Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tray-ai/refs/heads/main/openapi/tray-ai-platform-api-openapi.yml
apis:
- description: The Tray.ai Embedded API is a GraphQL-based API that allows partners and customers to present in-app embedded integration experiences. It provides programmatic access to manage users, solutions, solut
  name: Tray.ai Embedded API
  slug: embedded-api
- description: The Tray.ai Platform API (also known as the Connectivity API) provides direct programmatic REST access to Tray's 700+ pre-built service connectors, authentication management, trigger subscriptions, us
  name: Tray.ai Platform API
  slug: platform-api
capabilities:
- description: Unified workflow capability combining the Tray.ai Platform API and Embedded API for building and managing automated integrations. Covers connector discovery and invocation, embedded user lifecycle, so
  name: Tray.ai Integration Automation
  slug: integration-automation
common:
- title: ''
  type: NaftikoCapability
  url: capabilities/integration-automation.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/tray-ai-vocabulary.yml
- title: ''
  type: Plans
  url: https://tray.ai/packages
- title: ''
  type: Login
  url: https://app.tray.io/login
- title: ''
  type: Blog
  url: https://tray.ai/blog
- title: ''
  type: CaseStudies
  url: https://tray.ai/customers
- title: ''
  type: PrivacyPolicy
  url: https://tray.ai/privacy
- title: ''
  type: TermsOfService
  url: https://tray.ai/terms
- title: ''
  type: Status
  url: https://status.tray.ai/
- title: ''
  type: Website
  url: https://tray.ai/
- title: ''
  type: Portal
  url: https://developer.tray.ai/
created: '2025-06-05'
description: Tray.ai is an AI-ready integration and automation platform that helps enterprises connect systems, teams, and data. It provides 700+ pre-built connectors, a visual workflow builder, embedded integration capabilities, and programmatic APIs for building and managing integrations at scale.
features:
- name: 600+ Connectors
- name: Account Audit Log Streaming
- name: Advanced On-Prem
- name: All Packages Include
- name: Auth API
- name: Auth Collector
- name: Composable Templates
- name: Connectivity API
- name: Connector Builder
- name: Connector Development Kit (Sdk)
- name: Customer Success Resources
- name: Dedicated Slack Channel
- name: Embedded Bundle
- name: HIPAA
- name: In-App Support
- name: Insights
- name: Intelligent Document Processing
- name: Live Workshops
- name: Log Retention
- name: Log Streaming
- name: Management API
- name: Merlin Build
- name: Multi-Factor Authentication
- name: No Log Retention
- name: Regional Hosting
- name: Role-Based Access Control
- name: SSO
- name: Starter Task Credit
- name: Static IP for On-Prem
- name: Support
- name: Tray Academy
- name: Tray Advantage
- name: Tray Advantage Plus
- name: Tray Community
- name: Trigger API
- name: Usage
- name: User Interfaces
- name: Workflows
- name: Workspaces
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 51
  name: Tray Ai Context
  property_count: 0
  slug: tray-ai-context
layout: provider
modified: '2026-05-03'
name: Tray.ai
rules:
- name: Tray.ai API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: tray-ai-rules
skills: []
slug: tray-ai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tray-ai\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tray-ai/refs/heads/main/apis.yml\napis:\n  - aid: tray-ai:embedded-api\n    name: Tray.ai Embedded API\n    tags:\n      - Automation\n      - Embedded\n      - GraphQL\n      - Integration\n    humanURL: https://developer.tray.ai/openapi/embeddedapi-introduction/\n    baseURL: https://tray.io/graphql\n    properties:\n      - url: https://developer.tray.ai/openapi/embeddedapi-introduction/\n        type: Documentation\n      - url: openapi/tray-ai-embedded-api-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/tray-docs/tray-io-s-public-workspace/collection/uo51x8u/tray-embedded-apis-graphql\n        type: PostmanCollection\n      - url: json-schema/user.json\n        type: JSONSchema\n      - url: json-schema/solution.json\n        type: JSONSchema\n      - url: json-schema/solution-instance.json\n        type: JSONSchema\n      - url: json-schema/authentication.json\n        type:\
  \ JSONSchema\n      - url: json-ld/tray-ai-context.jsonld\n        type: JSONLD\n      - url: json-structure/tray-ai-solution-instance-structure.json\n        type: JSONStructure\n      - url: examples/tray-ai-create-solution-instance-example.json\n        type: Example\n      - url: capabilities/shared/embedded-api.yaml\n        type: NaftikoCapability\n    description: >-\n      The Tray.ai Embedded API is a GraphQL-based API that allows partners\n      and customers to present in-app embedded integration experiences.\n      It provides programmatic access to manage users, solutions, solution\n      instances, authentications, workflows, and connector operations via\n      HTTP POST to the GraphQL endpoint with Bearer token authentication.\n  - aid: tray-ai:platform-api\n    name: Tray.ai Platform API\n    tags:\n      - Automation\n      - Connectors\n      - Integration\n      - iPaaS\n    humanURL: https://developer.tray.ai/openapi/trayapi/overview/\n    baseURL: https://api.tray.io/core/v1\n\
  \    properties:\n      - url: https://developer.tray.ai/openapi/trayapi/overview/\n        type: Documentation\n      - url: openapi/tray-ai-platform-api-openapi.yml\n        type: OpenAPI\n      - url: json-schema/connector.json\n        type: JSONSchema\n      - url: json-schema/authentication.json\n        type: JSONSchema\n      - url: json-schema/subscription.json\n        type: JSONSchema\n      - url: json-schema/user.json\n        type: JSONSchema\n      - url: json-schema/workspace.json\n        type: JSONSchema\n      - url: json-ld/tray-ai-context.jsonld\n        type: JSONLD\n      - url: json-structure/tray-ai-connector-structure.json\n        type: JSONStructure\n      - url: examples/tray-ai-list-connectors-example.json\n        type: Example\n      - url: examples/tray-ai-call-connector-example.json\n        type: Example\n      - url: examples/tray-ai-create-authentication-example.json\n        type: Example\n      - url: rules/tray-ai-rules.yml\n        type: SpectralRuleset\n\
  \      - url: capabilities/shared/platform-api.yaml\n        type: NaftikoCapability\n    description: >-\n      The Tray.ai Platform API (also known as the Connectivity API) provides\n      direct programmatic REST access to Tray's 700+ pre-built service\n      connectors, authentication management, trigger subscriptions, user and\n      workspace administration, and project/solution lifecycle operations. It\n      enables developers to integrate third-party service operations into their\n      own applications without using the Builder UI.\nname: Tray.ai\ntags:\n  - Automation\n  - Integration\n  - iPaaS\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-06-05'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  Tray.ai is an AI-ready integration and automation platform that helps\n  enterprises connect systems, teams, and data. It provides 700+ pre-built\n  connectors, a visual workflow builder,\
  \ embedded integration capabilities,\n  and programmatic APIs for building and managing integrations at scale.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\ncommon:\n  - name: Tray.ai Integration Automation Capability\n    url: capabilities/integration-automation.yaml\n    type: NaftikoCapability\n  - name: Tray.ai Vocabulary\n    url: vocabulary/tray-ai-vocabulary.yml\n    type: Vocabulary\n  - name: Tray.ai Pricing | Compare AI agent & iPaaS plans\n    description: 'null'\n    url: https://tray.ai/packages\n    type: Plans\n  - name: Connector Hub\n    description: 'null'\n    url: https://tray.ai/connectors?sort=alphabetical\n    type: Integrations\n  - name: Tray.ai | Login\n    data:\n      - name: Acuity Scheduling\n      - name: Adobe Experience Manager\n      - name: Airtable\n      - name: Alteryx\n      - name: Anthropic\n      - name: ArcGIS\n      - name: Asana\n      - name: Atlassian Confluence\n      - name: Attentive Mobile\n\
  \      - name: AWS Bedrock\n      - name: AWS SageMaker\n      - name: Basecamp 2\n      - name: Box\n      - name: Bynder\n      - name: Calendly\n      - name: Cisco Webex\n      - name: ClickUp\n      - name: Coda\n      - name: Cohere\n      - name: Contentsquare Metrics API\n      - name: DocRaptor\n      - name: DocuSign\n      - name: Domo\n      - name: Drift\n      - name: Dropbox\n      - name: FirstRain\n      - name: Float\n      - name: Formstack\n      - name: Front\n      - name: G Suite\n      - name: Getty\n      - name: Giphy\n      - name: Gmail\n      - name: Google Calendar\n      - name: Google Chat\n      - name: Google Contacts\n      - name: Google Docs\n      - name: Google Drive\n      - name: Google Maps\n      - name: Google Sheets\n      - name: Google Slides\n      - name: Google Tasks\n      - name: Google Vision\n      - name: GoTo Meeting\n      - name: GoTo Webinar\n      - name: Harvest\n      - name: HelloSign\n      - name: Hive\n      - name: Huddle\n\
  \      - name: Hunter\n      - name: iContact\n      - name: Intercom\n      - name: iOffice\n      - name: Jira\n      - name: Jive\n      - name: Jotform\n      - name: Kapost\n      - name: Keatext\n      - name: Keen IO\n      - name: Kickbox\n      - name: LivePerson\n      - name: Looker\n      - name: MessageBird\n      - name: Microsoft Calendar\n      - name: Microsoft OneDrive\n      - name: Microsoft Outlook\n      - name: Microsoft Power BI\n      - name: Microsoft Sharepoint\n      - name: Microsoft Teams\n      - name: Monday\n      - name: MongoDB Cloud\n      - name: NewsCred\n      - name: Nexmo\n      - name: Nimble\n      - name: Notion\n      - name: Ooma\n      - name: OpenAI\n      - name: OptimoRoute\n      - name: Oracle Bronto\n      - name: Oracle Responsys\n      - name: Oxford Dictionaries\n      - name: PandaDoc\n      - name: Paymo\n      - name: Pinecone\n      - name: Plivo\n      - name: Qlik\n      - name: RingCentral\n      - name: Ringover\n      - name:\
  \ ruum by SAP\n      - name: Salesforce\n      - name: Samsara\n      - name: Scoop\n      - name: SearchBlox\n      - name: Sedna\n      - name: Sitecore\n      - name: Slack\n      - name: Smartsheet\n      - name: Sprinklr\n      - name: Teamwork\n      - name: Toggl\n      - name: Trello\n      - name: Twilio\n      - name: Typeform\n      - name: Uberflip\n      - name: Unbounce\n      - name: Vbrick\n      - name: VideoAsk\n      - name: Vonage\n      - name: WordPress\n      - name: Workfront\n      - name: Workplace by Facebook\n      - name: Workstack\n      - name: Wrike\n      - name: Wufoo\n      - name: Wunderlist\n      - name: Xverify\n      - name: Yammer\n      - name: Yodiz\n      - name: Zendesk\n      - name: Zoom\n      - name: ZoomInfo\n    url: https://app.tray.io/login\n    type: Login\n  - name: Blogs - All\n    description: 'null'\n    url: https://tray.ai/blog\n    type: Blog\n  - name: Customers\n    description: 'null'\n    url: https://tray.ai/customers\n\
  \    type: CaseStudies\n  - name: Privacy Policy\n    description: 'null'\n    url: https://tray.ai/privacy\n    type: PrivacyPolicy\n  - name: Master Subscription Agreement\n    description: 'null'\n    url: https://tray.ai/terms\n    type: TermsOfService\n  - name: Tray.ai Status\n    description: 'null'\n    url: https://status.tray.ai/\n    type: Status\n  - name: AI-ready integration & automation platform\n    description: 'null'\n    url: https://tray.ai/\n    type: Website\n  - name: Developer Portal\n    description: 'null'\n    url: https://developer.tray.ai/\n    type: Portal\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: E-commerce\n      - name: Embedded integrations\n      - name: IT Onboarding\n      - name: Lead lifecycle\n      - name: Order-to-cash\n  - name: Features\n    type: Features\n    data:\n      - name: 600+ Connectors\n      - name: Account Audit Log Streaming\n      - name: Advanced On-Prem\n      - name: All Packages Include\n      - name:\
  \ Auth API\n      - name: Auth Collector\n      - name: Composable Templates\n      - name: Connectivity API\n      - name: Connector Builder\n      - name: Connector Development Kit (Sdk)\n      - name: Customer Success Resources\n      - name: Dedicated Slack Channel\n      - name: Embedded Bundle\n      - name: HIPAA\n      - name: In-App Support\n      - name: Insights\n      - name: Intelligent Document Processing\n      - name: Live Workshops\n      - name: Log Retention\n      - name: Log Streaming\n      - name: Management API\n      - name: Merlin Build\n      - name: Multi-Factor Authentication\n      - name: No Log Retention\n      - name: Regional Hosting\n      - name: Role-Based Access Control\n      - name: SSO\n      - name: Starter Task Credit\n      - name: Static IP for On-Prem\n      - name: Support\n      - name: Tray Academy\n      - name: Tray Advantage\n      - name: Tray Advantage Plus\n      - name: Tray Community\n      - name: Trigger API\n      - name: Usage\n\
  \      - name: User Interfaces\n      - name: Workflows\n      - name: Workspaces\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tray-ai/refs/heads/main/apis.yml
tags:
- Automation
- Integration
- iPaaS
url: https://raw.githubusercontent.com/api-evangelist/tray-ai/refs/heads/main/apis.yml
use_cases:
- name: E-commerce
- name: Embedded integrations
- name: IT Onboarding
- name: Lead lifecycle
- name: Order-to-cash
---
