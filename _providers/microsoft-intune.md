---
api_count: 8
apis:
- description: The Microsoft Graph API for Intune enables programmatic access to Intune information and actions for your tenant. The API performs the same Intune operations as those available through the Azure Porta
  name: Microsoft Intune API
  slug: ''
- description: The Intune Data Warehouse API provides access to your Intune data in a machine-readable format for use in your favorite analytics tool. You can use the API to generate reports that provide insight int
  name: Intune Data Warehouse API
  slug: ''
- description: The Microsoft Graph Device Management API enables programmatic management of devices enrolled in Intune, including listing managed devices, performing remote actions such as wipe and retire, and retri
  name: Intune Device Management API
  slug: ''
- description: The Microsoft Graph Device Configuration API allows you to define and deploy device configuration policies across enrolled devices, including operating system platform and versioning, domain membershi
  name: Intune Device Configuration API
  slug: ''
- description: The Microsoft Graph Device Compliance API enables you to define and enforce device compliance policies, such as password complexity, encryption, and threat protection levels, and retrieve compliance s
  name: Intune Device Compliance API
  slug: ''
- description: The Microsoft Graph Device Enrollment API enables you to enroll organization-owned or corporate-owned devices for management with Intune, supporting various enrollment methods depending on device type
  name: Intune Device Enrollment API
  slug: ''
- description: The Microsoft Graph Mobile App Management (MAM) API enables you to manage app protection policies, deploy apps to devices, configure app settings, and manage app usage policies to protect organization
  name: Intune Mobile App Management API
  slug: ''
- description: The Intune Reports Export API enables you to export Intune reporting data using Microsoft Graph API export jobs. You can create export jobs to generate reports that provide insight into device complia
  name: Intune Reports Export API
  slug: ''
common:
- title: ''
  type: X-portal
  url: https://endpoint.microsoft.com/
- title: ''
  type: X-blog
  url: https://techcommunity.microsoft.com/t5/microsoft-intune-blog/bg-p/MicrosoftEndpointManagerBlog
- title: ''
  type: X-learning
  url: https://docs.microsoft.com/en-us/learn/browse/?products=m365%2Cmem
- title: ''
  type: X-privacy
  url: https://privacy.microsoft.com/
- title: ''
  type: X-terms-of-service
  url: https://www.microsoft.com/en-us/legal/terms-of-use
- title: ''
  type: X-status
  url: https://status.azure.com/
- title: ''
  type: X-github
  url: https://github.com/microsoftgraph
- title: ''
  type: X-github-samples
  url: https://github.com/microsoft/mggraph-intune-samples
- title: ''
  type: X-powershell-samples
  url: https://github.com/microsoftgraph/powershell-intune-samples
- title: ''
  type: X-developer-documentation
  url: https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis
- title: ''
  type: X-sdk
  url: https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk
- title: ''
  type: X-sdk-getting-started
  url: https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk-get-started
- title: ''
  type: X-app-wrapping-tool
  url: https://learn.microsoft.com/en-us/intune/intune-service/developer/apps-prepare-mobile-application-management
- title: ''
  type: X-community
  url: https://techcommunity.microsoft.com/t5/microsoft-intune/ct-p/MicrosoftIntune
- title: ''
  type: X-support
  url: https://learn.microsoft.com/en-us/mem/get-support
- title: ''
  type: X-twitter
  url: https://twitter.com/MSIntune
- title: ''
  type: X-whatsnew
  url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development
created: '2024'
description: Microsoft Intune is a cloud-based service that focuses on mobile device management (MDM) and mobile application management (MAM). It helps organizations control how their devices are used, including mobile phones, tablets, and laptops, and enables management of apps on those devices.
features: []
image: https://docs.microsoft.com/en-us/mem/intune/fundamentals/media/what-is-intune/intune-logo.png
integrations: []
jsonld:
- class_count: 0
  name: Microsoft Intune Context
  property_count: 5
  slug: microsoft-intune-context
layout: provider
modified: '2026-04-28'
name: Microsoft Intune
skills: []
slug: microsoft-intune
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: microsoft-intune\nname: Microsoft Intune\ndescription: Microsoft Intune is a cloud-based service that focuses on mobile device management (MDM) and mobile application management (MAM). It helps organizations control how their devices are used, including mobile phones, tablets, and laptops, and enables management of apps on those devices.\nimage: https://docs.microsoft.com/en-us/mem/intune/fundamentals/media/what-is-intune/intune-logo.png\nurl: https://www.microsoft.com/en-us/security/business/microsoft-intune\ncreated: '2024'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - App Protection\n  - Azure\n  - Compliance\n  - Device Configuration\n  - Endpoint Management\n  - Enrollment\n  - MAM\n  - MDM\n  - Microsoft Graph\n  - Mobile Application Management\n  - Mobile Device Management\n  - Security\napis:\n  - name: Microsoft Intune API\n    description: The Microsoft Graph API for Intune enables programmatic access to Intune information and actions for\
  \ your tenant. The API performs the same Intune operations as those available through the Azure Portal.\n    image: https://docs.microsoft.com/en-us/mem/intune/fundamentals/media/what-is-intune/intune-logo.png\n    humanURL: https://docs.microsoft.com/en-us/graph/api/resources/intune-graph-overview\n    baseURL: https://graph.microsoft.com/v1.0\n    tags:\n      - Applications\n      - Compliance\n      - Devices\n      - Groups\n      - Policies\n      - Users\n    properties:\n      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/graph/api/resources/intune-graph-overview\n      - type: X-openapi\n        url: https://raw.githubusercontent.com/microsoftgraph/msgraph-metadata/master/openapi/v1.0/openapi.yaml\n      - type: X-openapi-intune\n        url: openapi/microsoft-intune-openapi.yml\n      - type: X-json-schema-managed-device\n        url: json-schema/microsoft-intune-managed-device-schema.json\n      - type: X-json-ld-context\n        url: json-ld/microsoft-intune-context.jsonld\n\
  \      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/graph/auth/\n      - type: X-postman-collection\n        url: https://www.postman.com/microsoftgraph/workspace/microsoft-graph/overview\n      - type: X-rate-limits\n        url: https://docs.microsoft.com/en-us/graph/throttling\n      - type: X-change-log\n        url: https://docs.microsoft.com/en-us/graph/changelog\n      - type: X-sdks\n        url: https://docs.microsoft.com/en-us/graph/sdks/sdks-overview\n      - type: X-pricing\n        url: https://www.microsoft.com/en-us/security/business/microsoft-intune-pricing\n      - type: X-getting-started\n        url: https://learn.microsoft.com/en-us/graph/intune-concept-overview\n      - type: X-permissions\n        url: https://learn.microsoft.com/en-us/graph/permissions-reference\n    contact:\n      - type: X-support\n        url: https://docs.microsoft.com/en-us/mem/get-support\n      - type: X-twitter\n        url: https://twitter.com/MSIntune\n     \
  \ - type: X-status\n        url: https://status.azure.com/\n  - name: Intune Data Warehouse API\n    description: The Intune Data Warehouse API provides access to your Intune data in a machine-readable format for use in your favorite analytics tool. You can use the API to generate reports that provide insight into your mobile environment.\n    humanURL: https://docs.microsoft.com/en-us/mem/intune/developer/reports-nav-create-intune-reports\n    baseURL: https://api.manage.microsoft.com/\n    tags:\n      - Analytics\n      - Data Warehouse\n      - Odata\n      - Reporting\n    properties:\n      - type: X-documentation\n        url: https://docs.microsoft.com/en-us/mem/intune/developer/reports-nav-intune-data-warehouse\n      - type: X-authentication\n        url: https://docs.microsoft.com/en-us/mem/intune/developer/reports-proc-data-rest\n      - type: X-data-model\n        url: https://docs.microsoft.com/en-us/mem/intune/developer/reports-ref-data-model\n  - name: Intune Device Management\
  \ API\n    description: >-\n      The Microsoft Graph Device Management API enables programmatic management of\n      devices enrolled in Intune, including listing managed devices, performing\n      remote actions such as wipe and retire, and retrieving device compliance\n      state and configuration status.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/intune-devices-manageddevice?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0/deviceManagement\n    tags:\n      - Device Compliance\n      - Devices\n      - Managed Devices\n      - Remote Actions\n    properties:\n      - type: X-documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/intune-devices-manageddevice?view=graph-rest-1.0\n      - type: X-openapi\n        url: openapi/microsoft-intune-openapi.yml\n      - type: X-json-schema\n        url: json-schema/microsoft-intune-managed-device-schema.json\n      - type: X-json-ld-context\n        url: json-ld/microsoft-intune-context.jsonld\n\
  \      - type: X-list-endpoint\n        url: https://learn.microsoft.com/en-us/graph/api/intune-devices-manageddevice-list?view=graph-rest-1.0\n      - type: X-getting-started\n        url: https://learn.microsoft.com/en-us/graph/intune-concept-overview\n  - name: Intune Device Configuration API\n    description: >-\n      The Microsoft Graph Device Configuration API allows you to define and deploy\n      device configuration policies across enrolled devices, including operating\n      system platform and versioning, domain membership, and configuration setting\n      management through configuration service providers (CSPs).\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/intune-deviceconfig-deviceconfiguration?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0/deviceManagement/deviceConfigurations\n    tags:\n      - CSP\n      - Device Configuration\n      - Policies\n      - Settings\n    properties:\n      - type: X-documentation\n        url:\
  \ https://learn.microsoft.com/en-us/graph/api/resources/intune-deviceconfig-deviceconfiguration?view=graph-rest-1.0\n      - type: X-openapi\n        url: openapi/microsoft-intune-openapi.yml\n      - type: X-json-ld-context\n        url: json-ld/microsoft-intune-context.jsonld\n      - type: X-graph-apis\n        url: https://learn.microsoft.com/en-us/intune/intune-service/developer/graph-apis-used-by-intune-device-configuration-windows\n  - name: Intune Device Compliance API\n    description: >-\n      The Microsoft Graph Device Compliance API enables you to define and enforce\n      device compliance policies, such as password complexity, encryption, and\n      threat protection levels, and retrieve compliance state for managed devices.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/intune-deviceconfig-devicecompliancepolicy?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0/deviceManagement/deviceCompliancePolicies\n    tags:\n      - Compliance\n\
  \      - Device Compliance\n      - Policies\n      - Security\n    properties:\n      - type: X-documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/intune-deviceconfig-devicecompliancepolicy?view=graph-rest-1.0\n      - type: X-openapi\n        url: openapi/microsoft-intune-openapi.yml\n      - type: X-json-ld-context\n        url: json-ld/microsoft-intune-context.jsonld\n      - type: X-overview\n        url: https://learn.microsoft.com/en-us/intune/intune-service/protect/device-compliance-get-started\n  - name: Intune Device Enrollment API\n    description: >-\n      The Microsoft Graph Device Enrollment API enables you to enroll\n      organization-owned or corporate-owned devices for management with Intune,\n      supporting various enrollment methods depending on device type and\n      organizational needs.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/intune-enrollment-conceptual?view=graph-rest-1.0\n    baseURL: https://graph.microsoft.com/v1.0/deviceManagement\n\
  \    tags:\n      - Corporate Devices\n      - Enrollment\n      - Onboarding\n    properties:\n      - type: X-documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/intune-enrollment-conceptual?view=graph-rest-1.0\n      - type: X-onboarding\n        url: https://learn.microsoft.com/en-us/graph/api/resources/intune-onboarding-conceptual?view=graph-rest-1.0\n  - name: Intune Mobile App Management API\n    description: >-\n      The Microsoft Graph Mobile App Management (MAM) API enables you to manage\n      app protection policies, deploy apps to devices, configure app settings, and\n      manage app usage policies to protect organizational data within mobile\n      applications.\n    humanURL: https://learn.microsoft.com/en-us/graph/api/resources/intune-mam-conceptual?view=graph-rest-beta\n    baseURL: https://graph.microsoft.com/beta/deviceAppManagement\n    tags:\n      - App Protection\n      - Applications\n      - MAM\n      - Mobile App Management\n \
  \   properties:\n      - type: X-documentation\n        url: https://learn.microsoft.com/en-us/graph/api/resources/intune-mam-conceptual?view=graph-rest-beta\n      - type: X-app-protection-overview\n        url: https://learn.microsoft.com/en-us/intune/intune-service/apps/app-protection-policy\n      - type: X-app-configuration\n        url: https://learn.microsoft.com/en-us/intune/intune-service/apps/app-configuration-policies-overview\n  - name: Intune Reports Export API\n    description: >-\n      The Intune Reports Export API enables you to export Intune reporting data\n      using Microsoft Graph API export jobs. You can create export jobs to generate\n      reports that provide insight into device compliance, app usage, and other\n      aspects of your managed environment.\n    humanURL: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-apis\n    baseURL: https://graph.microsoft.com/v1.0/deviceManagement/reports\n    tags:\n      - Analytics\n\
  \      - Compliance Reports\n      - Export\n      - Reports\n    properties:\n      - type: X-documentation\n        url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-apis\n      - type: X-available-reports\n        url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/reports-export-graph-available-reports\n      - type: X-create-export-job\n        url: https://learn.microsoft.com/en-us/graph/api/intune-reporting-devicemanagementexportjob-create?view=graph-rest-1.0\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\ncommon:\n  - type: X-portal\n    url: https://endpoint.microsoft.com/\n  - type: X-blog\n    url: https://techcommunity.microsoft.com/t5/microsoft-intune-blog/bg-p/MicrosoftEndpointManagerBlog\n  - type: X-learning\n    url: https://docs.microsoft.com/en-us/learn/browse/?products=m365%2Cmem\n  - type: X-privacy\n    url: https://privacy.microsoft.com/\n  -\
  \ type: X-terms-of-service\n    url: https://www.microsoft.com/en-us/legal/terms-of-use\n  - type: X-status\n    url: https://status.azure.com/\n  - type: X-github\n    url: https://github.com/microsoftgraph\n  - type: X-github-samples\n    url: https://github.com/microsoft/mggraph-intune-samples\n  - type: X-powershell-samples\n    url: https://github.com/microsoftgraph/powershell-intune-samples\n  - type: X-developer-documentation\n    url: https://learn.microsoft.com/en-us/intune/intune-service/developer/intune-graph-apis\n  - type: X-sdk\n    url: https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk\n  - type: X-sdk-getting-started\n    url: https://learn.microsoft.com/en-us/intune/intune-service/developer/app-sdk-get-started\n  - type: X-app-wrapping-tool\n    url: https://learn.microsoft.com/en-us/intune/intune-service/developer/apps-prepare-mobile-application-management\n  - type: X-community\n    url: https://techcommunity.microsoft.com/t5/microsoft-intune/ct-p/MicrosoftIntune\n\
  \  - type: X-support\n    url: https://learn.microsoft.com/en-us/mem/get-support\n  - type: X-twitter\n    url: https://twitter.com/MSIntune\n  - type: X-whatsnew\n    url: https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/in-development\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/microsoft-intune/refs/heads/main/apis.yml
tags:
- App Protection
- Azure
- Compliance
- Device Configuration
- Endpoint Management
- Enrollment
- MAM
- MDM
- Microsoft Graph
- Mobile Application Management
- Mobile Device Management
- Security
url: https://www.microsoft.com/en-us/security/business/microsoft-intune
use_cases: []
---
