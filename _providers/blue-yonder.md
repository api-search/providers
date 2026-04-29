---
api_count: 4
apis:
- description: The Blue Yonder Demand Planning API enables access to demand forecasting models, statistical baselines, and demand signals for retail and manufacturing supply chains. REST APIs support integration wit
  name: Blue Yonder Demand Planning API
  slug: blue-yonder-demand-planning-api
- description: The Blue Yonder Warehouse Management API provides access to warehouse operations data including inventory positions, task management, labor optimization, and fulfillment workflows. REST APIs support i
  name: Blue Yonder Warehouse Management API
  slug: blue-yonder-warehouse-management-api
- description: 'The Blue Yonder Transportation Management API enables access to transportation planning, carrier management, load optimization, and freight audit capabilities. REST APIs support carrier connectivity, '
  name: Blue Yonder Transportation Management API
  slug: blue-yonder-transportation-management-api
- description: Blue Yonder Connect - API & Expansion Pack provides an advanced integration suite with pre-built MuleSoft connectors, enhanced API management tools, and higher throughput capacity. Supports REST, SOAP
  name: Blue Yonder Connect API & Expansion Pack
  slug: blue-yonder-connect-api
common:
- title: ''
  type: Website
  url: https://blueyonder.com
- title: ''
  type: Portal
  url: https://blueyonder.com/solutions/blue-yonder-platform
- title: ''
  type: Documentation
  url: https://blueyonder.com/solutions/blue-yonder-platform
- title: ''
  type: GettingStarted
  url: https://info.blueyonder.com/blue-yonder-platform/what-is-blue-yonder-connect-api-expansion-pack
- title: ''
  type: Blog
  url: https://blog.blueyonder.com/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/openapi/blue-yonder-warehouse-management-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/json-schema/blue-yonder-inventory-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/json-ld/blue-yonder-context.jsonld
created: ''
description: Transforming supply chains through an end-to-end platform for planning, execution, commerce and returns.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Blue Yonder Context
  property_count: 4
  slug: blue-yonder-context
layout: provider
modified: '2026-04-21'
name: blue-yonder
skills: []
slug: blue-yonder
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: blue-yonder\nurl: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/apis.yml\napis:\n  - aid: blue-yonder:blue-yonder-demand-planning-api\n    name: Blue Yonder Demand Planning API\n    tags:\n      - Demand Planning\n      - Forecasting\n      - REST\n      - Retail\n      - Supply Chain\n    image: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/image.png\n    humanURL: https://blueyonder.com/\n    baseURL: https://api.blueyonder.example.com\n    properties:\n      - url: https://blueyonder.com/solutions/blue-yonder-platform\n        type: Documentation\n    description: >-\n      The Blue Yonder Demand Planning API enables access to demand forecasting models,\n      statistical baselines, and demand signals for retail and manufacturing supply\n      chains. REST APIs support integration with ERP and POS systems for demand sensing,\n      shaping, and response workflows.\n\n  - aid: blue-yonder:blue-yonder-warehouse-management-api\n\
  \    name: Blue Yonder Warehouse Management API\n    tags:\n      - Logistics\n      - REST\n      - Supply Chain\n      - Warehouse Management\n      - WMS\n    image: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/image.png\n    humanURL: https://blueyonder.com/\n    baseURL: https://api.blueyonder.example.com\n    properties:\n      - url: https://blueyonder.com/solutions/blue-yonder-platform\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/openapi/blue-yonder-warehouse-management-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Blue Yonder Warehouse Management API provides access to warehouse operations\n      data including inventory positions, task management, labor optimization, and\n      fulfillment workflows. REST APIs support integration with automation systems,\n      robotics, and ERP platforms for distribution center operations.\n\n  - aid: blue-yonder:blue-yonder-transportation-management-api\n\
  \    name: Blue Yonder Transportation Management API\n    tags:\n      - Logistics\n      - REST\n      - Supply Chain\n      - TMS\n      - Transportation Management\n    image: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/image.png\n    humanURL: https://blueyonder.com/\n    baseURL: https://api.blueyonder.example.com\n    properties:\n      - url: https://blueyonder.com/solutions/blue-yonder-platform\n        type: Documentation\n    description: >-\n      The Blue Yonder Transportation Management API enables access to transportation\n      planning, carrier management, load optimization, and freight audit capabilities.\n      REST APIs support carrier connectivity, shipment tracking, and transportation\n      cost optimization across multimodal freight networks.\n\n  - aid: blue-yonder:blue-yonder-connect-api\n    name: Blue Yonder Connect API & Expansion Pack\n    tags:\n      - API Management\n      - EDI\n      - Integration\n      - MuleSoft\n  \
  \    - REST\n      - Supply Chain\n    image: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/image.png\n    humanURL: https://info.blueyonder.com/blue-yonder-platform/what-is-blue-yonder-connect-api-expansion-pack\n    baseURL: https://api.blueyonder.example.com\n    properties:\n      - url: https://info.blueyonder.com/blue-yonder-platform/what-is-blue-yonder-connect-api-expansion-pack\n        type: Documentation\n    description: >-\n      Blue Yonder Connect - API & Expansion Pack provides an advanced integration\n      suite with pre-built MuleSoft connectors, enhanced API management tools, and\n      higher throughput capacity. Supports REST, SOAP, EDI, and OData protocols for\n      connecting Blue Yonder supply chain platform with SAP, Oracle, Salesforce, and\n      custom applications.\n\ncommon:\n  - url: https://blueyonder.com\n    type: Website\n  - url: https://blueyonder.com/solutions/blue-yonder-platform\n    type: Portal\n  - url: https://blueyonder.com/solutions/blue-yonder-platform\n\
  \    type: Documentation\n  - url: https://info.blueyonder.com/blue-yonder-platform/what-is-blue-yonder-connect-api-expansion-pack\n    type: GettingStarted\n  - url: https://blog.blueyonder.com/\n    type: Blog\n  - url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/openapi/blue-yonder-warehouse-management-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/json-schema/blue-yonder-inventory-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/json-ld/blue-yonder-context.jsonld\n    type: JSONLDContext\n\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n\nmodified: '2026-04-21'\ndescription: >-\n  Transforming supply chains through an end-to-end platform for planning, execution,\n  commerce and returns.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/blue-yonder/refs/heads/main/apis.yml
use_cases: []
---
