---
api_count: 5
api_specs:
- filename: tufin-securetrack-openapi.yml
  format: yaml
  label: Tufin SecureTrack API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tufin/refs/heads/main/openapi/tufin-securetrack-openapi.yml
- filename: tufin-securechange-openapi.yml
  format: yaml
  label: Tufin SecureChange API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tufin/refs/heads/main/openapi/tufin-securechange-openapi.yml
apis:
- description: The SecureTrack REST API enables programmatic access to Tufin's network security policy management platform. It supports querying network devices and firewall rules, analyzing network topology and pat
  name: Tufin SecureTrack API
  slug: ''
- description: The SecureChange REST API automates security policy change workflows, enabling programmatic submission and management of access request tickets, approval workflows, and change implementation across ne
  name: Tufin SecureChange API
  slug: ''
- description: API for application-centric security policy management and micro-segmentation. SecureApp enables teams to manage security policies at the application level, define connectivity requirements, and autom
  name: Tufin SecureApp API
  slug: ''
- description: GraphQL API for the Tufin Orchestration Suite providing flexible querying capabilities for security policy data, network topology, and compliance information. Uses OAuth2 authentication and supports c
  name: Tufin SecureTrack GraphQL API
  slug: ''
- description: REST API for Tufin SecureCloud, the cloud-native security policy management platform. Provides endpoints for managing cloud accounts, applications, assets, Kubernetes clusters, and security policies a
  name: Tufin SecureCloud API
  slug: ''
capabilities:
- description: Unified workflow capability combining Tufin SecureTrack and SecureChange for end-to-end network security policy lifecycle management. Enables network security engineers and SOC analysts to analyze top
  name: Tufin Network Security Policy Management
  slug: network-security-policy-management
common:
- title: ''
  type: Portal
  url: https://forum.tufin.com/
- title: ''
  type: Support
  url: https://www.tufin.com/support
- title: ''
  type: Documentation
  url: https://forum.tufin.com/support/kc
- title: ''
  type: Blog
  url: https://www.tufin.com/blog
- title: ''
  type: Login
  url: https://portal.tufin.io/
- title: ''
  type: Contact
  url: https://www.tufin.com/company/contact-us
- title: ''
  type: Privacy Policy
  url: https://www.tufin.com/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.tufin.com/terms-of-use
- title: ''
  type: Website
  url: https://www.tufin.com
- title: ''
  type: GettingStarted
  url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm
- title: ''
  type: Community
  url: https://community.tufin.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/Tufin
- title: ''
  type: SDK
  url: https://gitlab.com/tufinps/pytos2-ce
- title: ''
  type: SDK
  url: https://github.com/Tufin/pytos
- title: ''
  type: PostmanCollection
  url: https://github.com/Tufin/postman
- title: ''
  type: Sign Up
  url: https://www.tufin.com/demo
- title: ''
  type: Videos
  url: https://www.tufin.com/resources/type/videos
- title: ''
  type: Developers
  url: https://www.tufin.com/developers
- title: ''
  type: OpenAPI
  url: openapi/tufin-securetrack-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/tufin-securechange-openapi.yml
- title: ''
  type: Vocabulary
  url: vocabulary/tufin-vocabulary.yml
- title: ''
  type: JSON-LD
  url: json-ld/tufin-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/tufin-device-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/tufin-ticket-schema.json
created: '2025'
description: Tufin provides security policy orchestration solutions for managing network security policies across hybrid cloud environments, including firewalls, SDN, and cloud security controls. The Tufin Orchestration Suite (TOS) includes SecureTrack for network topology and policy analysis, SecureChange for automated policy change workflows, SecureApp for application-centric policy management, and SecureCloud for cloud-native security posture management. Tufin offers comprehensive REST APIs and GraphQL APIs for integrating with ITSM, SIEM, and other security tools.
features: []
image: https://www.tufin.com/themes/custom/tufin/logo.svg
integrations: []
jsonld:
- class_count: 0
  name: Tufin Context
  property_count: 6
  slug: tufin-context
layout: provider
modified: '2026-05-03'
name: Tufin
rules:
- name: Tufin API Rules
  rule_count: 11
  severity_counts:
    error: 2
    hint: 0
    info: 1
    warn: 8
  slug: tufin-securetrack-rules
skills: []
slug: tufin
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Tufin\ndescription: >-\n  Tufin provides security policy orchestration solutions for managing network security policies\n  across hybrid cloud environments, including firewalls, SDN, and cloud security controls.\n  The Tufin Orchestration Suite (TOS) includes SecureTrack for network topology and policy\n  analysis, SecureChange for automated policy change workflows, SecureApp for application-centric\n  policy management, and SecureCloud for cloud-native security posture management. Tufin offers\n  comprehensive REST APIs and GraphQL APIs for integrating with ITSM, SIEM, and other security tools.\nimage: https://www.tufin.com/themes/custom/tufin/logo.svg\nurl: https://www.tufin.com\ncreated: '2025'\nmodified: '2026-05-03'\nspecificationVersion: '0.18'\ntags:\n  - Cloud Security\n  - Compliance\n  - Firewall Management\n  - Network Security\n  - Network Topology\n  - Policy Orchestration\n  - Risk Management\n  - Security Policy Management\n  - Zero Trust\napis:\n  - name:\
  \ Tufin SecureTrack API\n    description: >-\n      The SecureTrack REST API enables programmatic access to Tufin's network security\n      policy management platform. It supports querying network devices and firewall rules,\n      analyzing network topology and path queries, retrieving policy compliance data,\n      performing risk and cleanup analysis, managing rule documentation and recertification,\n      and searching for network objects, services, and interfaces across multi-vendor\n      firewall infrastructure. Authentication uses HTTP Basic Auth with TOS credentials.\n    image: https://www.tufin.com/themes/custom/tufin/logo.svg\n    humanURL: https://www.tufin.com/products/securetrack\n    baseURL: https://{tos_host}/securetrack/api\n    tags:\n      - Compliance\n      - Firewall Rules\n      - Network Devices\n      - Network Topology\n      - Policy Analysis\n      - Risk Analysis\n    properties:\n      - type: Documentation\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/securetrack_api.htm\n\
  \      - type: SwaggerUI\n        url: https://forum.tufin.com/support/kc/rest-api/R24-1/securetrack/apidoc/\n      - type: Authentication\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm\n      - type: Reference\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4420.htm\n      - type: GettingStarted\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm\n      - type: OpenAPI\n        url: openapi/tufin-securetrack-openapi.yml\n    features:\n      - name: Device and Policy Management\n        description: Retrieve, add, and update firewall devices and security policies across multi-vendor environments.\n      - name: Network Topology Analysis\n        description: Query network paths, retrieve topology maps, and analyze traffic flows across the managed network.\n      - name: Risk and Compliance Analysis\n        description: Identify policy violations, clean up unused rules, and generate\
  \ compliance reports.\n      - name: Rule Search and Documentation\n        description: Search for rules, network objects, and services across all managed devices with full documentation support.\n  - name: Tufin SecureChange API\n    description: >-\n      The SecureChange REST API automates security policy change workflows, enabling programmatic\n      submission and management of access request tickets, approval workflows, and change\n      implementation across network infrastructure. Supports integration with ITSM platforms\n      including ServiceNow, Jira, and Remedy for end-to-end change automation.\n    image: https://www.tufin.com/themes/custom/tufin/logo.svg\n    humanURL: https://www.tufin.com/products/securechange\n    baseURL: https://{tos_host}/securechangeworkflow/api\n    tags:\n      - Approvals\n      - Change Management\n      - ITSM Integration\n      - Policy Changes\n      - Ticketing\n      - Workflow Automation\n    properties:\n      - type: Documentation\n \
  \       url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/12309.htm\n      - type: SwaggerUI\n        url: https://forum.tufin.com/support/kc/rest-api/R24-1/securechangeworkflow/apidoc/\n      - type: Reference\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/12309.htm\n      - type: Authentication\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm\n      - type: OpenAPI\n        url: openapi/tufin-securechange-openapi.yml\n    features:\n      - name: Access Request Tickets\n        description: Create, retrieve, and update security access request tickets programmatically.\n      - name: Workflow Automation\n        description: Automate the full lifecycle of security policy changes from request through approval to implementation.\n      - name: ITSM Integration\n        description: Integrate with ServiceNow, Jira, and other ITSM platforms for unified change management.\n  - name: Tufin SecureApp API\n\
  \    description: >-\n      API for application-centric security policy management and micro-segmentation.\n      SecureApp enables teams to manage security policies at the application level,\n      define connectivity requirements, and automate policy changes for application\n      deployments.\n    image: https://www.tufin.com/themes/custom/tufin/logo.svg\n    humanURL: https://www.tufin.com/products/secureapp\n    baseURL: https://{tos_host}/securechangeworkflow/api\n    tags:\n      - Application Security\n      - Micro-Segmentation\n      - Policy Management\n      - Zero Trust\n    properties:\n      - type: Documentation\n        url: https://forum.tufin.com/support/kc/secureapp/\n      - type: Reference\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/6481.htm\n  - name: Tufin SecureTrack GraphQL API\n    description: >-\n      GraphQL API for the Tufin Orchestration Suite providing flexible querying\n      capabilities for security policy data, network\
  \ topology, and compliance\n      information. Uses OAuth2 authentication and supports complex nested queries\n      across SecureTrack resources including devices, policies, rules, and topology.\n    image: https://www.tufin.com/themes/custom/tufin/logo.svg\n    humanURL: https://forum.tufin.com/support/kc/latest/Content/ST2/API/API_Introduction.htm\n    baseURL: https://{tos_ip}/v2/api/sync/graphql\n    tags:\n      - GraphQL\n      - Network Topology\n      - OAuth2\n      - Policy Analysis\n      - Security Data\n    properties:\n      - type: Documentation\n        url: https://forum.tufin.com/support/kc/latest/Content/ST2/API/API_Introduction.htm\n      - type: Authentication\n        url: https://forum.tufin.com/support/kc/latest/Content/ST2/API/OAuth2.htm\n  - name: Tufin SecureCloud API\n    description: >-\n      REST API for Tufin SecureCloud, the cloud-native security policy management\n      platform. Provides endpoints for managing cloud accounts, applications,\n      assets,\
  \ Kubernetes clusters, and security policies across AWS, Azure, and\n      GCP environments. Enables cloud security posture management (CSPM) and\n      Kubernetes network policy enforcement through API integration.\n    image: https://www.tufin.com/themes/custom/tufin/logo.svg\n    humanURL: https://www.tufin.com/tufin-orchestration-suite/securecloud\n    baseURL: https://{account}.securecloud.tufin.io/api/v1\n    tags:\n      - Cloud Security\n      - CSPM\n      - Kubernetes\n      - Multi-Cloud\n      - Policy Management\n    properties:\n      - type: Documentation\n        url: https://forum.tufin.com/support/kc/securecloud/\n      - type: Reference\n        url: https://securecloud.tufin.io/api-documentation/index.html\ncommon:\n  - type: Portal\n    url: https://forum.tufin.com/\n  - type: Support\n    url: https://www.tufin.com/support\n  - type: Documentation\n    url: https://forum.tufin.com/support/kc\n  - type: Blog\n    url: https://www.tufin.com/blog\n  - type: Login\n \
  \   url: https://portal.tufin.io/\n  - type: Contact\n    url: https://www.tufin.com/company/contact-us\n  - type: Privacy Policy\n    url: https://www.tufin.com/privacy-policy\n  - type: Terms of Service\n    url: https://www.tufin.com/terms-of-use\n  - type: Website\n    url: https://www.tufin.com\n  - type: GettingStarted\n    url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm\n  - type: Community\n    url: https://community.tufin.com/\n  - type: GitHub Organization\n    url: https://github.com/Tufin\n  - type: SDK\n    url: https://gitlab.com/tufinps/pytos2-ce\n  - type: SDK\n    url: https://github.com/Tufin/pytos\n  - type: PostmanCollection\n    url: https://github.com/Tufin/postman\n  - type: Sign Up\n    url: https://www.tufin.com/demo\n  - type: Videos\n    url: https://www.tufin.com/resources/type/videos\n  - type: Developers\n    url: https://www.tufin.com/developers\n  - type: OpenAPI\n    url: openapi/tufin-securetrack-openapi.yml\n  - type: OpenAPI\n\
  \    url: openapi/tufin-securechange-openapi.yml\n  - type: Vocabulary\n    url: vocabulary/tufin-vocabulary.yml\n  - type: JSON-LD\n    url: json-ld/tufin-context.jsonld\n  - type: JSONSchema\n    url: json-schema/tufin-device-schema.json\n  - type: JSONSchema\n    url: json-schema/tufin-ticket-schema.json\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tufin/refs/heads/main/apis.yml
tags:
- Cloud Security
- Compliance
- Firewall Management
- Network Security
- Network Topology
- Policy Orchestration
- Risk Management
- Security Policy Management
- Zero Trust
url: https://www.tufin.com
use_cases: []
---
