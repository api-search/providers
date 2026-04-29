---
api_count: 1
api_specs:
- filename: zoominfo-openapi.yml
  format: yaml
  label: ZoomInfo
  slug: zoominfo
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zoominfo/refs/heads/main/openapi/zoominfo-openapi.yml
apis:
- description: The ZoomInfo API is a set of HTTPS endpoints you can use to programmatically retrieve and integrate ZoomInfo data into your existing technology stack and ...
  name: ZoomInfo
  slug: zoominfo
capabilities:
- description: 'Unified capability for B2B data enrichment workflows combining contact, company, org chart, corporate hierarchy, location, technology, intent, and IP enrichment. Used by sales ops, marketing ops, and '
  name: ZoomInfo Data Enrichment
  slug: data-enrichment
- description: Unified capability for monitoring and compliance workflows combining webhook management, API usage tracking, and compliance operations. Used by platform admins and data governance teams to manage data
  name: ZoomInfo Monitoring And Compliance
  slug: monitoring-and-compliance
- description: Unified capability for B2B prospecting workflows combining contact search, company search, intent signals, news, and scoops. Used by sales development reps and account executives to identify and prior
  name: ZoomInfo Prospecting And Search
  slug: prospecting-and-search
- description: Workflow for sales teams to find, qualify, and enrich prospect data. Combines contact search, company search, intent signals, and enrichment for targeted outreach.
  name: ZoomInfo Sales Prospecting
  slug: sales-prospecting
common:
- title: ''
  type: Pricing
  url: https://www.zoominfo.com/pricing
- title: ''
  type: Blog
  url: https://pipeline.zoominfo.com/
- title: ''
  type: Customers
  url: https://www.zoominfo.com/about/case-studies
- title: ''
  type: Partners
  url: https://www.zoominfo.com/partner
- title: ''
  type: Support
  url: https://www.zoominfo.com/about/help-center
- title: ''
  type: FAQ
  url: https://www.zoominfo.com/faqs/business
- title: ''
  type: Glossary
  url: https://pipeline.zoominfo.com/glossary
- title: ''
  type: Authentication
  url: https://api-docs.zoominfo.com/#authentication
- title: ''
  type: GettingStarted
  url: https://api-docs.zoominfo.com/getting-started
- title: ''
  type: RateLimits
  url: https://api-docs.zoominfo.com/rate-limits
- title: ''
  type: TermsOfService
  url: https://www.zoominfo.com/about/terms-of-service
- title: ''
  type: PrivacyPolicy
  url: https://www.zoominfo.com/about/privacy-policy
- title: ''
  type: StatusPage
  url: https://status.zoominfo.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/Zoominfo
- title: ''
  type: DeveloperPortal
  url: https://api-docs.zoominfo.com
- title: ''
  type: APIReference
  url: https://api-docs.zoominfo.com
- title: MCP Server
  type: Hub
  url: https://github.com/Zoominfo/zoominfo-mcp-plugin
- title: ''
  type: SpectralRules
  url: rules/zoominfo-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/zoominfo-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/data-enrichment.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/sales-prospecting.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/shared/zoominfo-api.yaml
created: '2025-02-09'
description: ZoomInfo is a leading B2B contact database and sales intelligence platform that provides detailed company and contact information, helping sales and marketing teams identify and connect with potential customers.
features:
- description: Search for contacts by job title, company, location, industry, and other criteria
  name: Contact Search
- description: Search for companies by industry, revenue, employee count, location, and technology stack
  name: Company Search
- description: Enrich contact records with verified email addresses, phone numbers, and professional details
  name: Contact Enrichment
- description: Enrich company records with firmographic data including revenue, employee count, and technographics
  name: Company Enrichment
- description: Identify companies showing buying intent signals based on content consumption patterns
  name: Intent Data
- description: Access business intelligence scoops about company changes, hiring, and strategic initiatives
  name: Scoops
- description: Search and enrich news articles related to companies and contacts
  name: News Intelligence
- description: Identify technologies used by companies across their tech stack
  name: Technology Tracking
- description: Map organizational structures including parent companies, subsidiaries, and divisions
  name: Corporate Hierarchy
- description: Access organizational chart data showing reporting relationships within companies
  name: Org Chart
- description: Real-time notifications for data changes and updates via webhook subscriptions
  name: Webhooks
- description: Submit batch search and enrichment jobs for large-scale data processing
  name: Bulk Operations
- description: Identify website visitors by IP address and enrich with company information
  name: WebSights
- description: Access compliance data to support GDPR and privacy regulation requirements
  name: Compliance
image: https://www.zoominfo.com/assets/img/zoominfo-logo.png
integrations:
- description: Native integration to enrich and sync contact and company data with Salesforce CRM
  name: Salesforce
- description: Seamless integration to push enriched data into HubSpot CRM and marketing automation
  name: HubSpot
- description: Integration to enrich records and sync data with Microsoft Dynamics CRM
  name: Microsoft Dynamics 365
- description: Marketing automation integration for lead enrichment and scoring with Marketo
  name: Marketo
- description: Sales engagement platform integration for enriched prospect data in Outreach sequences
  name: Outreach
- description: Integration to power Salesloft cadences with verified contact information
  name: Salesloft
- description: Notifications and alerts for intent signals and data updates delivered to Slack channels
  name: Slack
- description: Data sharing integration to access ZoomInfo data directly in Snowflake data warehouse
  name: Snowflake
- description: Audience targeting integration to reach ideal prospects with Google advertising campaigns
  name: Google Ads
- description: Integration to match and enrich LinkedIn profile data with ZoomInfo intelligence
  name: LinkedIn
jsonld:
- class_count: 0
  name: Zoominfo Context
  property_count: 278
  slug: zoominfo-context
layout: provider
modified: '2026-04-18'
name: ZoomInfo
rules:
- name: ZoomInfo API Rules
  rule_count: 21
  severity_counts:
    error: 19
    hint: 0
    info: 1
    warn: 1
  slug: zoominfo-spectral-rules
skills: []
slug: zoominfo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zoominfo\nurl: https://raw.githubusercontent.com/api-evangelist/zoominfo/refs/heads/main/apis.yml\napis:\n- aid: zoominfo:zoominfo\n  name: ZoomInfo\n  tags:\n  - Authentication\n  - Contact Search\n  - Company Search\n  - Contact Enrich\n  - Company Enrich\n  - Intent Search\n  - News Search\n  - Scoop Search\n  - Technology Enrich\n  - Webhooks\n  - Bulk Operations\n  - WebSights\n  - Compliance\n  - Lookup\n  - Corporate Hierarchy\n  - Org Chart\n  humanURL: https://www.zoominfo.com/\n  properties:\n  - url: https://www.zoominfo.com/solutions/data-as-a-service/enterprise-api\n    type: Documentation\n  - type: OpenAPI\n    url: openapi/zoominfo-openapi.yml\n  - type: SDK\n    url: https://github.com/Zoominfo/api-auth-python-client\n    title: Python SDK\n  - type: SDK\n    url: https://github.com/Zoominfo/api-auth-java-client\n    title: Java SDK\n  - type: SDK\n    url: https://github.com/Zoominfo/api-auth-nodejs-client\n    title: Node.js SDK\n  - type: SDK\n    url:\
  \ https://github.com/Zoominfo/api-auth-csharp-client\n    title: C# SDK\n  - type: JSONSchema\n    url: json-schema/zoominfo-address-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-authenticate-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-bulk-company-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-bulk-company-search-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-bulk-contact-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-bulk-contact-search-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-bulk-job-results-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-bulk-job-status-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-company-enrich-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-company-enrich-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-company-enrich-request-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/zoominfo-company-funding-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-company-master-data-enrich-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-company-master-data-enrich-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-company-master-data-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-company-search-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-company-search-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-competitor-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-compliance-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-contact-enrich-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-contact-enrich-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-contact-enrich-request-schema.json\n  - type: JSONSchema\n    url:\
  \ json-schema/zoominfo-contact-search-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-contact-search-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-contact-search-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-corporate-hierarchy-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-create-webhook-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-description-list-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-education-degree-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-education-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-employment-history-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-external-url-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-family-tree-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-get-company-ranking-schema.json\n  - type: JSONSchema\n\
  \    url: json-schema/zoominfo-get-company-search-output-field-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-get-corporate-hierarchy-enrich-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-get-corporate-hierarchy-enrich-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-get-hashtag-enrich-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-get-location-enrich-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-get-technology-enrich-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-hashtag-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-hashtags-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-i-p-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-intent-enrich-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-intent-enrich-output-schema.json\n  - type: JSONSchema\n    url:\
  \ json-schema/zoominfo-intent-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-intent-search-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-intent-search-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-intent-search-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-intent-topic-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-location-enrich-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-location-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-location-match-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-match-company-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-match-person-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-match-reason-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-naics-code-schema.json\n  - type: JSONSchema\n   \
  \ url: json-schema/zoominfo-news-enrich-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-news-enrich-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-news-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-news-search-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-news-search-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-news-search-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-org-chart-enrich-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-org-chart-enrich-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-org-chart-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-recommended-contact-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-scoop-enrich-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-scoop-enrich-output-schema.json\n\
  \  - type: JSONSchema\n    url: json-schema/zoominfo-scoop-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-scoop-search-input-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-scoop-search-output-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-scoop-search-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-sic-code-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-social-media-url-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-sub-unit-type-info-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-subscription-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-tech-attribute-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-technology-enrich-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-type-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-update-webhook-request-schema.json\n  - type: JSONSchema\n\
  \    url: json-schema/zoominfo-usage-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-validate-target-u-r-l-request-schema.json\n  - type: JSONSchema\n    url: json-schema/zoominfo-webhook-schema.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-address-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-authenticate-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-bulk-company-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-bulk-company-search-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-bulk-contact-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-bulk-contact-search-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-bulk-job-results-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-bulk-job-status-request-structure.json\n\
  \  - type: JSONStructure\n    url: json-structure/zoominfo-company-enrich-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-company-enrich-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-company-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-company-funding-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-company-master-data-enrich-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-company-master-data-enrich-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-company-master-data-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-company-search-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-company-search-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-competitor-structure.json\n  - type: JSONStructure\n\
  \    url: json-structure/zoominfo-compliance-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-contact-enrich-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-contact-enrich-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-contact-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-contact-search-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-contact-search-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-contact-search-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-corporate-hierarchy-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-create-webhook-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-description-list-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-education-degree-structure.json\n\
  \  - type: JSONStructure\n    url: json-structure/zoominfo-education-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-employment-history-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-external-url-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-family-tree-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-get-company-ranking-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-get-company-search-output-field-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-get-corporate-hierarchy-enrich-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-get-corporate-hierarchy-enrich-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-get-hashtag-enrich-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-get-location-enrich-input-structure.json\n  - type: JSONStructure\n \
  \   url: json-structure/zoominfo-get-technology-enrich-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-hashtag-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-hashtags-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-i-p-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-intent-enrich-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-intent-enrich-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-intent-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-intent-search-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-intent-search-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-intent-search-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-intent-topic-structure.json\n\
  \  - type: JSONStructure\n    url: json-structure/zoominfo-location-enrich-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-location-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-location-match-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-match-company-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-match-person-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-match-reason-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-naics-code-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-news-enrich-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-news-enrich-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-news-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-news-search-input-structure.json\n\
  \  - type: JSONStructure\n    url: json-structure/zoominfo-news-search-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-news-search-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-org-chart-enrich-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-org-chart-enrich-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-org-chart-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-recommended-contact-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-scoop-enrich-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-scoop-enrich-output-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-scoop-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-scoop-search-input-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-scoop-search-output-structure.json\n\
  \  - type: JSONStructure\n    url: json-structure/zoominfo-scoop-search-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-sic-code-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-social-media-url-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-sub-unit-type-info-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-subscription-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-tech-attribute-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-technology-enrich-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-type-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-update-webhook-request-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-usage-structure.json\n  - type: JSONStructure\n    url: json-structure/zoominfo-validate-target-u-r-l-request-structure.json\n\
  \  - type: JSONStructure\n    url: json-structure/zoominfo-webhook-structure.json\n  - type: JSONLD\n    url: json-ld/zoominfo-context.jsonld\n  - type: Example\n    url: examples/zoominfo-address-example.json\n  - type: Example\n    url: examples/zoominfo-authenticate-request-example.json\n  - type: Example\n    url: examples/zoominfo-bulk-company-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-bulk-company-search-request-example.json\n  - type: Example\n    url: examples/zoominfo-bulk-contact-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-bulk-contact-search-request-example.json\n  - type: Example\n    url: examples/zoominfo-bulk-job-results-request-example.json\n  - type: Example\n    url: examples/zoominfo-bulk-job-status-request-example.json\n  - type: Example\n    url: examples/zoominfo-company-enrich-input-example.json\n  - type: Example\n    url: examples/zoominfo-company-enrich-output-example.json\n  - type: Example\n    url:\
  \ examples/zoominfo-company-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-company-funding-example.json\n  - type: Example\n    url: examples/zoominfo-company-master-data-enrich-input-example.json\n  - type: Example\n    url: examples/zoominfo-company-master-data-enrich-output-example.json\n  - type: Example\n    url: examples/zoominfo-company-master-data-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-company-search-input-example.json\n  - type: Example\n    url: examples/zoominfo-company-search-request-example.json\n  - type: Example\n    url: examples/zoominfo-competitor-example.json\n  - type: Example\n    url: examples/zoominfo-compliance-output-example.json\n  - type: Example\n    url: examples/zoominfo-contact-enrich-input-example.json\n  - type: Example\n    url: examples/zoominfo-contact-enrich-output-example.json\n  - type: Example\n    url: examples/zoominfo-contact-enrich-request-example.json\n  - type: Example\n    url:\
  \ examples/zoominfo-contact-search-input-example.json\n  - type: Example\n    url: examples/zoominfo-contact-search-output-example.json\n  - type: Example\n    url: examples/zoominfo-contact-search-request-example.json\n  - type: Example\n    url: examples/zoominfo-corporate-hierarchy-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-create-webhook-request-example.json\n  - type: Example\n    url: examples/zoominfo-description-list-example.json\n  - type: Example\n    url: examples/zoominfo-education-degree-example.json\n  - type: Example\n    url: examples/zoominfo-education-example.json\n  - type: Example\n    url: examples/zoominfo-employment-history-example.json\n  - type: Example\n    url: examples/zoominfo-external-url-example.json\n  - type: Example\n    url: examples/zoominfo-family-tree-example.json\n  - type: Example\n    url: examples/zoominfo-get-company-ranking-example.json\n  - type: Example\n    url: examples/zoominfo-get-company-search-output-field-example.json\n\
  \  - type: Example\n    url: examples/zoominfo-get-corporate-hierarchy-enrich-input-example.json\n  - type: Example\n    url: examples/zoominfo-get-corporate-hierarchy-enrich-output-example.json\n  - type: Example\n    url: examples/zoominfo-get-hashtag-enrich-input-example.json\n  - type: Example\n    url: examples/zoominfo-get-location-enrich-input-example.json\n  - type: Example\n    url: examples/zoominfo-get-technology-enrich-input-example.json\n  - type: Example\n    url: examples/zoominfo-hashtag-example.json\n  - type: Example\n    url: examples/zoominfo-hashtags-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-i-p-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-intent-enrich-input-example.json\n  - type: Example\n    url: examples/zoominfo-intent-enrich-output-example.json\n  - type: Example\n    url: examples/zoominfo-intent-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-intent-search-input-example.json\n\
  \  - type: Example\n    url: examples/zoominfo-intent-search-output-example.json\n  - type: Example\n    url: examples/zoominfo-intent-search-request-example.json\n  - type: Example\n    url: examples/zoominfo-intent-topic-example.json\n  - type: Example\n    url: examples/zoominfo-location-enrich-output-example.json\n  - type: Example\n    url: examples/zoominfo-location-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-location-match-example.json\n  - type: Example\n    url: examples/zoominfo-match-company-input-example.json\n  - type: Example\n    url: examples/zoominfo-match-person-input-example.json\n  - type: Example\n    url: examples/zoominfo-match-reason-example.json\n  - type: Example\n    url: examples/zoominfo-naics-code-example.json\n  - type: Example\n    url: examples/zoominfo-news-enrich-input-example.json\n  - type: Example\n    url: examples/zoominfo-news-enrich-output-example.json\n  - type: Example\n    url: examples/zoominfo-news-enrich-request-example.json\n\
  \  - type: Example\n    url: examples/zoominfo-news-search-input-example.json\n  - type: Example\n    url: examples/zoominfo-news-search-output-example.json\n  - type: Example\n    url: examples/zoominfo-news-search-request-example.json\n  - type: Example\n    url: examples/zoominfo-org-chart-enrich-input-example.json\n  - type: Example\n    url: examples/zoominfo-org-chart-enrich-output-example.json\n  - type: Example\n    url: examples/zoominfo-org-chart-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-recommended-contact-example.json\n  - type: Example\n    url: examples/zoominfo-scoop-enrich-input-example.json\n  - type: Example\n    url: examples/zoominfo-scoop-enrich-output-example.json\n  - type: Example\n    url: examples/zoominfo-scoop-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-scoop-search-input-example.json\n  - type: Example\n    url: examples/zoominfo-scoop-search-output-example.json\n  - type: Example\n    url: examples/zoominfo-scoop-search-request-example.json\n\
  \  - type: Example\n    url: examples/zoominfo-sic-code-example.json\n  - type: Example\n    url: examples/zoominfo-social-media-url-example.json\n  - type: Example\n    url: examples/zoominfo-sub-unit-type-info-example.json\n  - type: Example\n    url: examples/zoominfo-subscription-example.json\n  - type: Example\n    url: examples/zoominfo-tech-attribute-example.json\n  - type: Example\n    url: examples/zoominfo-technology-enrich-request-example.json\n  - type: Example\n    url: examples/zoominfo-type-example.json\n  - type: Example\n    url: examples/zoominfo-update-webhook-request-example.json\n  - type: Example\n    url: examples/zoominfo-usage-example.json\n  - type: Example\n    url: examples/zoominfo-validate-target-u-r-l-request-example.json\n  - type: Example\n    url: examples/zoominfo-webhook-example.json\n  description: The ZoomInfo API is a set of HTTPS endpoints you can use to programmatically retrieve and integrate ZoomInfo data into your existing technology stack and\
  \ ...\nname: ZoomInfo\ntags:\n- B2B\n- B2B Data\n- Company Data\n- Contact Database\n- Contacts\n- Data\n- Lead Generation\n- Marketing Intelligence\n- Sales Intelligence\ntype: Contract\nimage: https://www.zoominfo.com/assets/img/zoominfo-logo.png\naccess: 3rd-Party\ncommon:\n- url: https://www.zoominfo.com/pricing\n  name: Pricing | ZoomInfo\n  type: Pricing\n- url: https://pipeline.zoominfo.com/\n  name: B2B Sales and Marketing Content | ZoomInfo Blog\n  type: Blog\n- url: https://www.zoominfo.com/about/case-studies\n  name: Case Studies | Customer Success | ZoomInfo\n  type: Customers\n- url: https://www.zoominfo.com/partner\n  name: Program Partnership Benefits | Partner with ZoomInfo\n  type: Partners\n- url: https://www.zoominfo.com/about/help-center\n  name: Help Center | ZoomInfo\n  type: Support\n- url: https://www.zoominfo.com/faqs/business\n  name: Frequently Asked Questions About ZoomInfos Business\n  type: FAQ\n- url: https://pipeline.zoominfo.com/glossary\n  name: Go-to-Market\
  \ Glossary | ZoomInfo Blog\n  type: Glossary\n- url: https://api-docs.zoominfo.com/#authentication\n  type: Authentication\n- url: https://api-docs.zoominfo.com/getting-started\n  type: GettingStarted\n- url: https://api-docs.zoominfo.com/rate-limits\n  type: RateLimits\n- url: https://www.zoominfo.com/about/terms-of-service\n  type: TermsOfService\n- url: https://www.zoominfo.com/about/privacy-policy\n  type: PrivacyPolicy\n- url: https://status.zoominfo.com\n  type: StatusPage\n- type: Features\n  data:\n  - name: Contact Search\n    description: Search for contacts by job title, company, location, industry, and other criteria\n  - name: Company Search\n    description: Search for companies by industry, revenue, employee count, location, and technology stack\n  - name: Contact Enrichment\n    description: Enrich contact records with verified email addresses, phone numbers, and professional details\n  - name: Company Enrichment\n    description: Enrich company records with firmographic\
  \ data including revenue, employee count, and technographics\n  - name: Intent Data\n    description: Identify companies showing buying intent signals based on content consumption patterns\n  - name: Scoops\n    description: Access business intelligence scoops about company changes, hiring, and strategic initiatives\n  - name: News Intelligence\n    description: Search and enrich news articles related to companies and contacts\n  - name: Technology Tracking\n    description: Identify technologies used by companies across their tech stack\n  - name: Corporate Hierarchy\n    description: Map organizational structures including parent companies, subsidiaries, and divisions\n  - name: Org Chart\n    description: Access organizational chart data showing reporting relationships within companies\n  - name: Webhooks\n    description: Real-time notifications for data changes and updates via webhook subscriptions\n  - name: Bulk Operations\n    description: Submit batch search and enrichment jobs\
  \ for large-scale data processing\n  - name: WebSights\n    description: Identify website visitors by IP address and enrich with company information\n  - name: Compliance\n    description: Access compliance data to support GDPR and privacy regulation requirements\n- type: UseCases\n  data:\n  - name: Sales Prospecting\n    description: Identify and prioritize ideal prospects using firmographic and intent data to build targeted sales pipelines\n  - name: Lead Enrichment\n    description: Automatically enrich inbound leads with verified contact and company data for faster qualification\n  - name: Account-Based Marketing\n    description: Build targeted account lists and personalize outreach using detailed company intelligence\n  - name: CRM Data Hygiene\n    description: Cleanse and update CRM records with accurate contact information and company details\n  - name: Market Research\n    description: Analyze market segments, technology adoption, and competitive landscapes using company data\n\
  \  - name: Competitive Intelligence\n    description: Monitor competitor activities, technology changes, and strategic moves through scoops and news\n  - name: Buyer Intent Analysis\n    description: Identify accounts actively researching solutions in your category based on intent signals\n  - name: Website Visitor Identification\n    description: Convert anonymous website traffic into identified company accounts using IP enrichment\n- type: Integrations\n  data:\n  - name: Salesforce\n    description: Native integration to enrich and sync contact and company data with Salesforce CRM\n  - name: HubSpot\n    description: Seamless integration to push enriched data into HubSpot CRM and marketing automation\n  - name: Microsoft Dynamics 365\n    description: Integration to enrich records and sync data with Microsoft Dynamics CRM\n  - name: Marketo\n    description: Marketing automation integration for lead enrichment and scoring with Marketo\n  - name: Outreach\n    description: Sales engagement\
  \ platform integration for enriched prospect data in Outreach sequences\n  - name: Salesloft\n    description: Integration to power Salesloft cadences with verified contact information\n  - name: Slack\n    description: Notifications and alerts for intent signals and data updates delivered to Slack channels\n  - name: Snowflake\n    description: Data sharing integration to access ZoomInfo data directly in Snowflake data warehouse\n  - name: Google Ads\n    description: Audience targeting integration to reach ideal prospects with Google advertising campaigns\n  - name: LinkedIn\n    description: Integration to match and enrich LinkedIn profile data with ZoomInfo intelligence\n- type: GitHubOrganization\n  url: https://github.com/Zoominfo\n- type: DeveloperPortal\n  url: https://api-docs.zoominfo.com\n- type: APIReference\n  url: https://api-docs.zoominfo.com\n- type: Hub\n  url: https://github.com/Zoominfo/zoominfo-mcp-plugin\n  title: MCP Server\n- type: SpectralRules\n  url: rules/zoominfo-spectral-rules.yml\n\
  - type: Vocabulary\n  url: vocabulary/zoominfo-vocabulary.yaml\n- type: NaftikoCapability\n  url: capabilities/data-enrichment.yaml\n- type: NaftikoCapability\n  url: capabilities/sales-prospecting.yaml\n- type: NaftikoCapability\n  url: capabilities/shared/zoominfo-api.yaml\ncreated: '2025-02-09'\nmodified: '2026-04-18'\nposition: Consuming\ndescription: ZoomInfo is a leading B2B contact database and sales intelligence platform that provides detailed company and contact information, helping sales and marketing teams identify and connect \n  with potential customers.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zoominfo/refs/heads/main/apis.yml
tags:
- B2B
- B2B Data
- Company Data
- Contact Database
- Contacts
- Data
- Lead Generation
- Marketing Intelligence
- Sales Intelligence
url: https://raw.githubusercontent.com/api-evangelist/zoominfo/refs/heads/main/apis.yml
use_cases:
- description: Identify and prioritize ideal prospects using firmographic and intent data to build targeted sales pipelines
  name: Sales Prospecting
- description: Automatically enrich inbound leads with verified contact and company data for faster qualification
  name: Lead Enrichment
- description: Build targeted account lists and personalize outreach using detailed company intelligence
  name: Account-Based Marketing
- description: Cleanse and update CRM records with accurate contact information and company details
  name: CRM Data Hygiene
- description: Analyze market segments, technology adoption, and competitive landscapes using company data
  name: Market Research
- description: Monitor competitor activities, technology changes, and strategic moves through scoops and news
  name: Competitive Intelligence
- description: Identify accounts actively researching solutions in your category based on intent signals
  name: Buyer Intent Analysis
- description: Convert anonymous website traffic into identified company accounts using IP enrichment
  name: Website Visitor Identification
---
