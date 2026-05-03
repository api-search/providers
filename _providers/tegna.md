---
api_count: 2
api_specs:
- filename: tegna-audience-one-openapi.yml
  format: yaml
  label: TEGNA AudienceOne API
  slug: audience-one-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tegna/refs/heads/main/openapi/tegna-audience-one-openapi.yml
- filename: tegna-premion-openapi.yml
  format: yaml
  label: TEGNA Premion OTT Advertising API
  slug: premion-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tegna/refs/heads/main/openapi/tegna-premion-openapi.yml
apis:
- description: TEGNA AudienceOne is a first-party data targeting platform enabling advertisers to reach audiences across TEGNA's 64 local television brands in 51 markets using privacy-first targeting. The platform p
  name: TEGNA AudienceOne API
  slug: audience-one-api
- description: Premion is TEGNA's over-the-top (OTT) and connected TV (CTV) advertising platform, enabling advertisers to reach audiences across premium streaming services including Roku, Hulu, Amazon Fire TV, and o
  name: TEGNA Premion OTT Advertising API
  slug: premion-api
capabilities:
- description: Unified media advertising capability for TEGNA, combining AudienceOne first-party digital targeting and Premion OTT/CTV streaming advertising. Enables advertisers, media buyers, and agency partners to
  name: TEGNA Media Advertising
  slug: media-advertising
common:
- title: ''
  type: Website
  url: https://www.tegna.com
- title: ''
  type: Website
  url: https://www.nexstar.tv/
- title: ''
  type: Advertising
  url: https://www.tegna.com/advertise/
- title: ''
  type: Documentation
  url: https://www.tegna.com/advertise/solutions/digital/
- title: ''
  type: Documentation
  url: https://www.tegna.com/advertise/solutions/broadcast/
- title: ''
  type: Documentation
  url: https://www.tegna.com/advertise/solutions/streaming/
- title: ''
  type: Website
  url: https://premion.com/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/tegna
created: '2026-03-24'
description: TEGNA Inc. is an American broadcast, digital media, and marketing services company headquartered in Tysons, Virginia, operating as a subsidiary of Nexstar Media Group following FCC approval of the $6.2 billion acquisition in March 2026. TEGNA operates 64 full-power broadcast television stations across 51 U.S. markets, reaching approximately 39 percent of all television households. TEGNA offers digital marketing solutions including AudienceOne first-party data targeting, OTT/CTV advertising through its Premion platform, and the TEGNA Marketing Solutions full-service agency. The company provides advertising APIs and programmatic integrations for digital, broadcast, streaming, and connected TV advertising campaigns.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 37
  name: Tegna Context
  property_count: 0
  slug: tegna-context
layout: provider
modified: '2026-05-03'
name: TEGNA
rules:
- name: TEGNA API Rules
  rule_count: 10
  severity_counts:
    error: 3
    hint: 1
    info: 0
    warn: 6
  slug: tegna-rules
skills: []
slug: tegna
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tegna\nname: TEGNA\ndescription: >-\n  TEGNA Inc. is an American broadcast, digital media, and marketing services\n  company headquartered in Tysons, Virginia, operating as a subsidiary of\n  Nexstar Media Group following FCC approval of the $6.2 billion acquisition\n  in March 2026. TEGNA operates 64 full-power broadcast television stations\n  across 51 U.S. markets, reaching approximately 39 percent of all television\n  households. TEGNA offers digital marketing solutions including AudienceOne\n  first-party data targeting, OTT/CTV advertising through its Premion platform,\n  and the TEGNA Marketing Solutions full-service agency. The company provides\n  advertising APIs and programmatic integrations for digital, broadcast,\n  streaming, and connected TV advertising campaigns.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Broadcasting\n  - Media\n  - Television\n  - Digital Advertising\n  - OTT\n  - CTV\n  -\
  \ Fortune 500\nurl: https://raw.githubusercontent.com/api-evangelist/tegna/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: tegna:audience-one-api\n    name: TEGNA AudienceOne API\n    description: >-\n      TEGNA AudienceOne is a first-party data targeting platform enabling\n      advertisers to reach audiences across TEGNA's 64 local television brands\n      in 51 markets using privacy-first targeting. The platform provides\n      programmatic access to audience segments, campaign management, and\n      performance analytics for digital, display, native, and pre-roll video\n      advertising. Supports geofencing, retargeting, and precision targeting\n      without third-party cookies.\n    humanURL: https://www.tegna.com/advertise/solutions/digital/\n    baseURL: https://api.tegna.com\n    tags:\n      - Advertising\n      - Audience Targeting\n      - Digital Media\n      - First-Party Data\n      - Programmatic\n\
  \    properties:\n      - type: Documentation\n        url: https://www.tegna.com/advertise/solutions/digital/\n      - type: OpenAPI\n        url: openapi/tegna-audience-one-openapi.yml\n      - type: JSONSchema\n        url: json-schema/tegna-campaign-schema.json\n  - aid: tegna:premion-api\n    name: TEGNA Premion OTT Advertising API\n    description: >-\n      Premion is TEGNA's over-the-top (OTT) and connected TV (CTV) advertising\n      platform, enabling advertisers to reach audiences across premium streaming\n      services including Roku, Hulu, Amazon Fire TV, and other OTT platforms.\n      The Premion API provides campaign creation, audience targeting, impression\n      delivery, and performance reporting for streaming video advertising at\n      local and national scale.\n    humanURL: https://premion.com/\n    baseURL: https://api.premion.com\n    tags:\n      - OTT Advertising\n      - CTV\n      - Connected TV\n      - Streaming\n      - Video Advertising\n    properties:\n\
  \      - type: Documentation\n        url: https://premion.com/\n      - type: OpenAPI\n        url: openapi/tegna-premion-openapi.yml\ncommon:\n  - url: https://www.tegna.com\n    name: TEGNA\n    type: Website\n    description: TEGNA corporate website (redirects to Nexstar).\n  - url: https://www.nexstar.tv/\n    name: Nexstar Media Group\n    type: Website\n    description: Parent company Nexstar Media Group website.\n  - url: https://www.tegna.com/advertise/\n    name: Advertise With TEGNA\n    type: Advertising\n    description: Advertising solutions overview for TEGNA.\n  - url: https://www.tegna.com/advertise/solutions/digital/\n    name: TEGNA Digital Advertising Solutions\n    type: Documentation\n    description: Digital advertising platform documentation for TEGNA AudienceOne.\n  - url: https://www.tegna.com/advertise/solutions/broadcast/\n    name: TEGNA Broadcast Advertising\n    type: Documentation\n    description: Broadcast TV advertising solutions from TEGNA.\n  - url:\
  \ https://www.tegna.com/advertise/solutions/streaming/\n    name: TEGNA Streaming/OTT Advertising\n    type: Documentation\n    description: OTT and streaming advertising solutions from TEGNA.\n  - url: https://premion.com/\n    name: Premion OTT Advertising\n    type: Website\n    description: TEGNA's Premion OTT advertising platform.\n  - url: https://www.linkedin.com/company/tegna\n    name: TEGNA on LinkedIn\n    type: LinkedIn\n    description: TEGNA LinkedIn company page.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tegna/refs/heads/main/apis.yml
tags:
- Broadcasting
- Media
- Television
- Digital Advertising
- OTT
- CTV
- Fortune 500
url: https://raw.githubusercontent.com/api-evangelist/tegna/refs/heads/main/apis.yml
use_cases: []
---
