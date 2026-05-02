---
api_count: 9
api_specs:
- filename: microsoft-endpoint-configuration-management-configmgr-rest-api-openapi.yml
  format: yaml
  label: Configuration Manager REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-endpoint-configuration-management/refs/heads/main/openapi/microsoft-endpoint-configuration-management-configmgr-rest-api-openapi.yml
- filename: microsoft-endpoint-configuration-management-intune-graph-api-openapi.yml
  format: yaml
  label: Microsoft Intune Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-endpoint-configuration-management/refs/heads/main/openapi/microsoft-endpoint-configuration-management-intune-graph-api-openapi.yml
- filename: microsoft-endpoint-configuration-management-intune-data-warehouse-api-openapi.yml
  format: yaml
  label: Intune Data Warehouse API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-endpoint-configuration-management/refs/heads/main/openapi/microsoft-endpoint-configuration-management-intune-data-warehouse-api-openapi.yml
- filename: microsoft-endpoint-configuration-management-intune-reporting-export-api-openapi.yml
  format: yaml
  label: Intune Reporting Export API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-endpoint-configuration-management/refs/heads/main/openapi/microsoft-endpoint-configuration-management-intune-reporting-export-api-openapi.yml
apis:
- description: REST API for managing Configuration Manager resources including collections, deployments, applications, and device queries. The administration service is based on the OData v4 protocol and supports bo
  name: Configuration Manager REST API
  slug: ''
- description: PowerShell module for Configuration Manager automation and scripting, providing over 1100 cmdlets for all major management tasks including device collections, software deployment, and compliance setti
  name: Configuration Manager PowerShell Cmdlets
  slug: ''
- description: Software Development Kit for extending and integrating with Configuration Manager, including WMI providers, class schemas, and programming interfaces for custom solutions.
  name: Configuration Manager SDK
  slug: ''
- description: Microsoft Graph API endpoints for Intune device management, enabling programmatic access to manage devices, apps, compliance policies, and configuration profiles. Supports both v1.0 and beta endpoints
  name: Microsoft Intune Graph API
  slug: ''
- description: OData-based REST API that provides access to Intune reporting data in a machine-readable format. Enables building custom reports and analytics for enterprise mobile environment insights.
  name: Intune Data Warehouse API
  slug: ''
- description: SDKs for iOS and Android that enable mobile apps to support Intune app protection policies. Allows developers to integrate mobile application management features into line-of-business and partner apps
  name: Intune App SDK
  slug: ''
- description: Microsoft Graph API endpoints for exporting Intune reports programmatically. Supports exporting device, compliance, and app management reports in CSV or JSON format using asynchronous export jobs.
  name: Intune Reporting Export API
  slug: ''
- description: Command-line tools for iOS and Android that enable existing line-of-business apps to be managed by Intune app protection policies without requiring source code changes.
  name: Intune App Wrapping Tool
  slug: ''
- description: PowerShell module providing native cmdlet support for invoking the Microsoft Intune Graph API. Enables IT administrators to automate device management, app deployment, and compliance policy operations
  name: Intune PowerShell SDK
  slug: ''
common:
- title: ''
  type: Portal
  url: https://endpoint.microsoft.com/
- title: ''
  type: Console
  url: https://intune.microsoft.com/
- title: ''
  type: Documentation
  url: https://learn.microsoft.com/en-us/intune/intune-service/
- title: ''
  type: Getting Started
  url: https://learn.microsoft.com/en-us/intune/configmgr/core/understand/introduction
- title: ''
  type: Authentication
  url: https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis
- title: ''
  type: Blog
  url: https://techcommunity.microsoft.com/t5/microsoft-endpoint-manager-blog/bg-p/MicrosoftEndpointManagerBlog
- title: ''
  type: Support
  url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/contact-assisted-support
- title: ''
  type: Status
  url: https://status.azure.com/
- title: ''
  type: Change Log
  url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new
- title: ''
  type: Pricing
  url: https://www.microsoft.com/en-us/security/business/microsoft-intune-pricing
- title: ''
  type: Sign Up
  url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/free-trial-sign-up
- title: ''
  type: Login
  url: https://intune.microsoft.com/
- title: ''
  type: Privacy Policy
  url: https://privacy.microsoft.com/
- title: ''
  type: Terms of Service
  url: https://www.microsoft.com/licensing/terms/
- title: ''
  type: GitHub Organization
  url: https://github.com/microsoftgraph
- title: ''
  type: Community
  url: https://techcommunity.microsoft.com/category/microsoftintune/blog/microsoftintuneblog
- title: ''
  type: Website
  url: https://learn.microsoft.com/en-us/intune/configmgr/
created: '2024'
description: Microsoft Endpoint Configuration Management (formerly System Center Configuration Manager) provides comprehensive management of devices and applications across an enterprise. It enables IT administrators to manage PCs, servers, and mobile devices, deploy software, manage compliance, and protect data.
features: []
image: https://docs.microsoft.com/en-us/mem/configmgr/core/media/configmgr-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Microsoft Endpoint Configuration Management Context
  property_count: 7
  slug: microsoft-endpoint-configuration-management-context
layout: provider
modified: '2026-04-28'
name: Microsoft Endpoint Configuration Management
skills: []
slug: microsoft-endpoint-configuration-management
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Microsoft Endpoint Configuration Management\ndescription: >-\n  Microsoft Endpoint Configuration Management (formerly System Center\n  Configuration Manager) provides comprehensive management of devices and\n  applications across an enterprise. It enables IT administrators to manage PCs,\n  servers, and mobile devices, deploy software, manage compliance, and protect\n  data.\nimage: https://docs.microsoft.com/en-us/mem/configmgr/core/media/configmgr-logo.png\nurl: https://learn.microsoft.com/en-us/intune/configmgr/\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.18'\ntags:\n  - Compliance\n  - Configuration Management\n  - Device Management\n  - Endpoint Management\n  - Mobile Device Management\n  - Patch Management\n  - Software Deployment\napis:\n  - name: Configuration Manager REST API\n    description: >-\n      REST API for managing Configuration Manager resources including collections,\n      deployments, applications, and device queries. The\
  \ administration service is\n      based on the OData v4 protocol and supports both WMI and versioned OData\n      routes.\n    image: https://docs.microsoft.com/en-us/mem/configmgr/core/media/configmgr-logo.png\n    humanURL: https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/overview\n    baseURL: https://{siteserver}/AdminService\n    tags:\n      - Admin Service\n      - Configuration Manager\n      - REST API\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/overview\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/set-up\n      - type: OpenAPI\n        url: openapi/microsoft-endpoint-configuration-management-configmgr-rest-api-openapi.yml\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/set-up#enable-secure-https-communication\n      - type: Reference\n\
  \        url: https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/usage\n      - type: Change Log\n        url: https://learn.microsoft.com/en-us/intune/configmgr/develop/adminservice/release-notes\n  - name: Configuration Manager PowerShell Cmdlets\n    description: >-\n      PowerShell module for Configuration Manager automation and scripting,\n      providing over 1100 cmdlets for all major management tasks including device\n      collections, software deployment, and compliance settings.\n    humanURL: https://learn.microsoft.com/en-us/powershell/sccm/overview?view=sccm-ps\n    tags:\n      - Automation\n      - Configuration Manager\n      - PowerShell\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/powershell/sccm/overview?view=sccm-ps\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/powershell/module/configurationmanager/?view=sccm-ps\n      - type: Getting Started\n    \
  \    url: https://learn.microsoft.com/en-us/intune/configmgr/core/servers/manage/admin-console\n      - type: Change Log\n        url: https://learn.microsoft.com/en-us/intune/configmgr/core/plan-design/changes/whats-new-incremental-versions\n  - name: Configuration Manager SDK\n    description: >-\n      Software Development Kit for extending and integrating with Configuration\n      Manager, including WMI providers, class schemas, and programming interfaces\n      for custom solutions.\n    humanURL: https://learn.microsoft.com/en-us/intune/configmgr/develop/\n    tags:\n      - Configuration Manager\n      - Development\n      - SDK\n      - WMI\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/intune/configmgr/develop/\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/intune/configmgr/develop/reference/configuration-manager-reference\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/intune/configmgr/develop/core/understand/getting-started-with-configuration-manager-programming\n\
  \      - type: Change Log\n        url: https://learn.microsoft.com/en-us/intune/configmgr/core/plan-design/changes/whats-new-incremental-versions\n  - name: Microsoft Intune Graph API\n    description: >-\n      Microsoft Graph API endpoints for Intune device management, enabling\n      programmatic access to manage devices, apps, compliance policies, and\n      configuration profiles. Supports both v1.0 and beta endpoints.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/intune-graph-overview?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Compliance\n      - Device Management\n      - Intune\n      - Microsoft Graph\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/intune-graph-overview?view=graph-rest-1.0\n      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/graph/intune-concept-overview\n      - type: OpenAPI\n        url: openapi/microsoft-endpoint-configuration-management-intune-graph-api-openapi.yml\n\
  \      - type: JSONSchema\n        url: json-schema/microsoft-endpoint-configuration-management-device-schema.json\n      - type: JSONSchema\n        url: json-schema/microsoft-endpoint-configuration-management-compliance-policy-schema.json\n      - type: JSONSchema\n        url: json-schema/microsoft-endpoint-configuration-management-application-schema.json\n      - type: JSONSchema\n        url: json-schema/microsoft-endpoint-configuration-management-configuration-profile-schema.json\n      - type: JSONLD\n        url: json-ld/microsoft-endpoint-configuration-management-context.jsonld\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/graph/intune-concept-overview\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis\n      - type: Change Log\n        url: https://developer.microsoft.com/en-us/graph/changelog\n      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdks-overview\n\
  \      - type: PostmanCollection\n        url: https://www.postman.com/microsoftgraph/workspace/microsoft-graph/overview\n  - name: Intune Data Warehouse API\n    description: >-\n      OData-based REST API that provides access to Intune reporting data in a\n      machine-readable format. Enables building custom reports and analytics for\n      enterprise mobile environment insights.\n    humanURL: https://learn.microsoft.com/en-us/intune/intune-service/developer/reports-nav-intune-data-warehouse\n    baseURL: https://fef.{location}.manage.microsoft.com/ReportingService/DataWarehouseFEService\n    tags:\n      - Data Warehouse\n      - Intune\n      - OData\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/reports-nav-intune-data-warehouse\n      - type: OpenAPI\n        url: openapi/microsoft-endpoint-configuration-management-intune-data-warehouse-api-openapi.yml\n      - type: Getting Started\n\
  \        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/reports-api-url\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/reports-proc-data-rest\n      - type: Change Log\n        url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new\n  - name: Intune App SDK\n    description: >-\n      SDKs for iOS and Android that enable mobile apps to support Intune app\n      protection policies. Allows developers to integrate mobile application\n      management features into line-of-business and partner apps.\n    humanURL: https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk-get-started\n    tags:\n      - App Protection\n      - Intune\n      - Mobile Apps\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk\n\
  \      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk-get-started\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk-ios-phase1\n      - type: GitHub Organization\n        url: https://github.com/msintuneappsdk\n  - name: Intune Reporting Export API\n    description: >-\n      Microsoft Graph API endpoints for exporting Intune reports programmatically.\n      Supports exporting device, compliance, and app management reports in CSV or\n      JSON format using asynchronous export jobs.\n    humanURL: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-apis\n    baseURL: https://graph.microsoft.com/v1.0/deviceManagement/reports\n    tags:\n      - Export\n      - Intune\n      - Microsoft Graph\n      - Reporting\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-apis\n\
  \      - type: OpenAPI\n        url: openapi/microsoft-endpoint-configuration-management-intune-reporting-export-api-openapi.yml\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-available-reports\n      - type: Authentication\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis\n  - name: Intune App Wrapping Tool\n    description: >-\n      Command-line tools for iOS and Android that enable existing line-of-business\n      apps to be managed by Intune app protection policies without requiring source\n      code changes.\n    humanURL: https://learn.microsoft.com/en-us/intune/intune-service/developer/apps-prepare-mobile-application-management\n    tags:\n      - Android\n      - App Protection\n      - Intune\n      - iOS\n      - Mobile Apps\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/apps-prepare-mobile-application-management\n\
  \      - type: Getting Started\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/app-wrapper-prepare-ios\n      - type: Reference\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/app-wrapper-prepare-android\n      - type: GitHub Organization\n        url: https://github.com/microsoftconnect\n  - name: Intune PowerShell SDK\n    description: >-\n      PowerShell module providing native cmdlet support for invoking the Microsoft\n      Intune Graph API. Enables IT administrators to automate device management,\n      app deployment, and compliance policy operations through scripting.\n    humanURL: https://github.com/microsoft/Intune-PowerShell-SDK\n    tags:\n      - Automation\n      - Intune\n      - PowerShell\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://github.com/microsoft/Intune-PowerShell-SDK\n      - type: Getting Started\n        url: https://github.com/microsoft/mggraph-intune-samples\n\
  \      - type: SDKs\n        url: https://learn.microsoft.com/en-us/graph/sdks/sdk-installation\ncommon:\n  - type: Portal\n    url: https://endpoint.microsoft.com/\n  - type: Console\n    url: https://intune.microsoft.com/\n  - type: Documentation\n    url: https://learn.microsoft.com/en-us/intune/intune-service/\n  - type: Getting Started\n    url: https://learn.microsoft.com/en-us/intune/configmgr/core/understand/introduction\n  - type: Authentication\n    url: https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis\n  - type: Blog\n    url: https://techcommunity.microsoft.com/t5/microsoft-endpoint-manager-blog/bg-p/MicrosoftEndpointManagerBlog\n  - type: Support\n    url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/contact-assisted-support\n  - type: Status\n    url: https://status.azure.com/\n  - type: Change Log\n    url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/whats-new\n  - type: Pricing\n    url:\
  \ https://www.microsoft.com/en-us/security/business/microsoft-intune-pricing\n  - type: Sign Up\n    url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/free-trial-sign-up\n  - type: Login\n    url: https://intune.microsoft.com/\n  - type: Privacy Policy\n    url: https://privacy.microsoft.com/\n  - type: Terms of Service\n    url: https://www.microsoft.com/licensing/terms/\n  - type: GitHub Organization\n    url: https://github.com/microsoftgraph\n  - type: Community\n    url: https://techcommunity.microsoft.com/category/microsoftintune/blog/microsoftintuneblog\n  - type: Website\n    url: https://learn.microsoft.com/en-us/intune/configmgr/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-endpoint-configuration-management/refs/heads/main/apis.yml
tags:
- Compliance
- Configuration Management
- Device Management
- Endpoint Management
- Mobile Device Management
- Patch Management
- Software Deployment
url: https://learn.microsoft.com/en-us/intune/configmgr/
use_cases: []
---
