---
api_count: 6
apis:
- description: 'Cloudflare Zero Trust (formerly Cloudflare for Teams / Cloudflare Access) provides ZTNA, secure web gateway, browser isolation, CASB, and DLP through a single global edge platform. The Cloudflare API '
  name: Cloudflare Zero Trust API
  slug: cloudflare-zero-trust
- description: 'Zscaler Private Access is a cloud-native ZTNA service that connects authenticated users to private applications without exposing them to the internet or placing them on the corporate network. The ZPA '
  name: Zscaler Private Access (ZPA) API
  slug: zscaler-zpa
- description: Netskope Private Access provides ZTNA as part of the Netskope SASE platform, brokering authenticated access to private applications across cloud and on-premises. The Netskope REST API surfaces operati
  name: Netskope Private Access API
  slug: netskope-private-access
- description: Palo Alto Networks Prisma Access offers cloud-delivered ZTNA, SWG, and FWaaS as part of the Prisma SASE platform. The Prisma Access REST API exposes operations on remote networks, mobile users, securi
  name: Palo Alto Prisma Access (Prisma SASE) API
  slug: palo-alto-prisma-access
- description: Tailscale is a WireGuard-based mesh-VPN ZTNA platform that exposes a REST API for managing devices, ACL policies, tailnet keys, DNS, and audit logs. It implements identity-based device-to-device tunne
  name: Tailscale API
  slug: tailscale-api
- description: Twingate is a software-defined ZTNA platform that exposes a GraphQL Admin API for managing remote networks, resources, groups, users, service accounts, and connectors.
  name: Twingate API
  slug: twingate-api
common:
- title: Cloudflare - What Is Zero Trust
  type: Documentation
  url: https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/
- title: Gartner Definition of ZTNA
  type: Documentation
  url: https://www.gartner.com/en/information-technology/glossary/zero-trust-network-access-ztna-
- title: NIST SP 800-207 (ZTA underpinnings of ZTNA)
  type: Documentation
  url: https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf
- title: CISA Zero Trust Maturity Model
  type: Compliance
  url: https://www.cisa.gov/zero-trust-maturity-model
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
- title: Tailscale
  type: Portal
  url: https://tailscale.com/
- title: Twingate
  type: Portal
  url: https://www.twingate.com/
- title: Tailscale on GitHub
  type: GitHubOrganization
  url: https://github.com/tailscale
- title: WireGuard
  type: GitHubOrganization
  url: https://github.com/WireGuard
- title: ZTNA Access Policy Schema
  type: JSONSchema
  url: json-schema/zero-trust-network-access-policy-schema.json
- title: ZTNA Application Schema
  type: JSONSchema
  url: json-schema/zero-trust-network-access-application-schema.json
- title: ZTNA Device Posture Schema
  type: JSONSchema
  url: json-schema/zero-trust-network-access-device-posture-schema.json
- title: ZTNA Access Policy Structure
  type: JSONStructure
  url: json-structure/zero-trust-network-access-policy-structure.json
- title: ZTNA JSON-LD Context
  type: JSONLD
  url: json-ld/zero-trust-network-access-context.jsonld
- title: ZTNA Access Policy Example
  type: CodeExamples
  url: examples/zero-trust-network-access-policy-example.json
- title: ZTNA Device Posture Example
  type: CodeExamples
  url: examples/zero-trust-network-access-device-posture-example.json
- title: ZTNA Vocabulary
  type: Resources
  url: vocabulary/zero-trust-network-access-vocabulary.yaml
created: '2025'
description: Zero Trust Network Access (ZTNA) is a security framework and product category that grants access to private applications and resources based on identity, device posture, and context, rather than network location. ZTNA replaces the implicit trust of legacy VPNs with explicit per-request verification, creating one-to-one encrypted tunnels between authenticated users and the specific applications they are authorized to use. This topic collects the leading ZTNA vendors, the standards bodies that govern the underlying primitives, and the data schemas used to describe access policies, identities, devices, and resources.
features:
- description: Access decisions are based on user and workload identity rather than network location.
  name: Identity-Centric Access
- description: One-to-one encrypted connections between authenticated users and specific applications.
  name: Application-Level Tunnels
- description: Continuous evaluation of device health, OS patch level, EDR status, and certificate state.
  name: Device Posture Checks
- description: Policies factor in time, location, risk score, and behavior in addition to identity.
  name: Context-Aware Policy
- description: Private applications are dark to the public internet and not advertised by IP or DNS.
  name: Application Cloaking
- description: Native integration with SAML, OIDC, and modern MFA providers.
  name: SSO and MFA Integration
- description: Lateral movement is prevented by issuing scoped, per-application access.
  name: Microsegmentation
- description: Sessions are reauthenticated and reauthorized as conditions change.
  name: Continuous Authorization
image: ''
integrations:
- description: Enterprise identity provider used by virtually all ZTNA platforms.
  name: Okta
- description: Cloud identity platform integrated as IdP for ZTNA brokers.
  name: Microsoft Entra ID
- description: EDR signals fed into ZTNA device-posture rules.
  name: CrowdStrike Falcon
- description: EDR signals fed into ZTNA device-posture rules.
  name: SentinelOne
- description: macOS / iOS MDM signals integrated into device posture for ZTNA.
  name: Jamf
- description: Microsoft Endpoint Manager signals integrated into device posture for ZTNA.
  name: Intune
- description: SIEM destination for ZTNA access and audit logs.
  name: Splunk
- description: ITSM workflow integration for granting and revoking ZTNA access.
  name: ServiceNow
jsonld:
- class_count: 24
  name: Zero Trust Network Access Context
  property_count: 0
  slug: zero-trust-network-access-context
layout: provider
modified: '2026-05-03'
name: Zero Trust Network Access
skills: []
slug: zero-trust-network-access
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: zero-trust-network-access\nname: Zero Trust Network Access\ndescription: >-\n  Zero Trust Network Access (ZTNA) is a security framework and product\n  category that grants access to private applications and resources based on\n  identity, device posture, and context, rather than network location. ZTNA\n  replaces the implicit trust of legacy VPNs with explicit per-request\n  verification, creating one-to-one encrypted tunnels between authenticated\n  users and the specific applications they are authorized to use. This topic\n  collects the leading ZTNA vendors, the standards bodies that govern the\n  underlying primitives, and the data schemas used to describe access\n  policies, identities, devices, and resources.\ntype: Index\nurl: https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/\ntags:\n  - Access Control\n  - Cloud Security\n  - Cybersecurity\n  - Identity Management\n  - Network Access\n  - Network Security\n  - Security\n  - VPN Replacement\n\
  \  - Zero Trust\n  - ZTNA\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: zero-trust-network-access:cloudflare-zero-trust\n    name: Cloudflare Zero Trust API\n    description: >-\n      Cloudflare Zero Trust (formerly Cloudflare for Teams / Cloudflare\n      Access) provides ZTNA, secure web gateway, browser isolation, CASB,\n      and DLP through a single global edge platform. The Cloudflare API\n      exposes endpoints for managing Access applications, policies, identity\n      providers, device posture, tunnels, and gateway rules.\n    humanURL: https://developers.cloudflare.com/cloudflare-one/\n    tags:\n      - Cloudflare\n      - SASE\n      - ZTNA\n    properties:\n      - type: Documentation\n        url: https://developers.cloudflare.com/cloudflare-one/\n      - type: APIReference\n        url: https://developers.cloudflare.com/api/\n      - type: Authentication\n        url: https://developers.cloudflare.com/fundamentals/api/get-started/keys/\n\
  \  - aid: zero-trust-network-access:zscaler-zpa\n    name: Zscaler Private Access (ZPA) API\n    description: >-\n      Zscaler Private Access is a cloud-native ZTNA service that connects\n      authenticated users to private applications without exposing them to\n      the internet or placing them on the corporate network. The ZPA Public\n      API supports application segments, server groups, policies, posture\n      profiles, and connector groups.\n    humanURL: https://help.zscaler.com/zpa/api-reference\n    tags:\n      - SASE\n      - Zscaler\n      - ZTNA\n    properties:\n      - type: Documentation\n        url: https://help.zscaler.com/zpa\n      - type: APIReference\n        url: https://help.zscaler.com/zpa/api-reference\n  - aid: zero-trust-network-access:netskope-private-access\n    name: Netskope Private Access API\n    description: >-\n      Netskope Private Access provides ZTNA as part of the Netskope SASE\n      platform, brokering authenticated access to private applications\
  \ across\n      cloud and on-premises. The Netskope REST API surfaces operations on\n      private apps, publishers, policies, and risk events.\n    humanURL: https://docs.netskope.com/en/netskope-help/admin-console/rest-api/\n    tags:\n      - Netskope\n      - SASE\n      - ZTNA\n    properties:\n      - type: Documentation\n        url: https://docs.netskope.com/en/netskope-help/admin-console/rest-api/\n  - aid: zero-trust-network-access:palo-alto-prisma-access\n    name: Palo Alto Prisma Access (Prisma SASE) API\n    description: >-\n      Palo Alto Networks Prisma Access offers cloud-delivered ZTNA, SWG, and\n      FWaaS as part of the Prisma SASE platform. The Prisma Access REST API\n      exposes operations on remote networks, mobile users, security policies,\n      and decryption rules.\n    humanURL: https://docs.paloaltonetworks.com/prisma/prisma-access\n    tags:\n      - Palo Alto\n      - SASE\n      - ZTNA\n    properties:\n      - type: Documentation\n        url: https://docs.paloaltonetworks.com/prisma/prisma-access\n\
  \  - aid: zero-trust-network-access:tailscale-api\n    name: Tailscale API\n    description: >-\n      Tailscale is a WireGuard-based mesh-VPN ZTNA platform that exposes a\n      REST API for managing devices, ACL policies, tailnet keys, DNS, and\n      audit logs. It implements identity-based device-to-device tunnels\n      brokered by an identity-aware control plane.\n    humanURL: https://tailscale.com/api\n    tags:\n      - Mesh VPN\n      - Tailscale\n      - WireGuard\n      - ZTNA\n    properties:\n      - type: Documentation\n        url: https://tailscale.com/api\n      - type: APIReference\n        url: https://tailscale.com/api\n      - type: GitHubOrganization\n        url: https://github.com/tailscale\n  - aid: zero-trust-network-access:twingate-api\n    name: Twingate API\n    description: >-\n      Twingate is a software-defined ZTNA platform that exposes a GraphQL\n      Admin API for managing remote networks, resources, groups, users,\n      service accounts, and connectors.\n\
  \    humanURL: https://www.twingate.com/docs/api\n    tags:\n      - Twingate\n      - ZTNA\n    properties:\n      - type: Documentation\n        url: https://www.twingate.com/docs/api\n      - type: APIReference\n        url: https://www.twingate.com/docs/api\ncommon:\n  - type: Documentation\n    title: Cloudflare - What Is Zero Trust\n    url: https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/\n    description: Cloudflare's reference explainer on Zero Trust security and ZTNA.\n  - type: Documentation\n    title: Gartner Definition of ZTNA\n    url: https://www.gartner.com/en/information-technology/glossary/zero-trust-network-access-ztna-\n    description: Gartner glossary entry defining ZTNA as a market category.\n  - type: Documentation\n    title: NIST SP 800-207 (ZTA underpinnings of ZTNA)\n    url: https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf\n    description: NIST Special Publication 800-207 - the architectural foundation behind\
  \ ZTNA.\n  - type: Compliance\n    title: CISA Zero Trust Maturity Model\n    url: https://www.cisa.gov/zero-trust-maturity-model\n    description: CISA Zero Trust Maturity Model that ZTNA deployments are commonly aligned to.\n  - type: Portal\n    title: Cloudflare Zero Trust\n    url: https://www.cloudflare.com/zero-trust/\n  - type: Portal\n    title: Zscaler Zero Trust Exchange\n    url: https://www.zscaler.com/products-and-solutions/zero-trust-exchange\n  - type: Portal\n    title: Netskope SASE\n    url: https://www.netskope.com/platform/sase\n  - type: Portal\n    title: Palo Alto Networks Prisma Access\n    url: https://www.paloaltonetworks.com/sase/access\n  - type: Portal\n    title: Tailscale\n    url: https://tailscale.com/\n  - type: Portal\n    title: Twingate\n    url: https://www.twingate.com/\n  - type: GitHubOrganization\n    title: Tailscale on GitHub\n    url: https://github.com/tailscale\n  - type: GitHubOrganization\n    title: WireGuard\n    url: https://github.com/WireGuard\n\
  \  - type: JSONSchema\n    title: ZTNA Access Policy Schema\n    url: json-schema/zero-trust-network-access-policy-schema.json\n  - type: JSONSchema\n    title: ZTNA Application Schema\n    url: json-schema/zero-trust-network-access-application-schema.json\n  - type: JSONSchema\n    title: ZTNA Device Posture Schema\n    url: json-schema/zero-trust-network-access-device-posture-schema.json\n  - type: JSONStructure\n    title: ZTNA Access Policy Structure\n    url: json-structure/zero-trust-network-access-policy-structure.json\n  - type: JSONLD\n    title: ZTNA JSON-LD Context\n    url: json-ld/zero-trust-network-access-context.jsonld\n  - type: CodeExamples\n    title: ZTNA Access Policy Example\n    url: examples/zero-trust-network-access-policy-example.json\n  - type: CodeExamples\n    title: ZTNA Device Posture Example\n    url: examples/zero-trust-network-access-device-posture-example.json\n  - type: Resources\n    title: ZTNA Vocabulary\n    url: vocabulary/zero-trust-network-access-vocabulary.yaml\n\
  \  - type: Features\n    data:\n      - name: Identity-Centric Access\n        description: Access decisions are based on user and workload identity rather than network location.\n      - name: Application-Level Tunnels\n        description: One-to-one encrypted connections between authenticated users and specific applications.\n      - name: Device Posture Checks\n        description: Continuous evaluation of device health, OS patch level, EDR status, and certificate state.\n      - name: Context-Aware Policy\n        description: Policies factor in time, location, risk score, and behavior in addition to identity.\n      - name: Application Cloaking\n        description: Private applications are dark to the public internet and not advertised by IP or DNS.\n      - name: SSO and MFA Integration\n        description: Native integration with SAML, OIDC, and modern MFA providers.\n      - name: Microsegmentation\n        description: Lateral movement is prevented by issuing scoped, per-application\
  \ access.\n      - name: Continuous Authorization\n        description: Sessions are reauthenticated and reauthorized as conditions change.\n  - type: UseCases\n    data:\n      - name: VPN Replacement\n        description: Replacing legacy site-to-site and remote-access VPNs with identity-aware brokered access.\n      - name: Third-Party Contractor Access\n        description: Granting time-bounded, application-scoped access to vendors and contractors.\n      - name: M&A Network Integration\n        description: Enabling acquired companies to reach internal applications without merging networks.\n      - name: BYOD Access\n        description: Allowing personal and unmanaged devices to access selected applications under posture rules.\n      - name: Privileged Access\n        description: Brokering jump-host and bastion access to sensitive infrastructure.\n      - name: Multi-Cloud Application Access\n        description: Providing consistent ZTNA across applications hosted in AWS, Azure,\
  \ GCP, and on-premises.\n  - type: Integrations\n    data:\n      - name: Okta\n        description: Enterprise identity provider used by virtually all ZTNA platforms.\n      - name: Microsoft Entra ID\n        description: Cloud identity platform integrated as IdP for ZTNA brokers.\n      - name: CrowdStrike Falcon\n        description: EDR signals fed into ZTNA device-posture rules.\n      - name: SentinelOne\n        description: EDR signals fed into ZTNA device-posture rules.\n      - name: Jamf\n        description: macOS / iOS MDM signals integrated into device posture for ZTNA.\n      - name: Intune\n        description: Microsoft Endpoint Manager signals integrated into device posture for ZTNA.\n      - name: Splunk\n        description: SIEM destination for ZTNA access and audit logs.\n      - name: ServiceNow\n        description: ITSM workflow integration for granting and revoking ZTNA access.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/zero-trust-network-access/refs/heads/main/apis.yml
tags:
- Access Control
- Cloud Security
- Cybersecurity
- Identity Management
- Network Access
- Network Security
- Security
- VPN Replacement
- Zero Trust
- ZTNA
url: https://www.cloudflare.com/learning/security/glossary/what-is-zero-trust/
use_cases:
- description: Replacing legacy site-to-site and remote-access VPNs with identity-aware brokered access.
  name: VPN Replacement
- description: Granting time-bounded, application-scoped access to vendors and contractors.
  name: Third-Party Contractor Access
- description: Enabling acquired companies to reach internal applications without merging networks.
  name: M&A Network Integration
- description: Allowing personal and unmanaged devices to access selected applications under posture rules.
  name: BYOD Access
- description: Brokering jump-host and bastion access to sensitive infrastructure.
  name: Privileged Access
- description: Providing consistent ZTNA across applications hosted in AWS, Azure, GCP, and on-premises.
  name: Multi-Cloud Application Access
---
