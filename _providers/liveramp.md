---
api_count: 9
apis:
- description: Programmatic activation of first-party and marketplace data across destination partners and connected platforms in the LiveRamp network.
  name: LiveRamp Activation API
  slug: activation-api
- description: Privacy-first, PII-based authentication API enabling programmatic addressability without third-party cookies via RampID envelopes.
  name: LiveRamp Authenticated Traffic Solution (ATS) API
  slug: ats-api
- description: API for setting up and managing clean rooms, data sources, and collaborative analytics queries between data partners.
  name: LiveRamp Clean Room API
  slug: clean-room-api
- description: API enabling platforms to host third-party segments from the LiveRamp Data Marketplace and access detailed segment metadata.
  name: LiveRamp Data Marketplace Buyer API
  slug: datamarketplace-buyer-api
- description: Identity resolution API that resolves offline PII data into stable AbiliTec links for enterprise customer-database unification.
  name: LiveRamp AbiliTec API
  slug: abilitec-api
- description: API for matching data to the LiveRamp Identity Graph, including envelope decryption and translation between pseudonymous identifiers.
  name: LiveRamp RampID API
  slug: rampid-api
- description: Automates Python, PySpark, and BigQuery jobs running in LiveRamp's Safe Haven Analytics Environment.
  name: LiveRamp Safe Haven Job Management API
  slug: job-management-api
- description: Automates data subject requests including opt-outs, deletions, and consent updates across the LiveRamp ecosystem.
  name: LiveRamp Privacy API
  slug: privacy-api
- description: Service enabling SSPs to decrypt RampID identity envelopes into DSP-specific identifiers for programmatic activation.
  name: LiveRamp Sidecar
  slug: sidecar
common:
- title: ''
  type: Website
  url: https://liveramp.com
- title: ''
  type: Portal
  url: https://developers.liveramp.com/
- title: ''
  type: Documentation
  url: https://docs.liveramp.com/
- title: ''
  type: SupportPortal
  url: https://support.liveramp.com/
- title: ''
  type: Blog
  url: https://liveramp.com/blog/
- title: ''
  type: GitHubOrganization
  url: https://github.com/LiveRamp
created: '2026-03-16'
description: LiveRamp is a data connectivity platform that enables enterprises to safely connect, control, and activate first-party customer data across the digital ecosystem. Their developer platform exposes a suite of REST APIs for identity resolution, data activation, clean-room collaboration, marketplace data access, and privacy-first authenticated traffic.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: LiveRamp
skills: []
slug: liveramp
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: liveramp\nname: LiveRamp\ndescription: >-\n  LiveRamp is a data connectivity platform that enables enterprises to safely\n  connect, control, and activate first-party customer data across the digital\n  ecosystem. Their developer platform exposes a suite of REST APIs for identity\n  resolution, data activation, clean-room collaboration, marketplace data\n  access, and privacy-first authenticated traffic.\ntype: Index\nposition: Consuming\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Connectivity\n  - Identity Resolution\n  - Activation\n  - Clean Room\n  - Privacy\n  - AdTech\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/liveramp/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: liveramp:activation-api\n    name: LiveRamp Activation API\n    description: >-\n      Programmatic activation of first-party and marketplace\
  \ data across\n      destination partners and connected platforms in the LiveRamp network.\n    humanURL: https://developers.liveramp.com/activation-api\n    tags:\n      - Activation\n      - AdTech\n      - Marketing\n    properties:\n      - type: Documentation\n        url: https://developers.liveramp.com/activation-api\n  - aid: liveramp:ats-api\n    name: LiveRamp Authenticated Traffic Solution (ATS) API\n    description: >-\n      Privacy-first, PII-based authentication API enabling programmatic\n      addressability without third-party cookies via RampID envelopes.\n    humanURL: https://developers.liveramp.com/authenticatedtraffic-api\n    tags:\n      - Identity\n      - Privacy\n      - Authentication\n    properties:\n      - type: Documentation\n        url: https://developers.liveramp.com/authenticatedtraffic-api\n  - aid: liveramp:clean-room-api\n    name: LiveRamp Clean Room API\n    description: >-\n      API for setting up and managing clean rooms, data sources, and\n\
  \      collaborative analytics queries between data partners.\n    humanURL: https://developers.liveramp.com/clean-room-api\n    tags:\n      - Clean Room\n      - Data Collaboration\n      - Privacy\n    properties:\n      - type: Documentation\n        url: https://developers.liveramp.com/clean-room-api\n  - aid: liveramp:datamarketplace-buyer-api\n    name: LiveRamp Data Marketplace Buyer API\n    description: >-\n      API enabling platforms to host third-party segments from the LiveRamp\n      Data Marketplace and access detailed segment metadata.\n    humanURL: https://developers.liveramp.com/datamarketplace-buyer-api\n    tags:\n      - Data Marketplace\n      - Segments\n      - AdTech\n    properties:\n      - type: Documentation\n        url: https://developers.liveramp.com/datamarketplace-buyer-api\n  - aid: liveramp:abilitec-api\n    name: LiveRamp AbiliTec API\n    description: >-\n      Identity resolution API that resolves offline PII data into stable\n      AbiliTec links\
  \ for enterprise customer-database unification.\n    humanURL: https://developers.liveramp.com/abilitec-api\n    tags:\n      - Identity\n      - Resolution\n      - PII\n    properties:\n      - type: Documentation\n        url: https://developers.liveramp.com/abilitec-api\n  - aid: liveramp:rampid-api\n    name: LiveRamp RampID API\n    description: >-\n      API for matching data to the LiveRamp Identity Graph, including envelope\n      decryption and translation between pseudonymous identifiers.\n    humanURL: https://developers.liveramp.com/rampid-api\n    tags:\n      - Identity\n      - RampID\n      - Pseudonymous\n    properties:\n      - type: Documentation\n        url: https://developers.liveramp.com/rampid-api\n  - aid: liveramp:job-management-api\n    name: LiveRamp Safe Haven Job Management API\n    description: >-\n      Automates Python, PySpark, and BigQuery jobs running in LiveRamp's Safe\n      Haven Analytics Environment.\n    humanURL: https://developers.liveramp.com/ae-job-management-api\n\
  \    tags:\n      - Analytics\n      - Automation\n      - Jobs\n    properties:\n      - type: Documentation\n        url: https://developers.liveramp.com/ae-job-management-api\n  - aid: liveramp:privacy-api\n    name: LiveRamp Privacy API\n    description: >-\n      Automates data subject requests including opt-outs, deletions, and\n      consent updates across the LiveRamp ecosystem.\n    humanURL: https://developers.liveramp.com/privacy-api\n    tags:\n      - Privacy\n      - Consent\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://developers.liveramp.com/privacy-api\n  - aid: liveramp:sidecar\n    name: LiveRamp Sidecar\n    description: >-\n      Service enabling SSPs to decrypt RampID identity envelopes into\n      DSP-specific identifiers for programmatic activation.\n    humanURL: https://sidecar.readme.io/\n    tags:\n      - SSP\n      - Programmatic\n      - Identity\n    properties:\n      - type: Documentation\n        url: https://sidecar.readme.io/\n\
  common:\n  - type: Website\n    url: https://liveramp.com\n  - type: Portal\n    url: https://developers.liveramp.com/\n  - type: Documentation\n    url: https://docs.liveramp.com/\n  - type: SupportPortal\n    url: https://support.liveramp.com/\n  - type: Blog\n    url: https://liveramp.com/blog/\n  - type: GitHubOrganization\n    url: https://github.com/LiveRamp\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/liveramp/refs/heads/main/apis.yml
tags:
- Data Connectivity
- Identity Resolution
- Activation
- Clean Room
- Privacy
- AdTech
url: https://raw.githubusercontent.com/api-evangelist/liveramp/refs/heads/main/apis.yml
use_cases: []
---
