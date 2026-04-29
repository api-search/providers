---
api_count: 6
api_specs:
- filename: facebook-graph-api.yaml
  format: yaml
  label: Facebook Graph API
  slug: facebook-graph-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-graph-api.yaml
- filename: facebook-marketing-api.yaml
  format: yaml
  label: Facebook Marketing API
  slug: facebook-marketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-marketing-api.yaml
- filename: facebook-instagram-api.yaml
  format: yaml
  label: Instagram API
  slug: instagram-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-instagram-api.yaml
- filename: facebook-messenger-api.yaml
  format: yaml
  label: Messenger Platform API
  slug: messenger-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-messenger-api.yaml
- filename: facebook-threads-api.yaml
  format: yaml
  label: Threads API
  slug: threads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-threads-api.yaml
- filename: facebook-whatsapp-api.yaml
  format: yaml
  label: WhatsApp Business API
  slug: whatsapp-business-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/openapi/facebook-whatsapp-api.yaml
apis:
- description: The primary way to read and write data to the Facebook social graph, providing access to user profiles, posts, pages, photos, videos, comments, and social interactions. Supports nodes, edges, and fiel
  name: Facebook Graph API
  slug: facebook-graph-api
- description: Programmatically manage Facebook ad campaigns, ad sets, ad creatives, Custom Audiences, and advertising reports. Access performance insights and automate campaign optimization at scale.
  name: Facebook Marketing API
  slug: facebook-marketing-api
- description: Manage Instagram Business and Creator account content including publishing media, retrieving posts, managing comments, discovering mentions, and accessing account insights for analytics.
  name: Instagram API
  slug: instagram-api
- description: Build messaging experiences on Facebook Messenger and Instagram Direct. Send and receive messages, create bot interactions, use templates and webviews, manage conversation routing, and integrate NLP c
  name: Messenger Platform API
  slug: messenger-platform-api
- description: Publish and manage content on Threads, Meta's text-based social platform. Create posts and carousels, retrieve and moderate replies, access insights, and manage creator profiles at scale.
  name: Threads API
  slug: threads-api
- description: Send and receive messages through WhatsApp Business Platform. Support text, media, templates, interactive messages, and manage business profiles for customer communication at scale.
  name: WhatsApp Business API
  slug: whatsapp-business-api
capabilities:
- description: Workflow capability for managing advertising campaigns across Facebook and Instagram. Combines Marketing API for campaign management with Graph API for content insights and Instagram API for visual ad
  name: Facebook Advertising and Marketing
  slug: advertising-and-marketing
- description: Workflow capability for customer messaging across Messenger and WhatsApp. Combines Messenger Platform API for Facebook/Instagram messaging with WhatsApp Business API for business communication. Used b
  name: Facebook Messaging and Communication
  slug: messaging-and-communication
- description: Workflow capability for managing content across Facebook, Instagram, and Threads. Combines Graph API for Facebook posts, Instagram API for visual content, and Threads API for text-based publishing. Us
  name: Facebook Social Media Management
  slug: social-media-management
common:
- title: ''
  type: Portal
  url: https://developers.facebook.com
- title: ''
  type: GettingStarted
  url: https://developers.facebook.com/docs/development/create-an-app
- title: ''
  type: ChangeLog
  url: https://developers.facebook.com/docs/graph-api/changelog
- title: ''
  type: StatusPage
  url: https://developers.facebook.com/status
- title: ''
  type: TermsOfService
  url: https://developers.facebook.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://developers.facebook.com/policy
- title: ''
  type: RateLimits
  url: https://developers.facebook.com/docs/graph-api/overview/rate-limiting
- title: ''
  type: GitHubOrganization
  url: https://github.com/facebook
- title: ''
  type: Blog
  url: https://developers.facebook.com/blog
- title: ''
  type: Support
  url: https://developers.facebook.com/support
- title: ''
  type: FAQ
  url: https://developers.facebook.com/docs/development/faq
- title: ''
  type: Errors
  url: https://developers.facebook.com/docs/graph-api/guides/error-handling
- title: ''
  type: SpectralRules
  url: rules/facebook-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/facebook-vocabulary.yaml
- title: Social Media Management
  type: NaftikoCapability
  url: capabilities/social-media-management.yaml
- title: Advertising and Marketing
  type: NaftikoCapability
  url: capabilities/advertising-and-marketing.yaml
- title: Messaging and Communication
  type: NaftikoCapability
  url: capabilities/messaging-and-communication.yaml
created: '2024-01-15'
description: Facebook is Meta's social networking platform providing APIs for developers to integrate with Facebook's ecosystem. The Facebook Graph API is the primary way to read and write data to the Facebook social graph. Meta also provides APIs for marketing and advertising, Instagram content management, Messenger bots, Threads publishing, and WhatsApp business messaging.
features:
- description: HTTP-based API for reading and writing to the Facebook social graph with nodes, edges, and fields.
  name: Graph API
- description: Real-time notifications when changes occur to data your app has access to.
  name: Webhooks
- description: Send multiple API calls in a single HTTP request for improved performance.
  name: Batch Requests
- description: OAuth 2.0 access tokens for user, page, app, and client authentication flows.
  name: Access Tokens
- description: Authentication system allowing users to log into apps with their Facebook credentials.
  name: Facebook Login
- description: Analytics tool for measuring ad effectiveness and tracking website visitor actions.
  name: Meta Pixel
- description: Server-side event tracking for ad measurement without browser dependencies.
  name: Conversions API
image: /assets/icons/facebook.png
integrations:
- description: Connect Shopify stores with Facebook and Instagram shops for social commerce.
  name: Shopify
- description: Facebook social plugins and login integration for WordPress sites.
  name: WordPress
- description: Sync Facebook lead ads and audiences with Salesforce CRM.
  name: Salesforce
- description: Connect Facebook advertising and messaging with HubSpot marketing automation.
  name: HubSpot
- description: Automate workflows between Facebook and thousands of other apps.
  name: Zapier
jsonld:
- class_count: 5
  name: Facebook Graph Api Context
  property_count: 14
  slug: facebook-graph-api-context
- class_count: 3
  name: Facebook Instagram Api Context
  property_count: 11
  slug: facebook-instagram-api-context
- class_count: 6
  name: Facebook Marketing Api Context
  property_count: 14
  slug: facebook-marketing-api-context
layout: provider
modified: '2026-04-18'
name: Facebook
rules:
- name: Facebook API Rules
  rule_count: 30
  severity_counts:
    error: 13
    hint: 0
    info: 5
    warn: 12
  slug: facebook-spectral-rules
skills: []
slug: facebook
solutions: []
source_filename: apis.yml
source_yaml: "aid: facebook\nname: Facebook\ndescription: >-\n  Facebook is Meta's social networking platform providing APIs for developers to\n  integrate with Facebook's ecosystem. The Facebook Graph API is the primary way\n  to read and write data to the Facebook social graph. Meta also provides APIs\n  for marketing and advertising, Instagram content management, Messenger bots,\n  Threads publishing, and WhatsApp business messaging.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Advertising\n  - Content Publishing\n  - Messaging\n  - Social Media\n  - Social Networking\nurl: https://developers.facebook.com\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\nposition: Consumer\naccess: 3rd-Party\napis:\n  - aid: facebook:facebook-graph-api\n    name: Facebook Graph API\n    description: >-\n      The primary way to read and write data to the Facebook social graph,\n      providing access to user profiles,\
  \ posts, pages, photos, videos, comments,\n      and social interactions. Supports nodes, edges, and fields for flexible\n      data access.\n    humanURL: https://developers.facebook.com/docs/graph-api\n    baseURL: https://graph.facebook.com\n    tags:\n      - Comments\n      - Graph\n      - Pages\n      - Photos\n      - Posts\n      - Social\n      - Users\n      - Videos\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/graph-api/overview\n      - type: APIReference\n        url: https://developers.facebook.com/docs/graph-api/reference\n      - type: Authentication\n        url: https://developers.facebook.com/docs/facebook-login/access-tokens\n      - type: OpenAPI\n        url: openapi/facebook-graph-api.yaml\n  - aid: facebook:facebook-marketing-api\n    name: Facebook Marketing API\n    description: >-\n      Programmatically manage Facebook ad campaigns, ad sets, ad creatives,\n      Custom Audiences, and advertising reports. Access\
  \ performance insights and\n      automate campaign optimization at scale.\n    humanURL: https://developers.facebook.com/docs/marketing-apis\n    baseURL: https://graph.facebook.com\n    tags:\n      - Ad Campaigns\n      - Advertising\n      - Audiences\n      - Insights\n      - Marketing\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/marketing-api\n      - type: APIReference\n        url: https://developers.facebook.com/docs/marketing-api/reference\n      - type: OpenAPI\n        url: openapi/facebook-marketing-api.yaml\n  - aid: facebook:instagram-api\n    name: Instagram API\n    description: >-\n      Manage Instagram Business and Creator account content including publishing\n      media, retrieving posts, managing comments, discovering mentions, and\n      accessing account insights for analytics.\n    humanURL: https://developers.facebook.com/docs/instagram-platform\n    baseURL: https://graph.facebook.com\n    tags:\n      - Content\
  \ Management\n      - Instagram\n      - Media\n      - Social Media\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/instagram-platform\n      - type: OpenAPI\n        url: openapi/facebook-instagram-api.yaml\n  - aid: facebook:messenger-platform-api\n    name: Messenger Platform API\n    description: >-\n      Build messaging experiences on Facebook Messenger and Instagram Direct.\n      Send and receive messages, create bot interactions, use templates and\n      webviews, manage conversation routing, and integrate NLP capabilities.\n    humanURL: https://developers.facebook.com/docs/messenger-platform\n    baseURL: https://graph.facebook.com\n    tags:\n      - Bots\n      - Chat\n      - Messaging\n      - Messenger\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/messenger-platform\n      - type: OpenAPI\n        url: openapi/facebook-messenger-api.yaml\n  - aid: facebook:threads-api\n\
  \    name: Threads API\n    description: >-\n      Publish and manage content on Threads, Meta's text-based social platform.\n      Create posts and carousels, retrieve and moderate replies, access insights,\n      and manage creator profiles at scale.\n    humanURL: https://developers.facebook.com/docs/threads\n    baseURL: https://graph.threads.net\n    tags:\n      - Content Publishing\n      - Social Media\n      - Threads\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/threads\n      - type: OpenAPI\n        url: openapi/facebook-threads-api.yaml\n  - aid: facebook:whatsapp-business-api\n    name: WhatsApp Business API\n    description: >-\n      Send and receive messages through WhatsApp Business Platform. Support\n      text, media, templates, interactive messages, and manage business profiles\n      for customer communication at scale.\n    humanURL: https://developers.facebook.com/docs/whatsapp\n    baseURL: https://graph.facebook.com\n\
  \    tags:\n      - Business Messaging\n      - Customer Communication\n      - WhatsApp\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/whatsapp\n      - type: OpenAPI\n        url: openapi/facebook-whatsapp-api.yaml\ncommon:\n  - type: Portal\n    url: https://developers.facebook.com\n  - type: GettingStarted\n    url: https://developers.facebook.com/docs/development/create-an-app\n  - type: ChangeLog\n    url: https://developers.facebook.com/docs/graph-api/changelog\n  - type: StatusPage\n    url: https://developers.facebook.com/status\n  - type: TermsOfService\n    url: https://developers.facebook.com/terms\n  - type: PrivacyPolicy\n    url: https://developers.facebook.com/policy\n  - type: RateLimits\n    url: https://developers.facebook.com/docs/graph-api/overview/rate-limiting\n  - type: GitHubOrganization\n    url: https://github.com/facebook\n  - type: Blog\n    url: https://developers.facebook.com/blog\n  - type: Support\n    url:\
  \ https://developers.facebook.com/support\n  - type: FAQ\n    url: https://developers.facebook.com/docs/development/faq\n  - type: Errors\n    url: https://developers.facebook.com/docs/graph-api/guides/error-handling\n  - type: Features\n    data:\n      - name: Graph API\n        description: >-\n          HTTP-based API for reading and writing to the Facebook social graph\n          with nodes, edges, and fields.\n      - name: Webhooks\n        description: >-\n          Real-time notifications when changes occur to data your app has access\n          to.\n      - name: Batch Requests\n        description: >-\n          Send multiple API calls in a single HTTP request for improved\n          performance.\n      - name: Access Tokens\n        description: >-\n          OAuth 2.0 access tokens for user, page, app, and client authentication\n          flows.\n      - name: Facebook Login\n        description: >-\n          Authentication system allowing users to log into apps with their\n\
  \          Facebook credentials.\n      - name: Meta Pixel\n        description: >-\n          Analytics tool for measuring ad effectiveness and tracking website\n          visitor actions.\n      - name: Conversions API\n        description: >-\n          Server-side event tracking for ad measurement without browser\n          dependencies.\n  - type: UseCases\n    data:\n      - name: Social Media Management\n        description: >-\n          Manage pages, publish content, and engage with audiences across\n          Facebook and Instagram.\n      - name: Advertising Automation\n        description: >-\n          Automate ad campaign creation, optimization, and reporting at scale.\n      - name: Customer Messaging\n        description: >-\n          Build conversational experiences on Messenger and WhatsApp for customer\n          support and engagement.\n      - name: Content Publishing\n        description: >-\n          Publish and schedule content across Facebook, Instagram, and\
  \ Threads\n          platforms.\n      - name: Analytics and Insights\n        description: >-\n          Access performance data and audience insights across Meta platforms.\n      - name: E-Commerce Integration\n        description: >-\n          Integrate product catalogs and shopping experiences with Facebook and\n          Instagram shops.\n  - type: Integrations\n    data:\n      - name: Shopify\n        description: >-\n          Connect Shopify stores with Facebook and Instagram shops for social\n          commerce.\n      - name: WordPress\n        description: >-\n          Facebook social plugins and login integration for WordPress sites.\n      - name: Salesforce\n        description: >-\n          Sync Facebook lead ads and audiences with Salesforce CRM.\n      - name: HubSpot\n        description: >-\n          Connect Facebook advertising and messaging with HubSpot marketing\n          automation.\n      - name: Zapier\n        description: >-\n          Automate workflows\
  \ between Facebook and thousands of other apps.\n  - type: SpectralRules\n    url: rules/facebook-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/facebook-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/social-media-management.yaml\n    title: Social Media Management\n  - type: NaftikoCapability\n    url: capabilities/advertising-and-marketing.yaml\n    title: Advertising and Marketing\n  - type: NaftikoCapability\n    url: capabilities/messaging-and-communication.yaml\n    title: Messaging and Communication\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/apis.yml
tags:
- Advertising
- Content Publishing
- Messaging
- Social Media
- Social Networking
url: https://developers.facebook.com
use_cases:
- description: Manage pages, publish content, and engage with audiences across Facebook and Instagram.
  name: Social Media Management
- description: Automate ad campaign creation, optimization, and reporting at scale.
  name: Advertising Automation
- description: Build conversational experiences on Messenger and WhatsApp for customer support and engagement.
  name: Customer Messaging
- description: Publish and schedule content across Facebook, Instagram, and Threads platforms.
  name: Content Publishing
- description: Access performance data and audience insights across Meta platforms.
  name: Analytics and Insights
- description: Integrate product catalogs and shopping experiences with Facebook and Instagram shops.
  name: E-Commerce Integration
---
