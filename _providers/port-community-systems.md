---
api_count: 2
api_specs:
- filename: portbase-port-community-openapi.yml
  format: yaml
  label: Portbase Port Community System API
  slug: portbase
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/port-community-systems/refs/heads/main/openapi/portbase-port-community-openapi.yml
apis:
- description: Portbase is the Dutch Port Community System providing APIs for customs declarations, cargo manifests, vessel call notifications, berth planning, and port logistics coordination at the Port of Rotterda
  name: Portbase Port Community System API
  slug: portbase
- description: The International Port Community Systems Association (IPCSA) represents Port Community System operators and Maritime Single Window operators worldwide. Member PCS platforms provide APIs for customs de
  name: IPCSA Port Community Systems API
  slug: ipcsa
asyncapis:
- description: Portbase publishes real-time vessel call and cargo events via webhooks to connected port community members. Events notify subscribers of vessel status changes, customs release notifications, and conta
  name: Portbase Vessel Events API
  slug: portbase-vessel-events-asyncapi
common:
- title: ''
  type: Website
  url: https://www.ipcsa.international/
- title: ''
  type: Portal
  url: https://www.ipcsa.international/
- title: ''
  type: Documentation
  url: https://www.ipcsa.international/
created: '2026-03-18'
description: Port Community Systems (PCS) are neutral and open electronic platforms enabling intelligent and secure exchange of information between public and private stakeholders to optimise, manage, and automate efficient port and logistics processes through a single submission of data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Portbase Context
  property_count: 30
  slug: portbase-context
layout: provider
modified: '2026-04-28'
name: Port Community Systems
skills: []
slug: port-community-systems
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: port-community-systems\nname: Port Community Systems\ndescription: >-\n  Port Community Systems (PCS) are neutral and open electronic platforms\n  enabling intelligent and secure exchange of information between public and\n  private stakeholders to optimise, manage, and automate efficient port and\n  logistics processes through a single submission of data.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Maritime\n  - Port\n  - Logistics\n  - Customs\n  - Cargo\n  - Shipping\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/port-community-systems/refs/heads/main/apis.yml\ncreated: '2026-03-18'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: port-community-systems:portbase\n    name: Portbase Port Community System API\n    description: >-\n      Portbase is the Dutch Port Community System providing APIs for customs\n      declarations, cargo manifests, vessel call notifications,\
  \ berth planning,\n      and port logistics coordination at the Port of Rotterdam and Amsterdam,\n      connecting shipping lines, freight forwarders, customs authorities, and\n      terminal operators.\n    humanURL: https://www.portbase.com/en/\n    tags:\n      - Maritime\n      - Port\n      - Customs\n      - Cargo\n      - Netherlands\n    properties:\n      - type: Documentation\n        url: https://www.portbase.com/en/\n      - type: OpenAPI\n        url: openapi/portbase-port-community-openapi.yml\n      - type: AsyncAPI\n        url: asyncapi/portbase-vessel-events-asyncapi.yml\n      - type: JSONSchema\n        url: json-schema/portbase-vessel-call-schema.json\n      - type: JSONLDContext\n        url: json-ld/portbase-context.jsonld\n  - aid: port-community-systems:ipcsa\n    name: IPCSA Port Community Systems API\n    description: >-\n      The International Port Community Systems Association (IPCSA) represents\n      Port Community System operators and Maritime Single Window\
  \ operators\n      worldwide. Member PCS platforms provide APIs for customs declarations,\n      cargo manifests, vessel call data, and port logistics coordination using\n      REST and EDIFACT protocols.\n    humanURL: https://www.ipcsa.international/\n    tags:\n      - Maritime\n      - Port\n      - Customs\n      - Cargo\n      - International\n    properties:\n      - type: Documentation\n        url: https://www.ipcsa.international/\ncommon:\n  - type: Website\n    url: https://www.ipcsa.international/\n  - type: Portal\n    url: https://www.ipcsa.international/\n  - type: Documentation\n    url: https://www.ipcsa.international/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/port-community-systems/refs/heads/main/apis.yml
tags:
- Maritime
- Port
- Logistics
- Customs
- Cargo
- Shipping
url: https://raw.githubusercontent.com/api-evangelist/port-community-systems/refs/heads/main/apis.yml
use_cases: []
---
