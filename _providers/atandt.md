---
api_count: 6
apis:
- description: Developer APIs for AT&T's wireless network capabilities including SMS messaging, MMS messaging, OAuth authentication, speech-to-text, text-to-speech, in-app messaging, and advertising APIs for consume
  name: AT&T Wireless APIs
  slug: att-wireless-apis
- description: CAMARA-standard 5G network APIs available through the AT&T Developer Hub and Network API Accelerator Program. Includes SIM Swap detection, Device Status, Number Verification, Quality on Demand, Networ
  name: AT&T 5G Network APIs
  slug: att-network-apis
- description: Enterprise-grade APIs for AT&T wireline business services including service qualification, quoting, ordering, and provisioning. The Alliance API suite supports automated ordering of AVPN, IPBB, ATTPho
  name: AT&T Enterprise Connectivity APIs
  slug: att-enterprise-connectivity-apis
- description: TM Forum-aligned APIs for mobile virtual network operators (MVNOs) on the AT&T network. The MVNX API suite covers subscriber activation, number portability, device management, service lifecycle manage
  name: AT&T MVNO APIs
  slug: att-mvno-apis
- description: REST APIs for AT&T Business Voice and Cloud Voice services enabling partners to manage service ordering, provisioning, and administration for AT&T's enterprise voice and cloud communication products.
  name: AT&T Cloud Voice APIs
  slug: att-cloud-voice-apis
- description: Seamless API integration with AT&T's wireless and wireline IT and ordering systems. eBonding APIs enable enterprise partners and resellers to integrate their BSS/OSS systems directly with AT&T's backe
  name: AT&T eBonding APIs
  slug: att-ebonding-apis
capabilities:
- description: Workflow capability combining AT&T CAMARA network APIs for fraud prevention and identity verification. Integrates SIM Swap detection and Number Verification for developers building secure authenticati
  name: AT&T Network Security
  slug: network-security
- description: Workflow capability combining AT&T Wireless APIs for SMS messaging and OAuth authentication. Used by developers building consumer and business messaging applications on the AT&T network.
  name: AT&T Wireless Messaging
  slug: wireless-messaging
common:
- title: ''
  type: SpectralRules
  url: rules/atandt-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/atandt-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/wireless-messaging.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/network-security.yaml
- title: ''
  type: Website
  url: https://www.att.com
- title: ''
  type: Portal
  url: https://developer.att.com/s/
- title: ''
  type: DeveloperPortal
  url: https://devex-web.att.com/
- title: ''
  type: Documentation
  url: https://developer.att.com/s/
- title: ''
  type: Authentication
  url: https://developer.att.com/oauth-2/docs
- title: ''
  type: Support
  url: https://developer.att.com/support
- title: ''
  type: TermsOfService
  url: https://www.att.com/gen/general?pid=11561
- title: ''
  type: PrivacyPolicy
  url: https://www.att.com/gen/privacy-policy?pid=2506
- title: ''
  type: Blog
  url: https://about.att.com/blogs
- title: ''
  type: StatusPage
  url: https://www.att.com/support/article/wireless/KM1000428
- title: ''
  type: GitHubOrganization
  url: https://github.com/attdevsupport
- title: ''
  type: GitHubOrganization
  url: https://github.com/att
- title: ''
  type: X
  url: https://x.com/att
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/att
- title: ''
  type: YouTube
  url: https://www.youtube.com/att
created: '2026-03-23'
description: AT&T Inc. is a multinational telecommunications conglomerate providing wireless and wireline communications, broadband internet, digital TV, and business services. As a Fortune 100 company, AT&T operates one of the largest telecommunications networks in the United States and globally. This profile covers AT&T's full API ecosystem including consumer telecommunications APIs, enterprise connectivity APIs, and business service management APIs available through AT&T's developer programs.
features:
- description: Nationwide 5G coverage with sub-6 GHz and mmWave providing broad coverage and ultra-fast speeds for consumer and business customers.
  name: 5G Network Coverage
- description: Dedicated wireless broadband network for first responders and public safety personnel with priority and preemption capabilities.
  name: FirstNet Public Safety Network
- description: High-speed fiber and wireless internet solutions for small, medium, and enterprise businesses including AT&T Internet Air for Business.
  name: AT&T Business Internet
- description: Implementation of GSMA CAMARA standardized network APIs enabling cross-carrier portability and developer interoperability.
  name: CAMARA Network API Standards
- description: Complete mobile virtual network operator infrastructure services using AT&T's nationwide 4G LTE and 5G networks.
  name: MVNO Infrastructure
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: AT&T and Microsoft partnership for 5G and Azure-powered edge computing solutions for enterprise applications.
  name: Microsoft Azure
- description: Integration with Cisco enterprise networking and collaboration solutions through AT&T's business services.
  name: Cisco
- description: AT&T and IBM partnership for AI-powered network management and cloud services integration.
  name: IBM
- description: MVNX and enterprise APIs follow TM Forum Open API standards for telecom BSS/OSS interoperability.
  name: TM Forum Open APIs
- description: AT&T implements CAMARA open-source standard network APIs for cross-carrier developer platform interoperability.
  name: GSMA CAMARA
jsonld:
- class_count: 0
  name: Enterprise Apis Context
  property_count: 1
  slug: enterprise-apis-context
- class_count: 0
  name: Network Apis Context
  property_count: 9
  slug: network-apis-context
- class_count: 0
  name: Wireless Apis Context
  property_count: 2
  slug: wireless-apis-context
layout: provider
modified: '2026-04-19'
name: AT&T
rules:
- name: AT&T API Rules
  rule_count: 27
  severity_counts:
    error: 13
    hint: 0
    info: 0
    warn: 14
  slug: atandt-spectral-rules
skills: []
slug: atandt
solutions:
- description: Comprehensive connectivity, cloud, cybersecurity, and collaboration solutions for small, medium, and enterprise businesses.
  name: AT&T Business
- description: Dedicated broadband network for America's first responders including priority access, preemption, and dedicated coverage expansion.
  name: FirstNet
- description: Network services for carriers, MVNOs, and resellers including voice, data, and roaming services on AT&T's infrastructure.
  name: AT&T Wholesale
tags:
- Telecommunications
- Fortune 100
- Wireless
- Wireline
- Broadband
- Enterprise
- 5G
- Network
url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/apis.yml
use_cases:
- description: Automate wireline service ordering, qualification, and provisioning for enterprise customers through API integration.
  name: Enterprise Digital Transformation
- description: Use AT&T network signals for frictionless authentication and fraud prevention in consumer and business mobile applications.
  name: Mobile App Authentication
- description: Connect and manage IoT devices using AT&T's 5G and LTE networks with quality of service guarantees for mission-critical applications.
  name: IoT and Edge Computing
- description: Launch and operate mobile virtual network services on AT&T's infrastructure using TM Forum-standard management APIs.
  name: MVNO Launch and Operations
- description: Integrate AT&T voice and messaging APIs into business workflows for employee and customer communication automation.
  name: Workforce Communication
---
