---
api_count: 9
apis:
- description: REST API for the Smart-1 Security Management Server. Automates policy and object management including host/network/service objects, access and NAT rulebases, and publish/install operations.
  name: Check Point Management API
  slug: management-api
- description: REST API for the Check Point Gaia operating system. Manages gateway interfaces, routing, system info, and configuration.
  name: Check Point Gaia API
  slug: gaia-api
- description: REST API for CloudGuard Native cloud security posture management, cloud account onboarding, compliance findings, and rulesets across AWS, Azure, and GCP.
  name: Check Point CloudGuard API
  slug: cloudguard-api
- description: REST API for posting and revoking user-to-IP identity associations on Check Point gateways, enabling identity-aware policy enforcement.
  name: Check Point Identity Awareness API
  slug: identity-awareness-api
- description: REST API for centrally managing Check Point Quantum Spark SMB appliances including configuration and policy.
  name: Check Point Spark Management API
  slug: spark-management-api
- description: REST API for the Zero Touch deployment service that streamlines bring-up of new Check Point appliances.
  name: Check Point Zero Touch API
  slug: zero-touch-api
- description: REST API for Harmony Email and Collaboration (formerly Avanan) surfacing email security events, quarantined items, and admin actions.
  name: Check Point Harmony Email API
  slug: harmony-email-api
- description: REST API for the Check Point Threat Hunting (TH) platform exposing threat intelligence, indicators, and hunting queries.
  name: Check Point Threat Hunting API
  slug: th-api
- description: Management API for the CloudGuard WAF cloud-native web application and API protection product.
  name: Check Point CloudGuard WAF API
  slug: cloudguard-waf-api
common:
- title: ''
  type: Website
  url: https://www.checkpoint.com/
- title: ''
  type: Documentation
  url: https://sc1.checkpoint.com/documents/
- title: ''
  type: Support
  url: https://www.checkpoint.com/support-services/
- title: ''
  type: Login
  url: https://portal.checkpoint.com/
- title: ''
  type: Blog
  url: https://blog.checkpoint.com/
- title: ''
  type: GitHub
  url: https://github.com/CheckPointSW
- title: ''
  type: TermsOfService
  url: https://www.checkpoint.com/about-us/terms-of-use/
- title: ''
  type: PrivacyPolicy
  url: https://www.checkpoint.com/about-us/privacy-statement/
- title: ''
  type: JSONLD
  url: json-ld/checkpoint-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/checkpoint-host-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/checkpoint-access-rule-schema.json
- title: ''
  type: Spectral
  url: spectral/checkpoint-spectral.yml
- title: ''
  type: NaftikoCapabilities
  url: naftiko/checkpoint-capabilities.yml
created: '2025-01-08'
description: Check Point Software Technologies is a global cybersecurity vendor providing network, cloud, endpoint, mobile, and email security through its Quantum, CloudGuard, and Harmony product families. Check Point exposes a wide range of REST APIs for security automation, including the Smart-1 Management API, Gaia OS API, CloudGuard cloud security posture API, Identity Awareness API, Spark and Zero Touch device management APIs, Harmony Email and Collaboration API, Threat Hunting (TH) API, and CloudGuard WAF API.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Checkpoint Context
  property_count: 6
  slug: checkpoint-context
layout: provider
modified: '2026-04-23'
name: Check Point
skills: []
slug: checkpoint
solutions: []
source_yaml: "aid: checkpoint\nname: Check Point\ndescription: >-\n  Check Point Software Technologies is a global cybersecurity vendor providing\n  network, cloud, endpoint, mobile, and email security through its Quantum,\n  CloudGuard, and Harmony product families. Check Point exposes a wide range\n  of REST APIs for security automation, including the Smart-1 Management API,\n  Gaia OS API, CloudGuard cloud security posture API, Identity Awareness API,\n  Spark and Zero Touch device management APIs, Harmony Email and Collaboration\n  API, Threat Hunting (TH) API, and CloudGuard WAF API.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/apis.yml\ntype: Index\naccess: 3rd-Party\nposition: Consumer\ntags:\n  - Cloud Security\n  - Cybersecurity\n  - Endpoint Security\n  - Firewall\n  - Identity Awareness\n  - Mobile Security\n  - Network Security\n  - Security\n  - Threat\
  \ Prevention\n  - WAF\ncreated: '2025-01-08'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: checkpoint:management-api\n    name: Check Point Management API\n    description: >-\n      REST API for the Smart-1 Security Management Server. Automates policy\n      and object management including host/network/service objects, access\n      and NAT rulebases, and publish/install operations.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://sc1.checkpoint.com/documents/latest/APIs/\n    baseURL: https://management.example.com/web_api\n    tags:\n      - Firewall\n      - Management\n      - Network Security\n    properties:\n      - type: Documentation\n        url: https://sc1.checkpoint.com/documents/latest/APIs/\n      - type: OpenAPI\n        url: openapi/checkpoint-management-api-openapi.yml\n  - aid: checkpoint:gaia-api\n    name: Check Point Gaia API\n    description: >-\n      REST API for the Check Point\
  \ Gaia operating system. Manages gateway\n      interfaces, routing, system info, and configuration.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://sc1.checkpoint.com/documents/latest/GaiaAPIs/\n    baseURL: https://gateway.example.com/gaia_api\n    tags:\n      - Gaia\n      - Operating System\n    properties:\n      - type: Documentation\n        url: https://sc1.checkpoint.com/documents/latest/GaiaAPIs/\n      - type: OpenAPI\n        url: openapi/checkpoint-gaia-api-openapi.yml\n  - aid: checkpoint:cloudguard-api\n    name: Check Point CloudGuard API\n    description: >-\n      REST API for CloudGuard Native cloud security posture management,\n      cloud account onboarding, compliance findings, and rulesets across\n      AWS, Azure, and GCP.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://docs.cgn.portal.checkpoint.com/reference/introduction\n    baseURL: https://api.dome9.com/v2\n\
  \    tags:\n      - Cloud Security\n      - Compliance\n      - Posture Management\n    properties:\n      - type: Documentation\n        url: https://docs.cgn.portal.checkpoint.com/\n      - type: OpenAPI\n        url: openapi/checkpoint-cloudguard-api-openapi.yml\n  - aid: checkpoint:identity-awareness-api\n    name: Check Point Identity Awareness API\n    description: >-\n      REST API for posting and revoking user-to-IP identity associations on\n      Check Point gateways, enabling identity-aware policy enforcement.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://sc1.checkpoint.com/documents/latest/IdentityAPIs/\n    baseURL: https://gateway.example.com/_IA_MU_Agent\n    tags:\n      - Identity\n      - Network Security\n    properties:\n      - type: Documentation\n        url: https://sc1.checkpoint.com/documents/latest/IdentityAPIs/\n      - type: OpenAPI\n        url: openapi/checkpoint-identity-awareness-api-openapi.yml\n\
  \  - aid: checkpoint:spark-management-api\n    name: Check Point Spark Management API\n    description: >-\n      REST API for centrally managing Check Point Quantum Spark SMB\n      appliances including configuration and policy.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://sc1.checkpoint.com/documents/latest/SmpAPIs/\n    tags:\n      - SMB\n      - Spark\n    properties:\n      - type: Documentation\n        url: https://sc1.checkpoint.com/documents/latest/SmpAPIs/\n  - aid: checkpoint:zero-touch-api\n    name: Check Point Zero Touch API\n    description: >-\n      REST API for the Zero Touch deployment service that streamlines\n      bring-up of new Check Point appliances.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://sc1.checkpoint.com/documents/Appliances/Zero_Touch_REST_API_Guide/EN/Content/Topics-API/Overview.htm\n    tags:\n      - Deployment\n      - Zero\
  \ Touch\n    properties:\n      - type: Documentation\n        url: https://sc1.checkpoint.com/documents/Appliances/Zero_Touch_REST_API_Guide/EN/Content/Topics-API/Overview.htm\n  - aid: checkpoint:harmony-email-api\n    name: Check Point Harmony Email API\n    description: >-\n      REST API for Harmony Email and Collaboration (formerly Avanan)\n      surfacing email security events, quarantined items, and admin actions.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://sc1.checkpoint.com/documents/Harmony_Email_and_Collaboration_API_Reference/Topics-HEC-Avanan-API-Reference-Guide/Overview/API-Overview.htm\n    baseURL: https://smart-api.avanan.net/v2.0\n    tags:\n      - Email Security\n      - Harmony\n    properties:\n      - type: Documentation\n        url: https://sc1.checkpoint.com/documents/Harmony_Email_and_Collaboration_API_Reference/Topics-HEC-Avanan-API-Reference-Guide/Overview/API-Overview.htm\n      - type: OpenAPI\n\
  \        url: openapi/checkpoint-harmony-email-api-openapi.yml\n  - aid: checkpoint:th-api\n    name: Check Point Threat Hunting API\n    description: >-\n      REST API for the Check Point Threat Hunting (TH) platform exposing\n      threat intelligence, indicators, and hunting queries.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://sc1.checkpoint.com/documents/latest/ThAPIs/index.html\n    tags:\n      - Threat Hunting\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://sc1.checkpoint.com/documents/latest/ThAPIs/index.html\n  - aid: checkpoint:cloudguard-waf-api\n    name: Check Point CloudGuard WAF API\n    description: >-\n      Management API for the CloudGuard WAF cloud-native web application\n      and API protection product.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://waf-doc.inext.checkpoint.com/references/management-api\n\
  \    tags:\n      - WAF\n      - Web Security\n    properties:\n      - type: Documentation\n        url: https://waf-doc.inext.checkpoint.com/\ncommon:\n  - type: Website\n    url: https://www.checkpoint.com/\n  - type: Documentation\n    url: https://sc1.checkpoint.com/documents/\n  - type: Support\n    url: https://www.checkpoint.com/support-services/\n  - type: Login\n    url: https://portal.checkpoint.com/\n  - type: Blog\n    url: https://blog.checkpoint.com/\n  - type: GitHub\n    url: https://github.com/CheckPointSW\n  - type: TermsOfService\n    url: https://www.checkpoint.com/about-us/terms-of-use/\n  - type: PrivacyPolicy\n    url: https://www.checkpoint.com/about-us/privacy-statement/\n  - type: JSONLD\n    url: json-ld/checkpoint-context.jsonld\n  - type: JSONSchema\n    url: json-schema/checkpoint-host-schema.json\n  - type: JSONSchema\n    url: json-schema/checkpoint-access-rule-schema.json\n  - type: Spectral\n    url: spectral/checkpoint-spectral.yml\n  - type: NaftikoCapabilities\n\
  \    url: naftiko/checkpoint-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/apis.yml
tags:
- Cloud Security
- Cybersecurity
- Endpoint Security
- Firewall
- Identity Awareness
- Mobile Security
- Network Security
- Security
- Threat Prevention
- WAF
url: https://raw.githubusercontent.com/api-evangelist/checkpoint/refs/heads/main/apis.yml
use_cases: []
---
