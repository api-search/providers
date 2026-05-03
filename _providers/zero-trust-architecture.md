---
api_count: 5
apis:
- description: NIST Special Publication 800-207 defines zero trust architecture (ZTA) and provides a roadmap for organizations migrating to ZTA. It describes seven ZTA tenets, three logical components (Policy Decisi
  name: NIST SP 800-207 Zero Trust Architecture
  slug: nist-sp-800-207
- description: NIST SP 800-207A extends the original ZTA guidance to cover cloud-native applications in multi-cloud environments. It addresses service mesh architectures, workload identity, microsegmentation, and AP
  name: NIST SP 800-207A ZTA for Cloud-Native Applications
  slug: nist-sp-800-207a
- description: SPIFFE is a CNCF-graduated open standard for workload identity in dynamic environments. It provides a framework for workloads to authenticate to each other using short-lived cryptographic SVIDs (SPIFF
  name: SPIFFE - Secure Production Identity Framework for Everyone
  slug: spiffe
- description: 'SPIRE is the reference implementation of SPIFFE, a CNCF-graduated production-ready toolchain for establishing trust between workloads. It issues SVIDs to workloads and exposes the SPIFFE Workload API '
  name: SPIRE - SPIFFE Runtime Environment
  slug: spire
- description: Open Policy Agent is a CNCF-graduated open source general-purpose policy engine that enables unified, context-aware policy enforcement across APIs, microservices, Kubernetes, and CI/CD pipelines. In Z
  name: Open Policy Agent (OPA)
  slug: open-policy-agent
common:
- title: NIST Zero Trust Architecture
  type: Portal
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
- title: NSA Zero Trust Guidance
  type: Compliance
  url: https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2899282/nsa-releases-guidance-on-zero-trust-security-model/
- title: DoD Zero Trust Reference Architecture
  type: Compliance
  url: https://dodcio.defense.gov/Portals/0/Documents/Library/ZT-Reference-Architecture.pdf
- title: SPIFFE Project
  type: Portal
  url: https://spiffe.io/
- title: Open Policy Agent
  type: Portal
  url: https://www.openpolicyagent.org/
- title: SPIFFE GitHub
  type: GitHubOrganization
  url: https://github.com/spiffe
- title: Open Policy Agent GitHub
  type: GitHubOrganization
  url: https://github.com/open-policy-agent
- title: Zero Trust Policy Schema
  type: JSONSchema
  url: json-schema/zero-trust-architecture-policy-schema.json
- title: Zero Trust Identity Schema
  type: JSONSchema
  url: json-schema/zero-trust-architecture-identity-schema.json
- title: Zero Trust Resource Schema
  type: JSONSchema
  url: json-schema/zero-trust-architecture-resource-schema.json
- title: Zero Trust Architecture JSON-LD Context
  type: JSONLD
  url: json-ld/zero-trust-architecture-context.jsonld
- title: Zero Trust Policy Structure
  type: JSONStructure
  url: json-structure/zero-trust-architecture-policy-structure.json
- title: Zero Trust Identity Structure
  type: JSONStructure
  url: json-structure/zero-trust-architecture-identity-structure.json
- title: Zero Trust Architecture Vocabulary
  type: Resources
  url: vocabulary/zero-trust-architecture-vocabulary.yaml
- title: Zero Trust Policy Example
  type: CodeExamples
  url: examples/zero-trust-architecture-policy-example.json
- title: Zero Trust Identity Example
  type: CodeExamples
  url: examples/zero-trust-architecture-identity-example.json
created: '2025'
description: Zero Trust Architecture (ZTA) is a security framework defined by NIST SP 800-207 that requires all users and devices to be authenticated, authorized, and continuously validated before being granted access to applications and data, regardless of whether they are inside or outside the network perimeter. The architecture is built on the principle of "never trust, always verify," replacing implicit trust with explicit verification for every access request. ZTA leverages APIs, identity providers, policy engines, and continuous monitoring to enforce least-privilege access across enterprise resources.
features:
- description: Every access request requires verification of user and device identity regardless of network location.
  name: Identity Verification
- description: Access is granted with minimum required permissions on a per-session basis.
  name: Least Privilege Access
- description: Networks are divided into small zones to limit lateral movement after breach.
  name: Microsegmentation
- description: All network traffic, user behavior, and device health are continuously monitored and analyzed.
  name: Continuous Monitoring
- description: Centralized policy engine evaluates access requests against defined policies.
  name: Policy Decision Point
- description: Gateway or proxy that enforces access decisions made by the policy engine.
  name: Policy Enforcement Point
- description: Cryptographic identity for workloads and services replacing static credentials.
  name: Workload Identity
- description: Device posture and compliance are verified before granting access.
  name: Device Health Attestation
- description: No user, device, or network is trusted implicitly, even inside the corporate perimeter.
  name: Implicit Trust Elimination
- description: Strong MFA is required as part of identity verification for all access.
  name: Multi-Factor Authentication
image: ''
integrations:
- description: Workload identity standard providing SVIDs for mutual TLS authentication.
  name: SPIFFE/SPIRE
- description: Policy engine serving as the Policy Decision Point in ZTA implementations.
  name: Open Policy Agent
- description: Service mesh proxy enforcing mTLS and authorization policies as PEP.
  name: Envoy Proxy
- description: Kubernetes service mesh providing ZTA controls through SPIFFE and OPA integration.
  name: Istio
- description: Secrets management platform providing dynamic credentials in ZTA pipelines.
  name: HashiCorp Vault
- description: Identity provider for user and device authentication in ZTA implementations.
  name: Okta
- description: Cloud identity platform used as Identity Provider in enterprise ZTA deployments.
  name: Microsoft Entra ID
- description: Google's ZTA implementation providing context-aware access for enterprise applications.
  name: BeyondCorp Enterprise
- description: Zero Trust Network Access and secure web gateway platform.
  name: Cloudflare Zero Trust
- description: Cloud-native ZTNA solution providing ZTA-compliant access to private applications.
  name: Zscaler Private Access
jsonld:
- class_count: 0
  name: Zero Trust Architecture Context
  property_count: 45
  slug: zero-trust-architecture-context
layout: provider
modified: '2026-05-03'
name: Zero Trust Architecture
skills: []
slug: zero-trust-architecture
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zero-trust-architecture\nname: Zero Trust Architecture\ndescription: >-\n  Zero Trust Architecture (ZTA) is a security framework defined by NIST SP 800-207 that\n  requires all users and devices to be authenticated, authorized, and continuously validated\n  before being granted access to applications and data, regardless of whether they are inside\n  or outside the network perimeter. The architecture is built on the principle of \"never\n  trust, always verify,\" replacing implicit trust with explicit verification for every\n  access request. ZTA leverages APIs, identity providers, policy engines, and continuous\n  monitoring to enforce least-privilege access across enterprise resources.\ntype: Index\nurl: https://www.nist.gov/publications/zero-trust-architecture\ntags:\n  - Access Control\n  - Authentication\n  - Authorization\n  - Cybersecurity\n  - Identity Management\n  - Least Privilege\n  - Network Security\n  - NIST\n  - Security\n  - Zero Trust\ncreated: '2025'\n\
  modified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: zero-trust-architecture:nist-sp-800-207\n    name: NIST SP 800-207 Zero Trust Architecture\n    description: >-\n      NIST Special Publication 800-207 defines zero trust architecture (ZTA) and provides\n      a roadmap for organizations migrating to ZTA. It describes seven ZTA tenets, three\n      logical components (Policy Decision Point, Policy Enforcement Point, Policy\n      Administration Point), three approaches to ZTA deployment, and guidance on threat\n      models and use cases. Published August 2020.\n    humanURL: https://csrc.nist.gov/pubs/sp/800/207/final\n    tags:\n      - NIST\n      - Security Framework\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://csrc.nist.gov/pubs/sp/800/207/final\n      - type: Documentation\n        url: https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf\n  - aid: zero-trust-architecture:nist-sp-800-207a\n    name:\
  \ NIST SP 800-207A ZTA for Cloud-Native Applications\n    description: >-\n      NIST SP 800-207A extends the original ZTA guidance to cover cloud-native applications\n      in multi-cloud environments. It addresses service mesh architectures, workload identity,\n      microsegmentation, and API-centric access control patterns for containerized workloads.\n    humanURL: https://csrc.nist.gov/pubs/sp/800/207/a/final\n    tags:\n      - Cloud Security\n      - Kubernetes\n      - NIST\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://csrc.nist.gov/pubs/sp/800/207/a/final\n      - type: Documentation\n        url: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-207A.pdf\n  - aid: zero-trust-architecture:spiffe\n    name: SPIFFE - Secure Production Identity Framework for Everyone\n    description: >-\n      SPIFFE is a CNCF-graduated open standard for workload identity in dynamic environments.\n      It provides a framework for workloads\
  \ to authenticate to each other using short-lived\n      cryptographic SVIDs (SPIFFE Verifiable Identity Documents) without static secrets,\n      forming a foundational element of API-centric Zero Trust implementations.\n    humanURL: https://spiffe.io/\n    tags:\n      - CNCF\n      - Identity\n      - Open Source\n      - Standards\n      - Workload Identity\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://spiffe.io/docs/latest/\n      - type: GitHubOrganization\n        url: https://github.com/spiffe\n  - aid: zero-trust-architecture:spire\n    name: SPIRE - SPIFFE Runtime Environment\n    description: >-\n      SPIRE is the reference implementation of SPIFFE, a CNCF-graduated production-ready\n      toolchain for establishing trust between workloads. It issues SVIDs to workloads\n      and exposes the SPIFFE Workload API for identity attestation across Kubernetes,\n      VMs, cloud instances, and bare metal environments.\n    humanURL: https://spiffe.io/docs/latest/spire-about/spire-concepts/\n\
  \    tags:\n      - CNCF\n      - Identity\n      - Open Source\n      - Runtime\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://spiffe.io/docs/latest/spire-about/\n      - type: GitHubOrganization\n        url: https://github.com/spiffe/spire\n  - aid: zero-trust-architecture:open-policy-agent\n    name: Open Policy Agent (OPA)\n    description: >-\n      Open Policy Agent is a CNCF-graduated open source general-purpose policy engine\n      that enables unified, context-aware policy enforcement across APIs, microservices,\n      Kubernetes, and CI/CD pipelines. In Zero Trust implementations, OPA serves as the\n      Policy Decision Point (PDP) evaluating access requests against defined policies\n      written in the Rego language.\n    humanURL: https://www.openpolicyagent.org/\n    tags:\n      - Authorization\n      - CNCF\n      - Open Source\n      - Policy Engine\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url:\
  \ https://www.openpolicyagent.org/docs/latest/\n      - type: GitHubOrganization\n        url: https://github.com/open-policy-agent\ncommon:\n  - type: Portal\n    title: NIST Zero Trust Architecture\n    url: https://www.nist.gov/publications/zero-trust-architecture\n    description: Official NIST page for Zero Trust Architecture publications and resources.\n  - type: Documentation\n    title: NIST SP 800-207 PDF\n    url: https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf\n    description: Downloadable PDF of NIST Special Publication 800-207 Zero Trust Architecture.\n  - type: Documentation\n    title: NIST SP 800-207A PDF\n    url: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-207A.pdf\n    description: NIST SP 800-207A covering ZTA for cloud-native applications in multi-cloud environments.\n  - type: Compliance\n    title: CISA Zero Trust Maturity Model\n    url: https://www.cisa.gov/zero-trust-maturity-model\n    description: CISA's Zero\
  \ Trust Maturity Model providing a roadmap across five pillars.\n  - type: Compliance\n    title: NSA Zero Trust Guidance\n    url: https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2899282/nsa-releases-guidance-on-zero-trust-security-model/\n    description: NSA guidance on Zero Trust Security Model for network and environment pillar.\n  - type: Compliance\n    title: DoD Zero Trust Reference Architecture\n    url: https://dodcio.defense.gov/Portals/0/Documents/Library/ZT-Reference-Architecture.pdf\n    description: Department of Defense Zero Trust Reference Architecture document.\n  - type: Portal\n    title: SPIFFE Project\n    url: https://spiffe.io/\n    description: Official site for SPIFFE workload identity standard and SPIRE runtime.\n  - type: Portal\n    title: Open Policy Agent\n    url: https://www.openpolicyagent.org/\n    description: Official site for Open Policy Agent (OPA), the CNCF policy engine used as PDP in ZTA.\n  - type: GitHubOrganization\n    title:\
  \ SPIFFE GitHub\n    url: https://github.com/spiffe\n    description: SPIFFE and SPIRE open source repositories on GitHub.\n  - type: GitHubOrganization\n    title: Open Policy Agent GitHub\n    url: https://github.com/open-policy-agent\n    description: Open Policy Agent (OPA) GitHub organization.\n  - type: JSONSchema\n    title: Zero Trust Policy Schema\n    url: json-schema/zero-trust-architecture-policy-schema.json\n  - type: JSONSchema\n    title: Zero Trust Identity Schema\n    url: json-schema/zero-trust-architecture-identity-schema.json\n  - type: JSONSchema\n    title: Zero Trust Resource Schema\n    url: json-schema/zero-trust-architecture-resource-schema.json\n  - type: JSONLD\n    title: Zero Trust Architecture JSON-LD Context\n    url: json-ld/zero-trust-architecture-context.jsonld\n  - type: JSONStructure\n    title: Zero Trust Policy Structure\n    url: json-structure/zero-trust-architecture-policy-structure.json\n  - type: JSONStructure\n    title: Zero Trust Identity\
  \ Structure\n    url: json-structure/zero-trust-architecture-identity-structure.json\n  - type: Resources\n    title: Zero Trust Architecture Vocabulary\n    url: vocabulary/zero-trust-architecture-vocabulary.yaml\n  - type: CodeExamples\n    title: Zero Trust Policy Example\n    url: examples/zero-trust-architecture-policy-example.json\n  - type: CodeExamples\n    title: Zero Trust Identity Example\n    url: examples/zero-trust-architecture-identity-example.json\n  - type: Features\n    data:\n      - name: Identity Verification\n        description: Every access request requires verification of user and device identity regardless of network location.\n      - name: Least Privilege Access\n        description: Access is granted with minimum required permissions on a per-session basis.\n      - name: Microsegmentation\n        description: Networks are divided into small zones to limit lateral movement after breach.\n      - name: Continuous Monitoring\n        description: All network\
  \ traffic, user behavior, and device health are continuously monitored and analyzed.\n      - name: Policy Decision Point\n        description: Centralized policy engine evaluates access requests against defined policies.\n      - name: Policy Enforcement Point\n        description: Gateway or proxy that enforces access decisions made by the policy engine.\n      - name: Workload Identity\n        description: Cryptographic identity for workloads and services replacing static credentials.\n      - name: Device Health Attestation\n        description: Device posture and compliance are verified before granting access.\n      - name: Implicit Trust Elimination\n        description: No user, device, or network is trusted implicitly, even inside the corporate perimeter.\n      - name: Multi-Factor Authentication\n        description: Strong MFA is required as part of identity verification for all access.\n  - type: UseCases\n    data:\n      - name: Remote Workforce Security\n        description:\
  \ Providing secure access to enterprise resources for remote employees without VPN.\n      - name: Cloud Application Access\n        description: Controlling access to multi-cloud and SaaS applications with consistent policies.\n      - name: API Security\n        description: Enforcing zero trust principles at API gateways with per-request authentication and authorization.\n      - name: Kubernetes Workload Identity\n        description: Using SPIFFE/SPIRE to assign cryptographic identities to Kubernetes pods.\n      - name: Supply Chain Security\n        description: Verifying identity and integrity of software components and build pipelines.\n      - name: Government Compliance\n        description: Meeting CISA Zero Trust Maturity Model requirements for federal agencies.\n      - name: Insider Threat Mitigation\n        description: Limiting damage from insider threats through continuous monitoring and least privilege.\n      - name: Multi-Cloud Security\n        description: Applying\
  \ consistent zero trust policies across AWS, Azure, GCP, and private clouds.\n  - type: Integrations\n    data:\n      - name: SPIFFE/SPIRE\n        description: Workload identity standard providing SVIDs for mutual TLS authentication.\n      - name: Open Policy Agent\n        description: Policy engine serving as the Policy Decision Point in ZTA implementations.\n      - name: Envoy Proxy\n        description: Service mesh proxy enforcing mTLS and authorization policies as PEP.\n      - name: Istio\n        description: Kubernetes service mesh providing ZTA controls through SPIFFE and OPA integration.\n      - name: HashiCorp Vault\n        description: Secrets management platform providing dynamic credentials in ZTA pipelines.\n      - name: Okta\n        description: Identity provider for user and device authentication in ZTA implementations.\n      - name: Microsoft Entra ID\n        description: Cloud identity platform used as Identity Provider in enterprise ZTA deployments.\n   \
  \   - name: BeyondCorp Enterprise\n        description: Google's ZTA implementation providing context-aware access for enterprise applications.\n      - name: Cloudflare Zero Trust\n        description: Zero Trust Network Access and secure web gateway platform.\n      - name: Zscaler Private Access\n        description: Cloud-native ZTNA solution providing ZTA-compliant access to private applications.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zero-trust-architecture/refs/heads/main/apis.yml
tags:
- Access Control
- Authentication
- Authorization
- Cybersecurity
- Identity Management
- Least Privilege
- Network Security
- NIST
- Security
- Zero Trust
url: https://www.nist.gov/publications/zero-trust-architecture
use_cases:
- description: Providing secure access to enterprise resources for remote employees without VPN.
  name: Remote Workforce Security
- description: Controlling access to multi-cloud and SaaS applications with consistent policies.
  name: Cloud Application Access
- description: Enforcing zero trust principles at API gateways with per-request authentication and authorization.
  name: API Security
- description: Using SPIFFE/SPIRE to assign cryptographic identities to Kubernetes pods.
  name: Kubernetes Workload Identity
- description: Verifying identity and integrity of software components and build pipelines.
  name: Supply Chain Security
- description: Meeting CISA Zero Trust Maturity Model requirements for federal agencies.
  name: Government Compliance
- description: Limiting damage from insider threats through continuous monitoring and least privilege.
  name: Insider Threat Mitigation
- description: Applying consistent zero trust policies across AWS, Azure, GCP, and private clouds.
  name: Multi-Cloud Security
---
