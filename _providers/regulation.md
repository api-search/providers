---
api_count: 3
api_specs:
- filename: api-docs
  format: yaml
  label: Regulations.gov API
  slug: regulations-gov
  spec_type: OpenAPI
  url: https://api.regulations.gov/v4/api-docs
apis:
- description: The Regulations.gov API provides access to federal regulatory dockets, documents, and public comments. Enables programmatic access to the full regulatory comment process and rulemaking lifecycle acros
  name: Regulations.gov API
  slug: regulations-gov
- description: The Federal Register API provides programmatic access to documents published in the Federal Register since 1994, including proposed rules, final rules, notices, and presidential documents. Supports ad
  name: Federal Register API
  slug: federal-register
- description: Compliance.ai provides an API for regulatory change management that automatically aggregates data from federal and state agencies, enforcement actions, regulatory publications, white papers, and milli
  name: Compliance.ai Regulatory Change Management API
  slug: compliance-ai
common:
- title: ''
  type: Website
  url: https://open.gsa.gov/api/regulationsgov/
- title: ''
  type: Website
  url: https://www.federalregister.gov/developers/documentation/api/v1
- title: ''
  type: Website
  url: https://catalog.data.gov/dataset/regulations-gov-api
- title: ''
  type: Website
  url: https://www.compliance.ai/api/
- title: ''
  type: Website
  url: https://developer.finra.org/
- title: ''
  type: Documentation
  url: https://en.wikipedia.org/wiki/Regulation
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/json-schema/regulation-document-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/json-schema/regulation-comment-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/json-structure/regulation-document-structure.json
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/json-ld/regulation-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/vocabulary/regulation-vocabulary.yml
- title: ''
  type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/examples/regulation-document-federal-register-example.json
created: '2025-01-01'
description: Regulation encompasses the rules, laws, and standards established by governments, agencies, and standards bodies that govern how businesses and individuals must operate. In the context of APIs and digital technology, regulation drives compliance requirements for data privacy (GDPR, CCPA), financial services (PSD2, Dodd-Frank), healthcare (HIPAA), and many other sectors. A rich ecosystem of APIs exists to access regulatory data, track regulatory changes, and automate compliance workflows.
features: []
image: ''
integrations: []
jsonld:
- class_count: 6
  name: Regulation Context
  property_count: 7
  slug: regulation-context
layout: provider
modified: '2026-05-02'
name: Regulation
skills: []
slug: regulation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: regulation\nname: Regulation\ndescription: Regulation encompasses the rules, laws, and standards established by governments, agencies, and standards bodies that govern how businesses and individuals must operate. In the context of APIs and digital technology, regulation drives compliance requirements for data privacy (GDPR, CCPA), financial services (PSD2, Dodd-Frank), healthcare (HIPAA), and many other sectors. A rich ecosystem of APIs exists to access regulatory data, track regulatory changes, and automate compliance workflows.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/apis.yml\ntags:\n  - Compliance\n  - Governance\n  - Government\n  - Legal\n  - Policy\n  - Regulation\n  - Regulatory Change\n  - Risk Management\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: regulation:regulations-gov\n    name: Regulations.gov API\n    description: The Regulations.gov API provides access\
  \ to federal regulatory dockets, documents, and public comments. Enables programmatic access to the full regulatory comment process and rulemaking lifecycle across US federal agencies.\n    humanURL: https://open.gsa.gov/api/regulationsgov/\n    baseURL: https://api.regulations.gov/v4\n    tags:\n      - Federal Regulations\n      - Government\n      - Public Comments\n      - Rulemaking\n    properties:\n      - type: Documentation\n        url: https://open.gsa.gov/api/regulationsgov/\n      - type: OpenAPI\n        url: https://api.regulations.gov/v4/api-docs\n  - aid: regulation:federal-register\n    name: Federal Register API\n    description: The Federal Register API provides programmatic access to documents published in the Federal Register since 1994, including proposed rules, final rules, notices, and presidential documents. Supports advanced search and full-text retrieval.\n    humanURL: https://www.federalregister.gov/developers/documentation/api/v1\n    baseURL: https://www.federalregister.gov/api/v1\n\
  \    tags:\n      - Federal Register\n      - Government\n      - Regulatory Documents\n      - Rules\n    properties:\n      - type: Documentation\n        url: https://www.federalregister.gov/developers/documentation/api/v1\n      - type: Documentation\n        url: https://www.federalregister.gov/reader-aids/developer-resources/rest-api\n  - aid: regulation:compliance-ai\n    name: Compliance.ai Regulatory Change Management API\n    description: Compliance.ai provides an API for regulatory change management that automatically aggregates data from federal and state agencies, enforcement actions, regulatory publications, white papers, and millions of new and existing rules. Enables financial institutions and businesses to stay current with regulatory developments.\n    humanURL: https://www.compliance.ai/api/\n    baseURL: https://api.compliance.ai\n    tags:\n      - Compliance\n      - Financial Services\n      - Regulatory Change\n      - RegTech\n    properties:\n      - type: Documentation\n\
  \        url: https://www.compliance.ai/api/\ncommon:\n  - type: Website\n    url: https://open.gsa.gov/api/regulationsgov/\n    name: Regulations.gov API - GSA Open Technology\n  - type: Website\n    url: https://www.federalregister.gov/developers/documentation/api/v1\n    name: Federal Register API Documentation\n  - type: Website\n    url: https://catalog.data.gov/dataset/regulations-gov-api\n    name: Regulations.gov API - Data.gov Catalog\n  - type: Website\n    url: https://www.compliance.ai/api/\n    name: Compliance.ai Developer Program\n  - type: Website\n    url: https://developer.finra.org/\n    name: FINRA Developer Center\n  - type: Documentation\n    url: https://en.wikipedia.org/wiki/Regulation\n    name: Regulation - Wikipedia\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/json-schema/regulation-document-schema.json\n    name: Regulatory Document JSON Schema\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/json-schema/regulation-comment-schema.json\n\
  \    name: Public Comment JSON Schema\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/json-structure/regulation-document-structure.json\n    name: Regulatory Document JSON Structure\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/json-ld/regulation-context.jsonld\n    name: Regulation JSON-LD Context\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/vocabulary/regulation-vocabulary.yml\n    name: Regulation Vocabulary\n  - type: Examples\n    url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/examples/regulation-document-federal-register-example.json\n    name: Federal Register Document Example\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/apis.yml
tags:
- Compliance
- Governance
- Government
- Legal
- Policy
- Regulation
- Regulatory Change
- Risk Management
url: https://raw.githubusercontent.com/api-evangelist/regulation/refs/heads/main/apis.yml
use_cases: []
---
