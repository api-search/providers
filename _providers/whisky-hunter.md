---
api_count: 1
api_specs:
- filename: whisky-hunter-openapi.yml
  format: yaml
  label: Whisky Hunter API
  slug: whisky-hunter
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/openapi/whisky-hunter-openapi.yml
apis:
- description: The Whisky Hunter API provides free, public access to historical whisky auction data aggregated from 28 online whisky auction platforms. Endpoints cover aggregated auction statistics, distillery listi
  name: Whisky Hunter API
  slug: whisky-hunter
capabilities:
- description: Unified whisky market intelligence capability composing auction data and distillery analytics from the Whisky Hunter API to support collectors, investors, and traders researching whisky market trends,
  name: Whisky Market Intelligence
  slug: whisky-market-intelligence
common:
- title: ''
  type: Website
  url: https://whiskyhunter.net
- title: ''
  type: API
  url: https://whiskyhunter.net/api/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/openapi/whisky-hunter-openapi.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/vocabulary/whisky-hunter-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/json-ld/whisky-hunter-context.jsonld
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/rules/whisky-hunter-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/capabilities/whisky-market-intelligence.yaml
created: '2025-02-24'
description: Whisky Hunter is a market research and data platform for whisky collectors, investors, traders, and enthusiasts that aggregates historical auction data from 28 online whisky auction sites into a single database. It tracks trading volumes, winning bids, lot counts, and per-distillery statistics. All trading volumes and winning bids are stated in GBP (£). The Whisky Hunter API provides free, public access to this auction data with no authentication required.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 40
  name: Whisky Hunter Context
  property_count: 0
  slug: whisky-hunter-context
layout: provider
modified: '2026-05-03'
name: Whisky Hunter
rules:
- name: Whisky Hunter API Rules
  rule_count: 9
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 7
  slug: whisky-hunter-rules
skills: []
slug: whisky-hunter
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: whisky-hunter\nname: Whisky Hunter\ndescription: >-\n  Whisky Hunter is a market research and data platform for whisky collectors, investors,\n  traders, and enthusiasts that aggregates historical auction data from 28 online whisky\n  auction sites into a single database. It tracks trading volumes, winning bids, lot counts,\n  and per-distillery statistics. All trading volumes and winning bids are stated in GBP (£).\n  The Whisky Hunter API provides free, public access to this auction data with no\n  authentication required.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Whisky\n  - Spirits\n  - Auctions\n  - Market Data\n  - Collectors\n  - Investors\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/apis.yml\ncreated: '2025-02-24'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: whisky-hunter:whisky-hunter\n\
  \    name: Whisky Hunter API\n    description: >-\n      The Whisky Hunter API provides free, public access to historical whisky auction\n      data aggregated from 28 online whisky auction platforms. Endpoints cover aggregated\n      auction statistics, distillery listings, and per-distillery historical auction data.\n      No authentication is required. All monetary values are in GBP (£). Only lots\n      actually sold (meeting reserve price) are included in trading volume calculations.\n    humanURL: https://whiskyhunter.net/api/\n    baseURL: https://whiskyhunter.net/api\n    tags:\n      - Whisky\n      - Auctions\n      - Market Data\n      - Distilleries\n      - Price Tracking\n      - Public API\n    properties:\n      - type: Documentation\n        url: https://whiskyhunter.net/api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/openapi/whisky-hunter-openapi.yml\n      - type: AuctionsData\n  \
  \      url: https://whiskyhunter.net/api/auctions_data/?format=json\n      - type: DistilleriesInfo\n        url: https://whiskyhunter.net/api/distilleries_info/?format=json\n\ncommon:\n  - type: Website\n    url: https://whiskyhunter.net\n  - type: API\n    url: https://whiskyhunter.net/api/\n  - type: OpenAPI\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/openapi/whisky-hunter-openapi.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/vocabulary/whisky-hunter-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/json-ld/whisky-hunter-context.jsonld\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/rules/whisky-hunter-rules.yml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/capabilities/whisky-market-intelligence.yaml\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/apis.yml
tags:
- Whisky
- Spirits
- Auctions
- Market Data
- Collectors
- Investors
url: https://raw.githubusercontent.com/api-evangelist/whisky-hunter/refs/heads/main/apis.yml
use_cases: []
---
