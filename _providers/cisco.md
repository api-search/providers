---
api_count: 8
apis:
- description: RESTful API for managing Cisco Meraki cloud-managed networking devices including wireless access points, switches, security appliances, and cameras. Supports network configuration, monitoring, and aut
  name: Cisco Meraki Dashboard API
  slug: meraki-api
- description: REST API for Webex collaboration platform enabling messaging, meeting management, device control, and administration. Supports bots, integrations, and embedded apps for extending Webex functionality.
  name: Cisco Webex API
  slug: webex-api
- description: 'REST API for Cisco Catalyst Center (formerly DNA Center), providing intent-based networking capabilities including network design, provisioning, assurance, and policy management for enterprise campus '
  name: Cisco Catalyst Center API
  slug: catalyst-center-api
- description: REST API for Cisco Application Centric Infrastructure (ACI) providing programmable access to data center network fabric configuration, policy management, and monitoring through the APIC controller.
  name: Cisco ACI API
  slug: aci-api
- description: REST API for Cisco Identity Services Engine (ISE) enabling network access policy management, guest services, BYOD onboarding, and security group administration for zero-trust network access.
  name: Cisco ISE API
  slug: ise-api
- description: REST API for Cisco Intersight cloud operations platform providing infrastructure management, workload optimization, and lifecycle automation for Cisco UCS, HyperFlex, and third-party infrastructure.
  name: Cisco Intersight API
  slug: intersight-api
- description: REST API for Cisco SD-WAN (formerly Viptela) providing programmatic access to WAN edge device management, policy configuration, monitoring, and analytics through the vManage controller.
  name: Cisco SD-WAN API
  slug: sdwan-api
- description: REST API for Cisco ThousandEyes digital experience monitoring platform, providing access to network, application, and internet visibility data for monitoring end-to-end digital experiences.
  name: Cisco ThousandEyes API
  slug: thousandeyes-api
capabilities:
- description: Unified network management workflow combining Meraki, Catalyst Center, and SD-WAN APIs for network administrators.
  name: Cisco Network Management
  slug: network-management
common:
- title: ''
  type: Portal
  url: https://developer.cisco.com/
- title: ''
  type: Documentation
  url: https://developer.cisco.com/docs/
- title: ''
  type: GettingStarted
  url: https://developer.cisco.com/learning/
- title: ''
  type: Blog
  url: https://blogs.cisco.com/developer
- title: ''
  type: GitHubOrganization
  url: https://github.com/CiscoDevNet
- title: ''
  type: Support
  url: https://developer.cisco.com/site/support/
- title: ''
  type: TermsOfService
  url: https://www.cisco.com/c/en/us/about/legal/cloud-and-software.html
- title: ''
  type: PrivacyPolicy
  url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html
- title: ''
  type: Sandbox
  url: https://developer.cisco.com/site/sandbox/
- title: ''
  type: Training
  url: https://developer.cisco.com/certification/
- title: ''
  type: YouTube
  url: https://www.youtube.com/ciscodevnet
- title: ''
  type: X
  url: https://twitter.com/CiscoDevNet
- title: ''
  type: StackOverflow
  url: https://stackoverflow.com/questions/tagged/cisco
created: '2024-01-01'
description: Cisco provides a comprehensive suite of APIs across its networking, security, collaboration, and cloud infrastructure platforms. Through Cisco DevNet, developers can access REST APIs, SDKs, and developer tools for Meraki, Webex, Catalyst Center, ACI, ISE, Intersight, ThousandEyes, SD-WAN, and other Cisco products to automate network operations, build integrations, and extend platform capabilities.
features:
- description: Automate network device configuration, provisioning, and management across campus, branch, and data center environments.
  name: Network Automation
- description: Define business intent and let the network translate it into device configurations automatically.
  name: Intent-Based Networking
- description: Manage distributed networks from the cloud with Meraki APIs for simplified operations.
  name: Cloud-Managed Networking
- description: Monitor end-to-end digital experiences with ThousandEyes for network, application, and internet visibility.
  name: Digital Experience Monitoring
- description: Implement zero-trust network access policies with ISE APIs for identity-based segmentation.
  name: Zero Trust Security
- description: Define and manage network infrastructure programmatically using APIs and configuration management tools.
  name: Infrastructure as Code
image: /assets/icons/cisco.png
integrations:
- description: Network automation modules for Cisco platforms including IOS, NX-OS, ACI, and Meraki.
  name: Ansible
- description: Terraform providers for Cisco ACI, Intersight, Meraki, and other platforms for infrastructure as code.
  name: Terraform
- description: ITSM integration for automated incident management and change control with Cisco platforms.
  name: ServiceNow
- description: Security and network analytics integration for log aggregation and threat detection.
  name: Splunk
- description: Python SDKs and libraries for all major Cisco platforms including Meraki, Webex, and ACI.
  name: Python
jsonld:
- class_count: 4
  name: Cisco Context
  property_count: 14
  slug: cisco-context
layout: provider
modified: '2026-04-18'
name: Cisco
rules:
- name: Cisco API Rules
  rule_count: 12
  severity_counts:
    error: 5
    hint: 0
    info: 1
    warn: 6
  slug: cisco-spectral-rules
skills: []
slug: cisco
solutions: []
source_filename: apis.yml
source_yaml: "aid: cisco\nname: Cisco\ndescription: >-\n  Cisco provides a comprehensive suite of APIs across its networking, security,\n  collaboration, and cloud infrastructure platforms. Through Cisco DevNet, developers\n  can access REST APIs, SDKs, and developer tools for Meraki, Webex, Catalyst Center,\n  ACI, ISE, Intersight, ThousandEyes, SD-WAN, and other Cisco products to automate\n  network operations, build integrations, and extend platform capabilities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/cisco/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Collaboration\n  - Enterprise\n  - Networking\n  - Security\n  - SD-WAN\napis:\n  - aid: cisco:meraki-api\n    name: Cisco Meraki Dashboard API\n    description: >-\n      RESTful API for managing Cisco Meraki cloud-managed networking devices including\n\
  \      wireless access points, switches, security appliances, and cameras. Supports\n      network configuration, monitoring, and automation at scale.\n    humanURL: https://developer.cisco.com/meraki/api-v1/\n    baseURL: https://api.meraki.com/api/v1\n    tags:\n      - Cloud Managed\n      - Meraki\n      - Network Management\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/meraki/api-v1/\n      - type: APIReference\n        url: https://developer.cisco.com/meraki/api-v1/\n      - type: GettingStarted\n        url: https://developer.cisco.com/meraki/api-v1/getting-started/\n      - type: Authentication\n        url: https://developer.cisco.com/meraki/api-v1/#!authorization\n  - aid: cisco:webex-api\n    name: Cisco Webex API\n    description: >-\n      REST API for Webex collaboration platform enabling messaging, meeting management,\n      device control, and administration. Supports bots, integrations, and embedded\n      apps for\
  \ extending Webex functionality.\n    humanURL: https://developer.webex.com/docs/getting-started\n    baseURL: https://webexapis.com/v1\n    tags:\n      - Collaboration\n      - Meetings\n      - Messaging\n      - REST\n      - Webex\n    properties:\n      - type: Documentation\n        url: https://developer.webex.com/docs/getting-started\n      - type: APIReference\n        url: https://developer.webex.com/docs/api/getting-started\n      - type: Authentication\n        url: https://developer.webex.com/docs/integrations\n  - aid: cisco:catalyst-center-api\n    name: Cisco Catalyst Center API\n    description: >-\n      REST API for Cisco Catalyst Center (formerly DNA Center), providing intent-based\n      networking capabilities including network design, provisioning, assurance, and\n      policy management for enterprise campus and branch networks.\n    humanURL: https://developer.cisco.com/docs/dna-center/\n    baseURL: https://sandboxdnac.cisco.com/dna\n    tags:\n      - Catalyst\
  \ Center\n      - Intent-Based Networking\n      - Network Automation\n      - REST\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/dna-center/\n      - type: APIReference\n        url: https://developer.cisco.com/docs/dna-center/api/\n  - aid: cisco:aci-api\n    name: Cisco ACI API\n    description: >-\n      REST API for Cisco Application Centric Infrastructure (ACI) providing programmable\n      access to data center network fabric configuration, policy management, and\n      monitoring through the APIC controller.\n    humanURL: https://developer.cisco.com/docs/aci/\n    baseURL: https://apic-ip/api\n    tags:\n      - ACI\n      - Data Center\n      - Fabric\n      - REST\n      - SDN\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/aci/\n      - type: APIReference\n        url: https://developer.cisco.com/docs/aci/apic-rest-api-user-guide/\n  - aid: cisco:ise-api\n    name: Cisco ISE API\n  \
  \  description: >-\n      REST API for Cisco Identity Services Engine (ISE) enabling network access policy\n      management, guest services, BYOD onboarding, and security group administration\n      for zero-trust network access.\n    humanURL: https://developer.cisco.com/docs/identity-services-engine/\n    baseURL: https://ise-server/ers\n    tags:\n      - Identity\n      - ISE\n      - Network Access\n      - REST\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/identity-services-engine/\n      - type: APIReference\n        url: https://developer.cisco.com/docs/identity-services-engine/ers-api-reference/\n  - aid: cisco:intersight-api\n    name: Cisco Intersight API\n    description: >-\n      REST API for Cisco Intersight cloud operations platform providing infrastructure\n      management, workload optimization, and lifecycle automation for Cisco UCS,\n      HyperFlex, and third-party infrastructure.\n    humanURL: https://intersight.com/apidocs/introduction/overview/\n\
  \    baseURL: https://intersight.com/api/v1\n    tags:\n      - Cloud Operations\n      - Infrastructure\n      - Intersight\n      - REST\n    properties:\n      - type: Documentation\n        url: https://intersight.com/apidocs/introduction/overview/\n      - type: APIReference\n        url: https://intersight.com/apidocs/apirefs/\n  - aid: cisco:sdwan-api\n    name: Cisco SD-WAN API\n    description: >-\n      REST API for Cisco SD-WAN (formerly Viptela) providing programmatic access to\n      WAN edge device management, policy configuration, monitoring, and analytics\n      through the vManage controller.\n    humanURL: https://developer.cisco.com/docs/sdwan/\n    baseURL: https://vmanage-ip/dataservice\n    tags:\n      - REST\n      - SD-WAN\n      - WAN\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/sdwan/\n      - type: APIReference\n        url: https://developer.cisco.com/docs/sdwan/api-reference/\n  - aid: cisco:thousandeyes-api\n\
  \    name: Cisco ThousandEyes API\n    description: >-\n      REST API for Cisco ThousandEyes digital experience monitoring platform,\n      providing access to network, application, and internet visibility data for\n      monitoring end-to-end digital experiences.\n    humanURL: https://developer.cisco.com/docs/thousandeyes/\n    baseURL: https://api.thousandeyes.com/v7\n    tags:\n      - Digital Experience\n      - Monitoring\n      - Network Visibility\n      - REST\n      - ThousandEyes\n    properties:\n      - type: Documentation\n        url: https://developer.cisco.com/docs/thousandeyes/\n      - type: APIReference\n        url: https://developer.cisco.com/docs/thousandeyes/api-reference/\ncommon:\n  - type: Portal\n    url: https://developer.cisco.com/\n  - type: Documentation\n    url: https://developer.cisco.com/docs/\n  - type: GettingStarted\n    url: https://developer.cisco.com/learning/\n  - type: Blog\n    url: https://blogs.cisco.com/developer\n  - type: GitHubOrganization\n\
  \    url: https://github.com/CiscoDevNet\n  - type: Support\n    url: https://developer.cisco.com/site/support/\n  - type: TermsOfService\n    url: https://www.cisco.com/c/en/us/about/legal/cloud-and-software.html\n  - type: PrivacyPolicy\n    url: https://www.cisco.com/c/en/us/about/legal/privacy-full.html\n  - type: Sandbox\n    url: https://developer.cisco.com/site/sandbox/\n  - type: Training\n    url: https://developer.cisco.com/certification/\n  - type: YouTube\n    url: https://www.youtube.com/ciscodevnet\n  - type: X\n    url: https://twitter.com/CiscoDevNet\n  - type: StackOverflow\n    url: https://stackoverflow.com/questions/tagged/cisco\n  - type: Features\n    data:\n      - name: Network Automation\n        description: Automate network device configuration, provisioning, and management across campus, branch, and data center environments.\n      - name: Intent-Based Networking\n        description: Define business intent and let the network translate it into device configurations\
  \ automatically.\n      - name: Cloud-Managed Networking\n        description: Manage distributed networks from the cloud with Meraki APIs for simplified operations.\n      - name: Digital Experience Monitoring\n        description: Monitor end-to-end digital experiences with ThousandEyes for network, application, and internet visibility.\n      - name: Zero Trust Security\n        description: Implement zero-trust network access policies with ISE APIs for identity-based segmentation.\n      - name: Infrastructure as Code\n        description: Define and manage network infrastructure programmatically using APIs and configuration management tools.\n  - type: UseCases\n    data:\n      - name: Network Configuration Management\n        description: Automate network device configuration changes across thousands of devices using APIs and templates.\n      - name: Security Policy Automation\n        description: Programmatically manage access control policies, security groups, and compliance\
  \ enforcement.\n      - name: Collaboration Integration\n        description: Build bots, integrations, and custom applications on the Webex platform for team collaboration.\n      - name: Cloud Infrastructure Management\n        description: Manage hybrid cloud infrastructure with Intersight APIs for lifecycle management and workload optimization.\n      - name: Network Monitoring and Analytics\n        description: Collect and analyze network telemetry data for performance monitoring and troubleshooting.\n  - type: Integrations\n    data:\n      - name: Ansible\n        description: Network automation modules for Cisco platforms including IOS, NX-OS, ACI, and Meraki.\n      - name: Terraform\n        description: Terraform providers for Cisco ACI, Intersight, Meraki, and other platforms for infrastructure as code.\n      - name: ServiceNow\n        description: ITSM integration for automated incident management and change control with Cisco platforms.\n      - name: Splunk\n        description:\
  \ Security and network analytics integration for log aggregation and threat detection.\n      - name: Python\n        description: Python SDKs and libraries for all major Cisco platforms including Meraki, Webex, and ACI.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/cisco/refs/heads/main/apis.yml
tags:
- Collaboration
- Enterprise
- Networking
- Security
- SD-WAN
url: https://raw.githubusercontent.com/api-evangelist/cisco/refs/heads/main/apis.yml
use_cases:
- description: Automate network device configuration changes across thousands of devices using APIs and templates.
  name: Network Configuration Management
- description: Programmatically manage access control policies, security groups, and compliance enforcement.
  name: Security Policy Automation
- description: Build bots, integrations, and custom applications on the Webex platform for team collaboration.
  name: Collaboration Integration
- description: Manage hybrid cloud infrastructure with Intersight APIs for lifecycle management and workload optimization.
  name: Cloud Infrastructure Management
- description: Collect and analyze network telemetry data for performance monitoring and troubleshooting.
  name: Network Monitoring and Analytics
---
