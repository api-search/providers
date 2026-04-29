---
api_count: 3
api_specs:
- filename: allianz-api-connect.yaml
  format: yaml
  label: Allianz API Connect
  slug: allianz-api-connect
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/allianz-docs/refs/heads/main/openapi/allianz-api-connect.yaml
apis:
- description: Allianz API Connect provides APIs for Australian insurance products including home and contents, landlord, and comprehensive car insurance. APIs support price estimation, quoting, lead referral, and c
  name: Allianz API Connect
  slug: allianz-api-connect
- description: The Allianz Partners API Management portal provides insurance and assistance product APIs covering the full customer journey. APIs support policy purchase, change, and cancellation operations in XML a
  name: Allianz Partners API
  slug: allianz-partners-api
- description: The Allianz Global API Portal provides enterprise insurance APIs for registered business partners. The portal uses Apigee Edge for API key management and OAuth2 for authentication. Most API documentat
  name: Allianz Global API
  slug: allianz-global-api
capabilities:
- description: Workflow capability for financial institutions and retail partners embedding Allianz Australian insurance products into their customer journeys. Combines quoting, lead referral, policy completion, and
  name: Allianz Insurance Partner Integration
  slug: insurance-partner-integration
common:
- title: ''
  type: Website
  url: https://www.allianz.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/allianz
- title: ''
  type: Support
  url: https://global.apis.allianz.com/contact
- title: ''
  type: SpectralRules
  url: rules/allianz-docs-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/allianz-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/insurance-partner-integration.yaml
created: '2024-01-15'
description: Allianz is one of the world's largest insurance and financial services companies, serving over 86 million customers worldwide. Allianz offers developer APIs across multiple product lines including insurance quoting, policy management, claims, and trade credit services, enabling partners and distributors to integrate Allianz insurance products directly into their platforms.
features:
- description: APIs for generating price estimates and quotes for home, auto, and other insurance products enabling partner-embedded quoting flows.
  name: Insurance Quoting
- description: Purchase, change, and cancel insurance policies programmatically through REST and SOAP-compatible API interfaces.
  name: Policy Management
- description: Retrieve and manage insurance claims data, enabling ERP and enterprise system integration for claims tracking.
  name: Claims Integration
- description: Enable distributors, brokers, and financial institutions to embed Allianz insurance products into their customer journeys.
  name: Partner Distribution
- description: Secure API authentication using OAuth2 client credentials flow for programmatic access to partner APIs.
  name: OAuth2 Authentication
- description: APIs support both XML and JSON formats with content negotiation for flexible enterprise integration.
  name: Multi-Format Support
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Allianz Trade APIs support Postman collection import for API exploration and testing.
  name: Postman
- description: Allianz Global API platform uses Apigee Edge for API key and credential management.
  name: Apigee Edge
- description: Allianz Partners portal is built on Azure API Management platform.
  name: Azure API Management
jsonld:
- class_count: 21
  name: Allianz Api Connect Context
  property_count: 48
  slug: allianz-api-connect-context
layout: provider
modified: '2026-04-19'
name: Allianz
skills: []
slug: allianz-docs
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: allianz-docs\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/allianz-docs/refs/heads/main/apis.yml\nname: Allianz\ntags:\n  - Financial Services\n  - Insurance\n  - Asset Management\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ndescription: >-\n  Allianz is one of the world's largest insurance and financial services\n  companies, serving over 86 million customers worldwide. Allianz offers\n  developer APIs across multiple product lines including insurance quoting,\n  policy management, claims, and trade credit services, enabling partners and\n  distributors to integrate Allianz insurance products directly into their\n  platforms.\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: allianz-docs:allianz-api-connect\n    name: Allianz API Connect\n    tags:\n      - Insurance\n      - Quoting\n      - Policy\n      - Australia\n    properties:\n      - url: https://www.allianz.com.au/about-us/work-with-us/partners/api-connect.html\n\
  \        type: Documentation\n      - url: https://www.allianz.com.au/about-us/work-with-us/partners/api-connect/our-apis.html\n        type: APIReference\n      - url: openapi/allianz-api-connect.yaml\n        type: OpenAPI\n      - url: json-schema/api-connect-price-estimate-response-schema.json\n        type: JSONSchema\n      - url: json-schema/api-connect-policy-details-response-schema.json\n        type: JSONSchema\n      - url: json-schema/api-connect-certificate-of-currency-schema.json\n        type: JSONSchema\n      - url: json-structure/api-connect-price-estimate-response-structure.json\n        type: JSONStructure\n      - url: json-structure/api-connect-policy-details-response-structure.json\n        type: JSONStructure\n      - url: json-structure/api-connect-certificate-of-currency-structure.json\n        type: JSONStructure\n      - url: json-ld/allianz-api-connect-context.jsonld\n        type: JSONLD\n      - url: examples/api-connect-price-estimate-response-example.json\n\
  \        type: Example\n      - url: examples/api-connect-certificate-of-currency-example.json\n        type: Example\n    description: >-\n      Allianz API Connect provides APIs for Australian insurance products\n      including home and contents, landlord, and comprehensive car insurance.\n      APIs support price estimation, quoting, lead referral, and certificate\n      of currency retrieval for partner integrations.\n    humanURL: https://www.allianz.com.au/about-us/work-with-us/partners/api-connect.html\n    baseURL: https://api.allianz.com.au\n\n  - aid: allianz-docs:allianz-partners-api\n    name: Allianz Partners API\n    tags:\n      - Insurance\n      - Assistance\n      - Policy Management\n    properties:\n      - url: https://developer.allianz-assistance.ca/\n        type: Portal\n      - url: https://developer.allianz-assistance.ca/get-started\n        type: GettingStarted\n    description: >-\n      The Allianz Partners API Management portal provides insurance and\n  \
  \    assistance product APIs covering the full customer journey. APIs support\n      policy purchase, change, and cancellation operations in XML and JSON\n      formats. Access requires contractual partnership agreement with Allianz.\n    humanURL: https://developer.allianz-assistance.ca/\n    baseURL: https://api.allianz-assistance.ca\n\n  - aid: allianz-docs:allianz-global-api\n    name: Allianz Global API\n    tags:\n      - Insurance\n      - Global\n      - Enterprise\n    properties:\n      - url: https://global.apis.allianz.com/api-catalog\n        type: Portal\n      - url: https://global.apis.allianz.com/contact\n        type: Contact\n    description: >-\n      The Allianz Global API Portal provides enterprise insurance APIs for\n      registered business partners. The portal uses Apigee Edge for API key\n      management and OAuth2 for authentication. Most API documentation is\n      restricted to contractual partners.\n    humanURL: https://global.apis.allianz.com/api-catalog\n\
  \    baseURL: https://apis.allianz.com\n\ncommon:\n  - url: https://www.allianz.com/\n    type: Website\n  - url: https://github.com/allianz\n    type: GitHubOrganization\n  - url: https://global.apis.allianz.com/contact\n    type: Support\n  - url: rules/allianz-docs-spectral-rules.yml\n    type: SpectralRules\n  - url: vocabulary/allianz-vocabulary.yaml\n    type: Vocabulary\n  - url: capabilities/insurance-partner-integration.yaml\n    type: NaftikoCapability\n  - type: Features\n    data:\n      - name: Insurance Quoting\n        description: >-\n          APIs for generating price estimates and quotes for home, auto, and\n          other insurance products enabling partner-embedded quoting flows.\n      - name: Policy Management\n        description: >-\n          Purchase, change, and cancel insurance policies programmatically\n          through REST and SOAP-compatible API interfaces.\n      - name: Claims Integration\n        description: >-\n          Retrieve and manage insurance\
  \ claims data, enabling ERP and\n          enterprise system integration for claims tracking.\n      - name: Partner Distribution\n        description: >-\n          Enable distributors, brokers, and financial institutions to embed\n          Allianz insurance products into their customer journeys.\n      - name: OAuth2 Authentication\n        description: >-\n          Secure API authentication using OAuth2 client credentials flow\n          for programmatic access to partner APIs.\n      - name: Multi-Format Support\n        description: >-\n          APIs support both XML and JSON formats with content negotiation\n          for flexible enterprise integration.\n  - type: UseCases\n    data:\n      - name: Embedded Insurance\n        description: >-\n          Financial institutions and retailers embedding Allianz insurance\n          offers at the point of sale within their own customer journey.\n      - name: ERP Integration\n        description: >-\n          Enterprise companies\
  \ integrating Allianz trade credit and policy\n          management directly into their ERP systems for automation.\n      - name: Broker Portals\n        description: >-\n          Insurance brokers building digital platforms that access Allianz\n          products to offer customers real-time quotes and policy management.\n      - name: Claims Automation\n        description: >-\n          Automating claims reporting, status tracking, and management\n          through API integration with enterprise workflow systems.\n  - type: Integrations\n    data:\n      - name: Postman\n        description: >-\n          Allianz Trade APIs support Postman collection import for API\n          exploration and testing.\n      - name: Apigee Edge\n        description: >-\n          Allianz Global API platform uses Apigee Edge for API key and\n          credential management.\n      - name: Azure API Management\n        description: >-\n          Allianz Partners portal is built on Azure API Management\
  \ platform.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/allianz-docs/refs/heads/main/apis.yml
tags:
- Financial Services
- Insurance
- Asset Management
url: https://raw.githubusercontent.com/api-evangelist/allianz-docs/refs/heads/main/apis.yml
use_cases:
- description: Financial institutions and retailers embedding Allianz insurance offers at the point of sale within their own customer journey.
  name: Embedded Insurance
- description: Enterprise companies integrating Allianz trade credit and policy management directly into their ERP systems for automation.
  name: ERP Integration
- description: Insurance brokers building digital platforms that access Allianz products to offer customers real-time quotes and policy management.
  name: Broker Portals
- description: Automating claims reporting, status tracking, and management through API integration with enterprise workflow systems.
  name: Claims Automation
---
