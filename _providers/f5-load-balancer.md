---
api_count: 3
api_specs:
- filename: f5-load-balancer-icontrol-rest-openapi.yml
  format: yaml
  label: F5 BIG-IP iControl REST API
  slug: f5-bigip-icontrol-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/f5-load-balancer/refs/heads/main/openapi/f5-load-balancer-icontrol-rest-openapi.yml
- filename: f5-load-balancer-as3-openapi.yml
  format: yaml
  label: F5 BIG-IP AS3 API
  slug: f5-bigip-as3-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/f5-load-balancer/refs/heads/main/openapi/f5-load-balancer-as3-openapi.yml
- filename: f5-load-balancer-declarative-onboarding-openapi.yml
  format: yaml
  label: F5 BIG-IP Declarative Onboarding API
  slug: f5-bigip-declarative-onboarding-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/f5-load-balancer/refs/heads/main/openapi/f5-load-balancer-declarative-onboarding-openapi.yml
apis:
- description: Primary REST API for managing F5 BIG-IP systems including virtual servers, pools, nodes, and policies for application delivery and load balancing.
  name: F5 BIG-IP iControl REST API
  slug: f5-bigip-icontrol-rest-api
- description: Application Services 3 Extension for declarative API-based application deployment using JSON declarations.
  name: F5 BIG-IP AS3 API
  slug: f5-bigip-as3-api
- description: Declarative Onboarding (DO) extension for initial BIG-IP system configuration and provisioning via JSON declarations covering licensing, networking, user management, and module provisioning.
  name: F5 BIG-IP Declarative Onboarding API
  slug: f5-bigip-declarative-onboarding-api
common:
- title: ''
  type: Portal
  url: https://clouddocs.f5.com/
- title: ''
  type: Documentation
  url: https://clouddocs.f5.com/api/
- title: ''
  type: Support
  url: https://www.f5.com/services/support
- title: ''
  type: TermsOfService
  url: https://www.f5.com/company/policies/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.f5.com/company/policies/privacy-notice
- title: ''
  type: Blog
  url: https://www.f5.com/company/blog
- title: ''
  type: GitHubOrganization
  url: https://github.com/F5Networks
- title: ''
  type: Website
  url: https://www.f5.com
created: '2024-01-01'
description: APIs for managing F5 BIG-IP Load Balancer configuration, monitoring, and operations. F5 BIG-IP is an application delivery controller that provides intelligent traffic management, load balancing, and application security.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: F5 Load Balancer
skills: []
slug: f5-load-balancer
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: f5-load-balancer\nname: F5 Load Balancer\ndescription: >-\n  APIs for managing F5 BIG-IP Load Balancer configuration, monitoring, and\n  operations. F5 BIG-IP is an application delivery controller that provides\n  intelligent traffic management, load balancing, and application security.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Application Delivery\n  - BIG-IP\n  - Load Balancer\n  - Networking\n  - Traffic Management\nurl: https://www.f5.com\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nposition: Consumer\naccess: 3rd-Party\nspecificationVersion: '0.19'\napis:\n  - aid: f5-load-balancer:f5-bigip-icontrol-rest-api\n    name: F5 BIG-IP iControl REST API\n    description: >-\n      Primary REST API for managing F5 BIG-IP systems including virtual servers,\n      pools, nodes, and policies for application delivery and load balancing.\n    humanURL: https://clouddocs.f5.com/api/icontrol-rest/\n    baseURL:\
  \ https://bigip-host/mgmt/tm\n    tags:\n      - Configuration\n      - Management\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://clouddocs.f5.com/api/icontrol-rest/\n      - type: Authentication\n        url: https://clouddocs.f5.com/api/icontrol-rest/Authentication.html\n      - type: OpenAPI\n        url: openapi/f5-load-balancer-icontrol-rest-openapi.yml\n  - aid: f5-load-balancer:f5-bigip-as3-api\n    name: F5 BIG-IP AS3 API\n    description: >-\n      Application Services 3 Extension for declarative API-based application\n      deployment using JSON declarations.\n    humanURL: https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/\n    baseURL: https://bigip-host/mgmt/shared/appsvcs\n    tags:\n      - AS3\n      - Automation\n      - Declarative\n    properties:\n      - type: Documentation\n        url: https://clouddocs.f5.com/products/extensions/f5-appsvcs-extension/latest/\n      - type: OpenAPI\n        url: openapi/f5-load-balancer-as3-openapi.yml\n\
  \  - aid: f5-load-balancer:f5-bigip-declarative-onboarding-api\n    name: F5 BIG-IP Declarative Onboarding API\n    description: >-\n      Declarative Onboarding (DO) extension for initial BIG-IP system\n      configuration and provisioning via JSON declarations covering\n      licensing, networking, user management, and module provisioning.\n    humanURL: https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/\n    baseURL: https://bigip-host/mgmt/shared/declarative-onboarding\n    tags:\n      - Declarative\n      - Onboarding\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://clouddocs.f5.com/products/extensions/f5-declarative-onboarding/latest/\n      - type: OpenAPI\n        url: openapi/f5-load-balancer-declarative-onboarding-openapi.yml\ncommon:\n  - type: Portal\n    url: https://clouddocs.f5.com/\n  - type: Documentation\n    url: https://clouddocs.f5.com/api/\n  - type: Support\n    url: https://www.f5.com/services/support\n\
  \  - type: TermsOfService\n    url: https://www.f5.com/company/policies/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.f5.com/company/policies/privacy-notice\n  - type: Blog\n    url: https://www.f5.com/company/blog\n  - type: GitHubOrganization\n    url: https://github.com/F5Networks\n  - type: Website\n    url: https://www.f5.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/f5-load-balancer/refs/heads/main/apis.yml
tags:
- Application Delivery
- BIG-IP
- Load Balancer
- Networking
- Traffic Management
url: https://www.f5.com
use_cases: []
---
