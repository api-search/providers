---
api_count: 6
api_specs:
- filename: swagger.json
  format: json
  label: Tufin SecureTrack API
  slug: ''
  spec_type: OpenAPI
  url: https://securetrack.example.com/securetrack/api/swagger.json
- filename: swagger.json
  format: json
  label: Tufin SecureChange API
  slug: ''
  spec_type: OpenAPI
  url: https://securechange.example.com/securechangeworkflow/api/swagger.json
apis:
- description: API for querying network topology, security policies, and performing policy analysis across multi-vendor firewall infrastructure.
  name: Tufin SecureTrack API
  slug: ''
- description: API for automating security policy change workflows, approvals, and implementation across network infrastructure.
  name: Tufin SecureChange API
  slug: ''
- description: API for application-centric security policy management and micro-segmentation.
  name: Tufin SecureApp API
  slug: ''
- description: Unified REST API for the Tufin Orchestration Suite providing comprehensive security policy lifecycle management.
  name: Tufin Orchestration Suite REST API
  slug: ''
- description: GraphQL API for the Tufin Orchestration Suite providing flexible querying capabilities for security policy data, network topology, and compliance information. Uses OAuth2 authentication and supports c
  name: Tufin SecureTrack GraphQL API
  slug: ''
- description: REST API for Tufin SecureCloud, the cloud-native security policy management platform. Provides endpoints for managing cloud accounts, applications, assets, Kubernetes clusters, and security policies a
  name: Tufin SecureCloud API
  slug: ''
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
  type: Getting Started
  url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm
- title: ''
  type: Community
  url: https://community.tufin.com/
- title: ''
  type: GitHub Organization
  url: https://github.com/Tufin
- title: ''
  type: SDKs
  url: https://gitlab.com/tufinps/pytos2-ce
- title: ''
  type: PostmanCollection
  url: https://github.com/Tufin/postman
- title: ''
  type: Sign Up
  url: https://www.tufin.com/demo
- title: ''
  type: Videos
  url: https://www.tufin.com/resources/type/videos
created: '2025'
description: Tufin provides security policy orchestration solutions for managing network security policies across hybrid cloud environments, including firewalls, SDN, and cloud security controls.
features: []
image: https://www.tufin.com/themes/custom/tufin/logo.svg
integrations: []
layout: provider
modified: '2026-03-16'
name: Tufin
skills: []
slug: tufin
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Tufin\ndescription: Tufin provides security policy orchestration solutions for managing network security policies across hybrid cloud environments, including firewalls, SDN, and cloud security controls.\nimage: https://www.tufin.com/themes/custom/tufin/logo.svg\nurl: https://www.tufin.com\ncreated: '2025'\nmodified: '2026-03-16'\nspecificationVersion: '0.18'\ntags:\n  - Cloud Security\n  - Compliance\n  - Firewall Management\n  - Network Security\n  - Risk Management\n  - Security Policy Management\napis:\n  - name: Tufin SecureTrack API\n    description: >-\n      API for querying network topology, security policies, and performing policy\n      analysis across multi-vendor firewall infrastructure.\n    image: https://www.tufin.com/themes/custom/tufin/logo.svg\n    humanURL: https://www.tufin.com/products/securetrack\n    baseURL: https://securetrack.example.com/securetrack/api\n    tags:\n      - Compliance\n      - Firewall Rules\n      - Network Topology\n      -\
  \ Policy Analysis\n    properties:\n      - type: Documentation\n        url: https://forum.tufin.com/support/kc/securetrack/Content/Suite/API/index.htm\n      - type: OpenAPI\n        url: https://securetrack.example.com/securetrack/api/swagger.json\n      - type: Authentication\n        url: https://forum.tufin.com/support/kc/securetrack/Content/Suite/API/Authentication.htm\n      - type: Reference\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4420.htm\n      - type: Getting Started\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm\n  - name: Tufin SecureChange API\n    description: >-\n      API for automating security policy change workflows, approvals, and implementation\n      across network infrastructure.\n    image: https://www.tufin.com/themes/custom/tufin/logo.svg\n    humanURL: https://www.tufin.com/products/securechange\n    baseURL: https://securechange.example.com/securechangeworkflow/api\n    tags:\n \
  \     - Approvals\n      - Change Management\n      - Policy Changes\n      - Workflow Automation\n    properties:\n      - type: Documentation\n        url: https://forum.tufin.com/support/kc/securechange/Content/Suite/API/index.htm\n      - type: OpenAPI\n        url: https://securechange.example.com/securechangeworkflow/api/swagger.json\n      - type: Reference\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/12309.htm\n      - type: Authentication\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm\n  - name: Tufin SecureApp API\n    description: >-\n      API for application-centric security policy management and micro-segmentation.\n    image: https://www.tufin.com/themes/custom/tufin/logo.svg\n    humanURL: https://www.tufin.com/products/secureapp\n    baseURL: https://secureapp.example.com/api\n    tags:\n      - Application Security\n      - Micro-Segmentation\n      - Zero Trust\n    properties:\n      - type: Documentation\n\
  \        url: https://forum.tufin.com/support/kc/secureapp/\n      - type: Reference\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/6481.htm\n  - name: Tufin Orchestration Suite REST API\n    description: >-\n      Unified REST API for the Tufin Orchestration Suite providing comprehensive security\n      policy lifecycle management.\n    image: https://www.tufin.com/themes/custom/tufin/logo.svg\n    humanURL: https://www.tufin.com/products/tufin-orchestration-suite\n    baseURL: https://tufin.example.com/api/v1\n    tags:\n      - Automation\n      - Orchestration\n      - Policy Management\n    properties:\n      - type: Documentation\n        url: https://forum.tufin.com/support/kc\n      - type: Reference\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/securetrack_api.htm\n      - type: Getting Started\n        url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm\n      - type: Authentication\n   \
  \     url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm\n  - name: Tufin SecureTrack GraphQL API\n    description: >-\n      GraphQL API for the Tufin Orchestration Suite providing flexible querying\n      capabilities for security policy data, network topology, and compliance\n      information. Uses OAuth2 authentication and supports complex nested queries\n      across SecureTrack resources.\n    image: https://www.tufin.com/themes/custom/tufin/logo.svg\n    humanURL: https://forum.tufin.com/support/kc/latest/Content/ST2/API/API_Introduction.htm\n    baseURL: https://{tos_ip}/v2/api/sync/graphql\n    tags:\n      - GraphQL\n      - Network Topology\n      - Policy Analysis\n      - Security Data\n    properties:\n      - type: Documentation\n        url: https://forum.tufin.com/support/kc/latest/Content/ST2/API/API_Introduction.htm\n      - type: Authentication\n        url: https://forum.tufin.com/support/kc/latest/Content/ST2/API/OAuth2.htm\n  - name: Tufin\
  \ SecureCloud API\n    description: >-\n      REST API for Tufin SecureCloud, the cloud-native security policy management\n      platform. Provides endpoints for managing cloud accounts, applications,\n      assets, Kubernetes clusters, and security policies across AWS, Azure, and\n      GCP environments.\n    image: https://www.tufin.com/themes/custom/tufin/logo.svg\n    humanURL: https://www.tufin.com/tufin-orchestration-suite/securecloud\n    baseURL: https://{account}.securecloud.tufin.io/api/v1\n    tags:\n      - Cloud Security\n      - Kubernetes\n      - Multi-Cloud\n      - Policy Management\n    properties:\n      - type: Documentation\n        url: https://forum.tufin.com/support/kc/securecloud/\n      - type: Reference\n        url: https://securecloud.tufin.io/api-documentation/index.html\ncommon:\n  - type: Portal\n    url: https://forum.tufin.com/\n  - type: Support\n    url: https://www.tufin.com/support\n  - type: Documentation\n    url: https://forum.tufin.com/support/kc\n\
  \  - type: Blog\n    url: https://www.tufin.com/blog\n  - type: Login\n    url: https://portal.tufin.io/\n  - type: Contact\n    url: https://www.tufin.com/company/contact-us\n  - type: Privacy Policy\n    url: https://www.tufin.com/privacy-policy\n  - type: Terms of Service\n    url: https://www.tufin.com/terms-of-use\n  - type: Website\n    url: https://www.tufin.com\n  - type: Getting Started\n    url: https://forum.tufin.com/support/kc/latest/Content/Suite/RESTAPI/4423.htm\n  - type: Community\n    url: https://community.tufin.com/\n  - type: GitHub Organization\n    url: https://github.com/Tufin\n  - type: SDKs\n    url: https://gitlab.com/tufinps/pytos2-ce\n  - type: PostmanCollection\n    url: https://github.com/Tufin/postman\n  - type: Sign Up\n    url: https://www.tufin.com/demo\n  - type: Videos\n    url: https://www.tufin.com/resources/type/videos\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tufin/refs/heads/main/apis.yml
tags:
- Cloud Security
- Compliance
- Firewall Management
- Network Security
- Risk Management
- Security Policy Management
url: https://www.tufin.com
use_cases: []
---
