---
api_count: 2
api_specs:
- filename: netbox-openapi.yml
  format: yaml
  label: NetBox REST API
  slug: netbox-rest
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/netbox/refs/heads/main/openapi/netbox-openapi.yml
apis:
- description: A comprehensive REST API for programmatic access to all NetBox data and functionality. Supports full CRUD operations for all objects including devices, IP addresses, circuits, and more.
  name: NetBox REST API
  slug: netbox-rest
- description: A GraphQL API providing flexible querying capabilities for NetBox data with support for nested queries and custom field selection.
  name: NetBox GraphQL API
  slug: ''
common:
- title: ''
  type: GitHub Organization
  url: https://github.com/netbox-community
- title: ''
  type: Slack Community
  url: https://netdev.chat/
- title: ''
  type: Blog
  url: https://netbox.dev/blog/
- title: ''
  type: Getting Started
  url: https://docs.netbox.dev/en/stable/getting-started/
- title: ''
  type: Plugins
  url: https://netbox.dev/plugins/
- title: ''
  type: Demo Instance
  url: https://demo.netbox.dev/
created: '2024-01-15'
description: NetBox is the leading solution for modeling and documenting modern networks. By combining the traditional disciplines of IP address management (IPAM) and datacenter infrastructure management (DCIM) with powerful APIs and extensions, NetBox provides the ideal "source of truth" to power network automation.
features: []
image: https://netbox.dev/static/img/netbox-logo.svg
integrations: []
layout: provider
modified: '2026-04-28'
name: NetBox
skills: []
slug: netbox
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: netbox\nname: NetBox\ndescription: NetBox is the leading solution for modeling and documenting modern networks. By combining the traditional disciplines of IP address management (IPAM) and datacenter infrastructure management (DCIM) with powerful APIs and extensions, NetBox provides the ideal \"source of truth\" to power network automation.\nimage: https://netbox.dev/static/img/netbox-logo.svg\ncreated: '2024-01-15'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nurl: https://raw.githubusercontent.com/api-evangelist/netbox/refs/heads/main/apis.yml\napis:\n  - aid: netbox:netbox-rest\n    name: NetBox REST API\n    description: A comprehensive REST API for programmatic access to all NetBox data and functionality. Supports full CRUD operations for all objects including devices, IP addresses, circuits, and more.\n    image: https://netbox.dev/static/img/netbox-logo.svg\n    humanURL: https://docs.netbox.dev/en/stable/\n    baseURL: https://demo.netbox.dev/api\n   \
  \ tags:\n      - Automation\n      - DCIM\n      - Documentation\n      - Infrastructure\n      - IPAM\n      - Network Management\n    properties:\n      - type: Documentation\n        url: https://docs.netbox.dev/en/stable/integrations/rest-api/\n      - type: OpenAPI\n        url: https://raw.githubusercontent.com/api-evangelist/netbox/refs/heads/main/openapi/netbox-openapi.yml\n      - type: Authentication\n        url: https://docs.netbox.dev/en/stable/integrations/rest-api/#authentication\n    contact:\n      - type: Email\n        url: mailto:info@netbox.dev\n      - type: GitHub\n        url: https://github.com/netbox-community/netbox\n  - name: NetBox GraphQL API\n    description: A GraphQL API providing flexible querying capabilities for NetBox data with support for nested queries and custom field selection.\n    image: https://netbox.dev/static/img/netbox-logo.svg\n    humanURL: https://docs.netbox.dev/en/stable/integrations/graphql-api/\n    baseURL: https://demo.netbox.dev/graphql\n\
  \    tags:\n      - DCIM\n      - GraphQL\n      - IPAM\n      - Query Language\n    properties:\n      - type: Documentation\n        url: https://docs.netbox.dev/en/stable/integrations/graphql-api/\n      - type: GraphiQL Interface\n        url: https://demo.netbox.dev/graphql\ncommon:\n  - type: GitHub Organization\n    url: https://github.com/netbox-community\n  - type: Slack Community\n    url: https://netdev.chat/\n  - type: Blog\n    url: https://netbox.dev/blog/\n  - type: Getting Started\n    url: https://docs.netbox.dev/en/stable/getting-started/\n  - type: Plugins\n    url: https://netbox.dev/plugins/\n  - type: Demo Instance\n    url: https://demo.netbox.dev/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ntags:\n  - Data Center\n  - DCIM\n  - Infrastructure as Code\n  - IPAM\n  - Network Automation\n  - Network Management\n  - Open Source\n  - Source of Truth\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/netbox/refs/heads/main/apis.yml
tags:
- Data Center
- DCIM
- Infrastructure as Code
- IPAM
- Network Automation
- Network Management
- Open Source
- Source of Truth
url: https://raw.githubusercontent.com/api-evangelist/netbox/refs/heads/main/apis.yml
use_cases: []
---
