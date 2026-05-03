---
api_count: 2
api_specs:
- filename: vmware-tanzu-service-mesh-openapi.yml
  format: yaml
  label: VMware Tanzu Service Mesh API
  slug: tanzu-service-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/openapi/vmware-tanzu-service-mesh-openapi.yml
- filename: vmware-tanzu-kubernetes-grid-openapi.yml
  format: yaml
  label: VMware Tanzu Kubernetes Grid API
  slug: tanzu-kubernetes-grid-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/openapi/vmware-tanzu-kubernetes-grid-openapi.yml
apis:
- description: The Tanzu Service Mesh REST API provides programmatic access to manage clusters, global namespaces, resource groups, and service mesh policies. Authentication uses a CSP API token exchanged for a shor
  name: VMware Tanzu Service Mesh API
  slug: tanzu-service-mesh-api
- description: Kubernetes-native API for provisioning and managing Tanzu Kubernetes clusters using the TanzuKubernetesCluster CRD (v1alpha1/v1alpha2). Runs on vSphere Supervisor clusters via the Tanzu Kubernetes Gri
  name: VMware Tanzu Kubernetes Grid API
  slug: tanzu-kubernetes-grid-api
capabilities:
- description: Workflow capability for platform engineers managing VMware Tanzu Kubernetes infrastructure. Combines Tanzu Service Mesh management (cluster onboarding, global namespaces, resource groups) with Kuberne
  name: VMware Tanzu Kubernetes Platform Workflow
  slug: kubernetes-platform
common:
- title: ''
  type: Website
  url: https://tanzu.vmware.com/
- title: ''
  type: Documentation
  url: https://docs.vmware.com/en/VMware-Tanzu/index.html
- title: ''
  type: GitHub Organization
  url: https://github.com/vmware-tanzu
- title: ''
  type: Blog
  url: https://tanzu.vmware.com/content/blog
- title: ''
  type: Pricing
  url: https://tanzu.vmware.com/pricing
- title: ''
  type: Sign Up
  url: https://tanzu.vmware.com/try
- title: ''
  type: Broadcom TechDocs
  url: https://techdocs.broadcom.com/us/en/vmware-tanzu.html
- title: ''
  type: CLI
  url: https://github.com/vmware-tanzu/tanzu-cli
- title: ''
  type: Velero
  url: https://github.com/vmware-tanzu/velero
- title: ''
  type: Sonobuoy
  url: https://github.com/vmware-tanzu/sonobuoy
- title: ''
  type: Cartographer
  url: https://github.com/vmware-tanzu/cartographer
created: '2026-03-26'
description: VMware Tanzu (now part of Broadcom) is a portfolio of products for modernizing applications and infrastructure with a common approach to building, running, and managing Kubernetes across multi-cloud environments. Key APIs include the Tanzu Service Mesh REST API for cluster and global namespace management, Kubernetes CRD-based APIs for VM Operator, Projects Operator, and NSX Operator, and the Tanzu CLI plugin runtime.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 8
  name: Vmware Tanzu Context
  property_count: 25
  slug: vmware-tanzu-context
layout: provider
modified: '2026-05-03'
name: VMware Tanzu
rules:
- name: VMware Tanzu API Rules
  rule_count: 8
  severity_counts:
    error: 2
    hint: 0
    info: 0
    warn: 6
  slug: vmware-tanzu-rules
skills: []
slug: vmware-tanzu
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: vmware-tanzu\nname: VMware Tanzu\ndescription: >-\n  VMware Tanzu (now part of Broadcom) is a portfolio of products for\n  modernizing applications and infrastructure with a common approach to\n  building, running, and managing Kubernetes across multi-cloud environments.\n  Key APIs include the Tanzu Service Mesh REST API for cluster and global\n  namespace management, Kubernetes CRD-based APIs for VM Operator, Projects\n  Operator, and NSX Operator, and the Tanzu CLI plugin runtime.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Cloud Native\n  - Containers\n  - Enterprise\n  - Kubernetes\n  - Multi-Cloud\n  - Service Mesh\n  - VMware\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/apis.yml\ncreated: '2026-03-26'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: vmware-tanzu:tanzu-service-mesh-api\n    name: VMware Tanzu Service Mesh API\n    description:\
  \ >-\n      The Tanzu Service Mesh REST API provides programmatic access to manage\n      clusters, global namespaces, resource groups, and service mesh policies.\n      Authentication uses a CSP API token exchanged for a short-lived Bearer\n      token. The API version is embedded in the URL path (e.g. /v1alpha1/).\n    humanURL: https://docs.vmware.com/en/VMware-Tanzu-Service-Mesh/index.html\n    tags:\n      - Clusters\n      - Global Namespaces\n      - Kubernetes\n      - Resource Groups\n      - Service Mesh\n    properties:\n      - type: Documentation\n        url: https://docs.vmware.com/en/VMware-Tanzu-Service-Mesh/services/api-programming-guide/GUID-6C5044B8-6950-42A6-87A5-3D88BEAE09DB.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/openapi/vmware-tanzu-service-mesh-openapi.yml\n  - aid: vmware-tanzu:tanzu-kubernetes-grid-api\n    name: VMware Tanzu Kubernetes Grid API\n    description: >-\n\
  \      Kubernetes-native API for provisioning and managing Tanzu Kubernetes\n      clusters using the TanzuKubernetesCluster CRD (v1alpha1/v1alpha2).\n      Runs on vSphere Supervisor clusters via the Tanzu Kubernetes Grid Service.\n    humanURL: https://docs.vmware.com/en/VMware-vSphere/index.html\n    tags:\n      - Cluster Provisioning\n      - Kubernetes\n      - TKG\n      - vSphere\n    properties:\n      - type: Documentation\n        url: https://docs.vmware.com/en/VMware-vSphere/7.0/vmware-vsphere-with-tanzu/GUID-31BF8166-5FC8-4D43-933D-5797F3BE4A36.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/openapi/vmware-tanzu-kubernetes-grid-openapi.yml\n      - type: KubernetesCRD\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/crd/tanzukubernetescluster-crd.yaml\ncommon:\n  - type: Website\n    url: https://tanzu.vmware.com/\n  - type: Documentation\n\
  \    url: https://docs.vmware.com/en/VMware-Tanzu/index.html\n  - type: GitHub Organization\n    url: https://github.com/vmware-tanzu\n  - type: Blog\n    url: https://tanzu.vmware.com/content/blog\n  - type: Pricing\n    url: https://tanzu.vmware.com/pricing\n  - type: Sign Up\n    url: https://tanzu.vmware.com/try\n  - type: Broadcom TechDocs\n    url: https://techdocs.broadcom.com/us/en/vmware-tanzu.html\n  - type: CLI\n    url: https://github.com/vmware-tanzu/tanzu-cli\n  - type: Velero\n    url: https://github.com/vmware-tanzu/velero\n  - type: Sonobuoy\n    url: https://github.com/vmware-tanzu/sonobuoy\n  - type: Cartographer\n    url: https://github.com/vmware-tanzu/cartographer\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/apis.yml
tags:
- Cloud Native
- Containers
- Enterprise
- Kubernetes
- Multi-Cloud
- Service Mesh
- VMware
url: https://raw.githubusercontent.com/api-evangelist/vmware-tanzu/refs/heads/main/apis.yml
use_cases: []
---
