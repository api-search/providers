---
api_count: 2
apis:
- description: Apollo.io's REST API provides programmatic access to Apollo's B2B data platform with 230M+ verified contacts and 30M+ companies. The API supports people enrichment, organization enrichment, people sea
  name: Apollo REST API
  slug: apollo-rest-api
- description: Apollo Client provides libraries and integrations for connecting to Apollo.io's sales platform from external applications and CRM systems.
  name: Apollo Client
  slug: apollo-client
common:
- title: ''
  type: Documentation
  url: https://docs.apollo.io/
- title: ''
  type: GettingStarted
  url: https://docs.apollo.io/docs
- title: ''
  type: Pricing
  url: https://www.apollo.io/pricing
- title: ''
  type: Blog
  url: https://www.apollo.io/blog
- title: ''
  type: Support
  url: https://www.apollo.io/support
- title: ''
  type: Training
  url: https://academy.apollo.io/
- title: ''
  type: PrivacyPolicy
  url: https://www.apollo.io/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.apollo.io/terms-of-service
- title: ''
  type: Compliance
  url: https://www.apollo.io/security
created: '2026-03-25'
description: Apollo.io is an AI-powered B2B sales intelligence and engagement platform combining a database of 230M+ verified contacts and 30M+ companies with prospecting, outreach, and deal execution tools. The platform helps sales teams build pipeline, qualify inbound leads, enrich data, and close deals faster with AI-powered workflows and conversation intelligence.
features:
- description: AI-powered multichannel outbound campaigns with email deliverability guardrails and workflow automations.
  name: Outbound Prospecting
- description: Anonymous visitor identification, real-time form enrichment, instant routing, and automated follow-ups.
  name: Inbound Lead Qualification
- description: Enrich contact and company records with always-fresh data from 230M+ verified contacts and 30M+ companies.
  name: Data Enrichment
- description: Pre-meeting insights, AI call summaries, pipeline boards, and coaching dashboards.
  name: Deal Execution
- description: AI-powered assistant for automating sales research, writing, and workflow tasks.
  name: AI Assistant
- description: Call recording, AI call summaries, and conversation analytics for sales coaching.
  name: Conversation Intelligence
- description: Browser extension for accessing Apollo data and workflows directly from any website.
  name: Chrome Extension
- description: No-code workflow automation engine for sales process automation.
  name: Workflow Automation
- description: Email deliverability guardrails to protect sender reputation and maximize inbox placement.
  name: Email Deliverability
- description: Integrated meeting scheduling functionality linked to sales workflows.
  name: Meeting Scheduler
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Bi-directional Salesforce CRM integration syncing contacts, accounts, activities, and sequences.
  name: Salesforce
- description: HubSpot CRM integration for syncing contact data and outreach activity.
  name: HubSpot
- description: Gmail integration for email tracking and outreach directly from inbox.
  name: Gmail
- description: Microsoft Outlook integration for email tracking and outreach.
  name: Outlook
- description: LinkedIn integration via Chrome extension for prospecting and data enrichment.
  name: LinkedIn
- description: Zapier integration for connecting Apollo to hundreds of other applications.
  name: Zapier
- description: Slack integration for deal alerts and notifications.
  name: Slack
layout: provider
modified: '2026-04-19'
name: Apollo
skills: []
slug: apollo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apollo\nname: Apollo\ndescription: >-\n  Apollo.io is an AI-powered B2B sales intelligence and engagement platform combining\n  a database of 230M+ verified contacts and 30M+ companies with prospecting, outreach,\n  and deal execution tools. The platform helps sales teams build pipeline, qualify\n  inbound leads, enrich data, and close deals faster with AI-powered workflows and\n  conversation intelligence.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AI\n  - B2B Sales\n  - CRM\n  - Data Enrichment\n  - Lead Generation\n  - Sales Intelligence\n  - Sales Platform\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apollo/refs/heads/main/apis.yml\ncreated: '2026-03-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: apollo:apollo-rest-api\n    name: Apollo REST API\n    description: >-\n      Apollo.io's REST API provides programmatic access to Apollo's B2B data platform\n     \
  \ with 230M+ verified contacts and 30M+ companies. The API supports people enrichment,\n      organization enrichment, people search, organization search, accounts and contacts\n      management, deals, sequences, tasks, analytics reporting, and calls management.\n      Authentication via API keys (direct access) or OAuth 2.0 (partner integrations).\n    humanURL: https://www.apollo.io/\n    tags:\n      - Analytics\n      - CRM\n      - Data Enrichment\n      - Organization Search\n      - People Search\n      - REST\n      - Sales Intelligence\n      - Sequences\n    properties:\n      - type: Documentation\n        url: https://docs.apollo.io/\n      - type: GettingStarted\n        url: https://docs.apollo.io/docs\n      - type: APIReference\n        url: https://docs.apollo.io/reference\n      - type: Authentication\n        url: https://docs.apollo.io/reference/authentication\n      - type: RateLimits\n        url: https://docs.apollo.io/reference/rate-limits\n      - type: Tutorials\n\
  \        url: https://docs.apollo.io/docs/overview-apollo-api-tutorials\n  - aid: apollo:apollo-client\n    name: Apollo Client\n    description: >-\n      Apollo Client provides libraries and integrations for connecting to Apollo.io's\n      sales platform from external applications and CRM systems.\n    humanURL: https://www.apollo.io/integrations\n    tags:\n      - CRM\n      - Integrations\n      - Salesforce\n      - SDKs\n    properties:\n      - type: Documentation\n        url: https://www.apollo.io/integrations\ncommon:\n  - type: Documentation\n    url: https://docs.apollo.io/\n  - type: GettingStarted\n    url: https://docs.apollo.io/docs\n  - type: Pricing\n    url: https://www.apollo.io/pricing\n  - type: Blog\n    url: https://www.apollo.io/blog\n  - type: Support\n    url: https://www.apollo.io/support\n  - type: Training\n    url: https://academy.apollo.io/\n  - type: PrivacyPolicy\n    url: https://www.apollo.io/privacy-policy\n  - type: TermsOfService\n    url: https://www.apollo.io/terms-of-service\n\
  \  - type: Compliance\n    url: https://www.apollo.io/security\n  - type: Features\n    data:\n      - name: Outbound Prospecting\n        description: AI-powered multichannel outbound campaigns with email deliverability guardrails and workflow automations.\n      - name: Inbound Lead Qualification\n        description: Anonymous visitor identification, real-time form enrichment, instant routing, and automated follow-ups.\n      - name: Data Enrichment\n        description: Enrich contact and company records with always-fresh data from 230M+ verified contacts and 30M+ companies.\n      - name: Deal Execution\n        description: Pre-meeting insights, AI call summaries, pipeline boards, and coaching dashboards.\n      - name: AI Assistant\n        description: AI-powered assistant for automating sales research, writing, and workflow tasks.\n      - name: Conversation Intelligence\n        description: Call recording, AI call summaries, and conversation analytics for sales coaching.\n \
  \     - name: Chrome Extension\n        description: Browser extension for accessing Apollo data and workflows directly from any website.\n      - name: Workflow Automation\n        description: No-code workflow automation engine for sales process automation.\n      - name: Email Deliverability\n        description: Email deliverability guardrails to protect sender reputation and maximize inbox placement.\n      - name: Meeting Scheduler\n        description: Integrated meeting scheduling functionality linked to sales workflows.\n  - type: UseCases\n    data:\n      - name: Outbound Sales Prospecting\n        description: Find and engage ideal prospects at scale using Apollo's contact database and multichannel outreach.\n      - name: Inbound Lead Management\n        description: Automatically qualify, route, and follow up on inbound leads in real time.\n      - name: CRM Data Enrichment\n        description: Enrich Salesforce, HubSpot, and other CRM records with verified contact and company\
  \ data.\n      - name: Sales Pipeline Building\n        description: Build and manage sales pipeline with AI-assisted prospecting and deal execution tools.\n      - name: Partner API Integration\n        description: Build third-party integrations using OAuth 2.0 to access Apollo data on behalf of customers.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: Bi-directional Salesforce CRM integration syncing contacts, accounts, activities, and sequences.\n      - name: HubSpot\n        description: HubSpot CRM integration for syncing contact data and outreach activity.\n      - name: Gmail\n        description: Gmail integration for email tracking and outreach directly from inbox.\n      - name: Outlook\n        description: Microsoft Outlook integration for email tracking and outreach.\n      - name: LinkedIn\n        description: LinkedIn integration via Chrome extension for prospecting and data enrichment.\n      - name: Zapier\n        description: Zapier\
  \ integration for connecting Apollo to hundreds of other applications.\n      - name: Slack\n        description: Slack integration for deal alerts and notifications.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apollo/refs/heads/main/apis.yml
tags:
- AI
- B2B Sales
- CRM
- Data Enrichment
- Lead Generation
- Sales Intelligence
- Sales Platform
url: https://raw.githubusercontent.com/api-evangelist/apollo/refs/heads/main/apis.yml
use_cases:
- description: Find and engage ideal prospects at scale using Apollo's contact database and multichannel outreach.
  name: Outbound Sales Prospecting
- description: Automatically qualify, route, and follow up on inbound leads in real time.
  name: Inbound Lead Management
- description: Enrich Salesforce, HubSpot, and other CRM records with verified contact and company data.
  name: CRM Data Enrichment
- description: Build and manage sales pipeline with AI-assisted prospecting and deal execution tools.
  name: Sales Pipeline Building
- description: Build third-party integrations using OAuth 2.0 to access Apollo data on behalf of customers.
  name: Partner API Integration
---
