---
api_count: 5
apis:
- description: 'Public-facing website of the Defense Technical Information Center describing DTIC services, products, and access programs. The site links to Discover, R&E Gateway, training, and registration but does '
  name: DTIC Website
  slug: defense-technical-information-center-website
- description: 'Search platform for DTIC''s collection of technical reports and other scientific and technical information assets. Discover offers faceted search, citation export, and document download for authorized '
  name: DTIC Discover
  slug: defense-technical-information-center-discover
- description: Authenticated portal for DoD researchers and registered users to access DTIC research and engineering resources, planning documents, and program information.
  name: DTIC Research and Engineering (R&E) Gateway
  slug: defense-technical-information-center-re-gateway
- description: Collaboration platform for DoD scientists, engineers, and program managers operated by DTIC for sharing knowledge, communities of practice, and project information.
  name: DoDTechSpace
  slug: defense-technical-information-center-dodtechspace
- description: Online portal that publishes records released under the Freedom of Information Act. Records are browsable and downloadable but there is no documented API.
  name: DTIC FOIA Reading Room
  slug: defense-technical-information-center-foia
common:
- title: ''
  type: Website
  url: https://www.dtic.mil
- title: ''
  type: Documentation
  url: https://www.dtic.mil/about-dtic
- title: ''
  type: News
  url: https://www.dtic.mil/dtic-digest
- title: ''
  type: ContactUs
  url: https://www.dtic.mil/contact-us
- title: ''
  type: PrivacyPolicy
  url: https://www.dtic.mil/website-policies
- title: ''
  type: FOIA
  url: https://www.dtic.mil/foia
created: '2024-12-25'
description: The Defense Technical Information Center (DTIC) is the U.S. Department of Defense field activity that acquires, manages, and disseminates scientific and technical information from DoD-funded research, development, test, and evaluation. DTIC operates a public Research and Engineering (R&E) Gateway, the Discover service for searching technical reports, the DoDTechSpace and Minsky natural-language platforms for defense researchers, and Dimensions for collaborative discovery. Most DTIC services require authentication tied to DoD or registered-user roles. DTIC does not publicly publish a developer API, though tools such as Dimensions and Minsky offer programmatic capabilities to authorized users.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Defense Technical Information Center
skills: []
slug: defense-technical-information-center
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: defense-technical-information-center\nname: Defense Technical Information Center\ndescription: >-\n  The Defense Technical Information Center (DTIC) is the U.S. Department of\n  Defense field activity that acquires, manages, and disseminates scientific\n  and technical information from DoD-funded research, development, test, and\n  evaluation. DTIC operates a public Research and Engineering (R&E)\n  Gateway, the Discover service for searching technical reports, the\n  DoDTechSpace and Minsky natural-language platforms for defense researchers,\n  and Dimensions for collaborative discovery. Most DTIC services require\n  authentication tied to DoD or registered-user roles. DTIC does not\n  publicly publish a developer API, though tools such as Dimensions and\n  Minsky offer programmatic capabilities to authorized users.\nurl: https://raw.githubusercontent.com/api-evangelist/defense-technical-information-center/refs/heads/main/apis.yml\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  specificationVersion: '0.19'\nxType: government\naccess: 3rd-Party\nposition: Consuming\ntags:\n  - Defense\n  - Department of Defense\n  - DTIC\n  - Federal Government\n  - Knowledge Management\n  - Library\n  - Research\n  - Scientific and Technical Information\ncreated: '2024-12-25'\nmodified: '2026-04-28'\napis:\n  - aid: defense-technical-information-center:defense-technical-information-center-website\n    name: DTIC Website\n    description: >-\n      Public-facing website of the Defense Technical Information Center\n      describing DTIC services, products, and access programs. The site\n      links to Discover, R&E Gateway, training, and registration but does\n      not publish a developer API.\n    humanURL: https://www.dtic.mil\n    tags:\n      - Federal Government\n      - Website\n    properties:\n      - type: Documentation\n        url: https://www.dtic.mil\n  - aid: defense-technical-information-center:defense-technical-information-center-discover\n    name: DTIC Discover\n\
  \    description: >-\n      Search platform for DTIC's collection of technical reports and other\n      scientific and technical information assets. Discover offers\n      faceted search, citation export, and document download for\n      authorized users. Programmatic access is not publicly documented.\n    humanURL: https://discover.dtic.mil\n    tags:\n      - Discovery\n      - Search\n      - Technical Reports\n    properties:\n      - type: Documentation\n        url: https://discover.dtic.mil\n  - aid: defense-technical-information-center:defense-technical-information-center-re-gateway\n    name: DTIC Research and Engineering (R&E) Gateway\n    description: >-\n      Authenticated portal for DoD researchers and registered users to\n      access DTIC research and engineering resources, planning documents,\n      and program information.\n    humanURL: https://discover.dtic.mil\n    tags:\n      - Engineering\n      - R&E\n      - Research\n    properties:\n      - type: Documentation\n\
  \        url: https://discover.dtic.mil\n  - aid: defense-technical-information-center:defense-technical-information-center-dodtechspace\n    name: DoDTechSpace\n    description: >-\n      Collaboration platform for DoD scientists, engineers, and program\n      managers operated by DTIC for sharing knowledge, communities of\n      practice, and project information.\n    humanURL: https://www.dodtechspace.mil\n    tags:\n      - Collaboration\n      - Communities of Practice\n    properties:\n      - type: Documentation\n        url: https://www.dodtechspace.mil\n  - aid: defense-technical-information-center:defense-technical-information-center-foia\n    name: DTIC FOIA Reading Room\n    description: >-\n      Online portal that publishes records released under the Freedom of\n      Information Act. Records are browsable and downloadable but there is\n      no documented API.\n    humanURL: https://www.dtic.mil/foia\n    tags:\n      - FOIA\n      - Open Records\n      - Transparency\n\
  \    properties:\n      - type: Documentation\n        url: https://www.dtic.mil/foia\ncommon:\n  - type: Website\n    url: https://www.dtic.mil\n  - type: Documentation\n    url: https://www.dtic.mil/about-dtic\n  - type: News\n    url: https://www.dtic.mil/dtic-digest\n  - type: ContactUs\n    url: https://www.dtic.mil/contact-us\n  - type: PrivacyPolicy\n    url: https://www.dtic.mil/website-policies\n  - type: FOIA\n    url: https://www.dtic.mil/foia\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/defense-technical-information-center/refs/heads/main/apis.yml
tags:
- Defense
- Department of Defense
- DTIC
- Federal Government
- Knowledge Management
- Library
- Research
- Scientific and Technical Information
url: https://raw.githubusercontent.com/api-evangelist/defense-technical-information-center/refs/heads/main/apis.yml
use_cases: []
---
