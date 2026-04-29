---
api_count: 9
apis:
- description: The public Snap Store Device API (api.snapcraft.io) serves information about snaps, revisions, channels, tracks, assertions, and refresh state to snap clients. The Snapcraft Dashboard API (dashboard.s
  name: Snap Store API
  slug: snap-store-api
- description: Developer-facing REST API for Charmhub, Canonical's marketplace for charms (Kubernetes and machine operators). Supports charm discovery, publishing, release channels, and token exchange — macaroons is
  name: Charmhub API
  slug: charmhub-api
- description: The local REST API exposed by snapd over a Unix domain socket on every Ubuntu system running snaps. Enables local clients and tools to query snap state, install / refresh / remove snaps, manage interf
  name: snapd REST API
  slug: snapd-rest-api
- description: The REST API exposed by LXD, Canonical's system-container and VM manager. All client–daemon communication happens over HTTPS (remote) or a Unix socket (local). Provides endpoints for instances, images
  name: LXD REST API
  slug: lxd-api
- description: The RESTful API for MAAS (Metal as a Service). Everything the MAAS UI can do — commissioning, allocation, deployment, DHCP/DNS, tags, zones, pools, users, machines — is available through the API, maki
  name: MAAS API
  slug: maas-api
- description: Juju is Canonical's open-source orchestration engine for deploying, integrating, scaling, and managing applications on clouds, MAAS, LXD, and Kubernetes via charms. Juju clients communicate with a con
  name: Juju Client / Controller API
  slug: juju-api
- description: Launchpad exposes a RESTful Web Services API over its project hosting, bug tracking, code, builds, translations, and distribution data. The API is authenticated with OAuth; anonymous access gives read
  name: Launchpad Web Services API
  slug: launchpad-api
- description: The Ubuntu Pro client exposes a local API/CLI for managing Ubuntu Pro subscription services on a host — enabling, disabling, and inspecting Extended Security Maintenance (ESM), Livepatch, FIPS, compli
  name: Ubuntu Pro Client API
  slug: ubuntu-pro-api
- description: Canonical Landscape is the systems-management platform for Ubuntu at scale. Its API lets operators manage and automate inventories, upgrades, patch compliance, reboots, scripts, monitoring, and alerts
  name: Landscape API
  slug: landscape-api
common:
- title: ''
  type: Website
  url: https://canonical.com/
- title: ''
  type: UbuntuWebsite
  url: https://ubuntu.com/
- title: ''
  type: Documentation
  url: https://documentation.ubuntu.com/
- title: ''
  type: GitHubOrg
  url: https://github.com/canonical
- title: ''
  type: SnapStore
  url: https://snapcraft.io/
- title: ''
  type: Charmhub
  url: https://charmhub.io/
- title: ''
  type: Launchpad
  url: https://launchpad.net/
- title: ''
  type: DiscourseForum
  url: https://discourse.ubuntu.com/
- title: ''
  type: DataPrivacy
  url: https://ubuntu.com/legal/data-privacy
- title: ''
  type: TermsOfService
  url: https://ubuntu.com/legal/terms
created: '2026-03-16'
description: Canonical is the company behind Ubuntu, the world's most popular open source operating system for cloud, servers, desktops, IoT, and Kubernetes. Canonical publishes a broad set of developer APIs spanning the Ubuntu and Canonical ecosystem — the Snap Store and Snapcraft, the Charmhub charm marketplace, LXD system containers, MAAS bare-metal provisioning, Juju orchestration, Launchpad project hosting, Ubuntu Pro subscription services, and Landscape systems management — most of which are RESTful, open, and well documented.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Canonical
skills: []
slug: canonical
solutions: []
source_yaml: "aid: canonical\nname: Canonical\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/canonical/refs/heads/main/apis.yml\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\ntags:\n  - Cloud\n  - Linux\n  - Open Source\n  - Ubuntu\n  - Containers\n  - Bare Metal\n  - Charms\n  - Identity\naccess: Open\ncreated: '2026-03-16'\nmodified: '2026-04-23'\nposition: Provider\nspecificationVersion: '0.19'\ndescription: >-\n  Canonical is the company behind Ubuntu, the world's most popular open\n  source operating system for cloud, servers, desktops, IoT, and Kubernetes.\n  Canonical publishes a broad set of developer APIs spanning the Ubuntu and\n  Canonical ecosystem — the Snap Store and Snapcraft, the Charmhub charm\n  marketplace, LXD system containers, MAAS bare-metal provisioning, Juju\n  orchestration, Launchpad project hosting, Ubuntu Pro subscription\n  services, and Landscape systems management — most of which are RESTful,\n\
  \  open, and well documented.\napis:\n  - aid: canonical:snap-store-api\n    name: Snap Store API\n    description: >-\n      The public Snap Store Device API (api.snapcraft.io) serves information\n      about snaps, revisions, channels, tracks, assertions, and refresh\n      state to snap clients. The Snapcraft Dashboard API\n      (dashboard.snapcraft.io) lets snap publishers manage releases, brand\n      stores, and snap metadata programmatically.\n    humanURL: https://api.snapcraft.io/docs/\n    baseURL: https://api.snapcraft.io\n    tags:\n      - Snaps\n      - Store\n      - Packaging\n    properties:\n      - type: Documentation\n        url: https://api.snapcraft.io/docs/\n      - type: DashboardAPI\n        url: https://dashboard.snapcraft.io/docs/reference/v2/en/index.html\n      - type: HowTo\n        url: https://snapcraft.io/docs/using-the-api\n  - aid: canonical:charmhub-api\n    name: Charmhub API\n    description: >-\n      Developer-facing REST API for Charmhub, Canonical's\
  \ marketplace for\n      charms (Kubernetes and machine operators). Supports charm discovery,\n      publishing, release channels, and token exchange — macaroons issued\n      by dashboard.snapcraft.io SSO are exchanged for Charmhub developer\n      tokens used in the Authorization header.\n    humanURL: https://api.charmhub.io/docs/default.html\n    baseURL: https://api.charmhub.io\n    tags:\n      - Charms\n      - Operators\n      - Kubernetes\n    properties:\n      - type: Documentation\n        url: https://api.charmhub.io/docs/default.html\n      - type: Portal\n        url: https://charmhub.io/\n  - aid: canonical:snapd-rest-api\n    name: snapd REST API\n    description: >-\n      The local REST API exposed by snapd over a Unix domain socket on every\n      Ubuntu system running snaps. Enables local clients and tools to query\n      snap state, install / refresh / remove snaps, manage interfaces and\n      connections, and read system information.\n    humanURL: https://snapcraft.io/docs/reference/development/snapd-rest-api/\n\
  \    tags:\n      - Local\n      - System\n      - Snaps\n    properties:\n      - type: Documentation\n        url: https://snapcraft.io/docs/reference/development/snapd-rest-api/\n      - type: HowTo\n        url: https://snapcraft.io/docs/how-to-guides/snap-development/use-the-rest-api/\n  - aid: canonical:lxd-api\n    name: LXD REST API\n    description: >-\n      The REST API exposed by LXD, Canonical's system-container and VM\n      manager. All client–daemon communication happens over HTTPS (remote)\n      or a Unix socket (local). Provides endpoints for instances, images,\n      networks, storage pools, profiles, projects, cluster members, and\n      events. Fully documented in an auto-generated OpenAPI (Swagger) spec.\n    humanURL: https://documentation.ubuntu.com/lxd/latest/rest-api/\n    baseURL: https://<host>:8443/1.0\n    tags:\n      - Containers\n      - Virtualisation\n      - OpenAPI\n    properties:\n      - type: Documentation\n        url: https://documentation.ubuntu.com/lxd/latest/rest-api/\n\
  \      - type: OpenAPI\n        url: https://github.com/canonical/lxd/blob/main/doc/rest-api.yaml\n      - type: Reference\n        url: https://linuxcontainers.org/lxd/rest-api/\n  - aid: canonical:maas-api\n    name: MAAS API\n    description: >-\n      The RESTful API for MAAS (Metal as a Service). Everything the MAAS UI\n      can do — commissioning, allocation, deployment, DHCP/DNS, tags, zones,\n      pools, users, machines — is available through the API, making bare-\n      metal infrastructure programmable and suitable for Infrastructure as\n      Code workflows. Python and CLI bindings are provided.\n    humanURL: https://canonical.com/maas/docs/api\n    baseURL: https://<maas-host>/MAAS/api/2.0\n    tags:\n      - Bare Metal\n      - Provisioning\n      - Infrastructure\n    properties:\n      - type: Documentation\n        url: https://canonical.com/maas/docs/api\n      - type: Overview\n        url: https://canonical.com/maas\n      - type: Portal\n        url: https://maas.io/docs\n\
  \  - aid: canonical:juju-api\n    name: Juju Client / Controller API\n    description: >-\n      Juju is Canonical's open-source orchestration engine for deploying,\n      integrating, scaling, and managing applications on clouds, MAAS, LXD,\n      and Kubernetes via charms. Juju clients communicate with a controller\n      over a websocket-based API; Python and Go libraries plus the juju CLI\n      consume this API.\n    humanURL: https://documentation.ubuntu.com/juju/\n    tags:\n      - Orchestration\n      - DevOps\n      - Charms\n    properties:\n      - type: Documentation\n        url: https://documentation.ubuntu.com/juju/\n      - type: Overview\n        url: https://canonical.com/juju\n      - type: Architecture\n        url: https://canonical.com/juju/juju-architecture\n  - aid: canonical:launchpad-api\n    name: Launchpad Web Services API\n    description: >-\n      Launchpad exposes a RESTful Web Services API over its project hosting,\n      bug tracking, code, builds, translations,\
  \ and distribution data. The\n      API is authenticated with OAuth; anonymous access gives read-only\n      access to public data. The launchpadlib Python library is the\n      officially supported client.\n    humanURL: https://documentation.ubuntu.com/launchpad/user/how-to/launchpad-api/\n    baseURL: https://api.launchpad.net/\n    tags:\n      - OAuth\n      - Open Source\n      - Project Hosting\n    properties:\n      - type: Documentation\n        url: https://documentation.ubuntu.com/launchpad/user/how-to/launchpad-api/\n      - type: Reference\n        url: https://help.launchpad.net/API\n      - type: ClientLibrary\n        url: https://launchpadlib.readthedocs.io/en/latest/introduction.html\n      - type: Portal\n        url: https://api.launchpad.net/\n  - aid: canonical:ubuntu-pro-api\n    name: Ubuntu Pro Client API\n    description: >-\n      The Ubuntu Pro client exposes a local API/CLI for managing Ubuntu Pro\n      subscription services on a host — enabling, disabling,\
  \ and inspecting\n      Extended Security Maintenance (ESM), Livepatch, FIPS, compliance\n      tooling (CIS, DISA-STIG), USG, and Landscape integration.\n    humanURL: https://documentation.ubuntu.com/pro/\n    tags:\n      - ESM\n      - Livepatch\n      - FIPS\n      - Compliance\n      - Subscription\n    properties:\n      - type: Documentation\n        url: https://documentation.ubuntu.com/pro/\n      - type: ClientDocs\n        url: https://documentation.ubuntu.com/pro-client/en/latest/\n      - type: Portal\n        url: https://ubuntu.com/pro\n  - aid: canonical:landscape-api\n    name: Landscape API\n    description: >-\n      Canonical Landscape is the systems-management platform for Ubuntu at\n      scale. Its API lets operators manage and automate inventories,\n      upgrades, patch compliance, reboots, scripts, monitoring, and alerts\n      across fleets of Ubuntu machines (on-prem, hybrid, or hosted\n      Landscape SaaS).\n    humanURL: https://ubuntu.com/landscape/docs\n\
  \    tags:\n      - Systems Management\n      - Patch Management\n      - Fleet\n    properties:\n      - type: Documentation\n        url: https://ubuntu.com/landscape/docs\n      - type: Portal\n        url: https://ubuntu.com/landscape\ncommon:\n  - type: Website\n    url: https://canonical.com/\n  - type: UbuntuWebsite\n    url: https://ubuntu.com/\n  - type: Documentation\n    url: https://documentation.ubuntu.com/\n  - type: GitHubOrg\n    url: https://github.com/canonical\n  - type: SnapStore\n    url: https://snapcraft.io/\n  - type: Charmhub\n    url: https://charmhub.io/\n  - type: Launchpad\n    url: https://launchpad.net/\n  - type: DiscourseForum\n    url: https://discourse.ubuntu.com/\n  - type: DataPrivacy\n    url: https://ubuntu.com/legal/data-privacy\n  - type: TermsOfService\n    url: https://ubuntu.com/legal/terms\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/canonical/refs/heads/main/apis.yml
tags:
- Cloud
- Linux
- Open Source
- Ubuntu
- Containers
- Bare Metal
- Charms
- Identity
url: https://raw.githubusercontent.com/api-evangelist/canonical/refs/heads/main/apis.yml
use_cases: []
---
