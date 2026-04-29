---
api_count: 6
apis:
- description: The Brocade Fabric OS REST API provides a programmable web-service interface for managing Brocade SAN switches across a fabric. It supports YANG-based modules for configuring and monitoring switch res
  name: Brocade Fabric OS REST API
  slug: ''
- description: 'The Brocade SANnav Management Portal REST API provides a programmable web-service interface for accessing and managing the SANnav Management Portal server. REST API services include Login, Discovery, '
  name: Brocade SANnav Management Portal REST API
  slug: ''
- description: The Brocade SANnav Northbound Streaming API enables real-time streaming of SAN telemetry and event data from the SANnav Management Portal to external systems. It provides northbound streaming of fault
  name: Brocade SANnav Northbound Streaming API
  slug: ''
- description: The Brocade Network Advisor REST API provided a web-services interface for configuring and monitoring Brocade SAN switches, including fabric management, topology, zoning, and performance data retrieva
  name: Brocade Network Advisor REST API
  slug: ''
- description: 'The Brocade Workflow Composer was a network automation platform based on StackStorm for event-driven automation and orchestration workflows. The product was transferred to Extreme Networks as part of '
  name: Brocade Workflow Composer API
  slug: ''
- description: 'The Brocade VCS Fabric API provided REST interfaces for Virtual Cluster Switching fabric configuration on Brocade VDX switches. The VCS Fabric product line was transferred to Extreme Networks as part '
  name: Brocade VCS Fabric API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://techdocs.broadcom.com/us/en/fibre-channel-networking.html
- title: ''
  type: Documentation
  url: https://techdocs.broadcom.com/us/en/fibre-channel-networking.html
- title: ''
  type: Getting Started
  url: https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x/v26395730/v24190001.html
- title: ''
  type: Support
  url: https://www.broadcom.com/support/fibre-channel-networking
- title: ''
  type: Website
  url: https://www.broadcom.com/products/fibre-channel-networking
- title: ''
  type: Sign Up
  url: https://www.broadcom.com/support/fibre-channel-networking
- title: ''
  type: Login
  url: https://www.broadcom.com/support/fibre-channel-networking
- title: ''
  type: Terms of Service
  url: https://www.broadcom.com/company/legal/terms-of-use
- title: ''
  type: Privacy Policy
  url: https://www.broadcom.com/company/legal/privacy/policy
- title: ''
  type: Community
  url: https://community.broadcom.com/t5/Fibre-Channel-SAN-Forums/bd-p/fibre
- title: ''
  type: Blog
  url: https://community.broadcom.com/landingpage/brocade-community
- title: ''
  type: GitHub Organization
  url: https://github.com/brocade
- title: ''
  type: SDKs
  url: https://github.com/brocade/pyfos
- title: ''
  type: Change Log
  url: https://www.broadcom.com/support/fibre-channel-networking/eol
created: '2024-01-01'
description: Brocade, now part of Broadcom, provides Fibre Channel networking solutions for storage area networks (SANs). The Brocade portfolio includes SAN switches, directors, Fabric OS software, and the SANnav management platform, all offering REST APIs for programmable management and automation of SAN infrastructure.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Brocade
skills: []
slug: brocade
solutions: []
source_yaml: "name: Brocade\ndescription: >-\n  Brocade, now part of Broadcom, provides Fibre Channel networking solutions\n  for storage area networks (SANs). The Brocade portfolio includes SAN switches,\n  directors, Fabric OS software, and the SANnav management platform, all offering\n  REST APIs for programmable management and automation of SAN infrastructure.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/brocade/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.18'\ntags:\n  - Data Center\n  - Directors\n  - Fibre Channel\n  - Network Automation\n  - Networking\n  - SAN\n  - Storage Area Networks\n  - Switches\napis:\n  - name: Brocade Fabric OS REST API\n    description: >-\n      The Brocade Fabric OS REST API provides a programmable web-service interface\n      for managing Brocade SAN switches across a fabric. It supports YANG-based\n      modules\
  \ for configuring and monitoring switch resources including chassis,\n      ports, zoning, security, logging, MAPS, and Fibre Channel features.\n      Supported on Fabric OS 8.2.0 and later.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x.html\n    baseURL: https://{switch-ip}/rest\n    tags:\n      - Fabric OS\n      - Fibre Channel\n      - Network Management\n      - SAN\n      - Switches\n    properties:\n      - type: Documentation\n        url: https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x.html\n      - type: Reference\n        url: https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/10-0-x.html\n      - type: Authentication\n        url: https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x/v26395730/v24190001.html\n\
  \      - type: Getting Started\n        url: https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x/v26395730/v24190001.html\n      - type: SDKs\n        url: https://github.com/brocade/pyfos\n  - name: Brocade SANnav Management Portal REST API\n    description: >-\n      The Brocade SANnav Management Portal REST API provides a programmable\n      web-service interface for accessing and managing the SANnav Management\n      Portal server. REST API services include Login, Discovery, FCR, Fault,\n      Inventory, Health Summary, User Management, RBAC, Zoning, and Proxy to\n      Fabric OS REST API. SANnav is the successor to Brocade Network Advisor\n      for SAN management.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api/3-0-0x.html\n    baseURL: https://{sannav-host}/external-api/v1\n    tags:\n    \
  \  - Discovery\n      - Fibre Channel\n      - Monitoring\n      - SAN Management\n      - Zoning\n    properties:\n      - type: Documentation\n        url: https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api/3-0-0x.html\n      - type: Reference\n        url: https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api/3-0-0x/SANnav-Overview.html\n      - type: Getting Started\n        url: https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api/3-0-0x/SANnav-Overview.html\n  - name: Brocade SANnav Northbound Streaming API\n    description: >-\n      The Brocade SANnav Northbound Streaming API enables real-time streaming\n      of SAN telemetry and event data from the SANnav Management Portal to\n      external systems. It provides northbound streaming of fault events,\n      performance metrics, and inventory changes for integration with third-party\n      monitoring and\
  \ analytics platforms.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api-and-nb-streaming/2-3-0x.html\n    baseURL: https://{sannav-host}/external-api/v1/stream\n    tags:\n      - Events\n      - Monitoring\n      - SAN Management\n      - Streaming\n      - Telemetry\n    properties:\n      - type: Documentation\n        url: https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api-and-nb-streaming/2-3-0x.html\n      - type: Reference\n        url: https://techdocs.broadcom.com/us/en/fibre-channel-networking/sannav/management-portal-rest-api/2-4-0x/Resources-REST-API/Stream-REST-API/GET--external-api-v1-stream-servers-REST-API.html\n  - name: Brocade Network Advisor REST API\n    description: >-\n      The Brocade Network Advisor REST API provided a web-services interface for\n      configuring and monitoring\
  \ Brocade SAN switches, including fabric management,\n      topology, zoning, and performance data retrieval. Network Advisor reached\n      end of life in March 2019 and has been replaced by SANnav Management Portal.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.broadcom.com/doc/12395099\n    baseURL: https://{bna-host}/rest\n    tags:\n      - Analytics\n      - Deprecated\n      - Monitoring\n      - SAN Management\n    properties:\n      - type: Documentation\n        url: https://docs.broadcom.com/doc/12395099\n      - type: Deprecation Notice\n        url: https://docs.broadcom.com/doc/12395099\n  - name: Brocade Workflow Composer API\n    description: >-\n      The Brocade Workflow Composer was a network automation platform based on\n      StackStorm for event-driven automation and orchestration workflows. The\n      product was transferred to Extreme Networks as part of the IP networking\n      business acquisition\
  \ and is now known as Extreme Workflow Composer.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://bwc-docs.brocade.com/\n    baseURL: https://{bwc-host}/api/v1\n    tags:\n      - Automation\n      - Deprecated\n      - Orchestration\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://bwc-docs.brocade.com/\n  - name: Brocade VCS Fabric API\n    description: >-\n      The Brocade VCS Fabric API provided REST interfaces for Virtual Cluster\n      Switching fabric configuration on Brocade VDX switches. The VCS Fabric\n      product line was transferred to Extreme Networks as part of the data center\n      networking business acquisition and is no longer part of the Broadcom Brocade\n      portfolio.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.extremenetworks.com/support/end-of-sale-and-end-of-support-products\n    baseURL: https://{switch-ip}/rest\n\
  \    tags:\n      - Deprecated\n      - Fabric\n      - Switching\n      - VCS\n    properties:\n      - type: Documentation\n        url: https://www.extremenetworks.com/support/end-of-sale-and-end-of-support-products\n      - type: Deprecation Notice\n        url: https://www.extremenetworks.com/support/end-of-sale-and-end-of-support-products\ncommon:\n  - type: Portal\n    url: https://techdocs.broadcom.com/us/en/fibre-channel-networking.html\n  - type: Documentation\n    url: https://techdocs.broadcom.com/us/en/fibre-channel-networking.html\n  - type: Getting Started\n    url: https://techdocs.broadcom.com/us/en/fibre-channel-networking/fabric-os/fabric-os-rest-api/9-2-x/v26395730/v24190001.html\n  - type: Support\n    url: https://www.broadcom.com/support/fibre-channel-networking\n  - type: Website\n    url: https://www.broadcom.com/products/fibre-channel-networking\n  - type: Sign Up\n    url: https://www.broadcom.com/support/fibre-channel-networking\n  - type: Login\n    url: https://www.broadcom.com/support/fibre-channel-networking\n\
  \  - type: Terms of Service\n    url: https://www.broadcom.com/company/legal/terms-of-use\n  - type: Privacy Policy\n    url: https://www.broadcom.com/company/legal/privacy/policy\n  - type: Community\n    url: https://community.broadcom.com/t5/Fibre-Channel-SAN-Forums/bd-p/fibre\n  - type: Blog\n    url: https://community.broadcom.com/landingpage/brocade-community\n  - type: GitHub Organization\n    url: https://github.com/brocade\n  - type: SDKs\n    url: https://github.com/brocade/pyfos\n  - type: Change Log\n    url: https://www.broadcom.com/support/fibre-channel-networking/eol\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/brocade/refs/heads/main/apis.yml
tags:
- Data Center
- Directors
- Fibre Channel
- Network Automation
- Networking
- SAN
- Storage Area Networks
- Switches
url: https://raw.githubusercontent.com/api-evangelist/brocade/refs/heads/main/apis.yml
use_cases: []
---
