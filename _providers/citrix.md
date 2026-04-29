---
api_count: 12
api_specs:
- filename: citrix-daas-openapi.yml
  format: yaml
  label: Citrix Virtual Apps and Desktops REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/openapi/citrix-daas-openapi.yml
- filename: citrix-adc-nitro-openapi.yml
  format: yaml
  label: Citrix ADC (NetScaler) NITRO API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/openapi/citrix-adc-nitro-openapi.yml
- filename: citrix-daas-openapi.yml
  format: yaml
  label: Citrix DaaS REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/openapi/citrix-daas-openapi.yml
- filename: citrix-cloud-openapi.yml
  format: yaml
  label: Citrix Cloud API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/openapi/citrix-cloud-openapi.yml
- filename: citrix-storefront-web-openapi.yml
  format: yaml
  label: Citrix StoreFront Web API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/openapi/citrix-storefront-web-openapi.yml
- filename: citrix-endpoint-management-openapi.yml
  format: yaml
  label: Citrix Endpoint Management REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/openapi/citrix-endpoint-management-openapi.yml
- filename: citrix-secure-private-access-openapi.yml
  format: yaml
  label: Citrix Secure Private Access API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/openapi/citrix-secure-private-access-openapi.yml
apis:
- description: Manage and monitor Citrix Virtual Apps and Desktops deployments.
  name: Citrix Virtual Apps and Desktops REST API
  slug: ''
- description: Integrate and customize Citrix Workspace for end users.
  name: Citrix Workspace API
  slug: ''
- description: Configure and monitor Citrix ADC application delivery controllers.
  name: Citrix ADC (NetScaler) NITRO API
  slug: ''
- description: Manage Citrix Desktop as a Service (DaaS) cloud deployments.
  name: Citrix DaaS REST API
  slug: ''
- description: Access analytics data for security and performance insights.
  name: Citrix Analytics API
  slug: ''
- description: Platform-level API for managing Citrix Cloud services, including authentication, service principals, resource locations, and notifications across the Citrix Cloud platform.
  name: Citrix Cloud API
  slug: ''
- description: OData-based API for querying monitoring data from Citrix Virtual Apps and Desktops deployments, including session, connection, machine, and application usage data for reporting and analytics.
  name: Citrix Monitor Service OData API
  slug: ''
- description: HTTP API for building custom client applications that authenticate users, enumerate available applications and desktops, manage HDX sessions, and launch resources from Citrix StoreFront.
  name: Citrix StoreFront Web API
  slug: ''
- description: Server-side API for customizing and extending the Citrix StoreFront store services, including endpoint management, authentication, and resource enumeration behaviors.
  name: Citrix StoreFront Store Services API
  slug: ''
- description: SDK for building custom authentication methods for Citrix StoreFront, allowing integration with third-party identity providers and custom authentication workflows.
  name: Citrix StoreFront Authentication SDK
  slug: ''
- description: REST API for managing mobile devices, applications, and policies in Citrix Endpoint Management, enabling integration with external systems for device lifecycle management and compliance.
  name: Citrix Endpoint Management REST API
  slug: ''
- description: REST API for managing zero trust network access policies, applications, application domains, and certificates in Citrix Secure Private Access, providing secure access to internal web and SaaS applicat
  name: Citrix Secure Private Access API
  slug: ''
capabilities: []
common:
- title: ''
  type: Portal
  url: https://developer-docs.citrix.com/
- title: ''
  type: Getting Started
  url: https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html
- title: ''
  type: Authentication
  url: https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html
- title: ''
  type: Blog
  url: https://www.citrix.com/blogs/
- title: ''
  type: Status
  url: https://status.cloud.com/
- title: ''
  type: Support
  url: https://support.citrix.com/
- title: ''
  type: Terms of Service
  url: https://developer.cloud.com/citrix-developer-terms-of-use
- title: ''
  type: Privacy Policy
  url: https://www.citrix.com/about/legal/privacy/plain.html
- title: ''
  type: GitHub Organization
  url: https://github.com/citrix
- title: ''
  type: Community
  url: https://discussions.citrix.com/
- title: ''
  type: SDKs
  url: https://docs.citrix.com/en-us/citrix-cloud/sdk-api.html
- title: ''
  type: Website
  url: https://www.citrix.com
- title: ''
  type: Login
  url: https://accounts.cloud.com/
- title: ''
  type: JSON-LD
  url: json-ld/citrix-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/citrix-machine-catalog-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/citrix-session-schema.json
- title: ''
  type: Spectral
  url: rules/citrix-rules.yml
- title: ''
  type: Naftiko Capabilities
  url: capabilities/citrix-capabilities.yml
created: '2024-01-01'
description: Citrix is a global software company providing virtualization, networking, workspace, and digital experience products that allow organizations to deliver applications and desktops securely from data centers and clouds to any device. Citrix exposes its programmable surface through the Citrix Cloud platform and developer.citrix.com / developer-docs.citrix.com, with REST APIs spanning Virtual Apps and Desktops, DaaS, Workspace, Citrix Cloud, ADC (NetScaler) NITRO, Endpoint Management, Secure Private Access, and Analytics. Authentication uses OAuth 2.0 bearer tokens issued through Citrix Cloud customer-id-scoped credentials.
features: []
image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Citrix Context
  property_count: 8
  slug: citrix-context
layout: provider
modified: '2026-04-23'
name: Citrix
rules:
- name: Citrix API Rules
  rule_count: 7
  severity_counts:
    error: 4
    hint: 0
    info: 0
    warn: 3
  slug: citrix-rules
skills: []
slug: citrix
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: citrix\nname: Citrix\ndescription: >-\n  Citrix is a global software company providing virtualization, networking,\n  workspace, and digital experience products that allow organizations to\n  deliver applications and desktops securely from data centers and clouds\n  to any device. Citrix exposes its programmable surface through the\n  Citrix Cloud platform and developer.citrix.com / developer-docs.citrix.com,\n  with REST APIs spanning Virtual Apps and Desktops, DaaS, Workspace,\n  Citrix Cloud, ADC (NetScaler) NITRO, Endpoint Management, Secure Private\n  Access, and Analytics. Authentication uses OAuth 2.0 bearer tokens\n  issued through Citrix Cloud customer-id-scoped credentials.\nimage: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\nurl: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-23'\ntype: Index\naccess: 3rd-Party\nposition: Consumer\nspecificationVersion:\
  \ '0.19'\ntags:\n  - Application Delivery\n  - Desktop-As-A-Service\n  - Networking\n  - Virtualization\n  - Workspace\napis:\n  - name: Citrix Virtual Apps and Desktops REST API\n    description: >-\n      Manage and monitor Citrix Virtual Apps and Desktops deployments.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://developer.citrix.com/citrix-virtual-apps-and-desktops\n    baseURL: https://{customer-id}.xendesktop.net\n    tags:\n      - Remote Access\n      - VDI\n      - Virtual Desktop\n    properties:\n      - type: Documentation\n        url: https://developer.citrix.com/citrix-virtual-apps-and-desktops/citrix-cvad-rest-apis\n      - type: OpenAPI\n        url: https://developer.citrix.com/citrix-virtual-apps-and-desktops/citrix-cvad-rest-apis/docs/openapi\n      - type: Authentication\n        url: https://developer.citrix.com/citrix-virtual-apps-and-desktops/citrix-cvad-rest-apis/docs/how-to-get-started\n      -\
  \ type: OpenAPI\n        url: openapi/citrix-daas-openapi.yml\n  - name: Citrix Workspace API\n    description: >-\n      Integrate and customize Citrix Workspace for end users.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://developer.citrix.com/citrix-workspace\n    baseURL: https://api.cloud.com\n    tags:\n      - SSO\n      - User Experience\n      - Workspace\n    properties:\n      - type: Documentation\n        url: https://developer.citrix.com/citrix-workspace/citrix-workspace-platform\n      - type: API Reference\n        url: https://developer.citrix.com/citrix-workspace/citrix-workspace-platform/build/api-reference\n  - name: Citrix ADC (NetScaler) NITRO API\n    description: >-\n      Configure and monitor Citrix ADC application delivery controllers.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://developer.citrix.com/citrix-adc\n    baseURL: https://{netscaler-ip}/nitro/v1\n\
  \    tags:\n      - ADC\n      - Application Delivery\n      - Load Balancing\n      - Networking\n    properties:\n      - type: Documentation\n        url: https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/latest/\n      - type: API Reference\n        url: https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/latest/api-reference/\n      - type: SDK\n        url: https://developer-docs.citrix.com/projects/netscaler-nitro-api/en/latest/getting-started/\n      - type: OpenAPI\n        url: openapi/citrix-adc-nitro-openapi.yml\n  - name: Citrix DaaS REST API\n    description: >-\n      Manage Citrix Desktop as a Service (DaaS) cloud deployments.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://developer.citrix.com/citrix-daas\n    baseURL: https://api.cloud.com/cvad\n    tags:\n      - Cloud\n      - DaaS\n      - Desktop as a Service\n    properties:\n      - type: Documentation\n        url: https://developer.citrix.com/citrix-daas/citrix-daas-rest-apis\n\
  \      - type: OpenAPI\n        url: https://developer.citrix.com/citrix-daas/citrix-daas-rest-apis/docs/openapi\n      - type: Getting Started\n        url: https://developer.citrix.com/citrix-daas/citrix-daas-rest-apis/docs/getting-started\n      - type: OpenAPI\n        url: openapi/citrix-daas-openapi.yml\n  - name: Citrix Analytics API\n    description: >-\n      Access analytics data for security and performance insights.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://developer.citrix.com/citrix-analytics\n    baseURL: https://api.analytics.cloud.com\n    tags:\n      - Analytics\n      - Insights\n      - Monitoring\n      - Security\n    properties:\n      - type: Documentation\n        url: https://developer.citrix.com/citrix-analytics/api-overview\n      - type: API Reference\n        url: https://developer.citrix.com/citrix-analytics/api-reference\n  - name: Citrix Cloud API\n    description: >-\n      Platform-level\
  \ API for managing Citrix Cloud services, including\n      authentication, service principals, resource locations, and\n      notifications across the Citrix Cloud platform.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html\n    baseURL: https://api.cloud.com\n    tags:\n      - Cloud\n      - Identity\n      - Management\n      - Platform\n    properties:\n      - type: Documentation\n        url: https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html\n      - type: Getting Started\n        url: https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/citrix-cloud-api-walkthrough.html\n      - type: Authentication\n        url: https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html\n\
  \      - type: OpenAPI\n        url: openapi/citrix-cloud-openapi.yml\n  - name: Citrix Monitor Service OData API\n    description: >-\n      OData-based API for querying monitoring data from Citrix Virtual Apps\n      and Desktops deployments, including session, connection, machine, and\n      application usage data for reporting and analytics.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://developer-docs.citrix.com/en-us/monitor-service-odata-api/overview.html\n    baseURL: https://{delivery-controller}/Citrix/Monitor/OData/v4/Data\n    tags:\n      - Analytics\n      - Monitoring\n      - OData\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://developer-docs.citrix.com/en-us/monitor-service-odata-api/overview.html\n      - type: Reference\n        url: https://developer-docs.citrix.com/en-us/monitor-service-odata-api/monitor-service-resources.html\n      - type: Getting Started\n  \
  \      url: https://developer-docs.citrix.com/en-us/monitor-service-odata-api/access-methods.html\n  - name: Citrix StoreFront Web API\n    description: >-\n      HTTP API for building custom client applications that authenticate\n      users, enumerate available applications and desktops, manage HDX\n      sessions, and launch resources from Citrix StoreFront.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://developer-docs.citrix.com/en-us/storefront/storefront-web-api/overview.html\n    baseURL: https://{storefront-server}/Citrix/Store\n    tags:\n      - Client\n      - Resources\n      - Sessions\n      - StoreFront\n    properties:\n      - type: Documentation\n        url: https://developer-docs.citrix.com/en-us/storefront/storefront-web-api/overview.html\n      - type: Getting Started\n        url: https://developer-docs.citrix.com/en-us/storefront/storefront-web-api/getting-started.html\n      - type: Reference\n  \
  \      url: https://developer-docs.citrix.com/en-us/storefront/storefront-web-api/apis/\n      - type: OpenAPI\n        url: openapi/citrix-storefront-web-openapi.yml\n  - name: Citrix StoreFront Store Services API\n    description: >-\n      Server-side API for customizing and extending the Citrix StoreFront\n      store services, including endpoint management, authentication, and\n      resource enumeration behaviors.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://developer-docs.citrix.com/en-us/storefront/storefront-store-services-api/overview.html\n    baseURL: https://{storefront-server}/Citrix/Store\n    tags:\n      - Customization\n      - Server\n      - StoreFront\n    properties:\n      - type: Documentation\n        url: https://developer-docs.citrix.com/en-us/storefront/storefront-store-services-api/overview.html\n      - type: Reference\n        url: https://developer-docs.citrix.com/en-us/storefront/storefront-store-services-api/endpoints-service/\n\
  \  - name: Citrix StoreFront Authentication SDK\n    description: >-\n      SDK for building custom authentication methods for Citrix StoreFront,\n      allowing integration with third-party identity providers and custom\n      authentication workflows.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://developer-docs.citrix.com/en-us/storefront/citrix-storefront-authentication-sdk/overview.html\n    baseURL: https://{storefront-server}\n    tags:\n      - Authentication\n      - Identity\n      - StoreFront\n    properties:\n      - type: Documentation\n        url: https://developer-docs.citrix.com/en-us/storefront/citrix-storefront-authentication-sdk/overview.html\n  - name: Citrix Endpoint Management REST API\n    description: >-\n      REST API for managing mobile devices, applications, and policies in\n      Citrix Endpoint Management, enabling integration with external systems\n      for device lifecycle management and\
  \ compliance.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://docs.citrix.com/en-us/citrix-endpoint-management/rest-apis.html\n    baseURL: https://{xms-server}:4443/xenmobile/api/v1\n    tags:\n      - Endpoint Management\n      - MDM\n      - Mobile\n      - UEM\n    properties:\n      - type: Documentation\n        url: https://docs.citrix.com/en-us/citrix-endpoint-management/rest-apis.html\n      - type: OpenAPI\n        url: openapi/citrix-endpoint-management-openapi.yml\n  - name: Citrix Secure Private Access API\n    description: >-\n      REST API for managing zero trust network access policies, applications,\n      application domains, and certificates in Citrix Secure Private Access,\n      providing secure access to internal web and SaaS applications.\n    image: https://www.citrix.com/content/dam/citrix/en_us/images/logos/citrix-logo.png\n    humanURL: https://developer-docs.citrix.com/en-us/secure-private-access/access-security/overview.html\n\
  \    baseURL: https://api.cloud.com/accessSecurity\n    tags:\n      - Access Control\n      - Security\n      - Zero Trust\n      - ZTNA\n    properties:\n      - type: Documentation\n        url: https://developer-docs.citrix.com/en-us/secure-private-access/access-security/overview.html\n      - type: Getting Started\n        url: https://developer-docs.citrix.com/en-us/secure-private-access/access-security/getting-started.html\n      - type: OpenAPI\n        url: openapi/citrix-secure-private-access-openapi.yml\ncommon:\n  - type: Portal\n    url: https://developer-docs.citrix.com/\n  - type: Getting Started\n    url: https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html\n  - type: Authentication\n    url: https://developer-docs.citrix.com/en-us/citrix-cloud/citrix-cloud-api-overview/get-started-with-citrix-cloud-apis.html\n  - type: Blog\n    url: https://www.citrix.com/blogs/\n  - type: Status\n    url: https://status.cloud.com/\n\
  \  - type: Support\n    url: https://support.citrix.com/\n  - type: Terms of Service\n    url: https://developer.cloud.com/citrix-developer-terms-of-use\n  - type: Privacy Policy\n    url: https://www.citrix.com/about/legal/privacy/plain.html\n  - type: GitHub Organization\n    url: https://github.com/citrix\n  - type: Community\n    url: https://discussions.citrix.com/\n  - type: SDKs\n    url: https://docs.citrix.com/en-us/citrix-cloud/sdk-api.html\n  - type: Website\n    url: https://www.citrix.com\n  - type: Login\n    url: https://accounts.cloud.com/\n  - type: JSON-LD\n    url: json-ld/citrix-context.jsonld\n  - type: JSONSchema\n    url: json-schema/citrix-machine-catalog-schema.json\n  - type: JSONSchema\n    url: json-schema/citrix-session-schema.json\n  - type: Spectral\n    url: rules/citrix-rules.yml\n  - type: Naftiko Capabilities\n    url: capabilities/citrix-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/apis.yml
tags:
- Application Delivery
- Desktop-As-A-Service
- Networking
- Virtualization
- Workspace
url: https://raw.githubusercontent.com/api-evangelist/citrix/refs/heads/main/apis.yml
use_cases: []
---
