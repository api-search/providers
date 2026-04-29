---
api_count: 3
api_specs:
- filename: broadcom-vsphere-automation-openapi.yml
  format: yaml
  label: Broadcom vSphere Automation API
  slug: vsphere-automation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/openapi/broadcom-vsphere-automation-openapi.yml
- filename: broadcom-operations-for-applications-openapi.yml
  format: yaml
  label: Broadcom Operations for Applications REST API
  slug: operations-for-applications
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/openapi/broadcom-operations-for-applications-openapi.yml
- filename: broadcom-vmware-cloud-foundation-openapi.yml
  format: yaml
  label: Broadcom VMware Cloud Foundation API
  slug: vmware-cloud-foundation
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/openapi/broadcom-vmware-cloud-foundation-openapi.yml
apis:
- description: The vSphere Automation API provides a unified programmatic interface for managing VMware vSphere environments. It enables automation of virtual machine lifecycle management, host and cluster configura
  name: Broadcom vSphere Automation API
  slug: vsphere-automation
- description: The VMware Aria Operations for Applications REST API (formerly Tanzu Observability by Wavefront) enables programmatic interaction with the observability service. It supports querying metrics, managing
  name: Broadcom Operations for Applications REST API
  slug: operations-for-applications
- description: The VMware Cloud Foundation API provides RESTful endpoints for managing SDDC (Software-Defined Data Center) infrastructure through the SDDC Manager. It enables automation of host commissioning, cluste
  name: Broadcom VMware Cloud Foundation API
  slug: vmware-cloud-foundation
common: []
created: '2025-01-14'
description: Broadcom is a global technology company that specializes in the design and manufacturing of semiconductors and other hardware components for a wide range of industries. They provide a diverse portfolio of products for the enterprise, data center, networking, telecommunications, and consumer electronics markets. Broadcom's technology is used in a variety of devices such as smartphones, tablets, routers, and smart TVs.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Broadcom Context
  property_count: 18
  slug: broadcom-context
layout: provider
modified: '2026-03-14'
name: Broadcom
skills: []
slug: broadcom
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: broadcom\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/apis.yml\napis:\n  - aid: broadcom:vsphere-automation\n    name: Broadcom vSphere Automation API\n    tags:\n      - Data Center\n      - Infrastructure\n      - Virtualization\n    humanURL: https://developer.broadcom.com/xapis/vsphere-automation-api/latest/\n    properties:\n      - url: https://developer.broadcom.com/xapis/vsphere-automation-api/latest/\n        type: Documentation\n      - url: openapi/broadcom-vsphere-automation-openapi.yml\n        type: OpenAPI\n      - url: json-schema/broadcom-virtual-machine-schema.json\n        type: JSONSchema\n      - url: json-schema/broadcom-host-schema.json\n        type: JSONSchema\n      - url: json-schema/broadcom-cluster-schema.json\n        type: JSONSchema\n      - url: json-ld/broadcom-context.jsonld\n        type: JSONLD\n    description: >-\n      The vSphere Automation API provides a unified programmatic interface for\n\
  \      managing VMware vSphere environments. It enables automation of virtual\n      machine lifecycle management, host and cluster configuration, content\n      library management, tagging, and other vSphere infrastructure operations.\n  - aid: broadcom:operations-for-applications\n    name: Broadcom Operations for Applications REST API\n    tags:\n      - Metrics\n      - Monitoring\n      - Observability\n    humanURL: https://developer.broadcom.com/xapis/operations-for-applications-rest-api/latest/\n    properties:\n      - url: https://developer.broadcom.com/xapis/operations-for-applications-rest-api/latest/\n        type: Documentation\n      - url: openapi/broadcom-operations-for-applications-openapi.yml\n        type: OpenAPI\n      - url: json-schema/broadcom-dashboard-schema.json\n        type: JSONSchema\n      - url: json-schema/broadcom-alert-schema.json\n        type: JSONSchema\n      - url: json-ld/broadcom-context.jsonld\n        type: JSONLD\n    description: >-\n   \
  \   The VMware Aria Operations for Applications REST API (formerly Tanzu\n      Observability by Wavefront) enables programmatic interaction with the\n      observability service. It supports querying metrics, managing dashboards,\n      alerts, events, sources, user accounts, API tokens, and ingesting data\n      directly.\n  - aid: broadcom:vmware-cloud-foundation\n    name: Broadcom VMware Cloud Foundation API\n    tags:\n      - Cloud Infrastructure\n      - Data Center\n      - SDDC\n    humanURL: https://developer.broadcom.com/xapis/sddc-manager-api/latest/\n    properties:\n      - url: https://developer.broadcom.com/xapis/sddc-manager-api/latest/\n        type: Documentation\n      - url: openapi/broadcom-vmware-cloud-foundation-openapi.yml\n        type: OpenAPI\n      - url: json-schema/broadcom-workload-domain-schema.json\n        type: JSONSchema\n      - url: json-schema/broadcom-task-schema.json\n        type: JSONSchema\n      - url: json-ld/broadcom-context.jsonld\n   \
  \     type: JSONLD\n    description: >-\n      The VMware Cloud Foundation API provides RESTful endpoints for managing\n      SDDC (Software-Defined Data Center) infrastructure through the SDDC\n      Manager. It enables automation of host commissioning, cluster management,\n      workload domain lifecycle, network pool configuration, task monitoring,\n      and VCF management component deployments.\nname: Broadcom\ntags:\n  - Cloud Infrastructure\n  - Gateways\n  - Management\n  - Networks\n  - Observability\n  - Virtualization\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2025-01-14'\nmodified: '2026-03-14'\nposition: Consumer\ndescription: >-\n  Broadcom is a global technology company that specializes in the design and manufacturing\n  of semiconductors and other hardware components for a wide range of industries.\n  They provide a diverse portfolio of products for the enterprise, data center, networking,\n\
  \  telecommunications, and consumer electronics markets. Broadcom's technology is used\n  in a variety of devices such as smartphones, tablets, routers, and smart TVs.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/apis.yml
tags:
- Cloud Infrastructure
- Gateways
- Management
- Networks
- Observability
- Virtualization
url: https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/apis.yml
use_cases: []
---
