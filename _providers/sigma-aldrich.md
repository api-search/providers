---
api_count: 3
api_specs:
- filename: sigma-aldrich-product-openapi.yml
  format: yaml
  label: Sigma-Aldrich Product Search API
  slug: sigma-aldrich-product-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sigma-aldrich/refs/heads/main/openapi/sigma-aldrich-product-openapi.yml
apis:
- description: The Sigma-Aldrich Product Search API provides programmatic access to the Sigma-Aldrich product catalog containing hundreds of thousands of chemical compounds, reagents, biochemicals, and laboratory su
  name: Sigma-Aldrich Product Search API
  slug: sigma-aldrich-product-api
- description: The Sigma-Aldrich Chemical Structure Search API enables substructure, exact structure, and similarity searches against the Sigma-Aldrich chemical catalog using SMILES, InChI, or molecular formula nota
  name: Sigma-Aldrich Chemical Structure Search API
  slug: sigma-aldrich-structure-search-api
- description: The Safety Data Sheet (SDS) API provides programmatic access to GHS- compliant Safety Data Sheets for all Sigma-Aldrich chemical products. Enables EHS systems, LIMS platforms, and safety management so
  name: Sigma-Aldrich Safety Data Sheet API
  slug: sigma-aldrich-sds-api
capabilities:
- description: Unified workflow capability for chemical and life science research workflows using the Sigma-Aldrich product catalog API. Enables researchers, LIMS systems, and EHS platforms to search the world's lar
  name: Sigma-Aldrich Chemical Research
  slug: chemical-research
common:
- title: ''
  type: Website
  url: https://www.sigmaaldrich.com/
- title: ''
  type: ProductCatalog
  url: https://www.sigmaaldrich.com/US/en/catalog
- title: ''
  type: SDS Portal
  url: https://www.sigmaaldrich.com/US/en/support/sds-portal
- title: ''
  type: Developer Portal
  url: https://www.sigmaaldrich.com/US/en/technical-documents/technical-article/chemistry/labware/sigma-aldrich-developer-portal
- title: ''
  type: Parent Company
  url: https://www.merckgroup.com/
created: '2025-01-01'
description: Sigma-Aldrich was a leading life science and high technology company whose biochemical and organic chemical products, kits, and services are used in scientific research, including genomics, proteomics, and drug discovery. Acquired by Merck KGaA in 2015, Sigma-Aldrich now operates as part of MilliporeSigma in North America and Merck in other regions, continuing to provide the world's largest catalog of research chemicals, biochemicals, laboratory equipment, and life science products to researchers globally.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 15
  name: Sigma Aldrich Context
  property_count: 8
  slug: sigma-aldrich-context
layout: provider
modified: '2026-05-02'
name: Sigma-Aldrich
rules:
- name: Sigma-Aldrich API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 4
  slug: sigma-aldrich-rules
skills: []
slug: sigma-aldrich
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sigma-aldrich\nurl: https://raw.githubusercontent.com/api-evangelist/sigma-aldrich/refs/heads/main/apis.yml\napis:\n  - aid: sigma-aldrich:sigma-aldrich-product-api\n    name: Sigma-Aldrich Product Search API\n    tags:\n      - Life Science\n      - Chemistry\n      - Products\n      - Search\n    humanURL: https://www.sigmaaldrich.com/US/en/technical-documents/technical-article/chemistry/labware/sigma-aldrich-developer-portal\n    properties:\n      - url: https://www.sigmaaldrich.com/US/en/technical-documents/technical-article/chemistry/labware/sigma-aldrich-developer-portal\n        type: Documentation\n      - url: openapi/sigma-aldrich-product-openapi.yml\n        type: OpenAPI\n      - url: rules/sigma-aldrich-rules.yml\n        type: SpectralRules\n      - url: capabilities/chemical-research.yaml\n        type: Capabilities\n      - url: json-schema/sigma-aldrich-product-schema.json\n        type: JSONSchema\n      - url: json-ld/sigma-aldrich-context.jsonld\n\
  \        type: JSONLD\n      - url: vocabulary/sigma-aldrich-vocabulary.yml\n        type: Vocabulary\n    description: >-\n      The Sigma-Aldrich Product Search API provides programmatic access to\n      the Sigma-Aldrich product catalog containing hundreds of thousands of\n      chemical compounds, reagents, biochemicals, and laboratory supplies.\n      Researchers and laboratory information management systems (LIMS) can\n      query products by CAS number, catalog number, product name, or chemical\n      structure (SMILES notation) to retrieve product details, safety data,\n      pricing, and availability information.\n\n  - aid: sigma-aldrich:sigma-aldrich-structure-search-api\n    name: Sigma-Aldrich Chemical Structure Search API\n    tags:\n      - Chemistry\n      - Cheminformatics\n      - Structure Search\n      - SMILES\n    humanURL: https://www.sigmaaldrich.com/US/en/support/contact-us\n    properties:\n      - url: https://www.sigmaaldrich.com/US/en/support/contact-us\n \
  \       type: Documentation\n    description: >-\n      The Sigma-Aldrich Chemical Structure Search API enables substructure,\n      exact structure, and similarity searches against the Sigma-Aldrich\n      chemical catalog using SMILES, InChI, or molecular formula notation.\n      Supports configuring similarity thresholds and returning ranked results\n      for drug discovery, materials research, and synthetic chemistry workflows.\n\n  - aid: sigma-aldrich:sigma-aldrich-sds-api\n    name: Sigma-Aldrich Safety Data Sheet API\n    tags:\n      - Safety\n      - SDS\n      - GHS\n      - Compliance\n    humanURL: https://www.sigmaaldrich.com/US/en/support/sds-portal\n    properties:\n      - url: https://www.sigmaaldrich.com/US/en/support/sds-portal\n        type: Documentation\n    description: >-\n      The Safety Data Sheet (SDS) API provides programmatic access to GHS-\n      compliant Safety Data Sheets for all Sigma-Aldrich chemical products.\n      Enables EHS systems, LIMS platforms,\
  \ and safety management software\n      to retrieve current SDSs in multiple languages and formats for\n      regulatory compliance and laboratory safety management.\n\nname: Sigma-Aldrich\ntags:\n  - Life Science\n  - Chemistry\n  - Biochemistry\n  - Laboratory\n  - Research\n  - Chemical Catalog\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nposition: Consuming\nsegments:\n  - Life Science\n  - Chemistry\n  - Research Tools\ndescription: >-\n  Sigma-Aldrich was a leading life science and high technology company whose\n  biochemical and organic chemical products, kits, and services are used in\n  scientific research, including genomics, proteomics, and drug discovery.\n  Acquired by Merck KGaA in 2015, Sigma-Aldrich now operates as part of\n  MilliporeSigma in North America and Merck in other regions, continuing to\n  provide the world's largest catalog of research chemicals,\
  \ biochemicals,\n  laboratory equipment, and life science products to researchers globally.\ncommon:\n  - type: Website\n    url: https://www.sigmaaldrich.com/\n  - type: ProductCatalog\n    url: https://www.sigmaaldrich.com/US/en/catalog\n  - type: SDS Portal\n    url: https://www.sigmaaldrich.com/US/en/support/sds-portal\n  - type: Developer Portal\n    url: https://www.sigmaaldrich.com/US/en/technical-documents/technical-article/chemistry/labware/sigma-aldrich-developer-portal\n  - type: Parent Company\n    url: https://www.merckgroup.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sigma-aldrich/refs/heads/main/apis.yml
tags:
- Life Science
- Chemistry
- Biochemistry
- Laboratory
- Research
- Chemical Catalog
url: https://raw.githubusercontent.com/api-evangelist/sigma-aldrich/refs/heads/main/apis.yml
use_cases: []
---
