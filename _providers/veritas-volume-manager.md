---
api_count: 7
apis:
- description: RESTful API for managing storage volumes, disk groups, and storage operations.
  name: Veritas Volume Manager REST API
  slug: ''
- description: Command-line interface and scripting API for Veritas Volume Manager operations.
  name: VxVM Command Line API
  slug: ''
- description: Comprehensive API for Veritas Storage Foundation including volume management.
  name: Storage Foundation API
  slug: ''
- description: 'REST API for InfoScale storage configuration and management operations including volume, disk group, and cluster management. The REST server is configured on cluster nodes and supports operations for '
  name: Veritas InfoScale REST API
  slug: ''
- description: REST API support for InfoScale 9.0 providing storage configuration and management operations, including HA configuration for the REST server and expanded supported operations for enterprise storage ma
  name: Veritas InfoScale 9.0 REST API
  slug: ''
- description: HTTPS-based Web Services API for Veritas InfoScale Operations Manager (VIOM) providing the ability to query discovered data, manage user-defined attributes, and perform operations on InfoScale objects
  name: InfoScale Operations Manager Web Services API
  slug: ''
- description: API for administering and monitoring InfoScale in Kubernetes and OpenShift container environments. Provides CSI driver integration for persistent storage, volume snapshots, and storage class managemen
  name: InfoScale for Kubernetes API
  slug: ''
common:
- title: ''
  type: Portal
  url: https://my.veritas.com
- title: ''
  type: GettingStarted
  url: https://www.veritas.com/support/en_US/article.GETSTART100
- title: ''
  type: TermsOfService
  url: https://www.veritas.com/about/legal/license-agreements
- title: ''
  type: PrivacyPolicy
  url: https://www.veritas.com/about/legal/privacy-policy
- title: ''
  type: StatusPage
  url: https://status.veritas.com
- title: ''
  type: ChangeLog
  url: https://www.veritas.com/support/en_US/article.CHANGELOG
- title: ''
  type: Blog
  url: https://www.veritas.com/blogs
- title: ''
  type: Support
  url: https://www.veritas.com/support/en_US/dpp.InfoScaleStorageFoundation
created: '2024-01-01'
description: APIs for managing storage volumes, disk groups, and file systems using Veritas Volume Manager (VVM).
features: []
image: https://www.veritas.com/content/dam/veritas/images/logos/veritas-logo.svg
integrations: []
layout: provider
modified: '2026-04-19'
name: Veritas Volume Manager
skills: []
slug: veritas-volume-manager
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Veritas Volume Manager\ndescription: >-\n  APIs for managing storage volumes, disk groups, and file systems using Veritas Volume\n  Manager (VVM).\nimage: https://www.veritas.com/content/dam/veritas/images/logos/veritas-logo.svg\nurl: https://www.veritas.com/support/en_US/volume-manager\ncreated: '2024-01-01'\nmodified: '2026-04-19'\nspecificationVersion: '0.16'\ntags:\n  - Disaster Recovery\n  - Enterprise Storage\n  - File Systems\n  - Storage\n  - Volume Management\napis:\n  - name: Veritas Volume Manager REST API\n    description: >-\n      RESTful API for managing storage volumes, disk groups, and storage operations.\n    image: https://www.veritas.com/content/dam/veritas/images/logos/veritas-logo.svg\n    humanURL: https://www.veritas.com/support/en_US/volume-manager\n    baseURL: https://api.veritas.com/vvm/v1\n    tags:\n      - Disk Groups\n      - Snapshots\n      - Storage Pools\n      - Volumes\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/article.DOC5555\n\
  \      - type: OpenAPI\n        url: https://api.veritas.com/vvm/v1/openapi.json\n      - type: Authentication\n        url: https://www.veritas.com/support/en_US/article.AUTH100\n      - type: SDK\n        url: https://www.veritas.com/support/en_US/downloads/sdks\n      - type: RateLimits\n        url: https://www.veritas.com/support/en_US/article.LIMITS100\n    contact:\n      - type: Support\n        url: https://www.veritas.com/support/en_US/contact-support\n      - type: Email\n        url: mailto:support@veritas.com\n      - type: Twitter\n        url: https://twitter.com/Veritas\n  - name: VxVM Command Line API\n    description: >-\n      Command-line interface and scripting API for Veritas Volume Manager operations.\n    humanURL: https://www.veritas.com/support/en_US/article.VXVM100\n    tags:\n      - Administration\n      - CLI\n      - Scripting\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/article.CLI5555\n      - type: APIReference\n\
  \        url: https://www.veritas.com/support/en_US/article.CMDREF100\n      - type: CodeExamples\n        url: https://www.veritas.com/support/en_US/article.EXAMPLES100\n  - name: Storage Foundation API\n    description: >-\n      Comprehensive API for Veritas Storage Foundation including volume management.\n    humanURL: https://www.veritas.com/support/en_US/storage-foundation\n    baseURL: https://api.veritas.com/sf/v1\n    tags:\n      - Enterprise\n      - High Availability\n      - Storage Foundation\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/article.SF5555\n      - type: APIReference\n        url: https://api.veritas.com/sf/v1/docs\n  - name: Veritas InfoScale REST API\n    description: >-\n      REST API for InfoScale storage configuration and management operations\n      including volume, disk group, and cluster management. The REST server\n      is configured on cluster nodes and supports operations for storage\n      provisioning,\
  \ snapshots, replication, and high availability management.\n    humanURL: https://www.veritas.com/support/en_US/doc/79638609-149461849-0/v151837041-149461849\n    tags:\n      - Cluster Management\n      - High Availability\n      - Infoscale\n      - REST\n      - Storage Configuration\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/79638609-149461849-0/v151837041-149461849\n      - type: APIReference\n        url: https://www.veritas.com/support/en_US/doc/79638609-149461849-0/v151832379-149461849\n      - type: ReleaseNotes\n        url: https://www.veritas.com/support/en_US/doc/109864724-166315456-0/index\n  - name: Veritas InfoScale 9.0 REST API\n    description: >-\n      REST API support for InfoScale 9.0 providing storage configuration and\n      management operations, including HA configuration for the REST server\n      and expanded supported operations for enterprise storage management.\n    humanURL: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478\n\
  \    tags:\n      - Enterprise\n      - Infoscale\n      - REST\n      - Storage Management\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151832379-166315478\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v151835060-166315478\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/79638609-166315478-0/v109543903-166315478\n  - name: InfoScale Operations Manager Web Services API\n    description: >-\n      HTTPS-based Web Services API for Veritas InfoScale Operations Manager\n      (VIOM) providing the ability to query discovered data, manage user-defined\n      attributes, and perform operations on InfoScale objects. Supports Meta,\n      Query, Update, and Operations API categories accessible via standard\n      HTTPS clients including cURL.\n    humanURL: https://www.veritas.com/support/en_US/doc/120572053-156079406-0/index\n\
  \    tags:\n      - Management\n      - Monitoring\n      - Operations Manager\n      - VIOM\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://sort.veritas.com/public/documents/vom/7.3/windowsandunix/productguides/html/viom_user/ch38.htm\n      - type: GettingStarted\n        url: https://sort.veritas.com/public/documents/vom/7.3/windowsandunix/productguides/html/viom_user/ch38s01.htm\n      - type: Authentication\n        url: https://www.veritas.com/support/en_US/doc/120572053-156079406-0/viom_tot_v84306317-156079406\n      - type: APIReference\n        url: https://sort.veritas.com/public/documents/vom/7.3/windowsandunix/productguides/html/viom_user/ch38s05.htm\n      - type: CodeExamples\n        url: https://www.veritas.com/support/en_US/doc/120572053-156079406-0/viom_tot_v96894970-156079406\n      - type: APIReference\n        url: https://www.veritas.com/content/support/en_US/doc/132757515-132757518-0/br74_viom_tot_v96212267-132757518\n  -\
  \ name: InfoScale for Kubernetes API\n    description: >-\n      API for administering and monitoring InfoScale in Kubernetes and OpenShift\n      container environments. Provides CSI driver integration for persistent\n      storage, volume snapshots, and storage class management with enterprise\n      data services for containerized applications.\n    humanURL: https://www.veritas.com/support/en_US/doc/167166372-167166485-0/v167165336-167166485\n    tags:\n      - Cloud Native\n      - Containers\n      - CSI\n      - Kubernetes\n      - Openshift\n    properties:\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/doc/167166372-167166485-0/v167165336-167166485\n      - type: GettingStarted\n        url: https://www.veritas.com/support/en_US/doc/161711084-161711096-0/index\n      - type: Documentation\n        url: https://www.veritas.com/support/en_US/downloads/detail.REL134671\ncommon:\n  - type: Portal\n    url: https://my.veritas.com\n  - type: GettingStarted\n\
  \    url: https://www.veritas.com/support/en_US/article.GETSTART100\n  - type: TermsOfService\n    url: https://www.veritas.com/about/legal/license-agreements\n  - type: PrivacyPolicy\n    url: https://www.veritas.com/about/legal/privacy-policy\n  - type: StatusPage\n    url: https://status.veritas.com\n  - type: ChangeLog\n    url: https://www.veritas.com/support/en_US/article.CHANGELOG\n  - type: Blog\n    url: https://www.veritas.com/blogs\n  - type: Support\n    url: https://www.veritas.com/support/en_US/dpp.InfoScaleStorageFoundation\n  - type: Features\n    url: https://www.veritas.com/availability/infoscale\n  - type: UseCases\n    url: https://www.veritas.com/availability/infoscale\n  - type: Integrations\n    url: https://www.veritas.com/availability/infoscale\nmaintainers:\n  - name: Kin Lane\n    email: kin@apievangelist.com\n    url: https://apievangelist.com\n  - name: Veritas Technologies LLC\n    email: api-support@veritas.com\n    url: https://www.veritas.com\n  - name:\
  \ API Team\n    email: api-team@veritas.com\ninclude:\n  - name: Volume Operations\n    url: https://api.veritas.com/vvm/v1/apis/volumes.yaml\n  - name: Disk Group Operations\n    url: https://api.veritas.com/vvm/v1/apis/diskgroups.yaml\n  - name: Snapshot Operations\n    url: https://api.veritas.com/vvm/v1/apis/snapshots.yaml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/veritas-volume-manager/refs/heads/main/apis.yml
tags:
- Disaster Recovery
- Enterprise Storage
- File Systems
- Storage
- Volume Management
url: https://www.veritas.com/support/en_US/volume-manager
use_cases: []
---
