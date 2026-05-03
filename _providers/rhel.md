---
api_count: 8
api_specs:
- filename: openapi.json
  format: json
  label: Red Hat Subscription Management API
  slug: subscription-management-api
  spec_type: OpenAPI
  url: https://api.access.redhat.com/management/v1/openapi.json
- filename: openapi.json
  format: json
  label: Red Hat Insights API
  slug: insights-api
  spec_type: OpenAPI
  url: https://cloud.redhat.com/api/insights/v1/openapi.json
- filename: rhel-security-data-openapi.yml
  format: yaml
  label: Red Hat Security Data API
  slug: security-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/openapi/rhel-security-data-openapi.yml
- filename: openapi.json
  format: json
  label: Red Hat Insights Compliance API
  slug: compliance-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/compliance/v2/openapi.json
- filename: openapi.json
  format: json
  label: Red Hat Insights Vulnerability API
  slug: vulnerability-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/vulnerability/v1/openapi.json
- filename: openapi.json
  format: json
  label: Red Hat Insights Patch API
  slug: patch-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/patch/v3/openapi.json
- filename: openapi.json
  format: json
  label: Red Hat Insights Host Inventory API
  slug: inventory-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/inventory/v1/openapi.json
- filename: openapi.json
  format: json
  label: Red Hat Insights Remediations API
  slug: remediations-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/remediations/v1/openapi.json
apis:
- description: API for managing RHEL subscriptions, entitlements, and system registrations. Enables automation of subscription lifecycle, system registration, and entitlement queries using OAuth 2.0 authentication.
  name: Red Hat Subscription Management API
  slug: subscription-management-api
- description: Predictive analytics and remediation service for RHEL systems. Provides advisor recommendations based on 20+ years of Red Hat support experience, covering security, performance, availability, and stab
  name: Red Hat Insights API
  slug: insights-api
- description: API for accessing security advisories, CVE data, bug fixes, and enhancement updates for Red Hat products. Enables automated vulnerability assessment and tracking of RHEL-relevant CVEs with severity fi
  name: Red Hat Security Data API
  slug: security-data-api
- description: API for assessing, monitoring, and reporting on security-policy compliance of RHEL systems. Based on the Security Content Automation Protocol (SCAP), enables creation and management of compliance poli
  name: Red Hat Insights Compliance API
  slug: compliance-api
- description: API for managing vulnerabilities on RHEL systems. Integrates with the Red Hat CVE database to assess outstanding CVEs and provide remediation guidance for registered RHEL hosts.
  name: Red Hat Insights Vulnerability API
  slug: vulnerability-api
- description: API for patch management of RHEL systems. Tracks applicable advisories and patches for registered systems, enabling automated patch compliance reporting and remediation workflows.
  name: Red Hat Insights Patch API
  slug: patch-api
- description: API for managing the inventory of RHEL systems registered with Red Hat Insights. Provides host metadata, system profiles, and group management for hybrid cloud environments.
  name: Red Hat Insights Host Inventory API
  slug: inventory-api
- description: API for creating and executing Ansible-based remediation playbooks for RHEL systems. Integrates with Insights advisor, vulnerability, and compliance services to automate issue resolution at scale.
  name: Red Hat Insights Remediations API
  slug: remediations-api
capabilities:
- description: Unified capability for Red Hat Enterprise Linux vulnerability management. Combines the Security Data API and Subscription Management API to enable automated CVE assessment, advisory lookup, and system
  name: RHEL Vulnerability Management
  slug: vulnerability-management
common:
- title: ''
  type: Portal
  url: https://access.redhat.com
- title: ''
  type: Developer
  url: https://developers.redhat.com/products/rhel
- title: ''
  type: Documentation
  url: https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/
- title: ''
  type: HybridCloudConsole
  url: https://console.redhat.com
- title: ''
  type: APIManagement
  url: https://access.redhat.com/management/api
- title: ''
  type: GithubOrg
  url: https://github.com/RedHatOfficial
- title: ''
  type: GithubOrg
  url: https://github.com/redhat-cop
- title: ''
  type: Support
  url: https://access.redhat.com/support
- title: ''
  type: TermsOfService
  url: https://www.redhat.com/en/about/terms-use
- title: ''
  type: PrivacyPolicy
  url: https://www.redhat.com/en/about/privacy-policy
- title: ''
  type: Website
  url: https://www.redhat.com
- title: ''
  type: Authentication
  url: https://access.redhat.com/articles/3626371
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/rules/rhel-rules.yml
- title: ''
  type: NaftikoCapabilities
  url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/capabilities/vulnerability-management.yaml
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/json-schema/rhel-cve-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/json-schema/rhel-system-schema.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/json-ld/rhel-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/vocabulary/rhel-vocabulary.yml
created: '2024-01-01'
description: Red Hat Enterprise Linux (RHEL) is the world's leading enterprise Linux platform, providing APIs and services for subscription management, security insights, compliance monitoring, vulnerability assessment, patch management, content delivery, and automation. The Red Hat Hybrid Cloud Console exposes a comprehensive suite of REST APIs for managing RHEL systems at scale.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 33
  name: Rhel Context
  property_count: 0
  slug: rhel-context
layout: provider
modified: '2026-05-02'
name: Red Hat Enterprise Linux
rules:
- name: Red Hat Enterprise Linux API Rules
  rule_count: 9
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 5
  slug: rhel-rules
skills: []
slug: rhel
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: rhel\nname: Red Hat Enterprise Linux\ndescription: >-\n  Red Hat Enterprise Linux (RHEL) is the world's leading enterprise Linux\n  platform, providing APIs and services for subscription management, security\n  insights, compliance monitoring, vulnerability assessment, patch management,\n  content delivery, and automation. The Red Hat Hybrid Cloud Console exposes\n  a comprehensive suite of REST APIs for managing RHEL systems at scale.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Automation\n  - Compliance\n  - Enterprise\n  - Linux\n  - Operating System\n  - Red Hat\n  - RHEL\n  - Security\n  - Subscription Management\n  - Vulnerability Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: rhel:subscription-management-api\n    name: Red Hat Subscription Management API\n\
  \    description: >-\n      API for managing RHEL subscriptions, entitlements, and system\n      registrations. Enables automation of subscription lifecycle, system\n      registration, and entitlement queries using OAuth 2.0 authentication.\n    humanURL: https://access.redhat.com/management/api\n    baseURL: https://api.access.redhat.com/management/v1\n    tags:\n      - Entitlements\n      - Systems Management\n      - Subscriptions\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/management/api/docs\n      - type: OpenAPI\n        url: https://api.access.redhat.com/management/v1/openapi.json\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/openapi/rhel-subscription-management-openapi.yml\n      - type: Authentication\n        url: https://access.redhat.com/articles/3626371\n  - aid: rhel:insights-api\n    name: Red Hat Insights API\n    description: >-\n      Predictive analytics and remediation\
  \ service for RHEL systems. Provides\n      advisor recommendations based on 20+ years of Red Hat support experience,\n      covering security, performance, availability, and stability issues.\n    humanURL: https://console.redhat.com/docs/api/insights\n    baseURL: https://console.redhat.com/api/insights/v1\n    tags:\n      - Analytics\n      - Monitoring\n      - Remediation\n    properties:\n      - type: Documentation\n        url: https://console.redhat.com/docs/api/insights\n      - type: OpenAPI\n        url: https://cloud.redhat.com/api/insights/v1/openapi.json\n  - aid: rhel:security-data-api\n    name: Red Hat Security Data API\n    description: >-\n      API for accessing security advisories, CVE data, bug fixes, and\n      enhancement updates for Red Hat products. Enables automated vulnerability\n      assessment and tracking of RHEL-relevant CVEs with severity filtering.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_security_data_api/\n    baseURL:\
  \ https://access.redhat.com/hydra/rest/securitydata\n    tags:\n      - Advisories\n      - CVE\n      - Errata\n      - Security\n      - Vulnerability Management\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_security_data_api/1.0/\n      - type: GithubRepository\n        url: https://github.com/RedHatOfficial/rhsecapi\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/openapi/rhel-security-data-openapi.yml\n  - aid: rhel:compliance-api\n    name: Red Hat Insights Compliance API\n    description: >-\n      API for assessing, monitoring, and reporting on security-policy compliance\n      of RHEL systems. Based on the Security Content Automation Protocol (SCAP),\n      enables creation and management of compliance policies and reports.\n    humanURL: https://console.redhat.com/docs/api/compliance\n    baseURL: https://console.redhat.com/api/compliance/v2\n    tags:\n\
  \      - Compliance\n      - SCAP\n      - Security\n    properties:\n      - type: Documentation\n        url: https://console.redhat.com/docs/api/compliance\n      - type: OpenAPI\n        url: https://console.redhat.com/api/compliance/v2/openapi.json\n  - aid: rhel:vulnerability-api\n    name: Red Hat Insights Vulnerability API\n    description: >-\n      API for managing vulnerabilities on RHEL systems. Integrates with the\n      Red Hat CVE database to assess outstanding CVEs and provide remediation\n      guidance for registered RHEL hosts.\n    humanURL: https://console.redhat.com/docs/api/vulnerability\n    baseURL: https://console.redhat.com/api/vulnerability/v1\n    tags:\n      - CVE\n      - Remediation\n      - Security\n      - Vulnerability Management\n    properties:\n      - type: Documentation\n        url: https://console.redhat.com/docs/api/vulnerability\n      - type: OpenAPI\n        url: https://console.redhat.com/api/vulnerability/v1/openapi.json\n  - aid: rhel:patch-api\n\
  \    name: Red Hat Insights Patch API\n    description: >-\n      API for patch management of RHEL systems. Tracks applicable advisories\n      and patches for registered systems, enabling automated patch compliance\n      reporting and remediation workflows.\n    humanURL: https://console.redhat.com/docs/api/patch\n    baseURL: https://console.redhat.com/api/patch/v3\n    tags:\n      - Advisories\n      - Patch Management\n      - Updates\n    properties:\n      - type: Documentation\n        url: https://console.redhat.com/docs/api/patch\n      - type: OpenAPI\n        url: https://console.redhat.com/api/patch/v3/openapi.json\n  - aid: rhel:inventory-api\n    name: Red Hat Insights Host Inventory API\n    description: >-\n      API for managing the inventory of RHEL systems registered with Red Hat\n      Insights. Provides host metadata, system profiles, and group management\n      for hybrid cloud environments.\n    humanURL: https://console.redhat.com/docs/api/inventory\n    baseURL:\
  \ https://console.redhat.com/api/inventory/v1\n    tags:\n      - Hosts\n      - Inventory\n      - Systems Management\n    properties:\n      - type: Documentation\n        url: https://console.redhat.com/docs/api/inventory\n      - type: OpenAPI\n        url: https://console.redhat.com/api/inventory/v1/openapi.json\n  - aid: rhel:remediations-api\n    name: Red Hat Insights Remediations API\n    description: >-\n      API for creating and executing Ansible-based remediation playbooks for\n      RHEL systems. Integrates with Insights advisor, vulnerability, and\n      compliance services to automate issue resolution at scale.\n    humanURL: https://console.redhat.com/docs/api/remediations\n    baseURL: https://console.redhat.com/api/remediations/v1\n    tags:\n      - Ansible\n      - Automation\n      - Remediation\n    properties:\n      - type: Documentation\n        url: https://console.redhat.com/docs/api/remediations\n      - type: OpenAPI\n        url: https://console.redhat.com/api/remediations/v1/openapi.json\n\
  common:\n  - type: Portal\n    url: https://access.redhat.com\n  - type: Developer\n    url: https://developers.redhat.com/products/rhel\n  - type: Documentation\n    url: https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/\n  - type: HybridCloudConsole\n    url: https://console.redhat.com\n  - type: APIManagement\n    url: https://access.redhat.com/management/api\n  - type: GithubOrg\n    url: https://github.com/RedHatOfficial\n  - type: GithubOrg\n    url: https://github.com/redhat-cop\n  - type: Support\n    url: https://access.redhat.com/support\n  - type: TermsOfService\n    url: https://www.redhat.com/en/about/terms-use\n  - type: PrivacyPolicy\n    url: https://www.redhat.com/en/about/privacy-policy\n  - type: Website\n    url: https://www.redhat.com\n  - type: Authentication\n    url: https://access.redhat.com/articles/3626371\n  - type: SpectralRules\n    url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/rules/rhel-rules.yml\n  - type:\
  \ NaftikoCapabilities\n    url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/capabilities/vulnerability-management.yaml\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/json-schema/rhel-cve-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/json-schema/rhel-system-schema.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/json-ld/rhel-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/vocabulary/rhel-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/apis.yml
tags:
- Automation
- Compliance
- Enterprise
- Linux
- Operating System
- Red Hat
- RHEL
- Security
- Subscription Management
- Vulnerability Management
url: https://raw.githubusercontent.com/api-evangelist/rhel/refs/heads/main/apis.yml
use_cases: []
---
