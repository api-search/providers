---
api_count: 10
api_specs:
- filename: dell-servers-idrac-redfish-openapi.yml
  format: yaml
  label: Dell iDRAC Redfish REST API
  slug: dell-servers-idrac-redfish
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/openapi/dell-servers-idrac-redfish-openapi.yml
- filename: dell-servers-openmanage-enterprise-openapi.yml
  format: yaml
  label: Dell OpenManage Enterprise API
  slug: dell-servers-openmanage-enterprise
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/openapi/dell-servers-openmanage-enterprise-openapi.yml
apis:
- description: Integrated Dell Remote Access Controller REST API for server management, monitoring, and configuration. The iDRAC RESTful API builds upon the DMTF Redfish standard to provide a comprehensive interface
  name: Dell iDRAC Redfish REST API
  slug: dell-servers-idrac-redfish
- description: REST API for centralized management of Dell EMC servers, chassis, and storage. OpenManage Enterprise provides a comprehensive console for discovery, inventory, monitoring, alerting, jobs, configuratio
  name: Dell OpenManage Enterprise API
  slug: dell-servers-openmanage-enterprise
- description: RESTful API for managing Dell PowerEdge MX7000 modular chassis and its components including compute sleds, network devices, IOMs, and storage. OME-Modular shares a common codebase with OpenManage Ente
  name: Dell OpenManage Enterprise Modular API
  slug: dell-servers-openmanage-enterprise-modular
- description: RESTful API for monitoring and managing power consumption, thermal conditions, and energy costs across Dell PowerEdge server infrastructure. Power Manager is a plug-in to the OpenManage Enterprise con
  name: Dell OpenManage Enterprise Power Manager API
  slug: dell-servers-openmanage-enterprise-power-manager
- description: RESTful API for the OpenManage Enterprise SupportAssist plug-in that enables proactive and predictive monitoring of Dell PowerEdge servers. SupportAssist automates support case creation and parts disp
  name: Dell OpenManage Enterprise SupportAssist API
  slug: dell-servers-openmanage-enterprise-supportassist
- description: RESTful API for the OpenManage Integration for VMware vCenter (OMIVV), enabling automation of Dell PowerEdge server management within VMware environments. The API is compliant with OpenAPI Specificati
  name: Dell OpenManage Integration for VMware vCenter API
  slug: dell-servers-openmanage-integration-vmware-vcenter
- description: Server-Sent Events (SSE) streaming API for real-time telemetry data from Dell PowerEdge servers via iDRAC. Provides continuous metric reports including power statistics, CPU and memory metrics, therma
  name: Dell iDRAC Telemetry Streaming API
  slug: dell-servers-idrac-telemetry-streaming
- description: Standards-based interface for remote deployment, configuration, and updates of Dell PowerEdge servers. Lifecycle Controller Remote Services supports WSMAN and Redfish management interfaces for bare-me
  name: Dell Lifecycle Controller Remote Services API
  slug: dell-servers-lifecycle-controller-remote-services
- description: Command-line interface for Dell Remote Access Controller Administration. RACADM provides local and remote command-line access to iDRAC for scripting and automating server configuration, monitoring, an
  name: Dell RACADM CLI
  slug: dell-servers-racadm
- description: Web Services Management API for Dell server hardware management. WSMan provides a SOAP-based interface for managing server configuration, BIOS, RAID, NIC, and HBA settings on Dell PowerEdge servers th
  name: Dell WSMan API
  slug: dell-servers-wsman
capabilities: []
common:
- title: ''
  type: Portal
  url: https://developer.dell.com/
- title: ''
  type: Getting Started
  url: https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v6.x-series/smog_26.0/idrac-restful-apis-redfish-standards-based?guid=guid-476c6603-818e-4e2e-82f0-699bde0c3a3c&lang=en-us
- title: ''
  type: Documentation
  url: https://www.dell.com/support/product-details/en-us/product/dell-openmanage-enterprise/resources/manuals
- title: ''
  type: Support
  url: https://www.dell.com/support
- title: ''
  type: Community
  url: https://www.dell.com/community/
- title: ''
  type: Blog
  url: https://www.dell.com/community/en/topics/developer-blogs
- title: ''
  type: TermsOfService
  url: https://i.dell.com/sites/csdocuments/Legal_Docs/en/us/api-terms-of-use_en.pdf
- title: ''
  type: PrivacyPolicy
  url: https://www.dell.com/en-us/lp/legal/policies-privacy
- title: ''
  type: Website
  url: https://www.dell.com/en-us/lp/dt/open-manage
- title: ''
  type: GitHub
  url: https://github.com/dell
- title: ''
  type: SDKs
  url: https://developer.dell.com/apis/
- title: ''
  type: SignUp
  url: https://developer.dell.com/
- title: ''
  type: Login
  url: https://developer.dell.com/
- title: ''
  type: JSON-LD
  url: json-ld/dell-servers-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/dell-servers-vocabulary.yml
created: '2024-01-01'
description: APIs for managing and monitoring Dell PowerEdge servers and infrastructure, including the iDRAC Redfish out-of-band management interface, OpenManage Enterprise centralized console and its modular, power, support, and VMware integrations, telemetry streaming, the Lifecycle Controller, RACADM, and the legacy WSMan interface.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 10
  name: Dell Servers Context
  property_count: 12
  slug: dell-servers-context
layout: provider
modified: '2026-04-28'
name: Dell Servers
rules:
- name: Dell Servers API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: dell-servers-idrac-redfish-rules
- name: Dell Servers API Rules
  rule_count: 5
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 4
  slug: dell-servers-openmanage-enterprise-rules
skills: []
slug: dell-servers
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dell-servers\nname: Dell Servers\ndescription: >-\n  APIs for managing and monitoring Dell PowerEdge servers and infrastructure,\n  including the iDRAC Redfish out-of-band management interface, OpenManage\n  Enterprise centralized console and its modular, power, support, and VMware\n  integrations, telemetry streaming, the Lifecycle Controller, RACADM, and the\n  legacy WSMan interface.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\nxType: company\naccess: 3rd-Party\nposition: Consuming\ntags:\n  - Hardware\n  - Infrastructure\n  - Management\n  - Monitoring\n  - Servers\ncreated: '2024-01-01'\nmodified: '2026-04-28'\napis:\n  - aid: dell-servers:dell-servers-idrac-redfish\n    name: Dell iDRAC Redfish REST API\n    description: >-\n      Integrated Dell Remote Access Controller REST API for server management,\n\
  \      monitoring, and configuration. The iDRAC RESTful API builds upon the DMTF\n      Redfish standard to provide a comprehensive interface for out-of-band\n      server lifecycle management of Dell PowerEdge servers, including\n      inventory, health monitoring, power control, BIOS configuration, virtual\n      media, firmware updates, event subscriptions, and telemetry.\n    image: https://www.dell.com/favicon.ico\n    baseURL: https://{idrac-ip}/redfish/v1\n    humanURL: https://www.dell.com/support/kbdoc/en-us/000178045/redfish-api-with-dell-integrated-remote-access-controller\n    tags:\n      - BMC\n      - Hardware Monitoring\n      - Redfish\n      - Server Management\n    properties:\n      - type: Documentation\n        url: https://www.dell.com/support/kbdoc/en-us/000178045/redfish-api-with-dell-integrated-remote-access-controller\n      - type: OpenAPI\n        url: openapi/dell-servers-idrac-redfish-openapi.yml\n      - type: Rules\n        url: rules/dell-servers-idrac-redfish-rules.yml\n\
  \      - type: Capabilities\n        url: capabilities/dell-servers-idrac-redfish-capabilities.yml\n      - type: Authentication\n        url: https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v4.x-series/idrac9_4.00.00.00_redfishapiguide_pub/redfish-authentication-and-authorization?guid=guid-d572792f-afd2-499a-bf12-38a6778b9bbc&lang=en-us\n      - type: Getting Started\n        url: https://developer.dell.com/apis/2978/versions/5.xx/docs/1.0Intro.md\n      - type: GitHub Repository\n        url: https://github.com/dell/iDRAC-Redfish-Scripting\n  - aid: dell-servers:dell-servers-openmanage-enterprise\n    name: Dell OpenManage Enterprise API\n    description: >-\n      REST API for centralized management of Dell EMC servers, chassis, and\n      storage. OpenManage Enterprise provides a comprehensive console for\n      discovery, inventory, monitoring, alerting, jobs, configuration\n      templates, firmware compliance baselines, and reporting across Dell\n      PowerEdge\
  \ infrastructure at scale.\n    image: https://www.dell.com/favicon.ico\n    baseURL: https://{ome-server}/api\n    humanURL: https://www.dell.com/support/kbdoc/en-us/000175879/support-for-openmanage-enterprise\n    tags:\n      - Automation\n      - Enterprise Management\n      - Monitoring\n      - Orchestration\n    properties:\n      - type: Documentation\n        url: https://www.dell.com/support/manuals/en-us/dell-openmanage-enterprise/ome_p_api_guide/preface?guid=guid-82bcb773-392d-43a4-bdfa-431dd06a06f4&lang=en-us\n      - type: OpenAPI\n        url: openapi/dell-servers-openmanage-enterprise-openapi.yml\n      - type: Rules\n        url: rules/dell-servers-openmanage-enterprise-rules.yml\n      - type: Capabilities\n        url: capabilities/dell-servers-openmanage-enterprise-capabilities.yml\n      - type: GitHub Repository\n        url: https://github.com/dell/OpenManage-Enterprise\n  - aid: dell-servers:dell-servers-openmanage-enterprise-modular\n    name: Dell OpenManage Enterprise\
  \ Modular API\n    description: >-\n      RESTful API for managing Dell PowerEdge MX7000 modular chassis and its\n      components including compute sleds, network devices, IOMs, and storage.\n      OME-Modular shares a common codebase with OpenManage Enterprise and\n      supports multi-chassis management with up to 20 chassis per group.\n    image: https://www.dell.com/favicon.ico\n    baseURL: https://{omem-server}/api\n    humanURL: https://www.dell.com/support/manuals/en-us/openmanage-enterprise-modular/omem_2.00.00_api/openmanage-enterprise-modular-edition?guid=guid-fe459ff7-030b-4375-a6d5-9f0ab2278946&lang=en-us\n    tags:\n      - Chassis Management\n      - Modular Infrastructure\n      - Multi-Chassis\n      - PowerEdge MX\n    properties:\n      - type: Documentation\n        url: https://www.dell.com/support/manuals/en-us/openmanage-enterprise-modular/omem_2.00.00_api/openmanage-enterprise-modular-edition?guid=guid-fe459ff7-030b-4375-a6d5-9f0ab2278946&lang=en-us\n      - type:\
  \ GitHub Repository\n        url: https://github.com/dell/OpenManage-Enterprise\n  - aid: dell-servers:dell-servers-openmanage-enterprise-power-manager\n    name: Dell OpenManage Enterprise Power Manager API\n    description: >-\n      RESTful API for monitoring and managing power consumption, thermal\n      conditions, and energy costs across Dell PowerEdge server infrastructure.\n      Power Manager is a plug-in to the OpenManage Enterprise console that\n      provides power policies, capping, and reporting capabilities.\n    image: https://www.dell.com/favicon.ico\n    baseURL: https://{ome-server}/api\n    humanURL: https://developer.dell.com/apis/5708/versions/3.0/docs/0.1%20Introduction-to-PMP-API.md\n    tags:\n      - Data Center\n      - Energy Efficiency\n      - Power Management\n      - Thermal Monitoring\n    properties:\n      - type: Documentation\n        url: https://www.dell.com/support/manuals/en-us/openmanage-enterprise-power-manager/pmp_3.1_apiguide/about-this-document\n\
  \  - aid: dell-servers:dell-servers-openmanage-enterprise-supportassist\n    name: Dell OpenManage Enterprise SupportAssist API\n    description: >-\n      RESTful API for the OpenManage Enterprise SupportAssist plug-in that\n      enables proactive and predictive monitoring of Dell PowerEdge servers.\n      SupportAssist automates support case creation and parts dispatch for\n      servers with ProSupport and ProSupport Plus entitlements.\n    image: https://www.dell.com/favicon.ico\n    baseURL: https://{ome-server}/api\n    humanURL: https://developer.dell.com/apis/2848/versions/1.2\n    tags:\n      - Alerting\n      - Predictive Analytics\n      - Proactive Monitoring\n      - Support\n    properties:\n      - type: Documentation\n        url: https://developer.dell.com/apis/2848/versions/1.2\n  - aid: dell-servers:dell-servers-openmanage-integration-vmware-vcenter\n    name: Dell OpenManage Integration for VMware vCenter API\n    description: >-\n      RESTful API for the OpenManage\
  \ Integration for VMware vCenter (OMIVV),\n      enabling automation of Dell PowerEdge server management within VMware\n      environments. The API is compliant with OpenAPI Specification 3.0.0 and\n      supports firmware updates, inventory, and monitoring tasks.\n    image: https://www.dell.com/favicon.ico\n    baseURL: https://{omivv-server}/api\n    humanURL: https://www.dell.com/support/manuals/en-us/openmanage-integration-vmware-vcenter/omivv_5.4_api/overview\n    tags:\n      - Server Management\n      - vCenter Integration\n      - Virtualization\n      - VMware\n    properties:\n      - type: Documentation\n        url: https://www.dell.com/support/manuals/en-us/openmanage-integration-vmware-vcenter/omivv_5.4_api/overview\n      - type: GitHub Repository\n        url: https://github.com/dell/omivv\n  - aid: dell-servers:dell-servers-idrac-telemetry-streaming\n    name: Dell iDRAC Telemetry Streaming API\n    description: >-\n      Server-Sent Events (SSE) streaming API for real-time\
  \ telemetry data from\n      Dell PowerEdge servers via iDRAC. Provides continuous metric reports\n      including power statistics, CPU and memory metrics, thermal sensor data,\n      NIC statistics, and PSU metrics using the Redfish TelemetryService.\n    image: https://www.dell.com/favicon.ico\n    baseURL: https://{idrac-ip}/redfish/v1/SSE\n    humanURL: https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v4.x-series/idrac9_4.00.00.00_redfishapiguide_pub/server-sent-events?guid=guid-fc87fd01-2cff-4ae0-9714-1bd712bb5ce3&lang=en-us\n    tags:\n      - Monitoring\n      - Server-Sent Events\n      - Streaming\n      - Telemetry\n    properties:\n      - type: Documentation\n        url: https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v4.x-series/idrac9_4.00.00.00_redfishapiguide_pub/server-sent-events?guid=guid-fc87fd01-2cff-4ae0-9714-1bd712bb5ce3&lang=en-us\n      - type: GitHub Repository\n        url: https://github.com/dell/iDRAC-Telemetry-Reference-Tools\n\
  \  - aid: dell-servers:dell-servers-lifecycle-controller-remote-services\n    name: Dell Lifecycle Controller Remote Services API\n    description: >-\n      Standards-based interface for remote deployment, configuration, and\n      updates of Dell PowerEdge servers. Lifecycle Controller Remote Services\n      supports WSMAN and Redfish management interfaces for bare-metal\n      provisioning and one-to-many operating system deployments.\n    image: https://www.dell.com/favicon.ico\n    baseURL: https://{idrac-ip}/wsman\n    humanURL: https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.4-series/idrac_3.40.40.40_lc_re_qsg/about-lifecycle-controller-api?guid=guid-f7bcc1d3-46c1-4ec3-9a45-0f33d734585c&lang=en-us\n    tags:\n      - Deployment\n      - Lifecycle Management\n      - Provisioning\n      - Remote Services\n    properties:\n      - type: Documentation\n        url: https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.4-series/idrac_3.40.40.40_lc_re_qsg/about-lifecycle-controller-api?guid=guid-f7bcc1d3-46c1-4ec3-9a45-0f33d734585c&lang=en-us\n\
  \  - aid: dell-servers:dell-servers-racadm\n    name: Dell RACADM CLI\n    description: >-\n      Command-line interface for Dell Remote Access Controller Administration.\n      RACADM provides local and remote command-line access to iDRAC for\n      scripting and automating server configuration, monitoring, and\n      management tasks.\n    image: https://www.dell.com/favicon.ico\n    humanURL: https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.x-series/idrac9_racadm_pub/\n    tags:\n      - Automation\n      - CLI\n      - Remote Management\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v3.x-series/idrac9_racadm_pub/\n  - aid: dell-servers:dell-servers-wsman\n    name: Dell WSMan API\n    description: >-\n      Web Services Management API for Dell server hardware management. WSMan\n      provides a SOAP-based interface for managing server configuration, BIOS,\n\
  \      RAID, NIC, and HBA settings on Dell PowerEdge servers through iDRAC.\n    image: https://www.dell.com/favicon.ico\n    baseURL: https://{idrac-ip}/wsman\n    humanURL: https://www.dell.com/support/kbdoc/en-us/000178046/how-to-use-the-wsman-interface-on-idrac\n    tags:\n      - Hardware Management\n      - Legacy\n      - Web Services\n      - WSMan\n    properties:\n      - type: Documentation\n        url: https://www.dell.com/support/kbdoc/en-us/000178046/how-to-use-the-wsman-interface-on-idrac\n      - type: Profile Catalog\n        url: https://downloads.dell.com/solutions/dell-management-solution-resources/\n      - type: GitHub Repository\n        url: https://github.com/dell/DellPEWSMANTools\ncommon:\n  - type: Portal\n    url: https://developer.dell.com/\n  - type: Getting Started\n    url: https://www.dell.com/support/manuals/en-us/idrac9-lifecycle-controller-v6.x-series/smog_26.0/idrac-restful-apis-redfish-standards-based?guid=guid-476c6603-818e-4e2e-82f0-699bde0c3a3c&lang=en-us\n\
  \  - type: Documentation\n    url: https://www.dell.com/support/product-details/en-us/product/dell-openmanage-enterprise/resources/manuals\n  - type: Support\n    url: https://www.dell.com/support\n  - type: Community\n    url: https://www.dell.com/community/\n  - type: Blog\n    url: https://www.dell.com/community/en/topics/developer-blogs\n  - type: TermsOfService\n    url: https://i.dell.com/sites/csdocuments/Legal_Docs/en/us/api-terms-of-use_en.pdf\n  - type: PrivacyPolicy\n    url: https://www.dell.com/en-us/lp/legal/policies-privacy\n  - type: Website\n    url: https://www.dell.com/en-us/lp/dt/open-manage\n  - type: GitHub\n    url: https://github.com/dell\n  - type: SDKs\n    url: https://developer.dell.com/apis/\n  - type: SignUp\n    url: https://developer.dell.com/\n  - type: Login\n    url: https://developer.dell.com/\n  - type: JSON-LD\n    url: json-ld/dell-servers-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/dell-servers-vocabulary.yml\nmaintainers:\n  - FN:\
  \ Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/apis.yml
tags:
- Hardware
- Infrastructure
- Management
- Monitoring
- Servers
url: https://raw.githubusercontent.com/api-evangelist/dell-servers/refs/heads/main/apis.yml
use_cases: []
---
