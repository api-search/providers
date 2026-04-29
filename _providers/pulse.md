---
api_count: 3
apis:
- description: 'REST API for managing Ivanti Connect Secure (formerly Pulse Connect Secure) VPN appliances. Provides endpoints for system configuration, user and role management, authentication server configuration, '
  name: Ivanti Connect Secure REST API
  slug: ivanti-connect-secure-rest-api
- description: REST API for managing Ivanti Policy Secure (formerly Pulse Policy Secure) network access control appliances.
  name: Ivanti Policy Secure REST API
  slug: ivanti-policy-secure-rest-api
- description: REST API for managing Ivanti Neurons for Zero Trust Access (nZTA), providing endpoints for managing zero trust access policies, gateways, and user access.
  name: Ivanti Neurons for Zero Trust Access REST API
  slug: ivanti-neurons-zero-trust-rest-api
common:
- title: ''
  type: Website
  url: https://www.ivanti.com/products/connect-secure-vpn
- title: ''
  type: Documentation
  url: https://www.ivanti.com/support/product-documentation
- title: ''
  type: PrivacyPolicy
  url: https://www.ivanti.com/company/legal/privacy-policy
- title: ''
  type: TermsOfService
  url: https://www.ivanti.com/company/legal
- title: ''
  type: Status
  url: https://status.ivanticloud.com/
- title: ''
  type: Blog
  url: https://www.ivanti.com/blog
- title: ''
  type: Community
  url: https://forums.ivanti.com/s/welcome-pulse-secure?language=en_US
created: '2024-01-15'
description: APIs for Ivanti Pulse Secure (formerly Pulse Secure), providing secure remote access VPN, network access control, and zero trust access solutions.
features:
- description: Secure remote access to corporate resources through SSL VPN tunnels with granular access policies.
  name: SSL VPN Remote Access
- description: Identity-aware, application-level access control without exposing network resources.
  name: Zero Trust Network Access
- description: Enforce security policies on endpoints before granting network access with 802.1X and agent-based checks.
  name: Network Access Control
- description: Integrate with MFA providers for strong authentication on VPN and network access.
  name: Multi-Factor Authentication
- description: Validate endpoint compliance with security policies before granting access.
  name: Host Checker
- description: Define granular access policies based on user roles, device type, and compliance status.
  name: Role-Based Access Control
image: /assets/icons/pulse.png
integrations:
- description: Authenticate users against Active Directory for single sign-on and role mapping.
  name: Microsoft Active Directory
- description: Integrate with RADIUS for centralized authentication and accounting.
  name: RADIUS Servers
- description: Forward access logs and security events to SIEM platforms for monitoring and analysis.
  name: SIEM Platforms
- description: Integrate with mobile device management solutions for endpoint compliance verification.
  name: MDM Solutions
- description: Connect with SAML and OIDC identity providers for federated authentication.
  name: Identity Providers
layout: provider
modified: '2026-04-18'
name: Pulse
skills: []
slug: pulse
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: pulse\nname: Pulse\ndescription: APIs for Ivanti Pulse Secure (formerly Pulse Secure), providing secure remote access VPN, network access control, and zero trust access solutions.\ntype: Index\nurl: https://raw.githubusercontent.com/api-evangelist/pulse/refs/heads/main/apis.yml\ntags:\n  - Ivanti\n  - Network Security\n  - Secure Access\n  - SSL VPN\n  - VPN\n  - Zero Trust\ncreated: '2024-01-15'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\napis:\n  - aid: pulse:ivanti-connect-secure-rest-api\n    name: Ivanti Connect Secure REST API\n    description: REST API for managing Ivanti Connect Secure (formerly Pulse Connect Secure) VPN appliances. Provides endpoints for system configuration, user and role management, authentication server configuration, license management, network settings, resource policies, and system maintenance operations.\n    humanURL: https://help.ivanti.com/ps/help/en_US/IPS/vNow/pcs-pps-rest-api/landingpage.htm\n    tags:\n      - Authentication\n\
  \      - Configuration\n      - Network Security\n      - Secure Access\n      - SSL VPN\n      - VPN\n    properties:\n      - type: Documentation\n        url: https://help.ivanti.com/ps/help/en_US/IPS/vNow/pcs-pps-rest-api/landingpage.htm\n  - aid: pulse:ivanti-policy-secure-rest-api\n    name: Ivanti Policy Secure REST API\n    description: REST API for managing Ivanti Policy Secure (formerly Pulse Policy Secure) network access control appliances.\n    humanURL: https://help.ivanti.com/ps/help/en_US/IPS/vNow/pcs-pps-rest-api/landingpage.htm\n    tags:\n      - NAC\n      - Network Access Control\n      - Policy\n      - Security\n    properties:\n      - type: Documentation\n        url: https://help.ivanti.com/ps/help/en_US/IPS/vNow/pcs-pps-rest-api/landingpage.htm\n  - aid: pulse:ivanti-neurons-zero-trust-rest-api\n    name: Ivanti Neurons for Zero Trust Access REST API\n    description: REST API for managing Ivanti Neurons for Zero Trust Access (nZTA), providing endpoints for managing\
  \ zero trust access policies, gateways, and user access.\n    humanURL: https://help.ivanti.com/ps/help/en_US/nSA/22.x/nsa-zta/api/landingpage.htm\n    tags:\n      - Secure Access\n      - Zero Trust\n      - ZTNA\n    properties:\n      - type: Documentation\n        url: https://help.ivanti.com/ps/help/en_US/nSA/22.x/nsa-zta/api/landingpage.htm\ncommon:\n  - type: Website\n    url: https://www.ivanti.com/products/connect-secure-vpn\n  - type: Documentation\n    url: https://www.ivanti.com/support/product-documentation\n  - type: PrivacyPolicy\n    url: https://www.ivanti.com/company/legal/privacy-policy\n  - type: TermsOfService\n    url: https://www.ivanti.com/company/legal\n  - type: Status\n    url: https://status.ivanticloud.com/\n  - type: Blog\n    url: https://www.ivanti.com/blog\n  - type: Community\n    url: https://forums.ivanti.com/s/welcome-pulse-secure?language=en_US\n  - type: Features\n    data:\n      - name: SSL VPN Remote Access\n        description: Secure remote\
  \ access to corporate resources through SSL VPN tunnels with granular access policies.\n      - name: Zero Trust Network Access\n        description: Identity-aware, application-level access control without exposing network resources.\n      - name: Network Access Control\n        description: Enforce security policies on endpoints before granting network access with 802.1X and agent-based checks.\n      - name: Multi-Factor Authentication\n        description: Integrate with MFA providers for strong authentication on VPN and network access.\n      - name: Host Checker\n        description: Validate endpoint compliance with security policies before granting access.\n      - name: Role-Based Access Control\n        description: Define granular access policies based on user roles, device type, and compliance status.\n  - type: UseCases\n    data:\n      - name: Remote Workforce Access\n        description: Provide secure remote access to corporate applications and resources for distributed\
  \ teams.\n      - name: Zero Trust Architecture\n        description: Implement zero trust security with per-application access controls and continuous verification.\n      - name: BYOD Management\n        description: Securely enable bring-your-own-device access with endpoint compliance checking.\n      - name: Partner and Contractor Access\n        description: Grant controlled, time-limited access to third-party partners and contractors.\n  - type: Integrations\n    data:\n      - name: Microsoft Active Directory\n        description: Authenticate users against Active Directory for single sign-on and role mapping.\n      - name: RADIUS Servers\n        description: Integrate with RADIUS for centralized authentication and accounting.\n      - name: SIEM Platforms\n        description: Forward access logs and security events to SIEM platforms for monitoring and analysis.\n      - name: MDM Solutions\n        description: Integrate with mobile device management solutions for endpoint compliance\
  \ verification.\n      - name: Identity Providers\n        description: Connect with SAML and OIDC identity providers for federated authentication.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/pulse/refs/heads/main/apis.yml
tags:
- Ivanti
- Network Security
- Secure Access
- SSL VPN
- VPN
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/pulse/refs/heads/main/apis.yml
use_cases:
- description: Provide secure remote access to corporate applications and resources for distributed teams.
  name: Remote Workforce Access
- description: Implement zero trust security with per-application access controls and continuous verification.
  name: Zero Trust Architecture
- description: Securely enable bring-your-own-device access with endpoint compliance checking.
  name: BYOD Management
- description: Grant controlled, time-limited access to third-party partners and contractors.
  name: Partner and Contractor Access
---
