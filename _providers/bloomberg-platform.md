---
api_count: 3
apis:
- description: The foundational API layer of the Bloomberg Platform providing real-time, reference, and historical data access through a socket-based protocol with SDKs for multiple programming languages.
  name: Bloomberg Open API (BLPAPI)
  slug: blpapi
- description: Cloud-native connectivity to Bloomberg data enabling access from AWS, Azure, and Google Cloud environments without on-premises Bloomberg infrastructure.
  name: Bloomberg Cloud Connect
  slug: bloomberg-cloud-api
- description: Authentication and authorization services for the Bloomberg Platform providing entitlement management, user authentication, and access control for Bloomberg data and applications.
  name: Bloomberg Identity and Access Management
  slug: bloomberg-identity-api
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: Documentation
  url: https://developer.bloomberg.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/bloomberg
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/privacy/
- title: ''
  type: Support
  url: https://www.bloomberg.com/professional/support/
created: '2024-01-01'
description: The Bloomberg Platform is the integrated technology infrastructure underpinning all Bloomberg professional products and services. It encompasses the data distribution network, cloud and on-premises deployment options, API connectivity layer, identity and access management, and enterprise integration capabilities that connect Bloomberg data and analytics to client systems.
features:
- description: BLPAPI socket protocol for real-time data connectivity.
  name: API Connectivity
- description: Cloud-native Bloomberg data access from major cloud platforms.
  name: Cloud Deployment
- description: B-PIPE and Server API for on-premises enterprise data integration.
  name: On-Premises Integration
- description: Enterprise authentication and entitlement management.
  name: Identity Management
- description: Redundant infrastructure for mission-critical data connectivity.
  name: High Availability
- description: Optimized data delivery for latency-sensitive trading applications.
  name: Low Latency
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Platform
skills: []
slug: bloomberg-platform
solutions: []
source_yaml: "aid: bloomberg-platform\nname: Bloomberg Platform\ndescription: The Bloomberg Platform is the integrated technology infrastructure underpinning\n  all Bloomberg professional products and services. It encompasses the data distribution\n  network, cloud and on-premises deployment options, API connectivity layer, identity\n  and access management, and enterprise integration capabilities that connect Bloomberg\n  data and analytics to client systems.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-platform/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Platform\n- Infrastructure\n- Data Distribution\n- API Gateway\n- Integration\n- Bloomberg\napis:\n- aid: bloomberg-platform:blpapi\n  name: Bloomberg Open API (BLPAPI)\n  description: The foundational API layer of the Bloomberg Platform providing real-time,\n\
  \    reference, and historical data access through a socket-based protocol with SDKs\n    for multiple programming languages.\n  humanURL: https://bloomberg.github.io/blpapi-docs/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Core API\n  - Market Data\n  - Platform API\n  properties:\n  - type: Documentation\n    url: https://bloomberg.github.io/blpapi-docs/\n  - type: GitHubRepository\n    url: https://github.com/bloomberg/blpapi-node\n- aid: bloomberg-platform:bloomberg-cloud-api\n  name: Bloomberg Cloud Connect\n  description: Cloud-native connectivity to Bloomberg data enabling access from AWS,\n    Azure, and Google Cloud environments without on-premises Bloomberg infrastructure.\n  humanURL: https://www.bloomberg.com/professional/solution/cloud/\n  baseURL: https://api.bloomberg.com/cloud\n  tags:\n  - Cloud\n  - AWS\n  - Azure\n  - Google Cloud\n  - Cloud Native\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/cloud/\n- aid: bloomberg-platform:bloomberg-identity-api\n\
  \  name: Bloomberg Identity and Access Management\n  description: Authentication and authorization services for the Bloomberg Platform\n    providing entitlement management, user authentication, and access control for\n    Bloomberg data and applications.\n  humanURL: https://www.bloomberg.com/professional/support/api-library/\n  baseURL: https://auth.bloomberg.com\n  tags:\n  - Authentication\n  - Authorization\n  - Identity\n  - Entitlements\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/support/api-library/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://developer.bloomberg.com/\n- type: GitHubOrganization\n  url: https://github.com/bloomberg\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n \
  \ - name: API Connectivity\n    description: BLPAPI socket protocol for real-time data connectivity.\n  - name: Cloud Deployment\n    description: Cloud-native Bloomberg data access from major cloud platforms.\n  - name: On-Premises Integration\n    description: B-PIPE and Server API for on-premises enterprise data integration.\n  - name: Identity Management\n    description: Enterprise authentication and entitlement management.\n  - name: High Availability\n    description: Redundant infrastructure for mission-critical data connectivity.\n  - name: Low Latency\n    description: Optimized data delivery for latency-sensitive trading applications.\n- type: UseCases\n  data:\n  - name: Enterprise Integration\n    description: Integrate Bloomberg data into enterprise technology stacks.\n  - name: Cloud Migration\n    description: Migrate Bloomberg data consumption to cloud-native architectures.\n  - name: Trading Infrastructure\n    description: Build low-latency trading systems on the Bloomberg\
  \ Platform.\n  - name: Data Platform Development\n    description: Develop enterprise data platforms consuming Bloomberg data.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-platform/refs/heads/main/apis.yml
tags:
- Platform
- Infrastructure
- Data Distribution
- API Gateway
- Integration
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-platform/refs/heads/main/apis.yml
use_cases:
- description: Integrate Bloomberg data into enterprise technology stacks.
  name: Enterprise Integration
- description: Migrate Bloomberg data consumption to cloud-native architectures.
  name: Cloud Migration
- description: Build low-latency trading systems on the Bloomberg Platform.
  name: Trading Infrastructure
- description: Develop enterprise data platforms consuming Bloomberg data.
  name: Data Platform Development
---
