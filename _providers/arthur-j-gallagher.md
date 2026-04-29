---
api_count: 2
api_specs:
- filename: gallagher-command-centre-api.yml
  format: yaml
  label: Gallagher Command Centre REST API
  slug: command-centre-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/arthur-j-gallagher/refs/heads/main/openapi/gallagher-command-centre-api.yml
apis:
- description: REST API providing HTTP functions to query and integrate with the Gallagher Command Centre physical security platform. Enables third-party systems to interact with access control, alarm monitoring, vi
  name: Gallagher Command Centre REST API
  slug: command-centre-api
- description: API for integrating with Gallagher Bassett claims management services. Gallagher Bassett is a global third-party claims administrator and subsidiary of Arthur J. Gallagher, providing workers compensat
  name: Gallagher Bassett Claims Management API
  slug: gallagher-bassett-api
common:
- title: Arthur J. Gallagher Website
  type: Portal
  url: https://www.ajg.com/
- title: Gallagher Security Developer Docs
  type: Documentation
  url: https://gallaghersecurity.github.io/
- title: Gallagher Bassett Developer Portal
  type: Portal
  url: https://developer.gallagherbassett.com/
- title: Gallagher Security GitHub
  type: GitHubOrganization
  url: https://github.com/GallagherSecurity
created: '2025-03-01'
description: Arthur J. Gallagher & Co. is a global insurance brokerage, risk management, and consulting firm headquartered in Rolling Meadows, Illinois. The company provides insurance brokerage, risk management, employee benefits, and retirement services to clients worldwide. Its subsidiaries include Gallagher Security (which offers the Command Centre REST API for physical security integration) and Gallagher Bassett (which offers claims management APIs for third-party claims administration). Arthur J. Gallagher serves clients in over 130 countries through its international network of brokers and offices.
features:
- description: Full REST API for integrating with Gallagher's Command Centre physical security system, enabling access control, alarm management, visitor tracking, and event monitoring from third-party applications.
  name: Command Centre REST API
- description: Internet-based secure connectivity to Command Centre servers, enabling remote integration without VPN through the Gallagher Cloud API Gateway.
  name: Cloud API Gateway
- description: SDK for developing mobile applications that connect to Gallagher Command Centre for access control, including code samples and technical guides.
  name: Mobile Connect SDK
- description: Gallagher Bassett API for programmatic integration with third-party claims administration workflows including claim submission, status tracking, and reporting.
  name: Claims Management API
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Formal partner program for companies integrating with Command Centre, providing access to proprietary technology resources, software licenses, and technical support.
  name: Gallagher Security Technology Partner Program
- description: Third-party administrators and enterprise clients integrate with Gallagher Bassett for outsourced claims management workflows.
  name: Gallagher Bassett Claims Administration
layout: provider
modified: '2026-04-19'
name: Arthur J. Gallagher
skills: []
slug: arthur-j-gallagher
solutions: []
source_filename: apis.yml
source_yaml: "aid: arthur-j-gallagher\nname: Arthur J. Gallagher\ndescription: >-\n  Arthur J. Gallagher & Co. is a global insurance brokerage, risk management,\n  and consulting firm headquartered in Rolling Meadows, Illinois. The company\n  provides insurance brokerage, risk management, employee benefits, and\n  retirement services to clients worldwide. Its subsidiaries include Gallagher\n  Security (which offers the Command Centre REST API for physical security\n  integration) and Gallagher Bassett (which offers claims management APIs for\n  third-party claims administration). Arthur J. Gallagher serves clients in\n  over 130 countries through its international network of brokers and offices.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/arthur-j-gallagher/refs/heads/main/apis.yml\ncreated: '2025-03-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntype: Index\ntags:\n  - Insurance\n\
  \  - Brokerage\n  - Risk Management\n  - Claims Management\n  - Security\n  - Benefits\napis:\n  - aid: arthur-j-gallagher:command-centre-api\n    name: Gallagher Command Centre REST API\n    description: >-\n      REST API providing HTTP functions to query and integrate with the\n      Gallagher Command Centre physical security platform. Enables third-party\n      systems to interact with access control, alarm monitoring, visitor\n      management, and site management features. Supports on-premise and cloud\n      gateway connectivity since version 8.60.\n    humanURL: https://gallaghersecurity.github.io/\n    baseURL: https://localhost:8904/api\n    tags:\n      - Access Control\n      - Security\n      - Alarms\n      - Integration\n      - Physical Security\n    properties:\n      - type: Documentation\n        url: https://gallaghersecurity.github.io/\n      - type: OpenAPI\n        url: openapi/gallagher-command-centre-api.yml\n      - type: GitHubRepository\n        url: https://github.com/GallagherSecurity/cc-rest-docs\n\
  \  - aid: arthur-j-gallagher:gallagher-bassett-api\n    name: Gallagher Bassett Claims Management API\n    description: >-\n      API for integrating with Gallagher Bassett claims management services.\n      Gallagher Bassett is a global third-party claims administrator and\n      subsidiary of Arthur J. Gallagher, providing workers compensation,\n      liability, property, and disability claims management.\n    humanURL: https://developer.gallagherbassett.com/\n    baseURL: https://api.gallagherbassett.com\n    tags:\n      - Claims\n      - Insurance\n      - Risk Management\n      - Workers Compensation\n    properties:\n      - type: Documentation\n        url: https://developer.gallagherbassett.com/\ncommon:\n  - type: Portal\n    url: https://www.ajg.com/\n    title: Arthur J. Gallagher Website\n  - type: Documentation\n    url: https://gallaghersecurity.github.io/\n    title: Gallagher Security Developer Docs\n  - type: Portal\n    url: https://developer.gallagherbassett.com/\n\
  \    title: Gallagher Bassett Developer Portal\n  - type: GitHubOrganization\n    url: https://github.com/GallagherSecurity\n    title: Gallagher Security GitHub\n  - type: Features\n    data:\n      - name: Command Centre REST API\n        description: >-\n          Full REST API for integrating with Gallagher's Command Centre physical\n          security system, enabling access control, alarm management, visitor\n          tracking, and event monitoring from third-party applications.\n      - name: Cloud API Gateway\n        description: >-\n          Internet-based secure connectivity to Command Centre servers, enabling\n          remote integration without VPN through the Gallagher Cloud API Gateway.\n      - name: Mobile Connect SDK\n        description: >-\n          SDK for developing mobile applications that connect to Gallagher\n          Command Centre for access control, including code samples and\n          technical guides.\n      - name: Claims Management API\n        description:\
  \ >-\n          Gallagher Bassett API for programmatic integration with third-party\n          claims administration workflows including claim submission, status\n          tracking, and reporting.\n  - type: UseCases\n    data:\n      - name: Physical Security Integration\n        description: >-\n          Technology partners integrate Command Centre REST API to build\n          visitor management systems, CCTV integrations, and security operations\n          center dashboards.\n      - name: Access Control Automation\n        description: >-\n          Corporate IT teams integrate access control with HR systems to\n          automatically provision and deprovision employee badge access based\n          on employment status changes.\n      - name: Claims Processing Integration\n        description: >-\n          Enterprise clients integrate Gallagher Bassett's claims API with their\n          ERP and HR systems to automate workers compensation and liability claims\n          submission\
  \ and tracking.\n      - name: Incident Response\n        description: >-\n          Security operations teams use the Command Centre API to correlate\n          access events with alarm triggers for automated incident response\n          and reporting.\n  - type: Integrations\n    data:\n      - name: Gallagher Security Technology Partner Program\n        description: >-\n          Formal partner program for companies integrating with Command Centre,\n          providing access to proprietary technology resources, software licenses,\n          and technical support.\n      - name: Gallagher Bassett Claims Administration\n        description: >-\n          Third-party administrators and enterprise clients integrate with\n          Gallagher Bassett for outsourced claims management workflows.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/arthur-j-gallagher/refs/heads/main/apis.yml
tags:
- Insurance
- Brokerage
- Risk Management
- Claims Management
- Security
- Benefits
url: https://raw.githubusercontent.com/api-evangelist/arthur-j-gallagher/refs/heads/main/apis.yml
use_cases:
- description: Technology partners integrate Command Centre REST API to build visitor management systems, CCTV integrations, and security operations center dashboards.
  name: Physical Security Integration
- description: Corporate IT teams integrate access control with HR systems to automatically provision and deprovision employee badge access based on employment status changes.
  name: Access Control Automation
- description: Enterprise clients integrate Gallagher Bassett's claims API with their ERP and HR systems to automate workers compensation and liability claims submission and tracking.
  name: Claims Processing Integration
- description: Security operations teams use the Command Centre API to correlate access events with alarm triggers for automated incident response and reporting.
  name: Incident Response
---
