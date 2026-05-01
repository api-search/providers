---
api_count: 3
api_specs:
- filename: inttra-ocean-execution-openapi.yml
  format: yaml
  label: INTTRA Ocean Execution API
  slug: inttra-ocean-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/openapi/inttra-ocean-execution-openapi.yml
apis:
- description: E2open supply chain platform APIs enable supply chain event management, transportation management, customs compliance, and end-to-end shipment visibility. The platform supports REST/JSON, XML, and EDI
  name: E2open Supply Chain Platform API
  slug: e2open-supply-chain-api
- description: INTTRA (now part of e2open) provides ocean execution APIs for the world's largest multi-carrier e-commerce platform for global shipping. The RESTful API uses HTTPS with JSON for booking, ocean schedul
  name: INTTRA Ocean Execution API
  slug: inttra-ocean-api
- description: E2open Transportation Management API provides appointment scheduling, carrier integration, and real-time rating capabilities. REST endpoints allow carriers to POST documents, retrieve current rates, m
  name: E2open Transportation Management API
  slug: e2open-transportation-management-api
common:
- title: ''
  type: Website
  url: https://www.e2open.com/
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/openapi/inttra-ocean-execution-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/json-schema/e2open-shipment-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/json-ld/e2open-context.jsonld
- title: ''
  type: Portal
  url: https://apidocs.inttra.com/
- title: ''
  type: Documentation
  url: https://www.e2open.com/e2open-network-connectivity/
- title: ''
  type: PrivacyPolicy
  url: https://www.e2open.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://www.inttra.com/legal/
- title: ''
  type: GettingStarted
  url: https://marketplace.e2open.com/
- title: ''
  type: Support
  url: https://knowledge.e2open.com/knowledgecenter/inttra-resources/
created: ''
description: Supply chain software with a connected network and SaaS platform help you seize opportunities, predict disruptions, and drive efficiency and sustainability.
features: []
image: ''
integrations: []
jsonld:
- class_count: 4
  name: E2Open Context
  property_count: 28
  slug: e2open-context
layout: provider
modified: '2026-04-28'
name: e2open
skills: []
slug: e2open
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: e2open\nurl: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/apis.yml\napis:\n  - aid: e2open:e2open-supply-chain-api\n    name: E2open Supply Chain Platform API\n    tags:\n      - JSON\n      - Logistics\n      - REST\n      - Supply Chain\n      - Trade Management\n      - Visibility\n    image: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/image.png\n    humanURL: https://www.e2open.com/\n    baseURL: https://api.e2open.com\n    properties:\n      - url: https://www.e2open.com/\n        type: Documentation\n    description: >-\n      E2open supply chain platform APIs enable supply chain event management, transportation\n      management, customs compliance, and end-to-end shipment visibility. The platform\n      supports REST/JSON, XML, and EDI protocols connecting over 400,000 manufacturing,\n      logistics, channel, and distribution partners, tracking over 12 billion transactions\n      annually.\n  - aid: e2open:inttra-ocean-api\n\
  \    name: INTTRA Ocean Execution API\n    tags:\n      - Booking\n      - JSON\n      - Logistics\n      - Ocean Shipping\n      - REST\n      - Supply Chain\n      - Track and Trace\n    image: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/image.png\n    humanURL: https://apidocs.inttra.com/\n    baseURL: https://api.inttra.com\n    properties:\n      - url: https://apidocs.inttra.com/\n        type: Documentation\n      - url: https://apidocs.inttra.com/\n        type: Reference\n      - url: https://www.inttra.com/services/integration/\n        type: GettingStarted\n      - url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/openapi/inttra-ocean-execution-openapi.yml\n        type: OpenAPI\n    description: >-\n      INTTRA (now part of e2open) provides ocean execution APIs for the world's largest\n      multi-carrier e-commerce platform for global shipping. The RESTful API uses\n      HTTPS with JSON for booking, ocean schedules,\
  \ rates, and visibility/track and\n      trace products. Authentication requires a token obtained from the identity service\n      before making API requests.\n  - aid: e2open:e2open-transportation-management-api\n    name: E2open Transportation Management API\n    tags:\n      - Appointment Scheduling\n      - Carrier Integration\n      - Logistics\n      - Supply Chain\n      - Transportation\n    image: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/image.png\n    humanURL: https://marketplace.e2open.com/\n    baseURL: https://api.e2open.com\n    properties:\n      - url: https://marketplace.e2open.com/product/api-implementation/\n        type: Documentation\n    description: >-\n      E2open Transportation Management API provides appointment scheduling, carrier\n      integration, and real-time rating capabilities. REST endpoints allow carriers\n      to POST documents, retrieve current rates, manage load stop details, and communicate\n      appointment status\
  \ updates with supply chain stakeholders.\ncommon:\n  - url: https://www.e2open.com/\n    type: Website\n  - url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/openapi/inttra-ocean-execution-openapi.yml\n    type: OpenAPI\n  - url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/json-schema/e2open-shipment-schema.json\n    type: JSONSchema\n  - url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/json-ld/e2open-context.jsonld\n    type: JSONLDContext\n  - url: https://apidocs.inttra.com/\n    type: Portal\n  - url: https://www.e2open.com/e2open-network-connectivity/\n    type: Documentation\n  - url: https://www.e2open.com/privacy-policy/\n    type: PrivacyPolicy\n  - url: https://www.inttra.com/legal/\n    type: TermsOfService\n  - url: https://marketplace.e2open.com/\n    type: GettingStarted\n  - url: https://knowledge.e2open.com/knowledgecenter/inttra-resources/\n    type: Support\nmaintainers:\n  - name: Kin\
  \ Lane\n    email: kin@apievangelist.com\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ndescription: >-\n  Supply chain software with a connected network and SaaS platform help you seize\n  opportunities, predict disruptions, and drive efficiency and sustainability.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/apis.yml
use_cases: []
---
