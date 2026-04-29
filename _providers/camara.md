---
api_count: 11
apis:
- description: The Quality On Demand (QoD) API allows applications to request on-demand, bounded-duration, guaranteed-quality network sessions for specific device flows (latency, throughput, priority class). Develop
  name: CAMARA Quality On Demand API
  slug: quality-on-demand-api
- description: Provides location-verification, location-retrieval, and geofencing subscription endpoints allowing applications to confirm whether a mobile device is in a specified area, to retrieve the last known ar
  name: CAMARA Device Location API
  slug: device-location-api
- description: Silent, cryptographically strong verification that the mobile number a user claims to own is actually the number of the SIM attached to the device making the request. Replaces SMS one-time-password fl
  name: CAMARA Number Verification API
  slug: number-verification-api
- description: Detects whether the SIM attached to a given mobile number has recently been changed. Used by banks, crypto platforms, and other high-assurance services to mitigate SIM-swap account-takeover attacks be
  name: CAMARA SIM Swap API
  slug: sim-swap-api
- description: Provides queries and event subscriptions about a mobile device's connectivity status (reachable, connected, roaming) so applications can adapt behaviour, trigger retries, or switch channels based on r
  name: CAMARA Device Status API
  slug: device-status-api
- description: Returns the closest Mobile Edge Cloud (MEC) endpoint for a given device based on operator network topology, allowing edge-native applications to connect to the lowest-latency edge zone without embeddi
  name: CAMARA Simple Edge Discovery API
  slug: simple-edge-discovery-api
- description: Lifecycle APIs for deploying, managing, and terminating edge-native application instances across operator Mobile Edge Cloud infrastructure, enabling developers to place workloads close to end users wi
  name: CAMARA Edge Application Management API
  slug: edge-application-management-api
- description: Returns a privacy-preserving identifier for a device associated with a network-attached session, enabling correlation and authentication flows while minimising exposure of raw MSISDNs or IMEIs.
  name: CAMARA Device Identifier API
  slug: device-identifier-api
- description: Extends Quality On Demand semantics to fixed-line / home broadband devices, allowing applications to request guaranteed bandwidth or low-latency sessions for devices attached to a home gateway.
  name: CAMARA Home Devices Quality On Demand API
  slug: home-devices-qod-api
- description: Exposes network insight data such as historical and real-time network quality, congestion, and throughput characteristics for a subscriber context, letting applications tune streaming, uploads, and sy
  name: CAMARA Connectivity Insights API
  slug: connectivity-insights-api
- description: Shared authorization and consent model across CAMARA APIs, built on OAuth 2.0 / OpenID Connect Client-Initiated Backchannel Authentication (CIBA) so subscribers explicitly consent to application use o
  name: CAMARA Identity and Consent Management API
  slug: identity-and-consent-management-api
common:
- title: ''
  type: Website
  url: https://camaraproject.org/
- title: ''
  type: Documentation
  url: https://camaraproject.org/apis/
- title: ''
  type: Portfolio
  url: https://camaraproject.github.io/releases/portfolio.html
- title: ''
  type: GitHubOrg
  url: https://github.com/camaraproject
- title: ''
  type: Governance
  url: https://github.com/camaraproject/Governance
- title: ''
  type: Commonalities
  url: https://github.com/camaraproject/Commonalities
- title: ''
  type: ReleaseManagement
  url: https://github.com/camaraproject/ReleaseManagement
- title: ''
  type: LinuxFoundationProject
  url: https://lfnetworking.org/projects/camara/
- title: ''
  type: JSON-LD
  url: json-ld/camara-context.jsonld
- title: ''
  type: VocabularyDefinition
  url: vocabulary.yml
- title: ''
  type: SpectralRules
  url: spectral/camara.spectral.yml
created: '2026-03-16'
description: CAMARA is an open-source Linux Foundation project developing standardized, open, and globally-available telecom APIs as part of the Telco Global API Alliance. Founded and supported by AT&T, Deutsche Telekom, Ericsson, Google Cloud, Microsoft, Nokia, Telefonica, Vodafone, GSMA, and many others, CAMARA defines consistent, operator-agnostic network capability APIs so developers can access programmable network services such as quality-on-demand, device location, SIM swap, number verification, and edge cloud across multiple carriers through a single, unified, standard API surface.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Camara Context
  property_count: 9
  slug: camara-context
layout: provider
modified: '2026-04-23'
name: CAMARA
skills: []
slug: camara
solutions: []
source_filename: apis.yml
source_yaml: "aid: camara\nname: CAMARA\ndescription: >-\n  CAMARA is an open-source Linux Foundation project developing standardized,\n  open, and globally-available telecom APIs as part of the Telco Global API\n  Alliance. Founded and supported by AT&T, Deutsche Telekom, Ericsson, Google\n  Cloud, Microsoft, Nokia, Telefonica, Vodafone, GSMA, and many others, CAMARA\n  defines consistent, operator-agnostic network capability APIs so developers\n  can access programmable network services such as quality-on-demand, device\n  location, SIM swap, number verification, and edge cloud across multiple\n  carriers through a single, unified, standard API surface.\ntype: Standard\nposition: Provider\naccess: Open\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Telecom\n  - Network APIs\n  - Standards\n  - Linux Foundation\n  - Open Gateway\n  - GSMA\n  - Connectivity\n  - 5G\ncreated: '2026-03-16'\nmodified: '2026-04-23'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/camara/refs/heads/main/apis.yml\n\
  specificationVersion: '0.19'\napis:\n  - aid: camara:quality-on-demand-api\n    name: CAMARA Quality On Demand API\n    description: >-\n      The Quality On Demand (QoD) API allows applications to request on-demand,\n      bounded-duration, guaranteed-quality network sessions for specific device\n      flows (latency, throughput, priority class). Developers can set QoS\n      profiles, receive events on session state changes, and manage sessions\n      without dealing with operator-specific signalling.\n    humanURL: https://github.com/camaraproject/QualityOnDemand\n    baseURL: https://api.example.com/quality-on-demand/v0\n    tags:\n      - Quality of Service\n      - Network\n      - QoD\n      - 5G\n    properties:\n      - type: Documentation\n        url: https://github.com/camaraproject/QualityOnDemand\n      - type: Repository\n        url: https://github.com/camaraproject/QualityOnDemand\n  - aid: camara:device-location-api\n    name: CAMARA Device Location API\n    description:\
  \ >-\n      Provides location-verification, location-retrieval, and geofencing\n      subscription endpoints allowing applications to confirm whether a mobile\n      device is in a specified area, to retrieve the last known area the device\n      connected from, and to receive asynchronous notifications when a device\n      enters or leaves a geofenced region — all using operator network data\n      rather than handset GPS.\n    humanURL: https://github.com/camaraproject/DeviceLocation\n    baseURL: https://api.example.com/location/v0\n    tags:\n      - Location\n      - Geofencing\n      - Network\n    properties:\n      - type: Documentation\n        url: https://github.com/camaraproject/DeviceLocation\n      - type: Repository\n        url: https://github.com/camaraproject/DeviceLocation\n  - aid: camara:number-verification-api\n    name: CAMARA Number Verification API\n    description: >-\n      Silent, cryptographically strong verification that the mobile number a\n      user claims\
  \ to own is actually the number of the SIM attached to the\n      device making the request. Replaces SMS one-time-password flows with an\n      operator-authenticated check over the data connection, reducing fraud\n      and user friction in onboarding and login.\n    humanURL: https://github.com/camaraproject/NumberVerification\n    baseURL: https://api.example.com/number-verification/v0\n    tags:\n      - Identity\n      - Authentication\n      - Anti-Fraud\n      - MSISDN\n    properties:\n      - type: Documentation\n        url: https://github.com/camaraproject/NumberVerification\n      - type: Repository\n        url: https://github.com/camaraproject/NumberVerification\n  - aid: camara:sim-swap-api\n    name: CAMARA SIM Swap API\n    description: >-\n      Detects whether the SIM attached to a given mobile number has recently\n      been changed. Used by banks, crypto platforms, and other high-assurance\n      services to mitigate SIM-swap account-takeover attacks before sending\n\
  \      SMS OTPs or authorizing high-risk transactions.\n    humanURL: https://github.com/camaraproject/SimSwap\n    baseURL: https://api.example.com/sim-swap/v0\n    tags:\n      - Anti-Fraud\n      - Identity\n      - Security\n      - SIM\n    properties:\n      - type: Documentation\n        url: https://github.com/camaraproject/SimSwap\n      - type: Repository\n        url: https://github.com/camaraproject/SimSwap\n  - aid: camara:device-status-api\n    name: CAMARA Device Status API\n    description: >-\n      Provides queries and event subscriptions about a mobile device's\n      connectivity status (reachable, connected, roaming) so applications can\n      adapt behaviour, trigger retries, or switch channels based on real-time\n      network reachability.\n    humanURL: https://github.com/camaraproject/DeviceStatus\n    baseURL: https://api.example.com/device-status/v0\n    tags:\n      - Connectivity\n      - Roaming\n      - Events\n    properties:\n      - type: Documentation\n\
  \        url: https://github.com/camaraproject/DeviceStatus\n      - type: Repository\n        url: https://github.com/camaraproject/DeviceStatus\n  - aid: camara:simple-edge-discovery-api\n    name: CAMARA Simple Edge Discovery API\n    description: >-\n      Returns the closest Mobile Edge Cloud (MEC) endpoint for a given device\n      based on operator network topology, allowing edge-native applications\n      to connect to the lowest-latency edge zone without embedding operator-\n      specific logic.\n    humanURL: https://github.com/camaraproject/SimpleEdgeDiscovery\n    baseURL: https://api.example.com/simple-edge-discovery/v0\n    tags:\n      - Edge\n      - MEC\n      - Latency\n    properties:\n      - type: Documentation\n        url: https://github.com/camaraproject/SimpleEdgeDiscovery\n      - type: Repository\n        url: https://github.com/camaraproject/SimpleEdgeDiscovery\n  - aid: camara:edge-application-management-api\n    name: CAMARA Edge Application Management API\n\
  \    description: >-\n      Lifecycle APIs for deploying, managing, and terminating edge-native\n      application instances across operator Mobile Edge Cloud infrastructure,\n      enabling developers to place workloads close to end users without\n      operator lock-in.\n    humanURL: https://github.com/camaraproject/EdgeApplicationManagement\n    baseURL: https://api.example.com/edge-application-management/v0\n    tags:\n      - Edge\n      - MEC\n      - Deployment\n    properties:\n      - type: Documentation\n        url: https://github.com/camaraproject/EdgeApplicationManagement\n      - type: Repository\n        url: https://github.com/camaraproject/EdgeApplicationManagement\n  - aid: camara:device-identifier-api\n    name: CAMARA Device Identifier API\n    description: >-\n      Returns a privacy-preserving identifier for a device associated with a\n      network-attached session, enabling correlation and authentication flows\n      while minimising exposure of raw MSISDNs or\
  \ IMEIs.\n    humanURL: https://github.com/camaraproject/DeviceIdentifier\n    baseURL: https://api.example.com/device-identifier/v0\n    tags:\n      - Identity\n      - Privacy\n    properties:\n      - type: Documentation\n        url: https://github.com/camaraproject/DeviceIdentifier\n      - type: Repository\n        url: https://github.com/camaraproject/DeviceIdentifier\n  - aid: camara:home-devices-qod-api\n    name: CAMARA Home Devices Quality On Demand API\n    description: >-\n      Extends Quality On Demand semantics to fixed-line / home broadband\n      devices, allowing applications to request guaranteed bandwidth or\n      low-latency sessions for devices attached to a home gateway.\n    humanURL: https://github.com/camaraproject/HomeDevicesQoD\n    baseURL: https://api.example.com/home-devices-qod/v0\n    tags:\n      - Broadband\n      - Home\n      - QoS\n    properties:\n      - type: Documentation\n        url: https://github.com/camaraproject/HomeDevicesQoD\n      -\
  \ type: Repository\n        url: https://github.com/camaraproject/HomeDevicesQoD\n  - aid: camara:connectivity-insights-api\n    name: CAMARA Connectivity Insights API\n    description: >-\n      Exposes network insight data such as historical and real-time network\n      quality, congestion, and throughput characteristics for a subscriber\n      context, letting applications tune streaming, uploads, and sync\n      behaviour to current network conditions.\n    humanURL: https://github.com/camaraproject/ConnectivityInsights\n    baseURL: https://api.example.com/connectivity-insights/v0\n    tags:\n      - Analytics\n      - Quality of Service\n      - Observability\n    properties:\n      - type: Documentation\n        url: https://github.com/camaraproject/ConnectivityInsights\n      - type: Repository\n        url: https://github.com/camaraproject/ConnectivityInsights\n  - aid: camara:identity-and-consent-management-api\n    name: CAMARA Identity and Consent Management API\n    description:\
  \ >-\n      Shared authorization and consent model across CAMARA APIs, built on\n      OAuth 2.0 / OpenID Connect Client-Initiated Backchannel Authentication\n      (CIBA) so subscribers explicitly consent to application use of network\n      capabilities such as location, SIM-swap, or QoD on their behalf.\n    humanURL: https://github.com/camaraproject/IdentityAndConsentManagement\n    baseURL: https://api.example.com/identity-consent/v0\n    tags:\n      - OAuth\n      - CIBA\n      - Consent\n      - Identity\n    properties:\n      - type: Documentation\n        url: https://github.com/camaraproject/IdentityAndConsentManagement\n      - type: Repository\n        url: https://github.com/camaraproject/IdentityAndConsentManagement\ncommon:\n  - type: Website\n    url: https://camaraproject.org/\n  - type: Documentation\n    name: CAMARA Documentation\n    description: Official documentation for CAMARA.\n    url: https://camaraproject.org/apis/\n  - type: Portfolio\n    url: https://camaraproject.github.io/releases/portfolio.html\n\
  \  - type: GitHubOrg\n    name: CAMARA GitHub\n    description: Source code and repositories for CAMARA.\n    url: https://github.com/camaraproject\n  - type: Governance\n    url: https://github.com/camaraproject/Governance\n  - type: Commonalities\n    url: https://github.com/camaraproject/Commonalities\n  - type: ReleaseManagement\n    url: https://github.com/camaraproject/ReleaseManagement\n  - type: LinuxFoundationProject\n    url: https://lfnetworking.org/projects/camara/\n  - type: JSON-LD\n    url: json-ld/camara-context.jsonld\n  - type: VocabularyDefinition\n    url: vocabulary.yml\n  - type: SpectralRules\n    url: spectral/camara.spectral.yml\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/camara/refs/heads/main/apis.yml
tags:
- Telecom
- Network APIs
- Standards
- Linux Foundation
- Open Gateway
- GSMA
- Connectivity
- 5G
url: https://raw.githubusercontent.com/api-evangelist/camara/refs/heads/main/apis.yml
use_cases: []
---
