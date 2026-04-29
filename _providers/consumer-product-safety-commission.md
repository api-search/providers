---
api_count: 2
api_specs:
- filename: cpsc-recalls-openapi.yml
  format: yaml
  label: CPSC Recalls API
  slug: recalls
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/consumer-product-safety-commission/refs/heads/main/openapi/cpsc-recalls-openapi.yml
apis:
- description: Public REST web service that returns CPSC recall records published on cpsc.gov. Supports case-insensitive wildcard search across recall number, date, product type, hazard, country, manufacturer, retai
  name: CPSC Recalls API
  slug: recalls
- description: 'OData web service exposing publicly published consumer product incident-report data submitted through SaferProducts.gov. Authenticated with a basic-auth header where the registered application key is '
  name: SaferProducts.gov OData API
  slug: saferproducts
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.cpsc.gov/
- title: ''
  type: Recalls
  url: https://www.cpsc.gov/Recalls
- title: ''
  type: Data
  url: https://www.cpsc.gov/Data
- title: ''
  type: SaferProducts.gov
  url: https://www.saferproducts.gov/
- title: ''
  type: Public Search
  url: https://www.saferproducts.gov/PublicSearch
- title: ''
  type: Programmers Guide
  url: https://cpsc.gov/s3fs-public/RecallRetrievalWebServicesProgrammersGuide20180917.pdf
- title: ''
  type: Privacy Policy
  url: https://www.cpsc.gov/Newsroom/Privacy-and-Security-Statement
- title: ''
  type: Terms of Service
  url: https://www.cpsc.gov/Newsroom/Privacy-and-Security-Statement
- title: ''
  type: JSON-LD
  url: json-ld/consumer-product-safety-commission-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/cpsc-recall-schema.json
- title: ''
  type: Spectral
  url: rules/consumer-product-safety-commission-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/consumer-product-safety-commission-capabilities.yml
created: '2024-12-25'
description: The U.S. Consumer Product Safety Commission (CPSC) is the federal agency responsible for protecting the public from unreasonable risks of injury or death associated with consumer products such as toys, household items, electronics, and furniture. CPSC publishes a public, unauthenticated Recalls Retrieval Web Service that exposes recall records (with products, hazards, manufacturers, retailers, distributors, importers, and remedies) in JSON or XML, plus the SaferProducts.gov OData service for incident-report data accessed by application key.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/apis-json.png
integrations: []
jsonld:
- class_count: 0
  name: Consumer Product Safety Commission Context
  property_count: 3
  slug: consumer-product-safety-commission-context
layout: provider
modified: '2026-04-29'
name: Consumer Product Safety Commission
rules:
- name: Consumer Product Safety Commission API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 2
  slug: consumer-product-safety-commission-rules
skills: []
slug: consumer-product-safety-commission
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: consumer-product-safety-commission\nname: Consumer Product Safety Commission\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/consumer-product-safety-commission/refs/heads/main/apis.yml\ntags:\n  - Consumer Protection\n  - Federal Government\n  - Hazards\n  - Open Data\n  - Product Safety\n  - Recalls\ntype: Index\nimage: >-\n  https://kinlane-productions2.s3.amazonaws.com/apis-json-icons/apis-json.png\naccess: 3rd-Party\ncreated: '2024-12-25'\nmodified: '2026-04-29'\nposition: Consumer\nspecificationVersion: '0.19'\nx-type: government\ndescription: >-\n  The U.S. Consumer Product Safety Commission (CPSC) is the federal agency\n  responsible for protecting the public from unreasonable risks of injury\n  or death associated with consumer products such as toys, household items,\n  electronics, and furniture. CPSC publishes a public, unauthenticated\n  Recalls Retrieval Web Service that exposes recall records (with\n  products, hazards, manufacturers, retailers,\
  \ distributors, importers,\n  and remedies) in JSON or XML, plus the SaferProducts.gov OData service\n  for incident-report data accessed by application key.\napis:\n  - aid: consumer-product-safety-commission:recalls\n    name: CPSC Recalls API\n    tags:\n      - JSON\n      - Open Data\n      - Recalls\n      - REST\n      - XML\n    humanURL: >-\n      https://www.cpsc.gov/Recalls/CPSC-Recalls-Application-Program-Interface-API-Information\n    baseURL: https://www.saferproducts.gov/RestWebServices\n    properties:\n      - url: >-\n          https://www.cpsc.gov/Recalls/CPSC-Recalls-Application-Program-Interface-API-Information\n        type: Documentation\n      - url: >-\n          https://cpsc.gov/s3fs-public/RecallRetrievalWebServicesProgrammersGuide20180917.pdf\n        type: Reference\n      - url: openapi/cpsc-recalls-openapi.yml\n        type: OpenAPI\n    description: >-\n      Public REST web service that returns CPSC recall records published\n      on cpsc.gov. Supports\
  \ case-insensitive wildcard search across\n      recall number, date, product type, hazard, country, manufacturer,\n      retailer, importer, distributor, and UPC. Output is available as\n      JSON or XML and the API requires no authentication.\n  - aid: consumer-product-safety-commission:saferproducts\n    name: SaferProducts.gov OData API\n    tags:\n      - Incident Reports\n      - OData\n      - Open Data\n    humanURL: https://www.saferproducts.gov/FAQs/FrequentlyAskedQuestions11\n    baseURL: https://www.saferproducts.gov/WebApi/Cpsc.Cpsrms.Web.Api.svc\n    properties:\n      - url: https://www.saferproducts.gov/FAQs/FrequentlyAskedQuestions11\n        type: Documentation\n      - url: https://www.saferproducts.gov/WebApi/Cpsc.Cpsrms.Web.Api.svc/$metadata\n        type: Reference\n    description: >-\n      OData web service exposing publicly published consumer product\n      incident-report data submitted through SaferProducts.gov.\n      Authenticated with a basic-auth header\
  \ where the registered\n      application key is sent as the username (no password).\ncommon:\n  - type: Website\n    url: https://www.cpsc.gov/\n  - type: Recalls\n    url: https://www.cpsc.gov/Recalls\n  - type: Data\n    url: https://www.cpsc.gov/Data\n  - type: SaferProducts.gov\n    url: https://www.saferproducts.gov/\n  - type: Public Search\n    url: https://www.saferproducts.gov/PublicSearch\n  - type: Programmers Guide\n    url: >-\n      https://cpsc.gov/s3fs-public/RecallRetrievalWebServicesProgrammersGuide20180917.pdf\n  - type: Privacy Policy\n    url: https://www.cpsc.gov/Newsroom/Privacy-and-Security-Statement\n  - type: Terms of Service\n    url: https://www.cpsc.gov/Newsroom/Privacy-and-Security-Statement\n  - type: JSON-LD\n    url: json-ld/consumer-product-safety-commission-context.jsonld\n  - type: JSONSchema\n    url: json-schema/cpsc-recall-schema.json\n  - type: Spectral\n    url: rules/consumer-product-safety-commission-rules.yml\n  - type: Naftiko Capabilities\n\
  \    url: capabilities/consumer-product-safety-commission-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/consumer-product-safety-commission/refs/heads/main/apis.yml
tags:
- Consumer Protection
- Federal Government
- Hazards
- Open Data
- Product Safety
- Recalls
url: https://raw.githubusercontent.com/api-evangelist/consumer-product-safety-commission/refs/heads/main/apis.yml
use_cases: []
---
