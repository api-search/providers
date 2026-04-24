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
