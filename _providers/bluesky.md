---
api_count: 2
api_specs:
- filename: bluesky-openapi.yml
  format: yaml
  label: Bluesky API
  slug: bluesky-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/bluesky/refs/heads/main/openapi/bluesky-openapi.yml
apis:
- description: The Bluesky API allows you to work programmatically with actors, feeds, graph, conversations, and other resources available for the the Bluesky app and social network.
  name: Bluesky API
  slug: bluesky-api
- description: Jetstream is a simplified JSON event stream for the AT Protocol that converts CBOR-encoded MST blocks from the firehose into JSON objects over WebSocket connections, making it easier to consume real-t
  name: Bluesky Jetstream
  slug: bluesky-jetstream
common:
- title: ''
  type: Bots
  url: https://docs.bsky.app/docs/starter-templates/bots
- title: ''
  type: Support
  url: https://docs.bsky.app/docs/category/support
- title: ''
  type: Blog
  url: https://docs.bsky.app/blog
- title: ''
  type: GettingStarted
  url: https://docs.bsky.app/docs/get-started
- title: ''
  type: Templates
  url: https://docs.bsky.app/docs/category/starter-templates
- title: ''
  type: Tutorials
  url: https://docs.bsky.app/docs/category/tutorials
- title: ''
  type: Newsletter
  url: https://docs.bsky.app/docs/support/mailing-list
- title: ''
  type: PostmanWorkspace
  url: https://www.postman.com/api-evangelist/bluesky/overview
- title: ''
  type: Guidelines
  url: https://docs.bsky.app/docs/support/developer-guidelines
- title: ''
  type: CustomFeeds
  url: https://docs.bsky.app/docs/starter-templates/custom-feeds
- title: ''
  type: Protocol
  url: https://docs.bsky.app/docs/advanced-guides/atproto
- title: ''
  type: AdvancedGuides
  url: https://docs.bsky.app/docs/category/advanced-guides
- title: ''
  type: TermsOfService
  url: https://bsky.social/about/support/tos
- title: ''
  type: PrivacyPolicy
  url: https://bsky.social/about/support/privacy-policy
- title: ''
  type: CommunityGuidelines
  url: https://bsky.social/about/support/community-guidelines
- title: ''
  type: SDKs
  url: https://atproto.com/sdks
- title: ''
  type: ProtocolOverview
  url: https://atproto.com/guides/overview
- title: ''
  type: Specifications
  url: https://atproto.com/
- title: ''
  type: GitHub Org
  url: https://github.com/bluesky-social
- title: ''
  type: GitHubRepository
  url: https://github.com/bluesky-social/atproto
- title: ''
  type: GitHubRepository
  url: https://github.com/bluesky-social/feed-generator
- title: ''
  type: GitHubRepository
  url: https://github.com/bluesky-social/ozone
- title: ''
  type: Forum
  url: https://github.com/bluesky-social/atproto/discussions
- title: ''
  type: Summary
  url: ''
created: '2024-11-16'
description: API for the Bluesky decentralized social network built on the AT Protocol.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bluesky
skills: []
slug: bluesky
solutions: []
source_filename: apis.yml
source_yaml: "aid: bluesky\nurl: https://raw.githubusercontent.com/api-search/bluesky/refs/heads/main/apis.yml\napis:\n  - aid: bluesky:bluesky-api\n    name: Bluesky API\n    tags:\n      - Social Networks\n    humanURL: https://docs.bsky.app/\n    properties:\n      - url: https://docs.bsky.app/\n        type: Documentation\n      - url: openapi/bluesky-openapi.yml\n        type: OpenAPI\n      - url: https://www.postman.com/api-evangelist/bluesky/collection/ubo2xuv/bluesky-api\n        type: PostmanCollection\n      - url: https://docs.bsky.app/docs/api/at-protocol-xrpc-api\n        type: APIReference\n      - url: https://docs.bsky.app/docs/category/http-reference\n        type: HTTPReference\n      - url: https://docs.bsky.app/docs/advanced-guides/api-directory\n        type: APIDirectory\n      - url: https://docs.bsky.app/docs/advanced-guides/oauth-client\n        type: Authentication\n      - url: https://docs.bsky.app/docs/advanced-guides/rate-limits\n        type: RateLimits\n\
  \      - url: https://docs.bsky.app/docs/advanced-guides/firehose\n        type: Firehose\n      - url: https://docs.bsky.app/docs/advanced-guides/moderation\n        type: Moderation\n      - url: https://docs.bsky.app/docs/advanced-guides/resolving-identities\n        type: Identity\n      - data:\n          numberOfAPITags: 1\n          numberOfAPIGetMethods: 93\n          numberOfAPIOperations: 168\n          numberOfAPIParameters: 2\n          numberOfAPIProperties: 4\n          numberOfAPIPutMethods: 0\n          numberOfAPIPostMethods: 75\n          numberOfAPIPatchMethods: 0\n          numberOfAPIDeleteMethods: 0\n          numberOfAPIOptionMethods: 0\n        type: Summary\n    description: The Bluesky API allows you to work programmatically with actors, feeds, graph, conversations, and other resources available for the the Bluesky app and social network.\n  - aid: bluesky:bluesky-jetstream\n    name: Bluesky Jetstream\n    tags:\n      - Events\n      - Social Networks\n    \
  \  - Streaming\n    humanURL: https://docs.bsky.app/blog/jetstream\n    properties:\n      - url: https://docs.bsky.app/blog/jetstream\n        type: Documentation\n      - url: https://github.com/bluesky-social/jetstream\n        type: GitHubRepository\n    description: Jetstream is a simplified JSON event stream for the AT Protocol that converts CBOR-encoded MST blocks from the firehose into JSON objects over WebSocket connections, making it easier to consume real-time Bluesky network events for building feed generators, bots, and search engines.\nname: Bluesky\ntags:\n  - At-Protocol\n  - Decentralized\n  - Federated\n  - Open-Source\n  - Social Networks\n  - Social-Media\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncommon:\n  - url: https://docs.bsky.app/docs/starter-templates/bots\n    name: Bots | Bluesky\n    type: Bots\n  - url: https://docs.bsky.app/docs/category/support\n    name: Support | Bluesky\n    type:\
  \ Support\n  - url: https://docs.bsky.app/blog\n    name: Blog | Bluesky\n    type: Blog\n  - url: https://docs.bsky.app/docs/get-started\n    name: Get Started | Bluesky\n    type: GettingStarted\n  - url: https://docs.bsky.app/docs/category/starter-templates\n    name: Starter Templates | Bluesky\n    type: Templates\n  - url: https://docs.bsky.app/docs/category/tutorials\n    name: Tutorials | Bluesky\n    type: Tutorials\n  - url: https://docs.bsky.app/docs/support/mailing-list\n    name: Developer Mailing List | Bluesky\n    type: Newsletter\n  - url: https://www.postman.com/api-evangelist/bluesky/overview\n    name: Postman Workspace\n    type: PostmanWorkspace\n    description: This is the dedicated workspace for the Bluesky API, storing collections and automations that can be used.\n  - url: https://docs.bsky.app/docs/support/developer-guidelines\n    name: Developer Guidelines | Bluesky\n    type: Guidelines\n  - url: https://docs.bsky.app/docs/starter-templates/custom-feeds\n\
  \    name: Custom Feeds | Bluesky\n    type: CustomFeeds\n  - url: https://docs.bsky.app/docs/advanced-guides/atproto\n    name: AT Protocol Guide | Bluesky\n    type: Protocol\n  - url: https://docs.bsky.app/docs/category/advanced-guides\n    name: Advanced Guides | Bluesky\n    type: AdvancedGuides\n  - url: https://bsky.social/about/support/tos\n    name: Terms of Service | Bluesky\n    type: TermsOfService\n  - url: https://bsky.social/about/support/privacy-policy\n    name: Privacy Policy | Bluesky\n    type: PrivacyPolicy\n  - url: https://bsky.social/about/support/community-guidelines\n    name: Community Guidelines | Bluesky\n    type: CommunityGuidelines\n  - url: https://atproto.com/sdks\n    name: AT Protocol SDKs\n    type: SDKs\n  - url: https://atproto.com/guides/overview\n    name: AT Protocol Overview\n    type: ProtocolOverview\n  - url: https://atproto.com/\n    name: AT Protocol Specifications\n    type: Specifications\n  - url: https://github.com/bluesky-social\n  \
  \  name: Bluesky GitHub Organization\n    type: GitHub Org\n  - url: https://github.com/bluesky-social/atproto\n    name: AT Protocol Reference Implementation\n    type: GitHubRepository\n  - url: https://github.com/bluesky-social/feed-generator\n    name: Feed Generator Starter Kit\n    type: GitHubRepository\n  - url: https://github.com/bluesky-social/ozone\n    name: Ozone Moderation Tool\n    type: GitHubRepository\n  - url: https://github.com/bluesky-social/atproto/discussions\n    name: GitHub Discussions | AT Protocol\n    type: Forum\n  - data:\n      numberOfAPITags: 2\n      numberOfAPIPaths: 168\n      numberOfAPISchema:\n      numberOfAPIGetMethods: 93\n      numberOfAPIParameters: 2\n      numberOfAPIProperties: 4\n      numberOfAPIPutMethods: 0\n      numberOfAPIPostMethods: 75\n      numberOfAPIPatchMethods: 0\n      numberOfAPIDeleteMethods: 0\n      numberOfAPIOptionMethods: 0\n    type: Summary\ncreated: '2024-11-16'\nmodified: '2026-04-21'\nposition: Consumer\ndescription:\
  \ >-\n  API for the Bluesky decentralized social network built on the AT Protocol.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n  - name: Bluesky Social PBC\n    email: support@bsky.app\n    url: https://bsky.social\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bluesky/refs/heads/main/apis.yml
tags:
- At-Protocol
- Decentralized
- Federated
- Open-Source
- Social Networks
- Social-Media
url: https://raw.githubusercontent.com/api-search/bluesky/refs/heads/main/apis.yml
use_cases: []
---
