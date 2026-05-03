---
api_count: 5
apis:
- description: Verizon Network APIs provide authentication, fraud prevention, and device intelligence capabilities leveraging Verizon's mobile network. Includes Number Verification API for seamless device authentica
  name: Verizon Network APIs
  slug: network-apis
- description: ThingSpace gives organizations of all sizes tools to build IoT solutions, manage connected devices, and solve business problems end-to-end. Provides device connectivity management, diagnostics, softwa
  name: Verizon ThingSpace IoT API
  slug: thingspace
- description: Verizon 5G Edge API enables developers to build ultra-low-latency applications by leveraging Verizon's multi-access edge computing (MEC) infrastructure. Provides discovery, session management, and loc
  name: Verizon 5G Edge API
  slug: 5g-edge
- description: Verizon provides a suite of TM Forum certified service management APIs exposing ITIL functions for inventory management, incident management, change management, event management, problem management, o
  name: Verizon TM Forum Service Management APIs
  slug: service-management
- description: Verizon Communications Platform as a Service (CPaaS) offering provides APIs for inbound and outbound IP interactive voice response (IPIVR) and call detail reporting. Available exclusively for IP Conta
  name: Verizon Voice API (CPaaS)
  slug: voice-api
common:
- title: ''
  type: Website
  url: https://www.verizon-communications.com
- title: ''
  type: Portal
  url: https://developers.verizon.com/
- title: ''
  type: Documentation
  url: https://developers.verizon.com/
- title: ''
  type: Support
  url: https://developers.verizon.com/#/apis/ns/documentation/help
- title: ''
  type: FAQ
  url: https://developers.verizon.com/#/apis/ns/documentation/frequently-asked-questions
- title: ''
  type: Login
  url: https://secure.verizon.com/signin?goto=https://developers.verizon.com/apis/sec/v1/login
- title: ''
  type: SignUp
  url: https://secure.verizon.com/account/register/start?goto=https%3A%2F%2Fdevelopers.verizon.com%2Fapis%2Fsec%2Fv1%2Flogin
- title: ''
  type: PrivacyPolicy
  url: https://www.verizon.com/about/privacy/
- title: ''
  type: TermsOfService
  url: https://www.verizon.com/about/terms-conditions/
created: '2026-05-03'
description: Verizon Communications is one of the world's leading providers of technology and communications services, offering wireless, wireline, broadband, and global enterprise services to consumers, businesses, and government customers. Verizon exposes developer APIs for network capabilities including SIM swap detection, number verification, IoT device management via ThingSpace, 5G edge computing, contact center voice APIs, and TM Forum-certified service management APIs for enterprise customers.
features:
- description: Seamless authentication of end-user mobile devices via network-based verification, eliminating passwords and one-time codes.
  name: Number Verification
- description: Check if a SIM card associated with a phone number has been recently changed to detect account takeover fraud.
  name: SIM Swap Detection
- description: Full lifecycle management of IoT devices including connectivity, diagnostics, software updates, and location tracking via ThingSpace.
  name: IoT Device Management
- description: Multi-access edge computing APIs for deploying ultra-low-latency applications on Verizon's 5G MEC infrastructure.
  name: 5G Edge Computing
- description: TM Forum-certified ITIL APIs for enterprise service management including inventory, incident, change, order, and billing management.
  name: TM Forum Open APIs
- description: CPaaS APIs for customized IP interactive voice response (IPIVR) and call detail reporting for contact center operations.
  name: Contact Center Voice APIs
image: ''
integrations:
- description: Integrate TM Forum service management APIs with ITSM platforms like ServiceNow for automated incident and change management.
  name: ITSM Platforms
- description: Embed Number Verification and SIM Swap APIs into authentication flows and identity provider SDKs.
  name: Identity Providers
- description: Connect ThingSpace device management APIs to IoT platforms and enterprise data lakes.
  name: IoT Platforms
- description: Deploy 5G Edge applications across Verizon's MEC nodes in partnership with AWS Wavelength and Google Cloud.
  name: Edge Cloud Providers
layout: provider
modified: '2026-05-03'
name: Verizon Communications
skills: []
slug: verizon-communications
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: verizon-communications\nname: Verizon Communications\ndescription: >-\n  Verizon Communications is one of the world's leading providers of technology\n  and communications services, offering wireless, wireline, broadband, and global\n  enterprise services to consumers, businesses, and government customers. Verizon\n  exposes developer APIs for network capabilities including SIM swap detection,\n  number verification, IoT device management via ThingSpace, 5G edge computing,\n  contact center voice APIs, and TM Forum-certified service management APIs for\n  enterprise customers.\nurl: https://raw.githubusercontent.com/api-evangelist/verizon-communications/refs/heads/main/apis.yml\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\ntags:\n  - Telecommunications\n  - Wireless\n  - Network APIs\n  - IoT\n  - 5G\n  - Enterprise\n  - Identity\napis:\n  - aid: verizon-communications:network-apis\n    name: Verizon Network APIs\n    description: >-\n \
  \     Verizon Network APIs provide authentication, fraud prevention, and device\n      intelligence capabilities leveraging Verizon's mobile network. Includes\n      Number Verification API for seamless device authentication and SIM Swap API\n      for detecting fraudulent account takeovers.\n    humanURL: https://www.verizon.com/business/solutions/network-apis/\n    tags:\n      - Network APIs\n      - Authentication\n      - Fraud Prevention\n      - Identity\n      - SIM Swap\n      - Number Verification\n    properties:\n      - type: Documentation\n        url: https://www.verizon.com/business/solutions/network-apis/\n      - type: Portal\n        url: https://developers.verizon.com/\n\n  - aid: verizon-communications:thingspace\n    name: Verizon ThingSpace IoT API\n    description: >-\n      ThingSpace gives organizations of all sizes tools to build IoT solutions,\n      manage connected devices, and solve business problems end-to-end. Provides\n      device connectivity management,\
  \ diagnostics, software management, and\n      location services for IoT deployments.\n    humanURL: https://thingspace.verizon.com\n    tags:\n      - IoT\n      - Device Management\n      - Connectivity\n      - Wireless\n    properties:\n      - type: Documentation\n        url: https://thingspace.verizon.com/resources/documentation/connectivity/API_Reference/\n      - type: Portal\n        url: https://thingspace.verizon.com\n      - type: APIReference\n        url: https://thingspace.verizon.com/resources/documentation/connectivity/API_Console/\n\n  - aid: verizon-communications:5g-edge\n    name: Verizon 5G Edge API\n    description: >-\n      Verizon 5G Edge API enables developers to build ultra-low-latency applications\n      by leveraging Verizon's multi-access edge computing (MEC) infrastructure.\n      Provides discovery, session management, and location services for 5G edge\n      compute workloads.\n    humanURL: https://www.verizon.com/business/5g-edge-portal/api-documentation.html\n\
  \    tags:\n      - 5G\n      - Edge Computing\n      - MEC\n      - Ultra-Low Latency\n    properties:\n      - type: Documentation\n        url: https://www.verizon.com/business/5g-edge-portal/api-documentation.html\n      - type: APIReference\n        url: https://www.verizon.com/business/5g-edge-portal/documentation/verizon-5g-edge-discovery-service/api-reference.html\n      - type: Portal\n        url: https://www.verizon.com/business/5g-edge-portal/index.html\n\n  - aid: verizon-communications:service-management\n    name: Verizon TM Forum Service Management APIs\n    description: >-\n      Verizon provides a suite of TM Forum certified service management APIs\n      exposing ITIL functions for inventory management, incident management,\n      change management, event management, problem management, order management,\n      and billing management. APIs are bi-directional and keep Verizon and\n      customer systems synchronized.\n    humanURL: https://developers.verizon.com/\n  \
  \  tags:\n      - TM Forum\n      - ITIL\n      - Service Management\n      - Enterprise\n      - B2B\n    properties:\n      - type: Documentation\n        url: https://developers.verizon.com/\n      - type: APIReference\n        url: https://developers.verizon.com/\n\n  - aid: verizon-communications:voice-api\n    name: Verizon Voice API (CPaaS)\n    description: >-\n      Verizon Communications Platform as a Service (CPaaS) offering provides\n      APIs for inbound and outbound IP interactive voice response (IPIVR) and\n      call detail reporting. Available exclusively for IP Contact Center (IPCC)\n      customers to build customized communication solutions.\n    humanURL: https://www.verizon.com/business/products/contact-center-cx/voice-api/\n    tags:\n      - CPaaS\n      - Voice\n      - Contact Center\n      - IVR\n      - Communications\n    properties:\n      - type: Documentation\n        url: https://www.verizon.com/business/products/contact-center-cx/voice-api/\n\ncommon:\n\
  \  - type: Website\n    url: https://www.verizon-communications.com\n  - type: Portal\n    url: https://developers.verizon.com/\n  - type: Documentation\n    url: https://developers.verizon.com/\n  - type: Support\n    url: https://developers.verizon.com/#/apis/ns/documentation/help\n  - type: FAQ\n    url: https://developers.verizon.com/#/apis/ns/documentation/frequently-asked-questions\n  - type: Login\n    url: https://secure.verizon.com/signin?goto=https://developers.verizon.com/apis/sec/v1/login\n  - type: SignUp\n    url: https://secure.verizon.com/account/register/start?goto=https%3A%2F%2Fdevelopers.verizon.com%2Fapis%2Fsec%2Fv1%2Flogin\n  - type: PrivacyPolicy\n    url: https://www.verizon.com/about/privacy/\n  - type: TermsOfService\n    url: https://www.verizon.com/about/terms-conditions/\n  - type: Features\n    data:\n      - name: Number Verification\n        description: Seamless authentication of end-user mobile devices via network-based verification, eliminating passwords\
  \ and one-time codes.\n      - name: SIM Swap Detection\n        description: Check if a SIM card associated with a phone number has been recently changed to detect account takeover fraud.\n      - name: IoT Device Management\n        description: Full lifecycle management of IoT devices including connectivity, diagnostics, software updates, and location tracking via ThingSpace.\n      - name: 5G Edge Computing\n        description: Multi-access edge computing APIs for deploying ultra-low-latency applications on Verizon's 5G MEC infrastructure.\n      - name: TM Forum Open APIs\n        description: TM Forum-certified ITIL APIs for enterprise service management including inventory, incident, change, order, and billing management.\n      - name: Contact Center Voice APIs\n        description: CPaaS APIs for customized IP interactive voice response (IPIVR) and call detail reporting for contact center operations.\n  - type: UseCases\n    data:\n      - name: Fraud Prevention\n        description:\
  \ Use SIM Swap and Number Verification APIs to protect users from account takeover and SIM-swapping fraud.\n      - name: Passwordless Authentication\n        description: Authenticate users seamlessly via mobile network without passwords using Number Verification API.\n      - name: IoT Fleet Management\n        description: Manage large-scale IoT device fleets with connectivity monitoring, remote diagnostics, and over-the-air software updates.\n      - name: 5G Application Development\n        description: Build edge-native applications leveraging ultra-low latency of Verizon's 5G MEC infrastructure.\n      - name: Enterprise Service Automation\n        description: Automate IT service management workflows using TM Forum-certified APIs integrated with ITSM platforms.\n      - name: Contact Center Modernization\n        description: Build customized IVR and call routing solutions using Verizon's CPaaS Voice API.\n  - type: Integrations\n    data:\n      - name: ITSM Platforms\n      \
  \  description: Integrate TM Forum service management APIs with ITSM platforms like ServiceNow for automated incident and change management.\n      - name: Identity Providers\n        description: Embed Number Verification and SIM Swap APIs into authentication flows and identity provider SDKs.\n      - name: IoT Platforms\n        description: Connect ThingSpace device management APIs to IoT platforms and enterprise data lakes.\n      - name: Edge Cloud Providers\n        description: Deploy 5G Edge applications across Verizon's MEC nodes in partnership with AWS Wavelength and Google Cloud.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/verizon-communications/refs/heads/main/apis.yml
tags:
- Telecommunications
- Wireless
- Network APIs
- IoT
- 5G
- Enterprise
- Identity
url: https://raw.githubusercontent.com/api-evangelist/verizon-communications/refs/heads/main/apis.yml
use_cases:
- description: Use SIM Swap and Number Verification APIs to protect users from account takeover and SIM-swapping fraud.
  name: Fraud Prevention
- description: Authenticate users seamlessly via mobile network without passwords using Number Verification API.
  name: Passwordless Authentication
- description: Manage large-scale IoT device fleets with connectivity monitoring, remote diagnostics, and over-the-air software updates.
  name: IoT Fleet Management
- description: Build edge-native applications leveraging ultra-low latency of Verizon's 5G MEC infrastructure.
  name: 5G Application Development
- description: Automate IT service management workflows using TM Forum-certified APIs integrated with ITSM platforms.
  name: Enterprise Service Automation
- description: Build customized IVR and call routing solutions using Verizon's CPaaS Voice API.
  name: Contact Center Modernization
---
