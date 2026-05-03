---
api_count: 3
apis:
- description: The Clearview AI facial recognition platform provides image-based identity matching backed by an indexed corpus of publicly available imagery. Access is restricted to vetted government, law enforcemen
  name: Clearview AI Facial Recognition Platform
  slug: facial-recognition
- description: 'Clearview AI offers investigation tooling for vetted law enforcement and public-safety users that surfaces matching imagery and source links for an uploaded probe image. Workflow tooling is delivered '
  name: Clearview AI Investigation Tools
  slug: investigation-tools
- description: Clearview AI markets identity-verification capabilities to regulated financial-services customers for fraud prevention, KYC enrichment, and investigative review. Integration is delivered as a vendor-m
  name: Clearview AI Financial Services
  slug: financial-services
capabilities:
- description: ''
  name: Clearview Ai
  slug: clearview-ai
common:
- title: ''
  type: Website
  url: https://www.clearview.ai/
- title: ''
  type: About
  url: https://www.clearview.ai/about-us
- title: ''
  type: Transparency
  url: https://www.clearview.ai/post/transparency-report
- title: ''
  type: Privacy Policy
  url: https://www.clearview.ai/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.clearview.ai/terms-of-service
- title: ''
  type: Contact
  url: https://www.clearview.ai/contact
- title: ''
  type: News
  url: https://www.clearview.ai/news
- title: ''
  type: JSON-LD
  url: json-ld/clearview-ai-context.jsonld
- title: ''
  type: Spectral
  url: rules/clearview-ai-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/clearview-ai.yaml
created: '2024-01-01'
description: Clearview AI is a U.S.-based facial recognition company providing identity verification, investigative search, and biometric matching services primarily to law enforcement, government agencies, and approved financial sector customers. The platform indexes publicly available images and exposes proprietary facial recognition technology through a controlled, customer-vetted developer surface. Public technical documentation of the API is intentionally limited; access is gated, and integrations are scoped through customer agreements with strict use-case, audit, and transparency requirements.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Clearview Ai Context
  property_count: 4
  slug: clearview-ai-context
layout: provider
modified: '2026-04-23'
name: Clearview AI
rules:
- name: Clearview AI API Rules
  rule_count: 8
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 4
  slug: clearview-ai-rules
skills: []
slug: clearview-ai
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: clearview-ai\nname: Clearview AI\ndescription: >-\n  Clearview AI is a U.S.-based facial recognition company providing\n  identity verification, investigative search, and biometric matching\n  services primarily to law enforcement, government agencies, and\n  approved financial sector customers. The platform indexes publicly\n  available images and exposes proprietary facial recognition\n  technology through a controlled, customer-vetted developer surface.\n  Public technical documentation of the API is intentionally limited;\n  access is gated, and integrations are scoped through customer\n  agreements with strict use-case, audit, and transparency\n  requirements.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/clearview-ai/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\nx-type: company\ntags:\n  - Biometrics\n  -\
  \ Facial Recognition\n  - Identity\n  - Investigations\n  - Law Enforcement\n  - Surveillance\napis:\n  - aid: clearview-ai:facial-recognition\n    name: Clearview AI Facial Recognition Platform\n    tags:\n      - Biometrics\n      - Facial Recognition\n      - Identity Verification\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.clearview.ai/\n    properties:\n      - url: https://www.clearview.ai/\n        type: Website\n      - url: https://www.clearview.ai/post/transparency-report\n        type: Transparency\n    description: >-\n      The Clearview AI facial recognition platform provides image-based\n      identity matching backed by an indexed corpus of publicly\n      available imagery. Access is restricted to vetted government,\n      law enforcement, and financial-services customers under\n      contractual use-case constraints. Technical integration details\n      are not publicly documented; customers receive\
  \ credentials,\n      endpoints, and reference material directly from Clearview AI\n      after onboarding.\n  - aid: clearview-ai:investigation-tools\n    name: Clearview AI Investigation Tools\n    tags:\n      - Investigations\n      - Law Enforcement\n      - Search\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.clearview.ai/law-enforcement\n    properties:\n      - url: https://www.clearview.ai/law-enforcement\n        type: Documentation\n    description: >-\n      Clearview AI offers investigation tooling for vetted law\n      enforcement and public-safety users that surfaces matching\n      imagery and source links for an uploaded probe image. Workflow\n      tooling is delivered through a hosted user interface; programmatic\n      access, when granted, is governed by separate customer agreements.\n  - aid: clearview-ai:financial-services\n    name: Clearview AI Financial Services\n    tags:\n      - Financial Services\n\
  \      - Identity Verification\n      - KYC\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.clearview.ai/\n    properties:\n      - url: https://www.clearview.ai/\n        type: Documentation\n    description: >-\n      Clearview AI markets identity-verification capabilities to\n      regulated financial-services customers for fraud prevention,\n      KYC enrichment, and investigative review. Integration is\n      delivered as a vendor-managed service with contractual\n      controls; public API documentation is not provided.\ncommon:\n  - type: Website\n    url: https://www.clearview.ai/\n  - type: About\n    url: https://www.clearview.ai/about-us\n  - type: Transparency\n    url: https://www.clearview.ai/post/transparency-report\n  - type: Privacy Policy\n    url: https://www.clearview.ai/privacy-policy\n  - type: Terms of Service\n    url: https://www.clearview.ai/terms-of-service\n  - type: Contact\n    url: https://www.clearview.ai/contact\n\
  \  - type: News\n    url: https://www.clearview.ai/news\n  - type: JSON-LD\n    url: json-ld/clearview-ai-context.jsonld\n  - type: Spectral\n    url: rules/clearview-ai-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/clearview-ai.yaml\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/clearview-ai/refs/heads/main/apis.yml
tags:
- Biometrics
- Facial Recognition
- Identity
- Investigations
- Law Enforcement
- Surveillance
url: https://raw.githubusercontent.com/api-evangelist/clearview-ai/refs/heads/main/apis.yml
use_cases: []
---
