---
api_count: 5
apis:
- description: The Cisco Secure Firewall Management Center API configures remote-access VPN gateways, group policies, and Secure Client profiles distributed to endpoints. Authentication uses a token generated via th
  name: Cisco Secure Firewall Management Center API
  slug: secure-firewall-management-api
- description: The Cisco Identity Services Engine External RESTful Services (ERS) API manages the network access control plane that Secure Client integrates with for posture assessment and policy enforcement. Endpoi
  name: Cisco ISE ERS API
  slug: ise-ers-api
- description: 'The Cisco Umbrella API exposes the cloud-delivered DNS, secure web gateway, and roaming protection services that integrate with the Secure Client Umbrella module. Authentication uses OAuth 2.0 client '
  name: Cisco Umbrella API
  slug: umbrella-api
- description: The Duo Admin API configures multi-factor authentication policies, users, groups, and integrations used by Secure Client deployments for ZTNA and adaptive authentication. Authentication uses an HMAC s
  name: Cisco Duo Admin API
  slug: duo-admin-api
- description: The Cisco Secure Access API is the management interface for Cisco's converged SSE platform that Secure Client connects to as a SASE endpoint agent. Endpoints cover network tunnels, ZTNA application de
  name: Cisco Secure Access API
  slug: secure-access-api
capabilities: []
common:
- title: ''
  type: Portal
  url: https://developer.cisco.com/
- title: ''
  type: Documentation
  url: https://www.cisco.com/c/en/us/support/security/secure-client-5/series.html
- title: ''
  type: Getting Started
  url: https://developer.cisco.com/docs/secure-client/getting-started/
- title: ''
  type: Change Log
  url: https://www.cisco.com/c/en/us/td/docs/security/vpn_client/anyconnect/Cisco-Secure-Client-5/release/notes/release-notes-cisco-secure-client-5.html
- title: ''
  type: Support
  url: https://www.cisco.com/c/en/us/support/index.html
- title: ''
  type: Status
  url: https://status.cisco.com/
- title: ''
  type: Community
  url: https://community.cisco.com/
- title: ''
  type: Terms of Service
  url: https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end-user-license-agreement.html
- title: ''
  type: Privacy Policy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: JSON-LD
  url: json-ld/cisco-secure-client-context.jsonld
- title: ''
  type: Spectral
  url: rules/cisco-secure-client-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/cisco-secure-client-capabilities.yml
created: '2024-01-01'
description: Cisco Secure Client (formerly AnyConnect) is the unified endpoint agent for Cisco security and connectivity, delivering VPN, Zero Trust Network Access, endpoint posture, network visibility, and secure web access from a single installer. Programmatic interfaces are exposed indirectly through Cisco Secure Firewall (ASA, FTD), Cisco Identity Services Engine (ISE), Cisco Secure Access, Umbrella, and Duo. There is no single public REST surface for the client itself; integration is achieved through profile XML packages, MDM-deployed configuration, and the management plane APIs exposed by these adjacent Cisco services.
features: []
image: ''
integrations: []
jsonld:
- class_count: 18
  name: Cisco Secure Client Context
  property_count: 0
  slug: cisco-secure-client-context
layout: provider
modified: '2026-04-23'
name: Cisco Secure Client
rules:
- name: Cisco Secure Client API Rules
  rule_count: 5
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 2
  slug: cisco-secure-client-rules
skills: []
slug: cisco-secure-client
solutions: []
source_yaml: "aid: cisco-secure-client\nname: Cisco Secure Client\nurl: https://raw.githubusercontent.com/api-evangelist/cisco-secure-client/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion: '0.19'\ntags:\n  - Endpoint Security\n  - Remote Access\n  - Security\n  - VPN\n  - Zero Trust\ndescription: >-\n  Cisco Secure Client (formerly AnyConnect) is the unified endpoint agent for\n  Cisco security and connectivity, delivering VPN, Zero Trust Network Access,\n  endpoint posture, network visibility, and secure web access from a single\n  installer. Programmatic interfaces are exposed indirectly through Cisco\n  Secure Firewall (ASA, FTD), Cisco Identity Services Engine (ISE), Cisco\n  Secure Access, Umbrella, and Duo. There is no single public REST surface\n  for the client itself; integration is achieved through profile XML\n  packages, MDM-deployed configuration, and the management plane APIs\n\
  \  exposed by these adjacent Cisco services.\napis:\n  - aid: cisco-secure-client:secure-firewall-management-api\n    name: Cisco Secure Firewall Management Center API\n    tags:\n      - ASA\n      - Firewall\n      - FTD\n      - Management\n      - VPN\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.cisco.com/docs/secure-firewall-management-center-api/\n    properties:\n      - url: https://developer.cisco.com/docs/secure-firewall-management-center-api/\n        type: Documentation\n    description: >-\n      The Cisco Secure Firewall Management Center API configures\n      remote-access VPN gateways, group policies, and Secure Client\n      profiles distributed to endpoints. Authentication uses a token\n      generated via the generatetoken endpoint and passed as the\n      X-auth-access-token header on subsequent calls.\n  - aid: cisco-secure-client:ise-ers-api\n    name: Cisco ISE ERS API\n    tags:\n      -\
  \ ERS\n      - Identity\n      - ISE\n      - NAC\n      - Posture\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.cisco.com/docs/identity-services-engine/\n    properties:\n      - url: https://developer.cisco.com/docs/identity-services-engine/\n        type: Documentation\n    description: >-\n      The Cisco Identity Services Engine External RESTful Services (ERS)\n      API manages the network access control plane that Secure Client\n      integrates with for posture assessment and policy enforcement.\n      Endpoints cover endpoint identity groups, posture conditions, and\n      authorization policies.\n  - aid: cisco-secure-client:umbrella-api\n    name: Cisco Umbrella API\n    tags:\n      - DNS\n      - Roaming\n      - Secure Web Gateway\n      - Umbrella\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.umbrella.com\n    humanURL: https://developer.cisco.com/docs/cloud-security/\n\
  \    properties:\n      - url: https://developer.cisco.com/docs/cloud-security/\n        type: Documentation\n    description: >-\n      The Cisco Umbrella API exposes the cloud-delivered DNS, secure web\n      gateway, and roaming protection services that integrate with the\n      Secure Client Umbrella module. Authentication uses OAuth 2.0 client\n      credentials and endpoints cover deployments, policies, reports, and\n      destination lists.\n  - aid: cisco-secure-client:duo-admin-api\n    name: Cisco Duo Admin API\n    tags:\n      - Authentication\n      - Duo\n      - MFA\n      - Zero Trust\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://duo.com/docs/adminapi\n    properties:\n      - url: https://duo.com/docs/adminapi\n        type: Documentation\n    description: >-\n      The Duo Admin API configures multi-factor authentication policies,\n      users, groups, and integrations used by Secure Client deployments\n\
  \      for ZTNA and adaptive authentication. Authentication uses an HMAC\n      signature scheme over the request and integration keys.\n  - aid: cisco-secure-client:secure-access-api\n    name: Cisco Secure Access API\n    tags:\n      - SASE\n      - Secure Access\n      - SSE\n      - ZTNA\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.cisco.com/docs/cloud-security/secure-access/\n    properties:\n      - url: https://developer.cisco.com/docs/cloud-security/secure-access/\n        type: Documentation\n    description: >-\n      The Cisco Secure Access API is the management interface for Cisco's\n      converged SSE platform that Secure Client connects to as a SASE\n      endpoint agent. Endpoints cover network tunnels, ZTNA application\n      definitions, posture profiles, and reporting.\ncommon:\n  - type: Portal\n    url: https://developer.cisco.com/\n  - type: Documentation\n    url: https://www.cisco.com/c/en/us/support/security/secure-client-5/series.html\n\
  \  - type: Getting Started\n    url: https://developer.cisco.com/docs/secure-client/getting-started/\n  - type: Change Log\n    url: https://www.cisco.com/c/en/us/td/docs/security/vpn_client/anyconnect/Cisco-Secure-Client-5/release/notes/release-notes-cisco-secure-client-5.html\n  - type: Support\n    url: https://www.cisco.com/c/en/us/support/index.html\n  - type: Status\n    url: https://status.cisco.com/\n  - type: Community\n    url: https://community.cisco.com/\n  - type: Terms of Service\n    url: https://www.cisco.com/c/en/us/about/legal/cloud-and-software/end-user-license-agreement.html\n  - type: Privacy Policy\n    url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html\n  - type: JSON-LD\n    url: json-ld/cisco-secure-client-context.jsonld\n  - type: Spectral\n    url: rules/cisco-secure-client-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/cisco-secure-client-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco-secure-client/refs/heads/main/apis.yml
tags:
- Endpoint Security
- Remote Access
- Security
- VPN
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/cisco-secure-client/refs/heads/main/apis.yml
use_cases: []
---
