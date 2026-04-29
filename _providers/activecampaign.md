---
api_count: 2
api_specs:
- filename: activecampaign-v3.json
  format: json
  label: ActiveCampaign API v3
  slug: activecampaign-v3
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/activecampaign/refs/heads/main/openapi/activecampaign-v3.json
- filename: activecampaign-sms.json
  format: json
  label: ActiveCampaign SMS Broadcast API
  slug: activecampaign-sms
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/activecampaign/refs/heads/main/openapi/activecampaign-sms.json
apis:
- description: 'The primary REST API for ActiveCampaign, organized around resources such as contacts, deals, accounts, automations, campaigns, messages, lists, tags, webhooks, custom objects, and ecommerce entities. '
  name: ActiveCampaign API v3
  slug: activecampaign-v3
- description: API for managing SMS broadcasts, lists, metrics, and AI-powered content generation in ActiveCampaign. Supports creating, scheduling, and tracking SMS broadcast campaigns.
  name: ActiveCampaign SMS Broadcast API
  slug: activecampaign-sms
capabilities:
- description: Workflow capability for CRM and sales pipeline management including deals, accounts, tasks, and pipeline stages. Used by sales teams and revenue operations to track and advance deals.
  name: ActiveCampaign CRM and Sales
  slug: crm-sales
- description: 'Unified workflow capability for marketing automation, contact management, campaign execution, and list segmentation. Used by marketing teams and growth engineers to orchestrate multi-channel customer '
  name: ActiveCampaign Marketing Automation
  slug: marketing-automation
common:
- title: ''
  type: Portal
  url: https://developers.activecampaign.com/
- title: ''
  type: GettingStarted
  url: https://help.activecampaign.com/hc/en-us/articles/207317590-Getting-started-with-the-API
- title: ''
  type: Authentication
  url: https://developers.activecampaign.com/reference/authentication
- title: ''
  type: Pricing
  url: https://www.activecampaign.com/pricing
- title: ''
  type: Blog
  url: https://www.activecampaign.com/blog
- title: ''
  type: FAQ
  url: https://www.activecampaign.com/about/faq
- title: ''
  type: Forums
  url: https://community.activecampaign.com/latest
- title: ''
  type: StatusPage
  url: https://status.activecampaign.com/
- title: ''
  type: PostmanWorkspace
  url: https://www.postman.com/acdevrel/activecampaign-developer-relations/overview
- title: ''
  type: GitHubOrganization
  url: https://github.com/ActiveCampaign
- title: PHP SDK
  type: SDK
  url: https://github.com/ActiveCampaign/activecampaign-api-php
- title: Node.js SDK
  type: SDK
  url: https://github.com/ActiveCampaign/activecampaign-api-nodejs
- title: ''
  type: SpectralRules
  url: rules/activecampaign-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/activecampaign-vocabulary.yaml
- title: ActiveCampaign API v3 Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/activecampaign-v3.yaml
- title: Marketing Automation Workflow
  type: NaftikoCapability
  url: capabilities/marketing-automation.yaml
- title: CRM and Sales Workflow
  type: NaftikoCapability
  url: capabilities/crm-sales.yaml
- title: SMS API Context
  type: JSON-LD
  url: json-ld/activecampaign-sms-context.jsonld
created: '2025-02-17'
description: ActiveCampaign is a leading marketing automation platform that helps businesses of all sizes seamlessly engage with their customers. With its user-friendly interface and powerful features, ActiveCampaign allows businesses to create personalized email campaigns, automate workflows, and track customer interactions in real-time. The platform offers a REST API (v3), SMS Broadcast API, webhooks, and custom object schemas for building deep integrations and automations.
features:
- description: Create and send conversion-focused email campaigns with personalization and segmentation.
  name: Email Marketing
- description: Build automated customer journeys and workflows triggered by contact behavior and events.
  name: Marketing Automation
- description: Built-in sales CRM for managing deals, pipelines, tasks, and customer relationships.
  name: CRM
- description: Reach contacts via SMS broadcast campaigns with AI-powered content generation.
  name: SMS Marketing
- description: Automate growth and customer engagement through WhatsApp communications.
  name: WhatsApp Messaging
- description: Automate transactional alerts, password resets, and notifications via Postmark integration.
  name: Transactional Email
- description: Create custom data schemas to activate complex data for segmentation and personalized automation.
  name: Custom Objects
- description: Track contact behaviors and activities across web properties and integrations.
  name: Contact Event Tracking
- description: Receive real-time event notifications for contact, campaign, automation, and custom object activities.
  name: Webhooks
- description: Deploy conversion-ready landing pages for lead capture and campaigns.
  name: Landing Pages
- description: AI-powered orchestration and autonomous marketing agents for campaign suggestions and personalization.
  name: Active Intelligence
- description: Connect AI applications to ActiveCampaign using the Model Context Protocol server.
  name: MCP Server
image: /assets/icons/activecampaign.png
integrations:
- description: Sync contact and deal data between ActiveCampaign and Salesforce CRM.
  name: Salesforce
- description: Connect ActiveCampaign to 1000+ apps via Zapier automation workflows.
  name: Zapier
- description: Send notifications and trigger automations from Slack using OAuth2 integration.
  name: Slack
- description: Sync scheduling data and trigger automations with custom objects via OAuth2.
  name: Calendly
- description: Integrate SMS workflows using Twilio with Basic Auth for outbound messaging.
  name: Twilio
- description: Sync ecommerce customers, orders, and products for automated campaigns.
  name: Shopify
- description: Embed forms and capture leads from WordPress sites.
  name: WordPress
- description: Connect Wix websites for lead capture and customer journey automation.
  name: Wix
jsonld:
- class_count: 18
  name: Activecampaign Sms Context
  property_count: 51
  slug: activecampaign-sms-context
layout: provider
modified: '2026-04-19'
name: ActiveCampaign
rules:
- name: ActiveCampaign API Rules
  rule_count: 26
  severity_counts:
    error: 12
    hint: 0
    info: 2
    warn: 12
  slug: activecampaign-spectral-rules
skills: []
slug: activecampaign
solutions:
- description: Entry-level plan with marketing automation, up to 5 automation actions, and 1 user.
  name: Starter
- description: Mid-tier plan with unlimited automation actions, landing pages, and standard segmentation.
  name: Plus
- description: Advanced plan with predictive content, advanced segmentation, and 3 users.
  name: Pro
- description: Full-featured plan with custom objects, dedicated account team, and premium segmentation.
  name: Enterprise
source_filename: apis.yml
source_yaml: "aid: activecampaign\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/activecampaign/refs/heads/main/apis.yml\napis:\n  - aid: activecampaign:activecampaign-v3\n    name: ActiveCampaign API v3\n    tags:\n      - Marketing Automation\n      - CRM\n      - Email Marketing\n      - Contacts\n      - Deals\n    humanURL: https://developers.activecampaign.com/reference/overview\n    baseURL: https://youraccountname.api-us1.com/api/3\n    properties:\n      - url: https://developers.activecampaign.com/reference/overview\n        type: Documentation\n      - url: https://developers.activecampaign.com/reference/authentication\n        type: Authentication\n      - url: openapi/activecampaign-v3.json\n        type: OpenAPI\n    description: >-\n      The primary REST API for ActiveCampaign, organized around resources such as\n      contacts, deals, accounts, automations, campaigns, messages, lists, tags, webhooks,\n      custom objects, and ecommerce entities. Uses API key\
  \ header authentication.\n  - aid: activecampaign:activecampaign-sms\n    name: ActiveCampaign SMS Broadcast API\n    tags:\n      - SMS\n      - Marketing Automation\n      - Messaging\n    humanURL: https://developers.activecampaign.com/reference/overview\n    baseURL: https://youraccountname.api-us1.com/api/3\n    properties:\n      - url: https://developers.activecampaign.com/reference/overview\n        type: Documentation\n      - url: openapi/activecampaign-sms.json\n        type: OpenAPI\n      - url: json-schema/activecampaign-sms-broadcast-message-schema.json\n        type: JSONSchema\n        title: Broadcast Message\n      - url: json-schema/activecampaign-sms-broadcast-create-request-schema.json\n        type: JSONSchema\n        title: Broadcast Create Request\n      - url: json-schema/activecampaign-sms-broadcast-update-request-schema.json\n        type: JSONSchema\n        title: Broadcast Update Request\n      - url: json-schema/activecampaign-sms-broadcast-metrics-schema.json\n\
  \        type: JSONSchema\n        title: Broadcast Metrics\n      - url: json-schema/activecampaign-sms-recipient-schema.json\n        type: JSONSchema\n        title: Recipient\n      - url: json-schema/activecampaign-sms-credits-response-schema.json\n        type: JSONSchema\n        title: Credits Response\n      - url: json-schema/activecampaign-sms-ai-broadcast-request-schema.json\n        type: JSONSchema\n        title: AI Broadcast Request\n      - url: json-structure/activecampaign-sms-broadcast-message-structure.json\n        type: JSONStructure\n        title: Broadcast Message\n      - url: json-structure/activecampaign-sms-recipient-structure.json\n        type: JSONStructure\n        title: Recipient\n      - url: examples/activecampaign-sms-broadcast-message-example.json\n        type: Example\n        title: Broadcast Message Example\n      - url: examples/activecampaign-sms-recipient-example.json\n        type: Example\n        title: Recipient Example\n    description:\
  \ >-\n      API for managing SMS broadcasts, lists, metrics, and AI-powered content generation\n      in ActiveCampaign. Supports creating, scheduling, and tracking SMS broadcast campaigns.\nname: ActiveCampaign\ntags:\n  - Marketing Automation\n  - Email Marketing\n  - CRM\n  - Sales Automation\n  - Customer Experience\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://developers.activecampaign.com/\n    type: Portal\n  - url: https://help.activecampaign.com/hc/en-us/articles/207317590-Getting-started-with-the-API\n    type: GettingStarted\n  - url: https://developers.activecampaign.com/reference/authentication\n    type: Authentication\n  - url: https://www.activecampaign.com/pricing\n    type: Pricing\n  - url: https://www.activecampaign.com/blog\n    type: Blog\n  - url: https://www.activecampaign.com/about/faq\n    type: FAQ\n  - url: https://community.activecampaign.com/latest\n    type: Forums\n\
  \  - url: https://status.activecampaign.com/\n    type: StatusPage\n  - url: https://www.postman.com/acdevrel/activecampaign-developer-relations/overview\n    type: PostmanWorkspace\n  - url: https://github.com/ActiveCampaign\n    type: GitHubOrganization\n  - url: https://github.com/ActiveCampaign/activecampaign-api-php\n    type: SDK\n    title: PHP SDK\n  - url: https://github.com/ActiveCampaign/activecampaign-api-nodejs\n    type: SDK\n    title: Node.js SDK\n  - url: rules/activecampaign-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/activecampaign-vocabulary.yaml\n    type: Vocabulary\n  - url: capabilities/shared/activecampaign-v3.yaml\n    type: NaftikoCapability\n    title: ActiveCampaign API v3 Shared Definition\n  - url: capabilities/marketing-automation.yaml\n    type: NaftikoCapability\n    title: Marketing Automation Workflow\n  - url: capabilities/crm-sales.yaml\n    type: NaftikoCapability\n    title: CRM and Sales Workflow\n  - url: json-ld/activecampaign-sms-context.jsonld\n\
  \    type: JSON-LD\n    title: SMS API Context\n  - type: Features\n    data:\n      - name: Email Marketing\n        description: Create and send conversion-focused email campaigns with personalization and segmentation.\n      - name: Marketing Automation\n        description: Build automated customer journeys and workflows triggered by contact behavior and events.\n      - name: CRM\n        description: Built-in sales CRM for managing deals, pipelines, tasks, and customer relationships.\n      - name: SMS Marketing\n        description: Reach contacts via SMS broadcast campaigns with AI-powered content generation.\n      - name: WhatsApp Messaging\n        description: Automate growth and customer engagement through WhatsApp communications.\n      - name: Transactional Email\n        description: Automate transactional alerts, password resets, and notifications via Postmark integration.\n      - name: Custom Objects\n        description: Create custom data schemas to activate complex\
  \ data for segmentation and personalized automation.\n      - name: Contact Event Tracking\n        description: Track contact behaviors and activities across web properties and integrations.\n      - name: Webhooks\n        description: Receive real-time event notifications for contact, campaign, automation, and custom object activities.\n      - name: Landing Pages\n        description: Deploy conversion-ready landing pages for lead capture and campaigns.\n      - name: Active Intelligence\n        description: AI-powered orchestration and autonomous marketing agents for campaign suggestions and personalization.\n      - name: MCP Server\n        description: Connect AI applications to ActiveCampaign using the Model Context Protocol server.\n  - type: UseCases\n    data:\n      - name: Lead Nurturing\n        description: Automate email sequences to nurture leads through the sales funnel based on behavior.\n      - name: E-Commerce Automation\n        description: Trigger post-purchase\
  \ emails, abandoned cart recovery, and personalized product recommendations.\n      - name: Customer Onboarding\n        description: Automate onboarding sequences for SaaS products to improve activation and retention.\n      - name: Contact Segmentation\n        description: Segment contacts using tags, custom fields, and custom objects for targeted campaigns.\n      - name: Sales Pipeline Management\n        description: Manage deals, tasks, and pipeline stages with CRM and automation integration.\n      - name: SMS Broadcast Campaigns\n        description: Send targeted SMS campaigns to subscriber lists with engagement tracking.\n      - name: Webhook-Driven Integrations\n        description: Build real-time integrations using webhooks for contact and campaign activity events.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: Sync contact and deal data between ActiveCampaign and Salesforce CRM.\n      - name: Zapier\n        description: Connect ActiveCampaign\
  \ to 1000+ apps via Zapier automation workflows.\n      - name: Slack\n        description: Send notifications and trigger automations from Slack using OAuth2 integration.\n      - name: Calendly\n        description: Sync scheduling data and trigger automations with custom objects via OAuth2.\n      - name: Twilio\n        description: Integrate SMS workflows using Twilio with Basic Auth for outbound messaging.\n      - name: Shopify\n        description: Sync ecommerce customers, orders, and products for automated campaigns.\n      - name: WordPress\n        description: Embed forms and capture leads from WordPress sites.\n      - name: Wix\n        description: Connect Wix websites for lead capture and customer journey automation.\n  - type: Solutions\n    data:\n      - name: Starter\n        description: Entry-level plan with marketing automation, up to 5 automation actions, and 1 user.\n      - name: Plus\n        description: Mid-tier plan with unlimited automation actions, landing\
  \ pages, and standard segmentation.\n      - name: Pro\n        description: Advanced plan with predictive content, advanced segmentation, and 3 users.\n      - name: Enterprise\n        description: Full-featured plan with custom objects, dedicated account team, and premium segmentation.\ncreated: '2025-02-17'\nmodified: '2026-04-19'\nposition: Consumer\ndescription: >-\n  ActiveCampaign is a leading marketing automation platform that helps businesses\n  of all sizes seamlessly engage with their customers. With its user-friendly interface\n  and powerful features, ActiveCampaign allows businesses to create personalized email\n  campaigns, automate workflows, and track customer interactions in real-time. The platform\n  offers a REST API (v3), SMS Broadcast API, webhooks, and custom object schemas for\n  building deep integrations and automations.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/activecampaign/refs/heads/main/apis.yml
tags:
- Marketing Automation
- Email Marketing
- CRM
- Sales Automation
- Customer Experience
url: https://raw.githubusercontent.com/api-evangelist/activecampaign/refs/heads/main/apis.yml
use_cases:
- description: Automate email sequences to nurture leads through the sales funnel based on behavior.
  name: Lead Nurturing
- description: Trigger post-purchase emails, abandoned cart recovery, and personalized product recommendations.
  name: E-Commerce Automation
- description: Automate onboarding sequences for SaaS products to improve activation and retention.
  name: Customer Onboarding
- description: Segment contacts using tags, custom fields, and custom objects for targeted campaigns.
  name: Contact Segmentation
- description: Manage deals, tasks, and pipeline stages with CRM and automation integration.
  name: Sales Pipeline Management
- description: Send targeted SMS campaigns to subscriber lists with engagement tracking.
  name: SMS Broadcast Campaigns
- description: Build real-time integrations using webhooks for contact and campaign activity events.
  name: Webhook-Driven Integrations
---
