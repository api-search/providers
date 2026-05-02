---
api_count: 2
api_specs:
- filename: lunar-dev-gateway-admin-openapi.yml
  format: yaml
  label: Lunar.dev Gateway Admin API
  slug: gateway-admin
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/openapi/lunar-dev-gateway-admin-openapi.yml
- filename: lunar-dev-gateway-proxy-openapi.yml
  format: yaml
  label: Lunar.dev Gateway Proxy API
  slug: gateway-proxy
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/openapi/lunar-dev-gateway-proxy-openapi.yml
apis:
- description: 'The Lunar.dev Gateway Admin API provides administrative endpoints for managing and monitoring the Lunar API Consumption Gateway. It enables health monitoring, endpoint discovery, flow validation, and '
  name: Lunar.dev Gateway Admin API
  slug: gateway-admin
- description: The Lunar.dev Gateway Proxy API handles routing of outbound egress API traffic through the Lunar Gateway. Client applications send third-party API requests through this proxy, which provides traffic m
  name: Lunar.dev Gateway Proxy API
  slug: gateway-proxy
common:
- title: ''
  type: Youtube
  url: https://www.youtube.com/channel/UCgWge-0djZcm-JWU82FbR7A
- title: ''
  type: GitHubOrganization
  url: https://github.com/TheLunarCompany
- title: ''
  type: Website
  url: https://www.lunar.dev/
- title: ''
  type: Blog
  url: https://www.lunar.dev/lunar-blog
- title: ''
  type: Guide
  url: https://www.lunar.dev/guides-resources
- title: ''
  type: FAQ
  url: https://www.lunar.dev/faqs
- title: ''
  type: Customers
  url: https://www.lunar.dev/case-study
- title: ''
  type: Customers
  url: https://www.lunar.dev/case-study
- title: ''
  type: Documentation
  url: https://docs.lunar.dev/
- title: ''
  type: GettingStarted
  url: https://docs.lunar.dev/quick-start-guide/
- title: ''
  type: Quotas
  url: https://docs.lunar.dev/quotas/quotas-overview
- title: ''
  type: FAQ
  url: https://docs.lunar.dev/additional-resources/faqs/faqIndex
- title: ''
  type: About
  url: https://www.lunar.dev/about-us
- title: ''
  type: Login
  url: https://login.lunar.dev/u/login?state=hKFo2SBYaVVrZmZpMHhLN3M3RFlmV0s1WUZCYzZjb2Nwa2FNWaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIEtDRC1iM2d3Z1ltMTNSYmpKZEloOHFHUFp3aG5FMk9vo2NpZNkgQTZBOVRoUnJ6anp2eEx6cFUwRm5JZE1Id0xUUmdnSFE
- title: ''
  type: SignUp
  url: https://login.lunar.dev/u/login?state=hKFo2SBkZkoxMlV1VVFQQmZ3ejlTQjU2QWdteFBEbG1tSWNERaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIFVCVnEySHI0MHlSLTdmRU0ydzBGeTd6aFlxLTFYUlhMo2NpZNkgQTZBOVRoUnJ6anp2eEx6cFUwRm5JZE1Id0xUUmdnSFE
- title: ''
  type: PrivacyPolicy
  url: https://www.lunar.dev/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.lunar.dev/terms-of-use
- title: ''
  type: Blog
  url: https://www.lunar.dev/lunar-blog
- title: ''
  type: Support
  url: https://www.lunar.dev/demo
- title: ''
  type: Pricing
  url: https://www.lunar.dev/pricing
created: '2025-01-08'
description: Lunar.dev is an enterprise-grade gateway platform for AI governance and third-party API consumption control. It unifies an MCP Gateway, AI Gateway, and API Consumption Gateway into a single control point that gives organizations observability, access control, policy enforcement, quota management, rate limiting, and real-time monitoring over how applications and AI agents authenticate, discover tools, and consume third-party APIs.
features:
- name: Additional Features
- name: Advanced Traffic Controls
- name: Broad Sdk Support
- name: Centralized Consumption
- name: Configurable Policies
- name: Consumer Tags
- name: Egress API Proxy
- name: Fail-Safe Mechanisms
- name: Generic Approach
- name: Inventory of APIs
- name: Insights
- name: Lunar Proxy
- name: Lunar Interceptor
- name: No Code Changes
- name: Plugin System
- name: Prioritized API Queuing
- name: Production-Grade Ready
- name: Quota Management
- name: Real-Time Insights
- name: Real-Time Controls
- name: Real-Time Monitoring
- name: Visibility
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Lunar Dev Context
  property_count: 5
  slug: lunar-dev-context
layout: provider
modified: '2026-04-28'
name: Lunar.dev
skills: []
slug: lunar-dev
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: lunar-dev\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/apis.yml\napis:\n  - aid: lunar-dev:gateway-admin\n    name: Lunar.dev Gateway Admin API\n    tags:\n      - AI Gateway\n      - Consumption Gateway\n      - Control\n      - Discovery\n      - Flows\n      - Health\n      - Integrations\n      - MCP Gateway\n      - Performance\n      - Platform\n      - Policies\n      - Visibility\n    humanURL: https://docs.lunar.dev/\n    properties:\n      - url: https://docs.lunar.dev/\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/openapi/lunar-dev-gateway-admin-openapi.yml\n        type: OpenAPI\n      - url: json-schema/health-status.json\n        type: JSONSchema\n      - url: json-schema/discovered-endpoint.json\n        type: JSONSchema\n      - url: json-schema/policy.json\n        type: JSONSchema\n      - url: json-schema/flow.json\n       \
  \ type: JSONSchema\n      - url: json-schema/validation-result.json\n        type: JSONSchema\n      - url: json-ld/lunar-dev-context.jsonld\n        type: JSONLD\n    description: >-\n      The Lunar.dev Gateway Admin API provides administrative endpoints for\n      managing and monitoring the Lunar API Consumption Gateway. It enables\n      health monitoring, endpoint discovery, flow validation, and policy\n      management for the running gateway instance.\n  - aid: lunar-dev:gateway-proxy\n    name: Lunar.dev Gateway Proxy API\n    tags:\n      - AI Gateway\n      - Consumption Gateway\n      - Egress\n      - Integrations\n      - MCP Gateway\n      - Platform\n      - Proxy\n      - Quota Management\n      - Rate Limiting\n      - Traffic Management\n    humanURL: https://docs.lunar.dev/\n    properties:\n      - url: https://docs.lunar.dev/\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/openapi/lunar-dev-gateway-proxy-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The Lunar.dev Gateway Proxy API handles routing of outbound egress API\n      traffic through the Lunar Gateway. Client applications send third-party\n      API requests through this proxy, which provides traffic management,\n      policy enforcement, caching, rate limiting, quota management, and\n      real-time observability.\nname: Lunar.dev\ntags:\n  - AI Gateway\n  - Automation\n  - Consumption Gateway\n  - Control\n  - Deployment\n  - Integrations\n  - MCP Gateway\n  - Performance\n  - Platform\n  - Version Control\n  - Visibility\n  - Workflows\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://www.youtube.com/channel/UCgWge-0djZcm-JWU82FbR7A\n    name: Youtube\n    type: Youtube\n  - url: https://github.com/TheLunarCompany\n    name: GitHub Organization\n    type: GitHubOrganization\n  - url: https://www.lunar.dev/\n    name: Lunar | Ground\
  \ Control for 3rd Party APIs\n    type: Website\n    description: 'null'\n  - url: https://www.lunar.dev/lunar-blog\n    name: API Management Blog | Lunar\n    type: Blog\n    description: 'null'\n  - url: https://www.lunar.dev/guides-resources\n    name: 'API Consumption Management: Resources & Guides | Lunar.dev'\n    type: Guide\n    description: 'null'\n  - url: https://www.lunar.dev/faqs\n    name: Lunar | Frequently asked questions\n    type: FAQ\n    description: 'null'\n  - url: https://www.lunar.dev/case-study\n    name: Lunar Case Studies\n    type: Customers\n    description: 'null'\n  - url: https://www.lunar.dev/case-study\n    name: Lunar Case Studies\n    type: Customers\n    description: 'null'\n  - url: https://www.lunar.dev/use-cases\n    name: Use cases\n    type: UseCases\n    description: 'null'\n  - url: https://docs.lunar.dev/\n    name: Home | Lunar Docs\n    type: Documentation\n    description: 'null'\n  - url: https://docs.lunar.dev/quick-start-guide/\n    name:\
  \ Quick Start Guide | Lunar Docs\n    type: GettingStarted\n    description: 'null'\n  - url: https://docs.lunar.dev/quotas/quotas-overview\n    name: Quotas Overview | Lunar Docs\n    type: Quotas\n    description: 'null'\n  - url: https://docs.lunar.dev/additional-resources/faqs/faqIndex\n    name: FAQs | Lunar Docs\n    type: FAQ\n    description: 'null'\n  - url: https://www.lunar.dev/about-us\n    name: About Us | Lunar\n    type: About\n    description: 'null'\n  - url: >-\n      https://login.lunar.dev/u/login?state=hKFo2SBYaVVrZmZpMHhLN3M3RFlmV0s1WUZCYzZjb2Nwa2FNWaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIEtDRC1iM2d3Z1ltMTNSYmpKZEloOHFHUFp3aG5FMk9vo2NpZNkgQTZBOVRoUnJ6anp2eEx6cFUwRm5JZE1Id0xUUmdnSFE\n    name: Sign in | Lunar.dev\n    type: Login\n    description: 'null'\n  - url: >-\n      https://login.lunar.dev/u/login?state=hKFo2SBkZkoxMlV1VVFQQmZ3ejlTQjU2QWdteFBEbG1tSWNERaFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIFVCVnEySHI0MHlSLTdmRU0ydzBGeTd6aFlxLTFYUlhMo2NpZNkgQTZBOVRoUnJ6anp2eEx6cFUwRm5JZE1Id0xUUmdnSFE\n\
  \    name: Sign in | Lunar.dev\n    type: SignUp\n    description: 'null'\n  - url: https://www.lunar.dev/privacy-policy\n    name: Lunar | Privacy Policy\n    type: PrivacyPolicy\n    description: 'null'\n  - url: https://www.lunar.dev/terms-of-use\n    name: Lunar | Terms of Use\n    type: TermsOfService\n    description: 'null'\n  - url: https://www.lunar.dev/lunar-blog\n    name: API Management Blog | Lunar\n    type: Blog\n    description: 'null'\n  - url: https://www.lunar.dev/demo\n    name: See lunar.dev in action\n    type: Support\n    description: 'null'\n  - url: https://www.lunar.dev/pricing\n    name: Lunar | Pricing\n    type: Pricing\n    description: 'null'\n  - name: Features\n    type: Features\n    data:\n      - name: Additional Features\n      - name: Advanced Traffic Controls\n      - name: Broad Sdk Support\n      - name: Centralized Consumption\n      - name: Configurable Policies\n      - name: Consumer Tags\n      - name: Egress API Proxy\n      - name: Fail-Safe\
  \ Mechanisms\n      - name: Generic Approach\n      - name: Inventory of APIs\n      - name: Insights\n      - name: Lunar Proxy\n      - name: Lunar Interceptor\n      - name: No Code Changes\n      - name: Plugin System\n      - name: Prioritized API Queuing\n      - name: Production-Grade Ready\n      - name: Quota Management\n      - name: Real-Time Insights\n      - name: Real-Time Controls\n      - name: Real-Time Monitoring\n      - name: Visibility\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: AI-Aware API Consumption\n      - name: API Consumption Management\n      - name: Consolidating Mcp Servers\n      - name: Cost Optimization\n      - name: Egress API Proxy\n      - name: Managing Api-Driven Tasks\n      - name: Policy Enforcement\n      - name: Visibility and Alerts\ncreated: '2025-01-08'\nmodified: '2026-04-28'\nposition: Consumer\ndescription: >-\n  Lunar.dev is an enterprise-grade gateway platform for AI governance and\n  third-party API consumption\
  \ control. It unifies an MCP Gateway, AI Gateway,\n  and API Consumption Gateway into a single control point that gives\n  organizations observability, access control, policy enforcement, quota\n  management, rate limiting, and real-time monitoring over how applications\n  and AI agents authenticate, discover tools, and consume third-party APIs.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/apis.yml
tags:
- AI Gateway
- Automation
- Consumption Gateway
- Control
- Deployment
- Integrations
- MCP Gateway
- Performance
- Platform
- Version Control
- Visibility
- Workflows
url: https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/apis.yml
use_cases:
- name: AI-Aware API Consumption
- name: API Consumption Management
- name: Consolidating Mcp Servers
- name: Cost Optimization
- name: Egress API Proxy
- name: Managing Api-Driven Tasks
- name: Policy Enforcement
- name: Visibility and Alerts
---
