---
api_count: 1
apis:
- description: Runway is American Airlines' developer experience platform providing APIs for flight operations, booking, scheduling, and travel services. Built on Spotify's Backstage platform, Runway serves as the c
  name: American Airlines Runway Developer API
  slug: runway-developer-api
capabilities:
- description: Unified workflow for travel applications and agents accessing American Airlines flight data, status, and booking capabilities. Serves travel technology teams and booking platform developers.
  name: American Airlines Flight Operations
  slug: flight-operations
common:
- title: ''
  type: Website
  url: https://www.aa.com/
- title: ''
  type: DeveloperPortal
  url: https://developer.aa.com/
- title: ''
  type: GitHubOrganization
  url: https://github.com/AmericanAirlines
- title: ''
  type: Blog
  url: https://tech.aa.com/
- title: ''
  type: GitHubRepository
  url: https://github.com/AmericanAirlines/backstage
- title: Flight Engine Mock API
  type: Tools
  url: https://github.com/AmericanAirlines/Flight-Engine
- title: Hangar Hackathon Tool
  type: Tools
  url: https://github.com/AmericanAirlines/Hangar
created: '2026-04-19'
description: American Airlines is one of the world's largest airlines, operating an extensive domestic and international route network. The company's Runway developer experience platform, built on Spotify's Backstage, provides internal developer tooling and API management for engineering teams. American Airlines exposes flight data, status, and booking capabilities through its developer portal, and maintains an active open-source presence via the AmericanAirlines GitHub organization.
features:
- description: Internal developer platform built on Spotify's Backstage providing centralized API management, service catalog, and self-service infrastructure tooling for engineering teams.
  name: Runway Developer Experience Platform
- description: APIs for querying flight schedules, routes, status information, and operational data across American Airlines' domestic and international network.
  name: Flight Data APIs
- description: APIs supporting flight search, booking, reservation management, and passenger services integration for travel applications.
  name: Booking and Reservation APIs
- description: Runway provides integrated API management with security, authentication toggles, and corporate authentication capabilities for development teams.
  name: Built-In API Management
- description: Kong-based service mesh enabling reliable microservices communication and traffic management across the American Airlines platform.
  name: Service Mesh Integration
- description: American Airlines maintains open-source tools including Flight Engine (mock flight data API), Hangar (hackathon management), and Backstage plugins via the AmericanAirlines GitHub organization.
  name: Open Source Tooling
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Runway developer portal is built on Spotify's Backstage platform for internal developer experience and service catalog management.
  name: Spotify Backstage
- description: American Airlines uses Kong's Kuma service mesh for microservices networking and API gateway capabilities.
  name: Kong Service Mesh
- description: Integration with HashiCorp Vault for secrets management in build pipelines via open-source vault-action GitHub Action.
  name: HashiCorp Vault
- description: Python API client for Dynatrace integration maintained in the AmericanAirlines GitHub organization.
  name: Dynatrace
jsonld:
- class_count: 5
  name: American Airlines Runway Context
  property_count: 12
  slug: american-airlines-runway-context
layout: provider
modified: '2026-04-19'
name: American Airlines
rules:
- name: American Airlines API Rules
  rule_count: 12
  severity_counts:
    error: 8
    hint: 0
    info: 1
    warn: 3
  slug: american-airlines-spectral-rules
skills: []
slug: american-airlines
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: american-airlines\nname: American Airlines\ndescription: >-\n  American Airlines is one of the world's largest airlines, operating an\n  extensive domestic and international route network. The company's Runway\n  developer experience platform, built on Spotify's Backstage, provides\n  internal developer tooling and API management for engineering teams.\n  American Airlines exposes flight data, status, and booking capabilities\n  through its developer portal, and maintains an active open-source presence\n  via the AmericanAirlines GitHub organization.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Airlines\n  - Aviation\n  - Flights\n  - Travel\n  - Booking\n  - Developer Experience\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/american-airlines/refs/heads/main/apis.yml\ncreated: '2026-04-19'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n  - aid: american-airlines:runway-developer-api\n\
  \    name: American Airlines Runway Developer API\n    description: >-\n      Runway is American Airlines' developer experience platform providing APIs\n      for flight operations, booking, scheduling, and travel services. Built on\n      Spotify's Backstage platform, Runway serves as the central hub for\n      American Airlines API integrations with built-in API management, security,\n      and authentication capabilities. Teams can deploy running apps with public\n      ingress in under six minutes.\n    humanURL: https://developer.aa.com/\n    baseURL: https://developer.aa.com/api\n    tags:\n      - Airlines\n      - Aviation\n      - Flights\n      - Travel\n      - Booking\n    properties:\n      - type: Documentation\n        url: https://developer.aa.com/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-evangelist/american-airlines/refs/heads/main/openapi/american-airlines-runway-developer-api-openapi.yml\n\ncommon:\n  - type: Website\n\
  \    url: https://www.aa.com/\n  - type: DeveloperPortal\n    url: https://developer.aa.com/\n  - type: GitHubOrganization\n    url: https://github.com/AmericanAirlines\n  - type: Blog\n    url: https://tech.aa.com/\n  - type: GitHubRepository\n    url: https://github.com/AmericanAirlines/backstage\n  - type: Tools\n    url: https://github.com/AmericanAirlines/Flight-Engine\n    title: Flight Engine Mock API\n  - type: Tools\n    url: https://github.com/AmericanAirlines/Hangar\n    title: Hangar Hackathon Tool\n  - type: Features\n    data:\n      - name: Runway Developer Experience Platform\n        description: >-\n          Internal developer platform built on Spotify's Backstage providing\n          centralized API management, service catalog, and self-service\n          infrastructure tooling for engineering teams.\n      - name: Flight Data APIs\n        description: >-\n          APIs for querying flight schedules, routes, status information, and\n          operational data across\
  \ American Airlines' domestic and international\n          network.\n      - name: Booking and Reservation APIs\n        description: >-\n          APIs supporting flight search, booking, reservation management, and\n          passenger services integration for travel applications.\n      - name: Built-In API Management\n        description: >-\n          Runway provides integrated API management with security, authentication\n          toggles, and corporate authentication capabilities for development teams.\n      - name: Service Mesh Integration\n        description: >-\n          Kong-based service mesh enabling reliable microservices communication\n          and traffic management across the American Airlines platform.\n      - name: Open Source Tooling\n        description: >-\n          American Airlines maintains open-source tools including Flight Engine\n          (mock flight data API), Hangar (hackathon management), and Backstage\n          plugins via the AmericanAirlines GitHub\
  \ organization.\n  - type: UseCases\n    data:\n      - name: Flight Search and Booking\n        description: >-\n          Travel agencies and booking platforms integrate flight availability,\n          pricing, and reservation APIs to offer American Airlines flights.\n      - name: Flight Status Tracking\n        description: >-\n          Applications query real-time flight status, departure, arrival, and\n          delay information for American Airlines flights.\n      - name: Internal Developer Tooling\n        description: >-\n          American Airlines engineering teams use Runway to self-service\n          infrastructure, register APIs in the service catalog, and manage\n          deployments.\n      - name: Hackathon and Innovation\n        description: >-\n          Open-source Hangar tool enables hackathon management for tech\n          innovation events sponsored by or affiliated with American Airlines.\n  - type: Integrations\n    data:\n      - name: Spotify Backstage\n\
  \        description: >-\n          Runway developer portal is built on Spotify's Backstage platform for\n          internal developer experience and service catalog management.\n      - name: Kong Service Mesh\n        description: >-\n          American Airlines uses Kong's Kuma service mesh for microservices\n          networking and API gateway capabilities.\n      - name: HashiCorp Vault\n        description: >-\n          Integration with HashiCorp Vault for secrets management in build\n          pipelines via open-source vault-action GitHub Action.\n      - name: Dynatrace\n        description: >-\n          Python API client for Dynatrace integration maintained in the\n          AmericanAirlines GitHub organization.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/american-airlines/refs/heads/main/apis.yml
tags:
- Airlines
- Aviation
- Flights
- Travel
- Booking
- Developer Experience
url: https://raw.githubusercontent.com/api-evangelist/american-airlines/refs/heads/main/apis.yml
use_cases:
- description: Travel agencies and booking platforms integrate flight availability, pricing, and reservation APIs to offer American Airlines flights.
  name: Flight Search and Booking
- description: Applications query real-time flight status, departure, arrival, and delay information for American Airlines flights.
  name: Flight Status Tracking
- description: American Airlines engineering teams use Runway to self-service infrastructure, register APIs in the service catalog, and manage deployments.
  name: Internal Developer Tooling
- description: Open-source Hangar tool enables hackathon management for tech innovation events sponsored by or affiliated with American Airlines.
  name: Hackathon and Innovation
---
