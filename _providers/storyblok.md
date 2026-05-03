---
api_count: 4
api_specs:
- filename: storyblok-content-delivery-api-v2-openapi.yml
  format: yaml
  label: Storyblok Content Delivery API
  slug: storyblok-content-delivery-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-content-delivery-api-v2-openapi.yml
- filename: storyblok-management-api-openapi.yml
  format: yaml
  label: Storyblok Management API
  slug: storyblok-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-management-api-openapi.yml
- filename: storyblok-image-service-openapi.yml
  format: yaml
  label: Storyblok Image Service
  slug: storyblok-image-service
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-image-service-openapi.yml
- filename: storyblok-webhooks-asyncapi.yml
  format: yaml
  label: Storyblok Webhooks
  slug: storyblok-webhooks
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/asyncapi/storyblok-webhooks-asyncapi.yml
apis:
- description: The Storyblok Content Delivery API v2 enables developers to fetch published content from a Storyblok space for delivery to web, mobile, and other channels. Provides access to stories, datasources, lin
  name: Storyblok Content Delivery API
  slug: storyblok-content-delivery-api
- description: The Storyblok Management API is a REST API for programmatically creating, reading, updating, and deleting content and configuration within a Storyblok space. Supports managing stories, components, ass
  name: Storyblok Management API
  slug: storyblok-management-api
- description: The Storyblok Image Service provides on-the-fly image resizing, cropping, filtering, and format conversion for assets stored in Storyblok. Supports fit-in resizing, smart cropping, focus-point-based c
  name: Storyblok Image Service
  slug: storyblok-image-service
- description: Storyblok emits webhook events when content actions occur in a space such as story publication, unpublication, deletion, asset upload, and pipeline stage transitions. AsyncAPI specification for webhoo
  name: Storyblok Webhooks
  slug: storyblok-webhooks
asyncapis:
- description: The Storyblok Webhook system delivers real-time event notifications to registered HTTP endpoints when content events occur in a Storyblok space. Events are triggered by actions such as story publicati
  name: Storyblok Webhooks
  slug: storyblok-webhooks-asyncapi
capabilities:
- description: Unified capability for managing and delivering Storyblok headless CMS content. Combines the Content Delivery API for fetching published content and the Management API for creating, editing, and publis
  name: Storyblok Content Management
  slug: content-management
common:
- title: ''
  type: Portal
  url: https://www.storyblok.com/
- title: ''
  type: Documentation
  url: https://www.storyblok.com/docs
- title: ''
  type: Pricing
  url: https://www.storyblok.com/pricing
- title: ''
  type: Blog
  url: https://www.storyblok.com/blog
- title: ''
  type: About
  url: https://www.storyblok.com/about
- title: ''
  type: Changelog
  url: https://www.storyblok.com/changelog
- title: ''
  type: CaseStudies
  url: https://www.storyblok.com/customer-stories
- title: ''
  type: Contact
  url: https://www.storyblok.com/contact
- title: ''
  type: Status
  url: https://status.storyblok.com/
- title: ''
  type: Support
  url: https://www.storyblok.com/support
- title: ''
  type: PrivacyPolicy
  url: https://www.storyblok.com/legal/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.storyblok.com/legal/terms-of-service
- title: ''
  type: Sign Up
  url: https://app.storyblok.com/#!/signup
- title: ''
  type: Login
  url: https://app.storyblok.com/
- title: ''
  type: GitHubOrg
  url: https://github.com/storyblok
- title: ''
  type: SDK
  url: https://www.storyblok.com/technologies
created: '2026-05-02'
description: Storyblok is a headless content management system (CMS) with a visual editor that enables developers and content editors to collaboratively build and manage digital experiences. It provides APIs for content delivery, content management, image optimization, and webhook-based event notifications. Storyblok supports composable content through reusable components, multi-language content, and multi-site management with real-time collaboration features.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Storyblok Context
  property_count: 10
  slug: storyblok-context
layout: provider
modified: '2026-05-02'
name: Storyblok
rules:
- name: Storyblok API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 6
  slug: storyblok-rules
skills: []
slug: storyblok
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: storyblok\nname: Storyblok\ndescription: >-\n  Storyblok is a headless content management system (CMS) with a visual editor\n  that enables developers and content editors to collaboratively build and manage\n  digital experiences. It provides APIs for content delivery, content management,\n  image optimization, and webhook-based event notifications. Storyblok supports\n  composable content through reusable components, multi-language content, and\n  multi-site management with real-time collaboration features.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CMS\n  - Content Delivery\n  - Content Management\n  - Headless CMS\n  - Image Optimization\n  - REST API\n  - Visual Editor\n  - Webhooks\ncreated: '2026-05-02'\nmodified: '2026-05-02'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  -\
  \ aid: storyblok:storyblok-content-delivery-api\n    name: Storyblok Content Delivery API\n    description: >-\n      The Storyblok Content Delivery API v2 enables developers to fetch\n      published content from a Storyblok space for delivery to web, mobile,\n      and other channels. Provides access to stories, datasources, links, tags,\n      and asset metadata with filtering, pagination, and relation resolution.\n      Available across multiple regional endpoints for global low-latency delivery.\n    humanURL: https://www.storyblok.com/docs/api/content-delivery/v2\n    baseURL: https://api.storyblok.com/v2/cdn\n    tags:\n      - Content Delivery\n      - Headless CMS\n      - REST API\n      - Stories\n    properties:\n      - type: Documentation\n        url: https://www.storyblok.com/docs/api/content-delivery/v2\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-content-delivery-api-v2-openapi.yml\n\
  \  - aid: storyblok:storyblok-management-api\n    name: Storyblok Management API\n    description: >-\n      The Storyblok Management API is a REST API for programmatically creating,\n      reading, updating, and deleting content and configuration within a\n      Storyblok space. Supports managing stories, components, assets,\n      datasources, collaborators, webhooks, and space settings. Used for\n      editorial tooling, content migration, CI/CD pipelines, and automated\n      publishing workflows.\n    humanURL: https://www.storyblok.com/docs/api/management\n    baseURL: https://mapi.storyblok.com/v1\n    tags:\n      - Assets\n      - CMS\n      - Components\n      - Content Management\n      - REST API\n      - Stories\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://www.storyblok.com/docs/api/management\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-management-api-openapi.yml\n\
  \  - aid: storyblok:storyblok-image-service\n    name: Storyblok Image Service\n    description: >-\n      The Storyblok Image Service provides on-the-fly image resizing, cropping,\n      filtering, and format conversion for assets stored in Storyblok. Supports\n      fit-in resizing, smart cropping, focus-point-based cropping, and custom\n      filter chains for quality adjustment, grayscale, and blur effects.\n    humanURL: https://www.storyblok.com/docs/image-service\n    baseURL: https://a.storyblok.com\n    tags:\n      - Image Optimization\n      - Image Processing\n      - Media\n    properties:\n      - type: Documentation\n        url: https://www.storyblok.com/docs/image-service\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/openapi/storyblok-image-service-openapi.yml\n  - aid: storyblok:storyblok-webhooks\n    name: Storyblok Webhooks\n    description: >-\n      Storyblok emits webhook events when\
  \ content actions occur in a space such\n      as story publication, unpublication, deletion, asset upload, and pipeline\n      stage transitions. AsyncAPI specification for webhook event schemas.\n    humanURL: https://www.storyblok.com/docs/guide/in-depth/webhooks\n    tags:\n      - AsyncAPI\n      - Events\n      - Real-Time\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://www.storyblok.com/docs/guide/in-depth/webhooks\n      - type: AsyncAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/asyncapi/storyblok-webhooks-asyncapi.yml\ncommon:\n  - type: Portal\n    url: https://www.storyblok.com/\n  - type: Documentation\n    url: https://www.storyblok.com/docs\n  - type: Pricing\n    url: https://www.storyblok.com/pricing\n  - type: Blog\n    url: https://www.storyblok.com/blog\n  - type: About\n    url: https://www.storyblok.com/about\n  - type: Changelog\n    url: https://www.storyblok.com/changelog\n\
  \  - type: CaseStudies\n    url: https://www.storyblok.com/customer-stories\n  - type: Contact\n    url: https://www.storyblok.com/contact\n  - type: Status\n    url: https://status.storyblok.com/\n  - type: Support\n    url: https://www.storyblok.com/support\n  - type: PrivacyPolicy\n    url: https://www.storyblok.com/legal/privacy-policy\n  - type: TermsOfService\n    url: https://www.storyblok.com/legal/terms-of-service\n  - type: Sign Up\n    url: https://app.storyblok.com/#!/signup\n  - type: Login\n    url: https://app.storyblok.com/\n  - type: GitHubOrg\n    url: https://github.com/storyblok\n  - type: SDK\n    url: https://www.storyblok.com/technologies\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/apis.yml
tags:
- CMS
- Content Delivery
- Content Management
- Headless CMS
- Image Optimization
- REST API
- Visual Editor
- Webhooks
url: https://raw.githubusercontent.com/api-evangelist/storyblok/refs/heads/main/apis.yml
use_cases: []
---
