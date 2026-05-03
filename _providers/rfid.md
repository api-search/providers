---
api_count: 4
apis:
- description: 'Zebra Technologies provides cloud-based REST APIs for managing RFID readers, collecting tag data, and integrating RFID intelligence into enterprise applications. Cloud Connect for RFID enables remote '
  name: Zebra Data Services for RFID
  slug: zebra-rfid-data-services
- description: ClearStream provides a RESTful API for RFID and Bluetooth Beacon technology, giving developers full control of RFID readers and gateways to integrate tag data into existing applications and websites.
  name: ClearStream RFID REST API
  slug: clearstream-rfid-api
- description: Impinj provides APIs for RAIN RFID reader management and item location data, enabling real-time item-level inventory visibility in retail, healthcare, and manufacturing environments.
  name: Impinj ItemSense RAIN RFID API
  slug: impinj-itemsense-api
- description: The Electronic Product Code Information Services (EPCIS) is GS1's standard for sharing supply chain visibility data. EPCIS 2.0 supports REST/HTTP and JSON-LD for capturing and querying RFID events inc
  name: GS1 EPCIS API
  slug: gs1-epcis-api
common:
- title: ''
  type: Website
  url: https://developer.zebra.com/products/rfid
- title: ''
  type: Website
  url: https://www.clearstreamrfid.com/
- title: ''
  type: Website
  url: https://www.gs1.org/standards/epcis
- title: ''
  type: Standard
  url: https://www.gs1.org/standards/epc-rfid-epcis-id-keys/epc-rfid-tds/1-12
created: '2025-01-01'
description: Radio-Frequency Identification (RFID) is an automatic identification technology that uses radio waves to read and capture information stored on a tag attached to an object. RFID powers supply chain visibility, inventory management, asset tracking, access control, and contactless payments. The RFID ecosystem includes hardware vendors (Zebra, Impinj, Alien Technology), software platforms (ClearStream, TagMatiks, Jetstream), and open standards (GS1 EPCIS, EPC Tag Data Standard, ISO 18000 series).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 27
  name: Rfid Context
  property_count: 1
  slug: rfid-context
layout: provider
modified: '2026-05-02'
name: RFID
skills: []
slug: rfid
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rfid\nname: RFID\ndescription: >-\n  Radio-Frequency Identification (RFID) is an automatic identification technology\n  that uses radio waves to read and capture information stored on a tag attached to\n  an object. RFID powers supply chain visibility, inventory management, asset\n  tracking, access control, and contactless payments. The RFID ecosystem includes\n  hardware vendors (Zebra, Impinj, Alien Technology), software platforms\n  (ClearStream, TagMatiks, Jetstream), and open standards (GS1 EPCIS, EPC Tag Data\n  Standard, ISO 18000 series).\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - RFID\n  - IoT\n  - Supply Chain\n  - Inventory Management\n  - Asset Tracking\n  - GS1\n  - EPCIS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/rfid/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rfid:zebra-rfid-data-services\n    name:\
  \ Zebra Data Services for RFID\n    description: >-\n      Zebra Technologies provides cloud-based REST APIs for managing RFID readers,\n      collecting tag data, and integrating RFID intelligence into enterprise\n      applications. Cloud Connect for RFID enables remote reader management\n      and data collection via REST API.\n    humanURL: https://developer.zebra.com/data-services-rfid-developer-guide\n    baseURL: https://api.zebra.com\n    tags:\n      - RFID\n      - Asset Tracking\n      - Inventory\n      - Zebra\n    properties:\n      - type: Documentation\n        url: https://developer.zebra.com/data-services-rfid-developer-guide\n      - type: Portal\n        url: https://developer.zebra.com/products/rfid\n\n  - aid: rfid:clearstream-rfid-api\n    name: ClearStream RFID REST API\n    description: >-\n      ClearStream provides a RESTful API for RFID and Bluetooth Beacon technology,\n      giving developers full control of RFID readers and gateways to integrate\n      tag\
  \ data into existing applications and websites.\n    humanURL: https://www.clearstreamrfid.com/software/integrate/api/\n    tags:\n      - RFID\n      - Bluetooth Beacon\n      - Asset Tracking\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://www.clearstreamrfid.com/software/integrate/api/\n\n  - aid: rfid:impinj-itemsense-api\n    name: Impinj ItemSense RAIN RFID API\n    description: >-\n      Impinj provides APIs for RAIN RFID reader management and item location\n      data, enabling real-time item-level inventory visibility in retail,\n      healthcare, and manufacturing environments.\n    humanURL: https://developer.impinj.com/\n    tags:\n      - RFID\n      - RAIN RFID\n      - Retail\n      - Healthcare\n      - Impinj\n    properties:\n      - type: Documentation\n        url: https://developer.impinj.com/\n\n  - aid: rfid:gs1-epcis-api\n    name: GS1 EPCIS API\n    description: >-\n      The Electronic Product Code Information Services (EPCIS)\
  \ is GS1's standard\n      for sharing supply chain visibility data. EPCIS 2.0 supports REST/HTTP and\n      JSON-LD for capturing and querying RFID events including Object, Aggregation,\n      Transaction, Transformation, and Association events.\n    humanURL: https://www.gs1.org/standards/epcis\n    tags:\n      - GS1\n      - EPCIS\n      - Supply Chain\n      - EPC\n      - Standard\n    properties:\n      - type: Documentation\n        url: https://www.gs1.org/standards/epcis\n\nfeatures:\n  - name: Tag Reading\n    description: Reading and decoding EPC/ISO RFID tags at item, case, and pallet levels\n  - name: Reader Management\n    description: Remote configuration, firmware update, and monitoring of RFID fixed and handheld readers\n  - name: Event Capture\n    description: EPCIS-compliant event capture for object events, aggregation events, and transaction events\n  - name: Inventory Visibility\n    description: Real-time item-level inventory counts and location tracking\n  - name:\
  \ Supply Chain Traceability\n    description: End-to-end product journey tracking from manufacture to point of sale\n  - name: Access Control\n    description: RFID-based employee and visitor access management\nuseCases:\n  - name: Retail Inventory Management\n    description: Automated cycle counting and real-time inventory accuracy with item-level RFID\n  - name: Supply Chain Visibility\n    description: Track products through manufacturing, distribution, and retail using EPCIS events\n  - name: Asset Tracking\n    description: Track tools, equipment, and IT assets in real time across facilities\n  - name: Healthcare Asset Management\n    description: Track medical equipment, surgical kits, and pharmaceutical inventory\n  - name: Access Control\n    description: RFID-based building access, parking management, and visitor management\ncommon:\n  - type: Website\n    url: https://developer.zebra.com/products/rfid\n  - type: Website\n    url: https://www.clearstreamrfid.com/\n  - type: Website\n\
  \    url: https://www.gs1.org/standards/epcis\n  - type: Standard\n    url: https://www.gs1.org/standards/epc-rfid-epcis-id-keys/epc-rfid-tds/1-12\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rfid/refs/heads/main/apis.yml
tags:
- RFID
- IoT
- Supply Chain
- Inventory Management
- Asset Tracking
- GS1
- EPCIS
url: https://raw.githubusercontent.com/api-evangelist/rfid/refs/heads/main/apis.yml
use_cases: []
---
