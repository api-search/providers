---
api_count: 1
api_specs:
- filename: wildapricot-admin-api-openapi.yml
  format: yaml
  label: WildApricot Admin API
  slug: wildapricot-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/openapi/wildapricot-admin-api-openapi.yml
apis:
- description: The WildApricot Admin API provides programmatic access to membership management features including contacts, events, event registrations, membership levels, invoices, payments, donations, email campai
  name: WildApricot Admin API
  slug: wildapricot-admin-api
capabilities:
- description: Unified capability for managing membership organizations using WildApricot. Covers contact/member lifecycle, event registration, membership levels, invoicing, and payment processing. Intended for asso
  name: WildApricot Membership Management
  slug: membership-management
common:
- title: ''
  type: Website
  url: https://www.wildapricot.com/
- title: ''
  type: Portal
  url: https://app.wildapricot.com/interfaces/api
- title: ''
  type: Documentation
  url: https://gethelp.wildapricot.com/en/articles/182
- title: ''
  type: GettingStarted
  url: https://gethelp.wildapricot.com/en/articles/484
- title: ''
  type: Authentication
  url: https://gethelp.wildapricot.com/en/articles/484
- title: ''
  type: RateLimits
  url: https://gethelp.wildapricot.com/en/articles/182
- title: ''
  type: Pricing
  url: https://www.wildapricot.com/pricing
- title: ''
  type: TermsOfService
  url: https://www.wildapricot.com/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.wildapricot.com/privacy-policy
- title: ''
  type: Support
  url: https://gethelp.wildapricot.com/
- title: ''
  type: Blog
  url: https://www.wildapricot.com/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/WildApricot
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/rules/wildapricot-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/vocabulary/wildapricot-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/capabilities/membership-management.yaml
created: '2025-02-17'
description: WildApricot is a cloud-based membership management software platform designed for associations, nonprofits, and clubs. It provides tools for managing members, events, email communications, online payments, and websites. The WildApricot Admin API provides programmatic access to all platform features including contacts, events, event registrations, membership levels, invoices, payments, donations, email campaigns, and store orders via a REST API secured with OAuth2.
features:
- description: Comprehensive member and contact database with custom fields, saved searches, and OData filtering.
  name: Contact Management
- description: Full event lifecycle management including registration types, waitlists, check-in, and capacity management.
  name: Event Management
- description: Configurable membership tiers with pricing, renewal periods, access restrictions, and bundle support.
  name: Membership Levels
- description: Integrated payment processing for membership fees, event registrations, donations, and store orders.
  name: Online Payments
- description: Built-in email campaign tool with draft management, recipient targeting, scheduling, and delivery tracking.
  name: Email Campaigns
- description: Track and manage charitable donations with custom fields and donor contact linking.
  name: Donation Management
- description: Self-service member portal for profile management, event registration, and membership renewals.
  name: Member Portal
- description: Simple online store for merchandise and product sales with order management.
  name: Store
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: WildApricot has a native QuickBooks integration for financial data sync and accounting workflows.
  name: QuickBooks
- description: WildApricot integrates with Zapier enabling no-code workflows connecting to 5000+ apps.
  name: Zapier
- description: Payments can be processed through Stripe as a payment gateway for online transactions.
  name: Stripe
- description: WildApricot supports PayPal as a payment gateway for member and event payments.
  name: PayPal
- description: WildApricot offers a WordPress integration for embedding member login and event lists.
  name: WordPress
- description: Member contact lists can be synced to Mailchimp for external email marketing campaigns.
  name: Mailchimp
jsonld:
- class_count: 10
  name: Wildapricot Context
  property_count: 101
  slug: wildapricot-context
layout: provider
modified: '2026-05-03'
name: WildApricot
rules:
- name: WildApricot API Rules
  rule_count: 26
  severity_counts:
    error: 11
    hint: 0
    info: 4
    warn: 11
  slug: wildapricot-spectral-rules
skills: []
slug: wildapricot
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: wildapricot\nname: WildApricot\ndescription: >-\n  WildApricot is a cloud-based membership management software platform designed for\n  associations, nonprofits, and clubs. It provides tools for managing members, events,\n  email communications, online payments, and websites. The WildApricot Admin API\n  provides programmatic access to all platform features including contacts, events,\n  event registrations, membership levels, invoices, payments, donations, email campaigns,\n  and store orders via a REST API secured with OAuth2.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Membership Management\n  - Associations\n  - Nonprofit\n  - Events\n  - Payments\ncreated: '2025-02-17'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: wildapricot:wildapricot-admin-api\n\
  \    name: WildApricot Admin API\n    description: >-\n      The WildApricot Admin API provides programmatic access to membership management\n      features including contacts, events, event registrations, membership levels,\n      invoices, payments, donations, email campaigns, and store orders. Secured\n      with OAuth2 client credentials or authorization code flow.\n    humanURL: https://app.wildapricot.com/interfaces/api\n    baseURL: https://api.wildapricot.org/v2.2\n    tags:\n      - Membership Management\n      - Associations\n      - Nonprofit\n      - Contacts\n      - Events\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://app.wildapricot.com/interfaces/api\n      - type: APIReference\n        url: https://app.swaggerhub.com/apis/WildApricot/wild-apricot_public_api/7.24.0\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/openapi/wildapricot-admin-api-openapi.yml\n      - type:\
  \ Authentication\n        url: https://gethelp.wildapricot.com/en/articles/484\n      - type: SDK\n        url: https://github.com/WildApricot/ApiSamples\n        title: API Samples (.NET)\n      - type: SDK\n        url: https://github.com/douglasdeodato/wildapricot-python-api\n        title: Python SDK (Community)\n\ncommon:\n  - type: Website\n    url: https://www.wildapricot.com/\n  - type: Portal\n    url: https://app.wildapricot.com/interfaces/api\n  - type: Documentation\n    url: https://gethelp.wildapricot.com/en/articles/182\n  - type: GettingStarted\n    url: https://gethelp.wildapricot.com/en/articles/484\n  - type: Authentication\n    url: https://gethelp.wildapricot.com/en/articles/484\n  - type: RateLimits\n    url: https://gethelp.wildapricot.com/en/articles/182\n  - type: Pricing\n    url: https://www.wildapricot.com/pricing\n  - type: TermsOfService\n    url: https://www.wildapricot.com/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.wildapricot.com/privacy-policy\n\
  \  - type: Support\n    url: https://gethelp.wildapricot.com/\n  - type: Blog\n    url: https://www.wildapricot.com/blog\n  - type: GitHubOrganization\n    url: https://github.com/WildApricot\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/rules/wildapricot-spectral-rules.yml\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/vocabulary/wildapricot-vocabulary.yaml\n  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/capabilities/membership-management.yaml\n  - type: Features\n    data:\n      - name: Contact Management\n        description: Comprehensive member and contact database with custom fields, saved searches, and OData filtering.\n      - name: Event Management\n        description: Full event lifecycle management including registration types, waitlists, check-in, and capacity management.\n     \
  \ - name: Membership Levels\n        description: Configurable membership tiers with pricing, renewal periods, access restrictions, and bundle support.\n      - name: Online Payments\n        description: Integrated payment processing for membership fees, event registrations, donations, and store orders.\n      - name: Email Campaigns\n        description: Built-in email campaign tool with draft management, recipient targeting, scheduling, and delivery tracking.\n      - name: Donation Management\n        description: Track and manage charitable donations with custom fields and donor contact linking.\n      - name: Member Portal\n        description: Self-service member portal for profile management, event registration, and membership renewals.\n      - name: Store\n        description: Simple online store for merchandise and product sales with order management.\n  - type: UseCases\n    data:\n      - name: Member Onboarding Automation\n        description: Automate new member welcome\
  \ workflows by monitoring contact creation events and sending personalized onboarding sequences.\n      - name: Event Registration Sync\n        description: Sync WildApricot event registrations to CRM or marketing platforms for post-event follow-up campaigns.\n      - name: Membership Renewal Reminders\n        description: Query lapsed and soon-to-expire members to trigger renewal reminder emails or SMS notifications.\n      - name: Financial Reporting\n        description: Extract invoice, payment, and donation data to build financial dashboards and audit reports.\n      - name: Badge and Check-In Systems\n        description: Use the event check-in API to power custom badge printing or door access control at events.\n      - name: Directory Integrations\n        description: Push member data to external directories, websites, or LDAP systems using the contacts API.\n  - type: Integrations\n    data:\n      - name: QuickBooks\n        description: WildApricot has a native QuickBooks\
  \ integration for financial data sync and accounting workflows.\n      - name: Zapier\n        description: WildApricot integrates with Zapier enabling no-code workflows connecting to 5000+ apps.\n      - name: Stripe\n        description: Payments can be processed through Stripe as a payment gateway for online transactions.\n      - name: PayPal\n        description: WildApricot supports PayPal as a payment gateway for member and event payments.\n      - name: WordPress\n        description: WildApricot offers a WordPress integration for embedding member login and event lists.\n      - name: Mailchimp\n        description: Member contact lists can be synced to Mailchimp for external email marketing campaigns.\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/apis.yml
tags:
- Membership Management
- Associations
- Nonprofit
- Events
- Payments
url: https://raw.githubusercontent.com/api-evangelist/wildapricot/refs/heads/main/apis.yml
use_cases:
- description: Automate new member welcome workflows by monitoring contact creation events and sending personalized onboarding sequences.
  name: Member Onboarding Automation
- description: Sync WildApricot event registrations to CRM or marketing platforms for post-event follow-up campaigns.
  name: Event Registration Sync
- description: Query lapsed and soon-to-expire members to trigger renewal reminder emails or SMS notifications.
  name: Membership Renewal Reminders
- description: Extract invoice, payment, and donation data to build financial dashboards and audit reports.
  name: Financial Reporting
- description: Use the event check-in API to power custom badge printing or door access control at events.
  name: Badge and Check-In Systems
- description: Push member data to external directories, websites, or LDAP systems using the contacts API.
  name: Directory Integrations
---
