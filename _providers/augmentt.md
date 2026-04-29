---
api_count: 3
apis:
- description: Augmentt Discover provides SaaS discovery and Shadow IT detection capabilities for MSPs, identifying all cloud applications used across managed client environments.
  name: Augmentt Discover
  slug: augmentt-discover
- description: Augmentt Optimize tracks SaaS usage and spend across client environments to identify unused licenses, redundant applications, and cost savings opportunities for MSPs.
  name: Augmentt Optimize
  slug: augmentt-optimize
- description: Augmentt Engage provides SaaS administration, management, and automation capabilities allowing MSPs to centralize SaaS security policy enforcement and user lifecycle management across Microsoft 365 an
  name: Augmentt Engage
  slug: augmentt-engage
common:
- title: ''
  type: Website
  url: https://www.augmentt.com
- title: ''
  type: Documentation
  url: https://www.augmentt.com/resources
- title: ''
  type: PrivacyPolicy
  url: https://www.augmentt.com/privacy-policy/
- title: ''
  type: TermsOfService
  url: https://www.augmentt.com/terms-of-service/
- title: ''
  type: Contact
  url: https://www.augmentt.com/contact/
- title: ''
  type: Blog
  url: https://www.augmentt.com/blog/
- title: ''
  type: SignUp
  url: https://www.augmentt.com/free-trial/
- title: ''
  type: Pricing
  url: https://www.augmentt.com/pricing/
created: '2026-03-27'
description: Augmentt is a multi-tenant SaaS management platform built for managed service providers (MSPs). It provides SaaS discovery (Shadow IT), license optimization, usage tracking, spend management, and SaaS security policy enforcement across Microsoft 365 and cloud applications. Augmentt integrates with major PSA and RMM platforms including ConnectWise and N-able.
features:
- description: Manage SaaS applications across multiple client tenants from a single MSP dashboard with hierarchical access control.
  name: Multi-Tenant Management
- description: Automatically discover all cloud applications in use across client environments including Shadow IT not approved by IT.
  name: SaaS Discovery
- description: Track license utilization, identify unused seats, and generate recommendations to reduce SaaS spend across clients.
  name: License Optimization
- description: Enforce security policies across SaaS applications including MFA requirements, conditional access, and app permissions.
  name: SaaS Security Policies
- description: Automate user onboarding and offboarding across SaaS applications when employees join or leave client organizations.
  name: User Lifecycle Management
- description: Integrate discovery and optimization data with PSA platforms for automated billing and service delivery.
  name: PSA Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Native integration with ConnectWise PSA for automated ticketing and billing based on SaaS discovery and license data.
  name: ConnectWise
- description: Integration with N-able RMM for combined endpoint and SaaS management visibility for MSPs.
  name: N-able
- description: Deep integration with Microsoft 365 tenant data for SaaS license, usage, and security policy management.
  name: Microsoft 365
- description: Augmentt data surfaced in CloudRadial customer portal for self-service SaaS app visibility.
  name: CloudRadial
layout: provider
modified: '2026-04-19'
name: Augmentt
skills: []
slug: augmentt
solutions:
- description: Package and deliver SaaS management as a managed service offering including discovery, optimization, and security monitoring.
  name: MSP SaaS Management Service
- description: Extend M365 security posture management with SaaS-specific controls, policy enforcement, and compliance reporting.
  name: Microsoft 365 Security
source_filename: apis.yml
source_yaml: "aid: augmentt\nname: Augmentt\ndescription: |\n  Augmentt is a multi-tenant SaaS management platform built for managed service providers (MSPs). It provides SaaS discovery (Shadow IT), license optimization, usage tracking, spend management, and SaaS security policy enforcement across Microsoft 365 and cloud applications. Augmentt integrates with major PSA and RMM platforms including ConnectWise and N-able.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n- MSP\n- Microsoft 365\n- SaaS Management\n- SaaS Security\n- Shadow IT\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/augmentt/refs/heads/main/apis.yml\ncreated: '2026-03-27'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n- aid: augmentt:augmentt-discover\n  name: Augmentt Discover\n  description: |\n    Augmentt Discover provides SaaS discovery and Shadow IT detection capabilities for MSPs, identifying all cloud applications used across managed\
  \ client environments.\n  humanURL: https://www.augmentt.com/the-tools-you-need-to-offer-saas-admin-services/\n  baseURL: https://www.augmentt.com\n  tags:\n  - Discovery\n  - MSP\n  - SaaS\n  - Shadow IT\n  properties:\n  - type: Documentation\n    url: https://www.augmentt.com/the-tools-you-need-to-offer-saas-admin-services/\n- aid: augmentt:augmentt-optimize\n  name: Augmentt Optimize\n  description: |\n    Augmentt Optimize tracks SaaS usage and spend across client environments to identify unused licenses, redundant applications, and cost savings opportunities for MSPs.\n  humanURL: https://www.augmentt.com/the-tools-you-need-to-offer-saas-admin-services/\n  baseURL: https://www.augmentt.com\n  tags:\n  - License Management\n  - MSP\n  - SaaS\n  - Spend Management\n  properties:\n  - type: Documentation\n    url: https://www.augmentt.com/the-tools-you-need-to-offer-saas-admin-services/\n- aid: augmentt:augmentt-engage\n  name: Augmentt Engage\n  description: |\n    Augmentt Engage\
  \ provides SaaS administration, management, and automation capabilities allowing MSPs to centralize SaaS security policy enforcement and user lifecycle management across Microsoft 365 and cloud apps.\n  humanURL: https://www.augmentt.com/user-management/\n  baseURL: https://www.augmentt.com\n  tags:\n  - Automation\n  - MSP\n  - SaaS Security\n  - User Management\n  properties:\n  - type: Documentation\n    url: https://www.augmentt.com/user-management/\ncommon:\n- type: Website\n  url: https://www.augmentt.com\n- type: Documentation\n  url: https://www.augmentt.com/resources\n- type: Integrations\n  data:\n  - name: ConnectWise\n    description: Native integration with ConnectWise PSA for automated ticketing and billing based on SaaS discovery and license data.\n  - name: N-able\n    description: Integration with N-able RMM for combined endpoint and SaaS management visibility for MSPs.\n  - name: Microsoft 365\n    description: Deep integration with Microsoft 365 tenant data for SaaS\
  \ license, usage, and security policy management.\n  - name: CloudRadial\n    description: Augmentt data surfaced in CloudRadial customer portal for self-service SaaS app visibility.\n- type: Features\n  data:\n  - name: Multi-Tenant Management\n    description: Manage SaaS applications across multiple client tenants from a single MSP dashboard with hierarchical access control.\n  - name: SaaS Discovery\n    description: Automatically discover all cloud applications in use across client environments including Shadow IT not approved by IT.\n  - name: License Optimization\n    description: Track license utilization, identify unused seats, and generate recommendations to reduce SaaS spend across clients.\n  - name: SaaS Security Policies\n    description: Enforce security policies across SaaS applications including MFA requirements, conditional access, and app permissions.\n  - name: User Lifecycle Management\n    description: Automate user onboarding and offboarding across SaaS applications\
  \ when employees join or leave client organizations.\n  - name: PSA Integration\n    description: Integrate discovery and optimization data with PSA platforms for automated billing and service delivery.\n- type: UseCases\n  data:\n  - name: SaaS Spend Management\n    description: Identify and eliminate wasted SaaS spend by discovering unused licenses and redundant applications across client portfolios.\n  - name: Shadow IT Control\n    description: Detect and manage unsanctioned cloud applications to reduce security risk and enforce acceptable use policies.\n  - name: Microsoft 365 Management\n    description: Manage M365 licenses, security settings, and user access across all client tenants from a unified MSP console.\n  - name: Employee Offboarding\n    description: Automate secure offboarding of departing employees by revoking access to all SaaS applications simultaneously.\n- type: Solutions\n  data:\n  - name: MSP SaaS Management Service\n    description: Package and deliver SaaS\
  \ management as a managed service offering including discovery, optimization, and security monitoring.\n  - name: Microsoft 365 Security\n    description: Extend M365 security posture management with SaaS-specific controls, policy enforcement, and compliance reporting.\n- type: PrivacyPolicy\n  url: https://www.augmentt.com/privacy-policy/\n- type: TermsOfService\n  url: https://www.augmentt.com/terms-of-service/\n- type: Contact\n  url: https://www.augmentt.com/contact/\n- type: Blog\n  url: https://www.augmentt.com/blog/\n- type: SignUp\n  url: https://www.augmentt.com/free-trial/\n- type: Pricing\n  url: https://www.augmentt.com/pricing/\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/augmentt/refs/heads/main/apis.yml
tags:
- MSP
- Microsoft 365
- SaaS Management
- SaaS Security
- Shadow IT
url: https://raw.githubusercontent.com/api-evangelist/augmentt/refs/heads/main/apis.yml
use_cases:
- description: Identify and eliminate wasted SaaS spend by discovering unused licenses and redundant applications across client portfolios.
  name: SaaS Spend Management
- description: Detect and manage unsanctioned cloud applications to reduce security risk and enforce acceptable use policies.
  name: Shadow IT Control
- description: Manage M365 licenses, security settings, and user access across all client tenants from a unified MSP console.
  name: Microsoft 365 Management
- description: Automate secure offboarding of departing employees by revoking access to all SaaS applications simultaneously.
  name: Employee Offboarding
---
