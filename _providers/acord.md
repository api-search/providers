---
api_count: 3
apis:
- description: ACORD XML Standards define data exchange formats for property & casualty, life, annuity, and reinsurance using SOAP/XML protocols. APIs enable claims inquiry, policy administration, and regulatory rep
  name: ACORD XML Standards API
  slug: acord-xml-standards-api
- description: The ACORD Next-Generation Digital Standards (NGDS) Object Model provides granular, transaction-centric standards for APIs, microservices, IoT, and RESTful architectures. Based on JSON and YAML data-in
  name: ACORD Next-Generation Digital Standards (NGDS) API
  slug: acord-ngds-api
- description: ACORD Global Reinsurance & Large Commercial Data Standards define XML data exchange formats for reinsurance and large commercial lines. APIs support facultative and treaty reinsurance transactions, pl
  name: ACORD Reinsurance & Large Commercial Data Standards API
  slug: acord-reinsurance-standards-api
capabilities:
- description: Unified insurance data exchange workflow for policy administration, claims management, party registry, and underwriting using ACORD Next-Generation Digital Standards (NGDS). Used by insurance carriers
  name: ACORD Insurance Data Exchange
  slug: insurance-data-exchange
common:
- title: ''
  type: Website
  url: https://www.acord.org
- title: ''
  type: Portal
  url: https://www.acord.org/standards-architecture/acord-data-standards
- title: ''
  type: Documentation
  url: https://www.acord.org/standards-architecture/acord-data-standards
- title: ''
  type: GettingStarted
  url: https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards
- title: ''
  type: Documentation
  url: https://www.acord.org/standards-architecture/reference-architecture
- title: ''
  type: Support
  url: https://www.acord.org/standards-architecture/get-involved/standards-project-advisory-groups
- title: ''
  type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/openapi/acord-ngds-openapi.yml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/acord-policy-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/acord-claim-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-ld/acord-context.jsonld
- title: ''
  type: GitHubOrganization
  url: https://github.com/api-evangelist/acord
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/rules/acord-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/capabilities/insurance-data-exchange.yaml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/vocabulary/acord-vocabulary.yaml
created: ''
description: ACORD is a global standards-setting body for the insurance industry, providing data standards, reference architecture, and digital tools that enable insurers, brokers, and software providers to exchange information.
features:
- description: ACORD XML standards for property & casualty, life, annuity, and reinsurance SOAP/XML data exchange.
  name: XML Data Standards
- description: JSON/YAML-based NGDS for RESTful APIs, microservices, and IoT insurance data exchange.
  name: Next-Generation Digital Standards
- description: Global reinsurance and large commercial data standards for facultative and treaty transactions.
  name: Reinsurance Standards
- description: Electronic data standards for life insurance and annuity products covering underwriting and policy management.
  name: Life and Annuity Standards
- description: ACORD reference architecture providing structural frameworks for insurance technology implementations.
  name: Reference Architecture
image: /assets/icons/acord.png
integrations:
- description: Integration with policy administration systems (PAS) and claims management systems (CMS).
  name: Insurance Core Systems
- description: Integration with reinsurance management platforms supporting ACORD AL3 and RIBO formats.
  name: Reinsurance Platforms
- description: Modern insurtech API platforms consuming ACORD NGDS JSON standards.
  name: Insurtech Solutions
- description: Integration with state and national insurance regulatory reporting systems.
  name: Regulatory Systems
jsonld:
- class_count: 0
  name: Acord Context
  property_count: 5
  slug: acord-context
- class_count: 19
  name: Acord Ngds Context
  property_count: 55
  slug: acord-ngds-context
layout: provider
modified: '2026-04-19'
name: ACORD
rules:
- name: ACORD API Rules
  rule_count: 33
  severity_counts:
    error: 14
    hint: 0
    info: 2
    warn: 17
  slug: acord-spectral-rules
skills: []
slug: acord
solutions: []
source_yaml: "aid: acord\nurl: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/apis.yml\napis:\n- aid: acord:acord-xml-standards-api\n  name: ACORD XML Standards API\n  tags:\n  - ACORD\n  - Claims\n  - Insurance\n  - Policy\n  - Property Casualty\n  - SOAP\n  - XML\n  image: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/image.png\n  humanURL: https://www.acord.org/standards-architecture/acord-data-standards\n  baseURL: https://claims.insurer-internal.example.com/acord\n  properties:\n  - url: https://www.acord.org/standards-architecture/acord-data-standards\n    type: Documentation\n  - url: https://www.acord.org/standards-architecture/acord-data-standards\n    type: Reference\n  description: >-\n    ACORD XML Standards define data exchange formats for property & casualty, life,\n    annuity, and reinsurance using SOAP/XML protocols. APIs enable claims inquiry,\n    policy administration, and regulatory reporting across insurers, reinsurers,\n\
  \    and intermediaries.\n\n- aid: acord:acord-ngds-api\n  name: ACORD Next-Generation Digital Standards (NGDS) API\n  tags:\n  - ACORD\n  - Digital Standards\n  - Insurance\n  - IoT\n  - JSON\n  - Microservices\n  - REST\n  image: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/image.png\n  humanURL: https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards\n  baseURL: https://api.insurer-internal.example.com/ngds\n  properties:\n  - url: https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards\n    type: Documentation\n  - url: https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards\n    type: Reference\n  - url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/openapi/acord-ngds-openapi.yml\n    type: OpenAPI\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/ngds-policy-schema.json\n\
  \  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/ngds-claim-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/ngds-party-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/ngds-coverage-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/ngds-underwriting-submission-schema.json\n  - type: NaftikoCapability\n    url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/capabilities/shared/acord-ngds.yaml\n  description: >-\n    The ACORD Next-Generation Digital Standards (NGDS) Object Model provides granular,\n    transaction-centric standards for APIs, microservices, IoT, and RESTful architectures.\n    Based on JSON and YAML data-interchange formats, NGDS enables modern insurance\n\
  \    data exchange for underwriting, policy management, and claims administration.\n\n- aid: acord:acord-reinsurance-standards-api\n  name: ACORD Reinsurance & Large Commercial Data Standards API\n  tags:\n  - Data Standards\n  - Insurance\n  - Large Commercial\n  - Reinsurance\n  - XML\n  image: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/image.png\n  humanURL: https://www.acord.org/standards-architecture/acord-data-standards/Global_Reinsurance_Data_Standards\n  baseURL: https://reinsurance.insurer-internal.example.com/acord\n  properties:\n  - url: https://www.acord.org/standards-architecture/acord-data-standards/Global_Reinsurance_Data_Standards\n    type: Documentation\n  description: >-\n    ACORD Global Reinsurance & Large Commercial Data Standards define XML data exchange\n    formats for reinsurance and large commercial lines. APIs support facultative\n    and treaty reinsurance transactions, placement, and settlement between cedants,\n    reinsurers,\
  \ and brokers.\n\ncommon:\n- url: https://www.acord.org\n  type: Website\n- url: https://www.acord.org/standards-architecture/acord-data-standards\n  type: Portal\n- url: https://www.acord.org/standards-architecture/acord-data-standards\n  type: Documentation\n- url: https://www.acord.org/standards-architecture/acord-data-standards/next-generation-digital-standards\n  type: GettingStarted\n- url: https://www.acord.org/standards-architecture/reference-architecture\n  type: Documentation\n- url: https://www.acord.org/standards-architecture/get-involved/standards-project-advisory-groups\n  type: Support\n- url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/openapi/acord-ngds-openapi.yml\n  type: OpenAPI\n- url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/acord-policy-schema.json\n  type: JSONSchema\n- url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-schema/acord-claim-schema.json\n  type: JSONSchema\n\
  - url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/json-ld/acord-context.jsonld\n  type: JSONLDContext\n\n- type: GitHubOrganization\n  url: https://github.com/api-evangelist/acord\n- type: SpectralRules\n  url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/rules/acord-spectral-rules.yml\n- type: NaftikoCapability\n  url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/capabilities/insurance-data-exchange.yaml\n- type: Vocabulary\n  url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/vocabulary/acord-vocabulary.yaml\n- type: Features\n  data:\n  - name: XML Data Standards\n    description: ACORD XML standards for property & casualty, life, annuity, and reinsurance SOAP/XML data exchange.\n  - name: Next-Generation Digital Standards\n    description: JSON/YAML-based NGDS for RESTful APIs, microservices, and IoT insurance data exchange.\n  - name: Reinsurance Standards\n    description: Global\
  \ reinsurance and large commercial data standards for facultative and treaty transactions.\n  - name: Life and Annuity Standards\n    description: Electronic data standards for life insurance and annuity products covering underwriting and policy management.\n  - name: Reference Architecture\n    description: ACORD reference architecture providing structural frameworks for insurance technology implementations.\n- type: UseCases\n  data:\n  - name: Claims Data Exchange\n    description: Standardized ACORD XML or NGDS JSON claims transaction exchange between carriers, adjusters, and reinsurers.\n  - name: Policy Administration\n    description: Automated policy issuance, endorsement, and renewal using ACORD NGDS microservices architecture.\n  - name: Underwriting Automation\n    description: Straight-through processing of insurance applications using ACORD standardized data elements.\n  - name: Reinsurance Settlement\n    description: Facultative and treaty reinsurance data exchange using\
  \ ACORD Global Reinsurance Data Standards.\n  - name: Regulatory Reporting\n    description: Compliance reporting using ACORD-standardized data formats for regulatory submissions.\n- type: Integrations\n  data:\n  - name: Insurance Core Systems\n    description: Integration with policy administration systems (PAS) and claims management systems (CMS).\n  - name: Reinsurance Platforms\n    description: Integration with reinsurance management platforms supporting ACORD AL3 and RIBO formats.\n  - name: Insurtech Solutions\n    description: Modern insurtech API platforms consuming ACORD NGDS JSON standards.\n  - name: Regulatory Systems\n    description: Integration with state and national insurance regulatory reporting systems.\nmaintainers:\n- name: Kin Lane\n  email: kin@apievangelist.com\n\nmodified: '2026-04-19'\ndescription: >-\n  ACORD is a global standards-setting body for the insurance industry, providing data\n  standards, reference architecture, and digital tools that enable insurers,\
  \ brokers,\n  and software providers to exchange information.\nname: ACORD\ntype: Index\nspecificationVersion: '0.19'\ntags:\n- Claims\n- Insurance\n- Policy\n- Standards\n- Underwriting\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/apis.yml
tags:
- Claims
- Insurance
- Policy
- Standards
- Underwriting
url: https://raw.githubusercontent.com/api-evangelist/acord/refs/heads/main/apis.yml
use_cases:
- description: Standardized ACORD XML or NGDS JSON claims transaction exchange between carriers, adjusters, and reinsurers.
  name: Claims Data Exchange
- description: Automated policy issuance, endorsement, and renewal using ACORD NGDS microservices architecture.
  name: Policy Administration
- description: Straight-through processing of insurance applications using ACORD standardized data elements.
  name: Underwriting Automation
- description: Facultative and treaty reinsurance data exchange using ACORD Global Reinsurance Data Standards.
  name: Reinsurance Settlement
- description: Compliance reporting using ACORD-standardized data formats for regulatory submissions.
  name: Regulatory Reporting
---
