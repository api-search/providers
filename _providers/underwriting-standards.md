---
api_count: 2
apis:
- description: ACORD (Association for Cooperative Operations Research and Development) provides the insurance industry's primary data standards. The Next-Generation Digital Standards (NGDS) are JSON/YAML-based trans
  name: ACORD Next-Generation Digital Standards API
  slug: acord-api
- description: The LIMRA Data Exchange (LDEx) Standards are free, collaboratively developed standards for exchanging employee workplace benefits data between carriers and benefits administration platforms. LDEx prov
  name: LIMRA LDEx Data Exchange Standards
  slug: ldex
common:
- title: ''
  type: Website
  url: https://www.acord.org/
- title: ''
  type: Website
  url: https://www.limra.com/
- title: ''
  type: Standard
  url: https://www.acord.org/standards-architecture/acord-data-standards
- title: ''
  type: Standard
  url: https://www.limra.com/en/solutions-and-services/data-exchange-standards/
- title: ''
  type: JSON-LD
  url: json-ld/underwriting-standards-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/underwriting-standards-vocabulary.yml
- title: ''
  type: JSONSchema
  url: json-schema/underwriting-standards-submission-schema.json
created: '2025-01-01'
description: A curated collection of data standards, APIs, and specifications used in insurance underwriting. This covers the landscape of industry-wide data interchange formats, protocol standards, and API ecosystems that enable carriers, MGAs, brokers, and InsurTech platforms to exchange underwriting data programmatically. Key standards include ACORD (Property & Casualty, Life, Reinsurance), LIMRA LDEx (employee benefits), and emerging OpenInsurance initiatives.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 11
  name: Underwriting Standards Context
  property_count: 19
  slug: underwriting-standards-context
layout: provider
modified: '2026-05-03'
name: Underwriting Standards
skills: []
slug: underwriting-standards
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: underwriting-standards\nname: Underwriting Standards\ndescription: >-\n  A curated collection of data standards, APIs, and specifications used in\n  insurance underwriting. This covers the landscape of industry-wide data\n  interchange formats, protocol standards, and API ecosystems that enable\n  carriers, MGAs, brokers, and InsurTech platforms to exchange underwriting\n  data programmatically. Key standards include ACORD (Property & Casualty,\n  Life, Reinsurance), LIMRA LDEx (employee benefits), and emerging OpenInsurance\n  initiatives.\nurl: https://raw.githubusercontent.com/api-evangelist/underwriting-standards/refs/heads/main/apis.yml\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Underwriting\n  - Insurance\n  - Standards\n  - ACORD\n  - Data Exchange\n  - InsurTech\ncreated: '2025-01-01'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: underwriting-standards:acord-api\n    name:\
  \ ACORD Next-Generation Digital Standards API\n    tags:\n      - Insurance\n      - ACORD\n      - Standards\n      - Property And Casualty\n      - Life Insurance\n      - Reinsurance\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://www.acord.org\n    humanURL: https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards\n    properties:\n      - url: https://www.acord.org/standards-architecture/acord-data-standards\n        type: Documentation\n      - url: https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards\n        type: Documentation\n      - url: https://www.acord.org/standards-architecture/reference-architecture\n        type: Reference Architecture\n    description: >-\n      ACORD (Association for Cooperative Operations Research and Development)\n      provides the insurance industry's primary data standards. The\n      Next-Generation\
  \ Digital Standards (NGDS) are JSON/YAML-based\n      transaction-centric standards for RESTful APIs and microservices, covering\n      Policy, Claims, Party, Product, and Reinsurance entities. ACORD standards\n      are used by over 3,000 member organizations worldwide.\n  - aid: underwriting-standards:ldex\n    name: LIMRA LDEx Data Exchange Standards\n    tags:\n      - Insurance\n      - LIMRA\n      - Benefits Administration\n      - Standards\n      - Employee Benefits\n      - Life Insurance\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://www.limra.com\n    humanURL: https://www.limra.com/en/solutions-and-services/data-exchange-standards/\n    properties:\n      - url: https://www.limra.com/en/solutions-and-services/data-exchange-standards/ldex-overview/\n        type: Documentation\n      - url: https://www.limra.com/en/solutions-and-services/data-exchange-standards/standards-download/\n        type: Downloads\n    description:\
  \ >-\n      The LIMRA Data Exchange (LDEx) Standards are free, collaboratively developed\n      standards for exchanging employee workplace benefits data between carriers\n      and benefits administration platforms. LDEx provides REST API endpoints\n      compliant with OpenAPI 3.1 and supports JSON, XML, and YAML payloads.\n      Use cases include enrollment, eligibility, coverage changes, terminations,\n      and evidence of insurability.\ncommon:\n  - type: Website\n    url: https://www.acord.org/\n  - type: Website\n    url: https://www.limra.com/\n  - type: Standard\n    url: https://www.acord.org/standards-architecture/acord-data-standards\n  - type: Standard\n    url: https://www.limra.com/en/solutions-and-services/data-exchange-standards/\n  - type: JSON-LD\n    url: json-ld/underwriting-standards-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/underwriting-standards-vocabulary.yml\n  - type: JSONSchema\n    url: json-schema/underwriting-standards-submission-schema.json\n\
  maintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/underwriting-standards/refs/heads/main/apis.yml
tags:
- Underwriting
- Insurance
- Standards
- ACORD
- Data Exchange
- InsurTech
url: https://raw.githubusercontent.com/api-evangelist/underwriting-standards/refs/heads/main/apis.yml
use_cases: []
---
