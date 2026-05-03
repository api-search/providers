---
api_count: 4
apis:
- description: FINRA (Financial Industry Regulatory Authority) provides APIs to support automation goals for member firms and the broader financial services industry. APIs provide access to market data, compliance t
  name: FINRA Developer Center API
  slug: finra
- description: Compliance.ai automatically aggregates regulatory data from Federal and State agencies, enforcement actions, regulatory publications, and millions of rules, providing an API for financial institutions
  name: Compliance.ai API
  slug: compliance-ai
- description: Regology is an AI-powered global regulatory compliance platform providing APIs for regulatory research, change management, and compliance workflows. Aggregates and organizes regulatory content from th
  name: Regology API
  slug: regology
- description: London Stock Exchange Group (LSEG) offers a developer portal with APIs for risk and regulatory compliance including sanctions screening, KYC/AML checks, and regulatory reporting tools used by financia
  name: LSEG Risk and Regulatory Compliance API
  slug: lseg-regulatory
common:
- title: ''
  type: Website
  url: https://developer.finra.org/
- title: ''
  type: Website
  url: https://www.compliance.ai/api/
- title: ''
  type: Website
  url: https://regology.com/
- title: ''
  type: Website
  url: https://developers.lseg.com/en/use-cases-catalog/risk-regulatory-compliance
- title: ''
  type: Website
  url: https://www.regulativ.ai/
- title: ''
  type: Website
  url: https://nordicapis.com/10-data-regulations-all-api-developers-should-know-about/
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/json-schema/regulatory-compliance-check-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/json-structure/regulatory-compliance-check-structure.json
- title: ''
  type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/json-ld/regulatory-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/vocabulary/regulatory-vocabulary.yml
- title: ''
  type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/examples/regulatory-compliance-check-finra-example.json
created: '2025-01-01'
description: The regulatory domain encompasses compliance requirements, regulatory reporting, and governance frameworks that organizations must adhere to across industries. APIs in this space enable businesses to automate compliance workflows, track regulatory changes, submit required filings, and manage risk. Key sectors include financial services (SEC, FINRA, CFTC), healthcare (FDA, CMS), telecommunications (FCC), and environmental regulation (EPA).
features: []
image: ''
integrations: []
jsonld:
- class_count: 4
  name: Regulatory Context
  property_count: 6
  slug: regulatory-context
layout: provider
modified: '2026-05-02'
name: Regulatory
skills: []
slug: regulatory
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: regulatory\nname: Regulatory\ndescription: The regulatory domain encompasses compliance requirements, regulatory reporting, and governance frameworks that organizations must adhere to across industries. APIs in this space enable businesses to automate compliance workflows, track regulatory changes, submit required filings, and manage risk. Key sectors include financial services (SEC, FINRA, CFTC), healthcare (FDA, CMS), telecommunications (FCC), and environmental regulation (EPA).\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/apis.yml\ntags:\n  - Compliance\n  - Financial Services\n  - Governance\n  - Healthcare Regulation\n  - Regulatory Reporting\n  - Risk Management\n  - RegTech\ncreated: '2025-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: regulatory:finra\n    name: FINRA Developer Center API\n    description: FINRA (Financial Industry Regulatory Authority) provides APIs to support automation\
  \ goals for member firms and the broader financial services industry. APIs provide access to market data, compliance tools, regulatory filings, and risk management resources.\n    humanURL: https://developer.finra.org/\n    baseURL: https://api.finra.org\n    tags:\n      - Financial Regulation\n      - FINRA\n      - Market Data\n      - Regulatory Compliance\n    properties:\n      - type: Documentation\n        url: https://developer.finra.org/\n  - aid: regulatory:compliance-ai\n    name: Compliance.ai API\n    description: Compliance.ai automatically aggregates regulatory data from Federal and State agencies, enforcement actions, regulatory publications, and millions of rules, providing an API for financial institutions and GRC platforms to stay current on regulatory changes.\n    humanURL: https://www.compliance.ai/api/\n    baseURL: https://api.compliance.ai\n    tags:\n      - Financial Services\n      - Regulatory Change Management\n      - RegTech\n    properties:\n      - type:\
  \ Documentation\n        url: https://www.compliance.ai/api/\n  - aid: regulatory:regology\n    name: Regology API\n    description: Regology is an AI-powered global regulatory compliance platform providing APIs for regulatory research, change management, and compliance workflows. Aggregates and organizes regulatory content from thousands of global sources.\n    humanURL: https://regology.com/\n    baseURL: https://api.regology.com/v1\n    tags:\n      - AI\n      - Compliance\n      - Global Regulation\n      - Regulatory Research\n    properties:\n      - type: Documentation\n        url: https://regology.com/platform\n  - aid: regulatory:lseg-regulatory\n    name: LSEG Risk and Regulatory Compliance API\n    description: London Stock Exchange Group (LSEG) offers a developer portal with APIs for risk and regulatory compliance including sanctions screening, KYC/AML checks, and regulatory reporting tools used by financial institutions globally.\n    humanURL: https://developers.lseg.com/en/use-cases-catalog/risk-regulatory-compliance\n\
  \    baseURL: https://api.refinitiv.com\n    tags:\n      - AML\n      - Financial Services\n      - KYC\n      - Regulatory Reporting\n      - Sanctions Screening\n    properties:\n      - type: Documentation\n        url: https://developers.lseg.com/en/use-cases-catalog/risk-regulatory-compliance\ncommon:\n  - type: Website\n    url: https://developer.finra.org/\n    name: FINRA Developer Center\n  - type: Website\n    url: https://www.compliance.ai/api/\n    name: Compliance.ai Developer Program\n  - type: Website\n    url: https://regology.com/\n    name: Regology AI Regulatory Compliance Platform\n  - type: Website\n    url: https://developers.lseg.com/en/use-cases-catalog/risk-regulatory-compliance\n    name: LSEG Risk and Regulatory Compliance Developer Portal\n  - type: Website\n    url: https://www.regulativ.ai/\n    name: Regulativ AI Compliance Platform\n  - type: Website\n    url: https://nordicapis.com/10-data-regulations-all-api-developers-should-know-about/\n    name: 10\
  \ Data Regulations All API Developers Should Know\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/json-schema/regulatory-compliance-check-schema.json\n    name: Regulatory Compliance Check JSON Schema\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/json-structure/regulatory-compliance-check-structure.json\n    name: Regulatory Compliance Check JSON Structure\n  - type: JSONLD\n    url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/json-ld/regulatory-context.jsonld\n    name: Regulatory JSON-LD Context\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/vocabulary/regulatory-vocabulary.yml\n    name: Regulatory Vocabulary\n  - type: Examples\n    url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/examples/regulatory-compliance-check-finra-example.json\n\
  \    name: FINRA Compliance Check Example\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/apis.yml
tags:
- Compliance
- Financial Services
- Governance
- Healthcare Regulation
- Regulatory Reporting
- Risk Management
- RegTech
url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/apis.yml
use_cases: []
---
