---
api_count: 5
apis:
- description: The foundational specification of the Zero Trust security model. Defines the seven tenets, the PDP/PEP/PA logical components, and the deployment variants (enhanced identity governance, microsegmentati
  name: NIST SP 800-207 Zero Trust Architecture
  slug: nist-sp-800-207
- description: CISA's Zero Trust Maturity Model defines four maturity levels (Traditional, Initial, Advanced, Optimal) across five pillars (Identity, Devices, Networks, Applications & Workloads, Data) and three cros
  name: CISA Zero Trust Maturity Model
  slug: cisa-zero-trust-maturity-model
- description: The Department of Defense Zero Trust Reference Architecture defines the seven DoD Zero Trust pillars (User, Device, Application & Workload, Data, Network & Environment, Automation & Orchestration, Vis
  name: DoD Zero Trust Reference Architecture
  slug: dod-zero-trust-reference-architecture
- description: A series of NSA Cybersecurity Information Sheets providing pillar-by- pillar guidance for implementing Zero Trust, including the Network and Environment, User, Device, Application & Workload, and Data
  name: NSA Zero Trust Guidance
  slug: nsa-zero-trust-guidance
- description: The UK National Cyber Security Centre's eight Zero Trust design principles, providing the British government's view of Zero Trust architecture for both public-sector and private organizations.
  name: UK NCSC Zero Trust Architecture Design Principles
  slug: ncsc-zero-trust-principles
common:
- title: NIST Zero Trust Architecture
  type: Documentation
  url: https://www.nist.gov/publications/zero-trust-architecture
- title: NIST SP 800-207 PDF
  type: Documentation
  url: https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf
- title: NIST SP 800-207A PDF
  type: Documentation
  url: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-207A.pdf
- title: CISA Zero Trust Maturity Model
  type: Compliance
  url: https://www.cisa.gov/zero-trust-maturity-model
- title: OMB M-22-09 Federal Zero Trust Strategy
  type: Compliance
  url: https://www.whitehouse.gov/wp-content/uploads/2022/01/M-22-09.pdf
- title: DoD Zero Trust Reference Architecture
  type: Compliance
  url: https://dodcio.defense.gov/Portals/0/Documents/Library/ZT-Reference-Architecture.pdf
- title: NSA Zero Trust Guidance
  type: Documentation
  url: https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2899282/nsa-releases-guidance-on-zero-trust-security-model/
- title: UK NCSC Zero Trust
  type: Documentation
  url: https://www.ncsc.gov.uk/collection/zero-trust-architecture
- title: Cloudflare Learning - What Is Zero Trust
  type: Portal
  url: https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/
- title: Microsoft Zero Trust Guidance Center
  type: Portal
  url: https://learn.microsoft.com/en-us/security/zero-trust/
- title: Google BeyondCorp
  type: Portal
  url: https://cloud.google.com/beyondcorp
- title: SPIFFE
  type: GitHubOrganization
  url: https://github.com/spiffe
- title: Open Policy Agent
  type: GitHubOrganization
  url: https://github.com/open-policy-agent
- title: Zero Trust Pillar Schema
  type: JSONSchema
  url: json-schema/zero-trust-security-model-pillar-schema.json
- title: Zero Trust Maturity Assessment Schema
  type: JSONSchema
  url: json-schema/zero-trust-security-model-maturity-schema.json
- title: Zero Trust Pillar Structure
  type: JSONStructure
  url: json-structure/zero-trust-security-model-pillar-structure.json
- title: Zero Trust Security Model JSON-LD Context
  type: JSONLD
  url: json-ld/zero-trust-security-model-context.jsonld
- title: Zero Trust Maturity Assessment Example
  type: CodeExamples
  url: examples/zero-trust-security-model-maturity-example.json
- title: Zero Trust Security Model Vocabulary
  type: Resources
  url: vocabulary/zero-trust-security-model-vocabulary.yaml
created: '2025'
description: The Zero Trust security model is a strategic cybersecurity approach that eliminates implicit trust and requires continuous verification of every user, device, workload, and request attempting to access resources, regardless of network location. It is rooted in NIST SP 800-207, formalized for federal agencies by the CISA Zero Trust Maturity Model and the DoD Zero Trust Reference Architecture, and operationalized by NSA, NCSC, and industry guidance. This topic indexes the canonical specifications, guidance documents, advocacy organizations, and reference data schemas that describe the Zero Trust security model and its pillars (Identity, Devices, Networks, Applications & Workloads, Data, Visibility & Analytics, Automation & Orchestration).
features:
- description: No user, device, or network is trusted by default; every access is verified.
  name: Never Trust Always Verify
- description: Authentication and authorization happen for every request using all available signals.
  name: Explicit Verification
- description: Users and workloads receive only the minimum permissions required for the task.
  name: Least Privilege Access
- description: The model is designed assuming attackers are already present in the environment.
  name: Assume Breach
- description: All sessions and signals are continuously analyzed and policies re-evaluated.
  name: Continuous Monitoring
- description: Networks and workloads are segmented to limit blast radius after compromise.
  name: Microsegmentation
- description: Security controls follow the data, not the perimeter.
  name: Data-Centric Protection
- description: User and workload identity replaces network location as the primary trust boundary.
  name: Identity as the Perimeter
image: ''
integrations: []
jsonld:
- class_count: 19
  name: Zero Trust Security Model Context
  property_count: 0
  slug: zero-trust-security-model-context
layout: provider
modified: '2026-05-03'
name: Zero-Trust Security Model
skills: []
slug: zero-trust-security-model
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zero-trust-security-model\nname: Zero-Trust Security Model\ndescription: >-\n  The Zero Trust security model is a strategic cybersecurity approach that\n  eliminates implicit trust and requires continuous verification of every\n  user, device, workload, and request attempting to access resources,\n  regardless of network location. It is rooted in NIST SP 800-207, formalized\n  for federal agencies by the CISA Zero Trust Maturity Model and the DoD\n  Zero Trust Reference Architecture, and operationalized by NSA, NCSC, and\n  industry guidance. This topic indexes the canonical specifications,\n  guidance documents, advocacy organizations, and reference data schemas\n  that describe the Zero Trust security model and its pillars (Identity,\n  Devices, Networks, Applications & Workloads, Data, Visibility & Analytics,\n  Automation & Orchestration).\ntype: Index\nurl: https://www.nist.gov/publications/zero-trust-architecture\ntags:\n  - Access Control\n  - Cybersecurity\n  -\
  \ Federal\n  - Identity Management\n  - Network Security\n  - NIST\n  - Security\n  - Security Framework\n  - Zero Trust\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: zero-trust-security-model:nist-sp-800-207\n    name: NIST SP 800-207 Zero Trust Architecture\n    description: >-\n      The foundational specification of the Zero Trust security model.\n      Defines the seven tenets, the PDP/PEP/PA logical components, and the\n      deployment variants (enhanced identity governance, microsegmentation,\n      and network infrastructure / SDP).\n    humanURL: https://csrc.nist.gov/pubs/sp/800/207/final\n    tags:\n      - NIST\n      - Specification\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://csrc.nist.gov/pubs/sp/800/207/final\n      - type: APIReference\n        url: https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf\n  - aid: zero-trust-security-model:cisa-zero-trust-maturity-model\n\
  \    name: CISA Zero Trust Maturity Model\n    description: >-\n      CISA's Zero Trust Maturity Model defines four maturity levels\n      (Traditional, Initial, Advanced, Optimal) across five pillars\n      (Identity, Devices, Networks, Applications & Workloads, Data) and three\n      cross-cutting capabilities (Visibility & Analytics, Automation &\n      Orchestration, Governance). It is the federal-civilian roadmap for\n      Zero Trust adoption.\n    humanURL: https://www.cisa.gov/zero-trust-maturity-model\n    tags:\n      - CISA\n      - Federal\n      - Maturity Model\n    properties:\n      - type: Documentation\n        url: https://www.cisa.gov/zero-trust-maturity-model\n      - type: APIReference\n        url: https://www.cisa.gov/sites/default/files/2023-04/zero_trust_maturity_model_v2_508.pdf\n  - aid: zero-trust-security-model:dod-zero-trust-reference-architecture\n    name: DoD Zero Trust Reference Architecture\n    description: >-\n      The Department of Defense Zero Trust\
  \ Reference Architecture defines\n      the seven DoD Zero Trust pillars (User, Device, Application & Workload,\n      Data, Network & Environment, Automation & Orchestration, Visibility &\n      Analytics) and 152 capabilities across target and advanced activities.\n    humanURL: https://dodcio.defense.gov/library/\n    tags:\n      - DoD\n      - Federal\n      - Reference Architecture\n    properties:\n      - type: Documentation\n        url: https://dodcio.defense.gov/Portals/0/Documents/Library/ZT-Reference-Architecture.pdf\n  - aid: zero-trust-security-model:nsa-zero-trust-guidance\n    name: NSA Zero Trust Guidance\n    description: >-\n      A series of NSA Cybersecurity Information Sheets providing pillar-by-\n      pillar guidance for implementing Zero Trust, including the Network and\n      Environment, User, Device, Application & Workload, and Data pillars.\n    humanURL: https://www.nsa.gov/Cybersecurity/\n    tags:\n      - Federal\n      - Guidance\n      - NSA\n    properties:\n\
  \      - type: Documentation\n        url: https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2899282/nsa-releases-guidance-on-zero-trust-security-model/\n  - aid: zero-trust-security-model:ncsc-zero-trust-principles\n    name: UK NCSC Zero Trust Architecture Design Principles\n    description: >-\n      The UK National Cyber Security Centre's eight Zero Trust design\n      principles, providing the British government's view of Zero Trust\n      architecture for both public-sector and private organizations.\n    humanURL: https://www.ncsc.gov.uk/collection/zero-trust-architecture\n    tags:\n      - Guidance\n      - NCSC\n      - UK\n    properties:\n      - type: Documentation\n        url: https://www.ncsc.gov.uk/collection/zero-trust-architecture\ncommon:\n  - type: Documentation\n    title: NIST Zero Trust Architecture\n    url: https://www.nist.gov/publications/zero-trust-architecture\n    description: NIST landing page for Zero Trust Architecture publications.\n  - type:\
  \ Documentation\n    title: NIST SP 800-207 PDF\n    url: https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf\n  - type: Documentation\n    title: NIST SP 800-207A PDF\n    url: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-207A.pdf\n  - type: Compliance\n    title: CISA Zero Trust Maturity Model\n    url: https://www.cisa.gov/zero-trust-maturity-model\n  - type: Compliance\n    title: OMB M-22-09 Federal Zero Trust Strategy\n    url: https://www.whitehouse.gov/wp-content/uploads/2022/01/M-22-09.pdf\n    description: White House OMB memorandum mandating Zero Trust adoption across federal civilian agencies.\n  - type: Compliance\n    title: DoD Zero Trust Reference Architecture\n    url: https://dodcio.defense.gov/Portals/0/Documents/Library/ZT-Reference-Architecture.pdf\n  - type: Documentation\n    title: NSA Zero Trust Guidance\n    url: https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2899282/nsa-releases-guidance-on-zero-trust-security-model/\n\
  \  - type: Documentation\n    title: UK NCSC Zero Trust\n    url: https://www.ncsc.gov.uk/collection/zero-trust-architecture\n  - type: Portal\n    title: Cloudflare Learning - What Is Zero Trust\n    url: https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/\n  - type: Portal\n    title: Microsoft Zero Trust Guidance Center\n    url: https://learn.microsoft.com/en-us/security/zero-trust/\n  - type: Portal\n    title: Google BeyondCorp\n    url: https://cloud.google.com/beyondcorp\n  - type: GitHubOrganization\n    title: SPIFFE\n    url: https://github.com/spiffe\n  - type: GitHubOrganization\n    title: Open Policy Agent\n    url: https://github.com/open-policy-agent\n  - type: JSONSchema\n    title: Zero Trust Pillar Schema\n    url: json-schema/zero-trust-security-model-pillar-schema.json\n  - type: JSONSchema\n    title: Zero Trust Maturity Assessment Schema\n    url: json-schema/zero-trust-security-model-maturity-schema.json\n  - type: JSONStructure\n    title:\
  \ Zero Trust Pillar Structure\n    url: json-structure/zero-trust-security-model-pillar-structure.json\n  - type: JSONLD\n    title: Zero Trust Security Model JSON-LD Context\n    url: json-ld/zero-trust-security-model-context.jsonld\n  - type: CodeExamples\n    title: Zero Trust Maturity Assessment Example\n    url: examples/zero-trust-security-model-maturity-example.json\n  - type: Resources\n    title: Zero Trust Security Model Vocabulary\n    url: vocabulary/zero-trust-security-model-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Never Trust Always Verify\n        description: No user, device, or network is trusted by default; every access is verified.\n      - name: Explicit Verification\n        description: Authentication and authorization happen for every request using all available signals.\n      - name: Least Privilege Access\n        description: Users and workloads receive only the minimum permissions required for the task.\n      - name: Assume Breach\n   \
  \     description: The model is designed assuming attackers are already present in the environment.\n      - name: Continuous Monitoring\n        description: All sessions and signals are continuously analyzed and policies re-evaluated.\n      - name: Microsegmentation\n        description: Networks and workloads are segmented to limit blast radius after compromise.\n      - name: Data-Centric Protection\n        description: Security controls follow the data, not the perimeter.\n      - name: Identity as the Perimeter\n        description: User and workload identity replaces network location as the primary trust boundary.\n  - type: UseCases\n    data:\n      - name: Federal Civilian Compliance\n        description: Meeting OMB M-22-09 and CISA Zero Trust Maturity Model requirements.\n      - name: DoD Mission Systems\n        description: Implementing the seven DoD Zero Trust pillars and 152 capabilities.\n      - name: Critical Infrastructure\n        description: Applying Zero Trust\
  \ to OT and ICS environments in energy, water, and transportation.\n      - name: Healthcare Data Protection\n        description: Protecting PHI under HIPAA using Zero Trust controls and continuous verification.\n      - name: Financial Services Compliance\n        description: Aligning Zero Trust with SOX, GLBA, and PCI-DSS requirements.\n      - name: Higher Education Research\n        description: Securing distributed research networks and BYOD environments.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zero-trust-security-model/refs/heads/main/apis.yml
tags:
- Access Control
- Cybersecurity
- Federal
- Identity Management
- Network Security
- NIST
- Security
- Security Framework
- Zero Trust
url: https://www.nist.gov/publications/zero-trust-architecture
use_cases:
- description: Meeting OMB M-22-09 and CISA Zero Trust Maturity Model requirements.
  name: Federal Civilian Compliance
- description: Implementing the seven DoD Zero Trust pillars and 152 capabilities.
  name: DoD Mission Systems
- description: Applying Zero Trust to OT and ICS environments in energy, water, and transportation.
  name: Critical Infrastructure
- description: Protecting PHI under HIPAA using Zero Trust controls and continuous verification.
  name: Healthcare Data Protection
- description: Aligning Zero Trust with SOX, GLBA, and PCI-DSS requirements.
  name: Financial Services Compliance
- description: Securing distributed research networks and BYOD environments.
  name: Higher Education Research
---
