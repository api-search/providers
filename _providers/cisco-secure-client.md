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
tags:
- Endpoint Security
- Remote Access
- Security
- VPN
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/cisco-secure-client/refs/heads/main/apis.yml
use_cases: []
---
