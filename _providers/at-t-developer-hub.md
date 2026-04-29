---
api_count: 6
apis:
- description: Delivers performance metrics and device-level network data, providing developers with insights into network conditions, signal quality, and performance indicators for connected devices on the AT&T net
  name: AT&T Network Insights API
  slug: att-network-insights-api
- description: Uses machine learning to identify threats and unusual activity on mobile devices on the AT&T network. Provides real-time threat detection signals to applications for enhanced security, fraud preventio
  name: AT&T Mobility Threat and Anomaly Detection API
  slug: att-mobility-threat-anomaly-detection-api
- description: CAMARA-standard API that checks when SIM cards associated with mobile numbers have changed. Enables applications to strengthen authentication flows and detect SIM swap fraud by querying AT&T's network
  name: AT&T SIM Swap API
  slug: att-sim-swap-api
- description: CAMARA-standard API that checks the connectivity status of user equipment, including roaming information. Enables applications to determine if a device is reachable, connected, and whether it is roami
  name: AT&T Device Status API
  slug: att-device-status-api
- description: CAMARA-standard Quality of Service on Demand (QoD) API that temporarily enhances Quality of Service on 5G PDU sessions. Enables applications to request prioritized network throughput, reduced latency,
  name: AT&T Quality on Demand API
  slug: att-quality-on-demand-api
- description: CAMARA-standard API enabling seamless device authentication via the mobile network. Verifies that a device is currently using a specific phone number without requiring the user to enter an OTP, levera
  name: AT&T Number Verification API
  slug: att-number-verification-api
capabilities:
- description: Unified network performance capability combining Device Status, Network Insights, and Quality on Demand APIs. Used by developers building connectivity-aware applications, real-time streaming platforms
  name: AT&T Network Performance
  slug: network-performance
- description: Unified network-based security capability combining SIM Swap detection, Number Verification, and Mobility Threat Detection APIs. Used by developers building fraud prevention, authentication, and secur
  name: AT&T Network Security
  slug: network-security
common:
- title: ''
  type: Website
  url: https://www.att.com/
- title: ''
  type: Portal
  url: https://developer.att.com/s/
- title: ''
  type: DeveloperPortal
  url: https://devex-web.att.com/developer-hub/
- title: ''
  type: Documentation
  url: https://devex-web.att.com/developer-hub/
- title: ''
  type: GettingStarted
  url: https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program
- title: ''
  type: SignUp
  url: https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program
- title: ''
  type: TermsOfService
  url: https://www.att.com/gen/general?pid=11561
- title: ''
  type: PrivacyPolicy
  url: https://www.att.com/gen/privacy-policy?pid=2506
- title: ''
  type: GitHubOrganization
  url: https://github.com/attdevsupport
- title: ''
  type: SpectralRules
  url: rules/at-t-developer-hub-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/at-t-developer-hub-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/network-security.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/network-performance.yaml
created: '2025-05-02'
description: The AT&T Developer Hub provides access to cutting-edge network APIs including 5G, edge computing, and CAMARA industry-standard APIs. The Network API Accelerator Program offers early adopters pre-release, invite-only access to network capabilities spanning device status, SIM swap detection, number verification, quality of service on demand, network insights, and mobility threat detection. AT&T's network APIs enable developers to build advanced applications leveraging the U.S. mobile network for authentication, fraud prevention, performance optimization, and security.
features:
- description: Implements GSMA CAMARA open-source standard APIs including SIM Swap, Device Status, Number Verification, and Quality on Demand for cross-carrier interoperability.
  name: CAMARA Industry-Standard APIs
- description: Invite-only early access program for developers to trial pre-release 5G network APIs and influence future network capability development.
  name: Network API Accelerator Program
- description: Exposes AT&T's 5G network intelligence including QoS on demand, network performance insights, and device connectivity status.
  name: 5G Network Capabilities
- description: Network-based fraud signals including SIM swap detection, number verification, and mobility threat detection to strengthen app security.
  name: Fraud Prevention Network Signals
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: AT&T's partnership with Aduna provides standardized access to AT&T 5G Network APIs with cross-carrier interoperability for all three major U.S. carriers.
  name: Aduna Network API Platform
- description: Collaboration with Vonage to bring AT&T CAMARA network APIs to communications platform developers.
  name: Vonage (Ericsson)
- description: Member of GSMA's CAMARA open-source project defining standardized telco network APIs for cross-operator portability.
  name: GSMA CAMARA
jsonld:
- class_count: 5
  name: At T Developer Hub Device Status Api Context
  property_count: 11
  slug: at-t-developer-hub-device-status-api-context
- class_count: 7
  name: At T Developer Hub Mobility Threat Anomaly Detection Api Context
  property_count: 14
  slug: at-t-developer-hub-mobility-threat-anomaly-detection-api-context
- class_count: 3
  name: At T Developer Hub Network Insights Api Context
  property_count: 10
  slug: at-t-developer-hub-network-insights-api-context
- class_count: 2
  name: At T Developer Hub Number Verification Api Context
  property_count: 2
  slug: at-t-developer-hub-number-verification-api-context
- class_count: 3
  name: At T Developer Hub Quality On Demand Api Context
  property_count: 13
  slug: at-t-developer-hub-quality-on-demand-api-context
- class_count: 4
  name: At T Developer Hub Sim Swap Api Context
  property_count: 4
  slug: at-t-developer-hub-sim-swap-api-context
layout: provider
modified: '2026-04-19'
name: AT&T Developer Hub
rules:
- name: AT&T Developer Hub API Rules
  rule_count: 26
  severity_counts:
    error: 14
    hint: 0
    info: 3
    warn: 9
  slug: at-t-developer-hub-spectral-rules
skills: []
slug: at-t-developer-hub
solutions: []
source_yaml: "aid: at-t-developer-hub\nname: AT&T Developer Hub\ndescription: >-\n  The AT&T Developer Hub provides access to cutting-edge network APIs including\n  5G, edge computing, and CAMARA industry-standard APIs. The Network API\n  Accelerator Program offers early adopters pre-release, invite-only access to\n  network capabilities spanning device status, SIM swap detection, number\n  verification, quality of service on demand, network insights, and mobility\n  threat detection. AT&T's network APIs enable developers to build advanced\n  applications leveraging the U.S. mobile network for authentication, fraud\n  prevention, performance optimization, and security.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - 5G\n  - Network APIs\n  - CAMARA\n  - Connectivity\n  - Telecommunications\n  - Edge Computing\n  - Device Status\n  - SIM Swap\nurl: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/apis.yml\n\
  created: '2025-05-02'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: at-t-developer-hub:att-network-insights-api\n    name: AT&T Network Insights API\n    description: >-\n      Delivers performance metrics and device-level network data, providing\n      developers with insights into network conditions, signal quality, and\n      performance indicators for connected devices on the AT&T network.\n    humanURL: https://devex-web.att.com/developer-hub/\n    baseURL: https://api.att.com\n    tags:\n      - Network Performance\n      - Metrics\n      - 5G\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/developer-hub/\n      - type: GettingStarted\n        url: https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program\n      - type: OpenAPI\n        url: openapi/at-t-developer-hub-network-insights-api.yaml\n  - aid: at-t-developer-hub:att-mobility-threat-anomaly-detection-api\n    name: AT&T\
  \ Mobility Threat and Anomaly Detection API\n    description: >-\n      Uses machine learning to identify threats and unusual activity on mobile\n      devices on the AT&T network. Provides real-time threat detection signals\n      to applications for enhanced security, fraud prevention, and anomaly\n      detection across subscriber devices.\n    humanURL: https://devex-web.att.com/developer-hub/\n    baseURL: https://api.att.com\n    tags:\n      - Security\n      - Fraud Detection\n      - Machine Learning\n      - Anomaly Detection\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/developer-hub/\n      - type: GettingStarted\n        url: https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program\n      - type: OpenAPI\n        url: openapi/at-t-developer-hub-mobility-threat-anomaly-detection-api.yaml\n  - aid: at-t-developer-hub:att-sim-swap-api\n    name: AT&T SIM Swap API\n    description: >-\n  \
  \    CAMARA-standard API that checks when SIM cards associated with mobile\n      numbers have changed. Enables applications to strengthen authentication\n      flows and detect SIM swap fraud by querying AT&T's network for recent\n      SIM card changes on a subscriber's number.\n    humanURL: https://devex-web.att.com/developer-hub/\n    baseURL: https://api.att.com\n    tags:\n      - SIM Swap\n      - Authentication\n      - Fraud Prevention\n      - CAMARA\n      - Security\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/developer-hub/\n      - type: GettingStarted\n        url: https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program\n      - type: OpenAPI\n        url: openapi/at-t-developer-hub-sim-swap-api.yaml\n  - aid: at-t-developer-hub:att-device-status-api\n    name: AT&T Device Status API\n    description: >-\n      CAMARA-standard API that checks the connectivity status of user equipment,\n      including roaming\
  \ information. Enables applications to determine if a device\n      is reachable, connected, and whether it is roaming on a partner network,\n      supporting location-aware and connectivity-sensitive application logic.\n    humanURL: https://devex-web.att.com/developer-hub/\n    baseURL: https://api.att.com\n    tags:\n      - Device Status\n      - Connectivity\n      - Roaming\n      - CAMARA\n      - 5G\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/developer-hub/\n      - type: GettingStarted\n        url: https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program\n      - type: OpenAPI\n        url: openapi/at-t-developer-hub-device-status-api.yaml\n  - aid: at-t-developer-hub:att-quality-on-demand-api\n    name: AT&T Quality on Demand API\n    description: >-\n      CAMARA-standard Quality of Service on Demand (QoD) API that temporarily\n      enhances Quality of Service on 5G PDU sessions. Enables applications to\n      request\
  \ prioritized network throughput, reduced latency, or guaranteed\n      bandwidth for time-sensitive operations like video streaming, gaming,\n      remote surgery, or industrial automation.\n    humanURL: https://devex-web.att.com/developer-hub/\n    baseURL: https://api.att.com\n    tags:\n      - Quality of Service\n      - QoS\n      - 5G\n      - CAMARA\n      - Network Slicing\n      - Latency\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/developer-hub/\n      - type: GettingStarted\n        url: https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program\n      - type: OpenAPI\n        url: openapi/at-t-developer-hub-quality-on-demand-api.yaml\n  - aid: at-t-developer-hub:att-number-verification-api\n    name: AT&T Number Verification API\n    description: >-\n      CAMARA-standard API enabling seamless device authentication via the mobile\n      network. Verifies that a device is currently using a specific phone number\n\
  \      without requiring the user to enter an OTP, leveraging the AT&T network\n      signal for frictionless identity verification in mobile applications.\n    humanURL: https://devex-web.att.com/developer-hub/\n    baseURL: https://api.att.com\n    tags:\n      - Number Verification\n      - Authentication\n      - Identity\n      - CAMARA\n      - Mobile\n    properties:\n      - type: Documentation\n        url: https://devex-web.att.com/developer-hub/\n      - type: GettingStarted\n        url: https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program\n      - type: OpenAPI\n        url: openapi/at-t-developer-hub-number-verification-api.yaml\ncommon:\n  - type: Website\n    url: https://www.att.com/\n  - type: Portal\n    url: https://developer.att.com/s/\n  - type: DeveloperPortal\n    url: https://devex-web.att.com/developer-hub/\n  - type: Documentation\n    url: https://devex-web.att.com/developer-hub/\n  - type: GettingStarted\n    url: https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program\n\
  \  - type: SignUp\n    url: https://devex-web.att.com/developer-hub/docs/network-api-accelerator-program\n  - type: TermsOfService\n    url: https://www.att.com/gen/general?pid=11561\n  - type: PrivacyPolicy\n    url: https://www.att.com/gen/privacy-policy?pid=2506\n  - type: GitHubOrganization\n    url: https://github.com/attdevsupport\n  - type: SpectralRules\n    url: rules/at-t-developer-hub-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/at-t-developer-hub-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/network-security.yaml\n  - type: NaftikoCapability\n    url: capabilities/network-performance.yaml\n  - type: Features\n    data:\n      - name: CAMARA Industry-Standard APIs\n        description: >-\n          Implements GSMA CAMARA open-source standard APIs including SIM Swap,\n          Device Status, Number Verification, and Quality on Demand for\n          cross-carrier interoperability.\n      - name: Network API Accelerator Program\n       \
  \ description: >-\n          Invite-only early access program for developers to trial pre-release\n          5G network APIs and influence future network capability development.\n      - name: 5G Network Capabilities\n        description: >-\n          Exposes AT&T's 5G network intelligence including QoS on demand,\n          network performance insights, and device connectivity status.\n      - name: Fraud Prevention Network Signals\n        description: >-\n          Network-based fraud signals including SIM swap detection, number\n          verification, and mobility threat detection to strengthen app security.\n  - type: UseCases\n    data:\n      - name: SIM Swap Fraud Prevention\n        description: >-\n          Detect recent SIM card changes to prevent account takeover attacks\n          and strengthen multi-factor authentication flows.\n      - name: Frictionless Mobile Authentication\n        description: >-\n          Verify device phone numbers silently via the network without\
  \ OTP codes,\n          reducing authentication friction in mobile apps.\n      - name: 5G Quality of Service Optimization\n        description: >-\n          Request guaranteed bandwidth or low latency for real-time applications\n          like video conferencing, AR/VR, and industrial IoT.\n      - name: Device Connectivity Monitoring\n        description: >-\n          Monitor device connectivity and roaming status to trigger\n          location-aware application behaviors.\n      - name: Threat Detection and Security\n        description: >-\n          Leverage AT&T network ML-based threat signals to detect anomalous\n          device behavior and security incidents.\n  - type: Integrations\n    data:\n      - name: Aduna Network API Platform\n        description: >-\n          AT&T's partnership with Aduna provides standardized access to AT&T\n          5G Network APIs with cross-carrier interoperability for all three\n          major U.S. carriers.\n      - name: Vonage (Ericsson)\n\
  \        description: >-\n          Collaboration with Vonage to bring AT&T CAMARA network APIs to\n          communications platform developers.\n      - name: GSMA CAMARA\n        description: >-\n          Member of GSMA's CAMARA open-source project defining standardized\n          telco network APIs for cross-operator portability.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/apis.yml
tags:
- 5G
- Network APIs
- CAMARA
- Connectivity
- Telecommunications
- Edge Computing
- Device Status
- SIM Swap
url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/apis.yml
use_cases:
- description: Detect recent SIM card changes to prevent account takeover attacks and strengthen multi-factor authentication flows.
  name: SIM Swap Fraud Prevention
- description: Verify device phone numbers silently via the network without OTP codes, reducing authentication friction in mobile apps.
  name: Frictionless Mobile Authentication
- description: Request guaranteed bandwidth or low latency for real-time applications like video conferencing, AR/VR, and industrial IoT.
  name: 5G Quality of Service Optimization
- description: Monitor device connectivity and roaming status to trigger location-aware application behaviors.
  name: Device Connectivity Monitoring
- description: Leverage AT&T network ML-based threat signals to detect anomalous device behavior and security incidents.
  name: Threat Detection and Security
---
