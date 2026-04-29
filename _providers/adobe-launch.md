---
api_count: 4
api_specs:
- filename: reactor-api.yml
  format: yaml
  label: Adobe Launch Reactor API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-launch/refs/heads/main/openapi/reactor-api.yml
- filename: extension-api.yml
  format: yaml
  label: Adobe Launch Extension API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-launch/refs/heads/main/openapi/extension-api.yml
- filename: event-forwarding-api.yml
  format: yaml
  label: Adobe Experience Platform Event Forwarding API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-launch/refs/heads/main/openapi/event-forwarding-api.yml
- filename: data-collection-api.yml
  format: yaml
  label: Adobe Experience Platform Data Collection API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-launch/refs/heads/main/openapi/data-collection-api.yml
apis:
- description: The Reactor API allows you to programmatically manage all resources for Adobe Experience Platform Tags, including properties, data elements, rules, extensions, library builds, and environments. It fol
  name: Adobe Launch Reactor API
  slug: ''
- description: 'API for developing custom extensions for Adobe Experience Platform Tags, allowing developers to create integrations with third-party tools and services. Extensions are the building blocks of tags and '
  name: Adobe Launch Extension API
  slug: ''
- description: 'Event forwarding allows you to send collected event data to destinations for server-side processing using the Adobe Experience Platform Edge Network. It decreases web page weight by moving tasks from '
  name: Adobe Experience Platform Event Forwarding API
  slug: ''
- description: The Data Collection APIs provide endpoints for sending data directly to the Adobe Experience Platform Edge Network, including the Edge Network API for authenticated and non-authenticated data ingestio
  name: Adobe Experience Platform Data Collection API
  slug: ''
capabilities:
- description: Unified workflow for Adobe Experience Platform data collection. Combines Event Forwarding and Data Collection APIs for data engineers managing server-side event routing, Edge Network data ingestion, a
  name: Adobe Launch Data Collection Pipeline
  slug: data-collection-pipeline
- description: Unified workflow for managing Adobe Experience Platform Tags. Combines the Reactor API and Extension API for marketing technologists and web developers managing tag properties, rules, data elements, e
  name: Adobe Launch Tag Management
  slug: tag-management
common:
- title: ''
  type: TermsOfService
  url: https://www.adobe.com/legal/terms.html
- title: ''
  type: PrivacyPolicy
  url: https://www.adobe.com/privacy.html
- title: ''
  type: Console
  url: https://developer.adobe.com/developer-console/
- title: ''
  type: Portal
  url: https://developer.adobe.com/
- title: ''
  type: StatusPage
  url: https://status.adobe.com/
- title: ''
  type: Blog
  url: https://medium.com/adobetech
- title: ''
  type: GitHubOrganization
  url: https://github.com/adobe
- title: ''
  type: SignUp
  url: https://developer.adobe.com/developer-console/
- title: ''
  type: Authentication
  url: https://experienceleague.adobe.com/en/docs/experience-platform/landing/platform-apis/api-authentication
- title: ''
  type: ChangeLog
  url: https://experienceleague.adobe.com/en/docs/experience-platform/release-notes/latest
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/@adobe/reactor-sdk
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/@adobe/reactor-scaffold
- title: ''
  type: SDK
  url: https://www.npmjs.com/package/@adobe/reactor-sandbox
created: '2024-01-15'
description: Adobe Launch, now known as Adobe Experience Platform Tags, is a next-generation tag management system that unifies the client-side marketing ecosystem by empowering developers to build integrations on a robust, extensible platform that partners, clients, and the broader industry can build on and contribute to.
features:
- Next-generation tag management for web and mobile
- Extensible platform with public extension marketplace
- Server-side event forwarding via Edge Network
- Rule-based data collection and routing
- Library versioning with staging and production environments
- JSON API specification-based programmatic management
- Real-time data collection to Edge Network
- Media tracking and analytics integration
image: /assets/icons/adobe-launch.png
integrations:
- Adobe Analytics
- Adobe Target
- Adobe Audience Manager
- Adobe Experience Platform
- Google Analytics
- Facebook Pixel
- LinkedIn Insight Tag
- Custom JavaScript libraries
- Third-party marketing platforms
jsonld:
- class_count: 67
  name: context Context
  property_count: 30
  slug: context
- class_count: 0
  name: Data Collection Context
  property_count: 0
  slug: data-collection-context
- class_count: 0
  name: Event Forwarding Context
  property_count: 0
  slug: event-forwarding-context
- class_count: 0
  name: Extension Context
  property_count: 0
  slug: extension-context
- class_count: 0
  name: Reactor Context
  property_count: 0
  slug: reactor-context
layout: provider
modified: '2026-04-18'
name: Adobe Launch
rules:
- name: Adobe Launch API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: adobe-launch-spectral-rules
skills: []
slug: adobe-launch
solutions: []
source_filename: apis.yml
source_yaml: "aid: adobe-launch\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/adobe-launch/refs/heads/main/apis.yml\nname: Adobe Launch\ndescription: >-\n  Adobe Launch, now known as Adobe Experience Platform Tags, is a\n  next-generation tag management system that unifies the client-side marketing\n  ecosystem by empowering developers to build integrations on a robust,\n  extensible platform that partners, clients, and the broader industry can\n  build on and contribute to.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - name: Adobe Launch Reactor API\n    description: >-\n      The Reactor API allows you to programmatically manage all resources for\n      Adobe Experience Platform Tags, including properties, data elements,\n      rules, extensions, library builds, and environments. It follows the JSON\n      API specification for request\
  \ and response formatting.\n    baseURL: https://reactor.adobe.io\n    humanURL: https://experienceleague.adobe.com/en/docs/experience-platform/tags/api/overview\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-corporate-logo.svg\n    tags:\n      - Automation\n      - Data Collection\n      - Marketing Technology\n      - Tag Management\n    properties:\n      - type: Documentation\n        url: https://experienceleague.adobe.com/en/docs/experience-platform/tags/api/overview\n      - type: APIReference\n        url: https://developer.adobe.com/experience-platform-apis/references/reactor/\n      - type: Authentication\n        url: https://experienceleague.adobe.com/en/docs/experience-platform/tags/api/getting-started\n      - type: GettingStarted\n        url: https://experienceleague.adobe.com/en/docs/experience-platform/tags/api/getting-started\n      - type: SDK\n        url: https://www.npmjs.com/package/@adobe/reactor-sdk\n      - type: ChangeLog\n        url: https://experienceleague.adobe.com/en/docs/experience-platform/release-notes/latest\n\
  \      - type: OpenAPI\n        url: openapi/reactor-api.yml\n      - type: JSONSchema\n        url: json-schema/property.json\n      - type: JSONSchema\n        url: json-schema/rule.json\n      - type: JSONSchema\n        url: json-schema/data-element.json\n      - type: JSONSchema\n        url: json-schema/extension.json\n      - type: JSONSchema\n        url: json-schema/library.json\n      - type: JSONSchema\n        url: json-schema/build.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n    contact:\n      - type: Support\n        url: https://experienceleague.adobe.com/?support-solution=Experience+Platform\n  - name: Adobe Launch Extension API\n    description: >-\n      API for developing custom extensions for Adobe Experience Platform Tags,\n      allowing developers to create integrations with third-party tools and\n      services. Extensions are the building blocks of tags and consist of\n      library modules and views.\n    baseURL: https://reactor.adobe.io\n\
  \    humanURL: https://experienceleague.adobe.com/en/docs/experience-platform/tags/extension-dev/overview\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-corporate-logo.svg\n    tags:\n      - Development\n      - Extensions\n      - Integrations\n      - Tag Management\n    properties:\n      - type: Documentation\n        url: https://experienceleague.adobe.com/en/docs/experience-platform/tags/extension-dev/overview\n      - type: SDK\n        url: https://www.npmjs.com/package/@adobe/reactor-scaffold\n      - type: SDK\n        url: https://www.npmjs.com/package/@adobe/reactor-sandbox\n      - type: OpenAPI\n        url: openapi/extension-api.yml\n      - type: JSONSchema\n        url: json-schema/extension.json\n      - type: JSONLD\n        url: json-ld/context.jsonld\n    contact:\n      - type: Support\n        url: https://experienceleague.adobe.com/?support-solution=Experience+Platform\n  - name: Adobe Experience Platform Event Forwarding API\n    description: >-\n\
  \      Event forwarding allows you to send collected event data to destinations\n      for server-side processing using the Adobe Experience Platform Edge\n      Network. It decreases web page weight by moving tasks from the client to\n      Adobe servers.\n    baseURL: https://reactor.adobe.io\n    humanURL: https://experienceleague.adobe.com/en/docs/experience-platform/tags/event-forwarding/overview\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-corporate-logo.svg\n    tags:\n      - Data Collection\n      - Edge Network\n      - Event Forwarding\n      - Server Side\n    properties:\n      - type: Documentation\n        url: https://experienceleague.adobe.com/en/docs/experience-platform/tags/event-forwarding/overview\n      - type: GettingStarted\n        url: https://experienceleague.adobe.com/en/docs/experience-platform/tags/event-forwarding/getting-started\n      - type: OpenAPI\n        url: openapi/event-forwarding-api.yml\n      - type: JSONLD\n        url: json-ld/context.jsonld\n\
  \    contact:\n      - type: Support\n        url: https://experienceleague.adobe.com/?support-solution=Experience+Platform\n  - name: Adobe Experience Platform Data Collection API\n    description: >-\n      The Data Collection APIs provide endpoints for sending data directly to\n      the Adobe Experience Platform Edge Network, including the Edge Network\n      API for authenticated and non-authenticated data ingestion and the Media\n      Edge API for media tracking data.\n    baseURL: https://edge.adobedc.net\n    humanURL: https://developer.adobe.com/data-collection-apis/docs/\n    image: https://www.adobe.com/content/dam/cc/icons/adobe-corporate-logo.svg\n    tags:\n      - Analytics\n      - Data Collection\n      - Data Ingestion\n      - Edge Network\n    properties:\n      - type: Documentation\n        url: https://developer.adobe.com/data-collection-apis/docs/\n      - type: GettingStarted\n        url: https://developer.adobe.com/data-collection-apis/docs/getting-started/\n\
  \      - type: Authentication\n        url: https://developer.adobe.com/data-collection-apis/docs/getting-started/authentication\n      - type: OpenAPI\n        url: openapi/data-collection-api.yml\n      - type: JSONLD\n        url: json-ld/context.jsonld\n    contact:\n      - type: Support\n        url: https://experienceleague.adobe.com/?support-solution=Experience+Platform\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: TermsOfService\n    url: https://www.adobe.com/legal/terms.html\n  - type: PrivacyPolicy\n    url: https://www.adobe.com/privacy.html\n  - type: Console\n    url: https://developer.adobe.com/developer-console/\n  - type: Portal\n    url: https://developer.adobe.com/\n  - type: StatusPage\n    url: https://status.adobe.com/\n  - type: Blog\n    url: https://medium.com/adobetech\n  - type: GitHubOrganization\n    url: https://github.com/adobe\n  - type: SignUp\n    url: https://developer.adobe.com/developer-console/\n  - type: Authentication\n\
  \    url: https://experienceleague.adobe.com/en/docs/experience-platform/landing/platform-apis/api-authentication\n  - type: ChangeLog\n    url: https://experienceleague.adobe.com/en/docs/experience-platform/release-notes/latest\n  - type: Features\n    url: https://experienceleague.adobe.com/en/docs/experience-platform/tags/home\n    data:\n      - Next-generation tag management for web and mobile\n      - Extensible platform with public extension marketplace\n      - Server-side event forwarding via Edge Network\n      - Rule-based data collection and routing\n      - Library versioning with staging and production environments\n      - JSON API specification-based programmatic management\n      - Real-time data collection to Edge Network\n      - Media tracking and analytics integration\n  - type: UseCases\n    url: https://experienceleague.adobe.com/en/docs/experience-platform/tags/home\n    data:\n      - Unified tag management across marketing tools\n      - Server-side event forwarding\
  \ for privacy compliance\n      - Custom extension development for third-party integrations\n      - Real-time data collection from web and mobile applications\n      - Media analytics tracking for video and audio content\n      - A/B testing and personalization data routing\n      - Cross-platform data collection orchestration\n  - type: Integrations\n    url: https://experienceleague.adobe.com/en/docs/experience-platform/tags/home\n    data:\n      - Adobe Analytics\n      - Adobe Target\n      - Adobe Audience Manager\n      - Adobe Experience Platform\n      - Google Analytics\n      - Facebook Pixel\n      - LinkedIn Insight Tag\n      - Custom JavaScript libraries\n      - Third-party marketing platforms\n  - type: SDK\n    url: https://www.npmjs.com/package/@adobe/reactor-sdk\n    description: Adobe Reactor SDK for Node.js\n  - type: SDK\n    url: https://www.npmjs.com/package/@adobe/reactor-scaffold\n    description: Adobe Reactor extension scaffold tool\n  - type: SDK\n    url:\
  \ https://www.npmjs.com/package/@adobe/reactor-sandbox\n    description: Adobe Reactor extension sandbox for local testing\ninclude:\n  - name: Adobe Experience Platform APIs\n    url: https://developer.adobe.com/experience-platform-apis/\ntags:\n  - Data Collection\n  - Edge Network\n  - Event Forwarding\n  - Marketing Technology\n  - Tag Management\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/adobe-launch/refs/heads/main/apis.yml
tags:
- Data Collection
- Edge Network
- Event Forwarding
- Marketing Technology
- Tag Management
url: https://raw.githubusercontent.com/api-evangelist/adobe-launch/refs/heads/main/apis.yml
use_cases:
- Unified tag management across marketing tools
- Server-side event forwarding for privacy compliance
- Custom extension development for third-party integrations
- Real-time data collection from web and mobile applications
- Media analytics tracking for video and audio content
- A/B testing and personalization data routing
- Cross-platform data collection orchestration
---
