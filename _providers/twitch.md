---
api_count: 9
api_specs:
- filename: reference
  format: yaml
  label: Twitch API
  slug: ''
  spec_type: OpenAPI
  url: https://dev.twitch.tv/docs/api/reference
- filename: twitch-eventsub-asyncapi.yml
  format: yaml
  label: Twitch EventSub
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/asyncapi/twitch-eventsub-asyncapi.yml
- filename: twitch-extensions-openapi.yml
  format: yaml
  label: Twitch Extensions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/openapi/twitch-extensions-openapi.yml
- filename: twitch-drops-openapi.yml
  format: yaml
  label: Twitch Drops API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/openapi/twitch-drops-openapi.yml
- filename: twitch-video-broadcast-openapi.yml
  format: yaml
  label: Twitch Video Broadcast API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/openapi/twitch-video-broadcast-openapi.yml
- filename: twitch-insights-analytics-openapi.yml
  format: yaml
  label: Twitch Insights and Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/openapi/twitch-insights-analytics-openapi.yml
- filename: twitch-igdb-openapi.yml
  format: yaml
  label: IGDB API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/openapi/twitch-igdb-openapi.yml
apis:
- description: The Twitch API enables developers to build experiences that integrate with Twitch, including retrieving stream data, managing users, and interacting with chat.
  name: Twitch API
  slug: ''
- description: EventSub is Twitch's webhook-based subscription service for receiving real-time notifications about events on Twitch.
  name: Twitch EventSub
  slug: ''
- description: IRC and WebSocket-based APIs for integrating with Twitch chat.
  name: Twitch Chat API
  slug: ''
- description: APIs for embedding Twitch live streams, video on demand, clips, and chat into external websites.
  name: Twitch Embed API
  slug: ''
- description: APIs for building interactive extensions that run as overlays or panels on Twitch channels, communicating via a sandboxed iframe.
  name: Twitch Extensions API
  slug: ''
- description: APIs for game developers to create and manage Drops campaigns that grant in-game rewards to Twitch viewers watching streamers play their game.
  name: Twitch Drops API
  slug: ''
- description: API for retrieving ingest server information used by broadcasters to send live video streams to Twitch via RTMP.
  name: Twitch Video Broadcast API
  slug: ''
- description: APIs for accessing extension and game analytics data including views, clicks, hours watched, and concurrent streamers as downloadable CSV reports.
  name: Twitch Insights and Analytics API
  slug: ''
- description: The Internet Game Database API provides comprehensive video game information including metadata, ratings, and media, and is owned and operated by Twitch.
  name: IGDB API
  slug: ''
asyncapis:
- description: EventSub is Twitch's event-driven subscription service for receiving real-time notifications about events on Twitch. Supports webhook, WebSocket, and conduit transport methods. Subscribe to events suc
  name: Twitch EventSub
  slug: twitch-eventsub-asyncapi
capabilities:
- description: Workflow capability for Twitch broadcasters to manage their channels, including chat configuration, polls, subscriptions, moderation, and channel points. Used by broadcaster tools, chatbots, and chann
  name: Twitch Channel Management
  slug: channel-management
- description: Unified workflow for discovering Twitch content including live streams, channels, games, clips, and videos. Used by app developers and content aggregators to surface the most relevant Twitch content.
  name: Twitch Content Discovery
  slug: content-discovery
common:
- title: ''
  type: Developer Portal
  url: https://dev.twitch.tv/
- title: ''
  type: Console
  url: https://dev.twitch.tv/console
- title: ''
  type: Blog
  url: https://blog.twitch.tv/en/tags/developers/
- title: ''
  type: GitHub
  url: https://github.com/twitchdev
- title: ''
  type: Extensions
  url: https://dev.twitch.tv/docs/extensions
- title: ''
  type: CLI Tools
  url: https://dev.twitch.tv/docs/cli
- title: ''
  type: Support
  url: https://dev.twitch.tv/support/
- title: ''
  type: Forum
  url: https://discuss.dev.twitch.com/
- title: ''
  type: Feedback
  url: https://twitch.uservoice.com/forums/310213-developers
- title: ''
  type: Community Resources
  url: https://dev.twitch.tv/code/
- title: ''
  type: Products
  url: https://dev.twitch.tv/products/
- title: ''
  type: Change Log
  url: https://dev.twitch.tv/docs/change-log/
- title: ''
  type: Product Lifecycle
  url: https://dev.twitch.tv/docs/product-lifecycle/
- title: ''
  type: Authentication
  url: https://dev.twitch.tv/docs/authentication
- title: ''
  type: Mobile Deep Links
  url: https://dev.twitch.tv/docs/mobile-deeplinks/
- title: ''
  type: Game Engine Plugins
  url: https://dev.twitch.tv/docs/game-engine-plugins/
- title: ''
  type: Terms of Service
  url: https://www.twitch.tv/p/legal/terms-of-service/
- title: ''
  type: Privacy Policy
  url: https://www.twitch.tv/p/legal/privacy-notice/
- title: ''
  type: JSON-LD
  url: json-ld/twitch-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/twitch-stream-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/twitch-user-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/twitch-channel-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/twitch-clip-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/twitch-subscription-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/twitch-video-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/twitch-stream-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/twitch-channel-structure.json
- title: ''
  type: JSONStructure
  url: json-structure/twitch-user-structure.json
- title: ''
  type: Vocabulary
  url: vocabulary/twitch-vocabulary.yml
- title: ''
  type: SpectralRules
  url: rules/twitch-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/content-discovery.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/channel-management.yaml
created: '2024'
description: Twitch is a live streaming platform for gamers, content creators, and communities.
features: []
image: https://www.twitch.tv/favicon.ico
integrations: []
jsonld:
- class_count: 0
  name: Twitch Context
  property_count: 11
  slug: twitch-context
layout: provider
modified: '2026-05-03'
name: Twitch
rules:
- name: Twitch API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 4
    info: 0
    warn: 4
  slug: twitch-rules
skills: []
slug: twitch
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Twitch\ndescription: >-\n  Twitch is a live streaming platform for gamers, content creators, and communities.\nimage: https://www.twitch.tv/favicon.ico\nurl: https://www.twitch.tv\ncreated: '2024'\nmodified: '2026-05-03'\nspecificationVersion: '0.18'\ntags:\n  - Entertainment\n  - Gaming\n  - Live Video\n  - Streaming\n  - Video\napis:\n  - name: Twitch API\n    description: >-\n      The Twitch API enables developers to build experiences that integrate with Twitch,\n      including retrieving stream data, managing users, and interacting with chat.\n    image: https://www.twitch.tv/favicon.ico\n    humanURL: https://dev.twitch.tv/\n    baseURL: https://api.twitch.tv/helix\n    tags:\n      - Chat\n      - Gaming\n      - Streaming\n      - Video\n    properties:\n      - type: Documentation\n        url: https://dev.twitch.tv/docs/api/\n      - type: OpenAPI\n        url: https://dev.twitch.tv/docs/api/reference\n      - type: Authentication\n        url: https://dev.twitch.tv/docs/authentication\n\
  \      - type: Getting Started\n        url: https://dev.twitch.tv/docs/api/get-started\n      - type: Rate Limits\n        url: https://dev.twitch.tv/docs/api/guide#rate-limits\n      - type: Webhooks\n        url: https://dev.twitch.tv/docs/eventsub\n      - type: API Status\n        url: https://devstatus.twitch.tv/\n      - type: Terms of Service\n        url: https://www.twitch.tv/p/legal/terms-of-service/\n      - type: Privacy Policy\n        url: https://www.twitch.tv/p/legal/privacy-notice/\n      - type: Scopes\n        url: https://dev.twitch.tv/docs/authentication/scopes/\n      - type: Change Log\n        url: https://dev.twitch.tv/docs/change-log/\n      - type: Migration Guide\n        url: https://dev.twitch.tv/docs/api/migration\n      - type: Concepts\n        url: https://dev.twitch.tv/docs/api/guide\n      - type: Clips\n        url: https://dev.twitch.tv/docs/api/clips\n      - type: Videos\n        url: https://dev.twitch.tv/docs/api/videos/\n      - type: OpenAPI\n\
  \        url: openapi/twitch-helix-openapi.yml\n    contact:\n      - type: Support\n        url: https://help.twitch.tv/\n      - type: Twitter\n        url: https://twitter.com/TwitchDev\n      - type: Discord\n        url: https://discord.gg/twitchdev\n  - name: Twitch EventSub\n    description: >-\n      EventSub is Twitch's webhook-based subscription service for receiving real-time\n      notifications about events on Twitch.\n    image: https://www.twitch.tv/favicon.ico\n    humanURL: https://dev.twitch.tv/docs/eventsub\n    baseURL: https://api.twitch.tv/helix/eventsub\n    tags:\n      - Events\n      - Notifications\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://dev.twitch.tv/docs/eventsub\n      - type: Subscription Types\n        url: https://dev.twitch.tv/docs/eventsub/eventsub-subscription-types\n      - type: WebSocket Reference\n        url: https://dev.twitch.tv/docs/eventsub/websocket-reference/\n      - type: Handling WebSocket Events\n\
  \        url: https://dev.twitch.tv/docs/eventsub/handling-websocket-events/\n      - type: Handling Conduit Events\n        url: https://dev.twitch.tv/docs/eventsub/handling-conduit-events/\n      - type: AsyncAPI\n        url: asyncapi/twitch-eventsub-asyncapi.yml\n  - name: Twitch Chat API\n    description: >-\n      IRC and WebSocket-based APIs for integrating with Twitch chat.\n    image: https://www.twitch.tv/favicon.ico\n    humanURL: https://dev.twitch.tv/docs/chat\n    baseURL: wss://irc-ws.chat.twitch.tv:443\n    tags:\n      - Chat\n      - Irc\n      - Messaging\n      - Websocket\n    properties:\n      - type: Documentation\n        url: https://dev.twitch.tv/docs/chat\n      - type: Chat Commands\n        url: https://dev.twitch.tv/docs/irc/commands\n      - type: Chat Badges\n        url: https://dev.twitch.tv/docs/irc/tags#privmsg-tags\n      - type: Authentication\n        url: https://dev.twitch.tv/docs/chat/authenticating/\n  - name: Twitch Embed API\n    description:\
  \ >-\n      APIs for embedding Twitch live streams, video on demand, clips, and chat into\n      external websites.\n    image: https://www.twitch.tv/favicon.ico\n    humanURL: https://dev.twitch.tv/docs/embed/\n    baseURL: https://embed.twitch.tv\n    tags:\n      - Chat\n      - Clips\n      - Embed\n      - Player\n      - Video\n    properties:\n      - type: Documentation\n        url: https://dev.twitch.tv/docs/embed/\n      - type: Video and Clips\n        url: https://dev.twitch.tv/docs/embed/video-and-clips/\n      - type: Chat\n        url: https://dev.twitch.tv/docs/embed/chat/\n      - type: Everything\n        url: https://dev.twitch.tv/docs/embed/everything/\n  - name: Twitch Extensions API\n    description: >-\n      APIs for building interactive extensions that run as overlays or panels on Twitch\n      channels, communicating via a sandboxed iframe.\n    image: https://www.twitch.tv/favicon.ico\n    humanURL: https://dev.twitch.tv/docs/extensions/\n    baseURL: https://api.twitch.tv/helix/extensions\n\
  \    tags:\n      - Extensions\n      - Interactive\n      - Overlays\n      - Panels\n    properties:\n      - type: Documentation\n        url: https://dev.twitch.tv/docs/extensions/\n      - type: Building Extensions\n        url: https://dev.twitch.tv/docs/extensions/building/\n      - type: Extensions Reference\n        url: https://dev.twitch.tv/docs/extensions/reference/\n      - type: Frontend API Usage\n        url: https://dev.twitch.tv/docs/extensions/frontend-api-usage/\n      - type: OpenAPI\n        url: openapi/twitch-extensions-openapi.yml\n  - name: Twitch Drops API\n    description: >-\n      APIs for game developers to create and manage Drops campaigns that grant in-game\n      rewards to Twitch viewers watching streamers play their game.\n    image: https://www.twitch.tv/favicon.ico\n    humanURL: https://dev.twitch.tv/docs/drops/\n    baseURL: https://api.twitch.tv/helix\n    tags:\n      - Campaigns\n      - Drops\n      - Gaming\n      - Rewards\n    properties:\n\
  \      - type: Documentation\n        url: https://dev.twitch.tv/docs/drops/\n      - type: Campaign Guide\n        url: https://dev.twitch.tv/docs/drops/campaign-guide\n      - type: Technical Guide\n        url: https://dev.twitch.tv/docs/drops/technical-guide/\n      - type: OpenAPI\n        url: openapi/twitch-drops-openapi.yml\n  - name: Twitch Video Broadcast API\n    description: >-\n      API for retrieving ingest server information used by broadcasters to send live\n      video streams to Twitch via RTMP.\n    image: https://www.twitch.tv/favicon.ico\n    humanURL: https://dev.twitch.tv/docs/video-broadcast/\n    baseURL: https://ingest.twitch.tv\n    tags:\n      - Broadcast\n      - Ingest\n      - Rtmp\n      - Streaming\n      - Video\n    properties:\n      - type: Documentation\n        url: https://dev.twitch.tv/docs/video-broadcast/\n      - type: API Reference\n        url: https://dev.twitch.tv/docs/video-broadcast/reference/\n      - type: OpenAPI\n        url: openapi/twitch-video-broadcast-openapi.yml\n\
  \  - name: Twitch Insights and Analytics API\n    description: >-\n      APIs for accessing extension and game analytics data including views, clicks,\n      hours watched, and concurrent streamers as downloadable CSV reports.\n    image: https://www.twitch.tv/favicon.ico\n    humanURL: https://dev.twitch.tv/docs/insights/\n    baseURL: https://api.twitch.tv/helix/analytics\n    tags:\n      - Analytics\n      - Insights\n      - Metrics\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://dev.twitch.tv/docs/insights/\n      - type: Dashboard\n        url: https://dev.twitch.tv/insights/\n      - type: OpenAPI\n        url: openapi/twitch-insights-analytics-openapi.yml\n  - name: IGDB API\n    description: >-\n      The Internet Game Database API provides comprehensive video game information\n      including metadata, ratings, and media, and is owned and operated by Twitch.\n    image: https://www.twitch.tv/favicon.ico\n    humanURL: https://api-docs.igdb.com/\n\
  \    baseURL: https://api.igdb.com/v4\n    tags:\n      - Database\n      - Games\n      - Metadata\n      - Ratings\n    properties:\n      - type: Documentation\n        url: https://api-docs.igdb.com/\n      - type: Authentication\n        url: https://dev.twitch.tv/docs/authentication\n      - type: OpenAPI\n        url: openapi/twitch-igdb-openapi.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Developer Portal\n    url: https://dev.twitch.tv/\n  - type: Console\n    url: https://dev.twitch.tv/console\n  - type: Blog\n    url: https://blog.twitch.tv/en/tags/developers/\n  - type: GitHub\n    url: https://github.com/twitchdev\n  - type: Extensions\n    url: https://dev.twitch.tv/docs/extensions\n  - type: CLI Tools\n    url: https://dev.twitch.tv/docs/cli\n  - type: Support\n    url: https://dev.twitch.tv/support/\n  - type: Forum\n    url: https://discuss.dev.twitch.com/\n  - type: Feedback\n    url: https://twitch.uservoice.com/forums/310213-developers\n\
  \  - type: Community Resources\n    url: https://dev.twitch.tv/code/\n  - type: Products\n    url: https://dev.twitch.tv/products/\n  - type: Change Log\n    url: https://dev.twitch.tv/docs/change-log/\n  - type: Product Lifecycle\n    url: https://dev.twitch.tv/docs/product-lifecycle/\n  - type: Authentication\n    url: https://dev.twitch.tv/docs/authentication\n  - type: Mobile Deep Links\n    url: https://dev.twitch.tv/docs/mobile-deeplinks/\n  - type: Game Engine Plugins\n    url: https://dev.twitch.tv/docs/game-engine-plugins/\n  - type: Terms of Service\n    url: https://www.twitch.tv/p/legal/terms-of-service/\n  - type: Privacy Policy\n    url: https://www.twitch.tv/p/legal/privacy-notice/\n  - type: JSON-LD\n    url: json-ld/twitch-context.jsonld\n  - type: JSONSchema\n    url: json-schema/twitch-stream-schema.json\n  - type: JSONSchema\n    url: json-schema/twitch-user-schema.json\n  - type: JSONSchema\n    url: json-schema/twitch-channel-schema.json\n  - type: JSONSchema\n  \
  \  url: json-schema/twitch-clip-schema.json\n  - type: JSONSchema\n    url: json-schema/twitch-subscription-schema.json\n  - type: JSONSchema\n    url: json-schema/twitch-video-schema.json\n  - type: JSONStructure\n    url: json-structure/twitch-stream-structure.json\n  - type: JSONStructure\n    url: json-structure/twitch-channel-structure.json\n  - type: JSONStructure\n    url: json-structure/twitch-user-structure.json\n  - type: Vocabulary\n    url: vocabulary/twitch-vocabulary.yml\n  - type: SpectralRules\n    url: rules/twitch-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/content-discovery.yaml\n  - type: NaftikoCapability\n    url: capabilities/channel-management.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/apis.yml
tags:
- Entertainment
- Gaming
- Live Video
- Streaming
- Video
url: https://www.twitch.tv
use_cases: []
---
