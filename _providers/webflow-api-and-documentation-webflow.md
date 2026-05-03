---
api_count: 5
api_specs:
- filename: webflow-data-api-openapi.yml
  format: yaml
  label: Webflow Data API
  slug: data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/openapi/webflow-data-api-openapi.yml
- filename: webflow-sites-openapi.yml
  format: yaml
  label: Webflow Sites API
  slug: sites-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/openapi/webflow-sites-openapi.yml
- filename: webflow-collections-openapi.yml
  format: yaml
  label: Webflow Collections API
  slug: collections-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/openapi/webflow-collections-openapi.yml
- filename: webflow-items-openapi.yml
  format: yaml
  label: Webflow CMS Items API
  slug: items-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/openapi/webflow-items-openapi.yml
- filename: webflow-webhooks-openapi.yml
  format: yaml
  label: Webflow Webhooks API
  slug: webhooks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/openapi/webflow-webhooks-openapi.yml
apis:
- description: The Webflow Data API is a comprehensive RESTful API providing programmatic access to Webflow sites, workspaces, CMS collections and items, ecommerce products and orders, assets, users, forms, and webh
  name: Webflow Data API
  slug: data-api
- description: Site management endpoints for creating, updating, publishing, and deleting Webflow sites, plus managing custom domains, redirects, robots.txt, and site activity logs.
  name: Webflow Sites API
  slug: sites-api
- description: CMS collection management endpoints for creating, listing, and deleting collections, and managing collection field configurations.
  name: Webflow Collections API
  slug: collections-api
- description: CMS item endpoints for creating, reading, updating, deleting, and publishing collection items, including support for bulk operations and live/staged item management.
  name: Webflow CMS Items API
  slug: items-api
- description: Webhook registration and management endpoints for receiving real-time event notifications from Webflow sites including form submissions, ecommerce events, and CMS changes.
  name: Webflow Webhooks API
  slug: webhooks-api
capabilities:
- description: 'Webflow CMS management workflow combining the Data API for programmatic content operations: site publishing, CMS collection and item management, webhook configuration, and content automation. Used by '
  name: Webflow CMS Management
  slug: cms-management
common:
- title: ''
  type: Portal
  url: https://developers.webflow.com/
- title: ''
  type: GettingStarted
  url: https://developers.webflow.com/data/reference/rest-introduction/quick-start
- title: ''
  type: Authentication
  url: https://developers.webflow.com/data/reference/authentication
- title: ''
  type: RateLimits
  url: https://developers.webflow.com/data/reference/rate-limits
- title: ''
  type: ChangeLog
  url: https://developers.webflow.com/data/v2.0.0/changelog
- title: ''
  type: SDK
  url: https://developers.webflow.com/data/reference/sdks
- title: ''
  type: Website
  url: https://webflow.com/
- title: ''
  type: Blog
  url: https://webflow.com/blog
- title: ''
  type: Support
  url: https://help.webflow.com/
- title: ''
  type: Community
  url: https://forum.webflow.com/
- title: ''
  type: Academy
  url: https://university.webflow.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/webflow
- title: ''
  type: TermsOfService
  url: https://webflow.com/legal/terms
- title: ''
  type: PrivacyPolicy
  url: https://webflow.com/legal/privacy
- title: ''
  type: StatusPage
  url: https://status.webflow.com/
- title: ''
  type: Marketplace
  url: https://webflow.com/marketplace
- title: ''
  type: SpectralRules
  url: rules/webflow-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/webflow-api-and-documentation-webflow-vocabulary.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/cms-management.yaml
- title: ''
  type: JSONLD
  url: json-ld/webflow-context.jsonld
created: '2026-03-16'
description: Webflow provides a visual web development platform with a comprehensive REST API for programmatically managing sites, CMS collections, ecommerce, assets, users, and forms. The Webflow Data API v2 enables developers to build integrations, automate content workflows, and extend Webflow's core functionality. All V2 API endpoints start with https://api.webflow.com/v2 and support OAuth 2.0 and API key authentication.
features:
- description: Drag-and-drop visual web design with clean, semantic HTML/CSS output.
  name: Visual Web Builder
- description: Programmatic management of CMS collections and items for dynamic content.
  name: CMS API
- description: Full ecommerce API for products, orders, inventory, and payment processing.
  name: Ecommerce API
- description: Secure OAuth 2.0 authorization for building Webflow apps and integrations.
  name: OAuth 2.0
- description: Real-time event notifications for form submissions, publishing, and ecommerce events.
  name: Webhooks
- description: Build custom panels and tools that run inside the Webflow Designer.
  name: Designer Extensions
- description: Programmatically publish Webflow sites to staging or production domains.
  name: Site Publishing API
- description: Manage multiple Webflow sites across workspaces from a single API key.
  name: Multisite Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: No-code Webflow integration for connecting with 5,000+ apps via Zapier.
  name: Zapier
- description: Visual automation platform for Webflow workflow automation.
  name: Make (Integromat)
- description: Connect Airtable as a data source for Webflow CMS content.
  name: Airtable
- description: Sync Webflow form submissions with HubSpot CRM.
  name: HubSpot
- description: Import Shopify product catalog into Webflow ecommerce.
  name: Shopify
- description: Deploy Webflow sites behind Cloudflare for CDN and security.
  name: Cloudflare
jsonld:
- class_count: 18
  name: Webflow Context
  property_count: 7
  slug: webflow-context
layout: provider
modified: '2026-05-03'
name: Webflow API and Documentation
rules:
- name: Webflow API and Documentation API Rules
  rule_count: 26
  severity_counts:
    error: 8
    hint: 0
    info: 8
    warn: 10
  slug: webflow-spectral-rules
skills: []
slug: webflow-api-and-documentation-webflow
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: webflow-api-and-documentation-webflow\nname: Webflow API and Documentation\ndescription: >-\n  Webflow provides a visual web development platform with a comprehensive REST\n  API for programmatically managing sites, CMS collections, ecommerce, assets,\n  users, and forms. The Webflow Data API v2 enables developers to build\n  integrations, automate content workflows, and extend Webflow's core\n  functionality. All V2 API endpoints start with https://api.webflow.com/v2 and\n  support OAuth 2.0 and API key authentication.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CMS\n  - Content Management\n  - Ecommerce\n  - No-Code\n  - Publishing\n  - Web Development\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: webflow-api-and-documentation-webflow:data-api\n\
  \    name: Webflow Data API\n    description: >-\n      The Webflow Data API is a comprehensive RESTful API providing programmatic\n      access to Webflow sites, workspaces, CMS collections and items, ecommerce\n      products and orders, assets, users, forms, and webhooks. All V2 endpoints\n      use https://api.webflow.com/v2 as the base URL and require OAuth 2.0 or\n      API key authentication.\n    humanURL: https://developers.webflow.com/data/reference/rest-introduction\n    tags:\n      - CMS\n      - Content Management\n      - Ecommerce\n      - REST\n      - Sites\n    properties:\n      - type: Documentation\n        url: https://developers.webflow.com/data/reference/rest-introduction\n      - type: OpenAPI\n        url: openapi/webflow-data-api-openapi.yml\n      - type: Authentication\n        url: https://developers.webflow.com/data/reference/authentication\n      - type: RateLimits\n        url: https://developers.webflow.com/data/reference/rate-limits\n      - type: ChangeLog\n\
  \        url: https://developers.webflow.com/data/v2.0.0/changelog\n      - type: JSONSchema\n        url: json-schema/webflow-site-schema.json\n      - type: JSONSchema\n        url: json-schema/webflow-collection-item-schema.json\n      - type: JSONSchema\n        url: json-schema/webflow-order-schema.json\n      - type: JSONSchema\n        url: json-schema/webflow-webhook-schema.json\n\n  - aid: webflow-api-and-documentation-webflow:sites-api\n    name: Webflow Sites API\n    description: >-\n      Site management endpoints for creating, updating, publishing, and\n      deleting Webflow sites, plus managing custom domains, redirects,\n      robots.txt, and site activity logs.\n    humanURL: https://developers.webflow.com/data/reference/rest-introduction\n    tags:\n      - Domains\n      - Publishing\n      - Sites\n    properties:\n      - type: Documentation\n        url: https://developers.webflow.com/data/reference/rest-introduction\n      - type: OpenAPI\n        url: openapi/webflow-sites-openapi.yml\n\
  \n  - aid: webflow-api-and-documentation-webflow:collections-api\n    name: Webflow Collections API\n    description: >-\n      CMS collection management endpoints for creating, listing, and deleting\n      collections, and managing collection field configurations.\n    humanURL: https://developers.webflow.com/data/reference/rest-introduction\n    tags:\n      - CMS\n      - Collections\n      - Fields\n    properties:\n      - type: Documentation\n        url: https://developers.webflow.com/data/reference/rest-introduction\n      - type: OpenAPI\n        url: openapi/webflow-collections-openapi.yml\n\n  - aid: webflow-api-and-documentation-webflow:items-api\n    name: Webflow CMS Items API\n    description: >-\n      CMS item endpoints for creating, reading, updating, deleting, and\n      publishing collection items, including support for bulk operations\n      and live/staged item management.\n    humanURL: https://developers.webflow.com/data/reference/rest-introduction\n    tags:\n\
  \      - CMS\n      - Content Management\n      - Items\n    properties:\n      - type: Documentation\n        url: https://developers.webflow.com/data/reference/rest-introduction\n      - type: OpenAPI\n        url: openapi/webflow-items-openapi.yml\n\n  - aid: webflow-api-and-documentation-webflow:webhooks-api\n    name: Webflow Webhooks API\n    description: >-\n      Webhook registration and management endpoints for receiving real-time\n      event notifications from Webflow sites including form submissions,\n      ecommerce events, and CMS changes.\n    humanURL: https://developers.webflow.com/data/reference/rest-introduction\n    tags:\n      - Events\n      - Notifications\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://developers.webflow.com/data/reference/rest-introduction\n      - type: OpenAPI\n        url: openapi/webflow-webhooks-openapi.yml\n\ncommon:\n  - url: https://developers.webflow.com/\n    name: Webflow Developer Documentation\n\
  \    type: Portal\n    description: Main developer portal for Webflow APIs, guides, and reference.\n  - url: https://developers.webflow.com/data/reference/rest-introduction/quick-start\n    name: Webflow API Quick Start\n    type: GettingStarted\n    description: Quick start guide for making your first Webflow API request.\n  - url: https://developers.webflow.com/data/reference/authentication\n    name: Webflow Authentication\n    type: Authentication\n    description: OAuth 2.0 and API key authentication for Webflow APIs.\n  - url: https://developers.webflow.com/data/reference/rate-limits\n    name: Webflow Rate Limits\n    type: RateLimits\n    description: API rate limiting documentation for Webflow Data API.\n  - url: https://developers.webflow.com/data/v2.0.0/changelog\n    name: Webflow API Changelog\n    type: ChangeLog\n    description: Version history and breaking changes for the Webflow Data API.\n  - url: https://developers.webflow.com/data/reference/sdks\n    name: Webflow\
  \ SDKs\n    type: SDK\n    description: Official Webflow SDKs for JavaScript, Python, and other languages.\n  - url: https://webflow.com/\n    name: Webflow Website\n    type: Website\n    description: Main Webflow website and product information.\n  - url: https://webflow.com/blog\n    name: Webflow Blog\n    type: Blog\n    description: Product news, tutorials, and design inspiration from Webflow.\n  - url: https://help.webflow.com/\n    name: Webflow Help Center\n    type: Support\n    description: Help articles and support resources for Webflow users.\n  - url: https://forum.webflow.com/\n    name: Webflow Forum\n    type: Community\n    description: Community forum for Webflow users and developers.\n  - url: https://university.webflow.com/\n    name: Webflow University\n    type: Academy\n    description: Free courses and tutorials for learning Webflow.\n  - url: https://github.com/webflow\n    name: Webflow GitHub Organization\n    type: GitHubOrganization\n    description: Official\
  \ Webflow GitHub organization with SDKs and tools.\n  - url: https://webflow.com/legal/terms\n    name: Webflow Terms of Service\n    type: TermsOfService\n    description: Terms of service for Webflow platform and APIs.\n  - url: https://webflow.com/legal/privacy\n    name: Webflow Privacy Policy\n    type: PrivacyPolicy\n    description: Privacy policy for Webflow services.\n  - url: https://status.webflow.com/\n    name: Webflow Status\n    type: StatusPage\n    description: Real-time status and uptime information for Webflow services.\n  - url: https://webflow.com/marketplace\n    name: Webflow Marketplace\n    type: Marketplace\n    description: Apps, integrations, and templates for the Webflow ecosystem.\n  - type: SpectralRules\n    url: rules/webflow-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/webflow-api-and-documentation-webflow-vocabulary.yml\n  - type: NaftikoCapability\n    url: capabilities/cms-management.yaml\n  - type: JSONLD\n    url: json-ld/webflow-context.jsonld\n\
  \  - name: Webflow Features\n    type: Features\n    data:\n      - name: Visual Web Builder\n        description: Drag-and-drop visual web design with clean, semantic HTML/CSS output.\n      - name: CMS API\n        description: Programmatic management of CMS collections and items for dynamic content.\n      - name: Ecommerce API\n        description: Full ecommerce API for products, orders, inventory, and payment processing.\n      - name: OAuth 2.0\n        description: Secure OAuth 2.0 authorization for building Webflow apps and integrations.\n      - name: Webhooks\n        description: Real-time event notifications for form submissions, publishing, and ecommerce events.\n      - name: Designer Extensions\n        description: Build custom panels and tools that run inside the Webflow Designer.\n      - name: Site Publishing API\n        description: Programmatically publish Webflow sites to staging or production domains.\n      - name: Multisite Support\n        description: Manage\
  \ multiple Webflow sites across workspaces from a single API key.\n  - name: Webflow Use Cases\n    type: UseCases\n    data:\n      - name: Headless CMS\n        description: Use Webflow as a headless CMS, managing content via the API and rendering with any frontend framework.\n      - name: Content Automation\n        description: Automatically create and publish CMS items from external data sources like spreadsheets or databases.\n      - name: Ecommerce Integration\n        description: Sync Webflow product catalog and orders with ERP or inventory management systems.\n      - name: Multi-Site Management\n        description: Manage content across multiple Webflow sites programmatically from a centralized platform.\n      - name: Form Lead Processing\n        description: Process form submissions via webhooks to integrate with CRM or marketing automation platforms.\n      - name: Site Deployment Automation\n        description: Automate Webflow site publishing as part of CI/CD pipelines\
  \ or content approval workflows.\n  - name: Webflow Integrations\n    type: Integrations\n    data:\n      - name: Zapier\n        description: No-code Webflow integration for connecting with 5,000+ apps via Zapier.\n      - name: Make (Integromat)\n        description: Visual automation platform for Webflow workflow automation.\n      - name: Airtable\n        description: Connect Airtable as a data source for Webflow CMS content.\n      - name: HubSpot\n        description: Sync Webflow form submissions with HubSpot CRM.\n      - name: Shopify\n        description: Import Shopify product catalog into Webflow ecommerce.\n      - name: Cloudflare\n        description: Deploy Webflow sites behind Cloudflare for CDN and security.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/apis.yml
tags:
- CMS
- Content Management
- Ecommerce
- No-Code
- Publishing
- Web Development
url: https://raw.githubusercontent.com/api-evangelist/webflow-api-and-documentation-webflow/refs/heads/main/apis.yml
use_cases:
- description: Use Webflow as a headless CMS, managing content via the API and rendering with any frontend framework.
  name: Headless CMS
- description: Automatically create and publish CMS items from external data sources like spreadsheets or databases.
  name: Content Automation
- description: Sync Webflow product catalog and orders with ERP or inventory management systems.
  name: Ecommerce Integration
- description: Manage content across multiple Webflow sites programmatically from a centralized platform.
  name: Multi-Site Management
- description: Process form submissions via webhooks to integrate with CRM or marketing automation platforms.
  name: Form Lead Processing
- description: Automate Webflow site publishing as part of CI/CD pipelines or content approval workflows.
  name: Site Deployment Automation
---
