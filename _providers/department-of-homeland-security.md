---
api_count: 6
apis:
- description: The OpenFEMA API is FEMA's public RESTful service that exposes more than 70 datasets including disaster declarations, public assistance funded projects, individual assistance grants, hazard mitigation
  name: OpenFEMA API
  slug: openfema-api
- description: The USCIS Case Status API provides programmatic access to the same Case Status Online lookup that immigration applicants use, allowing authorized partners to retrieve the current status and history of
  name: USCIS Case Status API
  slug: uscis-case-status-api
- description: The USCIS FOIA Request and Status API allows partners to submit Freedom of Information Act requests programmatically and check the status of submitted requests. It is published through the USCIS Devel
  name: USCIS FOIA Request and Status API
  slug: uscis-foia-api
- description: The CISA Known Exploited Vulnerabilities (KEV) catalog is a curated list of vulnerabilities that have been actively exploited in the wild. The catalog is published as a JSON and CSV feed by the Cybers
  name: CISA Known Exploited Vulnerabilities Catalog Feed
  slug: cisa-kev-feed
- description: The National Terrorism Advisory System (NTAS) feed publishes current terrorism alerts and bulletins issued by DHS as XML files. Developers can consume the feed to surface advisory content in their own
  name: National Terrorism Advisory System Feed
  slug: ntas-feed
- description: The DHS Open Data Catalog publishes datasets across the Department's mission areas (immigration, law enforcement, emergency management, cybersecurity, infrastructure protection, screening, and maritim
  name: DHS Open Data Catalog
  slug: dhs-open-data-catalog
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.dhs.gov
- title: ''
  type: Open Data
  url: https://www.dhs.gov/data
- title: ''
  type: Office of Homeland Security Statistics
  url: https://ohss.dhs.gov/
- title: ''
  type: FEMA
  url: https://www.fema.gov
- title: ''
  type: USCIS Developer Portal
  url: https://developer.uscis.gov/
- title: ''
  type: CISA
  url: https://www.cisa.gov
- title: ''
  type: TSA
  url: https://www.tsa.gov
- title: ''
  type: CBP
  url: https://www.cbp.gov
- title: ''
  type: ICE
  url: https://www.ice.gov
- title: ''
  type: Coast Guard
  url: https://www.uscg.mil
- title: ''
  type: Secret Service
  url: https://www.secretservice.gov
- title: ''
  type: Components
  url: https://www.dhs.gov/operational-and-support-components
- title: ''
  type: Data.gov DHS Catalog
  url: https://catalog.data.gov/organization/dhs-gov
- title: ''
  type: Privacy
  url: https://www.dhs.gov/privacy-office
- title: ''
  type: Contact
  url: https://www.dhs.gov/contact-us
- title: ''
  type: GitHub Organization
  url: https://github.com/cisagov
- title: ''
  type: JSON-LD
  url: json-ld/department-of-homeland-security-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/department-of-homeland-security-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/department-of-homeland-security-capabilities.yml
created: '2024-12-03'
description: The U.S. Department of Homeland Security (DHS) is a cabinet-level federal agency responsible for protecting the nation from terrorism, securing borders, enforcing immigration law, responding to disasters, and securing cyberspace. DHS exposes APIs across its operational components, including FEMA's OpenFEMA platform, USCIS's Developer Portal, the CISA Known Exploited Vulnerabilities catalog, the National Terrorism Advisory System (NTAS) feed, and the DHS Open Data Catalog.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Department Of Homeland Security Context
  property_count: 6
  slug: department-of-homeland-security-context
layout: provider
modified: '2026-04-28'
name: Department of Homeland Security
skills: []
slug: department-of-homeland-security
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: department-of-homeland-security\nname: Department of Homeland Security\ndescription: >-\n  The U.S. Department of Homeland Security (DHS) is a cabinet-level federal\n  agency responsible for protecting the nation from terrorism, securing\n  borders, enforcing immigration law, responding to disasters, and securing\n  cyberspace. DHS exposes APIs across its operational components, including\n  FEMA's OpenFEMA platform, USCIS's Developer Portal, the CISA Known\n  Exploited Vulnerabilities catalog, the National Terrorism Advisory System\n  (NTAS) feed, and the DHS Open Data Catalog.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CISA\n  - Cybersecurity\n  - Disaster\n  - Federal Government\n  - FEMA\n  - Homeland Security\n  - Immigration\n  - NTAS\n  - Open Data\n  - USCIS\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/department-of-homeland-security/refs/heads/main/apis.yml\ncreated: '2024-12-03'\n\
  modified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: government\nposition: Producer\naccess: Public\napis:\n  - aid: department-of-homeland-security:openfema-api\n    name: OpenFEMA API\n    description: >-\n      The OpenFEMA API is FEMA's public RESTful service that exposes more\n      than 70 datasets including disaster declarations, public assistance\n      funded projects, individual assistance grants, hazard mitigation, and\n      housing assistance program data. The API is free, requires no API key,\n      and supports OData-style query string parameters for filtering, sorting,\n      pagination, and field selection. Default page size is 1,000 records up\n      to a maximum of 10,000.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.fema.gov/about/openfema\n    baseURL: https://www.fema.gov/api/open\n    tags:\n      - Disaster\n      - FEMA\n      - Hazard Mitigation\n      - Public Assistance\n    properties:\n\
  \      - type: Documentation\n        url: https://www.fema.gov/about/openfema/api\n      - type: Developer Resources\n        url: https://www.fema.gov/about/openfema/developer-resources\n      - type: Datasets\n        url: https://www.fema.gov/about/openfema/data-sets\n      - type: Changelog\n        url: https://www.fema.gov/about/openfema/changelog\n    contact:\n      - FN: OpenFEMA\n        email: openfema@fema.dhs.gov\n        url: https://www.fema.gov/about/openfema\n  - aid: department-of-homeland-security:uscis-case-status-api\n    name: USCIS Case Status API\n    description: >-\n      The USCIS Case Status API provides programmatic access to the same\n      Case Status Online lookup that immigration applicants use, allowing\n      authorized partners to retrieve the current status and history of a\n      USCIS case by receipt number. The API uses OAuth 2.0 client credentials\n      and is published through the USCIS Developer Portal.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://developer.uscis.gov/api/case-status\n    baseURL: https://api.uscis.gov\n    tags:\n      - Case Status\n      - Immigration\n      - USCIS\n    properties:\n      - type: Documentation\n        url: https://developer.uscis.gov/api/case-status\n      - type: Portal\n        url: https://developer.uscis.gov/\n      - type: Catalog\n        url: https://developer.uscis.gov/apis\n    contact:\n      - FN: USCIS Developer Support\n        url: https://developer.uscis.gov/\n  - aid: department-of-homeland-security:uscis-foia-api\n    name: USCIS FOIA Request and Status API\n    description: >-\n      The USCIS FOIA Request and Status API allows partners to submit Freedom\n      of Information Act requests programmatically and check the status of\n      submitted requests. It is published through the USCIS Developer Portal\n      using OAuth 2.0.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://developer.uscis.gov/api/foia-request-and-status\n\
  \    baseURL: https://api.uscis.gov\n    tags:\n      - FOIA\n      - Immigration\n      - USCIS\n    properties:\n      - type: Documentation\n        url: https://developer.uscis.gov/api/foia-request-and-status\n      - type: Portal\n        url: https://developer.uscis.gov/\n    contact:\n      - FN: USCIS Developer Support\n        url: https://developer.uscis.gov/\n  - aid: department-of-homeland-security:cisa-kev-feed\n    name: CISA Known Exploited Vulnerabilities Catalog Feed\n    description: >-\n      The CISA Known Exploited Vulnerabilities (KEV) catalog is a curated\n      list of vulnerabilities that have been actively exploited in the wild.\n      The catalog is published as a JSON and CSV feed by the Cybersecurity\n      and Infrastructure Security Agency (CISA), and is mirrored on GitHub\n      for easy programmatic access.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.cisa.gov/known-exploited-vulnerabilities-catalog\n\
  \    baseURL: https://www.cisa.gov/sites/default/files/feeds\n    tags:\n      - CISA\n      - CVE\n      - Cybersecurity\n      - KEV\n      - Vulnerabilities\n    properties:\n      - type: Documentation\n        url: https://www.cisa.gov/known-exploited-vulnerabilities-catalog\n      - type: JSON Feed\n        url: https://www.cisa.gov/sites/default/files/feeds/known_exploited_vulnerabilities.json\n      - type: KEV Resources\n        url: https://www.cisa.gov/resources-tools/resources/kev-catalog\n      - type: Mirror\n        url: https://github.com/cisagov/kev-data\n    contact:\n      - FN: CISA Central\n        url: https://www.cisa.gov/about/contact\n  - aid: department-of-homeland-security:ntas-feed\n    name: National Terrorism Advisory System Feed\n    description: >-\n      The National Terrorism Advisory System (NTAS) feed publishes current\n      terrorism alerts and bulletins issued by DHS as XML files. Developers\n      can consume the feed to surface advisory content\
  \ in their own\n      applications and web pages.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.dhs.gov/ntas-api-documentation\n    baseURL: https://www.dhs.gov\n    tags:\n      - Alerts\n      - NTAS\n      - Terrorism\n      - XML\n    properties:\n      - type: Documentation\n        url: https://www.dhs.gov/ntas-api-documentation\n      - type: NTAS\n        url: https://www.dhs.gov/national-terrorism-advisory-system\n    contact:\n      - FN: DHS Public Affairs\n        url: https://www.dhs.gov/contact-us\n  - aid: department-of-homeland-security:dhs-open-data-catalog\n    name: DHS Open Data Catalog\n    description: >-\n      The DHS Open Data Catalog publishes datasets across the Department's\n      mission areas (immigration, law enforcement, emergency management,\n      cybersecurity, infrastructure protection, screening, and maritime).\n      Datasets are also available via Data.gov's CKAN-compatible API.\n\
  \    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.dhs.gov/data\n    baseURL: https://catalog.data.gov/api/3\n    tags:\n      - CKAN\n      - Datasets\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://www.dhs.gov/data\n      - type: OHSS\n        url: https://ohss.dhs.gov/\n      - type: Data.gov DHS\n        url: https://catalog.data.gov/organization/dhs-gov\n      - type: CKAN Reference\n        url: https://docs.ckan.org/en/2.8/api/\n    contact:\n      - FN: DHS Open Data\n        url: https://www.dhs.gov/data\ncommon:\n  - type: Website\n    url: https://www.dhs.gov\n  - type: Open Data\n    url: https://www.dhs.gov/data\n  - type: Office of Homeland Security Statistics\n    url: https://ohss.dhs.gov/\n  - type: FEMA\n    url: https://www.fema.gov\n  - type: USCIS Developer Portal\n    url: https://developer.uscis.gov/\n  - type: CISA\n    url: https://www.cisa.gov\n  - type: TSA\n\
  \    url: https://www.tsa.gov\n  - type: CBP\n    url: https://www.cbp.gov\n  - type: ICE\n    url: https://www.ice.gov\n  - type: Coast Guard\n    url: https://www.uscg.mil\n  - type: Secret Service\n    url: https://www.secretservice.gov\n  - type: Components\n    url: https://www.dhs.gov/operational-and-support-components\n  - type: Data.gov DHS Catalog\n    url: https://catalog.data.gov/organization/dhs-gov\n  - type: Privacy\n    url: https://www.dhs.gov/privacy-office\n  - type: Contact\n    url: https://www.dhs.gov/contact-us\n  - type: GitHub Organization\n    url: https://github.com/cisagov\n  - type: JSON-LD\n    url: json-ld/department-of-homeland-security-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/department-of-homeland-security-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/department-of-homeland-security-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/department-of-homeland-security/refs/heads/main/apis.yml
tags:
- CISA
- Cybersecurity
- Disaster
- Federal Government
- FEMA
- Homeland Security
- Immigration
- NTAS
- Open Data
- USCIS
url: https://raw.githubusercontent.com/api-evangelist/department-of-homeland-security/refs/heads/main/apis.yml
use_cases: []
---
