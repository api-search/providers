---
api_count: 6
api_specs:
- filename: atandt-wireless-apis.yaml
  format: yaml
  label: AT&T Wireless APIs
  slug: att-wireless-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/openapi/atandt-wireless-apis.yaml
- filename: atandt-network-apis.yaml
  format: yaml
  label: AT&T 5G Network APIs
  slug: att-network-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/openapi/atandt-network-apis.yaml
- filename: atandt-enterprise-connectivity-apis.yaml
  format: yaml
  label: AT&T Enterprise Connectivity APIs
  slug: att-enterprise-connectivity-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/openapi/atandt-enterprise-connectivity-apis.yaml
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
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: atandt\nname: AT&T\ndescription: >-\n  AT&T Inc. is a multinational telecommunications conglomerate providing\n  wireless and wireline communications, broadband internet, digital TV,\n  and business services. As a Fortune 100 company, AT&T operates one of the\n  largest telecommunications networks in the United States and globally.\n  This profile covers AT&T's full API ecosystem including consumer\n  telecommunications APIs, enterprise connectivity APIs, and business\n  service management APIs available through AT&T's developer programs.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Telecommunications\n  - Fortune 100\n  - Wireless\n  - Wireline\n  - Broadband\n  - Enterprise\n  - 5G\n  - Network\nurl: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: atandt:att-wireless-apis\n    name:\
  \ AT&T Wireless APIs\n    description: >-\n      Developer APIs for AT&T's wireless network capabilities including SMS\n      messaging, MMS messaging, OAuth authentication, speech-to-text,\n      text-to-speech, in-app messaging, and advertising APIs for consumer\n      and business applications.\n    humanURL: https://developer.att.com/s/\n    baseURL: https://api.att.com\n    tags:\n      - Wireless\n      - SMS\n      - MMS\n      - Speech\n      - Advertising\n      - OAuth\n    properties:\n      - type: Documentation\n        url: https://developer.att.com/s/\n      - type: Portal\n        url: https://developer.att.com/s/\n      - type: Authentication\n        url: https://developer.att.com/oauth-2/docs\n      - type: GettingStarted\n        url: https://developer.att.com/s/\n      - type: OpenAPI\n        url: openapi/atandt-wireless-apis.yaml\n  - aid: atandt:att-network-apis\n    name: AT&T 5G Network APIs\n    description: >-\n      CAMARA-standard 5G network APIs available\
  \ through the AT&T Developer Hub\n      and Network API Accelerator Program. Includes SIM Swap detection, Device\n      Status, Number Verification, Quality on Demand, Network Insights, and\n      Mobility Threat and Anomaly Detection APIs.\n    humanURL: https://devex-web.att.com/developer-hub/\n    baseURL: https://api.att.com\n    tags:\n      - 5G\n      - CAMARA\n      - Network\n      - Device Status\n      - SIM Swap\n      - Quality of Service\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/developer-hub/\n      - type: GettingStarted\n        url: https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program\n      - type: OpenAPI\n        url: openapi/atandt-network-apis.yaml\n  - aid: atandt:att-enterprise-connectivity-apis\n    name: AT&T Enterprise Connectivity APIs\n    description: >-\n      Enterprise-grade APIs for AT&T wireline business services including\n      service qualification, quoting, ordering, and provisioning.\
  \ The Alliance\n      API suite supports automated ordering of AVPN, IPBB, ATTPhone, ASE,\n      and AT&T Internet Air for Business services.\n    humanURL: https://devex-web.att.com/alliance\n    baseURL: https://devex-web.att.com\n    tags:\n      - Enterprise\n      - Wireline\n      - AVPN\n      - Service Ordering\n      - Service Qualification\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/alliance\n      - type: GettingStarted\n        url: https://devex-web.att.com/order/docs/get-started-with-ordering-api\n      - type: OpenAPI\n        url: openapi/atandt-enterprise-connectivity-apis.yaml\n  - aid: atandt:att-mvno-apis\n    name: AT&T MVNO APIs\n    description: >-\n      TM Forum-aligned APIs for mobile virtual network operators (MVNOs) on\n      the AT&T network. The MVNX API suite covers subscriber activation,\n      number portability, device management, service lifecycle management,\n      and balance management following TMF open standards.\n\
  \    humanURL: https://devex-web.att.com/mvnx\n    baseURL: https://devex-web.att.com\n    tags:\n      - MVNO\n      - TM Forum\n      - Subscriber Management\n      - Porting\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/mvnx/docs/mvnx-quickstart\n      - type: GettingStarted\n        url: https://devex-web.att.com/mvnx/docs/mvnx-quickstart\n  - aid: atandt:att-cloud-voice-apis\n    name: AT&T Cloud Voice APIs\n    description: >-\n      REST APIs for AT&T Business Voice and Cloud Voice services enabling\n      partners to manage service ordering, provisioning, and administration\n      for AT&T's enterprise voice and cloud communication products.\n    humanURL: https://devex-web.att.com/business-voice-cloud-voice\n    baseURL: https://devex-web.att.com\n    tags:\n      - Voice\n      - Cloud\n      - Business\n      - UCaaS\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/business-voice-cloud-voice\n  - aid:\
  \ atandt:att-ebonding-apis\n    name: AT&T eBonding APIs\n    description: >-\n      Seamless API integration with AT&T's wireless and wireline IT and\n      ordering systems. eBonding APIs enable enterprise partners and resellers\n      to integrate their BSS/OSS systems directly with AT&T's backend systems\n      for automated order management and status updates.\n    humanURL: https://devex-web.att.com/ebonding-common\n    baseURL: https://devex-web.att.com\n    tags:\n      - eBonding\n      - Enterprise\n      - BSS\n      - OSS\n      - Integration\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/ebonding-common\ncommon:\n  - type: SpectralRules\n    url: rules/atandt-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/atandt-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/wireless-messaging.yaml\n  - type: NaftikoCapability\n    url: capabilities/network-security.yaml\n  - type: Website\n    url: https://www.att.com\n\
  \  - type: Portal\n    url: https://developer.att.com/s/\n  - type: DeveloperPortal\n    url: https://devex-web.att.com/\n  - type: Documentation\n    url: https://developer.att.com/s/\n  - type: Authentication\n    url: https://developer.att.com/oauth-2/docs\n  - type: Support\n    url: https://developer.att.com/support\n  - type: TermsOfService\n    url: https://www.att.com/gen/general?pid=11561\n  - type: PrivacyPolicy\n    url: https://www.att.com/gen/privacy-policy?pid=2506\n  - type: Blog\n    url: https://about.att.com/blogs\n  - type: StatusPage\n    url: https://www.att.com/support/article/wireless/KM1000428\n  - type: GitHubOrganization\n    url: https://github.com/attdevsupport\n  - type: GitHubOrganization\n    url: https://github.com/att\n  - type: X\n    url: https://x.com/att\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/att\n  - type: YouTube\n    url: https://www.youtube.com/att\n  - type: Features\n    data:\n      - name: 5G Network Coverage\n      \
  \  description: >-\n          Nationwide 5G coverage with sub-6 GHz and mmWave providing broad\n          coverage and ultra-fast speeds for consumer and business customers.\n      - name: FirstNet Public Safety Network\n        description: >-\n          Dedicated wireless broadband network for first responders and public\n          safety personnel with priority and preemption capabilities.\n      - name: AT&T Business Internet\n        description: >-\n          High-speed fiber and wireless internet solutions for small, medium,\n          and enterprise businesses including AT&T Internet Air for Business.\n      - name: CAMARA Network API Standards\n        description: >-\n          Implementation of GSMA CAMARA standardized network APIs enabling\n          cross-carrier portability and developer interoperability.\n      - name: MVNO Infrastructure\n        description: >-\n          Complete mobile virtual network operator infrastructure services\n          using AT&T's nationwide\
  \ 4G LTE and 5G networks.\n  - type: UseCases\n    data:\n      - name: Enterprise Digital Transformation\n        description: >-\n          Automate wireline service ordering, qualification, and provisioning\n          for enterprise customers through API integration.\n      - name: Mobile App Authentication\n        description: >-\n          Use AT&T network signals for frictionless authentication and\n          fraud prevention in consumer and business mobile applications.\n      - name: IoT and Edge Computing\n        description: >-\n          Connect and manage IoT devices using AT&T's 5G and LTE networks\n          with quality of service guarantees for mission-critical applications.\n      - name: MVNO Launch and Operations\n        description: >-\n          Launch and operate mobile virtual network services on AT&T's\n          infrastructure using TM Forum-standard management APIs.\n      - name: Workforce Communication\n        description: >-\n          Integrate AT&T voice\
  \ and messaging APIs into business workflows\n          for employee and customer communication automation.\n  - type: Integrations\n    data:\n      - name: Microsoft Azure\n        description: >-\n          AT&T and Microsoft partnership for 5G and Azure-powered edge\n          computing solutions for enterprise applications.\n      - name: Cisco\n        description: >-\n          Integration with Cisco enterprise networking and collaboration\n          solutions through AT&T's business services.\n      - name: IBM\n        description: >-\n          AT&T and IBM partnership for AI-powered network management\n          and cloud services integration.\n      - name: TM Forum Open APIs\n        description: >-\n          MVNX and enterprise APIs follow TM Forum Open API standards\n          for telecom BSS/OSS interoperability.\n      - name: GSMA CAMARA\n        description: >-\n          AT&T implements CAMARA open-source standard network APIs\n          for cross-carrier developer\
  \ platform interoperability.\n  - type: Solutions\n    data:\n      - name: AT&T Business\n        description: >-\n          Comprehensive connectivity, cloud, cybersecurity, and collaboration\n          solutions for small, medium, and enterprise businesses.\n      - name: FirstNet\n        description: >-\n          Dedicated broadband network for America's first responders including\n          priority access, preemption, and dedicated coverage expansion.\n      - name: AT&T Wholesale\n        description: >-\n          Network services for carriers, MVNOs, and resellers including\n          voice, data, and roaming services on AT&T's infrastructure.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/apis.yml
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
