---
api_count: 5
api_specs:
- filename: openapi.json
  format: json
  label: Tallyman Collections API
  slug: ''
  spec_type: OpenAPI
  url: https://api.tallyman.co.uk/v1/openapi.json
- filename: openapi.json
  format: json
  label: Tallyman Customer API
  slug: ''
  spec_type: OpenAPI
  url: https://api.tallyman.co.uk/v1/customers/openapi.json
- filename: openapi.json
  format: json
  label: Tallyman Payment API
  slug: ''
  spec_type: OpenAPI
  url: https://api.tallyman.co.uk/v1/payments/openapi.json
- filename: openapi.json
  format: json
  label: Tallyman Reporting API
  slug: ''
  spec_type: OpenAPI
  url: https://api.tallyman.co.uk/v1/reports/openapi.json
apis:
- description: Core API for managing debt collections, customer accounts, and payment arrangements.
  name: Tallyman Collections API
  slug: ''
- description: API for managing customer information, communication preferences, and profile data.
  name: Tallyman Customer API
  slug: ''
- description: API for processing payments, refunds, and payment plan management.
  name: Tallyman Payment API
  slug: ''
- description: API for generating reports, analytics, and business intelligence data.
  name: Tallyman Reporting API
  slug: ''
- description: Event-driven webhooks for real-time notifications on collection activities.
  name: Tallyman Webhooks API
  slug: ''
common:
- title: ''
  type: Getting Started
  url: https://docs.tallyman.co.uk/getting-started
- title: ''
  type: Authentication
  url: https://docs.tallyman.co.uk/authentication
- title: ''
  type: SDKs
  url: https://docs.tallyman.co.uk/sdks
- title: ''
  type: Terms of Service
  url: https://www.tallyman.co.uk/terms
- title: ''
  type: Privacy Policy
  url: https://www.tallyman.co.uk/privacy
- title: ''
  type: Change Log
  url: https://docs.tallyman.co.uk/changelog
- title: ''
  type: Contact
  url: https://www.tallyman.co.uk/contact
created: '2024'
description: Collection management and debt recovery platform APIs.
features: []
image: https://www.tallyman.co.uk/logo.png
integrations: []
layout: provider
modified: '2026-03-16'
name: Tallyman
skills: []
slug: tallyman
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Tallyman\ndescription: >-\n  Collection management and debt recovery platform APIs.\nimage: https://www.tallyman.co.uk/logo.png\nurl: https://www.tallyman.co.uk\ncreated: '2024'\nmodified: '2026-03-16'\ntags:\n  - Collections\n  - Credit Management\n  - CRM\n  - Debt Recovery\n  - Financial Services\napis:\n  - name: Tallyman Collections API\n    description: >-\n      Core API for managing debt collections, customer accounts, and payment arrangements.\n    image: https://www.tallyman.co.uk/api-logo.png\n    humanURL: https://www.tallyman.co.uk/collections\n    baseURL: https://api.tallyman.co.uk/v1\n    tags:\n      - Accounts\n      - Arrangements\n      - Collections\n      - Payments\n    properties:\n      - type: Documentation\n        url: https://docs.tallyman.co.uk/api/collections\n      - type: OpenAPI\n        url: https://api.tallyman.co.uk/v1/openapi.json\n      - type: Authentication\n        url: https://docs.tallyman.co.uk/api/authentication\n      - type:\
  \ Swagger\n        url: https://api.tallyman.co.uk/swagger\n      - type: Postman Collection\n        url: https://www.postman.com/tallyman/collections\n      - type: Rate Limits\n        url: https://docs.tallyman.co.uk/api/rate-limits\n      - type: Status\n        url: https://status.tallyman.co.uk\n    contact:\n      - type: Support\n        url: https://support.tallyman.co.uk\n      - type: Email\n        url: mailto:api-support@tallyman.co.uk\n      - type: Twitter\n        url: https://twitter.com/tallymantech\n  - name: Tallyman Customer API\n    description: >-\n      API for managing customer information, communication preferences, and profile\n      data.\n    humanURL: https://www.tallyman.co.uk/customer-api\n    baseURL: https://api.tallyman.co.uk/v1/customers\n    tags:\n      - Communications\n      - Customers\n      - Preferences\n      - Profiles\n    properties:\n      - type: Documentation\n        url: https://docs.tallyman.co.uk/api/customers\n      - type: OpenAPI\n\
  \        url: https://api.tallyman.co.uk/v1/customers/openapi.json\n  - name: Tallyman Payment API\n    description: >-\n      API for processing payments, refunds, and payment plan management.\n    humanURL: https://www.tallyman.co.uk/payment-api\n    baseURL: https://api.tallyman.co.uk/v1/payments\n    tags:\n      - Payment Plans\n      - Payments\n      - Refunds\n      - Transactions\n    properties:\n      - type: Documentation\n        url: https://docs.tallyman.co.uk/api/payments\n      - type: OpenAPI\n        url: https://api.tallyman.co.uk/v1/payments/openapi.json\n      - type: Security\n        url: https://docs.tallyman.co.uk/api/payment-security\n  - name: Tallyman Reporting API\n    description: >-\n      API for generating reports, analytics, and business intelligence data.\n    humanURL: https://www.tallyman.co.uk/reporting-api\n    baseURL: https://api.tallyman.co.uk/v1/reports\n    tags:\n      - Analytics\n      - Business Intelligence\n      - Metrics\n      - Reporting\n\
  \    properties:\n      - type: Documentation\n        url: https://docs.tallyman.co.uk/api/reporting\n      - type: OpenAPI\n        url: https://api.tallyman.co.uk/v1/reports/openapi.json\n  - name: Tallyman Webhooks API\n    description: >-\n      Event-driven webhooks for real-time notifications on collection activities.\n    humanURL: https://www.tallyman.co.uk/webhooks\n    baseURL: https://api.tallyman.co.uk/v1/webhooks\n    tags:\n      - Events\n      - Notifications\n      - Real-Time\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://docs.tallyman.co.uk/api/webhooks\n      - type: Event Catalog\n        url: https://docs.tallyman.co.uk/api/webhook-events\ncommon:\n  - type: Getting Started\n    url: https://docs.tallyman.co.uk/getting-started\n  - type: Authentication\n    url: https://docs.tallyman.co.uk/authentication\n  - type: SDKs\n    url: https://docs.tallyman.co.uk/sdks\n  - type: Terms of Service\n    url: https://www.tallyman.co.uk/terms\n\
  \  - type: Privacy Policy\n    url: https://www.tallyman.co.uk/privacy\n  - type: Change Log\n    url: https://docs.tallyman.co.uk/changelog\n  - type: Contact\n    url: https://www.tallyman.co.uk/contact\nmaintainers:\n  - name: Tallyman API Team\n    email: api-team@tallyman.co.uk\n    twitter: '@tallymantech'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tallyman/refs/heads/main/apis.yml
tags:
- Collections
- Credit Management
- CRM
- Debt Recovery
- Financial Services
url: https://www.tallyman.co.uk
use_cases: []
---
