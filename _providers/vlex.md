---
api_count: 3
api_specs:
- filename: vlex-iceberg-anonymization-openapi.yml
  format: yaml
  label: vLex Iceberg Anonymization API
  slug: iceberg-anonymization-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/openapi/vlex-iceberg-anonymization-openapi.yml
- filename: vlex-iceberg-legal-research-openapi.yml
  format: yaml
  label: vLex Iceberg Legal Research API
  slug: iceberg-legal-research-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/openapi/vlex-iceberg-legal-research-openapi.yml
apis:
- description: 'Identifies and anonymizes names and personally identifiable information from any text input. Pre-trained on legal data to recognize names, organizations, and sensitive entities within legal documents '
  name: vLex Iceberg Anonymization API
  slug: iceberg-anonymization-api
- description: AI-powered legal research API providing document search, classification, key phrase extraction, citation detection (vCite), and legal entity identification across vLex's corpus of 100+ million legal d
  name: vLex Iceberg Legal Research API
  slug: iceberg-legal-research-api
- description: Single sign-on authentication API for corporate vLex accounts. Generates redirect URLs using HMAC authentication for seamless user access to vLex.com from institutional portals.
  name: vLex Remote Authentication API
  slug: remote-auth-api
capabilities:
- description: Workflow capability for legal professionals and legaltech developers using vLex AI APIs. Combines legal document search, classification, key phrase extraction, citation detection, and text anonymizati
  name: vLex Legal AI Workflow
  slug: legal-ai-workflow
common:
- title: ''
  type: Website
  url: https://vlex.com/
- title: ''
  type: Developer Portal
  url: https://developer.vlex.com/
- title: ''
  type: Reference
  url: https://developer.vlex.com/apis
- title: ''
  type: Documentation
  url: https://vlex.com/iceberg-ai
- title: ''
  type: Use Cases
  url: https://developer.vlex.com/use-cases
- title: ''
  type: GitHub Organization
  url: https://github.com/vlex
- title: ''
  type: Product
  url: https://vlex.com/products/fastcase
- title: ''
  type: Support
  url: https://support.vlex.com/
created: '2025-03-01'
description: vLex (part of Clio) is a global legal intelligence platform that applies AI to ingest, enrich, classify, and deliver insights from over 100 million legal documents across 2,000+ multilingual sources. The vLex Iceberg platform provides REST APIs for legal document anonymization, classification, key phrase extraction, citation detection, and AI-powered legal research. vLex also offers the Fastcase Legal Data API for raw legal data feeds.
features: []
image: https://vlex.com/hubfs/vlex-logo.svg
integrations: []
jsonld:
- class_count: 11
  name: Vlex Context
  property_count: 23
  slug: vlex-context
layout: provider
modified: '2026-05-03'
name: vLex
rules:
- name: vLex API Rules
  rule_count: 8
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 5
  slug: vlex-rules
skills: []
slug: vlex
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vlex\nname: vLex\ndescription: >-\n  vLex (part of Clio) is a global legal intelligence platform that applies AI\n  to ingest, enrich, classify, and deliver insights from over 100 million legal\n  documents across 2,000+ multilingual sources. The vLex Iceberg platform\n  provides REST APIs for legal document anonymization, classification, key\n  phrase extraction, citation detection, and AI-powered legal research. vLex\n  also offers the Fastcase Legal Data API for raw legal data feeds.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://vlex.com/hubfs/vlex-logo.svg\ntags:\n  - AI\n  - Classification\n  - Legal Research\n  - Legal Tech\n  - Natural Language Processing\n  - Privacy\ncreated: '2025-03-01'\nmodified: '2026-05-03'\nurl: https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: vlex:iceberg-anonymization-api\n    name: vLex Iceberg Anonymization API\n    description: >-\n  \
  \    Identifies and anonymizes names and personally identifiable information\n      from any text input. Pre-trained on legal data to recognize names,\n      organizations, and sensitive entities within legal documents for\n      privacy protection and data compliance.\n    humanURL: https://developer.vlex.com/apis\n    tags:\n      - Anonymization\n      - NLP\n      - Privacy\n      - Legal Tech\n    properties:\n      - type: Documentation\n        url: https://developer.vlex.com/apis\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/openapi/vlex-iceberg-anonymization-openapi.yml\n  - aid: vlex:iceberg-legal-research-api\n    name: vLex Iceberg Legal Research API\n    description: >-\n      AI-powered legal research API providing document search, classification,\n      key phrase extraction, citation detection (vCite), and legal entity\n      identification across vLex's corpus of 100+ million legal documents\n \
  \     from global jurisdictions.\n    humanURL: https://developer.vlex.com/apis\n    tags:\n      - AI\n      - Case Law\n      - Citation Detection\n      - Classification\n      - Legal Research\n      - Legal Tech\n      - Search\n    properties:\n      - type: Documentation\n        url: https://developer.vlex.com/apis\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/openapi/vlex-iceberg-legal-research-openapi.yml\n  - aid: vlex:remote-auth-api\n    name: vLex Remote Authentication API\n    description: >-\n      Single sign-on authentication API for corporate vLex accounts. Generates\n      redirect URLs using HMAC authentication for seamless user access to\n      vLex.com from institutional portals.\n    humanURL: https://github.com/vlex/remote_auth\n    tags:\n      - Authentication\n      - Single Sign-On\n      - SSO\n    properties:\n      - type: GitHub Repository\n        url: https://github.com/vlex/remote_auth\n\
  common:\n  - url: https://vlex.com/\n    type: Website\n  - url: https://developer.vlex.com/\n    type: Developer Portal\n  - url: https://developer.vlex.com/apis\n    type: Reference\n  - url: https://vlex.com/iceberg-ai\n    type: Documentation\n  - url: https://developer.vlex.com/use-cases\n    type: Use Cases\n  - url: https://vlex.com/integrations\n    type: Integrations\n  - url: https://github.com/vlex\n    type: GitHub Organization\n  - url: https://vlex.com/products/fastcase\n    type: Product\n  - url: https://support.vlex.com/\n    type: Support\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/apis.yml
tags:
- AI
- Classification
- Legal Research
- Legal Tech
- Natural Language Processing
- Privacy
url: https://raw.githubusercontent.com/api-evangelist/vlex/refs/heads/main/apis.yml
use_cases: []
---
