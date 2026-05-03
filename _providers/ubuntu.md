---
api_count: 8
apis:
- description: REST API for Launchpad, Ubuntu's project hosting and collaboration platform.
  name: Launchpad API
  slug: ''
- description: API for managing Ubuntu Pro subscriptions and entitlements.
  name: Ubuntu Pro API
  slug: ''
- description: API for the Snap Store for publishing and managing snap packages.
  name: Snap Store API
  slug: ''
- description: Access to Ubuntu package repositories and archive information.
  name: Ubuntu Archive API
  slug: ''
- description: Systems management API for Ubuntu servers.
  name: Landscape API
  slug: ''
- description: Metal as a Service API for physical server provisioning.
  name: MAAS API
  slug: ''
- description: Application modeling and deployment API.
  name: Juju API
  slug: ''
- description: API for Ubuntu security notices and CVE information.
  name: Ubuntu CVE API
  slug: ''
common: []
created: '2024-01-15'
description: Collection of APIs and services provided by Canonical for Ubuntu and related products.
features: []
image: https://assets.ubuntu.com/v1/29985a98-ubuntu-logo32.png
integrations: []
layout: provider
modified: '2026-03-16'
name: Ubuntu
skills: []
slug: ubuntu
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Ubuntu\ndescription: >-\n  Collection of APIs and services provided by Canonical for Ubuntu and related products.\nimage: https://assets.ubuntu.com/v1/29985a98-ubuntu-logo32.png\nurl: https://ubuntu.com\ncreated: '2024-01-15'\nmodified: '2026-03-16'\napis:\n  - name: Launchpad API\n    description: >-\n      REST API for Launchpad, Ubuntu's project hosting and collaboration platform.\n    image: https://launchpad.net/@@/launchpad-logo\n    humanURL: https://launchpad.net/\n    baseURL: https://api.launchpad.net/\n    tags:\n      - Bugs\n      - Collaboration\n      - Distributions\n      - Packages\n      - Projects\n    properties:\n      - type: Documentation\n        url: https://launchpad.net/+apidoc/\n      - type: Authentication\n        url: https://help.launchpad.net/API/Uses\n      - type: Wadl\n        url: https://api.launchpad.net/devel\n    contact:\n      - type: Support\n        url: https://answers.launchpad.net/launchpad\n  - name: Ubuntu Pro API\n \
  \   description: >-\n      API for managing Ubuntu Pro subscriptions and entitlements.\n    humanURL: https://ubuntu.com/pro\n    baseURL: https://contracts.canonical.com/\n    tags:\n      - Enterprise\n      - Security\n      - Subscriptions\n      - Support\n    properties:\n      - type: Documentation\n        url: https://canonical-ubuntu-pro-client.readthedocs-hosted.com/\n      - type: Authentication\n        url: https://ubuntu.com/pro/dashboard\n    contact:\n      - type: Support\n        url: https://ubuntu.com/support\n  - name: Snap Store API\n    description: >-\n      API for the Snap Store for publishing and managing snap packages.\n    humanURL: https://snapcraft.io/\n    baseURL: https://api.snapcraft.io/\n    tags:\n      - Applications\n      - Distribution\n      - Packages\n      - Snaps\n    properties:\n      - type: Documentation\n        url: https://snapcraft.io/docs/snapcraft-store-api\n      - type: Dashboard\n        url: https://snapcraft.io/account\n   \
  \   - type: Developer Portal\n        url: https://snapcraft.io/docs\n    contact:\n      - type: Forum\n        url: https://forum.snapcraft.io/\n  - name: Ubuntu Archive API\n    description: >-\n      Access to Ubuntu package repositories and archive information.\n    humanURL: https://archive.ubuntu.com/\n    baseURL: https://api.launchpad.net/devel/ubuntu\n    tags:\n      - Archives\n      - Packages\n      - Releases\n      - Repositories\n    properties:\n      - type: Documentation\n        url: https://wiki.ubuntu.com/ArchiveAdministration\n      - type: Package Search\n        url: https://packages.ubuntu.com/\n  - name: Landscape API\n    description: >-\n      Systems management API for Ubuntu servers.\n    humanURL: https://ubuntu.com/landscape\n    baseURL: https://landscape.canonical.com/api/\n    tags:\n      - Automation\n      - Management\n      - Monitoring\n      - Servers\n    properties:\n      - type: Documentation\n        url: https://ubuntu.com/landscape/docs/api\n\
  \      - type: Authentication\n        url: https://ubuntu.com/landscape/docs/api-authentication\n    contact:\n      - type: Support\n        url: https://ubuntu.com/landscape/contact-us\n  - name: MAAS API\n    description: >-\n      Metal as a Service API for physical server provisioning.\n    humanURL: https://maas.io/\n    baseURL: https://maas.io/docs/api\n    tags:\n      - Bare-Metal\n      - Cloud\n      - Infrastructure\n      - Provisioning\n    properties:\n      - type: Documentation\n        url: https://maas.io/docs/api\n      - type: GitHub\n        url: https://github.com/canonical/maas\n    contact:\n      - type: Discourse\n        url: https://discourse.maas.io/\n  - name: Juju API\n    description: >-\n      Application modeling and deployment API.\n    humanURL: https://juju.is/\n    baseURL: wss://[controller-address]:17070/api\n    tags:\n      - Automation\n      - Deployment\n      - Devops\n      - Orchestration\n    properties:\n      - type: Documentation\n\
  \        url: https://juju.is/docs/juju/api\n      - type: GitHub\n        url: https://github.com/juju/juju\n    contact:\n      - type: Discourse\n        url: https://discourse.charmhub.io/\n  - name: Ubuntu CVE API\n    description: >-\n      API for Ubuntu security notices and CVE information.\n    humanURL: https://ubuntu.com/security/cves\n    baseURL: https://ubuntu.com/security/cves.json\n    tags:\n      - Cve\n      - Patches\n      - Security\n      - Vulnerabilities\n    properties:\n      - type: Documentation\n        url: https://ubuntu.com/security/api\n      - type: RSS\n        url: https://ubuntu.com/security/notices/rss.xml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Cloud\n  - Containers\n  - Devops\n  - Enterprise\n  - Linux\n  - Security\n  - Ubuntu\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/ubuntu/refs/heads/main/apis.yml
tags:
- Cloud
- Containers
- Devops
- Enterprise
- Linux
- Security
- Ubuntu
url: https://ubuntu.com
use_cases: []
---
