---
api_count: 2
apis:
- description: The AAM iSupplier Portal provides suppliers access to DELFORS forecasts, DELJIT releases, standard purchase orders, payment status, bulletins, specifications, manuals, PPAP documents, and ASN (Advance
  name: AAM iSupplier Portal
  slug: isupplier-portal
- description: Demand AAM provides access to genuine AAM OE replacement driveline parts for the aftermarket. The portal serves automotive parts distributors and repair shops with OE-quality driveline components.
  name: Demand AAM Aftermarket Parts Portal
  slug: demand-aam
common:
- title: ''
  type: Website
  url: https://www.aam.com/
- title: ''
  type: Portal
  url: https://www.aam.com/suppliers
created: '2026-03-23'
description: American Axle & Manufacturing (AAM), now operating as Dauch Corporation following the February 2026 acquisition of Dowlais Group (GKN Automotive and GKN Powder Metallurgy), is a global Tier 1 automotive supplier designing, engineering, and manufacturing driveline and metal forming technologies for electric, hybrid, and internal combustion vehicles. AAM operates an iSupplier Portal for supplier communication, EDI integration for forecasts and releases, and the Demand AAM aftermarket parts portal.
features:
- description: Electronic Data Interchange (EDI) integration required for all AAM suppliers, supporting DELFORS forecasts, DELJIT releases, and ASN transmission at time of shipment.
  name: EDI Integration
- description: Web-based supplier portal providing access to forecasts, purchase orders, payment status, bulletins, specifications, PPAP documents, and ASN creation tools.
  name: iSupplier Portal
- description: Mandatory ASN submission via EDI or portal at time of shipment providing visibility of in-transit material to AAM manufacturing facilities.
  name: Advanced Shipping Notification
- description: Next-generation electric drive units, eDrive systems, and driveline components for battery electric and hybrid vehicle platforms.
  name: Electric Vehicle Driveline Technology
- description: Following the February 2026 acquisition of Dowlais Group, AAM (now Dauch Corporation) integrates GKN Automotive's ePowertrain and driveline portfolio.
  name: GKN Automotive Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: ANSI X12 and EDIFACT EDI transaction sets for forecast (DELFORS), just-in-time releases (DELJIT), and Advanced Shipping Notifications.
  name: EDI Systems
- description: Integration of GKN Automotive's ePowertrain and sideshaft technology following Dauch Corporation acquisition of Dowlais Group.
  name: GKN Automotive
- description: Integration of GKN Powder Metallurgy's sintered components business following the Dowlais Group acquisition.
  name: GKN Powder Metallurgy
layout: provider
modified: '2026-04-19'
name: American Axle and Manufacturing
skills: []
slug: american-axle-and-manufacturing
solutions: []
source_yaml: "aid: american-axle-and-manufacturing\nname: American Axle and Manufacturing\ndescription: >-\n  American Axle & Manufacturing (AAM), now operating as Dauch Corporation\n  following the February 2026 acquisition of Dowlais Group (GKN Automotive and\n  GKN Powder Metallurgy), is a global Tier 1 automotive supplier designing,\n  engineering, and manufacturing driveline and metal forming technologies for\n  electric, hybrid, and internal combustion vehicles. AAM operates an iSupplier\n  Portal for supplier communication, EDI integration for forecasts and releases,\n  and the Demand AAM aftermarket parts portal.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automotive\n  - Manufacturing\n  - Driveline\n  - Automotive Supplier\n  - EDI\n  - Supply Chain\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/american-axle-and-manufacturing/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-19'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: american-axle-and-manufacturing:isupplier-portal\n    name: AAM iSupplier Portal\n    description: >-\n      The AAM iSupplier Portal provides suppliers access to DELFORS forecasts,\n      DELJIT releases, standard purchase orders, payment status, bulletins,\n      specifications, manuals, PPAP documents, and ASN (Advanced Shipping\n      Notification) transmission. EDI integration is required for all AAM\n      suppliers, with EDI or portal-based ASN submission mandatory at time\n      of shipment.\n    humanURL: https://www.aam.com/suppliers/doing-business-with-aam\n    baseURL: https://www.aam.com\n    tags:\n      - Supply Chain\n      - EDI\n      - Supplier Portal\n      - Automotive\n    properties:\n      - type: Documentation\n        url: https://www.aam.com/suppliers/doing-business-with-aam\n      - type: Portal\n        url: https://www.aam.com/suppliers/doing-business-with-aam/isupplier-faq\n\n  - aid: american-axle-and-manufacturing:demand-aam\n\
  \    name: Demand AAM Aftermarket Parts Portal\n    description: >-\n      Demand AAM provides access to genuine AAM OE replacement driveline parts\n      for the aftermarket. The portal serves automotive parts distributors and\n      repair shops with OE-quality driveline components.\n    humanURL: https://www.demandaam.com/\n    baseURL: https://www.demandaam.com\n    tags:\n      - Aftermarket\n      - Parts\n      - Automotive\n    properties:\n      - type: Documentation\n        url: https://www.demandaam.com/\n      - type: Portal\n        url: https://www.demandaam.com/\n\ncommon:\n  - type: Website\n    url: https://www.aam.com/\n  - type: Portal\n    url: https://www.aam.com/suppliers\n  - type: Features\n    data:\n      - name: EDI Integration\n        description: >-\n          Electronic Data Interchange (EDI) integration required for all AAM\n          suppliers, supporting DELFORS forecasts, DELJIT releases, and ASN\n          transmission at time of shipment.\n      -\
  \ name: iSupplier Portal\n        description: >-\n          Web-based supplier portal providing access to forecasts, purchase\n          orders, payment status, bulletins, specifications, PPAP documents,\n          and ASN creation tools.\n      - name: Advanced Shipping Notification\n        description: >-\n          Mandatory ASN submission via EDI or portal at time of shipment\n          providing visibility of in-transit material to AAM manufacturing\n          facilities.\n      - name: Electric Vehicle Driveline Technology\n        description: >-\n          Next-generation electric drive units, eDrive systems, and driveline\n          components for battery electric and hybrid vehicle platforms.\n      - name: GKN Automotive Integration\n        description: >-\n          Following the February 2026 acquisition of Dowlais Group, AAM (now\n          Dauch Corporation) integrates GKN Automotive's ePowertrain and\n          driveline portfolio.\n  - type: UseCases\n    data:\n  \
  \    - name: Supplier Collaboration\n        description: >-\n          Tier 2 and Tier 3 suppliers access forecasts, purchase orders, and\n          payment status through the iSupplier Portal for supply chain\n          coordination.\n      - name: Shipment Management\n        description: >-\n          Suppliers submit Advanced Shipping Notifications via EDI or portal\n          to provide in-transit material visibility to AAM plants.\n      - name: Aftermarket Parts Distribution\n        description: >-\n          Automotive parts distributors and repair shops source genuine OE\n          driveline replacement parts through Demand AAM.\n  - type: Integrations\n    data:\n      - name: EDI Systems\n        description: >-\n          ANSI X12 and EDIFACT EDI transaction sets for forecast (DELFORS),\n          just-in-time releases (DELJIT), and Advanced Shipping Notifications.\n      - name: GKN Automotive\n        description: >-\n          Integration of GKN Automotive's ePowertrain\
  \ and sideshaft technology\n          following Dauch Corporation acquisition of Dowlais Group.\n      - name: GKN Powder Metallurgy\n        description: >-\n          Integration of GKN Powder Metallurgy's sintered components business\n          following the Dowlais Group acquisition.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/american-axle-and-manufacturing/refs/heads/main/apis.yml
tags:
- Automotive
- Manufacturing
- Driveline
- Automotive Supplier
- EDI
- Supply Chain
url: https://raw.githubusercontent.com/api-evangelist/american-axle-and-manufacturing/refs/heads/main/apis.yml
use_cases:
- description: Tier 2 and Tier 3 suppliers access forecasts, purchase orders, and payment status through the iSupplier Portal for supply chain coordination.
  name: Supplier Collaboration
- description: Suppliers submit Advanced Shipping Notifications via EDI or portal to provide in-transit material visibility to AAM plants.
  name: Shipment Management
- description: Automotive parts distributors and repair shops source genuine OE driveline replacement parts through Demand AAM.
  name: Aftermarket Parts Distribution
---
