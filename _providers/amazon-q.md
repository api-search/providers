---
api_count: 5
apis:
- description: 'API for Amazon Q Business, a fully managed generative AI-powered enterprise chat assistant that you can deploy within your organization. It enables employees to ask questions, get summaries, generate '
  name: Amazon Q Business API
  slug: ''
- description: API for Amazon Q Apps, a feature within Amazon Q Business that allows web experience users to create lightweight, purpose-built AI apps to fulfill specific tasks using their enterprise data. It suppor
  name: Amazon Q Business QApps API
  slug: ''
- description: API for Amazon Q Developer, the most capable generative AI-powered assistant for software development. It provides inline code suggestions, chat-based coding assistance, security scanning, code transf
  name: Amazon Q Developer API
  slug: ''
- description: API for Amazon Q in Connect, a generative AI-powered customer service assistant integrated with Amazon Connect. It automatically detects customer intent during calls and chats using conversational ana
  name: Amazon Q Connect API
  slug: ''
- description: API for Amazon Q Developer in chat applications, which enables integration of Amazon Q Developer capabilities into messaging platforms. It provides descriptions, request parameters, and response forma
  name: Amazon Q Developer in Chat Applications API
  slug: ''
capabilities:
- description: Workflow capability for Amazon Q. Enables automation of Amazon Q resources for cloud operations teams.
  name: Amazon Q Operations
  slug: amazon-q
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/q/
- title: ''
  type: GettingStarted
  url: https://aws.amazon.com/q/getting-started/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/amazonq/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/aws/tag/amazon-q/
- title: ''
  type: FAQ
  url: https://aws.amazon.com/q/faqs/
- title: ''
  type: Support
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Pricing
  url: https://aws.amazon.com/q/pricing/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: SDK
  url: https://aws.amazon.com/tools/
- title: ''
  type: Portal
  url: https://console.aws.amazon.com/
- title: ''
  type: SignUp
  url: https://portal.aws.amazon.com/billing/signup
- title: ''
  type: Community
  url: https://repost.aws/tags/TALmcXzmfeRaKOzrBowJ9cJQ/amazon-q
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: JSON-LD
  url: json-ld/amazon-q-openapi-application-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/amazon-q-openapi-conversation-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/amazon-q-openapi-data-source-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/amazon-q-openapi-index-context.jsonld
- title: ''
  type: JSON-LD
  url: json-ld/amazon-q-openapi-message-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/amazon-q-openapi-application-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amazon-q-openapi-conversation-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amazon-q-openapi-data-source-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amazon-q-openapi-index-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/amazon-q-openapi-message-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-q-openapi-application-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-q-openapi-conversation-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-q-openapi-data-source-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-q-openapi-index-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/amazon-q-openapi-message-structure.json
- title: ''
  type: Example
  url: examples/amazon-q-openapi-application-example.json
- title: ''
  type: Example
  url: examples/amazon-q-openapi-conversation-example.json
- title: ''
  type: Example
  url: examples/amazon-q-openapi-data-source-example.json
- title: ''
  type: Example
  url: examples/amazon-q-openapi-index-example.json
- title: ''
  type: Example
  url: examples/amazon-q-openapi-message-example.json
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-q.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/amazon-q.yaml
- title: ''
  type: SpectralRules
  url: rules/amazon-q-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-q-vocabulary.yaml
- title: ''
  type: OpenAPI
  url: openapi/amazon-q-openapi.yml
created: 2024-01-15 00:00:00+00:00
description: Amazon Q is a generative AI-powered assistant that helps with various tasks including answering questions, generating content, and taking actions based on your enterprise data and systems. It is available in multiple product variants including Amazon Q Business for enterprise knowledge, Amazon Q Developer for software development, and Amazon Q in Connect for customer service agents.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 1
  name: Amazon Q Openapi Application Context
  property_count: 5
  slug: amazon-q-openapi-application-context
- class_count: 1
  name: Amazon Q Openapi Conversation Context
  property_count: 3
  slug: amazon-q-openapi-conversation-context
- class_count: 1
  name: Amazon Q Openapi Data Source Context
  property_count: 4
  slug: amazon-q-openapi-data-source-context
- class_count: 1
  name: Amazon Q Openapi Index Context
  property_count: 3
  slug: amazon-q-openapi-index-context
- class_count: 1
  name: Amazon Q Openapi Message Context
  property_count: 4
  slug: amazon-q-openapi-message-context
layout: provider
modified: '2026-04-19'
name: Amazon Q
rules:
- name: Amazon Q API Rules
  rule_count: 19
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 10
  slug: amazon-q-spectral-rules
skills: []
slug: amazon-q
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Q\ndescription: >-\n  Amazon Q is a generative AI-powered assistant that helps with various tasks\n  including answering questions, generating content, and taking actions based on\n  your enterprise data and systems. It is available in multiple product variants\n  including Amazon Q Business for enterprise knowledge, Amazon Q Developer for\n  software development, and Amazon Q in Connect for customer service agents.\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/apis.yml\ncreated: 2024-01-15 00:00:00+00:00\nmodified: '2026-04-19'\nspecificationVersion: '0.18'\ntags:\n- Artificial Intelligence\n- Assistant\n- AWS\n- Enterprise\n- Generative AI\napis:\n- name: Amazon Q Business API\n  description: >-\n    API for Amazon Q Business, a fully managed generative AI-powered enterprise\n    chat assistant that you can deploy within your organization. It enables\n\
  \    employees to ask questions, get summaries, generate content, and complete\n    tasks using enterprise data from connected data sources with\n    permissions-aware responses.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://aws.amazon.com/q/business/\n  baseURL: https://qbusiness.{region}.amazonaws.com\n  tags:\n  - Business Intelligence\n  - Enterprise\n  - Generative AI\n  - Knowledge Management\n  - Q&A\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/amazonq/latest/qbusiness-ug/\n  - type: OpenAPI\n    url: https://example.com/openapi/amazon-q-business.json\n  - type: Authentication\n    url: https://docs.aws.amazon.com/amazonq/latest/qbusiness-ug/security-iam.html\n  - type: Pricing\n    url: https://aws.amazon.com/q/business/pricing/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/amazonq/latest/api-reference/Welcome.html\n  - type: GettingStarted\n    url: https://aws.amazon.com/q/business/getting-started/\n\
  \  - type: Features\n    url: https://aws.amazon.com/q/business/features/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/amazonq/latest/qbusiness-ug/what-is.html\n  - type: CLI\n    url: https://docs.aws.amazon.com/cli/latest/reference/qbusiness/\n  - type: SDK\n    url: https://aws.amazon.com/tools/\n  - type: Quotas\n    url: https://docs.aws.amazon.com/amazonq/latest/qbusiness-ug/quotas-regions.html\n  - type: ChangeLog\n    url: https://docs.aws.amazon.com/amazonq/latest/qbusiness-ug/doc-history.html\n- name: Amazon Q Business QApps API\n  description: >-\n    API for Amazon Q Apps, a feature within Amazon Q Business that allows web\n    experience users to create lightweight, purpose-built AI apps to fulfill\n    specific tasks using their enterprise data. It supports creating, managing,\n    sharing, and running custom Q Apps through a library system.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://docs.aws.amazon.com/amazonq/latest/api-reference/API_Operations_QApps.html\n\
  \  baseURL: https://qbusiness.{region}.amazonaws.com\n  tags:\n  - Applications\n  - Enterprise\n  - Generative AI\n  - Low Code\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/amazonq/latest/qbusiness-ug/\n  - type: APIReference\n    url: https://docs.aws.amazon.com/amazonq/latest/api-reference/API_Operations_QApps.html\n- name: Amazon Q Developer API\n  description: >-\n    API for Amazon Q Developer, the most capable generative AI-powered assistant\n    for software development. It provides inline code suggestions, chat-based\n    coding assistance, security scanning, code transformations, and agentic\n    feature development across IDEs, the CLI, and the AWS Management Console.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://aws.amazon.com/q/developer/\n  baseURL: https://q.{region}.amazonaws.com\n  tags:\n  - AI Assistant\n  - Code Generation\n  - Developer Tools\n  - IDE Integration\n  - Security\
  \ Scanning\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/\n  - type: OpenAPI\n    url: https://example.com/openapi/amazon-q-developer.json\n  - type: Authentication\n    url: https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/security-iam.html\n  - type: Pricing\n    url: https://aws.amazon.com/q/developer/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/q/developer/getting-started/\n  - type: Features\n    url: https://aws.amazon.com/q/developer/features/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/what-is.html\n  - type: Quotas\n    url: https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/quotas.html\n  - type: SDK\n    url: https://aws.amazon.com/tools/\n  - type: ChangeLog\n    url: https://docs.aws.amazon.com/amazonq/latest/qdeveloper-ug/doc-history.html\n  - type: GitHubRepository\n    url: https://github.com/aws/amazon-q-developer-cli\n- name:\
  \ Amazon Q Connect API\n  description: >-\n    API for Amazon Q in Connect, a generative AI-powered customer service\n    assistant integrated with Amazon Connect. It automatically detects customer\n    intent during calls and chats using conversational analytics and natural\n    language understanding, then provides contact center agents with real-time\n    generative responses, suggested actions, and links to relevant documents.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://aws.amazon.com/connect/q/\n  baseURL: https://wisdom.{region}.amazonaws.com\n  tags:\n  - Agent Assistance\n  - Contact Center\n  - Customer Service\n  - Generative AI\n  - Real-Time\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/connect/latest/adminguide/amazon-q-connect.html\n  - type: APIReference\n    url: https://docs.aws.amazon.com/connect/latest/APIReference/API_Operations_Amazon_Q_Connect.html\n  - type: CLI\n    url:\
  \ https://docs.aws.amazon.com/cli/latest/reference/qconnect/\n  - type: SDK\n    url: https://aws.amazon.com/tools/\n  - type: GitHubRepository\n    url: https://github.com/aws/amazon-q-connectjs\n- name: Amazon Q Developer in Chat Applications API\n  description: >-\n    API for Amazon Q Developer in chat applications, which enables integration\n    of Amazon Q Developer capabilities into messaging platforms. It provides\n    descriptions, request parameters, and response formats for interacting with\n    Amazon Q Developer through chat-based interfaces.\n  image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n  humanURL: https://docs.aws.amazon.com/chatbot/latest/APIReference/Welcome.html\n  baseURL: https://chatbot.{region}.amazonaws.com\n  tags:\n  - Chat\n  - Developer Tools\n  - Integration\n  - Messaging\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/chatbot/latest/APIReference/Welcome.html\n  - type: APIReference\n   \
  \ url: https://docs.aws.amazon.com/chatbot/latest/APIReference/Welcome.html\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/q/\n- type: GettingStarted\n  url: https://aws.amazon.com/q/getting-started/\n- type: Documentation\n  url: https://docs.aws.amazon.com/amazonq/\n- type: Blog\n  url: https://aws.amazon.com/blogs/aws/tag/amazon-q/\n- type: FAQ\n  url: https://aws.amazon.com/q/faqs/\n- type: Support\n  url: https://aws.amazon.com/contact-us/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Pricing\n  url: https://aws.amazon.com/q/pricing/\n- type: StatusPage\n  url: https://health.aws.amazon.com/health/status\n- type: SDK\n  url: https://aws.amazon.com/tools/\n- type: Portal\n  url: https://console.aws.amazon.com/\n- type: SignUp\n  url: https://portal.aws.amazon.com/billing/signup\n- type: Community\n  url: https://repost.aws/tags/TALmcXzmfeRaKOzrBowJ9cJQ/amazon-q\n- type: GitHubOrganization\n\
  \  url: https://github.com/aws\n- type: JSON-LD\n  url: json-ld/amazon-q-openapi-application-context.jsonld\n- type: JSON-LD\n  url: json-ld/amazon-q-openapi-conversation-context.jsonld\n- type: JSON-LD\n  url: json-ld/amazon-q-openapi-data-source-context.jsonld\n- type: JSON-LD\n  url: json-ld/amazon-q-openapi-index-context.jsonld\n- type: JSON-LD\n  url: json-ld/amazon-q-openapi-message-context.jsonld\n- type: JSONSchema\n  url: json-schema/amazon-q-openapi-application-schema.json\n- type: JSONSchema\n  url: json-schema/amazon-q-openapi-conversation-schema.json\n- type: JSONSchema\n  url: json-schema/amazon-q-openapi-data-source-schema.json\n- type: JSONSchema\n  url: json-schema/amazon-q-openapi-index-schema.json\n- type: JSONSchema\n  url: json-schema/amazon-q-openapi-message-schema.json\n- type: JSONStructure\n  url: json-structure/amazon-q-openapi-application-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-q-openapi-conversation-structure.json\n- type: JSONStructure\n\
  \  url: json-structure/amazon-q-openapi-data-source-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-q-openapi-index-structure.json\n- type: JSONStructure\n  url: json-structure/amazon-q-openapi-message-structure.json\n- type: Example\n  url: examples/amazon-q-openapi-application-example.json\n- type: Example\n  url: examples/amazon-q-openapi-conversation-example.json\n- type: Example\n  url: examples/amazon-q-openapi-data-source-example.json\n- type: Example\n  url: examples/amazon-q-openapi-index-example.json\n- type: Example\n  url: examples/amazon-q-openapi-message-example.json\n- type: NaftikoCapability\n  url: capabilities/amazon-q.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/amazon-q.yaml\n- type: SpectralRules\n  url: rules/amazon-q-spectral-rules.yml\n- type: Vocabulary\n  url: vocabulary/amazon-q-vocabulary.yaml\n- type: OpenAPI\n  url: openapi/amazon-q-openapi.yml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  x-twitter: apievangelist\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/apis.yml
tags:
- Artificial Intelligence
- Assistant
- AWS
- Enterprise
- Generative AI
url: https://raw.githubusercontent.com/api-evangelist/amazon-q/refs/heads/main/apis.yml
use_cases: []
---
