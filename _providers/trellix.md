---
api_count: 14
apis:
- description: McAfee ePolicy Orchestrator (ePO) REST API for centralized security management, policy enforcement, and reporting across the enterprise.
  name: Trellix ePO API
  slug: ''
- description: The Trellix ePO SaaS API provides cloud-based access to ePolicy Orchestrator management capabilities. It enables programmatic control of devices, events, tags, queries, and response actions through th
  name: Trellix ePO SaaS API
  slug: ''
- description: API for accessing threat intelligence, security analytics, and insights from the Trellix threat research platform. Provides investigation of indicators of compromise, campaign tracking, and prioritize
  name: Trellix Insights API
  slug: ''
- description: Endpoint Detection and Response API for advanced threat hunting, investigation, and automated response capabilities. The EDR API supports querying threat data, searching devices, retrieving action his
  name: Trellix EDR API
  slug: ''
- description: Messaging fabric API that enables real-time communication between security tools and data sharing across the security ecosystem. OpenDXL provides client libraries in Python, JavaScript, and Java for i
  name: Trellix Data Exchange Layer (DXL) API
  slug: ''
- description: REST API for the Trellix Endpoint Security (HX) platform, formerly FireEye HX. Provides programmatic access to endpoint information, acquisitions, alerts, indicators, conditions, and containment opera
  name: Trellix Endpoint Security (HX) API
  slug: ''
- description: REST API for Trellix Data Loss Prevention Endpoint that enables programmatic management of DLP policies, retrieval and analysis of data loss incidents, and integration with cloud gateways. Supports ap
  name: Trellix Data Loss Prevention (DLP) API
  slug: ''
- description: RESTful API for Trellix Email Security Cloud (formerly FireEye ETP) providing custom integration capabilities for advanced threat detection in email. Supports APIs for querying advanced threats, email
  name: Trellix Email Security Cloud API
  slug: ''
- description: API for the Trellix Helix security operations platform that integrates security controls from Trellix and over 500 third-party sources to create multi-vector threat detections and AI-guided responses.
  name: Trellix Helix API
  slug: ''
- description: REST API for Trellix Intelligent Sandbox (formerly Advanced Threat Defense) that enables automated submission and analysis of files and URLs in a sandboxed environment. Supports file submission, analy
  name: Trellix Intelligent Sandbox API
  slug: ''
- description: API for Trellix Threat Intelligence Exchange which acts as a reputation broker enabling real-time sharing of threat intelligence from global and local sources across the security ecosystem via the Dat
  name: Trellix Threat Intelligence Exchange (TIE) API
  slug: ''
- description: REST API interface for managing indicators of compromise within the Trellix security platform. Enables uploading, querying, and managing IOCs including file hashes, IP addresses, domains, and email ad
  name: Trellix IOC (Indicators of Compromise) API
  slug: ''
- description: API-driven malware detection service that leverages the Trellix Multi-Vector Virtual Execution (MVX) engine and multiple dynamic machine learning, AI, and correlation engines to analyze submitted file
  name: Trellix Detection as a Service API
  slug: ''
- description: Interactive API documentation and testing tool for Trellix security products formerly under the FireEye brand. Provides a web-based interface for exploring and testing API endpoints across multiple Tr
  name: Trellix API Explorer
  slug: ''
common:
- title: ''
  type: Portal
  url: https://www.trellix.com/
- title: ''
  type: Developer Portal
  url: https://developer.manage.trellix.com/
- title: ''
  type: Documentation
  url: https://docs.trellix.com/
- title: ''
  type: Authentication
  url: https://developer.manage.trellix.com/mvision/docs/umam
- title: ''
  type: GettingStarted
  url: https://developer.manage.trellix.com/mvision/docs/uma
- title: ''
  type: Support
  url: https://www.trellix.com/support/
- title: ''
  type: Login
  url: https://sso.trellix.com/
- title: ''
  type: Sign Up
  url: https://developer.manage.trellix.com/
- title: ''
  type: Community
  url: https://communitym.trellix.com/
- title: ''
  type: Status
  url: https://status.trellix.com/
- title: ''
  type: Blog
  url: https://www.trellix.com/blogs/
- title: ''
  type: Privacy Policy
  url: https://www.trellix.com/en-us/about/legal/privacy.html
- title: ''
  type: Terms of Service
  url: https://www.trellix.com/en-us/about/legal/terms-of-use.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/trellix-enterprise
- title: ''
  type: GitHubOrganization
  url: https://github.com/opendxl
- title: ''
  type: GitHubOrganization
  url: https://github.com/trellix-opensource
- title: ''
  type: GitHubOrganization
  url: https://github.com/advanced-threat-research
- title: ''
  type: Website
  url: https://www.trellix.com/
- title: ''
  type: Knowledge Base
  url: https://kcm.trellix.com/
- title: ''
  type: PostmanCollection
  url: https://www.postman.com/bmarandel/trellix-api-gateway/documentation/d3e3gan/trellix-api-gateway
- title: ''
  type: ReleaseNotes
  url: https://docs.trellix.com/bundle/trellix-developer-portal-and-marketplace-release-notes
created: '2024'
description: Trellix is a cybersecurity company that delivers comprehensive, open, and native extended detection and response (XDR) platform. The company provides threat detection, investigation, and response capabilities across endpoints, networks, data, and cloud environments.
features: []
image: https://www.trellix.com/favicon.ico
integrations: []
layout: provider
modified: '2026-03-16'
name: Trellix
skills: []
slug: trellix
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Trellix\ndescription: >-\n  Trellix is a cybersecurity company that delivers comprehensive, open, and native\n  extended detection and response (XDR) platform. The company provides threat detection,\n  investigation, and response capabilities across endpoints, networks, data, and cloud\n  environments.\nimage: https://www.trellix.com/favicon.ico\nurl: https://www.trellix.com\ncreated: '2024'\nmodified: '2026-03-16'\ntags:\n  - Cloud Security\n  - Cybersecurity\n  - Endpoint Security\n  - Threat Detection\n  - Threat Intelligence\n  - XDR\napis:\n  - name: Trellix ePO API\n    description: >-\n      McAfee ePolicy Orchestrator (ePO) REST API for centralized security management,\n      policy enforcement, and reporting across the enterprise.\n    image: https://www.trellix.com/favicon.ico\n    humanURL: https://docs.trellix.com/bundle/epolicy-orchestrator\n    baseURL: https://your-epo-server:8443/remote\n    tags:\n      - Endpoint Management\n      - Enterprise Security\n\
  \      - Policy Orchestration\n      - Security Management\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/epolicy-orchestrator\n      - type: Authentication\n        url: https://developer.manage.trellix.com/mvision/docs/umam\n      - type: GettingStarted\n        url: https://developer.manage.trellix.com/mvision/docs/uma\n      - type: APIReference\n        url: https://developer.manage.trellix.com/mvision/apis/v2-devices\n    contact:\n      - FN: Trellix Support\n        url: https://www.trellix.com/support/\n  - name: Trellix ePO SaaS API\n    description: >-\n      The Trellix ePO SaaS API provides cloud-based access to ePolicy\n      Orchestrator management capabilities. It enables programmatic control\n      of devices, events, tags, queries, and response actions through\n      the Trellix cloud management platform.\n    image: https://www.trellix.com/favicon.ico\n    humanURL: https://docs.trellix.com/bundle/epolicy-orchestrator-saas-product-guide\n\
  \    baseURL: https://api.manage.trellix.com\n    tags:\n      - Cloud Management\n      - Endpoint Management\n      - SaaS\n      - Security Management\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/epolicy-orchestrator-saas-product-guide\n      - type: Authentication\n        url: https://developer.manage.trellix.com/mvision/docs/umam\n      - type: GettingStarted\n        url: https://developer.manage.trellix.com/mvision/docs/uma\n  - name: Trellix Insights API\n    description: >-\n      API for accessing threat intelligence, security analytics, and\n      insights from the Trellix threat research platform. Provides\n      investigation of indicators of compromise, campaign tracking,\n      and prioritized threat intelligence for security operations.\n    image: https://www.trellix.com/favicon.ico\n    humanURL: https://docs.trellix.com/bundle/trellix-insights-product-guide\n    baseURL: https://api.manage.trellix.com\n    tags:\n     \
  \ - Analytics\n      - Security Insights\n      - Threat Intelligence\n      - Threat Research\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/trellix-insights-product-guide\n      - type: APIReference\n        url: https://docs.trellix.com/bundle/trellix-insights-product-guide/page/UUID-e5e4730b-ac74-d923-f691-168ea880e3cd.html\n  - name: Trellix EDR API\n    description: >-\n      Endpoint Detection and Response API for advanced threat hunting,\n      investigation, and automated response capabilities. The EDR API\n      supports querying threat data, searching devices, retrieving action\n      history, and executing real-time search and response actions across\n      managed endpoints.\n    image: https://www.trellix.com/favicon.ico\n    humanURL: https://docs.trellix.com/bundle/mvision-endpoint-detection-and-response-product-guide\n    baseURL: https://api.manage.trellix.com\n    tags:\n      - Endpoint Detection\n      - Forensics\n    \
  \  - Incident Response\n      - Threat Hunting\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/mvision-endpoint-detection-and-response-product-guide\n      - type: APIReference\n        url: https://docs.trellix.com/bundle/mvision-endpoint-detection-and-response-product-guide/page/UUID-d4602e2b-5adc-bdb4-c8cf-163997d5cd6e.html\n      - type: Authentication\n        url: https://developer.manage.trellix.com/mvision/docs/umam\n      - type: GitHubRepository\n        url: https://github.com/trellix-enterprise/EDR-Integration-Scripts\n  - name: Trellix Data Exchange Layer (DXL) API\n    description: >-\n      Messaging fabric API that enables real-time communication between\n      security tools and data sharing across the security ecosystem.\n      OpenDXL provides client libraries in Python, JavaScript, and Java\n      for integrating applications with the DXL message bus, enabling\n      automated threat response and security tool orchestration.\n\
  \    image: https://www.trellix.com/favicon.ico\n    humanURL: https://opendxl.github.io/\n    baseURL: https://dxl.trellix.com\n    tags:\n      - Automation\n      - Data Exchange\n      - Integration\n      - Messaging\n    properties:\n      - type: Documentation\n        url: https://opendxl.github.io/\n      - type: GitHubOrganization\n        url: https://github.com/opendxl\n      - type: SDKs\n        url: https://opendxl.github.io/opendxl-client-python/\n  - name: Trellix Endpoint Security (HX) API\n    description: >-\n      REST API for the Trellix Endpoint Security (HX) platform, formerly\n      FireEye HX. Provides programmatic access to endpoint information,\n      acquisitions, alerts, indicators, conditions, and containment\n      operations. Uses role-based access control with api_admin and\n      api_analyst user roles.\n    image: https://www.trellix.com/favicon.ico\n    humanURL: https://docs.trellix.com/bundle/hx_api_2020-2/page/UUID-973bb2b7-aeba-2ea1-afb9-7d20b136d3f6.html\n\
  \    baseURL: https://{hx-appliance}/hx/api/v3\n    tags:\n      - Containment\n      - Endpoint Security\n      - Incident Response\n      - Threat Detection\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/hx_api_2020-2/page/UUID-973bb2b7-aeba-2ea1-afb9-7d20b136d3f6.html\n      - type: APIReference\n        url: https://docs.trellix.com/bundle/hx_api_2020-2/page/UUID-33b4d7e3-a428-5137-d583-d40753483fbe.html\n      - type: GettingStarted\n        url: https://docs.trellix.com/bundle/api_1-0-0_ug/page/api-documentation-module-home-page/using-the-endpoint-security-apis.html\n  - name: Trellix Data Loss Prevention (DLP) API\n    description: >-\n      REST API for Trellix Data Loss Prevention Endpoint that enables\n      programmatic management of DLP policies, retrieval and analysis\n      of data loss incidents, and integration with cloud gateways. Supports\n      applying DLP policies, querying incident IDs for data-in-use and\n      data-in-motion\
  \ events, and retrieving incident details.\n    image: https://www.trellix.com/favicon.ico\n    humanURL: https://docs.trellix.com/bundle/data-loss-prevention-landing-page/page/UUID-d99a9913-80b8-d1b9-e030-9186ad9648ff.html\n    baseURL: https://{epo-server}:8443\n    tags:\n      - Compliance\n      - Data Loss Prevention\n      - Data Protection\n      - Incident Management\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/data-loss-prevention-landing-page/page/UUID-d99a9913-80b8-d1b9-e030-9186ad9648ff.html\n      - type: APIReference\n        url: https://docs.trellix.com/bundle/data-loss-prevention-11.11.x-product-guide/page/UUID-fde8c193-c95f-0f3c-2ccf-926691ea31d8.html\n  - name: Trellix Email Security Cloud API\n    description: >-\n      RESTful API for Trellix Email Security Cloud (formerly FireEye ETP)\n      providing custom integration capabilities for advanced threat\n      detection in email. Supports APIs for querying advanced threats,\n\
  \      email trace, and quarantine management operations.\n    image: https://www.trellix.com/favicon.ico\n    humanURL: https://docs.trellix.com/bundle/fe-email-cloud-landing/page/UUID-aa9b8905-c585-0327-7f24-f66ea402d3b6.html\n    baseURL: https://etp.us.fireeye.com/api/v1\n    tags:\n      - Cloud Security\n      - Email Security\n      - Quarantine\n      - Threat Detection\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/fe-email-cloud-landing/page/UUID-aa9b8905-c585-0327-7f24-f66ea402d3b6.html\n      - type: APIReference\n        url: https://docs.trellix.com/bundle/etp_api/page/UUID-30726aa3-e420-6f62-6b84-6ad0bdace483.html\n  - name: Trellix Helix API\n    description: >-\n      API for the Trellix Helix security operations platform that integrates\n      security controls from Trellix and over 500 third-party sources to\n      create multi-vector threat detections and AI-guided responses. The\n      Helix API supports querying alerts,\
  \ managing cases, searching events,\n      and automating security operations workflows.\n    image: https://www.trellix.com/favicon.ico\n    humanURL: https://www.trellix.com/products/helix/\n    baseURL: https://apps.fireeye.com/helix/api/v3\n    tags:\n      - Security Operations\n      - SIEM\n      - SOAR\n      - Threat Detection\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/helix_pg/page/UUID-889d9be0-0cc8-3ab3-cdb3-9aab24208509.html\n      - type: APIReference\n        url: https://docs.trellix.com/bundle/helix_pg/page/UUID-1fa29a61-f2d5-601e-dd27-e72f93627e59.html\n  - name: Trellix Intelligent Sandbox API\n    description: >-\n      REST API for Trellix Intelligent Sandbox (formerly Advanced Threat\n      Defense) that enables automated submission and analysis of files and\n      URLs in a sandboxed environment. Supports file submission, analysis\n      status queries, and report retrieval for malware detection and\n      threat analysis.\n\
  \    image: https://www.trellix.com/favicon.ico\n    humanURL: https://docs.trellix.com/bundle/trellix-intelligent-sandbox-5.0.x-api-reference-guide/page/GUID-F600CDC5-827A-4435-BD37-E0DF91810AB1.html\n    baseURL: https://{sandbox-server}/php\n    tags:\n      - File Analysis\n      - Malware Analysis\n      - Sandbox\n      - Threat Detection\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/trellix-intelligent-sandbox-5.0.x-api-reference-guide/page/GUID-F600CDC5-827A-4435-BD37-E0DF91810AB1.html\n      - type: GitHubRepository\n        url: https://github.com/trellix-opensource/intelligent-sandbox-api\n  - name: Trellix Threat Intelligence Exchange (TIE) API\n    description: >-\n      API for Trellix Threat Intelligence Exchange which acts as a reputation\n      broker enabling real-time sharing of threat intelligence from global\n      and local sources across the security ecosystem via the Data Exchange\n      Layer. The TIE API allows querying\
  \ file and certificate reputations,\n      setting local reputations, and receiving reputation change notifications.\n    image: https://www.trellix.com/favicon.ico\n    humanURL: https://docs.trellix.com/bundle/threat-intelligence-exchange-3.0.x-product-guide\n    baseURL: https://dxl.trellix.com\n    tags:\n      - Data Exchange\n      - Malware Detection\n      - Reputation\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/threat-intelligence-exchange-3.0.x-product-guide\n      - type: SDKs\n        url: https://github.com/opendxl/opendxl-tie-client-javascript\n  - name: Trellix IOC (Indicators of Compromise) API\n    description: >-\n      REST API interface for managing indicators of compromise within the\n      Trellix security platform. Enables uploading, querying, and managing\n      IOCs including file hashes, IP addresses, domains, and email addresses\n      for threat detection and investigation.\n    image:\
  \ https://www.trellix.com/favicon.ico\n    humanURL: https://docs.trellix.com/bundle/iocs_1-2-144_ug/page/UUID-d981cbd0-d535-dd8f-7cf8-a287bf077392.html\n    baseURL: https://{hx-appliance}/hx/api/v3\n    tags:\n      - Indicators of Compromise\n      - Security Operations\n      - Threat Detection\n      - Threat Intelligence\n    properties:\n      - type: Documentation\n        url: https://docs.trellix.com/bundle/iocs_1-2-144_ug/page/UUID-d981cbd0-d535-dd8f-7cf8-a287bf077392.html\n      - type: APIReference\n        url: https://docs.trellix.com/bundle/iocs_1-2-144_ug/page/UUID-11acd4c1-f095-333a-c394-5bfbf0a69823.html\n  - name: Trellix Detection as a Service API\n    description: >-\n      API-driven malware detection service that leverages the Trellix\n      Multi-Vector Virtual Execution (MVX) engine and multiple dynamic\n      machine learning, AI, and correlation engines to analyze submitted\n      files. Designed for integration into security operations workflows,\n      SIEM\
  \ systems, and custom web applications.\n    image: https://www.trellix.com/favicon.ico\n    humanURL: https://www.trellix.com/products/detection-as-a-service/\n    baseURL: https://feapi.marketplace.apps.fireeye.com\n    tags:\n      - Cloud Security\n      - File Analysis\n      - Malware Detection\n      - Threat Detection\n    properties:\n      - type: Documentation\n        url: https://developer.manage.trellix.com/mvision/docs/uma\n  - name: Trellix API Explorer\n    description: >-\n      Interactive API documentation and testing tool for Trellix security\n      products formerly under the FireEye brand. Provides a web-based\n      interface for exploring and testing API endpoints across multiple\n      Trellix product lines with regional endpoint support for US, EU,\n      and AP data centers.\n    image: https://www.trellix.com/favicon.ico\n    humanURL: https://api-docs.us.fireeye.com/\n    baseURL: https://api-docs.us.fireeye.com\n    tags:\n      - API Explorer\n      - Developer\
  \ Tools\n      - Documentation\n      - Testing\n    properties:\n      - type: Documentation\n        url: https://api-docs.us.fireeye.com/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncommon:\n  - type: Portal\n    url: https://www.trellix.com/\n  - type: Developer Portal\n    url: https://developer.manage.trellix.com/\n  - type: Documentation\n    url: https://docs.trellix.com/\n  - type: Authentication\n    url: https://developer.manage.trellix.com/mvision/docs/umam\n  - type: GettingStarted\n    url: https://developer.manage.trellix.com/mvision/docs/uma\n  - type: Support\n    url: https://www.trellix.com/support/\n  - type: Login\n    url: https://sso.trellix.com/\n  - type: Sign Up\n    url: https://developer.manage.trellix.com/\n  - type: Community\n    url: https://communitym.trellix.com/\n  - type: Status\n    url: https://status.trellix.com/\n  - type: Blog\n    url: https://www.trellix.com/blogs/\n  - type: Privacy Policy\n\
  \    url: https://www.trellix.com/en-us/about/legal/privacy.html\n  - type: Terms of Service\n    url: https://www.trellix.com/en-us/about/legal/terms-of-use.html\n  - type: GitHubOrganization\n    url: https://github.com/trellix-enterprise\n  - type: GitHubOrganization\n    url: https://github.com/opendxl\n  - type: GitHubOrganization\n    url: https://github.com/trellix-opensource\n  - type: GitHubOrganization\n    url: https://github.com/advanced-threat-research\n  - type: Website\n    url: https://www.trellix.com/\n  - type: Knowledge Base\n    url: https://kcm.trellix.com/\n  - type: PostmanCollection\n    url: https://www.postman.com/bmarandel/trellix-api-gateway/documentation/d3e3gan/trellix-api-gateway\n  - type: ReleaseNotes\n    url: https://docs.trellix.com/bundle/trellix-developer-portal-and-marketplace-release-notes\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/trellix/refs/heads/main/apis.yml
tags:
- Cloud Security
- Cybersecurity
- Endpoint Security
- Threat Detection
- Threat Intelligence
- XDR
url: https://www.trellix.com
use_cases: []
---
