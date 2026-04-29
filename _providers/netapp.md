---
api_count: 14
api_specs:
- filename: netapp-ontap-openapi.yml
  format: yaml
  label: NetApp ONTAP REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/netapp/refs/heads/main/openapi/netapp-ontap-openapi.yml
apis:
- description: API for managing NetApp Cloud Volumes ONTAP and cloud data services.
  name: NetApp Cloud Manager API
  slug: ''
- description: REST API for NetApp ONTAP storage management system.
  name: NetApp ONTAP REST API
  slug: ''
- description: API for managing NetApp Cloud Volumes Service in major cloud providers.
  name: NetApp Cloud Volumes Service API
  slug: ''
- description: API for Kubernetes-native application data management.
  name: NetApp Astra Control API
  slug: ''
- description: API for object storage management with StorageGRID.
  name: NetApp StorageGRID API
  slug: ''
- description: API for NetApp Element software and NetApp HCI storage management.
  name: NetApp Element API
  slug: ''
- description: API for infrastructure monitoring and analytics.
  name: NetApp Cloud Insights API
  slug: ''
- description: REST API for automating the administration of cloud-based and on-premises storage resources managed by NetApp BlueXP, including Cloud Volumes ONTAP, on-premises ONTAP, and other BlueXP services.
  name: NetApp BlueXP Automation API
  slug: ''
- description: REST API for managing and monitoring storage resources on supported NetApp storage systems, including health, performance, capacity, and event management.
  name: NetApp Active IQ Unified Manager API
  slug: ''
- description: API services for NetApp Active IQ Digital Advisor providing system information, storage efficiency, performance, health, and upgrade insights across your NetApp installed base.
  name: NetApp Active IQ Digital Advisor API
  slug: ''
- description: REST API for automating SnapCenter data protection operations including backup, restore, and clone management for applications and databases.
  name: NetApp SnapCenter API
  slug: ''
- description: RESTful API for managing and monitoring NetApp E-Series and EF-Series storage systems through the SANtricity Web Services Proxy.
  name: NetApp E-Series SANtricity Web Services API
  slug: ''
- description: REST API for managing Azure NetApp Files resources including NetApp accounts, capacity pools, volumes, and snapshots in Microsoft Azure.
  name: Azure NetApp Files REST API
  slug: ''
- description: REST API for managing ONTAP tools for VMware vSphere, enabling storage provisioning, virtual machine lifecycle management, and vSphere integration.
  name: NetApp ONTAP Tools for VMware vSphere API
  slug: ''
capabilities:
- description: Unified workflow for managing NetApp ONTAP storage infrastructure including volumes, aggregates, SVMs, snapshots, and network interfaces. Used by storage administrators for provisioning and day-to-day
  name: NetApp Storage Management
  slug: storage-management
common:
- title: ''
  type: DeveloperPortal
  url: https://devnet.netapp.com/
- title: ''
  type: Support
  url: https://www.netapp.com/support-and-training/
- title: ''
  type: Blog
  url: https://netapp.io/
- title: ''
  type: GitHubOrganization
  url: https://github.com/NetApp
- title: ''
  type: Blog
  url: https://blog.netapp.com/
created: '2024'
description: Collection of NetApp APIs for cloud data services, storage management, and infrastructure.
features: []
image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg
integrations: []
jsonld:
- class_count: 0
  name: Netapp Context
  property_count: 8
  slug: netapp-context
- class_count: 0
  name: Netapp Ontap Context
  property_count: 0
  slug: netapp-ontap-context
layout: provider
modified: '2026-04-19'
name: NetApp
rules:
- name: NetApp API Rules
  rule_count: 7
  severity_counts:
    error: 7
    hint: 0
    info: 0
    warn: 0
  slug: netapp-spectral-rules
skills: []
slug: netapp
solutions: []
source_filename: apis.yml
source_yaml: "name: NetApp\ndescription: >-\n  Collection of NetApp APIs for cloud data services, storage management, and infrastructure.\nimage: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\nurl: https://www.netapp.com\ncreated: '2024'\nmodified: '2026-04-19'\nspecificationVersion: '0.18'\ntype: Index\naccess: 3rd-Party\ntags:\n  - Cloud\n  - Data Management\n  - Hybrid Cloud\n  - Infrastructure\n  - Storage\napis:\n  - name: NetApp Cloud Manager API\n    description: >-\n      API for managing NetApp Cloud Volumes ONTAP and cloud data services.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://cloudmanager.cloud.netapp.com\n    humanURL: https://docs.netapp.com/us-en/cloud-manager-automation/\n    tags:\n      - Automation\n      - Cloud Management\n      - ONTAP\n    properties:\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/cloud-manager-automation/\n      - type: OpenAPI\n  \
  \      url: https://docs.netapp.com/us-en/cloud-manager-automation/api/openapi.yaml\n      - type: Authentication\n        url: https://docs.netapp.com/us-en/cloud-manager-automation/platform/get_identifiers.html\n      - type: GettingStarted\n        url: https://docs.netapp.com/us-en/cloud-manager-automation/cm/your_api_call.html\n  - name: NetApp ONTAP REST API\n    description: >-\n      REST API for NetApp ONTAP storage management system.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://<cluster-management-ip>/api\n    humanURL: https://docs.netapp.com/us-en/ontap-automation/\n    tags:\n      - ONTAP\n      - REST API\n      - Storage Management\n    properties:\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/ontap-automation/\n      - type: APIReference\n        url: https://docs.netapp.com/us-en/ontap-automation/reference/api_reference.html\n      - type: GettingStarted\n        url: https://docs.netapp.com/us-en/ontap-automation/getting_started_with_the_ontap_rest_api.html\n\
  \      - type: Authentication\n        url: https://docs.netapp.com/us-en/ontap-automation/rest/authentication.html\n      - type: ReleaseNotes\n        url: https://docs.netapp.com/us-en/ontap-automation/whats-new.html\n      - type: APIReference\n        url: https://docs.netapp.com/us-en/ontap-restapi/\n      - type: GitHubRepository\n        url: https://github.com/NetApp/ontap-rest-python\n      - type: OpenAPI\n        url: openapi/netapp-ontap-openapi.yml\n      - type: JSONSchema\n        url: json-schema/netapp-volume-schema.json\n      - type: JSONLD\n        url: json-ld/netapp-context.jsonld\n  - name: NetApp Cloud Volumes Service API\n    description: >-\n      API for managing NetApp Cloud Volumes Service in major cloud providers.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://cloudvolumesgcp-api.netapp.com\n    humanURL: https://cloud.google.com/architecture/partners/netapp-cloud-volumes/api\n    tags:\n      - AWS\n\
  \      - Azure\n      - Cloud Volumes\n      - GCP\n    properties:\n      - type: Documentation\n        url: https://cloud.google.com/architecture/partners/netapp-cloud-volumes/api\n      - type: APIReference\n        url: https://cloud.google.com/architecture/partners/netapp-cloud-volumes/reference\n      - type: APIReference\n        url: https://docs.cloud.google.com/netapp/volumes/docs/reference/rest\n  - name: NetApp Astra Control API\n    description: >-\n      API for Kubernetes-native application data management.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://astra.netapp.io/accounts\n    humanURL: https://docs.netapp.com/us-en/astra-automation/\n    tags:\n      - Application Management\n      - Container Storage\n      - Data Protection\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/astra-automation/\n      - type: APIReference\n        url: https://docs.netapp.com/us-en/astra-automation/reference/overview.html\n\
  \      - type: GettingStarted\n        url: https://docs.netapp.com/us-en/astra-automation/get-started/overview.html\n  - name: NetApp StorageGRID API\n    description: >-\n      API for object storage management with StorageGRID.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://<storagegrid-endpoint>/api/v3\n    humanURL: https://docs.netapp.com/us-en/storagegrid-116/admin/using-grid-management-api.html\n    tags:\n      - Grid Management\n      - Object Storage\n      - S3\n    properties:\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/storagegrid-116/admin/using-grid-management-api.html\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/storagegrid/admin/using-grid-management-api.html\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/storagegrid/s3/\n  - name: NetApp Element API\n    description: >-\n      API for NetApp Element software and NetApp HCI storage\
  \ management.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://<mvip>/json-rpc\n    humanURL: https://docs.netapp.com/us-en/element-software/api/index.html\n    tags:\n      - Element\n      - HCI\n      - JSON-RPC\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/element-software/api/index.html\n      - type: APIReference\n        url: https://docs.netapp.com/us-en/element-software/api/reference_element_api_reference.html\n  - name: NetApp Cloud Insights API\n    description: >-\n      API for infrastructure monitoring and analytics.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://<tenant>.cloudinsights.netapp.com/rest/v1\n    humanURL: https://docs.netapp.com/us-en/cloudinsights/API_Overview.html\n    tags:\n      - Analytics\n      - Monitoring\n      - Observability\n    properties:\n      - type: Documentation\n\
  \        url: https://docs.netapp.com/us-en/cloudinsights/API_Overview.html\n      - type: Authentication\n        url: https://docs.netapp.com/us-en/cloudinsights/API_Overview.html#api-access-tokens\n  - name: NetApp BlueXP Automation API\n    description: REST API for automating the administration of cloud-based and on-premises storage resources managed by NetApp BlueXP, including Cloud Volumes ONTAP, on-premises ONTAP, and other BlueXP services.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://cloudmanager.cloud.netapp.com\n    humanURL: https://docs.netapp.com/us-en/bluexp-automation/\n    tags:\n      - BlueXP\n      - Cloud Automation\n      - Hybrid Cloud\n      - Storage Management\n    properties:\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/bluexp-automation/\n      - type: APIReference\n        url: https://docs.netapp.com/us-en/bluexp-automation/cm/api_reference.html\n      - type: GettingStarted\n\
  \        url: https://docs.netapp.com/us-en/bluexp-automation/cm/your_api_call.html\n      - type: Portal\n        url: https://bluexp.netapp.com/\n  - name: NetApp Active IQ Unified Manager API\n    description: REST API for managing and monitoring storage resources on supported NetApp storage systems, including health, performance, capacity, and event management.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://<aiqum-host>/api\n    humanURL: https://docs.netapp.com/us-en/active-iq-unified-manager/api-automation/concept_get_started_with_um_apis.html\n    tags:\n      - Active IQ\n      - Monitoring\n      - Storage Analytics\n      - Unified Manager\n    properties:\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/active-iq-unified-manager/api-automation/concept_get_started_with_um_apis.html\n      - type: Authentication\n        url: https://docs.netapp.com/us-en/active-iq-unified-manager/api-automation/concept_rest_api_access_and_authentication_in_um_apis.html\n\
  \  - name: NetApp Active IQ Digital Advisor API\n    description: API services for NetApp Active IQ Digital Advisor providing system information, storage efficiency, performance, health, and upgrade insights across your NetApp installed base.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://api.activeiq.netapp.com\n    humanURL: https://docs.netapp.com/us-en/active-iq/concept_overview_API_service.html\n    tags:\n      - Active IQ\n      - Digital Advisor\n      - Health\n      - Monitoring\n      - Upgrades\n    properties:\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/active-iq/concept_overview_API_service.html\n  - name: NetApp SnapCenter API\n    description: REST API for automating SnapCenter data protection operations including backup, restore, and clone management for applications and databases.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://<snapcenter-host>:8146/api\n\
  \    humanURL: https://docs.netapp.com/us-en/snapcenter/sc-automation/overview_rest_apis.html\n    tags:\n      - Backup\n      - Clone\n      - Data Protection\n      - Restore\n      - SnapCenter\n    properties:\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/snapcenter/sc-automation/overview_rest_apis.html\n      - type: APIReference\n        url: https://docs.netapp.com/us-en/snapcenter/sc-automation/reference_supported_rest_apis.html\n      - type: GettingStarted\n        url: https://docs.netapp.com/us-en/snapcenter/sc-automation/task_get_started_with_the_rest_api.html\n  - name: NetApp E-Series SANtricity Web Services API\n    description: RESTful API for managing and monitoring NetApp E-Series and EF-Series storage systems through the SANtricity Web Services Proxy.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://<web-services-proxy-host>/devmgr/v2\n    humanURL: https://docs.netapp.com/us-en/e-series/web-services-proxy/index.html\n\
  \    tags:\n      - E-Series\n      - SANtricity\n      - Storage\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/e-series/web-services-proxy/index.html\n      - type: APIReference\n        url: https://library.netapp.com/ecmdocs/ECMLP2839901/html/v2.html\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/e-series-family/\n  - name: Azure NetApp Files REST API\n    description: REST API for managing Azure NetApp Files resources including NetApp accounts, capacity pools, volumes, and snapshots in Microsoft Azure.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://management.azure.com\n    humanURL: https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-develop-with-rest-api\n    tags:\n      - Azure\n      - Cloud Volumes\n      - Microsoft Azure\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://learn.microsoft.com/en-us/azure/azure-netapp-files/azure-netapp-files-develop-with-rest-api\n\
  \      - type: APIReference\n        url: https://learn.microsoft.com/en-us/rest/api/netapp/\n  - name: NetApp ONTAP Tools for VMware vSphere API\n    description: REST API for managing ONTAP tools for VMware vSphere, enabling storage provisioning, virtual machine lifecycle management, and vSphere integration.\n    image: https://www.netapp.com/media/na_logo_black_rgb_reg-mark_tcm19-21014.jpg\n    baseURL: https://<ontap-tools-host>:8443\n    humanURL: https://docs.netapp.com/us-en/ontap-tools-vmware-vsphere/\n    tags:\n      - ONTAP\n      - Virtualization\n      - VMware\n      - vSphere\n    properties:\n      - type: Documentation\n        url: https://docs.netapp.com/us-en/ontap-tools-vmware-vsphere/\n      - type: APIReference\n        url: https://docs.netapp.com/us-en/ontap-tools-vmware-vsphere-104/automation/api-reference.html\n      - type: GettingStarted\n        url: https://docs.netapp.com/us-en/ontap-tools-vmware-vsphere-10/automation/get-started-with-the-rest-api.html\n\
  common:\n  - type: DeveloperPortal\n    url: https://devnet.netapp.com/\n  - type: Support\n    url: https://www.netapp.com/support-and-training/\n  - type: Blog\n    url: https://netapp.io/\n  - type: GitHubOrganization\n    url: https://github.com/NetApp\n  - type: Blog\n    url: https://blog.netapp.com/\n  - type: Features\n    url: https://www.netapp.com/data-management/\n  - type: UseCases\n    url: https://www.netapp.com/solutions/\n  - type: Integrations\n    url: https://bluexp.netapp.com/\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/netapp/refs/heads/main/apis.yml
tags:
- Cloud
- Data Management
- Hybrid Cloud
- Infrastructure
- Storage
url: https://www.netapp.com
use_cases: []
---
