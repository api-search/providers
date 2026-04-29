---
api_count: 4
api_specs:
- filename: instagram-graph-api.yaml
  format: yaml
  label: Instagram API with Instagram Login
  slug: instagram-api-with-instagram-login
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/instagram/refs/heads/main/openapi/instagram-graph-api.yaml
- filename: instagram-graph-api.yaml
  format: yaml
  label: Instagram API with Facebook Login
  slug: instagram-api-with-facebook-login
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/instagram/refs/heads/main/openapi/instagram-graph-api.yaml
apis:
- description: The Instagram API with Instagram Login enables access to Instagram Business and Creator accounts using Instagram native login flow. Supports media management, content publishing, comment handling, men
  name: Instagram API with Instagram Login
  slug: instagram-api-with-instagram-login
- description: The Instagram API with Facebook Login accesses Instagram Business and Creator accounts linked to Facebook Pages. Enables media retrieval and publishing, comment management, mention identification, has
  name: Instagram API with Facebook Login
  slug: instagram-api-with-facebook-login
- description: 'The Messenger API support for Instagram consolidates Instagram and Facebook Page messaging into a unified platform. Enables businesses and creators to manage conversations, send and receive messages, '
  name: Instagram Messaging API
  slug: instagram-messaging-api
- description: The Instagram oEmbed endpoint returns HTML and metadata for embedding Instagram photos, videos, reels, and carousels on third-party websites using the standard oEmbed protocol.
  name: Instagram oEmbed API
  slug: instagram-oembed-api
capabilities:
- description: Unified workflow for Instagram analytics and insights including account-level metrics, media-level performance data, user profile analysis, and competitor research via business discovery. Used by mark
  name: Instagram Analytics And Insights
  slug: analytics-and-insights
- description: Unified workflow for managing Instagram community interactions including comment moderation, replies, hashtag discovery, and mention tracking. Used by community managers and social media teams to enga
  name: Instagram Community Engagement
  slug: community-engagement
- description: Unified workflow for managing Instagram content including media browsing, publishing (container creation and publish), stories, carousel albums, and media updates. Used by social media managers and co
  name: Instagram Content Management
  slug: content-management
common:
- title: ''
  type: Portal
  url: https://developers.facebook.com/docs/instagram-platform
- title: ''
  type: GettingStarted
  url: https://developers.facebook.com/docs/instagram-api/getting-started
- title: ''
  type: Authentication
  url: https://developers.facebook.com/docs/instagram-api/overview#authentication
- title: ''
  type: TermsOfService
  url: https://developers.facebook.com/terms
- title: ''
  type: PrivacyPolicy
  url: https://www.facebook.com/privacy/explanation
- title: ''
  type: StatusPage
  url: https://developers.facebook.com/status/
- title: ''
  type: ChangeLog
  url: https://developers.facebook.com/docs/instagram-api/changelog
- title: ''
  type: Support
  url: https://developers.facebook.com/support
- title: ''
  type: Blog
  url: https://developers.facebook.com/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/fbsamples
created: '2024-01-01'
description: Instagram is a photo and video sharing social networking platform owned by Meta. The Instagram APIs allow developers to build integrations with Instagram Business and Creator accounts for content publishing, media management, comment moderation, hashtag discovery, insights and analytics, messaging, and embedding. Available through the Meta Developer Platform with Facebook Login or Instagram Login authentication.
features:
- description: Publish photos, videos, reels, carousels, and stories to Instagram Business and Creator accounts programmatically.
  name: Content Publishing
- description: Retrieve, manage, and organize published media including photos, videos, stories, and albums.
  name: Media Management
- description: Read, reply to, hide, and delete comments on Instagram media for brand safety and engagement.
  name: Comment Moderation
- description: Search for hashtags and discover top and recent media associated with specific hashtags.
  name: Hashtag Discovery
- description: Identify and retrieve media where your account has been mentioned by other Instagram users.
  name: Mention Tracking
- description: Access account-level and media-level metrics for reach, impressions, engagement, and audience demographics.
  name: Insights and Analytics
- description: Send and receive messages through Instagram Direct for customer service and business communication.
  name: Instagram Direct Messaging
- description: Publish ephemeral story content including photos and videos that disappear after 24 hours.
  name: Stories Publishing
- description: Create and publish short-form video content as Instagram Reels.
  name: Reels Publishing
- description: Embed Instagram posts, reels, and videos on third-party websites using the standard oEmbed protocol.
  name: oEmbed
- description: Receive real-time notifications for comments, mentions, messages, and story insights via webhooks.
  name: Webhooks
- description: Send private direct messages in response to public comments on your Instagram media.
  name: Private Replies
image: /assets/icons/instagram.png
integrations:
- description: Unified management of Instagram and Facebook content, messaging, and advertising through the Meta platform.
  name: Facebook
- description: Centralized dashboard for managing Instagram and Facebook business accounts, content, and insights.
  name: Meta Business Suite
- description: Cross-platform messaging through Meta unified messaging infrastructure.
  name: WhatsApp
- description: Real-time event notifications for comments, mentions, messages, and story insights.
  name: Webhooks
jsonld:
- class_count: 11
  name: Instagram Graph Api Context
  property_count: 37
  slug: instagram-graph-api-context
layout: provider
modified: '2026-04-17'
name: Instagram
rules:
- name: Instagram API Rules
  rule_count: 20
  severity_counts:
    error: 14
    hint: 0
    info: 2
    warn: 4
  slug: instagram-spectral-rules
skills: []
slug: instagram
solutions:
- description: Native Instagram authentication for Business and Creator accounts with full API access.
  name: Instagram API with Instagram Login
- description: Facebook Page-linked authentication for Instagram Business accounts with hashtag discovery.
  name: Instagram API with Facebook Login
- description: Unified messaging across Instagram Direct and Facebook Messenger for business communication.
  name: Instagram Messaging
- description: oEmbed and embed tools for displaying Instagram content on third-party websites.
  name: Instagram Embedding
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: instagram\nname: Instagram\ndescription: Instagram is a photo and video sharing social networking platform owned\n  by Meta. The Instagram APIs allow developers to build integrations with Instagram\n  Business and Creator accounts for content publishing, media management, comment\n  moderation, hashtag discovery, insights and analytics, messaging, and embedding.\n  Available through the Meta Developer Platform with Facebook Login or Instagram Login\n  authentication.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/instagram/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\ntags:\n- Instagram\n- Meta\n- Photos\n- Social Media\n- Videos\n- Content Publishing\napis:\n- aid: instagram:instagram-api-with-instagram-login\n  name: Instagram API with Instagram Login\n  description: The Instagram API with Instagram Login enables\
  \ access to Instagram\n    Business and Creator accounts using Instagram native login flow. Supports media\n    management, content publishing, comment handling, mention identification, messaging,\n    insights, and webhooks.\n  humanURL: https://developers.facebook.com/docs/instagram-platform/instagram-api-with-instagram-login\n  baseURL: https://graph.instagram.com\n  properties:\n  - type: Documentation\n    url: https://developers.facebook.com/docs/instagram-platform/instagram-api-with-instagram-login\n  - type: GettingStarted\n    url: https://developers.facebook.com/docs/instagram-platform/instagram-api-with-instagram-login/getting-started\n  - type: APIReference\n    url: https://developers.facebook.com/docs/instagram-api/reference\n  - type: Authentication\n    url: https://developers.facebook.com/docs/instagram-platform/instagram-api-with-instagram-login/business-login\n  - type: OpenAPI\n    url: openapi/instagram-graph-api.yaml\n  tags:\n  - Content Publishing\n  - Instagram\
  \ Login\n  - Media\n  - Messaging\n  - Social Media\n- aid: instagram:instagram-api-with-facebook-login\n  name: Instagram API with Facebook Login\n  description: The Instagram API with Facebook Login accesses Instagram Business and\n    Creator accounts linked to Facebook Pages. Enables media retrieval and publishing,\n    comment management, mention identification, hashtag-based media discovery, insights,\n    and business metadata.\n  humanURL: https://developers.facebook.com/docs/instagram-api\n  baseURL: https://graph.facebook.com\n  properties:\n  - type: Documentation\n    url: https://developers.facebook.com/docs/instagram-api/\n  - type: GettingStarted\n    url: https://developers.facebook.com/docs/instagram-api/getting-started\n  - type: APIReference\n    url: https://developers.facebook.com/docs/instagram-api/reference\n  - type: Authentication\n    url: https://developers.facebook.com/docs/instagram-api/overview#authentication\n  - type: ChangeLog\n    url: https://developers.facebook.com/docs/instagram-api/changelog\n\
  \  - type: OpenAPI\n    url: openapi/instagram-graph-api.yaml\n  tags:\n  - Content Publishing\n  - Facebook Login\n  - Hashtags\n  - Media\n  - Social Media\n- aid: instagram:instagram-messaging-api\n  name: Instagram Messaging API\n  description: The Messenger API support for Instagram consolidates Instagram and\n    Facebook Page messaging into a unified platform. Enables businesses and creators\n    to manage conversations, send and receive messages, and handle messaging automation\n    across Instagram Direct.\n  humanURL: https://developers.facebook.com/docs/instagram-platform/instagram-api-with-instagram-login/messaging-api\n  baseURL: https://graph.instagram.com\n  properties:\n  - type: Documentation\n    url: https://developers.facebook.com/docs/instagram-platform/instagram-api-with-instagram-login/messaging-api\n  tags:\n  - Direct Messages\n  - Messaging\n  - Social Media\n- aid: instagram:instagram-oembed-api\n  name: Instagram oEmbed API\n  description: The Instagram oEmbed\
  \ endpoint returns HTML and metadata for embedding\n    Instagram photos, videos, reels, and carousels on third-party websites using the\n    standard oEmbed protocol.\n  humanURL: https://developers.facebook.com/docs/instagram-platform/oembed\n  baseURL: https://graph.facebook.com\n  properties:\n  - type: Documentation\n    url: https://developers.facebook.com/docs/instagram-platform/oembed\n  tags:\n  - Embedding\n  - oEmbed\n  - Social Media\ncommon:\n- type: Portal\n  url: https://developers.facebook.com/docs/instagram-platform\n- type: GettingStarted\n  url: https://developers.facebook.com/docs/instagram-api/getting-started\n- type: Authentication\n  url: https://developers.facebook.com/docs/instagram-api/overview#authentication\n- type: TermsOfService\n  url: https://developers.facebook.com/terms\n- type: PrivacyPolicy\n  url: https://www.facebook.com/privacy/explanation\n- type: StatusPage\n  url: https://developers.facebook.com/status/\n- type: ChangeLog\n  url: https://developers.facebook.com/docs/instagram-api/changelog\n\
  - type: Support\n  url: https://developers.facebook.com/support\n- type: Blog\n  url: https://developers.facebook.com/blog/\n- type: GitHubOrganization\n  url: https://github.com/fbsamples\n- type: Features\n  data:\n  - name: Content Publishing\n    description: Publish photos, videos, reels, carousels, and stories to Instagram\n      Business and Creator accounts programmatically.\n  - name: Media Management\n    description: Retrieve, manage, and organize published media including photos,\n      videos, stories, and albums.\n  - name: Comment Moderation\n    description: Read, reply to, hide, and delete comments on Instagram media for\n      brand safety and engagement.\n  - name: Hashtag Discovery\n    description: Search for hashtags and discover top and recent media associated\n      with specific hashtags.\n  - name: Mention Tracking\n    description: Identify and retrieve media where your account has been mentioned\n      by other Instagram users.\n  - name: Insights and Analytics\n\
  \    description: Access account-level and media-level metrics for reach, impressions,\n      engagement, and audience demographics.\n  - name: Instagram Direct Messaging\n    description: Send and receive messages through Instagram Direct for customer service\n      and business communication.\n  - name: Stories Publishing\n    description: Publish ephemeral story content including photos and videos that\n      disappear after 24 hours.\n  - name: Reels Publishing\n    description: Create and publish short-form video content as Instagram Reels.\n  - name: oEmbed\n    description: Embed Instagram posts, reels, and videos on third-party websites\n      using the standard oEmbed protocol.\n  - name: Webhooks\n    description: Receive real-time notifications for comments, mentions, messages,\n      and story insights via webhooks.\n  - name: Private Replies\n    description: Send private direct messages in response to public comments on your\n      Instagram media.\n- type: UseCases\n  data:\n\
  \  - name: Social Media Management\n    description: Automate content publishing, scheduling, and media management across\n      Instagram accounts.\n  - name: Brand Monitoring\n    description: Track mentions, comments, and hashtags to monitor brand sentiment\n      and engagement.\n  - name: Customer Service\n    description: Manage Instagram Direct conversations for customer support and business\n      inquiries.\n  - name: Analytics and Reporting\n    description: Retrieve insights and metrics for measuring content performance and\n      audience growth.\n  - name: Content Curation\n    description: Discover and curate content through hashtag search and mention tracking.\n  - name: E-commerce Integration\n    description: Connect product catalogs and shopping features with Instagram content\n      for social commerce.\n  - name: Influencer Marketing\n    description: Track creator account metrics, media performance, and audience insights\n      for influencer campaigns.\n  - name:\
  \ Website Embedding\n    description: Embed Instagram posts, reels, and galleries on websites and blogs\n      using oEmbed.\n- type: Integrations\n  data:\n  - name: Facebook\n    description: Unified management of Instagram and Facebook content, messaging,\n      and advertising through the Meta platform.\n  - name: Meta Business Suite\n    description: Centralized dashboard for managing Instagram and Facebook business\n      accounts, content, and insights.\n  - name: WhatsApp\n    description: Cross-platform messaging through Meta unified messaging infrastructure.\n  - name: Webhooks\n    description: Real-time event notifications for comments, mentions, messages, and\n      story insights.\n- type: Solutions\n  data:\n  - name: Instagram API with Instagram Login\n    description: Native Instagram authentication for Business and Creator accounts\n      with full API access.\n  - name: Instagram API with Facebook Login\n    description: Facebook Page-linked authentication for Instagram\
  \ Business accounts\n      with hashtag discovery.\n  - name: Instagram Messaging\n    description: Unified messaging across Instagram Direct and Facebook Messenger\n      for business communication.\n  - name: Instagram Embedding\n    description: oEmbed and embed tools for displaying Instagram content on third-party\n      websites.\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/instagram/refs/heads/main/apis.yml
tags:
- Instagram
- Meta
- Photos
- Social Media
- Videos
- Content Publishing
url: https://raw.githubusercontent.com/api-evangelist/instagram/refs/heads/main/apis.yml
use_cases:
- description: Automate content publishing, scheduling, and media management across Instagram accounts.
  name: Social Media Management
- description: Track mentions, comments, and hashtags to monitor brand sentiment and engagement.
  name: Brand Monitoring
- description: Manage Instagram Direct conversations for customer support and business inquiries.
  name: Customer Service
- description: Retrieve insights and metrics for measuring content performance and audience growth.
  name: Analytics and Reporting
- description: Discover and curate content through hashtag search and mention tracking.
  name: Content Curation
- description: Connect product catalogs and shopping features with Instagram content for social commerce.
  name: E-commerce Integration
- description: Track creator account metrics, media performance, and audience insights for influencer campaigns.
  name: Influencer Marketing
- description: Embed Instagram posts, reels, and galleries on websites and blogs using oEmbed.
  name: Website Embedding
---
