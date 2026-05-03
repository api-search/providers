---
api_count: 2
api_specs:
- filename: rsc-chemspider-compounds-openapi.yml
  format: yaml
  label: ChemSpider Compounds API
  slug: chemspider-compounds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/openapi/rsc-chemspider-compounds-openapi.yml
- filename: rsc-chemspider-compounds-openapi.yml
  format: yaml
  label: ChemSpider Tools API
  slug: chemspider-tools
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/openapi/rsc-chemspider-compounds-openapi.yml
apis:
- description: The ChemSpider Compounds API (v1) provides comprehensive access to the RSC ChemSpider chemical database, supporting compound filtering by name, SMILES, InChI, InChIKey, formula, molecular weight, mass
  name: ChemSpider Compounds API
  slug: chemspider-compounds
- description: The ChemSpider Tools API provides chemical format conversion utilities, supporting conversions between SMILES, InChI, InChIKey, and Mol file formats. It also includes InChIKey validation. The tools ar
  name: ChemSpider Tools API
  slug: chemspider-tools
capabilities:
- description: Workflow capability for chemical research and cheminformatics tasks using the RSC ChemSpider database. Supports compound discovery, structure lookup, property analysis, and cross-database reference re
  name: RSC Chemical Research
  slug: chemical-research
common:
- title: ''
  type: Portal
  url: https://developer.rsc.org/
- title: ''
  type: Authentication
  url: https://developer.rsc.org/
- title: ''
  type: SignUp
  url: https://developer.rsc.org/
- title: ''
  type: TermsOfService
  url: https://www.rsc.org/legal/
- title: ''
  type: PrivacyPolicy
  url: https://www.rsc.org/help-legal/legal/privacy/
created: '2025-03-01'
description: The Royal Society of Chemistry (RSC) provides developer APIs through its ChemSpider platform, enabling programmatic access to one of the world's largest chemistry databases with over 88 million unique chemical compounds. The APIs support compound search, structure retrieval, format conversion, and data enrichment for cheminformatics applications.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 5
  name: Rsc Context
  property_count: 15
  slug: rsc-context
layout: provider
modified: '2026-05-02'
name: RSC
rules:
- name: RSC API Rules
  rule_count: 8
  severity_counts:
    error: 1
    hint: 0
    info: 1
    warn: 6
  slug: rsc-spectral-rules
skills: []
slug: rsc
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rsc\nname: RSC\ndescription: >-\n  The Royal Society of Chemistry (RSC) provides developer APIs through its\n  ChemSpider platform, enabling programmatic access to one of the world's\n  largest chemistry databases with over 88 million unique chemical compounds.\n  The APIs support compound search, structure retrieval, format conversion,\n  and data enrichment for cheminformatics applications.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Chemistry\n  - Cheminformatics\n  - Chemical Data\n  - Science\ncreated: '2025-03-01'\nmodified: '2026-05-02'\nurl: https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: rsc:chemspider-compounds\n    name: ChemSpider Compounds API\n    description: >-\n      The ChemSpider Compounds API (v1) provides comprehensive access to the\n      RSC ChemSpider chemical database,\
  \ supporting compound filtering by name,\n      SMILES, InChI, InChIKey, formula, molecular weight, mass, and elemental\n      composition. Authenticated endpoints allow retrieval of compound records,\n      external references, molecular images, and MOL files. The API also\n      supports batch operations and chemical format conversions between SMILES,\n      InChI, InChIKey, and Mol formats.\n    humanURL: https://developer.rsc.org/\n    baseURL: https://api.rsc.org/compounds/v1\n    tags:\n      - Chemistry\n      - Cheminformatics\n      - Compounds\n      - Chemical Search\n    properties:\n      - type: Documentation\n        url: https://developer.rsc.org/compounds-v1/apis\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/openapi/rsc-chemspider-compounds-openapi.yml\n    contact:\n      - FN: RSC Developer Support\n        url: https://developer.rsc.org/\n  - aid: rsc:chemspider-tools\n    name: ChemSpider Tools API\n    description:\
  \ >-\n      The ChemSpider Tools API provides chemical format conversion utilities,\n      supporting conversions between SMILES, InChI, InChIKey, and Mol file\n      formats. It also includes InChIKey validation. The tools are useful for\n      cheminformatics pipelines that need to normalize chemical identifiers\n      across different format conventions.\n    humanURL: https://developer.rsc.org/\n    baseURL: https://api.rsc.org/compounds/v1\n    tags:\n      - Chemistry\n      - Format Conversion\n      - Cheminformatics\n      - Tools\n    properties:\n      - type: Documentation\n        url: https://developer.rsc.org/compounds-v1/apis\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/openapi/rsc-chemspider-compounds-openapi.yml\ncommon:\n  - type: Portal\n    url: https://developer.rsc.org/\n  - type: Authentication\n    url: https://developer.rsc.org/\n  - type: SignUp\n    url: https://developer.rsc.org/\n  - type: TermsOfService\n\
  \    url: https://www.rsc.org/legal/\n  - type: PrivacyPolicy\n    url: https://www.rsc.org/help-legal/legal/privacy/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/apis.yml
tags:
- Chemistry
- Cheminformatics
- Chemical Data
- Science
url: https://raw.githubusercontent.com/api-evangelist/rsc/refs/heads/main/apis.yml
use_cases: []
---
