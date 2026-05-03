---
api_count: 13
apis:
- description: Verifies phone numbers in real time against the operator network for identity confirmation, fraud prevention, and frictionless authentication.
  name: Number Verification API
  slug: number-verification
- description: Detects recent SIM card changes for a given mobile number to help prevent account takeover and fraud.
  name: SIM Swap API
  slug: sim-swap
- description: Conducts know-your-customer matching against operator-held subscriber data to validate identities during onboarding.
  name: KYC Match API
  slug: kyc-match
- description: Identifies recent changes of the device associated with a mobile number to flag potential fraud and verify continuity of identity.
  name: Device Swap API
  slug: device-swap
- description: Identity verification suite including Live Identity Captcha and Live Identity Verify for confirming a real, present user.
  name: Live Identity API
  slug: live-identity
- description: A portfolio of messaging APIs including SMS Middle East and Africa, Messaging Pro Cameroon, Voice as a Service, Business Talk, and Contact Everyone for enterprise and regional communications.
  name: Messaging APIs
  slug: messaging
- description: Device Location Retrieval and Device Location Verification APIs that obtain or confirm a device's geographic position from the network.
  name: Device Location APIs
  slug: device-location
- description: Establishes geographic boundary alerts based on real-time device location served by the operator network.
  name: Geofencing API
  slug: geofencing
- description: Network insight APIs including Population Density Data, Quality of Service on Demand, Device Reachability Status, and Device Roaming Status.
  name: Network Dynamics APIs
  slug: network-dynamics
- description: Mobile payment platform API enabling developers to integrate Orange Money wallet transactions, transfers, and payments.
  name: Orange Money API
  slug: orange-money
- description: Direct carrier billing API allowing customers to charge purchases to their Orange mobile bill.
  name: Pay with Orange Bill API
  slug: pay-with-orange-bill
- description: A set of cloud and connectivity APIs including Cloud Avenue, Evolution Platform, EVPL Online, and Content Delivery Boost.
  name: Cloud Connectivity APIs
  slug: cloud-connectivity
- description: SIM management and device monitoring for IoT deployments across Orange's global cellular footprint.
  name: IoT Managed Global Connectivity API
  slug: iot
common:
- title: ''
  type: Portal
  url: https://developer.orange.com/
- title: ''
  type: Documentation
  url: https://developer.orange.com/apis/
- title: ''
  type: Sign Up
  url: https://developer.orange.com/user/register
- title: ''
  type: Login
  url: https://developer.orange.com/user/login
- title: ''
  type: Terms of Service
  url: https://developer.orange.com/terms-conditions
- title: ''
  type: Privacy Policy
  url: https://developer.orange.com/privacy-policy
- title: ''
  type: Support
  url: https://developer.orange.com/forum
- title: ''
  type: Website
  url: https://www.orange.com/
created: '2025-02-09'
description: Orange Developer offers a portfolio of network, communication, identity, location, payment, IoT, and cloud APIs that allow developers to build new customer experiences powered by programmable networks and Orange's telecom infrastructure across Europe, the Middle East, and Africa.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Orange
skills: []
slug: orange
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: orange\nname: Orange\ndescription: >-\n  Orange Developer offers a portfolio of network, communication, identity, location,\n  payment, IoT, and cloud APIs that allow developers to build new customer experiences\n  powered by programmable networks and Orange's telecom infrastructure across Europe,\n  the Middle East, and Africa.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Network\n  - Telecom\n  - Identity\n  - Messaging\n  - Location\n  - Payment\n  - IoT\ncreated: '2025-02-09'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/orange/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: orange:number-verification\n    name: Number Verification API\n    description: >-\n      Verifies phone numbers in real time against the operator network for identity\n      confirmation, fraud prevention, and frictionless authentication.\n\
  \    humanURL: https://docs.developer.orange.com/network-apis/api-catalog/number-verification/playground/1.0/overview\n    tags:\n      - Identity\n      - Verification\n      - Network\n    properties:\n      - type: Documentation\n        url: https://docs.developer.orange.com/network-apis/api-catalog/number-verification/playground/1.0/overview\n  - aid: orange:sim-swap\n    name: SIM Swap API\n    description: >-\n      Detects recent SIM card changes for a given mobile number to help prevent account\n      takeover and fraud.\n    humanURL: https://docs.developer.orange.com/network-apis/api-catalog/sim-swap/playground/1.0/overview\n    tags:\n      - Fraud Prevention\n      - Identity\n      - Network\n    properties:\n      - type: Documentation\n        url: https://docs.developer.orange.com/network-apis/api-catalog/sim-swap/playground/1.0/overview\n  - aid: orange:kyc-match\n    name: KYC Match API\n    description: >-\n      Conducts know-your-customer matching against operator-held\
  \ subscriber data to\n      validate identities during onboarding.\n    humanURL: https://docs.developer.orange.com/network-apis/api-catalog/kyc-match/playground/0.2/overview\n    tags:\n      - Identity\n      - KYC\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://docs.developer.orange.com/network-apis/api-catalog/kyc-match/playground/0.2/overview\n  - aid: orange:device-swap\n    name: Device Swap API\n    description: >-\n      Identifies recent changes of the device associated with a mobile number to flag\n      potential fraud and verify continuity of identity.\n    humanURL: https://docs.developer.orange.com/network-apis/api-catalog/device-swap/es/0.1/overview\n    tags:\n      - Fraud Prevention\n      - Network\n    properties:\n      - type: Documentation\n        url: https://docs.developer.orange.com/network-apis/api-catalog/device-swap/es/0.1/overview\n  - aid: orange:live-identity\n    name: Live Identity API\n    description: >-\n  \
  \    Identity verification suite including Live Identity Captcha and Live Identity\n      Verify for confirming a real, present user.\n    humanURL: https://developer.orange.com/apis/live-identity-verify\n    tags:\n      - Identity\n      - Verification\n    properties:\n      - type: Documentation\n        url: https://developer.orange.com/apis/live-identity-verify\n      - type: Captcha\n        url: https://developer.orange.com/apis/live-identity-captcha\n  - aid: orange:messaging\n    name: Messaging APIs\n    description: >-\n      A portfolio of messaging APIs including SMS Middle East and Africa, Messaging\n      Pro Cameroon, Voice as a Service, Business Talk, and Contact Everyone for enterprise\n      and regional communications.\n    humanURL: https://developer.orange.com/apis/\n    tags:\n      - Messaging\n      - SMS\n      - Voice\n    properties:\n      - type: Documentation\n        url: https://developer.orange.com/apis/\n  - aid: orange:device-location\n    name: Device\
  \ Location APIs\n    description: >-\n      Device Location Retrieval and Device Location Verification APIs that obtain or\n      confirm a device's geographic position from the network.\n    humanURL: https://developer.orange.com/apis/\n    tags:\n      - Location\n      - Network\n    properties:\n      - type: Documentation\n        url: https://developer.orange.com/apis/\n  - aid: orange:geofencing\n    name: Geofencing API\n    description: >-\n      Establishes geographic boundary alerts based on real-time device location served\n      by the operator network.\n    humanURL: https://developer.orange.com/apis/\n    tags:\n      - Location\n      - Geofencing\n    properties:\n      - type: Documentation\n        url: https://developer.orange.com/apis/\n  - aid: orange:network-dynamics\n    name: Network Dynamics APIs\n    description: >-\n      Network insight APIs including Population Density Data, Quality of Service on\n      Demand, Device Reachability Status, and Device Roaming\
  \ Status.\n    humanURL: https://developer.orange.com/apis/\n    tags:\n      - Network\n      - Quality of Service\n      - Insights\n    properties:\n      - type: Documentation\n        url: https://developer.orange.com/apis/\n  - aid: orange:orange-money\n    name: Orange Money API\n    description: >-\n      Mobile payment platform API enabling developers to integrate Orange Money wallet\n      transactions, transfers, and payments.\n    humanURL: https://developer.orange.com/apis/\n    tags:\n      - Payment\n      - Wallet\n      - Mobile Money\n    properties:\n      - type: Documentation\n        url: https://developer.orange.com/apis/\n  - aid: orange:pay-with-orange-bill\n    name: Pay with Orange Bill API\n    description: >-\n      Direct carrier billing API allowing customers to charge purchases to their Orange\n      mobile bill.\n    humanURL: https://developer.orange.com/apis/\n    tags:\n      - Payment\n      - Carrier Billing\n    properties:\n      - type: Documentation\n\
  \        url: https://developer.orange.com/apis/\n  - aid: orange:cloud-connectivity\n    name: Cloud Connectivity APIs\n    description: >-\n      A set of cloud and connectivity APIs including Cloud Avenue, Evolution Platform,\n      EVPL Online, and Content Delivery Boost.\n    humanURL: https://developer.orange.com/apis/\n    tags:\n      - Cloud\n      - Connectivity\n    properties:\n      - type: Documentation\n        url: https://developer.orange.com/apis/\n  - aid: orange:iot\n    name: IoT Managed Global Connectivity API\n    description: >-\n      SIM management and device monitoring for IoT deployments across Orange's global\n      cellular footprint.\n    humanURL: https://developer.orange.com/apis/\n    tags:\n      - IoT\n      - Connectivity\n      - SIM\n    properties:\n      - type: Documentation\n        url: https://developer.orange.com/apis/\ncommon:\n  - type: Portal\n    url: https://developer.orange.com/\n  - type: Documentation\n    url: https://developer.orange.com/apis/\n\
  \  - type: Sign Up\n    url: https://developer.orange.com/user/register\n  - type: Login\n    url: https://developer.orange.com/user/login\n  - type: Terms of Service\n    url: https://developer.orange.com/terms-conditions\n  - type: Privacy Policy\n    url: https://developer.orange.com/privacy-policy\n  - type: Support\n    url: https://developer.orange.com/forum\n  - type: Website\n    url: https://www.orange.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/orange/refs/heads/main/apis.yml
tags:
- Network
- Telecom
- Identity
- Messaging
- Location
- Payment
- IoT
url: https://raw.githubusercontent.com/api-evangelist/orange/refs/heads/main/apis.yml
use_cases: []
---
