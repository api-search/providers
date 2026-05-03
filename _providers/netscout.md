---
api_count: 8
apis:
- description: RESTful interface for the nGeniusONE platform, enabling network performance monitoring, analytics, and service assurance automation.
  name: Netscout nGeniusONE API
  slug: ngeniusone
- description: REST API for DDoS detection, mitigation, and threat intelligence on the Arbor Sightline platform. Provides programmatic access to alerts, mitigations, routers, managed objects, and annotations via a J
  name: Netscout Arbor Sightline SP REST API
  slug: arbor-sightline
- description: Open API surface for the Omnis Cyber Intelligence NDR platform, enabling network investigation and adding network context to third-party alerts from SIEM and EDR systems using historical network metad
  name: Netscout Omnis Cyber Intelligence API
  slug: omnis-cyber-intelligence
- description: Programmatic interface to deep packet inspection data and network flow analytics from InfiniStreamNG appliances. Feeds ASI Smart Data metadata to analytics stacks for service assurance, application pe
  name: Netscout InfiniStreamNG API
  slug: infinistreamng
- description: REST API for Arbor Edge Defense (AED), an inline security appliance deployed at the network perimeter that provides stateless, on-premises DDoS protection. Enables programmatic management of inbound a
  name: Netscout Arbor Edge Defense API
  slug: arbor-edge-defense
- description: API for the Arbor Threat Mitigation System (TMS), the carrier-class DDoS mitigation solution that works with Arbor Sightline to surgically remove DDoS attack traffic from network flows. Provides progr
  name: Netscout Arbor Threat Mitigation System API
  slug: arbor-tms
- description: API surface for nGeniusPULSE, Netscout's synthetic testing and active monitoring platform. nGeniusPULSE uses nPoint test agents deployed across LAN, WAN, Wi-Fi, VPN, data centers, and cloud environmen
  name: Netscout nGeniusPULSE API
  slug: ngeniuspulse
- description: REST and Kafka interfaces for the nGenius Business Analytics platform, enabling service providers to export enriched ASI Smart Data to third-party data lakes, applications, and analytics platforms for
  name: Netscout nGenius Business Analytics API
  slug: ngenius-business-analytics
common:
- title: ''
  type: Portal
  url: https://my.netscout.com/Pages/overview.aspx
- title: ''
  type: Documentation
  url: https://www.netscout.com/resources
- title: ''
  type: Terms of Service
  url: https://www.netscout.com/legal/terms-and-conditions
- title: ''
  type: Website Terms of Use
  url: https://www.netscout.com/legal/website-terms-of-use
- title: ''
  type: Privacy Policy
  url: https://www.netscout.com/legal/privacy-policy
- title: ''
  type: Legal
  url: https://www.netscout.com/legal
- title: ''
  type: Contact
  url: https://www.netscout.com/contact-us
- title: ''
  type: Blog
  url: https://www.netscout.com/blog
- title: ''
  type: Support
  url: https://www.netscout.com/support-services
- title: ''
  type: Website
  url: https://www.netscout.com
- title: ''
  type: Login
  url: https://my.netscout.com/Pages/overview.aspx
- title: ''
  type: GitHub Organization
  url: https://github.com/arbor
- title: ''
  type: Security
  url: https://www.netscout.com/data-privacy-and-trust-center
created: '2025-01-20'
description: Netscout provides service assurance, cybersecurity, and DDoS protection solutions. Their products enable network visibility, threat intelligence, and performance monitoring across hybrid and cloud environments. Several Netscout products expose REST APIs and integration interfaces for observability, security automation, and analytics workflows.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Netscout
skills: []
slug: netscout
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: netscout\nname: Netscout\ndescription: >-\n  Netscout provides service assurance, cybersecurity, and DDoS protection\n  solutions. Their products enable network visibility, threat intelligence,\n  and performance monitoring across hybrid and cloud environments. Several\n  Netscout products expose REST APIs and integration interfaces for\n  observability, security automation, and analytics workflows.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/netscout/refs/heads/main/apis.yml\ncreated: '2025-01-20'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Cybersecurity\n  - DDoS Protection\n  - Network Monitoring\n  - Network Performance\n  - Service Assurance\n  - Threat Intelligence\napis:\n  - aid: netscout:ngeniusone\n    name: Netscout nGeniusONE API\n    description: >-\n      RESTful interface for the nGeniusONE\
  \ platform, enabling network\n      performance monitoring, analytics, and service assurance automation.\n    humanURL: https://www.netscout.com/product/ngenius-one\n    tags:\n      - Analytics\n      - Monitoring\n      - Network Performance\n      - Service Assurance\n    properties:\n      - type: Documentation\n        url: https://www.netscout.com/product/ngenius-one\n      - type: Reference\n        url: https://www.netscout.com/product/ngeniusone-solution\n    contact:\n      - FN: Netscout Support\n        url: https://www.netscout.com/support-services\n  - aid: netscout:arbor-sightline\n    name: Netscout Arbor Sightline SP REST API\n    description: >-\n      REST API for DDoS detection, mitigation, and threat intelligence on\n      the Arbor Sightline platform. Provides programmatic access to alerts,\n      mitigations, routers, managed objects, and annotations via a\n      JSON:API-style REST interface, with cookbook examples and tutorials\n      maintained on GitHub.\n  \
  \  humanURL: https://www.netscout.com/product/arbor-sightline\n    tags:\n      - DDoS Protection\n      - Security\n      - SIEM Integration\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://www.netscout.com/product/arbor-sightline\n      - type: Getting Started\n        url: https://arbor.github.io/sp-rest-api-cookbook/sp-rest-api-tutorial.html\n      - type: GitHubRepository\n        url: https://github.com/arbor/sp-rest-api-cookbook\n  - aid: netscout:omnis-cyber-intelligence\n    name: Netscout Omnis Cyber Intelligence API\n    description: >-\n      Open API surface for the Omnis Cyber Intelligence NDR platform,\n      enabling network investigation and adding network context to\n      third-party alerts from SIEM and EDR systems using historical network\n      metadata and packet data.\n    humanURL: https://www.netscout.com/product/cyber-intelligence\n    tags:\n      - Attack Detection\n      - Cybersecurity\n      - IOC\n      -\
  \ Network Detection and Response\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://www.netscout.com/product/cyber-intelligence\n      - type: Reference\n        url: https://www.netscout.com/resources/data-sheets/omnis-cyberstream-and-omnis-cyber-intelligence\n  - aid: netscout:infinistreamng\n    name: Netscout InfiniStreamNG API\n    description: >-\n      Programmatic interface to deep packet inspection data and network\n      flow analytics from InfiniStreamNG appliances. Feeds ASI Smart Data\n      metadata to analytics stacks for service assurance, application\n      performance management, cybersecurity, and business intelligence.\n    humanURL: https://www.netscout.com/product/isng-platform\n    tags:\n      - Deep Packet Inspection\n      - Network Flow\n      - Packet Analysis\n      - Service Assurance\n    properties:\n      - type: Documentation\n        url: https://www.netscout.com/product/isng-platform\n      - type: Reference\n\
  \        url: https://www.netscout.com/resources/data-sheets/infinistream-platform\n  - aid: netscout:arbor-edge-defense\n    name: Netscout Arbor Edge Defense API\n    description: >-\n      REST API for Arbor Edge Defense (AED), an inline security appliance\n      deployed at the network perimeter that provides stateless, on-premises\n      DDoS protection. Enables programmatic management of inbound and\n      outbound block/allow lists, protection groups, and mitigation\n      policies, with integration via REST, STIX/TAXII, and Syslog. An\n      Ansible collection is published for automation.\n    humanURL: https://www.netscout.com/product/arbor-aed-aem\n    tags:\n      - DDoS Protection\n      - Inline Defense\n      - Network Security\n      - Threat Mitigation\n    properties:\n      - type: Documentation\n        url: https://www.netscout.com/product/arbor-aed-aem\n      - type: Reference\n        url: https://www.netscout.com/resources/data-sheets/netscout-aed-and-aem\n     \
  \ - type: GitHubRepository\n        url: https://github.com/arbor/aedansible\n  - aid: netscout:arbor-tms\n    name: Netscout Arbor Threat Mitigation System API\n    description: >-\n      API for the Arbor Threat Mitigation System (TMS), the carrier-class\n      DDoS mitigation solution that works with Arbor Sightline to surgically\n      remove DDoS attack traffic from network flows. Provides programmatic\n      control of mitigation operations, countermeasure configuration, and\n      attack response automation.\n    humanURL: https://www.netscout.com/product/arbor-threat-mitigation-system\n    tags:\n      - Attack Response\n      - DDoS Mitigation\n      - Network Security\n      - Threat Management\n    properties:\n      - type: Documentation\n        url: https://www.netscout.com/product/arbor-threat-mitigation-system\n      - type: Reference\n        url: https://www.netscout.com/resources/data-sheets/arbor-threat-mitigation-system-tms\n  - aid: netscout:ngeniuspulse\n    name:\
  \ Netscout nGeniusPULSE API\n    description: >-\n      API surface for nGeniusPULSE, Netscout's synthetic testing and active\n      monitoring platform. nGeniusPULSE uses nPoint test agents deployed\n      across LAN, WAN, Wi-Fi, VPN, data centers, and cloud environments to\n      run scheduled and on-demand tests for HTTP/HTTPS, DNS, DHCP, ICMP,\n      TCP, and voice/collaboration transactions.\n    humanURL: https://www.netscout.com/product/ngeniuspulse\n    tags:\n      - Active Testing\n      - Application Performance\n      - Network Testing\n      - Synthetic Monitoring\n    properties:\n      - type: Documentation\n        url: https://www.netscout.com/product/ngeniuspulse\n      - type: Reference\n        url: https://www.netscout.com/demo/application-and-infrastructure-health\n  - aid: netscout:ngenius-business-analytics\n    name: Netscout nGenius Business Analytics API\n    description: >-\n      REST and Kafka interfaces for the nGenius Business Analytics platform,\n     \
  \ enabling service providers to export enriched ASI Smart Data to\n      third-party data lakes, applications, and analytics platforms for\n      business intelligence and data monetization.\n    humanURL: https://www.netscout.com/product/ngenius-business-analytics\n    tags:\n      - Business Analytics\n      - Data Streaming\n      - Kafka\n      - Service Provider\n      - Smart Data\n    properties:\n      - type: Documentation\n        url: https://www.netscout.com/product/ngenius-business-analytics\n      - type: Reference\n        url: https://www.netscout.com/resources/data-sheets/ngenius-business-analytics\ncommon:\n  - type: Portal\n    url: https://my.netscout.com/Pages/overview.aspx\n  - type: Documentation\n    url: https://www.netscout.com/resources\n  - type: Terms of Service\n    url: https://www.netscout.com/legal/terms-and-conditions\n  - type: Website Terms of Use\n    url: https://www.netscout.com/legal/website-terms-of-use\n  - type: Privacy Policy\n    url: https://www.netscout.com/legal/privacy-policy\n\
  \  - type: Legal\n    url: https://www.netscout.com/legal\n  - type: Contact\n    url: https://www.netscout.com/contact-us\n  - type: Blog\n    url: https://www.netscout.com/blog\n  - type: Support\n    url: https://www.netscout.com/support-services\n  - type: Website\n    url: https://www.netscout.com\n  - type: Login\n    url: https://my.netscout.com/Pages/overview.aspx\n  - type: GitHub Organization\n    url: https://github.com/arbor\n  - type: Security\n    url: https://www.netscout.com/data-privacy-and-trust-center\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/netscout/refs/heads/main/apis.yml
tags:
- Cybersecurity
- DDoS Protection
- Network Monitoring
- Network Performance
- Service Assurance
- Threat Intelligence
url: https://raw.githubusercontent.com/api-evangelist/netscout/refs/heads/main/apis.yml
use_cases: []
---
