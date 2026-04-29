---
api_count: 4
api_specs:
- filename: veritas-infoscale-rest-api.yaml
  format: yaml
  label: Veritas InfoScale REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veritas-infoscale/refs/heads/main/openapi/veritas-infoscale-rest-api.yaml
apis:
- description: REST API for managing InfoScale clusters, storage resources, and high availability configurations. Supports storage configuration and management operations including disk groups, volumes, and file sys
  name: Veritas InfoScale REST API
  slug: rest-api
- description: REST API for centralized monitoring and management of InfoScale environments. Provides meta, query, update, and operational endpoints for managing clusters, service groups, hosts, storage, and extende
  name: Veritas InfoScale Operations Manager API
  slug: operations-manager-api
- description: 'API for managing VCS clusters, service groups, and resources within InfoScale. Provides operations for cluster node management, service group failover and failback, resource dependency configuration, '
  name: Veritas Cluster Server API
  slug: vcs-api
- description: API for storage volume management, including volume creation, resizing, mirroring, and snapshot operations. Manages disk groups, plexes, subdisks, and provides advanced storage features like thin prov
  name: Veritas Volume Manager API
  slug: vxvm-api
capabilities:
- description: Unified infrastructure management workflow combining the Veritas InfoScale REST API for managing clusters, service groups, storage volumes, disk groups, and alerts. Used by infrastructure engineers, s
  name: Veritas InfoScale Infrastructure Management
  slug: infrastructure-management
common:
- title: ''
  type: Portal
  url: https://my.veritas.com
- title: ''
  type: Support
  url: https://www.veritas.com/support
- title: ''
  type: KnowledgeCenter
  url: https://www.veritas.com/support/en_US/dpp.InfoScaleStorageFoundation
- title: ''
  type: Documentation
  url: https://sort.veritas.com
- title: ''
  type: GettingStarted
  url: https://sort.veritas.com/infoscale/intro
- title: ''
  type: Training
  url: https://www.veritas.com/support/training
- title: ''
  type: Blog
  url: https://vox.veritas.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/VeritasOS
- title: InfoScale Ansible Playbooks
  type: GitHubRepository
  url: https://github.com/VeritasOS/infoscale_ansible
- title: ''
  type: TermsOfService
  url: https://www.veritas.com/company/legal/terms-of-use
- title: ''
  type: PrivacyPolicy
  url: https://www.veritas.com/company/legal/privacy
- title: ''
  type: Contact
  url: https://www.veritas.com/form/requestacall
- title: ''
  type: Pricing
  url: https://sort.veritas.com/license_calc
- title: ''
  type: ReleaseNotes
  url: https://www.veritas.com/support/en_US/doc/infoscale
- title: ''
  type: SpectralRules
  url: rules/veritas-infoscale-spectral-rules.yml
- title: Infrastructure Management
  type: NaftikoCapability
  url: capabilities/infrastructure-management.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/veritas-infoscale-vocabulary.yaml
created: '2025-03-14'
description: APIs for Veritas InfoScale, an enterprise storage and availability management solution that provides high availability, disaster recovery, and storage management capabilities across physical, virtual, and cloud environments.
features:
- description: Provides application-aware clustering with automatic failover and failback to ensure continuous availability of mission-critical applications.
  name: High Availability Clustering
- description: Uses asynchronous event-based monitoring (IMF) to detect failures instantaneously, eliminating CPU overhead of legacy poll-based monitoring.
  name: Intelligent Monitoring Framework
- description: Software-defined storage services for volume management, thin provisioning, data migration, and multi-pathing across heterogeneous storage arrays.
  name: Storage Management
- description: Volume replication (VVR) and file replication (VFR) for real-time data replication across sites with automated disaster recovery orchestration.
  name: Disaster Recovery
- description: Space-optimized snapshots for backup, data analytics, forensic discovery, and point-in-time recovery without impacting production workloads.
  name: Snapshot Management
- description: Native CSI driver providing persistent storage on DAS and SAN with data integrity using I/O fencing for Kubernetes and OpenShift environments.
  name: Kubernetes Integration
- description: Deployment on AWS, Azure, Google Cloud, and Oracle Cloud with solution templates and marketplace offerings for elastic scaling.
  name: Cloud Deployment
- description: Full REST API support for control plane operations enabling automation and integration with DevOps pipelines and orchestration tools.
  name: REST API Management
image: /assets/icons/veritas-infoscale.png
integrations:
- description: Deep integration with Oracle RAC and single-instance databases for storage management, availability, and disaster recovery.
  name: Oracle Database
- description: Certified integration with SAP HANA and SAP applications for high availability and disaster recovery in enterprise environments.
  name: SAP Applications
- description: High availability and storage management for SQL Server Always On availability groups and failover cluster instances.
  name: Microsoft SQL Server
- description: Integration with VMware vSphere and vSAN for virtualized application availability and storage management.
  name: VMware vSphere
- description: CSI driver integration for persistent storage provisioning and management in container orchestration platforms.
  name: Kubernetes and OpenShift
- description: Ansible modules for automated deployment, configuration, and management of InfoScale environments in DevOps pipelines.
  name: Ansible Automation
- description: SRDF MetroCluster support with Dell EMC PowerMax and vMAX arrays for storage replication and disaster recovery.
  name: Dell EMC Storage
- description: Cloud marketplace offerings and solution templates for deployment on Amazon Web Services and Microsoft Azure platforms.
  name: AWS and Azure
jsonld:
- class_count: 10
  name: Veritas Infoscale Rest Api Context
  property_count: 38
  slug: veritas-infoscale-rest-api-context
layout: provider
modified: '2026-04-18'
name: Veritas InfoScale
rules:
- name: Veritas InfoScale API Rules
  rule_count: 39
  severity_counts:
    error: 23
    hint: 0
    info: 6
    warn: 10
  slug: veritas-infoscale-spectral-rules
skills: []
slug: veritas-infoscale
solutions: []
source_filename: apis.yml
source_yaml: "aid: veritas-infoscale\nname: Veritas InfoScale\ndescription: >-\n  APIs for Veritas InfoScale, an enterprise storage and availability management\n  solution that provides high availability, disaster recovery, and storage\n  management capabilities across physical, virtual, and cloud environments.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/veritas-infoscale/refs/heads/main/apis.yml\ncreated: '2025-03-14'\nmodified: '2026-04-18'\nspecificationVersion: '0.19'\ntags:\n  - Clustering\n  - Data Management\n  - Disaster Recovery\n  - High Availability\n  - Storage Management\n  - Virtualization\napis:\n  - aid: veritas-infoscale:rest-api\n    name: Veritas InfoScale REST API\n    description: >-\n      REST API for managing InfoScale clusters, storage resources, and high\n      availability configurations. Supports storage configuration and management\n      operations including\
  \ disk groups, volumes, and file systems, as well as\n      cluster configuration and management operations including service groups,\n      resources, and heartbeats.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478\n    baseURL: https://{infoscale-server}:14149/api/v1\n    tags:\n      - Availability\n      - Clustering\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478\n      - type: OpenAPI\n        url: openapi/veritas-infoscale-rest-api.yaml\n      - type: Authentication\n        url: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151837041-166315478\n      - type: JSONSchema\n        url: json-schema/rest-api-cluster-schema.json\n        title: Cluster Schema\n      - type: JSONSchema\n        url: json-schema/rest-api-service-group-schema.json\n\
  \        title: Service Group Schema\n      - type: JSONSchema\n        url: json-schema/rest-api-disk-group-schema.json\n        title: Disk Group Schema\n      - type: JSONSchema\n        url: json-schema/rest-api-volume-schema.json\n        title: Volume Schema\n      - type: JSONSchema\n        url: json-schema/rest-api-system-schema.json\n        title: System Schema\n      - type: JSONSchema\n        url: json-schema/rest-api-alert-schema.json\n        title: Alert Schema\n      - type: JSONStructure\n        url: json-structure/rest-api-cluster-structure.json\n        title: Cluster Structure\n      - type: JSONStructure\n        url: json-structure/rest-api-service-group-structure.json\n        title: Service Group Structure\n      - type: JSONStructure\n        url: json-structure/rest-api-disk-group-structure.json\n        title: Disk Group Structure\n      - type: JSONStructure\n        url: json-structure/rest-api-volume-structure.json\n        title: Volume Structure\n   \
  \   - type: JSONLD\n        url: json-ld/veritas-infoscale-rest-api-context.jsonld\n      - type: Example\n        url: examples/rest-api-cluster-example.json\n        title: Cluster Example\n      - type: Example\n        url: examples/rest-api-service-group-example.json\n        title: Service Group Example\n      - type: Example\n        url: examples/rest-api-disk-group-example.json\n        title: Disk Group Example\n      - type: Example\n        url: examples/rest-api-volume-example.json\n        title: Volume Example\n      - type: Example\n        url: examples/rest-api-system-example.json\n        title: System Example\n      - type: Example\n        url: examples/rest-api-alert-example.json\n        title: Alert Example\n    contact:\n      - FN: Veritas Support\n        email: support@veritas.com\n        url: https://www.veritas.com/support\n  - aid: veritas-infoscale:operations-manager-api\n    name: Veritas InfoScale Operations Manager API\n    description: >-\n      REST\
  \ API for centralized monitoring and management of InfoScale\n      environments. Provides meta, query, update, and operational endpoints for\n      managing clusters, service groups, hosts, storage, and extended attributes\n      across the entire InfoScale infrastructure.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.veritas.com/support/en_US/doc/120572053-156079406-0/viom_tot_v96894970-156079406\n    baseURL: https://{isom-server}:14161/vom/api\n    tags:\n      - Management\n      - Monitoring\n      - Operations\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/120572053-156079406-0/viom_tot_v96894970-156079406\n      - type: APIReference\n        url: https://sort.veritas.com/public/documents/vom/7.3/windowsandunix/productguides/html/viom_user/ch38.htm\n  - aid: veritas-infoscale:vcs-api\n    name: Veritas Cluster Server API\n    description: >-\n      API for managing\
  \ VCS clusters, service groups, and resources within\n      InfoScale. Provides operations for cluster node management, service group\n      failover and failback, resource dependency configuration, and heartbeat\n      monitoring.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478\n    baseURL: https://{vcs-server}:14149/vcs/api\n    tags:\n      - Clustering\n      - Failover\n      - High Availability\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478\n      - type: CLI\n        url: https://www.veritas.com/support/en_US/doc/cluster-server/cli-reference\n  - aid: veritas-infoscale:vxvm-api\n    name: Veritas Volume Manager API\n    description: >-\n      API for storage volume management, including volume creation, resizing,\n      mirroring, and snapshot operations.\
  \ Manages disk groups, plexes, subdisks,\n      and provides advanced storage features like thin provisioning, data\n      migration, and volume replication.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478\n    baseURL: https://{server}:14149/vxvm/api\n    tags:\n      - Snapshots\n      - Storage\n      - Volumes\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478\n      - type: GettingStarted\n        url: https://www.veritas.com/support/en_US/doc/volume-manager/admin-guide\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ncommon:\n  - type: Portal\n    url: https://my.veritas.com\n  - type: Support\n    url: https://www.veritas.com/support\n  - type: KnowledgeCenter\n    url: https://www.veritas.com/support/en_US/dpp.InfoScaleStorageFoundation\n\
  \  - type: Documentation\n    url: https://sort.veritas.com\n  - type: GettingStarted\n    url: https://sort.veritas.com/infoscale/intro\n  - type: Training\n    url: https://www.veritas.com/support/training\n  - type: Blog\n    url: https://vox.veritas.com\n  - type: GitHubOrganization\n    url: https://github.com/VeritasOS\n  - type: GitHubRepository\n    url: https://github.com/VeritasOS/infoscale_ansible\n    title: InfoScale Ansible Playbooks\n  - type: TermsOfService\n    url: https://www.veritas.com/company/legal/terms-of-use\n  - type: PrivacyPolicy\n    url: https://www.veritas.com/company/legal/privacy\n  - type: Contact\n    url: https://www.veritas.com/form/requestacall\n  - type: Pricing\n    url: https://sort.veritas.com/license_calc\n  - type: ReleaseNotes\n    url: https://www.veritas.com/support/en_US/doc/infoscale\n  - type: SpectralRules\n    url: rules/veritas-infoscale-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/infrastructure-management.yaml\n\
  \    title: Infrastructure Management\n  - type: Vocabulary\n    url: vocabulary/veritas-infoscale-vocabulary.yaml\n  - type: Features\n    data:\n      - name: High Availability Clustering\n        description: Provides application-aware clustering with automatic failover and failback to ensure continuous availability of mission-critical applications.\n      - name: Intelligent Monitoring Framework\n        description: Uses asynchronous event-based monitoring (IMF) to detect failures instantaneously, eliminating CPU overhead of legacy poll-based monitoring.\n      - name: Storage Management\n        description: Software-defined storage services for volume management, thin provisioning, data migration, and multi-pathing across heterogeneous storage arrays.\n      - name: Disaster Recovery\n        description: Volume replication (VVR) and file replication (VFR) for real-time data replication across sites with automated disaster recovery orchestration.\n      - name: Snapshot Management\n\
  \        description: Space-optimized snapshots for backup, data analytics, forensic discovery, and point-in-time recovery without impacting production workloads.\n      - name: Kubernetes Integration\n        description: Native CSI driver providing persistent storage on DAS and SAN with data integrity using I/O fencing for Kubernetes and OpenShift environments.\n      - name: Cloud Deployment\n        description: Deployment on AWS, Azure, Google Cloud, and Oracle Cloud with solution templates and marketplace offerings for elastic scaling.\n      - name: REST API Management\n        description: Full REST API support for control plane operations enabling automation and integration with DevOps pipelines and orchestration tools.\n  - type: UseCases\n    data:\n      - name: Application High Availability\n        description: Ensure zero-downtime for mission-critical applications like Oracle, SAP, and SQL Server with automatic failover and health monitoring.\n      - name: Disaster Recovery\
  \ Automation\n        description: Automate cross-site replication and recovery orchestration to meet RPO and RTO requirements for business continuity planning.\n      - name: Storage Consolidation\n        description: Consolidate heterogeneous storage arrays into a unified software-defined storage layer with volume management.\n      - name: Cloud Migration\n        description: Migrate on-premises applications to cloud environments with consistent storage and availability management across hybrid infrastructure.\n      - name: Container Storage\n        description: Provide enterprise-grade persistent storage for containerized applications on Kubernetes and OpenShift with CSI driver integration.\n      - name: Database Protection\n        description: Protect databases with application-consistent snapshots, online data migration, and real-time replication without application downtime.\n  - type: Integrations\n    data:\n      - name: Oracle Database\n        description: Deep integration\
  \ with Oracle RAC and single-instance databases for storage management, availability, and disaster recovery.\n      - name: SAP Applications\n        description: Certified integration with SAP HANA and SAP applications for high availability and disaster recovery in enterprise environments.\n      - name: Microsoft SQL Server\n        description: High availability and storage management for SQL Server Always On availability groups and failover cluster instances.\n      - name: VMware vSphere\n        description: Integration with VMware vSphere and vSAN for virtualized application availability and storage management.\n      - name: Kubernetes and OpenShift\n        description: CSI driver integration for persistent storage provisioning and management in container orchestration platforms.\n      - name: Ansible Automation\n        description: Ansible modules for automated deployment, configuration, and management of InfoScale environments in DevOps pipelines.\n      - name: Dell EMC Storage\n\
  \        description: SRDF MetroCluster support with Dell EMC PowerMax and vMAX arrays for storage replication and disaster recovery.\n      - name: AWS and Azure\n        description: Cloud marketplace offerings and solution templates for deployment on Amazon Web Services and Microsoft Azure platforms.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/veritas-infoscale/refs/heads/main/apis.yml
tags:
- Clustering
- Data Management
- Disaster Recovery
- High Availability
- Storage Management
- Virtualization
url: https://raw.githubusercontent.com/api-evangelist/veritas-infoscale/refs/heads/main/apis.yml
use_cases:
- description: Ensure zero-downtime for mission-critical applications like Oracle, SAP, and SQL Server with automatic failover and health monitoring.
  name: Application High Availability
- description: Automate cross-site replication and recovery orchestration to meet RPO and RTO requirements for business continuity planning.
  name: Disaster Recovery Automation
- description: Consolidate heterogeneous storage arrays into a unified software-defined storage layer with volume management.
  name: Storage Consolidation
- description: Migrate on-premises applications to cloud environments with consistent storage and availability management across hybrid infrastructure.
  name: Cloud Migration
- description: Provide enterprise-grade persistent storage for containerized applications on Kubernetes and OpenShift with CSI driver integration.
  name: Container Storage
- description: Protect databases with application-consistent snapshots, online data migration, and real-time replication without application downtime.
  name: Database Protection
---
