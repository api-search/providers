---
api_count: 4
api_specs:
- filename: reddit-data-api-openapi.yml
  format: yaml
  label: Reddit Data API
  slug: data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reddit/refs/heads/main/openapi/reddit-data-api-openapi.yml
- filename: reddit-ads-api-openapi.yml
  format: yaml
  label: Reddit Ads API
  slug: ads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reddit/refs/heads/main/openapi/reddit-ads-api-openapi.yml
- filename: reddit-embeds-openapi.yml
  format: yaml
  label: Reddit Embeds (oEmbed)
  slug: embeds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/reddit/refs/heads/main/openapi/reddit-embeds-openapi.yml
apis:
- description: 'The Reddit Data API provides programmatic access to Reddit content including subreddits, posts, comments, user profiles, and voting data. Developers can use the API to read and submit content, manage '
  name: Reddit Data API
  slug: data-api
- description: The Reddit Ads API allows advertisers and their marketing partners to programmatically create, edit, manage, and report on advertising campaigns on the Reddit platform. It provides endpoints for manag
  name: Reddit Ads API
  slug: ads-api
- description: 'Reddit Embeds allows developers and content creators to embed Reddit posts and comments directly into external websites and applications. The service provides oEmbed endpoints that return embed codes '
  name: Reddit Embeds (oEmbed)
  slug: embeds
- description: Reddit's OAuth 2.0 authorization system provides authentication for all Reddit API access. Developers register applications at reddit.com/prefs/apps to obtain client credentials. Supported grant types
  name: Reddit OAuth 2.0 Authorization
  slug: oauth
capabilities:
- description: Unified capability for managing Reddit advertising campaigns. Combines the Reddit Ads API for campaign lifecycle management and the Data API for audience research and targeting intelligence. Used by d
  name: Reddit Advertising
  slug: advertising
- description: Unified capability for reading and engaging with Reddit community content. Combines the Reddit Data API for browsing posts, searching communities, and accessing user profiles. Used by community manage
  name: Reddit Community Engagement
  slug: community-engagement
common:
- title: ''
  type: Website
  url: https://www.reddit.com
- title: ''
  type: Developer Portal
  url: https://www.reddit.com/dev/api
- title: ''
  type: Documentation
  url: https://support.reddithelp.com/hc/en-us/articles/16160319875092-Reddit-Data-API-Wiki
- title: ''
  type: GitHub Organization
  url: https://github.com/reddit-archive
- title: ''
  type: Blog
  url: https://www.redditinc.com/blog
- title: ''
  type: Privacy Policy
  url: https://www.reddit.com/policies/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.redditinc.com/policies/user-agreement
- title: ''
  type: Status
  url: https://www.redditstatus.com/
- title: ''
  type: Support
  url: https://support.reddithelp.com/hc/en-us
- title: ''
  type: Sign Up
  url: https://www.reddit.com/register
- title: ''
  type: OpenAPI
  url: openapi/reddit-data-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/reddit-ads-api-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/reddit-embeds-openapi.yml
- title: ''
  type: JSONSchema
  url: json-schema/reddit-post-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/reddit-comment-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/reddit-subreddit-schema.json
- title: ''
  type: JSONLDContext
  url: json-ld/reddit-context.jsonld
- title: ''
  type: JSONStructure
  url: json-structure/reddit-post-structure.json
- title: ''
  type: SpectralRuleset
  url: rules/reddit-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/community-engagement.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/advertising.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/reddit-vocabulary.yml
created: '2026-01-01'
description: Reddit is a social news aggregation, discussion, and community platform where users submit, vote, and comment on content organized into topic-based communities called subreddits. Reddit provides developer APIs for accessing platform data, managing communities, running advertising campaigns, and embedding content. The Reddit Data API provides access to posts, comments, subreddits, user profiles, and moderation tools via OAuth 2.0. The Reddit Ads API enables programmatic management of advertising campaigns, audiences, and conversion tracking. All API access requires OAuth 2.0 authentication via the oauth.reddit.com server at 60 requests per minute.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Reddit Context
  property_count: 7
  slug: reddit-context
layout: provider
modified: '2026-05-02'
name: Reddit
rules:
- name: Reddit API Rules
  rule_count: 12
  severity_counts:
    error: 3
    hint: 0
    info: 1
    warn: 8
  slug: reddit-rules
skills: []
slug: reddit
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: reddit\nname: Reddit\ndescription: >-\n  Reddit is a social news aggregation, discussion, and community platform where\n  users submit, vote, and comment on content organized into topic-based\n  communities called subreddits. Reddit provides developer APIs for accessing\n  platform data, managing communities, running advertising campaigns, and\n  embedding content. The Reddit Data API provides access to posts, comments,\n  subreddits, user profiles, and moderation tools via OAuth 2.0. The Reddit\n  Ads API enables programmatic management of advertising campaigns, audiences,\n  and conversion tracking. All API access requires OAuth 2.0 authentication\n  via the oauth.reddit.com server at 60 requests per minute.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Advertising\n  - Communities\n  - Content\n  - Social Media\n  - Social News\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/reddit/refs/heads/main/apis.yml\n\
  created: '2026-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: reddit:data-api\n    name: Reddit Data API\n    description: >-\n      The Reddit Data API provides programmatic access to Reddit content\n      including subreddits, posts, comments, user profiles, and voting data.\n      Developers can use the API to read and submit content, manage subreddits,\n      search across the platform, interact with Reddit communities, handle\n      private messages, and manage flair. All requests require OAuth 2.0\n      authentication via oauth.reddit.com with rate limits of 60 requests per\n      minute for authenticated clients. A Data API Terms agreement is required\n      for high-volume access.\n    humanURL: https://www.reddit.com/dev/api\n    baseURL: https://oauth.reddit.com\n    tags:\n      - Comments\n      - Communities\n      - Content\n      - Posts\n      - Social Media\n      - Subreddits\n    properties:\n      - type: Documentation\n        url: https://www.reddit.com/dev/api\n\
  \      - type: Authentication\n        url: https://github.com/reddit-archive/reddit/wiki/OAuth2\n      - type: Terms of Service\n        url: https://www.redditinc.com/policies/data-api-terms\n      - type: OpenAPI\n        url: openapi/reddit-data-api-openapi.yml\n\n  - aid: reddit:ads-api\n    name: Reddit Ads API\n    description: >-\n      The Reddit Ads API allows advertisers and their marketing partners to\n      programmatically create, edit, manage, and report on advertising campaigns\n      on the Reddit platform. It provides endpoints for managing ad accounts,\n      campaigns, ad groups, ads, creatives, targeting configurations, custom\n      audiences (email lists, mobile IDs, pixel-based), conversion pixels, and\n      performance reporting. Authentication uses OAuth 2.0 with a rate limit of\n      one request per second per advertiser account.\n    humanURL: https://ads-api.reddit.com/docs/\n    baseURL: https://ads-api.reddit.com/api/v3\n    tags:\n      - Advertising\n\
  \      - Campaigns\n      - Marketing\n      - Social Media\n      - Targeting\n    properties:\n      - type: Documentation\n        url: https://ads-api.reddit.com/docs/\n      - type: Terms of Service\n        url: https://business.reddithelp.com/s/article/Reddit-Ads-API-Terms\n      - type: OpenAPI\n        url: openapi/reddit-ads-api-openapi.yml\n\n  - aid: reddit:embeds\n    name: Reddit Embeds (oEmbed)\n    description: >-\n      Reddit Embeds allows developers and content creators to embed Reddit posts\n      and comments directly into external websites and applications. The service\n      provides oEmbed endpoints that return embed codes and metadata for rendering\n      Reddit content in a visually consistent format outside of the Reddit\n      platform. It follows the oEmbed specification for content discovery and\n      embedding, returning HTML embed code for any Reddit post or comment URL.\n    humanURL: https://oembed.com/\n    baseURL: https://www.reddit.com\n    tags:\n\
  \      - Content\n      - Embedding\n      - oEmbed\n      - Social Media\n    properties:\n      - type: Documentation\n        url: https://support.reddithelp.com/hc/en-us/articles/14945211791892-Developer-Platform-Accessing-Reddit-Data\n      - type: OpenAPI\n        url: openapi/reddit-embeds-openapi.yml\n\n  - aid: reddit:oauth\n    name: Reddit OAuth 2.0 Authorization\n    description: >-\n      Reddit's OAuth 2.0 authorization system provides authentication for all\n      Reddit API access. Developers register applications at reddit.com/prefs/apps\n      to obtain client credentials. Supported grant types include authorization_code\n      (for user-delegated access), client_credentials (for app-only access), and\n      implicit (for installed apps). Access tokens are obtained from\n      https://www.reddit.com/api/v1/access_token and must be refreshed using\n      refresh tokens. All scopes and permissions are listed at\n      https://www.reddit.com/api/v1/scopes.\n    humanURL:\
  \ https://github.com/reddit-archive/reddit/wiki/OAuth2\n    baseURL: https://www.reddit.com/api/v1\n    tags:\n      - Authentication\n      - Authorization\n      - OAuth 2.0\n      - Security\n    properties:\n      - type: Documentation\n        url: https://github.com/reddit-archive/reddit/wiki/OAuth2\n      - type: Scopes\n        url: https://www.reddit.com/api/v1/scopes\n      - type: App Registration\n        url: https://www.reddit.com/prefs/apps\n\ncommon:\n  - type: Website\n    url: https://www.reddit.com\n  - type: Developer Portal\n    url: https://www.reddit.com/dev/api\n  - type: Documentation\n    url: https://support.reddithelp.com/hc/en-us/articles/16160319875092-Reddit-Data-API-Wiki\n  - type: GitHub Organization\n    url: https://github.com/reddit-archive\n  - type: Blog\n    url: https://www.redditinc.com/blog\n  - type: Privacy Policy\n    url: https://www.reddit.com/policies/privacy-policy\n  - type: Terms of Service\n    url: https://www.redditinc.com/policies/user-agreement\n\
  \  - type: Status\n    url: https://www.redditstatus.com/\n  - type: Support\n    url: https://support.reddithelp.com/hc/en-us\n  - type: Sign Up\n    url: https://www.reddit.com/register\n  - type: OpenAPI\n    url: openapi/reddit-data-api-openapi.yml\n  - type: OpenAPI\n    url: openapi/reddit-ads-api-openapi.yml\n  - type: OpenAPI\n    url: openapi/reddit-embeds-openapi.yml\n  - type: JSONSchema\n    url: json-schema/reddit-post-schema.json\n  - type: JSONSchema\n    url: json-schema/reddit-comment-schema.json\n  - type: JSONSchema\n    url: json-schema/reddit-subreddit-schema.json\n  - type: JSONLDContext\n    url: json-ld/reddit-context.jsonld\n  - type: JSONStructure\n    url: json-structure/reddit-post-structure.json\n  - type: SpectralRuleset\n    url: rules/reddit-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/community-engagement.yaml\n  - type: NaftikoCapability\n    url: capabilities/advertising.yaml\n  - type: Vocabulary\n    url: vocabulary/reddit-vocabulary.yml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/reddit/refs/heads/main/apis.yml
tags:
- Advertising
- Communities
- Content
- Social Media
- Social News
url: https://raw.githubusercontent.com/api-evangelist/reddit/refs/heads/main/apis.yml
use_cases: []
---
