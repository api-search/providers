---
api_count: 1
apis:
- description: 'U-Haul provides do-it-yourself moving and storage services including truck and trailer rentals, self-storage, moving supplies, and U-Box portable storage containers. Partners access dealer management '
  name: U-Haul
  slug: uhaul
common:
- title: ''
  type: Website
  url: https://www.amerco.com/
- title: ''
  type: Website
  url: https://www.uhaul.com/
- title: ''
  type: Portal
  url: https://www.uhaul.com/Dealer/
created: '2026-03-23'
description: AMERCO, operating as U-Haul Holding Company, is America's largest do-it-yourself moving and storage company. The company provides truck and trailer rentals, self-storage facilities, moving supplies, and portable moving and storage containers through its U-Haul brand. AMERCO operates the Moving Help marketplace connecting consumers to moving service providers, the U-Haul Self-Storage Affiliate Network, and WebSelfStorage management software for independent storage facilities. It also operates AMERITAS Life Insurance and Oxford Life Insurance subsidiaries.
features:
- description: Nationwide network of U-Haul trucks and trailers available through dealer locations with online booking and 24/7 customer support.
  name: Truck and Trailer Rental Network
- description: U-Haul owned and affiliate self-storage facilities with online reservation management and climate-controlled options.
  name: Self-Storage Facilities
- description: Online marketplace connecting consumers to independent moving service providers for loading, unloading, packing, and cleaning services.
  name: Moving Help Marketplace
- description: Partner network for independent self-storage facilities to list inventory and accept reservations through uhaul.com with WebSelfStorage management software.
  name: U-Haul Self-Storage Affiliate Network
- description: Self-storage management application providing reservation management, tenant tracking, payment processing, and reporting for independent storage facilities.
  name: WebSelfStorage Management Software
- description: Portable moving and storage container service with pickup, transport, and delivery options for local and long-distance moves.
  name: U-Box Portable Storage
- description: No-investment dealer program for small businesses to add U-Haul truck and trailer rental to existing product offerings with 21% average commission and weekly direct deposit payments.
  name: Dealer Program
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Platform integration connecting consumers to independent moving service providers nationwide through uhaul.com.
  name: Moving Help Marketplace
- description: AMERCO subsidiary providing life insurance products as part of the broader AMERCO financial services portfolio.
  name: AMERITAS Life Insurance
layout: provider
modified: '2026-04-19'
name: AMERCO
skills: []
slug: amerco
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: amerco\nname: AMERCO\ndescription: >-\n  AMERCO, operating as U-Haul Holding Company, is America's largest do-it-yourself\n  moving and storage company. The company provides truck and trailer rentals,\n  self-storage facilities, moving supplies, and portable moving and storage\n  containers through its U-Haul brand. AMERCO operates the Moving Help marketplace\n  connecting consumers to moving service providers, the U-Haul Self-Storage\n  Affiliate Network, and WebSelfStorage management software for independent\n  storage facilities. It also operates AMERITAS Life Insurance and Oxford Life\n  Insurance subsidiaries.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Moving\n  - Storage\n  - Truck Rental\n  - Logistics\n  - Consumer Services\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/amerco/refs/heads/main/apis.yml\ncreated: '2026-03-23'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: amerco:uhaul\n    name: U-Haul\n    description: >-\n      U-Haul provides do-it-yourself moving and storage services including truck\n      and trailer rentals, self-storage, moving supplies, and U-Box portable\n      storage containers. Partners access dealer management tools via the U-Haul\n      dealer portal and self-storage affiliates use WebSelfStorage management\n      software.\n    humanURL: https://www.uhaul.com/\n    baseURL: https://www.uhaul.com\n    tags:\n      - Moving\n      - Storage\n      - Truck Rental\n      - Dealer Program\n    properties:\n      - type: Documentation\n        url: https://www.uhaul.com/\n      - type: Portal\n        url: https://www.uhaul.com/Dealer/\n\ncommon:\n  - type: Website\n    url: https://www.amerco.com/\n  - type: Website\n    url: https://www.uhaul.com/\n  - type: Portal\n    url: https://www.uhaul.com/Dealer/\n  - type: Features\n    data:\n      - name: Truck and Trailer Rental Network\n        description: >-\n       \
  \   Nationwide network of U-Haul trucks and trailers available through\n          dealer locations with online booking and 24/7 customer support.\n      - name: Self-Storage Facilities\n        description: >-\n          U-Haul owned and affiliate self-storage facilities with online\n          reservation management and climate-controlled options.\n      - name: Moving Help Marketplace\n        description: >-\n          Online marketplace connecting consumers to independent moving service\n          providers for loading, unloading, packing, and cleaning services.\n      - name: U-Haul Self-Storage Affiliate Network\n        description: >-\n          Partner network for independent self-storage facilities to list\n          inventory and accept reservations through uhaul.com with\n          WebSelfStorage management software.\n      - name: WebSelfStorage Management Software\n        description: >-\n          Self-storage management application providing reservation management,\n  \
  \        tenant tracking, payment processing, and reporting for independent\n          storage facilities.\n      - name: U-Box Portable Storage\n        description: >-\n          Portable moving and storage container service with pickup, transport,\n          and delivery options for local and long-distance moves.\n      - name: Dealer Program\n        description: >-\n          No-investment dealer program for small businesses to add U-Haul truck\n          and trailer rental to existing product offerings with 21% average\n          commission and weekly direct deposit payments.\n  - type: UseCases\n    data:\n      - name: Local and Long-Distance Moving\n        description: >-\n          Individuals and families rent trucks and trailers for DIY residential\n          and commercial moves across the U-Haul network.\n      - name: Self-Storage Management\n        description: >-\n          Independent storage facility owners manage reservations, payments,\n          and tenant accounts\
  \ through WebSelfStorage software.\n      - name: Moving Service Provider Marketplace\n        description: >-\n          Independent movers offer loading, unloading, and packing services\n          through the Moving Help marketplace on uhaul.com.\n      - name: Dealer Business Revenue\n        description: >-\n          Small businesses add U-Haul rental services to generate supplemental\n          revenue with zero startup costs and high commissions.\n  - type: Integrations\n    data:\n      - name: Moving Help Marketplace\n        description: >-\n          Platform integration connecting consumers to independent moving\n          service providers nationwide through uhaul.com.\n      - name: AMERITAS Life Insurance\n        description: >-\n          AMERCO subsidiary providing life insurance products as part of the\n          broader AMERCO financial services portfolio.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amerco/refs/heads/main/apis.yml
tags:
- Moving
- Storage
- Truck Rental
- Logistics
- Consumer Services
url: https://raw.githubusercontent.com/api-evangelist/amerco/refs/heads/main/apis.yml
use_cases:
- description: Individuals and families rent trucks and trailers for DIY residential and commercial moves across the U-Haul network.
  name: Local and Long-Distance Moving
- description: Independent storage facility owners manage reservations, payments, and tenant accounts through WebSelfStorage software.
  name: Self-Storage Management
- description: Independent movers offer loading, unloading, and packing services through the Moving Help marketplace on uhaul.com.
  name: Moving Service Provider Marketplace
- description: Small businesses add U-Haul rental services to generate supplemental revenue with zero startup costs and high commissions.
  name: Dealer Business Revenue
---
