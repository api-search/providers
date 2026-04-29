---
api_count: 13
api_specs:
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Domain Search API
  slug: domain-search
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Email Finder API
  slug: email-finder
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Email Verifier API
  slug: email-verifier
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Email Count API
  slug: email-count
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Account API
  slug: account
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Discover API
  slug: discover
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Email Enrichment API
  slug: email-enrichment
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Company Enrichment API
  slug: company-enrichment
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Combined Enrichment API
  slug: combined-enrichment
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Leads API
  slug: leads
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Leads Lists API
  slug: leads-lists
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Campaigns API
  slug: campaigns
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
- filename: hunter-api-openapi.yml
  format: yaml
  label: Hunter Logo API
  slug: logo
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/openapi/hunter-api-openapi.yml
apis:
- description: Returns all the email addresses found using a given domain name, with sources.
  name: Hunter Domain Search API
  slug: domain-search
- description: Generates the most likely email address from a domain name, a first name and a last name.
  name: Hunter Email Finder API
  slug: email-finder
- description: Verifies the deliverability of a given email address.
  name: Hunter Email Verifier API
  slug: email-verifier
- description: Returns the number of email addresses found for a given domain.
  name: Hunter Email Count API
  slug: email-count
- description: Returns information about the account associated with the API key.
  name: Hunter Account API
  slug: account
- description: Returns companies matching a set of criteria using natural language queries or robust filters to find companies aligned with your ideal customer profile.
  name: Hunter Discover API
  slug: discover
- description: Returns comprehensive personal information linked to an email address or LinkedIn profile, providing enriched data points about the person.
  name: Hunter Email Enrichment API
  slug: email-enrichment
- description: Returns detailed organizational data associated with a domain name, including company size, industry, location, and other firmographic information.
  name: Hunter Company Enrichment API
  slug: company-enrichment
- description: Merges person and company information for a single email address, returning enriched records combining both datasets.
  name: Hunter Combined Enrichment API
  slug: combined-enrichment
- description: Allows you to manage the leads stored in Hunter, including listing, creating, updating, upserting, and deleting leads.
  name: Hunter Leads API
  slug: leads
- description: Allows you to manage leads lists in Hunter, including listing, creating, updating, and deleting lead collection groups.
  name: Hunter Leads Lists API
  slug: leads-lists
- description: Allows you to manage email sequences including listing campaigns, managing recipients, and starting sequences for automated email outreach.
  name: Hunter Campaigns API
  slug: campaigns
- description: Retrieves any company logo using a domain name. Free to use with no authentication required, just a backlink from your site to hunter.io.
  name: Hunter Logo API
  slug: logo
capabilities:
- description: Unified workflow for sales prospecting including email discovery, verification, enrichment, lead management, and outreach campaigns. Used by sales development representatives and marketing teams.
  name: Hunter Sales Prospecting
  slug: sales-prospecting
common:
- title: ''
  type: Portal
  url: https://hunter.io/api
- title: ''
  type: Documentation
  url: https://hunter.io/api-documentation/v2
- title: ''
  type: OpenAPI
  url: openapi/hunter-api-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/hunter-lead-schema.json
- title: ''
  type: JSONLD
  url: json-ld/hunter-context.jsonld
- title: ''
  type: Authentication
  url: https://hunter.io/api-documentation/v2#authentication
- title: ''
  type: RateLimits
  url: https://hunter.io/api-documentation/v2#rate-limiting
- title: ''
  type: Pricing
  url: https://hunter.io/pricing
- title: ''
  type: TermsOfService
  url: https://hunter.io/terms
- title: ''
  type: PrivacyPolicy
  url: https://hunter.io/privacy-policy
- title: ''
  type: StatusPage
  url: https://status.hunter.io
- title: ''
  type: Blog
  url: https://hunter.io/blog
- title: ''
  type: Login
  url: https://hunter.io/users/sign_in
- title: ''
  type: SignUp
  url: https://hunter.io/users/sign_up
- title: ''
  type: ChangeLog
  url: https://hunter.io/changelog
- title: ''
  type: GitHubOrganization
  url: https://github.com/hunter-io
- title: ''
  type: Contact
  url: https://hunter.io/contact
- title: ''
  type: Support
  url: https://help.hunter.io
- title: Hunter API Shared Definition
  type: NaftikoCapability
  url: capabilities/shared/hunter-api.yaml
- title: Sales Prospecting Workflow
  type: NaftikoCapability
  url: capabilities/sales-prospecting.yaml
created: '2024-01-01'
description: Hunter is an email finding and verification service that helps find professional email addresses associated with a domain and verify email deliverability.
features:
- description: Find all email addresses associated with a domain name along with confidence scores and sources.
  name: Domain Search
- description: Generate the most likely email address for a person given their name and company domain.
  name: Email Finder
- description: Verify the deliverability and validity of email addresses with detailed status reporting.
  name: Email Verification
- description: Store, organize, and manage prospect leads with lists, tags, and CRM-like contact management.
  name: Lead Management
- description: Create and manage automated email outreach sequences with recipient tracking and scheduling.
  name: Email Campaigns
- description: Enrich email addresses and domains with personal, company, and firmographic data points.
  name: Data Enrichment
- description: Find companies matching ideal customer profiles using natural language queries and advanced filters.
  name: Company Discovery
image: https://hunter.io/images/hunter-logo.png
integrations:
- description: Push verified leads and enriched contacts directly to Salesforce CRM for pipeline management.
  name: Salesforce
- description: Sync leads and contact data with HubSpot CRM for unified sales and marketing workflows.
  name: HubSpot
- description: Export leads to Pipedrive CRM with enriched contact and company information.
  name: Pipedrive
- description: Connect Hunter with thousands of apps through Zapier for automated lead processing workflows.
  name: Zapier
- description: Export domain search results and verified emails directly to Google Sheets for analysis.
  name: Google Sheets
- description: Integrate lead data with Zoho CRM for end-to-end sales pipeline management.
  name: Zoho CRM
jsonld:
- class_count: 0
  name: Hunter Context
  property_count: 0
  slug: hunter-context
layout: provider
modified: '2026-04-18'
name: Hunter
rules:
- name: Hunter API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: hunter-spectral-rules
skills: []
slug: hunter
solutions: []
source_filename: apis.yml
source_yaml: "aid: hunter\nname: Hunter\ndescription: Hunter is an email finding and verification service that helps find professional email addresses associated with a domain and verify email deliverability.\nimage: https://hunter.io/images/hunter-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntype: Index\naccess: 3rd-Party\ntags:\n  - Contact Discovery\n  - Email\n  - Email Verification\n  - Lead Generation\n  - Prospecting\n  - Sales Intelligence\napis:\n  - aid: hunter:domain-search\n    name: Hunter Domain Search API\n    description: Returns all the email addresses found using a given domain name, with sources.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io/api/domain-search\n    baseURL: https://api.hunter.io/v2\n    tags:\n      - Contact Discovery\n      - Domain\n      - Email\n      - Search\n    properties:\n   \
  \   - type: Documentation\n        url: https://hunter.io/api-documentation/v2#domain-search\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:email-finder\n    name: Hunter Email Finder API\n    description: Generates the most likely email address from a domain name, a first name and a last name.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io/api/email-finder\n    baseURL: https://api.hunter.io/v2\n    tags:\n      - Contact Discovery\n      - Email\n      - Finder\n      - Lead Generation\n    properties:\n      - type: Documentation\n        url: https://hunter.io/api-documentation/v2#email-finder\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:email-verifier\n\
  \    name: Hunter Email Verifier API\n    description: Verifies the deliverability of a given email address.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io/api/email-verifier\n    baseURL: https://api.hunter.io/v2\n    tags:\n      - Data Quality\n      - Email\n      - Validation\n      - Verification\n    properties:\n      - type: Documentation\n        url: https://hunter.io/api-documentation/v2#email-verifier\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:email-count\n    name: Hunter Email Count API\n    description: Returns the number of email addresses found for a given domain.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io\n    baseURL: https://api.hunter.io/v2\n    tags:\n      - Analytics\n      - Count\n      - Email\n    properties:\n      - type:\
  \ Documentation\n        url: https://hunter.io/api-documentation/v2#email-count\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:account\n    name: Hunter Account API\n    description: Returns information about the account associated with the API key.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io\n    baseURL: https://api.hunter.io/v2\n    tags:\n      - Account\n      - Management\n      - Usage\n    properties:\n      - type: Documentation\n        url: https://hunter.io/api-documentation/v2#account\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:discover\n    name: Hunter Discover API\n    description: Returns companies matching a set of criteria\
  \ using natural language queries or robust filters to find companies aligned with your ideal customer profile.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io/api/discover\n    baseURL: https://api.hunter.io/v2\n    tags:\n      - Companies\n      - Discover\n      - Lead Generation\n      - Prospecting\n    properties:\n      - type: Documentation\n        url: https://hunter.io/api-documentation/v2#discover\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:email-enrichment\n    name: Hunter Email Enrichment API\n    description: Returns comprehensive personal information linked to an email address or LinkedIn profile, providing enriched data points about the person.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io/api/lead-enrichment\n    baseURL: https://api.hunter.io/v2\n\
  \    tags:\n      - Data\n      - Email\n      - Enrichment\n      - People\n    properties:\n      - type: Documentation\n        url: https://hunter.io/api-documentation/v2#email-enrichment\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:company-enrichment\n    name: Hunter Company Enrichment API\n    description: Returns detailed organizational data associated with a domain name, including company size, industry, location, and other firmographic information.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io/api/company-enrichment\n    baseURL: https://api.hunter.io/v2\n    tags:\n      - Company\n      - Data\n      - Enrichment\n      - Firmographic\n    properties:\n      - type: Documentation\n        url: https://hunter.io/api-documentation/v2#company-enrichment\n      - type: OpenAPI\n      \
  \  url: openapi/hunter-api-openapi.yml\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:combined-enrichment\n    name: Hunter Combined Enrichment API\n    description: Merges person and company information for a single email address, returning enriched records combining both datasets.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io/api/combined-enrichment\n    baseURL: https://api.hunter.io/v2\n    tags:\n      - Combined\n      - Company\n      - Enrichment\n      - People\n    properties:\n      - type: Documentation\n        url: https://hunter.io/api-documentation/v2#combined-enrichment\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:leads\n    name: Hunter Leads API\n    description: Allows you to manage the leads\
  \ stored in Hunter, including listing, creating, updating, upserting, and deleting leads.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io/api/leads\n    baseURL: https://api.hunter.io/v2\n    tags:\n      - Contacts\n      - CRM\n      - Leads\n      - Management\n    properties:\n      - type: Documentation\n        url: https://hunter.io/api-documentation/v2#leads\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/hunter-lead-schema.json\n      - type: JSONLD\n        url: json-ld/hunter-context.jsonld\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:leads-lists\n    name: Hunter Leads Lists API\n    description: Allows you to manage leads lists in Hunter, including listing, creating, updating, and deleting lead collection groups.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL:\
  \ https://hunter.io/api/leads\n    baseURL: https://api.hunter.io/v2\n    tags:\n      - Leads\n      - Lists\n      - Management\n      - Organization\n    properties:\n      - type: Documentation\n        url: https://hunter.io/api-documentation/v2#leads_lists\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/hunter-lead-schema.json\n      - type: JSONLD\n        url: json-ld/hunter-context.jsonld\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:campaigns\n    name: Hunter Campaigns API\n    description: Allows you to manage email sequences including listing campaigns, managing recipients, and starting sequences for automated email outreach.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io/api/campaigns\n    baseURL: https://api.hunter.io/v2\n    tags:\n      - Automation\n      - Campaigns\n   \
  \   - Email Outreach\n      - Sequences\n    properties:\n      - type: Documentation\n        url: https://hunter.io/api-documentation/v2#campaigns\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n        url: https://hunter.io/contact\n  - aid: hunter:logo\n    name: Hunter Logo API\n    description: Retrieves any company logo using a domain name. Free to use with no authentication required, just a backlink from your site to hunter.io.\n    image: https://hunter.io/images/hunter-logo.png\n    humanURL: https://hunter.io/api/logo\n    baseURL: https://logos.hunter.io\n    tags:\n      - Branding\n      - Company\n      - Images\n      - Logo\n    properties:\n      - type: Documentation\n        url: https://hunter.io/api-documentation/v2#logo\n      - type: OpenAPI\n        url: openapi/hunter-api-openapi.yml\n    contact:\n      - FN: Hunter Support\n        email: support@hunter.io\n   \
  \     url: https://hunter.io/contact\ncommon:\n  - type: Portal\n    url: https://hunter.io/api\n  - type: Documentation\n    url: https://hunter.io/api-documentation/v2\n  - type: OpenAPI\n    url: openapi/hunter-api-openapi.yml\n  - type: JSONSchema\n    url: json-schema/hunter-lead-schema.json\n  - type: JSONLD\n    url: json-ld/hunter-context.jsonld\n  - type: Authentication\n    url: https://hunter.io/api-documentation/v2#authentication\n  - type: RateLimits\n    url: https://hunter.io/api-documentation/v2#rate-limiting\n  - type: Pricing\n    url: https://hunter.io/pricing\n  - type: TermsOfService\n    url: https://hunter.io/terms\n  - type: PrivacyPolicy\n    url: https://hunter.io/privacy-policy\n  - type: StatusPage\n    url: https://status.hunter.io\n  - type: Blog\n    url: https://hunter.io/blog\n  - type: Login\n    url: https://hunter.io/users/sign_in\n  - type: SignUp\n    url: https://hunter.io/users/sign_up\n  - type: ChangeLog\n    url: https://hunter.io/changelog\n\
  \  - type: Integrations\n    url: https://hunter.io/integrations\n  - type: GitHubOrganization\n    url: https://github.com/hunter-io\n  - type: Contact\n    url: https://hunter.io/contact\n  - type: Support\n    url: https://help.hunter.io\n  - type: NaftikoCapability\n    url: capabilities/shared/hunter-api.yaml\n    title: Hunter API Shared Definition\n  - type: NaftikoCapability\n    url: capabilities/sales-prospecting.yaml\n    title: Sales Prospecting Workflow\n  - type: Features\n    data:\n      - name: Domain Search\n        description: Find all email addresses associated with a domain name along with confidence scores and sources.\n      - name: Email Finder\n        description: Generate the most likely email address for a person given their name and company domain.\n      - name: Email Verification\n        description: Verify the deliverability and validity of email addresses with detailed status reporting.\n      - name: Lead Management\n        description: Store, organize,\
  \ and manage prospect leads with lists, tags, and CRM-like contact management.\n      - name: Email Campaigns\n        description: Create and manage automated email outreach sequences with recipient tracking and scheduling.\n      - name: Data Enrichment\n        description: Enrich email addresses and domains with personal, company, and firmographic data points.\n      - name: Company Discovery\n        description: Find companies matching ideal customer profiles using natural language queries and advanced filters.\n  - type: UseCases\n    data:\n      - name: Sales Prospecting\n        description: Find and verify email addresses for sales outreach by searching company domains and building prospect lists.\n      - name: Lead Qualification\n        description: Enrich leads with company and personal data to qualify prospects and prioritize outreach efforts.\n      - name: Email List Cleaning\n        description: Verify large email lists to reduce bounce rates and improve email deliverability.\n\
  \      - name: Account-Based Marketing\n        description: Discover key contacts at target accounts using domain search and build targeted outreach campaigns.\n      - name: Recruitment Outreach\n        description: Find professional email addresses for passive candidates at target companies for recruitment campaigns.\n  - type: Integrations\n    data:\n      - name: Salesforce\n        description: Push verified leads and enriched contacts directly to Salesforce CRM for pipeline management.\n      - name: HubSpot\n        description: Sync leads and contact data with HubSpot CRM for unified sales and marketing workflows.\n      - name: Pipedrive\n        description: Export leads to Pipedrive CRM with enriched contact and company information.\n      - name: Zapier\n        description: Connect Hunter with thousands of apps through Zapier for automated lead processing workflows.\n      - name: Google Sheets\n        description: Export domain search results and verified emails directly\
  \ to Google Sheets for analysis.\n      - name: Zoho CRM\n        description: Integrate lead data with Zoho CRM for end-to-end sales pipeline management.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/apis.yml
tags:
- Contact Discovery
- Email
- Email Verification
- Lead Generation
- Prospecting
- Sales Intelligence
url: https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/apis.yml
use_cases:
- description: Find and verify email addresses for sales outreach by searching company domains and building prospect lists.
  name: Sales Prospecting
- description: Enrich leads with company and personal data to qualify prospects and prioritize outreach efforts.
  name: Lead Qualification
- description: Verify large email lists to reduce bounce rates and improve email deliverability.
  name: Email List Cleaning
- description: Discover key contacts at target accounts using domain search and build targeted outreach campaigns.
  name: Account-Based Marketing
- description: Find professional email addresses for passive candidates at target companies for recruitment campaigns.
  name: Recruitment Outreach
---
