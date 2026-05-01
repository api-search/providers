---
api_count: 11
apis:
- description: Create and manage ad campaigns, analyze performance, and automate advertising workflows.
  name: Facebook Marketing API
  slug: facebook-marketing-api
- description: Manage Facebook Pages, posts, comments, and engagement.
  name: Facebook Pages API
  slug: facebook-pages-api
- description: Send web and offline events directly to Facebook for improved tracking and attribution.
  name: Facebook Conversions API
  slug: ''
- description: Manage business assets including pixels, catalogs, and custom audiences.
  name: Facebook Business Asset API
  slug: ''
- description: Manage Instagram Business and Creator accounts through Business Manager.
  name: Facebook Instagram API
  slug: ''
- description: Access performance metrics and analytics data for Facebook Pages, ad campaigns, and content. The Insights API provides detailed reporting on engagement, reach, impressions, and audience demographics f
  name: Facebook Insights API
  slug: ''
- description: Build conversational experiences on the Messenger platform. The Messenger Platform API enables businesses to send and receive messages, create automated bots, manage customer interactions, and integra
  name: Facebook Messenger Platform API
  slug: ''
- description: Create and manage product catalogs for use in dynamic ads, shops, and commerce experiences across Meta platforms. The Catalog API allows businesses to upload product information, manage inventory feed
  name: Facebook Catalog API
  slug: ''
- description: Stream live video content directly to Facebook Pages, user profiles, and groups. The Live Video API enables scheduling broadcasts, managing live streams, interacting with audiences through comments, a
  name: Facebook Live Video API
  slug: ''
- description: Publish content, manage replies, and retrieve analytics on the Threads platform. The Threads API provides programmatic access for creating text posts, sharing media, managing conversations, and access
  name: Facebook Threads API
  slug: ''
- description: 'Send and receive messages, manage business profiles, and automate customer communications through the WhatsApp Business Platform. The Cloud API enables businesses to integrate WhatsApp messaging into '
  name: Facebook WhatsApp Business Platform API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://developers.facebook.com
- title: ''
  type: Developer Console
  url: https://developers.facebook.com/apps
- title: ''
  type: Business Manager
  url: https://business.facebook.com
- title: ''
  type: Support
  url: https://developers.facebook.com/support
- title: ''
  type: Status
  url: https://developers.facebook.com/status
- title: ''
  type: Terms of Service
  url: https://developers.facebook.com/terms
- title: ''
  type: Privacy Policy
  url: https://www.facebook.com/privacy/explanation
- title: ''
  type: Getting Started
  url: https://developers.facebook.com/docs/development/create-an-app
- title: ''
  type: Documentation
  url: https://developers.facebook.com/docs
- title: ''
  type: Authentication
  url: https://developers.facebook.com/docs/facebook-login/guides/access-tokens
- title: ''
  type: Rate Limits
  url: https://developers.facebook.com/docs/graph-api/overview/rate-limiting
- title: ''
  type: Change Log
  url: https://developers.facebook.com/docs/graph-api/changelog
- title: ''
  type: Blog
  url: https://developers.meta.com/blog/
- title: ''
  type: Website
  url: https://www.meta.com
- title: ''
  type: Sign Up
  url: https://developers.facebook.com/async/registration/
- title: ''
  type: SDKs
  url: https://developers.facebook.com/docs/business-sdk/getting-started
- title: ''
  type: GitHub Organization
  url: https://github.com/facebook
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/facebook-graph-api
- title: ''
  type: Community
  url: https://developers.facebook.com/community
- title: ''
  type: Developer Tools
  url: https://developers.facebook.com/tools/explorer
created: '2024-01-01'
description: APIs for managing Facebook Business accounts, advertising, pages, and assets across the Meta platform family. Facebook Business Manager exposes a deep catalog of Graph API surfaces for marketing, pages, conversions, business asset management, Instagram, insights, Messenger, catalogs, live video, Threads, and the WhatsApp Business Platform, all governed through a shared authentication and access model.
features: []
image: https://www.facebook.com/images/fb_icon_325x325.png
integrations: []
layout: provider
modified: '2026-04-28'
name: Facebook Business Manager
skills: []
slug: facebook-business-manager
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: facebook-business-manager\nname: Facebook Business Manager\ndescription: >-\n  APIs for managing Facebook Business accounts, advertising, pages, and assets\n  across the Meta platform family. Facebook Business Manager exposes a deep\n  catalog of Graph API surfaces for marketing, pages, conversions, business\n  asset management, Instagram, insights, Messenger, catalogs, live video,\n  Threads, and the WhatsApp Business Platform, all governed through a shared\n  authentication and access model.\nimage: https://www.facebook.com/images/fb_icon_325x325.png\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/facebook-business-manager/refs/heads/main/apis.yml\napis:\n  - aid: facebook-business-manager:facebook-marketing-api\n    name: Facebook Marketing API\n    description: >-\n      Create and manage ad campaigns, analyze performance, and\
  \ automate advertising\n      workflows.\n    image: https://www.facebook.com/images/fb_icon_325x325.png\n    humanURL: https://developers.facebook.com/docs/marketing-apis\n    baseURL: https://graph.facebook.com/v18.0\n    tags:\n      - Ads\n      - Advertising\n      - Campaigns\n      - Marketing\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/marketing-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/facebook-business-manager/refs/heads/main/openapi/facebook-marketing-openapi.yml\n      - type: Authentication\n        url: https://developers.facebook.com/docs/marketing-api/authentication\n      - type: Change Log\n        url: https://developers.facebook.com/docs/graph-api/changelog\n      - type: Rate Limits\n        url: https://developers.facebook.com/docs/graph-api/overview/rate-limiting\n      - type: Getting Started\n        url: https://developers.facebook.com/docs/marketing-api/get-started\n\
  \      - type: Reference\n        url: https://developers.facebook.com/docs/marketing-api/reference\n      - type: SDKs\n        url: https://developers.facebook.com/docs/business-sdk/getting-started\n  - aid: facebook-business-manager:facebook-pages-api\n    name: Facebook Pages API\n    description: >-\n      Manage Facebook Pages, posts, comments, and engagement.\n    image: https://www.facebook.com/images/fb_icon_325x325.png\n    humanURL: https://developers.facebook.com/docs/pages\n    baseURL: https://graph.facebook.com/v18.0\n    tags:\n      - Content\n      - Pages\n      - Publishing\n      - Social Media\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/pages-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/facebook-business-manager/refs/heads/main/openapi/facebook-pages-openapi.yml\n      - type: Getting Started\n        url: https://developers.facebook.com/docs/pages/getting-started\n\
  \      - type: Reference\n        url: https://developers.facebook.com/docs/pages-api/overview\n      - type: Authentication\n        url: https://developers.facebook.com/docs/pages/access-tokens\n  - name: Facebook Conversions API\n    description: >-\n      Send web and offline events directly to Facebook for improved tracking and attribution.\n    image: https://www.facebook.com/images/fb_icon_325x325.png\n    humanURL: https://developers.facebook.com/docs/marketing-api/conversions-api\n    baseURL: https://graph.facebook.com/v18.0\n    tags:\n      - Attribution\n      - Conversions\n      - Events\n      - Tracking\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/marketing-api/conversions-api\n      - type: Implementation Guide\n        url: https://developers.facebook.com/docs/marketing-api/conversions-api/get-started\n      - type: Reference\n        url: https://developers.facebook.com/docs/marketing-api/conversions-api/parameters\n\
  \      - type: SDKs\n        url: https://developers.facebook.com/docs/marketing-api/conversions-api/using-the-api\n  - name: Facebook Business Asset API\n    description: >-\n      Manage business assets including pixels, catalogs, and custom audiences.\n    image: https://www.facebook.com/images/fb_icon_325x325.png\n    humanURL: https://developers.facebook.com/docs/marketing-api/business-asset-management\n    baseURL: https://graph.facebook.com/v18.0\n    tags:\n      - Assets\n      - Audiences\n      - Catalogs\n      - Pixels\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/marketing-api/business-asset-management\n      - type: Reference\n        url: https://developers.facebook.com/docs/marketing-api/business-asset-management/get-started\n  - name: Facebook Instagram API\n    description: >-\n      Manage Instagram Business and Creator accounts through Business Manager.\n    image: https://www.facebook.com/images/fb_icon_325x325.png\n\
  \    humanURL: https://developers.facebook.com/docs/instagram-api\n    baseURL: https://graph.facebook.com/v18.0\n    tags:\n      - Content\n      - Instagram\n      - Media\n      - Social Media\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/instagram-api\n      - type: Getting Started\n        url: https://developers.facebook.com/docs/instagram-api/getting-started\n      - type: Reference\n        url: https://developers.facebook.com/docs/instagram-api/reference\n      - type: Authentication\n        url: https://developers.facebook.com/docs/instagram-api/getting-started#authentication\n  - name: Facebook Insights API\n    description: >-\n      Access performance metrics and analytics data for Facebook Pages, ad\n      campaigns, and content. The Insights API provides detailed reporting on\n      engagement, reach, impressions, and audience demographics for businesses\n      managing their Meta presence.\n    image: https://www.facebook.com/images/fb_icon_325x325.png\n\
  \    humanURL: https://developers.facebook.com/docs/platforminsights\n    baseURL: https://graph.facebook.com/v25.0\n    tags:\n      - Analytics\n      - Insights\n      - Metrics\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/platforminsights\n      - type: Reference\n        url: https://developers.facebook.com/docs/graph-api/reference/page/insights\n  - name: Facebook Messenger Platform API\n    description: >-\n      Build conversational experiences on the Messenger platform. The Messenger\n      Platform API enables businesses to send and receive messages, create\n      automated bots, manage customer interactions, and integrate rich media\n      and quick replies into chat workflows.\n    image: https://www.facebook.com/images/fb_icon_325x325.png\n    humanURL: https://developers.facebook.com/docs/messenger-platform\n    baseURL: https://graph.facebook.com/v25.0\n    tags:\n      - Bots\n      - Chat\n      - Customer\
  \ Service\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/messenger-platform\n      - type: Getting Started\n        url: https://developers.facebook.com/docs/messenger-platform/getting-started\n      - type: Reference\n        url: https://developers.facebook.com/docs/messenger-platform/reference\n  - name: Facebook Catalog API\n    description: >-\n      Create and manage product catalogs for use in dynamic ads, shops, and\n      commerce experiences across Meta platforms. The Catalog API allows\n      businesses to upload product information, manage inventory feeds, and\n      synchronize product data for advertising and shopping features.\n    image: https://www.facebook.com/images/fb_icon_325x325.png\n    humanURL: https://developers.facebook.com/docs/marketing-api/catalog\n    baseURL: https://graph.facebook.com/v25.0\n    tags:\n      - Catalogs\n      - Commerce\n      - Products\n      - Shopping\n    properties:\n\
  \      - type: Documentation\n        url: https://developers.facebook.com/docs/marketing-api/catalog\n      - type: Reference\n        url: https://developers.facebook.com/docs/marketing-api/catalog/reference\n      - type: Getting Started\n        url: https://developers.facebook.com/docs/marketing-api/catalog/get-started\n  - name: Facebook Live Video API\n    description: >-\n      Stream live video content directly to Facebook Pages, user profiles, and\n      groups. The Live Video API enables scheduling broadcasts, managing live\n      streams, interacting with audiences through comments, and retrieving\n      post-broadcast analytics.\n    image: https://www.facebook.com/images/fb_icon_325x325.png\n    humanURL: https://developers.facebook.com/docs/videos/live-video\n    baseURL: https://graph.facebook.com/v25.0\n    tags:\n      - Broadcasting\n      - Live Streaming\n      - Media\n      - Video\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/videos/live-video\n\
  \      - type: Reference\n        url: https://developers.facebook.com/docs/graph-api/reference/live-video\n      - type: Getting Started\n        url: https://developers.facebook.com/docs/videos/live-video/getting-started\n  - name: Facebook Threads API\n    description: >-\n      Publish content, manage replies, and retrieve analytics on the Threads\n      platform. The Threads API provides programmatic access for creating text\n      posts, sharing media, managing conversations, and accessing engagement\n      metrics for Threads profiles.\n    image: https://www.facebook.com/images/fb_icon_325x325.png\n    humanURL: https://developers.facebook.com/docs/threads\n    baseURL: https://graph.threads.net/v25.0\n    tags:\n      - Content\n      - Publishing\n      - Social Media\n      - Threads\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/threads\n      - type: Getting Started\n        url: https://developers.facebook.com/docs/threads/get-started\n\
  \      - type: Reference\n        url: https://developers.facebook.com/docs/threads/threads-api\n  - name: Facebook WhatsApp Business Platform API\n    description: >-\n      Send and receive messages, manage business profiles, and automate customer\n      communications through the WhatsApp Business Platform. The Cloud API\n      enables businesses to integrate WhatsApp messaging into their applications\n      for customer support, notifications, and transactional communications.\n    image: https://www.facebook.com/images/fb_icon_325x325.png\n    humanURL: https://developers.facebook.com/docs/whatsapp\n    baseURL: https://graph.facebook.com/v25.0\n    tags:\n      - Customer Service\n      - Messaging\n      - Notifications\n      - WhatsApp\n    properties:\n      - type: Documentation\n        url: https://developers.facebook.com/docs/whatsapp/cloud-api\n      - type: Getting Started\n        url: https://developers.facebook.com/docs/whatsapp/cloud-api/get-started\n      - type: Reference\n\
  \        url: https://developers.facebook.com/docs/whatsapp/cloud-api/reference\ncommon:\n  - type: Portal\n    url: https://developers.facebook.com\n  - type: Developer Console\n    url: https://developers.facebook.com/apps\n  - type: Business Manager\n    url: https://business.facebook.com\n  - type: Support\n    url: https://developers.facebook.com/support\n  - type: Status\n    url: https://developers.facebook.com/status\n  - type: Terms of Service\n    url: https://developers.facebook.com/terms\n  - type: Privacy Policy\n    url: https://www.facebook.com/privacy/explanation\n  - type: Getting Started\n    url: https://developers.facebook.com/docs/development/create-an-app\n  - type: Documentation\n    url: https://developers.facebook.com/docs\n  - type: Authentication\n    url: https://developers.facebook.com/docs/facebook-login/guides/access-tokens\n  - type: Rate Limits\n    url: https://developers.facebook.com/docs/graph-api/overview/rate-limiting\n  - type: Change Log\n    url:\
  \ https://developers.facebook.com/docs/graph-api/changelog\n  - type: Blog\n    url: https://developers.meta.com/blog/\n  - type: Website\n    url: https://www.meta.com\n  - type: Sign Up\n    url: https://developers.facebook.com/async/registration/\n  - type: SDKs\n    url: https://developers.facebook.com/docs/business-sdk/getting-started\n  - type: GitHub Organization\n    url: https://github.com/facebook\n  - type: Stack Overflow\n    url: https://stackoverflow.com/questions/tagged/facebook-graph-api\n  - type: Community\n    url: https://developers.facebook.com/community\n  - type: Developer Tools\n    url: https://developers.facebook.com/tools/explorer\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Advertising\n  - Analytics\n  - Business Management\n  - Marketing\n  - Social Media\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/facebook-business-manager/refs/heads/main/apis.yml
tags:
- Advertising
- Analytics
- Business Management
- Marketing
- Social Media
url: https://raw.githubusercontent.com/api-evangelist/facebook-business-manager/refs/heads/main/apis.yml
use_cases: []
---
