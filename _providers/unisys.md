---
api_count: 1
api_specs:
- filename: unisys-stealth-ecoapi-openapi.yaml
  format: yaml
  label: Unisys Stealth EcoAPI
  slug: unisys-stealth-ecoapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/openapi/unisys-stealth-ecoapi-openapi.yaml
apis:
- description: The Unisys Stealth EcoAPI enables security teams and automation platforms to integrate with Unisys Stealth zero trust network segmentation. Using the EcoAPI, teams can programmatically isolate and un-
  name: Unisys Stealth EcoAPI
  slug: unisys-stealth-ecoapi
capabilities:
- description: Zero trust security operations workflow for dynamic endpoint and user isolation, security incident response, and Stealth network management. Used by security operations teams, SIEM/SOAR platforms, and
  name: Unisys Zero Trust Security Operations
  slug: zero-trust-security
common: []
created: '2025-02-06'
description: Unisys is a global information technology company that provides specialized solutions integrated with leading-edge security. Unisys delivers digital workplace services, cloud and infrastructure services, and enterprise computing solutions including the ClearPath mainframe platform and the Unisys Stealth zero trust security suite. Unisys serves clients across industries including financial services, government, healthcare, and transportation.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Unisys Context
  property_count: 11
  slug: unisys-context
layout: provider
modified: '2026-05-03'
name: Unisys
rules:
- name: Unisys API Rules
  rule_count: 30
  severity_counts:
    error: 13
    hint: 0
    info: 3
    warn: 14
  slug: unisys-stealth-spectral-rules
skills: []
slug: unisys
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: unisys\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/apis.yml\napis:\n  - aid: unisys:unisys-stealth-ecoapi\n    name: Unisys Stealth EcoAPI\n    tags:\n      - Security\n      - Zero Trust\n      - Network Security\n      - Endpoint Isolation\n      - Cybersecurity\n    humanURL: https://stealthsecurity.unisys.com\n    baseURL: https://stealth-server:8448\n    properties:\n      - url: https://stealthsecurity.unisys.com/resources/\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/openapi/unisys-stealth-ecoapi-openapi.yaml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/rules/unisys-stealth-spectral-rules.yml\n        type: SpectralRules\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/capabilities/shared/unisys-stealth-ecoapi.yaml\n\
  \        type: NaftikoCapability\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/capabilities/zero-trust-security.yaml\n        type: NaftikoCapability\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/vocabulary/unisys-vocabulary.yaml\n        type: Vocabulary\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-ld/unisys-context.jsonld\n        type: JSONLDContext\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-schema/unisys-stealth-role-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-schema/unisys-isolation-request-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-schema/unisys-unisolation-request-schema.json\n\
  \        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-schema/unisys-action-response-schema.json\n        type: JSONSchema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-structure/unisys-stealth-role-structure.json\n        type: JSONStructure\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-structure/unisys-isolation-request-structure.json\n        type: JSONStructure\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-structure/unisys-action-response-structure.json\n        type: JSONStructure\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/examples/unisys-stealth-isolate-endpoint-example.json\n        type: Example\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/examples/unisys-stealth-isolate-user-example.json\n\
  \        type: Example\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/examples/unisys-stealth-get-roles-example.json\n        type: Example\n    description: >-\n      The Unisys Stealth EcoAPI enables security teams and automation platforms\n      to integrate with Unisys Stealth zero trust network segmentation. Using the\n      EcoAPI, teams can programmatically isolate and un-isolate endpoints and users\n      from the Stealth network in response to security events, retrieve Stealth role\n      configurations, and manage dynamic endpoint isolation workflows. The API uses\n      HTTP Basic authentication against a configurable Stealth server endpoint.\n    data:\n      - name: Features\n        data:\n          - name: Dynamic Endpoint Isolation\n            description: Programmatically isolate compromised endpoints from the Stealth zero trust network in real time\n          - name: Dynamic User Isolation\n            description:\
  \ Isolate specific users from network access without disrupting other endpoints or users\n          - name: Combined Isolation\n            description: Simultaneously isolate both an endpoint and associated user in a single API call\n          - name: Role-Based Isolation Policies\n            description: Apply specific Stealth isolation role policies during isolation for granular containment\n          - name: Un-Isolation and Restoration\n            description: Restore isolated endpoints and users to normal Stealth network access after incident resolution\n          - name: Stealth Role Retrieval\n            description: Retrieve available Stealth isolation role configurations for policy selection\n          - name: SOAR/SIEM Integration\n            description: Integrate with security orchestration platforms for automated incident response workflows\n      - name: UseCases\n        data:\n          - name: Incident Response Containment\n            description: Security operations\
  \ teams isolate compromised endpoints immediately upon alert detection\n          - name: SOAR Automation\n            description: SOAR platforms trigger Stealth isolation automatically based on SIEM threat detection rules\n          - name: Insider Threat Containment\n            description: Isolate specific users when suspicious activity is detected while preserving investigation access\n          - name: Ransomware Containment\n            description: Rapidly isolate infected endpoints to prevent lateral movement and ransomware spread\n          - name: Compliance-Driven Isolation\n            description: Enforce regulatory compliance by isolating non-compliant endpoints from sensitive network segments\n      - name: Integrations\n        data:\n          - name: SIEM Platforms\n            description: Integrate with Splunk, IBM QRadar, and Microsoft Sentinel for automated threat-triggered isolation\n          - name: SOAR Platforms\n            description: Connect with Palo Alto\
  \ XSOAR, Splunk SOAR, and other orchestration platforms\n          - name: Vulnerability Management\n            description: Trigger isolation based on critical vulnerability scan results\n          - name: Endpoint Detection and Response\n            description: Integrate with EDR solutions to trigger Stealth isolation for confirmed threats\n\nname: Unisys\ntags:\n  - Security\n  - Zero Trust\n  - Network Security\n  - IT Services\n  - Cybersecurity\n  - Enterprise Technology\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-02-06'\nmodified: '2026-05-03'\nposition: Consumer\ndescription: >-\n  Unisys is a global information technology company that provides specialized solutions\n  integrated with leading-edge security. Unisys delivers digital workplace services,\n  cloud and infrastructure services, and enterprise computing solutions including the\n  ClearPath mainframe platform and the Unisys Stealth zero\
  \ trust security suite. Unisys\n  serves clients across industries including financial services, government, healthcare,\n  and transportation.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/apis.yml
tags:
- Security
- Zero Trust
- Network Security
- IT Services
- Cybersecurity
- Enterprise Technology
url: https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/apis.yml
use_cases: []
---
