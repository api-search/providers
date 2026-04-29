---
api_count: 1
api_specs:
- filename: amazon-workspaces-web-openapi-original.yaml
  format: yaml
  label: Amazon WorkSpaces Web API
  slug: amazon-workspaces-web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces-web/refs/heads/main/openapi/amazon-workspaces-web-openapi-original.yaml
apis:
- description: 'The Amazon WorkSpaces Web API provides programmatic access to create and manage web portals, network settings, user access logging, user settings, browser settings, and trust store configurations for '
  name: Amazon WorkSpaces Web API
  slug: amazon-workspaces-web-api
capabilities:
- description: Unified workflow for IT administrators to manage Amazon WorkSpaces Web portals, user settings, browser policies, network configurations, and trust stores for enterprise secure browser deployments.
  name: Amazon WorkSpaces Web Secure Browser Management
  slug: secure-browser-management
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Website
  url: https://aws.amazon.com/workspaces/web/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/workspaces-web/latest/adminguide/
- title: ''
  type: Console
  url: https://console.aws.amazon.com/workspaces-web/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: StatusPage
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: SpectralRules
  url: rules/amazon-workspaces-web-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-workspaces-web-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/secure-browser-management.yaml
created: '2026-03-16'
description: Amazon WorkSpaces Web is a purpose-built, low-cost, fully managed service that enables secure browser access to internal websites and SaaS applications. It provides persistent browser sessions with built-in security controls, preventing users from downloading content to local devices while maintaining a seamless browsing experience. The service offers 58 API operations for managing portals, user settings, browser policies, network settings, trust stores, and IP access controls.
features:
- description: Purpose-built browser portals that provide secure access to internal websites and SaaS applications without VPN requirements.
  name: Secure Browser Portals
- description: Built-in controls to prevent users from downloading, uploading, printing, or copying content to local devices.
  name: Data Loss Prevention Controls
- description: Configurable browser policies to control features like clipboard access, printing, and file transfers at the organizational level.
  name: Browser Policy Management
- description: VPC-based network settings to isolate browser sessions within enterprise network boundaries with security group controls.
  name: Network Isolation
- description: SSL certificate trust stores for validating internal website certificates in secure browser sessions.
  name: Trust Store Management
- description: IP-based access rules to restrict portal access to specific corporate IP ranges or geographic locations.
  name: IP Access Controls
- description: Detailed session logging for audit and compliance purposes with integration to Kinesis data streams.
  name: User Access Logging
- description: SAML-based identity provider integration for single sign-on to secure browser portal sessions.
  name: Identity Integration
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Single sign-on integration for WorkSpaces Web portal authentication.
  name: AWS IAM Identity Center
- description: User access logging integration to stream session data for analysis.
  name: Amazon Kinesis
- description: Encryption key management for browser settings and data at rest.
  name: AWS KMS
- description: VPC integration for network isolation of browser sessions.
  name: Amazon VPC
- description: Certificate management for trust store and SSL configurations.
  name: AWS Certificate Manager
jsonld:
- class_count: 139
  name: Amazon Workspaces Web Context
  property_count: 63
  slug: amazon-workspaces-web-context
layout: provider
modified: '2026-04-19'
name: Amazon WorkSpaces Web
rules:
- name: Amazon WorkSpaces Web API Rules
  rule_count: 18
  severity_counts:
    error: 8
    hint: 0
    info: 3
    warn: 7
  slug: amazon-workspaces-web-spectral-rules
skills: []
slug: amazon-workspaces-web
solutions: []
source_filename: apis.yml
source_yaml: "aid: amazon-workspaces-web\nname: Amazon WorkSpaces Web\ndescription: >-\n  Amazon WorkSpaces Web is a purpose-built, low-cost, fully managed service\n  that enables secure browser access to internal websites and SaaS applications.\n  It provides persistent browser sessions with built-in security controls,\n  preventing users from downloading content to local devices while maintaining\n  a seamless browsing experience. The service offers 58 API operations for\n  managing portals, user settings, browser policies, network settings, trust\n  stores, and IP access controls.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - AWS\n  - End User Computing\n  - Secure Browser\n  - Virtual Desktop\n  - Zero Trust\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amazon-workspaces-web/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: amazon-workspaces-web:amazon-workspaces-web-api\n\
  \    name: Amazon WorkSpaces Web API\n    description: >-\n      The Amazon WorkSpaces Web API provides programmatic access to create and\n      manage web portals, network settings, user access logging, user settings,\n      browser settings, and trust store configurations for secure browser\n      deployments. 58 operations covering portals, user settings, browser\n      policies, network settings, trust stores, and IP access controls.\n    humanURL: https://aws.amazon.com/workspaces/web/\n    baseURL: https://workspaces-web.amazonaws.com\n    tags:\n      - AWS\n      - End User Computing\n      - Secure Browser\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/workspaces-web/latest/adminguide/\n      - type: APIReference\n        url: https://docs.aws.amazon.com/workspaces-web/latest/APIReference/\n      - type: GettingStarted\n        url: https://docs.aws.amazon.com/workspaces-web/latest/adminguide/getting-started.html\n \
  \     - type: Pricing\n        url: https://aws.amazon.com/workspaces/web/pricing/\n      - type: FAQ\n        url: https://aws.amazon.com/workspaces/web/faqs/\n      - type: OpenAPI\n        url: openapi/amazon-workspaces-web-openapi-original.yaml\n      - type: JSONSchema\n        url: json-schema/workspaces-web-portal-schema.json\n      - type: JSONLD\n        url: json-ld/amazon-workspaces-web-context.jsonld\ncommon:\n  - type: Portal\n    url: https://aws.amazon.com/\n  - type: Website\n    url: https://aws.amazon.com/workspaces/web/\n  - type: Documentation\n    url: https://docs.aws.amazon.com/workspaces-web/latest/adminguide/\n  - type: Console\n    url: https://console.aws.amazon.com/workspaces-web/\n  - type: TermsOfService\n    url: https://aws.amazon.com/service-terms/\n  - type: PrivacyPolicy\n    url: https://aws.amazon.com/privacy/\n  - type: Support\n    url: https://aws.amazon.com/premiumsupport/\n  - type: SignUp\n    url: https://signin.aws.amazon.com/signup?request_type=register\n\
  \  - type: Login\n    url: https://aws.amazon.com/console/\n  - type: StatusPage\n    url: https://health.aws.amazon.com/health/status\n  - type: GitHubOrganization\n    url: https://github.com/aws\n  - type: SpectralRules\n    url: rules/amazon-workspaces-web-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/amazon-workspaces-web-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/secure-browser-management.yaml\n  - type: Features\n    data:\n      - name: Secure Browser Portals\n        description: >-\n          Purpose-built browser portals that provide secure access to internal\n          websites and SaaS applications without VPN requirements.\n      - name: Data Loss Prevention Controls\n        description: >-\n          Built-in controls to prevent users from downloading, uploading,\n          printing, or copying content to local devices.\n      - name: Browser Policy Management\n        description: >-\n          Configurable browser policies to control\
  \ features like clipboard\n          access, printing, and file transfers at the organizational level.\n      - name: Network Isolation\n        description: >-\n          VPC-based network settings to isolate browser sessions within\n          enterprise network boundaries with security group controls.\n      - name: Trust Store Management\n        description: >-\n          SSL certificate trust stores for validating internal website\n          certificates in secure browser sessions.\n      - name: IP Access Controls\n        description: >-\n          IP-based access rules to restrict portal access to specific\n          corporate IP ranges or geographic locations.\n      - name: User Access Logging\n        description: >-\n          Detailed session logging for audit and compliance purposes\n          with integration to Kinesis data streams.\n      - name: Identity Integration\n        description: >-\n          SAML-based identity provider integration for single sign-on\n     \
  \     to secure browser portal sessions.\n  - type: UseCases\n    data:\n      - name: Secure Third-Party Access\n        description: >-\n          Provide contractors and third-party vendors secure access to\n          internal tools without requiring VPN or device enrollment.\n      - name: BYOD Security\n        description: >-\n          Enable bring-your-own-device policies while maintaining security\n          controls over corporate application access.\n      - name: Compliance-Driven Browsing\n        description: >-\n          Enforce data handling compliance requirements through browser-level\n          controls for regulated industries.\n      - name: SaaS Application Security\n        description: >-\n          Provide secure, controlled access to SaaS applications with\n          session recording and data exfiltration prevention.\n      - name: Developer Sandbox Environments\n        description: >-\n          Create isolated browser environments for development and testing\n\
  \          of internal web applications.\n  - type: Integrations\n    data:\n      - name: AWS IAM Identity Center\n        description: >-\n          Single sign-on integration for WorkSpaces Web portal authentication.\n      - name: Amazon Kinesis\n        description: >-\n          User access logging integration to stream session data for analysis.\n      - name: AWS KMS\n        description: >-\n          Encryption key management for browser settings and data at rest.\n      - name: Amazon VPC\n        description: >-\n          VPC integration for network isolation of browser sessions.\n      - name: AWS Certificate Manager\n        description: >-\n          Certificate management for trust store and SSL configurations.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces-web/refs/heads/main/apis.yml
tags:
- AWS
- End User Computing
- Secure Browser
- Virtual Desktop
- Zero Trust
url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces-web/refs/heads/main/apis.yml
use_cases:
- description: Provide contractors and third-party vendors secure access to internal tools without requiring VPN or device enrollment.
  name: Secure Third-Party Access
- description: Enable bring-your-own-device policies while maintaining security controls over corporate application access.
  name: BYOD Security
- description: Enforce data handling compliance requirements through browser-level controls for regulated industries.
  name: Compliance-Driven Browsing
- description: Provide secure, controlled access to SaaS applications with session recording and data exfiltration prevention.
  name: SaaS Application Security
- description: Create isolated browser environments for development and testing of internal web applications.
  name: Developer Sandbox Environments
---
