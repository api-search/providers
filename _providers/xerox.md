---
api_count: 4
api_specs:
- filename: xerox-public-print-openapi.yml
  format: yaml
  label: Xerox Public Print API
  slug: xerox-public-print-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/xerox/refs/heads/main/openapi/xerox-public-print-openapi.yml
apis:
- description: 'REST API for managing print jobs through the Xerox Public Print Service. Provides endpoints for job creation, status monitoring, site discovery, provider management, EULA handling, and print history. '
  name: Xerox Public Print API
  slug: xerox-public-print-api
- description: 'The Xerox MPS-API and Support Assistant API (SA-API) provide a secure common interface allowing third parties to access features in the Xerox hosted technology suite for managed print services. Based '
  name: Xerox Managed Print Services API
  slug: xerox-managed-print-services-api
- description: 'SDK and API framework for building custom applications that run directly on Xerox ConnectKey-enabled multifunction printers and compatible devices. Apps are deployed through the Xerox App Gallery and '
  name: Xerox Extensible Interface Platform (EIP)
  slug: xerox-extensible-interface-platform
- description: Software development kit for integrating with the Xerox FreeFlow production printing platform. Includes interfaces for Prepress, Press, Variable Information (VIPP), and Photo modules enabling custom w
  name: Xerox FreeFlow SDK
  slug: xerox-freeflow-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.xerox.com
- title: ''
  type: DeveloperProgram
  url: https://www.xerox.com/en-us/about/developer-program
- title: ''
  type: AppGallery
  url: https://appgallery.services.xerox.com
- title: ''
  type: DeveloperPortal
  url: https://developers.xerox-solutions.net
- title: ''
  type: PublicPrintAPI
  url: https://publicprintapi.services.xerox.com/
- title: ''
  type: TermsOfService
  url: https://www.xerox.com/en-us/about/legal
- title: ''
  type: PrivacyPolicy
  url: https://www.xerox.com/en-us/about/privacy
- title: ''
  type: Contact
  url: mailto:xerox.global.developer.program@xerox.com
created: '2024-01-01'
description: Xerox is a global technology company and document management leader providing printing, digital document management, and business process solutions. Xerox offers the Xerox Developer Program providing open, standards-based APIs for integration with ConnectKey multifunction printers, FreeFlow production printing, Managed Print Services (MPS), and the Xerox Public Print Service. The program provides SDKs, APIs, and tools for building custom printing applications, workflow integrations, and enterprise print management solutions.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-05-03'
name: Xerox
skills: []
slug: xerox
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: xerox\nname: Xerox\ndescription: >-\n  Xerox is a global technology company and document management leader providing\n  printing, digital document management, and business process solutions. Xerox\n  offers the Xerox Developer Program providing open, standards-based APIs for\n  integration with ConnectKey multifunction printers, FreeFlow production\n  printing, Managed Print Services (MPS), and the Xerox Public Print Service.\n  The program provides SDKs, APIs, and tools for building custom printing\n  applications, workflow integrations, and enterprise print management solutions.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Document Management\n  - Enterprise\n  - Fortune 500\n  - Managed Print Services\n  - Print Services\n  - Printing\ncreated: '2024-01-01'\nmodified: '2026-05-03'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/xerox/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n\
  \  - aid: xerox:xerox-public-print-api\n    name: Xerox Public Print API\n    description: >-\n      REST API for managing print jobs through the Xerox Public Print Service.\n      Provides endpoints for job creation, status monitoring, site discovery,\n      provider management, EULA handling, and print history. Requires\n      authentication via xrxauth header, user-email, and appid for all secure\n      calls. Supports location-based site search for finding nearby printers.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://publicprintapi.services.xerox.com/\n    baseURL: https://publicprintapi.services.xerox.com/api/v1\n    tags:\n      - Print Jobs\n      - Print Management\n      - Printing\n      - REST\n    properties:\n      - type: Documentation\n        url: https://publicprintapi.services.xerox.com/\n      - type: OpenAPI\n        url: openapi/xerox-public-print-openapi.yml\n    contact:\n      - type: Email\n      \
  \  url: mailto:xerox.global.developer.program@xerox.com\n  - aid: xerox:xerox-managed-print-services-api\n    name: Xerox Managed Print Services API\n    description: >-\n      The Xerox MPS-API and Support Assistant API (SA-API) provide a secure\n      common interface allowing third parties to access features in the Xerox\n      hosted technology suite for managed print services. Based on standard\n      Web Service technologies supporting fleet management, device monitoring,\n      supply replenishment, and service request automation.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.xerox.com/en-us/about/developer-program\n    tags:\n      - Fleet Management\n      - Managed Print Services\n      - Monitoring\n      - Print Management\n    properties:\n      - type: Documentation\n        url: https://www.xerox.com/en-us/about/developer-program\n  - aid: xerox:xerox-extensible-interface-platform\n    name: Xerox Extensible\
  \ Interface Platform (EIP)\n    description: >-\n      SDK and API framework for building custom applications that run directly\n      on Xerox ConnectKey-enabled multifunction printers and compatible devices.\n      Apps are deployed through the Xerox App Gallery and can integrate\n      device capabilities including scanning, printing, and workflow automation.\n      Includes the Xerox App Developer Kit for ConnectKey applications.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.xerox.com/en-us/about/developer-program\n    tags:\n      - App Development\n      - ConnectKey\n      - Multifunction Printer\n      - SDK\n    properties:\n      - type: Documentation\n        url: https://www.xerox.com/en-us/about/developer-program\n      - type: AppGallery\n        url: https://appgallery.services.xerox.com\n  - aid: xerox:xerox-freeflow-api\n    name: Xerox FreeFlow SDK\n    description: >-\n      Software development kit for\
  \ integrating with the Xerox FreeFlow\n      production printing platform. Includes interfaces for Prepress, Press,\n      Variable Information (VIPP), and Photo modules enabling custom workflow\n      automation for high-volume production printing environments.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.xerox.com/en-us/about/developer-program\n    tags:\n      - FreeFlow\n      - Production Printing\n      - SDK\n      - VIPP\n    properties:\n      - type: Documentation\n        url: https://www.xerox.com/en-us/about/developer-program\ncommon:\n  - type: Website\n    url: https://www.xerox.com\n  - type: DeveloperProgram\n    url: https://www.xerox.com/en-us/about/developer-program\n  - type: AppGallery\n    url: https://appgallery.services.xerox.com\n  - type: DeveloperPortal\n    url: https://developers.xerox-solutions.net\n  - type: PublicPrintAPI\n    url: https://publicprintapi.services.xerox.com/\n  - type: TermsOfService\n\
  \    url: https://www.xerox.com/en-us/about/legal\n  - type: PrivacyPolicy\n    url: https://www.xerox.com/en-us/about/privacy\n  - type: Contact\n    url: mailto:xerox.global.developer.program@xerox.com\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/xerox/refs/heads/main/apis.yml
tags:
- Document Management
- Enterprise
- Fortune 500
- Managed Print Services
- Print Services
- Printing
url: https://raw.githubusercontent.com/api-evangelist/xerox/refs/heads/main/apis.yml
use_cases: []
---
