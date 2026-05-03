---
api_count: 3
apis:
- description: The Whirlpool connected appliances cloud API enables control and monitoring of Whirlpool, Maytag, KitchenAid, and Consul smart appliances including washers, dryers, ovens, refrigerators, and air condi
  name: Whirlpool Connected Appliances API
  slug: connected-appliances
- description: Whirlpool smart appliances integrate with Amazon Alexa to enable voice control of washers, dryers, ovens, and refrigerators across the Whirlpool brand portfolio. Users can start/pause laundry, check c
  name: Whirlpool Alexa Voice Control
  slug: amazon-alexa-integration
- description: Whirlpool was the first appliance company to integrate Amazon Dash Replenishment Service. Whirlpool smart washers monitor laundry detergent levels and automatically reorder supplies via Amazon when ru
  name: Whirlpool Amazon Dash Replenishment
  slug: amazon-dash-replenishment
common:
- title: ''
  type: Website
  url: https://www.whirlpool.com
- title: ''
  type: Corporate Website
  url: https://www.whirlpoolcorp.com
- title: ''
  type: Smart Appliances
  url: https://www.whirlpool.com/smart-appliances.html
- title: ''
  type: Developer Portal
  url: https://developer-latam.whirlpool.com
- title: ''
  type: Wikipedia
  url: https://en.wikipedia.org/wiki/Whirlpool_Corporation
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/whirlpool/refs/heads/main/vocabulary/whirlpool-vocabulary.yml
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/whirlpool/refs/heads/main/json-ld/whirlpool-context.jsonld
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/whirlpool/refs/heads/main/json-schema/whirlpool-appliance-schema.json
created: '2026-03-21'
description: Whirlpool Corporation is the world's only major U.S.-based manufacturer of kitchen and laundry appliances, with approximately $16 billion in annual net sales and 41,000 employees globally. Its brand portfolio includes Whirlpool, KitchenAid, JennAir, Maytag, Amana, Brastemp, Consul, and InSinkErator. Whirlpool offers connected smart appliances integrating with Amazon Alexa, Amazon Dash Replenishment, Google Assistant, and Matter for smart home automation, and provides a cloud-connected appliance API used by the Whirlpool mobile app and third-party integrations.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 44
  name: Whirlpool Context
  property_count: 0
  slug: whirlpool-context
layout: provider
modified: '2026-05-03'
name: Whirlpool Corporation
skills: []
slug: whirlpool
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: whirlpool\nname: Whirlpool Corporation\ndescription: >-\n  Whirlpool Corporation is the world's only major U.S.-based manufacturer of kitchen\n  and laundry appliances, with approximately $16 billion in annual net sales and 41,000\n  employees globally. Its brand portfolio includes Whirlpool, KitchenAid, JennAir, Maytag,\n  Amana, Brastemp, Consul, and InSinkErator. Whirlpool offers connected smart appliances\n  integrating with Amazon Alexa, Amazon Dash Replenishment, Google Assistant, and Matter\n  for smart home automation, and provides a cloud-connected appliance API used by the\n  Whirlpool mobile app and third-party integrations.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Appliances\n  - Smart Home\n  - IoT\n  - Connected Devices\n  - Fortune 500\n  - Consumer Electronics\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/whirlpool/refs/heads/main/apis.yml\ncreated: '2026-03-21'\nmodified:\
  \ '2026-05-03'\nspecificationVersion: '0.19'\nx-fortune: Fortune 500\napis:\n  - aid: whirlpool:connected-appliances\n    name: Whirlpool Connected Appliances API\n    description: >-\n      The Whirlpool connected appliances cloud API enables control and monitoring\n      of Whirlpool, Maytag, KitchenAid, and Consul smart appliances including\n      washers, dryers, ovens, refrigerators, and air conditioners. Used by the\n      official Whirlpool mobile app and third-party integrations such as Home\n      Assistant via the 6th Sense unofficial API. Authentication is via username\n      and password with brand/region selection.\n    humanURL: https://www.whirlpool.com/smart-appliances.html\n    baseURL: https://api.whrcloud.com\n    tags:\n      - Smart Appliances\n      - IoT\n      - Connected Devices\n      - Washer\n      - Dryer\n      - Oven\n      - Refrigerator\n    properties:\n      - type: Documentation\n        url: https://www.whirlpool.com/smart-appliances.html\n      - type:\
  \ Home Assistant Integration\n        url: https://www.home-assistant.io/integrations/whirlpool/\n      - type: Unofficial Python SDK\n        url: https://github.com/abmantis/whirlpool-sixth-sense\n      - type: PyPI Package\n        url: https://pypi.org/project/whirlpool-sixth-sense/\n      - type: Mobile App\n        url: https://www.whirlpool.com/home-innovations/connected-appliances/connect.html\n\n  - aid: whirlpool:amazon-alexa-integration\n    name: Whirlpool Alexa Voice Control\n    description: >-\n      Whirlpool smart appliances integrate with Amazon Alexa to enable voice control\n      of washers, dryers, ovens, and refrigerators across the Whirlpool brand portfolio.\n      Users can start/pause laundry, check cycle status, adjust oven temperature,\n      and manage refrigerator settings through Alexa-enabled devices.\n    humanURL: https://www.whirlpool.com/smart-appliances.html\n    tags:\n      - Amazon Alexa\n      - Voice Control\n      - Smart Home\n      - Integration\n\
  \    properties:\n      - type: Documentation\n        url: https://www.whirlpool.com/smart-appliances.html\n      - type: Press Release\n        url: >-\n          https://www.prnewswire.com/news-releases/whirlpool-corporation--amazon-team-up-to-deliver-next-generation-voice-controlled-appliances-300384836.html\n\n  - aid: whirlpool:amazon-dash-replenishment\n    name: Whirlpool Amazon Dash Replenishment\n    description: >-\n      Whirlpool was the first appliance company to integrate Amazon Dash Replenishment\n      Service. Whirlpool smart washers monitor laundry detergent levels and automatically\n      reorder supplies via Amazon when running low, using appliance usage data and\n      supply estimation algorithms.\n    humanURL: https://www.whirlpool.com/smart-appliances.html\n    tags:\n      - Amazon Dash\n      - Auto-Replenishment\n      - Smart Home\n      - IoT\n      - Laundry\n    properties:\n      - type: Documentation\n        url: https://www.whirlpool.com/smart-appliances.html\n\
  \      - type: News\n        url: >-\n          https://www.geekwire.com/2016/whirlpool-is-first-appliance-company-to-integrate-amazon-dash-replenishment-service/\n\ncommon:\n  - type: Website\n    url: https://www.whirlpool.com\n  - type: Corporate Website\n    url: https://www.whirlpoolcorp.com\n  - type: Smart Appliances\n    url: https://www.whirlpool.com/smart-appliances.html\n  - type: Developer Portal\n    url: https://developer-latam.whirlpool.com\n  - type: Wikipedia\n    url: https://en.wikipedia.org/wiki/Whirlpool_Corporation\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whirlpool/refs/heads/main/vocabulary/whirlpool-vocabulary.yml\n  - type: JSONLDContext\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whirlpool/refs/heads/main/json-ld/whirlpool-context.jsonld\n  - type: JSONSchema\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/whirlpool/refs/heads/main/json-schema/whirlpool-appliance-schema.json\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/whirlpool/refs/heads/main/apis.yml
tags:
- Appliances
- Smart Home
- IoT
- Connected Devices
- Fortune 500
- Consumer Electronics
url: https://raw.githubusercontent.com/api-evangelist/whirlpool/refs/heads/main/apis.yml
use_cases: []
---
