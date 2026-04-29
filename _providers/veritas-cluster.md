---
api_count: 8
apis:
- description: RESTful API for managing cluster resources, service groups, and cluster configuration.
  name: Veritas Cluster Server REST API
  slug: ''
- description: Python SDK for programmatic cluster management and automation.
  name: Veritas Cluster Server Python API
  slug: ''
- description: Java-based API for integrating VCS management into enterprise applications.
  name: Veritas Cluster Server Java API
  slug: ''
- description: Command-line tools for cluster administration and monitoring.
  name: Veritas Cluster Server Command Line Interface
  slug: ''
- description: SNMP-based monitoring interface for cluster health and status.
  name: Veritas Cluster Server SNMP Agent
  slug: ''
- description: REST API for InfoScale storage and cluster configuration and management operations, supporting storage provisioning, disk group management, and volume operations. Available in InfoScale 8.0 and 9.0.
  name: Veritas InfoScale REST API
  slug: ''
- description: Web services API for InfoScale Operations Manager (VIOM) providing meta, query, update, and operations APIs for managing InfoScale objects over HTTPS. Supports management of hosts, clusters, LDEVs, an
  name: Veritas InfoScale Operations Manager Web Services API
  slug: ''
- description: InfoScale container support for Kubernetes and OpenShift, providing CSI-compliant storage drivers for dynamic and static provisioning, volume snapshots, and Prometheus metrics integration for monitori
  name: Veritas InfoScale for Kubernetes Environments
  slug: ''
common:
- title: ''
  type: Support
  url: https://www.veritas.com/support/en_US
- title: ''
  type: Portal
  url: https://my.veritas.com/
- title: ''
  type: KnowledgeCenter
  url: https://www.veritas.com/support/en_US/article-search.html
- title: ''
  type: TermsOfService
  url: https://www.veritas.com/about/legal/license-agreements
- title: ''
  type: PrivacyPolicy
  url: https://www.veritas.com/about/legal/privacy
- title: ''
  type: Documentation
  url: https://sort.veritas.com/documents/doc_details/via/8.0/Linux/Documentation/
- title: ''
  type: ReleaseNotes
  url: https://www.veritas.com/availability/infoscale/whats-new
- title: ''
  type: Blog
  url: https://vox.veritas.com/
- title: ''
  type: X
  url: https://twitter.com/VeritasTechLLC
- title: ''
  type: GitHubOrganization
  url: https://github.com/VeritasOS
created: '2024-01-15'
description: APIs for managing and monitoring Veritas Cluster Server (VCS) and InfoScale infrastructure, providing high availability, disaster recovery, and storage management capabilities across on-premises and containerized environments.
features: []
image: /assets/icons/veritas-cluster.png
integrations: []
layout: provider
modified: '2026-04-19'
name: Veritas Cluster Server
skills: []
slug: veritas-cluster
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: veritas-cluster\nname: Veritas Cluster Server\ndescription: APIs for managing and monitoring Veritas Cluster Server (VCS) and InfoScale infrastructure, providing high availability, disaster recovery, and storage management capabilities across on-premises and containerized environments.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/veritas-cluster/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n  - Clustering\n  - Containers\n  - Disaster Recovery\n  - Failover\n  - High Availability\n  - InfoScale\n  - Infrastructure Management\n  - Kubernetes\n  - Storage Management\n  - Veritas\napis:\n  - name: Veritas Cluster Server REST API\n    description: >-\n      RESTful API for managing cluster resources, service groups, and cluster configuration.\n    baseURL: https://{vcs-management-server}:14150/api/v1\n    humanURL:\
  \ https://www.veritas.com/support/en_US/article.100040102\n    tags:\n      - Cluster Management\n      - Resources\n      - REST\n      - Service Groups\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/vcs/8.0/linux/productguides/html/vcs_rest_api/index.htm\n      - type: OpenAPI\n        url: https://vcs-server:14150/api/docs/openapi.json\n      - type: Authentication\n        url: https://sort.veritas.com/public/documents/vcs/8.0/linux/productguides/html/vcs_rest_api/ch02.htm\n    contact:\n      - FN: Veritas Support\n        email: support@veritas.com\n        X-twitter: VeritasTechLLC\n  - name: Veritas Cluster Server Python API\n    description: >-\n      Python SDK for programmatic cluster management and automation.\n    baseURL: https://{vcs-management-server}:14150\n    humanURL: https://www.veritas.com/support/en_US/article.100040102\n    tags:\n      - Automation\n      - Python\n      - Scripting\n      - SDK\n    properties:\n\
  \      - type: Documentation\n        url: https://sort.veritas.com/public/documents/vcs/8.0/linux/productguides/html/vcs_python_api/\n      - type: SDK\n        url: https://sort.veritas.com/public/documents/vcs/8.0/linux/productguides/html/vcs_python_api/ch01s02.htm\n  - name: Veritas Cluster Server Java API\n    description: >-\n      Java-based API for integrating VCS management into enterprise applications.\n    humanURL: https://www.veritas.com/support/en_US/article.DOC5308\n    tags:\n      - Enterprise Integration\n      - Java\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/vcs/7.4/linux/productguides/html/vcs_java_api/\n      - type: SDK\n        url: https://sort.veritas.com/public/documents/vcs/7.4/linux/productguides/html/vcs_java_api/ch01s03.htm\n  - name: Veritas Cluster Server Command Line Interface\n    description: >-\n      Command-line tools for cluster administration and monitoring.\n    humanURL: https://www.veritas.com/support/en_US/article.DOC5308\n\
  \    tags:\n      - Administration\n      - CLI\n      - Command Line\n      - Monitoring\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/vcs/8.0/linux/productguides/html/vcs_admin/index.htm\n      - type: APIReference\n        url: https://sort.veritas.com/public/documents/vcs/8.0/linux/productguides/html/vcs_command_reference/\n  - name: Veritas Cluster Server SNMP Agent\n    description: >-\n      SNMP-based monitoring interface for cluster health and status.\n    humanURL: https://www.veritas.com/support/en_US/article.DOC5308\n    tags:\n      - Alerting\n      - Monitoring\n      - SNMP\n      - Traps\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/vcs/8.0/linux/productguides/html/vcs_admin/ch22.htm\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/article.TECH95356\n  - name: Veritas InfoScale REST API\n    description: REST API for InfoScale\
  \ storage and cluster configuration and management operations, supporting storage provisioning, disk group management, and volume operations. Available in InfoScale 8.0 and 9.0.\n    baseURL: https://{infoscale-rest-server}:14150/infoscale/api/2.0\n    humanURL: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478\n    tags:\n      - Cluster Management\n      - InfoScale\n      - REST\n      - Storage Management\n      - Volume Management\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478\n      - type: APIReference\n        url: https://www.veritas.com/support/en_US/doc/79638609-149461849-0/v151832379-149461849\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/79638609-149461849-0/v151837041-149461849\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151835060-166315478\n\
  \      - type: ReleaseNotes\n        url: https://www.veritas.com/support/en_US/doc/109864724-166315456-0/v151831652-166315456\n      - type: Documentation\n        url: https://{infoscale-rest-server}:14150/infoscale/api/2.0/metrics\n  - name: Veritas InfoScale Operations Manager Web Services API\n    description: Web services API for InfoScale Operations Manager (VIOM) providing meta, query, update, and operations APIs for managing InfoScale objects over HTTPS. Supports management of hosts, clusters, LDEVs, and virtualization servers.\n    baseURL: https://{management-server}:14161/vom/api\n    humanURL: https://www.veritas.com/support/en_US/doc/120572053-156079406-0/index\n    tags:\n      - Management\n      - Monitoring\n      - Operations Manager\n      - REST\n      - VIOM\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/120572053-156079406-0/index\n      - type: Authentication\n        url: https://www.veritas.com/support/en_US/doc/120572053-156079406-0/viom_tot_v84306317-156079406\n\
  \      - type: CodeExamples\n        url: https://www.veritas.com/support/en_US/doc/120572053-156079406-0/viom_tot_v96894970-156079406\n      - type: APIReference\n        url: https://www.veritas.com/content/support/en_US/doc/132757515-132757518-0/br74_viom_tot_v96212267-132757518\n      - type: Blog\n        url: https://vox.veritas.com/blog/storage-and-availability-management/increasing-flexibility-for-infoscale-environments-with-the-viom-api/881889\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/downloads/detail.REL133180\n      - type: GettingStarted\n        url: https://www.veritas.com/support/en_US/doc/120571566-156079382-0/index\n  - name: Veritas InfoScale for Kubernetes Environments\n    description: InfoScale container support for Kubernetes and OpenShift, providing CSI-compliant storage drivers for dynamic and static provisioning, volume snapshots, and Prometheus metrics integration for monitoring.\n    humanURL: https://www.veritas.com/support/en_US/doc/167166372-167166485-0/index\n\
  \    tags:\n      - Containers\n      - CSI\n      - Kubernetes\n      - Monitoring\n      - OpenShift\n      - Prometheus\n      - Storage Provisioning\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/167166372-167166485-0/index\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/167166372-167166485-0/v167165336-167166485\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/151215298-151215302-0/index\ncommon:\n  - type: Support\n    url: https://www.veritas.com/support/en_US\n  - type: Portal\n    url: https://my.veritas.com/\n  - type: KnowledgeCenter\n    url: https://www.veritas.com/support/en_US/article-search.html\n  - type: TermsOfService\n    url: https://www.veritas.com/about/legal/license-agreements\n  - type: PrivacyPolicy\n    url: https://www.veritas.com/about/legal/privacy\n  - type: Documentation\n    url: https://sort.veritas.com/documents/doc_details/via/8.0/Linux/Documentation/\n\
  \  - type: ReleaseNotes\n    url: https://www.veritas.com/availability/infoscale/whats-new\n  - type: Blog\n    url: https://vox.veritas.com/\n  - type: X\n    url: https://twitter.com/VeritasTechLLC\n  - type: GitHubOrganization\n    url: https://github.com/VeritasOS\n  - type: Features\n    url: https://www.veritas.com/availability/infoscale\n  - type: UseCases\n    url: https://www.veritas.com/availability/infoscale/whats-new\n  - type: Integrations\n    url: https://www.veritas.com/availability/infoscale\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n    X-github: kinlane\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/veritas-cluster/refs/heads/main/apis.yml
tags:
- Clustering
- Containers
- Disaster Recovery
- Failover
- High Availability
- InfoScale
- Infrastructure Management
- Kubernetes
- Storage Management
- Veritas
url: https://raw.githubusercontent.com/api-evangelist/veritas-cluster/refs/heads/main/apis.yml
use_cases: []
---
