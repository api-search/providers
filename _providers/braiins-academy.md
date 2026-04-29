---
api_count: 3
apis:
- description: The Braiins Mining Insights Public API provides access to Bitcoin mining network statistics, hashrate data, and mining pool performance metrics. Used for research, analysis, and integration with minin
  name: Braiins Mining Insights Public API
  slug: mining-insights-api
- description: API access for Braiins Pool (formerly Slush Pool), the world's first Bitcoin mining pool. Provides miner statistics, payout data, worker management, and pool hashrate information.
  name: Braiins Pool API
  slug: braiins-pool-api
- description: Braiins OS+ is custom mining firmware for Bitcoin ASICs (Antminer series) featuring autotuning, dynamic performance scaling, and thermal management. Supports remote batch configuration via Braiins Too
  name: Braiins OS+ Firmware API
  slug: braiins-os-api
common:
- title: ''
  type: Website
  url: https://braiins.com
- title: ''
  type: Academy
  url: https://academy.braiins.com
- title: ''
  type: Pool
  url: https://braiins.com/pool
- title: ''
  type: Firmware
  url: https://braiins.com/os/plus
- title: ''
  type: StratumV2
  url: https://braiins.com/stratum-v2
- title: ''
  type: Documentation
  url: https://academy.braiins.com/os/plus-en/
created: '2025-03-01'
description: Braiins is a Bitcoin mining technology company operating the world's longest-running Bitcoin mining pool (Slush Pool, now Braiins Pool), developing Braiins OS+ mining firmware, and pioneering the Stratum V2 next-generation mining protocol. Braiins Academy provides educational resources on Bitcoin mining, and the company publishes a public Mining Insights API with network statistics. Stratum V2 increases mining security, bandwidth efficiency, and miner autonomy through decentralized transaction selection.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Braiins
skills: []
slug: braiins-academy
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: braiins-academy\nurl: https://raw.githubusercontent.com/api-evangelist/braiins-academy/refs/heads/main/apis.yml\nname: Braiins\ntags:\n  - Bitcoin Mining\n  - Cryptocurrency\n  - Mining Pool\n  - Mining Firmware\n  - Blockchain\n  - Stratum V2\ntype: Index\nx-type: company\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-21'\nposition: Consumer\ndescription: >-\n  Braiins is a Bitcoin mining technology company operating the world's longest-running\n  Bitcoin mining pool (Slush Pool, now Braiins Pool), developing Braiins OS+ mining\n  firmware, and pioneering the Stratum V2 next-generation mining protocol. Braiins\n  Academy provides educational resources on Bitcoin mining, and the company publishes\n  a public Mining Insights API with network statistics. Stratum V2 increases mining\n  security, bandwidth efficiency, and miner autonomy through decentralized transaction\n  selection.\n\
  apis:\n  - aid: braiins-academy:mining-insights-api\n    name: Braiins Mining Insights Public API\n    tags:\n      - Bitcoin Mining\n      - Mining Statistics\n      - Network Data\n      - Hashrate\n    humanURL: https://academy.braiins.com/en/mining-insights/public-api/\n    properties:\n      - url: https://academy.braiins.com/en/mining-insights/public-api/\n        type: Documentation\n    description: >-\n      The Braiins Mining Insights Public API provides access to Bitcoin mining\n      network statistics, hashrate data, and mining pool performance metrics.\n      Used for research, analysis, and integration with mining management tools.\n  - aid: braiins-academy:braiins-pool-api\n    name: Braiins Pool API\n    tags:\n      - Mining Pool\n      - Bitcoin\n      - Hashrate\n      - Payouts\n    humanURL: https://braiins.com/pool\n    properties:\n      - url: https://braiins.com/pool\n        type: Documentation\n    description: >-\n      API access for Braiins Pool (formerly\
  \ Slush Pool), the world's first Bitcoin\n      mining pool. Provides miner statistics, payout data, worker management,\n      and pool hashrate information.\n  - aid: braiins-academy:braiins-os-api\n    name: Braiins OS+ Firmware API\n    tags:\n      - Mining Firmware\n      - ASIC\n      - Autotuning\n      - Performance\n    humanURL: https://braiins.com/os/plus\n    properties:\n      - url: https://braiins.com/os/plus\n        type: Documentation\n    description: >-\n      Braiins OS+ is custom mining firmware for Bitcoin ASICs (Antminer series)\n      featuring autotuning, dynamic performance scaling, and thermal management.\n      Supports remote batch configuration via Braiins Toolbox and integrates with\n      Braiins Pool for 0% effective pool fee.\ncommon:\n  - type: Website\n    url: https://braiins.com\n  - type: Academy\n    url: https://academy.braiins.com\n  - type: Pool\n    url: https://braiins.com/pool\n  - type: Firmware\n    url: https://braiins.com/os/plus\n  -\
  \ type: StratumV2\n    url: https://braiins.com/stratum-v2\n  - type: Documentation\n    url: https://academy.braiins.com/os/plus-en/\nproperties:\n  - type: x-domain\n    value: braiins.com\n  - type: x-founded\n    value: '2011'\n  - type: x-headquarters\n    value: Prague, Czech Republic\n  - type: x-industry\n    value: Bitcoin Mining Technology\n  - type: x-products\n    value: Braiins Pool, Braiins OS+, Braiins Toolbox, Stratum V2, Braiins Academy\n  - type: x-protocol\n    value: Stratum V2 - next-generation Bitcoin mining protocol\n  - type: x-stratum-v2-features\n    value: >-\n      Enhanced security (prevents MITM attacks and hashrate hijacking), bandwidth\n      efficiency, miner-side transaction selection, decentralization improvement\n  - type: x-firmware-features\n    value: >-\n      Autotuning per-chip frequency calibration, dynamic thermal management,\n      overclocking, underclocking, batch remote configuration, 24/7 support\n  - type: x-supported-hardware\n    value:\
  \ Antminer S21 series, S19 series, T19, S17 series, S9 series\n  - type: x-capabilities\n    value: >-\n      Mining pool management, firmware-based performance optimization, hashrate\n      monitoring, mining network analytics, Stratum V2 protocol implementation\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/braiins-academy/refs/heads/main/apis.yml
tags:
- Bitcoin Mining
- Cryptocurrency
- Mining Pool
- Mining Firmware
- Blockchain
- Stratum V2
url: https://raw.githubusercontent.com/api-evangelist/braiins-academy/refs/heads/main/apis.yml
use_cases: []
---
