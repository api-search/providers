---
api_count: 7
api_specs:
- filename: red-hat-3scale-service-management-openapi.yml
  format: yaml
  label: Red Hat 3scale Service Management API
  slug: service-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/openapi/red-hat-3scale-service-management-openapi.yml
- filename: red-hat-3scale-account-management-openapi.yml
  format: yaml
  label: Red Hat 3scale Account Management API
  slug: account-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/openapi/red-hat-3scale-account-management-openapi.yml
- filename: red-hat-3scale-analytics-openapi.yml
  format: yaml
  label: Red Hat 3scale Analytics API
  slug: analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/openapi/red-hat-3scale-analytics-openapi.yml
- filename: red-hat-3scale-billing-openapi.yml
  format: yaml
  label: Red Hat 3scale Billing API
  slug: billing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/openapi/red-hat-3scale-billing-openapi.yml
- filename: red-hat-3scale-apicast-management-openapi.yml
  format: yaml
  label: Red Hat 3scale APIcast Management API
  slug: apicast-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/openapi/red-hat-3scale-apicast-management-openapi.yml
apis:
- description: The 3scale Service Management API allows API providers to control and manage access to their APIs, track usage, and enforce traffic policies. It is used by the API gateway (APIcast) to authorize and r
  name: Red Hat 3scale Service Management API
  slug: service-management-api
- description: The 3scale Account Management API provides programmatic access to manage developer accounts, applications, application plans, keys, and API subscriptions within the 3scale platform. It enables automat
  name: Red Hat 3scale Account Management API
  slug: account-management-api
- description: 'The 3scale Analytics API provides access to API usage data, traffic metrics, hit counts, and reporting for APIs managed through the 3scale platform. It enables operators to retrieve usage statistics, '
  name: Red Hat 3scale Analytics API
  slug: analytics-api
- description: The 3scale Billing API enables management of billing and invoicing for API usage within the 3scale platform. It supports creating and managing invoices, payment transactions, and monetization of API s
  name: Red Hat 3scale Billing API
  slug: billing-api
- description: 3scale Webhooks allow API providers to receive real-time HTTP callbacks about account, application, user, and plan events within the 3scale platform. Webhooks can be configured to trigger external sys
  name: Red Hat 3scale Webhooks
  slug: webhooks-api
- description: The APIcast Management API is an HTTP REST interface exposed by the APIcast API gateway on port 8090 for debugging and runtime configuration. It provides endpoints to retrieve and update the gateway c
  name: Red Hat 3scale APIcast Management API
  slug: apicast-management-api
- description: The 3scale Toolbox is a command-line interface for automating 3scale configuration tasks. It wraps the 3scale Admin REST API to support copying APIs between tenants, promoting configurations between s
  name: Red Hat 3scale Toolbox CLI
  slug: toolbox-cli
capabilities:
- description: Unified capability for managing APIs, developer accounts, applications, and monitoring usage through the Red Hat 3scale API Management platform. Combines the Service Management API for gateway authori
  name: Red Hat 3scale API Management
  slug: api-management
common:
- title: ''
  type: Website
  url: https://www.redhat.com/en/technologies/jboss-middleware/3scale
- title: ''
  type: Documentation
  url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management
- title: ''
  type: Getting Started
  url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/getting_started/index
- title: ''
  type: Portal
  url: https://access.redhat.com/products/red-hat-3scale-api-management
- title: ''
  type: GitHub Organization
  url: https://github.com/3scale
- title: ''
  type: GitHubRepository
  url: https://github.com/3scale/APIcast
- title: ''
  type: GitHubRepository
  url: https://github.com/3scale/porta
- title: ''
  type: GitHubRepository
  url: https://github.com/3scale/3scale_toolbox
- title: ''
  type: Blog
  url: https://www.redhat.com/en/blog/channel/red-hat-middleware
- title: ''
  type: Support
  url: https://access.redhat.com/support
- title: ''
  type: Terms of Service
  url: https://www.redhat.com/en/about/agreements
- title: ''
  type: Privacy Policy
  url: https://www.redhat.com/en/about/privacy-policy
- title: ''
  type: Status
  url: https://status.redhat.com/
- title: ''
  type: Changelog
  url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/release_notes/index
- title: ''
  type: OpenAPI
  url: openapi/red-hat-3scale-service-management-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/red-hat-3scale-account-management-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/red-hat-3scale-analytics-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/red-hat-3scale-billing-openapi.yml
- title: ''
  type: OpenAPI
  url: openapi/red-hat-3scale-apicast-management-openapi.yml
- title: ''
  type: JSONLDContext
  url: json-ld/red-hat-3scale-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/red-hat-3scale-account-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/red-hat-3scale-application-schema.json
- title: ''
  type: JSONStructure
  url: json-structure/red-hat-3scale-account-structure.json
- title: ''
  type: SpectralRuleset
  url: rules/red-hat-3scale-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/api-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/red-hat-3scale-vocabulary.yml
created: '2026-03-16'
description: Red Hat 3scale API Management is an enterprise-grade API management platform that enables organizations to share, secure, distribute, control, and monetize APIs across internal and external teams. It provides a developer portal, analytics, access control, policy enforcement, and billing for REST, SOAP, GraphQL, and other API types. 3scale runs on-premises via OpenShift or as a hosted managed service, and is fully Kubernetes-native.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Red Hat 3Scale Context
  property_count: 20
  slug: red-hat-3scale-context
layout: provider
modified: '2026-05-02'
name: Red Hat 3scale
rules:
- name: Red Hat 3scale API Rules
  rule_count: 12
  severity_counts:
    error: 3
    hint: 0
    info: 2
    warn: 7
  slug: red-hat-3scale-rules
skills: []
slug: red-hat-3scale
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: red-hat-3scale\nname: Red Hat 3scale\ndescription: >-\n  Red Hat 3scale API Management is an enterprise-grade API management platform\n  that enables organizations to share, secure, distribute, control, and monetize\n  APIs across internal and external teams. It provides a developer portal,\n  analytics, access control, policy enforcement, and billing for REST, SOAP,\n  GraphQL, and other API types. 3scale runs on-premises via OpenShift or as a\n  hosted managed service, and is fully Kubernetes-native.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - API Management\n  - Developer Portal\n  - Enterprise\n  - Red Hat\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-05-02'\nspecificationVersion: '0.19'\napis:\n  - aid: red-hat-3scale:service-management-api\n    name: Red Hat 3scale Service Management API\n \
  \   description: >-\n      The 3scale Service Management API allows API providers to control and\n      manage access to their APIs, track usage, and enforce traffic policies.\n      It is used by the API gateway (APIcast) to authorize and report API calls\n      in real time. The API supports both API key and OAuth 2.0 based\n      authorization flows. Calls are made from the API gateway on behalf of the\n      API consumer application.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management\n    baseURL: https://su1.3scale.net\n    tags:\n      - Access Control\n      - API Management\n      - Authorization\n      - Traffic Management\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/api_authentication/index\n      - type: Reference\n        url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/index\n\
  \      - type: OpenAPI\n        url: openapi/red-hat-3scale-service-management-openapi.yml\n\n  - aid: red-hat-3scale:account-management-api\n    name: Red Hat 3scale Account Management API\n    description: >-\n      The 3scale Account Management API provides programmatic access to manage\n      developer accounts, applications, application plans, keys, and API\n      subscriptions within the 3scale platform. It enables automation of\n      developer onboarding, subscription management, and application lifecycle\n      operations from external systems or scripts. The API is accessible on the\n      admin domain and requires admin API credentials.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/index\n    baseURL: https://{your-domain}-admin.3scale.net\n    tags:\n      - Account Management\n      - API Management\n      - Applications\n      - Developer Portal\n    properties:\n      - type: Documentation\n      \
  \  url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/index\n      - type: Reference\n        url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/accounts\n      - type: OpenAPI\n        url: openapi/red-hat-3scale-account-management-openapi.yml\n\n  - aid: red-hat-3scale:analytics-api\n    name: Red Hat 3scale Analytics API\n    description: >-\n      The 3scale Analytics API provides access to API usage data, traffic\n      metrics, hit counts, and reporting for APIs managed through the 3scale\n      platform. It enables operators to retrieve usage statistics, query by\n      time period and granularity, and integrate analytics data into external\n      dashboards or monitoring systems.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/analytics\n    baseURL: https://{your-domain}-admin.3scale.net\n\
  \    tags:\n      - Analytics\n      - API Management\n      - Metrics\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/analytics\n      - type: OpenAPI\n        url: openapi/red-hat-3scale-analytics-openapi.yml\n\n  - aid: red-hat-3scale:billing-api\n    name: Red Hat 3scale Billing API\n    description: >-\n      The 3scale Billing API enables management of billing and invoicing for\n      API usage within the 3scale platform. It supports creating and managing\n      invoices, payment transactions, and monetization of API subscriptions\n      based on usage plans and application metrics. Billing is integrated with\n      the account management system.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/billing\n    baseURL: https://{your-domain}-admin.3scale.net\n    tags:\n      - API\
  \ Management\n      - Billing\n      - Invoices\n      - Monetization\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/billing\n      - type: OpenAPI\n        url: openapi/red-hat-3scale-billing-openapi.yml\n\n  - aid: red-hat-3scale:webhooks-api\n    name: Red Hat 3scale Webhooks\n    description: >-\n      3scale Webhooks allow API providers to receive real-time HTTP callbacks\n      about account, application, user, and plan events within the 3scale\n      platform. Webhooks can be configured to trigger external systems when\n      subscriptions change, new developers sign up, applications are updated,\n      or keys are created or deleted.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/webhooks\n    tags:\n      - API Management\n      - Events\n      - Notifications\n      - Webhooks\n    properties:\n\
  \      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/admin_portal_guide/webhooks\n\n  - aid: red-hat-3scale:apicast-management-api\n    name: Red Hat 3scale APIcast Management API\n    description: >-\n      The APIcast Management API is an HTTP REST interface exposed by the\n      APIcast API gateway on port 8090 for debugging and runtime configuration.\n      It provides endpoints to retrieve and update the gateway configuration,\n      inspect DNS cache, trigger boot/initialization, and check readiness and\n      liveness health status. Access is controlled via the\n      APICAST_MANAGEMENT_API environment variable.\n    humanURL: https://github.com/3scale/APIcast/blob/master/doc/management-api.md\n    baseURL: http://localhost:8090\n    tags:\n      - API Gateway\n      - Configuration\n      - Health Checks\n      - Management\n    properties:\n      - type: Documentation\n        url: https://github.com/3scale/APIcast/blob/master/doc/management-api.md\n\
  \      - type: OpenAPI\n        url: openapi/red-hat-3scale-apicast-management-openapi.yml\n\n  - aid: red-hat-3scale:toolbox-cli\n    name: Red Hat 3scale Toolbox CLI\n    description: >-\n      The 3scale Toolbox is a command-line interface for automating 3scale\n      configuration tasks. It wraps the 3scale Admin REST API to support\n      copying APIs between tenants, promoting configurations between staging\n      and production environments, importing OpenAPI specifications, and\n      managing application plans and policies from the command line or CI/CD\n      pipelines.\n    humanURL: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/operating_3scale/the-threescale-toolbox\n    tags:\n      - API Management\n      - Automation\n      - CLI\n      - DevOps\n    properties:\n      - type: Documentation\n        url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/operating_3scale/the-threescale-toolbox\n\
  \      - type: GitHub\n        url: https://github.com/3scale/3scale_toolbox\n\ncommon:\n  - type: Website\n    url: https://www.redhat.com/en/technologies/jboss-middleware/3scale\n  - type: Documentation\n    url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management\n  - type: Getting Started\n    url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/getting_started/index\n  - type: Portal\n    url: https://access.redhat.com/products/red-hat-3scale-api-management\n  - type: GitHub Organization\n    url: https://github.com/3scale\n  - type: GitHubRepository\n    url: https://github.com/3scale/APIcast\n  - type: GitHubRepository\n    url: https://github.com/3scale/porta\n  - type: GitHubRepository\n    url: https://github.com/3scale/3scale_toolbox\n  - type: Blog\n    url: https://www.redhat.com/en/blog/channel/red-hat-middleware\n  - type: Support\n    url: https://access.redhat.com/support\n  - type: Terms of Service\n    url:\
  \ https://www.redhat.com/en/about/agreements\n  - type: Privacy Policy\n    url: https://www.redhat.com/en/about/privacy-policy\n  - type: Status\n    url: https://status.redhat.com/\n  - type: Changelog\n    url: https://access.redhat.com/documentation/en-us/red_hat_3scale_api_management/2.14/html/release_notes/index\n  - type: OpenAPI\n    url: openapi/red-hat-3scale-service-management-openapi.yml\n  - type: OpenAPI\n    url: openapi/red-hat-3scale-account-management-openapi.yml\n  - type: OpenAPI\n    url: openapi/red-hat-3scale-analytics-openapi.yml\n  - type: OpenAPI\n    url: openapi/red-hat-3scale-billing-openapi.yml\n  - type: OpenAPI\n    url: openapi/red-hat-3scale-apicast-management-openapi.yml\n  - type: JSONLDContext\n    url: json-ld/red-hat-3scale-context.jsonld\n  - type: JSONSchema\n    url: json-schema/red-hat-3scale-account-schema.json\n  - type: JSONSchema\n    url: json-schema/red-hat-3scale-application-schema.json\n  - type: JSONStructure\n    url: json-structure/red-hat-3scale-account-structure.json\n\
  \  - type: SpectralRuleset\n    url: rules/red-hat-3scale-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/api-management.yaml\n  - type: Vocabulary\n    url: vocabulary/red-hat-3scale-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/apis.yml
tags:
- API Gateway
- API Management
- Developer Portal
- Enterprise
- Red Hat
url: https://raw.githubusercontent.com/api-evangelist/red-hat-3scale/refs/heads/main/apis.yml
use_cases: []
---
