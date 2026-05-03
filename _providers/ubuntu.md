---
api_count: 8
api_specs:
- filename: ubuntu-launchpad-openapi.yml
  format: yaml
  label: Launchpad API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ubuntu/refs/heads/main/openapi/ubuntu-launchpad-openapi.yml
- filename: ubuntu-snap-store-openapi.yml
  format: yaml
  label: Snap Store API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ubuntu/refs/heads/main/openapi/ubuntu-snap-store-openapi.yml
- filename: ubuntu-cve-openapi.yml
  format: yaml
  label: Ubuntu CVE API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ubuntu/refs/heads/main/openapi/ubuntu-cve-openapi.yml
apis:
- description: REST API for Launchpad, Ubuntu's project hosting and collaboration platform. Provides access to people, projects, bugs, packages, branches, and distributions. Uses OAuth 1.0a authentication and WADL-d
  name: Launchpad API
  slug: ''
- description: API for managing Ubuntu Pro subscriptions and entitlements, including security patches, compliance tooling, and extended security maintenance.
  name: Ubuntu Pro API
  slug: ''
- description: API for the Snap Store for publishing and managing snap packages. Enables snap search, package info retrieval, refresh operations, category listings, and usage metrics for IoT and desktop deployments.
  name: Snap Store API
  slug: ''
- description: Access to Ubuntu package repositories and archive information via the Launchpad API's Ubuntu distribution endpoint.
  name: Ubuntu Archive API
  slug: ''
- description: Systems management API for Ubuntu servers enabling automated patch management, compliance reporting, and fleet monitoring for Ubuntu deployments.
  name: Landscape API
  slug: ''
- description: Metal as a Service API for physical server provisioning, enabling automated bare-metal infrastructure management and cloud-like workflows.
  name: MAAS API
  slug: ''
- description: Application modeling and deployment API supporting automated deployment, scaling, and management of applications across clouds and bare metal.
  name: Juju API
  slug: ''
- description: API for Ubuntu security notices and CVE vulnerability information, enabling programmatic queries of the Ubuntu CVE database including affected packages and patch status across Ubuntu releases.
  name: Ubuntu CVE API
  slug: ''
capabilities:
- description: Workflow capability combining the Snap Store API (package discovery and management) and Ubuntu Security CVE API (vulnerability intelligence). Supports DevOps engineers, system administrators, and secu
  name: Ubuntu Package and Security Management
  slug: package-and-security-management
common: []
created: '2024-01-15'
description: Collection of APIs and services provided by Canonical for Ubuntu and related products. Includes the Snap Store API for package management, Launchpad API for project hosting and bug tracking, Ubuntu Security CVE API for vulnerability intelligence, and enterprise services including Ubuntu Pro, MAAS, Juju, and Landscape.
features: []
image: https://assets.ubuntu.com/v1/29985a98-ubuntu-logo32.png
integrations: []
jsonld:
- class_count: 8
  name: Ubuntu Context
  property_count: 18
  slug: ubuntu-context
layout: provider
modified: '2026-05-03'
name: Ubuntu
rules:
- name: Ubuntu API Rules
  rule_count: 6
  severity_counts:
    error: 1
    hint: 0
    info: 0
    warn: 5
  slug: ubuntu-rules
skills: []
slug: ubuntu
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Ubuntu\ndescription: >-\n  Collection of APIs and services provided by Canonical for Ubuntu and related products.\n  Includes the Snap Store API for package management, Launchpad API for project hosting\n  and bug tracking, Ubuntu Security CVE API for vulnerability intelligence, and enterprise\n  services including Ubuntu Pro, MAAS, Juju, and Landscape.\nimage: https://assets.ubuntu.com/v1/29985a98-ubuntu-logo32.png\nurl: https://ubuntu.com\ncreated: '2024-01-15'\nmodified: '2026-05-03'\napis:\n  - name: Launchpad API\n    description: >-\n      REST API for Launchpad, Ubuntu's project hosting and collaboration platform.\n      Provides access to people, projects, bugs, packages, branches, and distributions.\n      Uses OAuth 1.0a authentication and WADL-described resources.\n    image: https://launchpad.net/@@/launchpad-logo\n    humanURL: https://launchpad.net/\n    baseURL: https://api.launchpad.net/1.0\n    tags:\n      - Bugs\n      - Collaboration\n      - Distributions\n\
  \      - Packages\n      - Projects\n      - Open Source\n    properties:\n      - type: Documentation\n        url: https://launchpad.net/+apidoc/\n      - type: Documentation\n        url: https://documentation.ubuntu.com/launchpad/user/explanation/launchpad-api/launchpad-web-service/\n      - type: Authentication\n        url: https://help.launchpad.net/API/Uses\n      - type: Wadl\n        url: https://api.launchpad.net/devel\n      - type: OpenAPI\n        url: openapi/ubuntu-launchpad-openapi.yml\n    contact:\n      - type: Support\n        url: https://answers.launchpad.net/launchpad\n\n  - name: Ubuntu Pro API\n    description: >-\n      API for managing Ubuntu Pro subscriptions and entitlements, including\n      security patches, compliance tooling, and extended security maintenance.\n    humanURL: https://ubuntu.com/pro\n    baseURL: https://contracts.canonical.com/\n    tags:\n      - Enterprise\n      - Security\n      - Subscriptions\n      - Support\n    properties:\n  \
  \    - type: Documentation\n        url: https://canonical-ubuntu-pro-client.readthedocs-hosted.com/\n      - type: Authentication\n        url: https://ubuntu.com/pro/dashboard\n    contact:\n      - type: Support\n        url: https://ubuntu.com/support\n\n  - name: Snap Store API\n    description: >-\n      API for the Snap Store for publishing and managing snap packages. Enables\n      snap search, package info retrieval, refresh operations, category listings,\n      and usage metrics for IoT and desktop deployments.\n    humanURL: https://snapcraft.io/\n    baseURL: https://api.snapcraft.io\n    tags:\n      - Applications\n      - Distribution\n      - Packages\n      - Snaps\n      - Package Management\n    properties:\n      - type: Documentation\n        url: https://snapcraft.io/docs/snapcraft-store-api\n      - type: Documentation\n        url: https://api.snapcraft.io/docs/\n      - type: Dashboard\n        url: https://snapcraft.io/account\n      - type: Developer Portal\n\
  \        url: https://snapcraft.io/docs\n      - type: OpenAPI\n        url: openapi/ubuntu-snap-store-openapi.yml\n      - type: Example\n        url: examples/ubuntu-snap-search-example.json\n      - type: JSONSchema\n        url: json-schema/ubuntu-snap-schema.json\n    contact:\n      - type: Forum\n        url: https://forum.snapcraft.io/\n\n  - name: Ubuntu Archive API\n    description: >-\n      Access to Ubuntu package repositories and archive information via\n      the Launchpad API's Ubuntu distribution endpoint.\n    humanURL: https://archive.ubuntu.com/\n    baseURL: https://api.launchpad.net/devel/ubuntu\n    tags:\n      - Archives\n      - Packages\n      - Releases\n      - Repositories\n    properties:\n      - type: Documentation\n        url: https://wiki.ubuntu.com/ArchiveAdministration\n      - type: Package Search\n        url: https://packages.ubuntu.com/\n\n  - name: Landscape API\n    description: >-\n      Systems management API for Ubuntu servers enabling automated\
  \ patch management,\n      compliance reporting, and fleet monitoring for Ubuntu deployments.\n    humanURL: https://ubuntu.com/landscape\n    baseURL: https://landscape.canonical.com/api/\n    tags:\n      - Automation\n      - Management\n      - Monitoring\n      - Servers\n    properties:\n      - type: Documentation\n        url: https://ubuntu.com/landscape/docs/api\n      - type: Authentication\n        url: https://ubuntu.com/landscape/docs/api-authentication\n    contact:\n      - type: Support\n        url: https://ubuntu.com/landscape/contact-us\n\n  - name: MAAS API\n    description: >-\n      Metal as a Service API for physical server provisioning, enabling\n      automated bare-metal infrastructure management and cloud-like workflows.\n    humanURL: https://maas.io/\n    baseURL: https://maas.io/docs/api\n    tags:\n      - Bare-Metal\n      - Cloud\n      - Infrastructure\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://maas.io/docs/api\n\
  \      - type: GitHub\n        url: https://github.com/canonical/maas\n    contact:\n      - type: Discourse\n        url: https://discourse.maas.io/\n\n  - name: Juju API\n    description: >-\n      Application modeling and deployment API supporting automated deployment,\n      scaling, and management of applications across clouds and bare metal.\n    humanURL: https://juju.is/\n    baseURL: wss://[controller-address]:17070/api\n    tags:\n      - Automation\n      - Deployment\n      - Devops\n      - Orchestration\n    properties:\n      - type: Documentation\n        url: https://juju.is/docs/juju/api\n      - type: GitHub\n        url: https://github.com/juju/juju\n    contact:\n      - type: Discourse\n        url: https://discourse.charmhub.io/\n\n  - name: Ubuntu CVE API\n    description: >-\n      API for Ubuntu security notices and CVE vulnerability information,\n      enabling programmatic queries of the Ubuntu CVE database including\n      affected packages and patch status\
  \ across Ubuntu releases.\n    humanURL: https://ubuntu.com/security/cves\n    baseURL: https://ubuntu.com/security\n    tags:\n      - Cve\n      - Patches\n      - Security\n      - Vulnerabilities\n    properties:\n      - type: Documentation\n        url: https://ubuntu.com/security/api\n      - type: RSS\n        url: https://ubuntu.com/security/notices/rss.xml\n      - type: OpenAPI\n        url: openapi/ubuntu-cve-openapi.yml\n      - type: Example\n        url: examples/ubuntu-cve-list-example.json\n      - type: JSONSchema\n        url: json-schema/ubuntu-cve-schema.json\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Cloud\n  - Containers\n  - Devops\n  - Enterprise\n  - Linux\n  - Security\n  - Ubuntu\n  - Package Management\n  - Open Source\nproperties:\n  - url: rules/ubuntu-rules.yml\n    type: SpectralRules\n  - url: vocabulary/ubuntu-vocabulary.yml\n    type: Vocabulary\n  - url: json-ld/ubuntu-context.jsonld\n    type: JSONLDContext\n  -\
  \ url: capabilities/package-and-security-management.yaml\n    type: NaftikoCapabilities\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ubuntu/refs/heads/main/apis.yml
tags:
- Cloud
- Containers
- Devops
- Enterprise
- Linux
- Security
- Ubuntu
- Package Management
- Open Source
url: https://ubuntu.com
use_cases: []
---
