---
api_count: 9
apis:
- description: The foundational US specification of Zero Trust, defining the seven tenets, PDP/PEP/PA components, and three deployment variants (enhanced identity governance, microsegmentation, network infrastructur
  name: NIST SP 800-207 Zero Trust Architecture
  slug: nist-sp-800-207
- description: The federal-civilian Zero Trust roadmap from CISA, with four maturity levels across the Identity, Devices, Networks, Applications & Workloads, and Data pillars plus cross-cutting capabilities for Visi
  name: CISA Zero Trust Maturity Model v2
  slug: cisa-ztmm
- description: The Department of Defense seven-pillar Zero Trust reference architecture and 152-capability target/advanced execution roadmap.
  name: DoD Zero Trust Reference Architecture
  slug: dod-zt-ra
- description: Cloudflare's Zero Trust platform combining ZTNA, SWG, CASB, RBI, DLP and an REST API for managing all of it.
  name: Cloudflare Zero Trust API
  slug: cloudflare-zero-trust
- description: Zscaler's combined ZIA (internet access) and ZPA (private access) Zero Trust platform with REST APIs for both.
  name: Zscaler Zero Trust Exchange API
  slug: zscaler-zia-zpa
- description: Microsoft Entra (formerly Azure AD), Conditional Access, Defender for Cloud Apps, and Microsoft Intune together implement Zero Trust on the Microsoft platform; Microsoft Graph exposes a unified REST s
  name: Microsoft Entra Zero Trust APIs
  slug: microsoft-entra
- description: Google's productized Zero Trust platform building on the original BeyondCorp research; provides context-aware access through Identity-Aware Proxy and Chrome Enterprise.
  name: Google BeyondCorp Enterprise
  slug: google-beyondcorp
- description: CNCF-graduated workload identity standard (SPIFFE) and reference runtime (SPIRE) used as the workload-identity foundation in Zero Trust deployments.
  name: SPIFFE / SPIRE
  slug: spiffe-spire
- description: CNCF-graduated general-purpose policy engine commonly deployed as the PDP in Zero Trust implementations.
  name: Open Policy Agent (OPA)
  slug: open-policy-agent
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
- title: CISA Zero Trust Maturity Model v2
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
- title: UK NCSC Zero Trust Architecture
  type: Documentation
  url: https://www.ncsc.gov.uk/collection/zero-trust-architecture
- title: Cloudflare Zero Trust
  type: Portal
  url: https://www.cloudflare.com/zero-trust/
- title: Zscaler Zero Trust Exchange
  type: Portal
  url: https://www.zscaler.com/products-and-solutions/zero-trust-exchange
- title: Netskope SASE
  type: Portal
  url: https://www.netskope.com/platform/sase
- title: Palo Alto Networks Prisma Access
  type: Portal
  url: https://www.paloaltonetworks.com/sase/access
- title: Microsoft Zero Trust Guidance Center
  type: Portal
  url: https://learn.microsoft.com/en-us/security/zero-trust/
- title: Google BeyondCorp
  type: Portal
  url: https://cloud.google.com/beyondcorp
- title: Tailscale
  type: Portal
  url: https://tailscale.com/
- title: Twingate
  type: Portal
  url: https://www.twingate.com/
- title: SPIFFE
  type: GitHubOrganization
  url: https://github.com/spiffe
- title: Open Policy Agent
  type: GitHubOrganization
  url: https://github.com/open-policy-agent
- title: Sister Topic - Zero Trust Architecture
  type: Resources
  url: https://github.com/api-evangelist/zero-trust-architecture
- title: Sister Topic - Zero Trust Network Access
  type: Resources
  url: https://github.com/api-evangelist/zero-trust-network-access
- title: Sister Topic - Zero Trust Security Model
  type: Resources
  url: https://github.com/api-evangelist/zero-trust-security-model
- title: Zero Trust Access Decision Schema
  type: JSONSchema
  url: json-schema/zero-trust-access-decision-schema.json
- title: Zero Trust Subject Schema
  type: JSONSchema
  url: json-schema/zero-trust-subject-schema.json
- title: Zero Trust Access Decision Structure
  type: JSONStructure
  url: json-structure/zero-trust-access-decision-structure.json
- title: Zero Trust JSON-LD Context
  type: JSONLD
  url: json-ld/zero-trust-context.jsonld
- title: Zero Trust Access Decision Example
  type: CodeExamples
  url: examples/zero-trust-access-decision-example.json
- title: Zero Trust Vocabulary
  type: Resources
  url: vocabulary/zero-trust-vocabulary.yaml
created: '2025'
description: Zero Trust is the umbrella cybersecurity strategy that eliminates implicit trust based on network location and requires continuous verification of every user, device, workload, and access request. This index aggregates the core specifications (NIST, CISA, DoD, NSA, NCSC), the leading vendor platforms that implement Zero Trust (Cloudflare, Zscaler, Netskope, Palo Alto Networks, Tailscale, Twingate, Microsoft, Google), and the CNCF-graduated open standards that the ecosystem depends on (SPIFFE, SPIRE, OPA). Three sister API Evangelist topics cover Zero Trust Architecture, Zero Trust Network Access (ZTNA), and the Zero Trust Security Model in greater depth.
features:
- description: Authenticate every user and workload regardless of location.
  name: Identity Verification
- description: Continuously evaluate device posture before and during access.
  name: Device Trust
- description: Grant minimum required permissions per session.
  name: Least Privilege
- description: Limit lateral movement by segmenting workloads and networks.
  name: Microsegmentation
- description: Continuously analyze signals and re-evaluate authorization.
  name: Continuous Monitoring
- description: Use mTLS and end-to-end encryption between all components.
  name: Encryption Everywhere
- description: Author and version policy in machine-readable form (Rego, Cedar, JSON).
  name: Policy as Code
- description: Design controls assuming attackers are already inside.
  name: Assume Breach
image: ''
integrations: []
jsonld:
- class_count: 21
  name: Zero Trust Context
  property_count: 0
  slug: zero-trust-context
layout: provider
modified: '2026-05-03'
name: Zero Trust
skills: []
slug: zero-trust
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zero-trust\nname: Zero Trust\ndescription: >-\n  Zero Trust is the umbrella cybersecurity strategy that eliminates implicit\n  trust based on network location and requires continuous verification of\n  every user, device, workload, and access request. This index aggregates\n  the core specifications (NIST, CISA, DoD, NSA, NCSC), the leading vendor\n  platforms that implement Zero Trust (Cloudflare, Zscaler, Netskope,\n  Palo Alto Networks, Tailscale, Twingate, Microsoft, Google), and the\n  CNCF-graduated open standards that the ecosystem depends on (SPIFFE,\n  SPIRE, OPA). Three sister API Evangelist topics cover Zero Trust\n  Architecture, Zero Trust Network Access (ZTNA), and the Zero Trust\n  Security Model in greater depth.\ntype: Index\nurl: https://www.nist.gov/publications/zero-trust-architecture\ntags:\n  - Access Control\n  - Cloud Security\n  - Cybersecurity\n  - Federal\n  - Identity and Access Management\n  - Network Security\n  - Security\n  - Zero Trust\n\
  created: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: zero-trust:nist-sp-800-207\n    name: NIST SP 800-207 Zero Trust Architecture\n    description: >-\n      The foundational US specification of Zero Trust, defining the seven\n      tenets, PDP/PEP/PA components, and three deployment variants (enhanced\n      identity governance, microsegmentation, network infrastructure / SDP).\n    humanURL: https://csrc.nist.gov/pubs/sp/800/207/final\n    tags: [NIST, Specification]\n    properties:\n      - type: Documentation\n        url: https://csrc.nist.gov/pubs/sp/800/207/final\n      - type: APIReference\n        url: https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf\n  - aid: zero-trust:cisa-ztmm\n    name: CISA Zero Trust Maturity Model v2\n    description: >-\n      The federal-civilian Zero Trust roadmap from CISA, with four maturity\n      levels across the Identity, Devices, Networks, Applications &\n      Workloads, and Data pillars\
  \ plus cross-cutting capabilities for\n      Visibility & Analytics, Automation & Orchestration, and Governance.\n    humanURL: https://www.cisa.gov/zero-trust-maturity-model\n    tags: [CISA, Federal, Maturity Model]\n    properties:\n      - type: Documentation\n        url: https://www.cisa.gov/zero-trust-maturity-model\n      - type: APIReference\n        url: https://www.cisa.gov/sites/default/files/2023-04/zero_trust_maturity_model_v2_508.pdf\n  - aid: zero-trust:dod-zt-ra\n    name: DoD Zero Trust Reference Architecture\n    description: >-\n      The Department of Defense seven-pillar Zero Trust reference\n      architecture and 152-capability target/advanced execution roadmap.\n    humanURL: https://dodcio.defense.gov/library/\n    tags: [DoD, Federal, Reference Architecture]\n    properties:\n      - type: Documentation\n        url: https://dodcio.defense.gov/Portals/0/Documents/Library/ZT-Reference-Architecture.pdf\n  - aid: zero-trust:cloudflare-zero-trust\n    name: Cloudflare\
  \ Zero Trust API\n    description: Cloudflare's Zero Trust platform combining ZTNA, SWG, CASB, RBI, DLP and an REST API for managing all of it.\n    humanURL: https://developers.cloudflare.com/cloudflare-one/\n    tags: [Cloudflare, SASE, Vendor, ZTNA]\n    properties:\n      - type: Documentation\n        url: https://developers.cloudflare.com/cloudflare-one/\n      - type: APIReference\n        url: https://developers.cloudflare.com/api/\n  - aid: zero-trust:zscaler-zia-zpa\n    name: Zscaler Zero Trust Exchange API\n    description: Zscaler's combined ZIA (internet access) and ZPA (private access) Zero Trust platform with REST APIs for both.\n    humanURL: https://help.zscaler.com/\n    tags: [SASE, Vendor, Zscaler]\n    properties:\n      - type: Documentation\n        url: https://help.zscaler.com/\n      - type: APIReference\n        url: https://help.zscaler.com/zpa/api-reference\n  - aid: zero-trust:microsoft-entra\n    name: Microsoft Entra Zero Trust APIs\n    description: >-\n\
  \      Microsoft Entra (formerly Azure AD), Conditional Access, Defender for\n      Cloud Apps, and Microsoft Intune together implement Zero Trust on the\n      Microsoft platform; Microsoft Graph exposes a unified REST surface.\n    humanURL: https://learn.microsoft.com/en-us/security/zero-trust/\n    tags: [Microsoft, Vendor, IdP]\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/security/zero-trust/\n      - type: APIReference\n        url: https://learn.microsoft.com/en-us/graph/api/overview\n  - aid: zero-trust:google-beyondcorp\n    name: Google BeyondCorp Enterprise\n    description: Google's productized Zero Trust platform building on the original BeyondCorp research; provides context-aware access through Identity-Aware Proxy and Chrome Enterprise.\n    humanURL: https://cloud.google.com/beyondcorp-enterprise\n    tags: [Google, Vendor]\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/beyondcorp-enterprise/docs\n\
  \  - aid: zero-trust:spiffe-spire\n    name: SPIFFE / SPIRE\n    description: CNCF-graduated workload identity standard (SPIFFE) and reference runtime (SPIRE) used as the workload-identity foundation in Zero Trust deployments.\n    humanURL: https://spiffe.io/\n    tags: [CNCF, Open Source, Workload Identity]\n    properties:\n      - type: Documentation\n        url: https://spiffe.io/docs/latest/\n      - type: GitHubOrganization\n        url: https://github.com/spiffe\n  - aid: zero-trust:open-policy-agent\n    name: Open Policy Agent (OPA)\n    description: CNCF-graduated general-purpose policy engine commonly deployed as the PDP in Zero Trust implementations.\n    humanURL: https://www.openpolicyagent.org/\n    tags: [CNCF, Open Source, Policy Engine]\n    properties:\n      - type: Documentation\n        url: https://www.openpolicyagent.org/docs/latest/\n      - type: GitHubOrganization\n        url: https://github.com/open-policy-agent\ncommon:\n  - type: Documentation\n    title:\
  \ NIST Zero Trust Architecture\n    url: https://www.nist.gov/publications/zero-trust-architecture\n  - type: Documentation\n    title: NIST SP 800-207 PDF\n    url: https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf\n  - type: Documentation\n    title: NIST SP 800-207A PDF\n    url: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-207A.pdf\n  - type: Compliance\n    title: CISA Zero Trust Maturity Model v2\n    url: https://www.cisa.gov/zero-trust-maturity-model\n  - type: Compliance\n    title: OMB M-22-09 Federal Zero Trust Strategy\n    url: https://www.whitehouse.gov/wp-content/uploads/2022/01/M-22-09.pdf\n  - type: Compliance\n    title: DoD Zero Trust Reference Architecture\n    url: https://dodcio.defense.gov/Portals/0/Documents/Library/ZT-Reference-Architecture.pdf\n  - type: Documentation\n    title: NSA Zero Trust Guidance\n    url: https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2899282/nsa-releases-guidance-on-zero-trust-security-model/\n\
  \  - type: Documentation\n    title: UK NCSC Zero Trust Architecture\n    url: https://www.ncsc.gov.uk/collection/zero-trust-architecture\n  - type: Portal\n    title: Cloudflare Zero Trust\n    url: https://www.cloudflare.com/zero-trust/\n  - type: Portal\n    title: Zscaler Zero Trust Exchange\n    url: https://www.zscaler.com/products-and-solutions/zero-trust-exchange\n  - type: Portal\n    title: Netskope SASE\n    url: https://www.netskope.com/platform/sase\n  - type: Portal\n    title: Palo Alto Networks Prisma Access\n    url: https://www.paloaltonetworks.com/sase/access\n  - type: Portal\n    title: Microsoft Zero Trust Guidance Center\n    url: https://learn.microsoft.com/en-us/security/zero-trust/\n  - type: Portal\n    title: Google BeyondCorp\n    url: https://cloud.google.com/beyondcorp\n  - type: Portal\n    title: Tailscale\n    url: https://tailscale.com/\n  - type: Portal\n    title: Twingate\n    url: https://www.twingate.com/\n  - type: GitHubOrganization\n    title:\
  \ SPIFFE\n    url: https://github.com/spiffe\n  - type: GitHubOrganization\n    title: Open Policy Agent\n    url: https://github.com/open-policy-agent\n  - type: Resources\n    title: Sister Topic - Zero Trust Architecture\n    url: https://github.com/api-evangelist/zero-trust-architecture\n  - type: Resources\n    title: Sister Topic - Zero Trust Network Access\n    url: https://github.com/api-evangelist/zero-trust-network-access\n  - type: Resources\n    title: Sister Topic - Zero Trust Security Model\n    url: https://github.com/api-evangelist/zero-trust-security-model\n  - type: JSONSchema\n    title: Zero Trust Access Decision Schema\n    url: json-schema/zero-trust-access-decision-schema.json\n  - type: JSONSchema\n    title: Zero Trust Subject Schema\n    url: json-schema/zero-trust-subject-schema.json\n  - type: JSONStructure\n    title: Zero Trust Access Decision Structure\n    url: json-structure/zero-trust-access-decision-structure.json\n  - type: JSONLD\n    title: Zero Trust\
  \ JSON-LD Context\n    url: json-ld/zero-trust-context.jsonld\n  - type: CodeExamples\n    title: Zero Trust Access Decision Example\n    url: examples/zero-trust-access-decision-example.json\n  - type: Resources\n    title: Zero Trust Vocabulary\n    url: vocabulary/zero-trust-vocabulary.yaml\n  - type: Features\n    data:\n      - name: Identity Verification\n        description: Authenticate every user and workload regardless of location.\n      - name: Device Trust\n        description: Continuously evaluate device posture before and during access.\n      - name: Least Privilege\n        description: Grant minimum required permissions per session.\n      - name: Microsegmentation\n        description: Limit lateral movement by segmenting workloads and networks.\n      - name: Continuous Monitoring\n        description: Continuously analyze signals and re-evaluate authorization.\n      - name: Encryption Everywhere\n        description: Use mTLS and end-to-end encryption between all\
  \ components.\n      - name: Policy as Code\n        description: Author and version policy in machine-readable form (Rego, Cedar, JSON).\n      - name: Assume Breach\n        description: Design controls assuming attackers are already inside.\n  - type: UseCases\n    data:\n      - name: VPN Modernization\n        description: Replace flat-network VPNs with brokered, identity-aware access.\n      - name: Federal Compliance\n        description: Meet OMB M-22-09 Zero Trust mandate and CISA ZTMM milestones.\n      - name: DoD Mission Adoption\n        description: Implement the seven DoD Zero Trust pillars and 152 capabilities.\n      - name: Multi-Cloud Workload Security\n        description: Apply consistent Zero Trust controls across AWS, Azure, GCP.\n      - name: Critical Infrastructure\n        description: Apply Zero Trust to OT/ICS environments under TSA, NERC, and ENISA guidance.\n      - name: Healthcare and Financial Compliance\n        description: Align Zero Trust with HIPAA,\
  \ GLBA, PCI-DSS, and SOX requirements.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zero-trust/refs/heads/main/apis.yml
tags:
- Access Control
- Cloud Security
- Cybersecurity
- Federal
- Identity and Access Management
- Network Security
- Security
- Zero Trust
url: https://www.nist.gov/publications/zero-trust-architecture
use_cases:
- description: Replace flat-network VPNs with brokered, identity-aware access.
  name: VPN Modernization
- description: Meet OMB M-22-09 Zero Trust mandate and CISA ZTMM milestones.
  name: Federal Compliance
- description: Implement the seven DoD Zero Trust pillars and 152 capabilities.
  name: DoD Mission Adoption
- description: Apply consistent Zero Trust controls across AWS, Azure, GCP.
  name: Multi-Cloud Workload Security
- description: Apply Zero Trust to OT/ICS environments under TSA, NERC, and ENISA guidance.
  name: Critical Infrastructure
- description: Align Zero Trust with HIPAA, GLBA, PCI-DSS, and SOX requirements.
  name: Healthcare and Financial Compliance
---
