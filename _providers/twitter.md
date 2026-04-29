---
api_count: 3
api_specs:
- filename: x-api-openapi.json
  format: json
  label: X API
  slug: x-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitter/refs/heads/main/openapi/x-api-openapi.json
apis:
- description: The core X API providing programmatic access to posts, users, spaces, lists, direct messages, bookmarks, likes, reposts, follows, blocks, mutes, trends, communities, and compliance data. Supports post
  name: X API
  slug: x-api
- description: 'The X Ads API enables programmatic management of advertising campaigns on the X platform including campaign creation and scheduling, custom audience building, creative management (draft posts, cards, '
  name: X Ads API
  slug: x-ads-api
- description: The X Activity API provides real-time activity event subscriptions with sub-second delivery via streaming or webhooks. Subscribe to profile updates, follows, likes, reposts, and other user activity ev
  name: X Activity API
  slug: x-activity-api
capabilities:
- description: Unified workflow for managing compliance jobs, data streams, and real-time compliance monitoring on X. Used by compliance officers, data engineers, and platform operations.
  name: X Compliance and Data Management
  slug: compliance-and-data
- description: Unified workflow for creating, managing, and analyzing posts, media, bookmarks, and lists on X. Used by social media managers, content creators, and marketing teams.
  name: X Content Publishing and Management
  slug: content-publishing
- description: Unified workflow for managing user relationships, direct messages, spaces, and community interactions on X. Used by community managers, customer support teams, and engagement specialists.
  name: X Engagement and Community Management
  slug: engagement
- description: Unified workflow for monitoring conversations, searching posts, analyzing trends, and extracting insights from X data. Used by data analysts, brand managers, and researchers.
  name: X Social Listening and Analytics
  slug: social-listening
common:
- title: ''
  type: Portal
  url: https://developer.x.com/en/portal/dashboard
- title: ''
  type: GettingStarted
  url: https://docs.x.com/x-api/getting-started/make-your-first-request
- title: ''
  type: Console
  url: https://developer.x.com/en/portal/dashboard
- title: ''
  type: SignUp
  url: https://developer.x.com/en/portal/petition/essential/basic-info
- title: ''
  type: Authentication
  url: https://docs.x.com/resources/fundamentals/authentication
- title: Python XDK
  type: SDK
  url: https://docs.x.com/sdks-and-tools/python-xdk
- title: TypeScript XDK
  type: SDK
  url: https://docs.x.com/sdks-and-tools/typescript-xdk
- title: xurl
  type: CLI
  url: https://docs.x.com/sdks-and-tools/xurl
- title: ''
  type: Pricing
  url: https://developer.x.com/en/portal/petition/essential/basic-info
- title: ''
  type: TermsOfService
  url: https://developer.x.com/en/developer-terms/agreement-and-policy
- title: ''
  type: PrivacyPolicy
  url: https://x.com/en/privacy
- title: ''
  type: StatusPage
  url: https://api.twitterstat.us/
- title: ''
  type: Support
  url: https://devcommunity.x.com/
- title: ''
  type: Blog
  url: https://blog.x.com/developer
- title: ''
  type: ReleaseNotes
  url: https://docs.x.com/changelog
- title: ''
  type: GitHubOrganization
  url: https://github.com/xdevplatform
- title: ''
  type: GitHubRepository
  url: https://github.com/xdevplatform/xdk-python
- title: ''
  type: GitHubRepository
  url: https://github.com/xdevplatform/xdk-typescript
- title: ''
  type: GitHubRepository
  url: https://github.com/xdevplatform/xurl
- title: ''
  type: GitHubRepository
  url: https://github.com/xdevplatform/xdk
- title: ''
  type: GitHubRepository
  url: https://github.com/xdevplatform/twitter-api-java-sdk
- title: ''
  type: GitHubRepository
  url: https://github.com/xdevplatform/twitter-ruby-ads-sdk
- title: ''
  type: Tools
  url: https://github.com/xdevplatform/xmcp
- title: ''
  type: Sandbox
  url: https://github.com/xdevplatform/playground
- title: ''
  type: CodeExamples
  url: https://github.com/xdevplatform/samples
- title: ''
  type: CodeExamples
  url: https://github.com/xdevplatform/xchat-bot-python
- title: ''
  type: PostmanWorkspace
  url: https://docs.x.com/sdks-and-tools/postman
- title: ''
  type: PostmanCollection
  url: postman/x-api-v2-postman-collection.json
- title: ''
  type: X
  url: https://x.com/XDevelopers
created: '2025-07-29'
description: X (formerly Twitter) is a social media platform providing APIs for accessing and integrating with posts, users, spaces, direct messages, lists, media, trends, and real-time streaming data. The X API enables developers to build applications that read and write X data, manage advertising campaigns, and subscribe to real-time activity events. Available through pay-per-use credit-based pricing with enterprise options for high-volume access.
features:
- description: Create, delete, edit, repost, quote, like, and bookmark posts programmatically.
  name: Post Management
- description: Access filtered streams, sampled streams, firehose, and language-specific streams for real-time post data.
  name: Real-Time Streaming
- description: Search the complete archive of public posts with advanced query operators and date filtering.
  name: Full-Archive Search
- description: Look up users by ID or username, manage follows, blocks, mutes, and retrieve user metrics.
  name: User Lookup and Management
- description: Discover and look up live audio Spaces with host, speaker, and listener data.
  name: Spaces
- description: Send and receive direct messages, create conversations, and manage participants.
  name: Direct Messages
- description: Create, manage, and query lists including membership, followers, and pinned lists.
  name: Lists
- description: Access personalized and geographic trending topics.
  name: Trends
- description: Upload images, videos, and large files using chunked upload with metadata and subtitle support.
  name: Media Upload
- description: Access compliance streams and batch jobs for data deletion and user protection events.
  name: Compliance
- description: Access community data and community notes for collaborative fact-checking.
  name: Communities and Community Notes
- description: Programmatically create, schedule, and manage advertising campaigns with targeting and budget controls.
  name: Ad Campaign Management
image: https://abs.twimg.com/favicons/twitter.ico
integrations:
- description: Official Postman collections for exploring and testing X API endpoints interactively.
  name: Postman
- description: Integration with AI tools and agents through Model Context Protocol servers.
  name: MCP Servers
- description: Real-time event delivery via webhooks for the Activity API.
  name: Webhook Delivery
jsonld:
- class_count: 23
  name: X Api Context
  property_count: 118
  slug: x-api-context
layout: provider
modified: '2026-04-17'
name: X (Twitter)
rules:
- name: X (Twitter) API Rules
  rule_count: 53
  severity_counts:
    error: 17
    hint: 0
    info: 18
    warn: 18
  slug: twitter-spectral-rules
skills: []
slug: twitter
solutions:
- description: Credit-based pricing with no commitments. Pay only for what you use with access to core X API endpoints.
  name: X API Pay-Per-Use
- description: High-volume access with custom rate limits, dedicated account management, full firehose, and premium support.
  name: X API Enterprise
- description: Advertising platform API for campaign management, audience targeting, creative management, and analytics.
  name: X Ads API
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: twitter\nname: X (Twitter)\ndescription: >-\n  X (formerly Twitter) is a social media platform providing APIs for accessing and\n  integrating with posts, users, spaces, direct messages, lists, media, trends, and\n  real-time streaming data. The X API enables developers to build applications that\n  read and write X data, manage advertising campaigns, and subscribe to real-time\n  activity events. Available through pay-per-use credit-based pricing with enterprise\n  options for high-volume access.\ntype: Index\nimage: https://abs.twimg.com/favicons/twitter.ico\nurl: https://raw.githubusercontent.com/api-evangelist/twitter/refs/heads/main/apis.yml\ncreated: '2025-07-29'\nmodified: '2026-04-17'\nspecificationVersion: '0.19'\ntags:\n  - Social Media\n  - Microblogging\n  - Real-Time Data\n  - Streaming\n  - Advertising\n  - Content\napis:\n  - aid: twitter:x-api\n    name: X API\n    description: >-\n      The core X API providing programmatic access to posts, users, spaces,\
  \ lists,\n      direct messages, bookmarks, likes, reposts, follows, blocks, mutes, trends,\n      communities, and compliance data. Supports post creation, search (recent and\n      full-archive), timelines, filtered streams, sampled streams, and real-time\n      data access. Uses OAuth 2.0 with PKCE or OAuth 1.0a authentication with\n      credit-based pay-per-use pricing.\n    image: https://abs.twimg.com/favicons/twitter.ico\n    humanURL: https://docs.x.com/x-api\n    baseURL: https://api.x.com/2\n    properties:\n      - type: Documentation\n        url: https://docs.x.com/x-api\n      - type: GettingStarted\n        url: https://docs.x.com/x-api/getting-started/make-your-first-request\n      - type: APIReference\n        url: https://docs.x.com/x-api\n      - type: Authentication\n        url: https://docs.x.com/resources/fundamentals/authentication\n      - type: RateLimits\n        url: https://docs.x.com/x-api/fundamentals/rate-limits\n      - type: SDK\n        url: https://docs.x.com/sdks-and-tools/python-xdk\n\
  \        title: Python XDK\n      - type: SDK\n        url: https://docs.x.com/sdks-and-tools/typescript-xdk\n        title: TypeScript XDK\n      - type: OpenAPI\n        url: openapi/x-api-openapi.json\n    tags:\n      - Posts\n      - Users\n      - Spaces\n      - Lists\n      - Direct Messages\n      - Streaming\n      - Search\n      - Timelines\n  - aid: twitter:x-ads-api\n    name: X Ads API\n    description: >-\n      The X Ads API enables programmatic management of advertising campaigns on the\n      X platform including campaign creation and scheduling, custom audience building,\n      creative management (draft posts, cards, media), and analytics retrieval for\n      campaign performance metrics. Supports both synchronous and asynchronous\n      analytics endpoints for reporting.\n    image: https://abs.twimg.com/favicons/twitter.ico\n    humanURL: https://docs.x.com/x-ads-api\n    baseURL: https://ads-api.x.com\n    properties:\n      - type: Documentation\n        url: https://docs.x.com/x-ads-api\n\
  \      - type: GettingStarted\n        url: https://docs.x.com/x-ads-api/getting-started/create-a-campaign\n      - type: RateLimits\n        url: https://docs.x.com/x-ads-api/fundamentals/rate-limiting\n      - type: PostmanCollection\n        url: postman/x-ads-api-postman-collection.json\n    tags:\n      - Advertising\n      - Campaigns\n      - Analytics\n      - Audiences\n      - Creatives\n  - aid: twitter:x-activity-api\n    name: X Activity API\n    description: >-\n      The X Activity API provides real-time activity event subscriptions with\n      sub-second delivery via streaming or webhooks. Subscribe to profile updates,\n      follows, likes, reposts, and other user activity events. Recently exited\n      beta and is now generally available.\n    image: https://abs.twimg.com/favicons/twitter.ico\n    humanURL: https://docs.x.com/x-activity-api\n    baseURL: https://api.x.com\n    properties:\n      - type: Documentation\n        url: https://docs.x.com/x-activity-api\n \
  \   tags:\n      - Activity\n      - Events\n      - Real-Time\n      - Streaming\n      - Webhooks\ncommon:\n  - type: Portal\n    url: https://developer.x.com/en/portal/dashboard\n  - type: GettingStarted\n    url: https://docs.x.com/x-api/getting-started/make-your-first-request\n  - type: Console\n    url: https://developer.x.com/en/portal/dashboard\n  - type: SignUp\n    url: https://developer.x.com/en/portal/petition/essential/basic-info\n  - type: Authentication\n    url: https://docs.x.com/resources/fundamentals/authentication\n  - type: SDK\n    url: https://docs.x.com/sdks-and-tools/python-xdk\n    title: Python XDK\n  - type: SDK\n    url: https://docs.x.com/sdks-and-tools/typescript-xdk\n    title: TypeScript XDK\n  - type: CLI\n    url: https://docs.x.com/sdks-and-tools/xurl\n    title: xurl\n  - type: Pricing\n    url: https://developer.x.com/en/portal/petition/essential/basic-info\n  - type: TermsOfService\n    url: https://developer.x.com/en/developer-terms/agreement-and-policy\n\
  \  - type: PrivacyPolicy\n    url: https://x.com/en/privacy\n  - type: StatusPage\n    url: https://api.twitterstat.us/\n  - type: Support\n    url: https://devcommunity.x.com/\n  - type: Blog\n    url: https://blog.x.com/developer\n  - type: ReleaseNotes\n    url: https://docs.x.com/changelog\n  - type: GitHubOrganization\n    url: https://github.com/xdevplatform\n  - type: GitHubRepository\n    url: https://github.com/xdevplatform/xdk-python\n    description: Auto-generated Python SDK for the X API.\n  - type: GitHubRepository\n    url: https://github.com/xdevplatform/xdk-typescript\n    description: Auto-generated TypeScript SDK for the X API.\n  - type: GitHubRepository\n    url: https://github.com/xdevplatform/xurl\n    description: Official CLI for the X API with built-in authentication.\n  - type: GitHubRepository\n    url: https://github.com/xdevplatform/xdk\n    description: SDK generator for the X APIs producing auto-generated client libraries.\n  - type: GitHubRepository\n \
  \   url: https://github.com/xdevplatform/twitter-api-java-sdk\n    description: Official Java SDK for the Twitter/X API.\n  - type: GitHubRepository\n    url: https://github.com/xdevplatform/twitter-ruby-ads-sdk\n    description: Official Ruby SDK for the Twitter/X Ads API.\n  - type: Tools\n    url: https://github.com/xdevplatform/xmcp\n    description: MCP server for the X API enabling AI agent integration.\n  - type: Sandbox\n    url: https://github.com/xdevplatform/playground\n    description: Standalone local HTTP server simulating the X API v2 for testing and development with interactive web UI.\n  - type: CodeExamples\n    url: https://github.com/xdevplatform/samples\n    description: Official sample code for X API v2 endpoints.\n  - type: CodeExamples\n    url: https://github.com/xdevplatform/xchat-bot-python\n    description: Example DM reply bot in Python for X encrypted chat system.\n  - type: PostmanWorkspace\n    url: https://docs.x.com/sdks-and-tools/postman\n  - type: PostmanCollection\n\
  \    url: postman/x-api-v2-postman-collection.json\n  - type: X\n    url: https://x.com/XDevelopers\n  - type: Features\n    data:\n      - name: Post Management\n        description: Create, delete, edit, repost, quote, like, and bookmark posts programmatically.\n      - name: Real-Time Streaming\n        description: Access filtered streams, sampled streams, firehose, and language-specific streams for real-time post data.\n      - name: Full-Archive Search\n        description: Search the complete archive of public posts with advanced query operators and date filtering.\n      - name: User Lookup and Management\n        description: Look up users by ID or username, manage follows, blocks, mutes, and retrieve user metrics.\n      - name: Spaces\n        description: Discover and look up live audio Spaces with host, speaker, and listener data.\n      - name: Direct Messages\n        description: Send and receive direct messages, create conversations, and manage participants.\n      - name:\
  \ Lists\n        description: Create, manage, and query lists including membership, followers, and pinned lists.\n      - name: Trends\n        description: Access personalized and geographic trending topics.\n      - name: Media Upload\n        description: Upload images, videos, and large files using chunked upload with metadata and subtitle support.\n      - name: Compliance\n        description: Access compliance streams and batch jobs for data deletion and user protection events.\n      - name: Communities and Community Notes\n        description: Access community data and community notes for collaborative fact-checking.\n      - name: Ad Campaign Management\n        description: Programmatically create, schedule, and manage advertising campaigns with targeting and budget controls.\n  - type: UseCases\n    data:\n      - name: Social Listening\n        description: Monitor brand mentions, sentiment, and conversations in real-time using filtered streams and search endpoints.\n    \
  \  - name: Content Publishing\n        description: Automate post creation, scheduling, and thread publishing for social media management platforms.\n      - name: Analytics and Reporting\n        description: Retrieve post metrics, user engagement data, and campaign performance for business intelligence.\n      - name: Bot Development\n        description: Build automated accounts that respond to mentions, post updates, or provide customer service.\n      - name: Research and Academic Analysis\n        description: Access full-archive search and streaming data for social media research and trend analysis.\n      - name: Advertising Automation\n        description: Programmatically manage ad campaigns, audiences, creatives, and bidding strategies at scale.\n      - name: Real-Time Event Monitoring\n        description: Track live events, breaking news, and trending topics with streaming APIs and trend endpoints.\n      - name: Community Management\n        description: Manage followers,\
  \ lists, and direct messages for community engagement and moderation.\n  - type: Integrations\n    data:\n      - name: Postman\n        description: Official Postman collections for exploring and testing X API endpoints interactively.\n      - name: MCP Servers\n        description: Integration with AI tools and agents through Model Context Protocol servers.\n      - name: Webhook Delivery\n        description: Real-time event delivery via webhooks for the Activity API.\n  - type: Solutions\n    data:\n      - name: X API Pay-Per-Use\n        description: Credit-based pricing with no commitments. Pay only for what you use with access to core X API endpoints.\n      - name: X API Enterprise\n        description: High-volume access with custom rate limits, dedicated account management, full firehose, and premium support.\n      - name: X Ads API\n        description: Advertising platform API for campaign management, audience targeting, creative management, and analytics.\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/twitter/refs/heads/main/apis.yml
tags:
- Social Media
- Microblogging
- Real-Time Data
- Streaming
- Advertising
- Content
url: https://raw.githubusercontent.com/api-evangelist/twitter/refs/heads/main/apis.yml
use_cases:
- description: Monitor brand mentions, sentiment, and conversations in real-time using filtered streams and search endpoints.
  name: Social Listening
- description: Automate post creation, scheduling, and thread publishing for social media management platforms.
  name: Content Publishing
- description: Retrieve post metrics, user engagement data, and campaign performance for business intelligence.
  name: Analytics and Reporting
- description: Build automated accounts that respond to mentions, post updates, or provide customer service.
  name: Bot Development
- description: Access full-archive search and streaming data for social media research and trend analysis.
  name: Research and Academic Analysis
- description: Programmatically manage ad campaigns, audiences, creatives, and bidding strategies at scale.
  name: Advertising Automation
- description: Track live events, breaking news, and trending topics with streaming APIs and trend endpoints.
  name: Real-Time Event Monitoring
- description: Manage followers, lists, and direct messages for community engagement and moderation.
  name: Community Management
---
