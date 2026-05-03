---
api_count: 10
api_specs:
- filename: openapi.json
  format: json
  label: RHEL 8 Subscription Management API
  slug: subscription-management-api
  spec_type: OpenAPI
  url: https://api.access.redhat.com/management/v1/openapi.json
- filename: openapi.json
  format: json
  label: RHEL 8 Insights API
  slug: insights-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/insights/v1/openapi.json
- filename: openapi.json
  format: json
  label: RHEL 8 Image Builder API
  slug: image-builder-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/image-builder/v1/openapi.json
- filename: openapi.json
  format: json
  label: RHEL 8 Patch Management API
  slug: patch-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/patch/v3/openapi.json
- filename: openapi.json
  format: json
  label: RHEL 8 Vulnerability Management API
  slug: vulnerability-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/vulnerability/v1/openapi.json
- filename: openapi.json
  format: json
  label: RHEL 8 Compliance API
  slug: compliance-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/compliance/v2/openapi.json
- filename: red-hat-enterprise-linux-8-security-data-openapi.yml
  format: yaml
  label: RHEL 8 Security Data API
  slug: security-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-enterprise-linux-8/refs/heads/main/openapi/red-hat-enterprise-linux-8-security-data-openapi.yml
- filename: openapi.json
  format: json
  label: RHEL 8 Host Inventory API
  slug: host-inventory-api
  spec_type: OpenAPI
  url: https://console.redhat.com/api/inventory/v1/openapi.json
apis:
- description: The Red Hat Subscription Management (RHSM) API provides programmatic access to manage Red Hat subscriptions, entitlements, and system registrations. Operators can list, activate, and manage subscripti
  name: RHEL 8 Subscription Management API
  slug: subscription-management-api
- description: Red Hat Insights is a predictive analytics service for RHEL systems that provides API access to vulnerability assessment, compliance reporting, patch management, drift analysis, and advisor recommenda
  name: RHEL 8 Insights API
  slug: insights-api
- description: 'The Red Hat Image Builder API enables automated creation of custom RHEL system images for cloud, virtual machine, and bare-metal deployments. Users can define image compositions, specify packages and '
  name: RHEL 8 Image Builder API
  slug: image-builder-api
- description: The Red Hat Patch Management API (part of Red Hat Insights) provides endpoints for querying available errata, advisories, and CVE patches for registered RHEL systems. It enables operators to list appl
  name: RHEL 8 Patch Management API
  slug: patch-api
- description: The Red Hat Vulnerability Management API (part of Insights) provides programmatic access to CVE vulnerability data for registered RHEL systems. Operators can query known CVEs affecting their hosts, re
  name: RHEL 8 Vulnerability Management API
  slug: vulnerability-api
- description: The Red Hat Compliance API (part of Insights) enables automated compliance scanning and reporting against security profiles such as CIS, DISA STIG, and PCI-DSS for RHEL systems. Operators can list com
  name: RHEL 8 Compliance API
  slug: compliance-api
- description: The Red Hat Security Data API provides public access to Red Hat's security advisory and CVE data. Operators can query CVEs affecting RHEL products, retrieve CVSS scores, list security advisories (RHSA
  name: RHEL 8 Security Data API
  slug: security-data-api
- description: 'The Red Hat Insights Host Inventory API provides programmatic access to the inventory of RHEL systems registered with Red Hat Insights. Operators can query hosts by attributes, retrieve system facts, '
  name: RHEL 8 Host Inventory API
  slug: host-inventory-api
- description: Cockpit is a web-based system management interface for RHEL that exposes internal D-Bus and system APIs through a WebSocket-based transport. The Cockpit API provides access to system configuration, st
  name: RHEL 8 Cockpit Web Console API
  slug: cockpit-api
- description: RHEL System Roles are a collection of Ansible roles and modules for automating RHEL system configuration tasks including networking, storage, certificate management, SELinux, time sync, and firewall c
  name: RHEL 8 System Roles API
  slug: system-roles-api
common:
- title: ''
  type: Portal
  url: https://access.redhat.com/
- title: ''
  type: Customer Portal
  url: https://console.redhat.com/
- title: ''
  type: Documentation
  url: https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/
- title: ''
  type: Knowledge Base
  url: https://access.redhat.com/knowledgebase/
- title: ''
  type: Support
  url: https://access.redhat.com/support/
- title: ''
  type: Downloads
  url: https://access.redhat.com/downloads/
- title: ''
  type: Blog
  url: https://www.redhat.com/en/blog/channel/red-hat-enterprise-linux
- title: ''
  type: Release Notes
  url: https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/8.0_release_notes/index
- title: ''
  type: Security
  url: https://access.redhat.com/security/
- title: ''
  type: Training
  url: https://www.redhat.com/en/services/training-and-certification
- title: ''
  type: GitHub Organization
  url: https://github.com/redhat-developer
- title: ''
  type: Privacy Policy
  url: https://www.redhat.com/en/about/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.redhat.com/en/about/agreements
- title: ''
  type: OpenAPI
  url: openapi/red-hat-enterprise-linux-8-security-data-openapi.yml
- title: ''
  type: JSONLDContext
  url: json-ld/red-hat-enterprise-linux-8-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/red-hat-enterprise-linux-8-cve-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/red-hat-enterprise-linux-8-cve-structure.json
- title: ''
  type: SpectralRuleset
  url: rules/red-hat-enterprise-linux-8-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/red-hat-enterprise-linux-8-vocabulary.yml
created: '2024-01-15'
description: Red Hat Enterprise Linux 8 (RHEL 8) is an enterprise-grade Linux distribution that provides a stable, secure, and high-performance operating system platform for modern IT environments. RHEL 8 is managed and accessed programmatically through Red Hat's cloud console APIs, subscription management APIs, security data APIs, and system management interfaces including Insights, Image Builder, and Cockpit. These APIs enable automated provisioning, configuration, security scanning, patch management, and compliance reporting for RHEL deployments at scale.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Red Hat Enterprise Linux 8 Context
  property_count: 19
  slug: red-hat-enterprise-linux-8-context
layout: provider
modified: '2026-05-02'
name: Red Hat Enterprise Linux 8
rules:
- name: Red Hat Enterprise Linux 8 API Rules
  rule_count: 11
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 6
  slug: red-hat-enterprise-linux-8-rules
skills: []
slug: red-hat-enterprise-linux-8
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: red-hat-enterprise-linux-8\nname: Red Hat Enterprise Linux 8\ndescription: >-\n  Red Hat Enterprise Linux 8 (RHEL 8) is an enterprise-grade Linux distribution\n  that provides a stable, secure, and high-performance operating system platform\n  for modern IT environments. RHEL 8 is managed and accessed programmatically\n  through Red Hat's cloud console APIs, subscription management APIs, security\n  data APIs, and system management interfaces including Insights, Image Builder,\n  and Cockpit. These APIs enable automated provisioning, configuration, security\n  scanning, patch management, and compliance reporting for RHEL deployments at scale.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Enterprise\n  - Linux\n  - Operating System\n  - Red Hat\n  - RHEL\nurl: https://raw.githubusercontent.com/api-evangelist/red-hat-enterprise-linux-8/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-05-02'\nspecificationVersion:\
  \ '0.19'\napis:\n  - aid: red-hat-enterprise-linux-8:subscription-management-api\n    name: RHEL 8 Subscription Management API\n    description: >-\n      The Red Hat Subscription Management (RHSM) API provides programmatic\n      access to manage Red Hat subscriptions, entitlements, and system\n      registrations. Operators can list, activate, and manage subscriptions,\n      query available SKUs, register and unregister systems, and retrieve\n      entitlement certificates. Authentication uses OAuth 2.0 tokens obtained\n      via the Red Hat SSO service.\n    humanURL: https://access.redhat.com/management/api\n    baseURL: https://api.access.redhat.com/management/v1\n    tags:\n      - Entitlements\n      - Registration\n      - Subscriptions\n      - System Management\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/management/api/rhsm\n      - type: OpenAPI\n        url: https://api.access.redhat.com/management/v1/openapi.json\n      - type: Authentication\n\
  \        url: https://access.redhat.com/articles/3626371\n\n  - aid: red-hat-enterprise-linux-8:insights-api\n    name: RHEL 8 Insights API\n    description: >-\n      Red Hat Insights is a predictive analytics service for RHEL systems that\n      provides API access to vulnerability assessment, compliance reporting,\n      patch management, drift analysis, and advisor recommendations. The Insights\n      API allows automation of security scanning, patch prioritization, and\n      system health monitoring for registered RHEL hosts. Authentication uses\n      OAuth 2.0 tokens via the console.redhat.com identity service.\n    humanURL: https://console.redhat.com/docs/api/insights\n    baseURL: https://console.redhat.com/api/insights/v1\n    tags:\n      - Analytics\n      - Compliance\n      - Monitoring\n      - Predictive Analytics\n      - Security\n      - Vulnerabilities\n    properties:\n      - type: Documentation\n        url: https://console.redhat.com/docs/api/insights\n      -\
  \ type: OpenAPI\n        url: https://console.redhat.com/api/insights/v1/openapi.json\n      - type: Console\n        url: https://console.redhat.com/insights\n\n  - aid: red-hat-enterprise-linux-8:image-builder-api\n    name: RHEL 8 Image Builder API\n    description: >-\n      The Red Hat Image Builder API enables automated creation of custom RHEL\n      system images for cloud, virtual machine, and bare-metal deployments.\n      Users can define image compositions, specify packages and customizations,\n      build images for specific target environments (AWS, Azure, GCP, VMware,\n      ISO), and download completed image artifacts. The API is part of the\n      Red Hat Hybrid Cloud Console.\n    humanURL: https://console.redhat.com/docs/api/image-builder\n    baseURL: https://console.redhat.com/api/image-builder/v1\n    tags:\n      - Cloud\n      - Deployment\n      - Image Builder\n      - Infrastructure\n      - Provisioning\n    properties:\n      - type: Documentation\n        url:\
  \ https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/composing_a_customized_rhel_system_image/index\n      - type: OpenAPI\n        url: https://console.redhat.com/api/image-builder/v1/openapi.json\n      - type: Tutorial\n        url: https://www.redhat.com/en/blog/using-red-hat-image-builder\n\n  - aid: red-hat-enterprise-linux-8:patch-api\n    name: RHEL 8 Patch Management API\n    description: >-\n      The Red Hat Patch Management API (part of Red Hat Insights) provides\n      endpoints for querying available errata, advisories, and CVE patches for\n      registered RHEL systems. It enables operators to list applicable patches\n      per system, filter by severity or type, and trigger patch installations.\n      The API integrates with Satellite for on-premises patch orchestration.\n    humanURL: https://console.redhat.com/docs/api/patch\n    baseURL: https://console.redhat.com/api/patch/v3\n    tags:\n      - Errata\n      - Packages\n      - Patch Management\n\
  \      - Security\n      - Updates\n    properties:\n      - type: Documentation\n        url: https://console.redhat.com/docs/api/patch\n      - type: OpenAPI\n        url: https://console.redhat.com/api/patch/v3/openapi.json\n\n  - aid: red-hat-enterprise-linux-8:vulnerability-api\n    name: RHEL 8 Vulnerability Management API\n    description: >-\n      The Red Hat Vulnerability Management API (part of Insights) provides\n      programmatic access to CVE vulnerability data for registered RHEL systems.\n      Operators can query known CVEs affecting their hosts, retrieve severity\n      scores, filter by system or CVE, and export vulnerability reports for\n      compliance and risk management purposes.\n    humanURL: https://console.redhat.com/docs/api/vulnerability\n    baseURL: https://console.redhat.com/api/vulnerability/v1\n    tags:\n      - CVE\n      - Risk Management\n      - Security\n      - Vulnerabilities\n    properties:\n      - type: Documentation\n        url: https://console.redhat.com/docs/api/vulnerability\n\
  \      - type: OpenAPI\n        url: https://console.redhat.com/api/vulnerability/v1/openapi.json\n\n  - aid: red-hat-enterprise-linux-8:compliance-api\n    name: RHEL 8 Compliance API\n    description: >-\n      The Red Hat Compliance API (part of Insights) enables automated compliance\n      scanning and reporting against security profiles such as CIS, DISA STIG,\n      and PCI-DSS for RHEL systems. Operators can list compliance policies,\n      query system compliance scores, retrieve rule results, and download\n      compliance reports in SCAP and PDF formats.\n    humanURL: https://console.redhat.com/docs/api/compliance\n    baseURL: https://console.redhat.com/api/compliance/v2\n    tags:\n      - Compliance\n      - SCAP\n      - Security\n      - STIG\n    properties:\n      - type: Documentation\n        url: https://console.redhat.com/docs/api/compliance\n      - type: OpenAPI\n        url: https://console.redhat.com/api/compliance/v2/openapi.json\n\n  - aid: red-hat-enterprise-linux-8:security-data-api\n\
  \    name: RHEL 8 Security Data API\n    description: >-\n      The Red Hat Security Data API provides public access to Red Hat's\n      security advisory and CVE data. Operators can query CVEs affecting RHEL\n      products, retrieve CVSS scores, list security advisories (RHSA), bug fix\n      advisories (RHBA), and enhancement advisories (RHEA), and obtain OVAL\n      XML data for vulnerability scanning integration. No authentication is\n      required for public data.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_security_data_api/1.0\n    baseURL: https://access.redhat.com/labs/securitydataapi\n    tags:\n      - Advisories\n      - CVE\n      - OVAL\n      - Public Data\n      - Security\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_security_data_api/1.0/html/red_hat_security_data_api/index\n      - type: API Endpoint\n        url: https://access.redhat.com/labs/securitydataapi/\n      - type:\
  \ Examples\n        url: https://access.redhat.com/articles/2915291\n      - type: OpenAPI\n        url: openapi/red-hat-enterprise-linux-8-security-data-openapi.yml\n\n  - aid: red-hat-enterprise-linux-8:host-inventory-api\n    name: RHEL 8 Host Inventory API\n    description: >-\n      The Red Hat Insights Host Inventory API provides programmatic access to\n      the inventory of RHEL systems registered with Red Hat Insights. Operators\n      can query hosts by attributes, retrieve system facts, manage host groups,\n      query system profiles, and track system metadata including OS version,\n      hardware, and installed packages.\n    humanURL: https://console.redhat.com/docs/api/inventory\n    baseURL: https://console.redhat.com/api/inventory/v1\n    tags:\n      - Asset Management\n      - Inventory\n      - System Management\n    properties:\n      - type: Documentation\n        url: https://console.redhat.com/docs/api/inventory\n      - type: OpenAPI\n        url: https://console.redhat.com/api/inventory/v1/openapi.json\n\
  \n  - aid: red-hat-enterprise-linux-8:cockpit-api\n    name: RHEL 8 Cockpit Web Console API\n    description: >-\n      Cockpit is a web-based system management interface for RHEL that exposes\n      internal D-Bus and system APIs through a WebSocket-based transport. The\n      Cockpit API provides access to system configuration, storage management,\n      network configuration, service management, user accounts, and system\n      logs from a web browser. It operates locally on each managed system at\n      port 9090.\n    humanURL: https://cockpit-project.org/guide/latest/api-base1.html\n    baseURL: https://localhost:9090/cockpit\n    tags:\n      - Management\n      - System Administration\n      - UI\n      - Web Console\n    properties:\n      - type: Documentation\n        url: https://cockpit-project.org/guide/latest/api-base1.html\n      - type: GitHub\n        url: https://github.com/cockpit-project/cockpit\n      - type: Guide\n        url: https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/managing_systems_using_the_rhel_8_web_console/index\n\
  \n  - aid: red-hat-enterprise-linux-8:system-roles-api\n    name: RHEL 8 System Roles API\n    description: >-\n      RHEL System Roles are a collection of Ansible roles and modules for\n      automating RHEL system configuration tasks including networking, storage,\n      certificate management, SELinux, time sync, and firewall configuration.\n      The roles expose a structured YAML-based API for declarative system\n      state management through Ansible Automation Platform or standalone Ansible.\n    humanURL: https://access.redhat.com/articles/3050101\n    baseURL: https://console.redhat.com/ansible/automation-hub/\n    tags:\n      - Ansible\n      - Automation\n      - Configuration Management\n      - System Roles\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/administration_and_configuration_tasks_using_system_roles_in_rhel/index\n      - type: GitHub\n        url: https://github.com/linux-system-roles\n\
  \      - type: Ansible Galaxy\n        url: https://galaxy.ansible.com/linux-system-roles\n\ncommon:\n  - type: Portal\n    url: https://access.redhat.com/\n  - type: Customer Portal\n    url: https://console.redhat.com/\n  - type: Documentation\n    url: https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/\n  - type: Knowledge Base\n    url: https://access.redhat.com/knowledgebase/\n  - type: Support\n    url: https://access.redhat.com/support/\n  - type: Downloads\n    url: https://access.redhat.com/downloads/\n  - type: Blog\n    url: https://www.redhat.com/en/blog/channel/red-hat-enterprise-linux\n  - type: Release Notes\n    url: https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/8.0_release_notes/index\n  - type: Security\n    url: https://access.redhat.com/security/\n  - type: Training\n    url: https://www.redhat.com/en/services/training-and-certification\n  - type: GitHub Organization\n    url: https://github.com/redhat-developer\n\
  \  - type: Privacy Policy\n    url: https://www.redhat.com/en/about/privacy-policy\n  - type: Terms of Service\n    url: https://www.redhat.com/en/about/agreements\n  - type: OpenAPI\n    url: openapi/red-hat-enterprise-linux-8-security-data-openapi.yml\n  - type: JSONLDContext\n    url: json-ld/red-hat-enterprise-linux-8-context.jsonld\n  - type: JSONSchema\n    url: json-schema/red-hat-enterprise-linux-8-cve-schema.json\n  - type: JSONStructure\n    url: json-structure/red-hat-enterprise-linux-8-cve-structure.json\n  - type: SpectralRuleset\n    url: rules/red-hat-enterprise-linux-8-rules.yml\n  - type: Vocabulary\n    url: vocabulary/red-hat-enterprise-linux-8-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ninclude: []\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/red-hat-enterprise-linux-8/refs/heads/main/apis.yml
tags:
- Enterprise
- Linux
- Operating System
- Red Hat
- RHEL
url: https://raw.githubusercontent.com/api-evangelist/red-hat-enterprise-linux-8/refs/heads/main/apis.yml
use_cases: []
---
