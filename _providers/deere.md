---
api_count: 7
apis:
- description: Provides access to the organizations a John Deere Operations Center user belongs to. Organizations are the top-level container for users, fields, equipment, and partner relationships in Operations Cen
  name: John Deere Operations Center Organizations API
  slug: operations-center-organizations-api
- description: Exposes growers, farms, fields, and field boundaries in Operations Center so that partner applications can sync agronomic field metadata and boundary geometry.
  name: John Deere Operations Center Fields API
  slug: operations-center-fields-api
- description: Provides metadata, telematics, and engine information for connected John Deere machines, including machine locations, engine hours, hours of operation, alerts, and device state reports.
  name: John Deere Operations Center Machines API
  slug: operations-center-machines-api
- description: Returns information about field operations such as planting, application, tillage, and harvest performed by connected John Deere machines, with links to machine, field, and product data.
  name: John Deere Operations Center Field Operations API
  slug: operations-center-field-operations-api
- description: Manages crop, seed, chemical, and fertilizer products used in field operations, allowing applications to read and reconcile product catalogs across an organization.
  name: John Deere Operations Center Products API
  slug: operations-center-products-api
- description: Lets partner applications subscribe to event notifications from Operations Center so that changes to organizations, machines, fields, and field operations can be received without polling.
  name: John Deere Operations Center Webhook API
  slug: operations-center-webhook-api
- description: A suite of APIs supporting precision agriculture workflows including prescription maps, work plans, setup files, and equipment configuration for connected John Deere machinery.
  name: John Deere Precision Tech APIs
  slug: precision-tech-apis
common:
- title: ''
  type: Website
  url: https://www.deere.com
- title: ''
  type: Developer Portal
  url: https://developer.deere.com/
- title: ''
  type: Getting Started
  url: https://developer.deere.com/precision/get-started
- title: ''
  type: Documentation
  url: https://developer.deere.com/
- title: ''
  type: ChangeLog
  url: https://developer.deere.com/whats-new
created: '2024-12-03'
description: John Deere is a manufacturer of agricultural, construction, and forestry machinery, equipment, and technology. Through its Operations Center and Precision Tech developer programs, John Deere exposes APIs that allow authorized partners and customers to access organization, field, machine, field operations, and webhook data tied to connected equipment and farm management workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: John Deere
skills: []
slug: deere
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: deere\nname: John Deere\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/deere/refs/heads/main/apis.yml\ndescription: >-\n  John Deere is a manufacturer of agricultural, construction, and forestry\n  machinery, equipment, and technology. Through its Operations Center and\n  Precision Tech developer programs, John Deere exposes APIs that allow\n  authorized partners and customers to access organization, field, machine,\n  field operations, and webhook data tied to connected equipment and farm\n  management workflows.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\nposition: Consuming\nspecificationVersion: '0.19'\nxType: company\ntags:\n  - Agriculture\n  - Agricultural Technology\n  - AgTech\n  - Construction\n  - Farming\n  - Forestry\n  - Machinery\n  - Operations Center\n  - Precision Agriculture\ncreated: '2024-12-03'\nmodified: '2026-04-28'\napis:\n  - aid: deere:operations-center-organizations-api\n\
  \    name: John Deere Operations Center Organizations API\n    description: >-\n      Provides access to the organizations a John Deere Operations Center user\n      belongs to. Organizations are the top-level container for users, fields,\n      equipment, and partner relationships in Operations Center.\n    humanURL: https://developer.deere.com/dev-docs/organizations\n    tags:\n      - Operations Center\n      - Organizations\n    properties:\n      - type: Documentation\n        url: https://developer.deere.com/dev-docs/organizations\n  - aid: deere:operations-center-fields-api\n    name: John Deere Operations Center Fields API\n    description: >-\n      Exposes growers, farms, fields, and field boundaries in Operations Center\n      so that partner applications can sync agronomic field metadata and\n      boundary geometry.\n    humanURL: https://developer.deere.com/\n    tags:\n      - Operations Center\n      - Fields\n      - Boundaries\n      - Agronomy\n    properties:\n    \
  \  - type: Documentation\n        url: https://developer.deere.com/\n  - aid: deere:operations-center-machines-api\n    name: John Deere Operations Center Machines API\n    description: >-\n      Provides metadata, telematics, and engine information for connected John\n      Deere machines, including machine locations, engine hours, hours of\n      operation, alerts, and device state reports.\n    humanURL: https://developer.deere.com/\n    tags:\n      - Operations Center\n      - Machines\n      - Telematics\n      - Equipment\n    properties:\n      - type: Documentation\n        url: https://developer.deere.com/\n  - aid: deere:operations-center-field-operations-api\n    name: John Deere Operations Center Field Operations API\n    description: >-\n      Returns information about field operations such as planting, application,\n      tillage, and harvest performed by connected John Deere machines, with\n      links to machine, field, and product data.\n    humanURL: https://developer.deere.com/\n\
  \    tags:\n      - Operations Center\n      - Field Operations\n      - Planting\n      - Harvest\n      - Application\n    properties:\n      - type: Documentation\n        url: https://developer.deere.com/\n  - aid: deere:operations-center-products-api\n    name: John Deere Operations Center Products API\n    description: >-\n      Manages crop, seed, chemical, and fertilizer products used in field\n      operations, allowing applications to read and reconcile product\n      catalogs across an organization.\n    humanURL: https://developer.deere.com/dev-docs/products\n    tags:\n      - Operations Center\n      - Products\n      - Inputs\n    properties:\n      - type: Documentation\n        url: https://developer.deere.com/dev-docs/products\n  - aid: deere:operations-center-webhook-api\n    name: John Deere Operations Center Webhook API\n    description: >-\n      Lets partner applications subscribe to event notifications from\n      Operations Center so that changes to organizations,\
  \ machines, fields,\n      and field operations can be received without polling.\n    humanURL: https://developer.deere.com/dev-docs/webhook\n    tags:\n      - Operations Center\n      - Webhooks\n      - Events\n    properties:\n      - type: Documentation\n        url: https://developer.deere.com/dev-docs/webhook\n  - aid: deere:precision-tech-apis\n    name: John Deere Precision Tech APIs\n    description: >-\n      A suite of APIs supporting precision agriculture workflows including\n      prescription maps, work plans, setup files, and equipment configuration\n      for connected John Deere machinery.\n    humanURL: https://developer.deere.com/precision\n    tags:\n      - Precision Agriculture\n      - Prescriptions\n      - Work Plans\n      - Setup Files\n    properties:\n      - type: Documentation\n        url: https://developer.deere.com/precision\ncommon:\n  - type: Website\n    url: https://www.deere.com\n  - type: Developer Portal\n    url: https://developer.deere.com/\n\
  \  - type: Getting Started\n    url: https://developer.deere.com/precision/get-started\n  - type: Documentation\n    url: https://developer.deere.com/\n  - type: ChangeLog\n    url: https://developer.deere.com/whats-new\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/deere/refs/heads/main/apis.yml
tags:
- Agriculture
- Agricultural Technology
- AgTech
- Construction
- Farming
- Forestry
- Machinery
- Operations Center
- Precision Agriculture
url: https://raw.githubusercontent.com/api-evangelist/deere/refs/heads/main/apis.yml
use_cases: []
---
