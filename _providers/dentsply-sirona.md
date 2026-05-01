---
api_count: 2
apis:
- description: DS Core is the open cloud platform from Dentsply Sirona that connects dental practices, laboratories, and DSOs through a single web-based experience. The DS Core API enables Practice Management System
  name: DS Core API
  slug: ds-core-api
- description: The DSIO modality API enables third-party imaging software to drive Dentsply Sirona intraoral imaging hardware (sensors and cameras) through a documented protocol. The API and its reference client are
  name: Dentsply Sirona Intraoral Imaging Modality API
  slug: dsio-modality-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.dentsply-sirona.com
- title: ''
  type: USA Website
  url: https://www.dentsplysirona.com/en-us
- title: ''
  type: Open Platform
  url: https://open.dscore.com/
- title: ''
  type: DS Core Marketing
  url: https://www.dentsplysirona.com/en-us/discover/discover-by-brand/ds-core.html
- title: ''
  type: Connected Dentistry
  url: https://www.dentsplysirona.com/en/lp/connected-dentistry.html
- title: ''
  type: Connect Software
  url: https://www.dentsplysirona.com/en-us/discover/discover-by-brand/connect-software.html
- title: ''
  type: Service Portal
  url: https://service.dscore.com/
- title: ''
  type: GitHub Imaging
  url: https://github.com/dsimaging
- title: ''
  type: Investors
  url: https://investor.dentsplysirona.com
- title: ''
  type: Newsroom
  url: https://www.dentsplysirona.com/en/about-dentsply-sirona/news.html
- title: ''
  type: Sustainability
  url: https://www.dentsplysirona.com/en/about-dentsply-sirona/sustainability.html
- title: ''
  type: Careers
  url: https://www.dentsplysirona.com/en/about-dentsply-sirona/careers.html
- title: ''
  type: Contact
  url: https://www.dentsplysirona.com/en/about-dentsply-sirona/contact-us.html
- title: ''
  type: Terms of Use
  url: https://www.dentsplysirona.com/en/legal-notice.html
- title: ''
  type: Privacy Policy
  url: https://www.dentsplysirona.com/en/legal-notice/privacy-policy.html
- title: ''
  type: JSON-LD
  url: json-ld/dentsply-sirona-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/dentsply-sirona-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/dentsply-sirona-capabilities.yml
created: '2026-03-24'
description: Dentsply Sirona is the world's largest manufacturer of professional dental products and technologies, providing comprehensive solutions for dentists, dental laboratories, and dental specialists worldwide. The company exposes developer integrations through DS Core, an open cloud platform, and through the Dentsply Sirona Imaging modality API for intraoral imaging hardware.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Dentsply Sirona Context
  property_count: 6
  slug: dentsply-sirona-context
layout: provider
modified: '2026-04-28'
name: Dentsply Sirona
skills: []
slug: dentsply-sirona
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: dentsply-sirona\nname: Dentsply Sirona\ndescription: >-\n  Dentsply Sirona is the world's largest manufacturer of professional dental\n  products and technologies, providing comprehensive solutions for dentists,\n  dental laboratories, and dental specialists worldwide. The company exposes\n  developer integrations through DS Core, an open cloud platform, and through\n  the Dentsply Sirona Imaging modality API for intraoral imaging hardware.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CAD/CAM\n  - CEREC\n  - Dental\n  - DS Core\n  - Imaging\n  - Intraoral Imaging\n  - Lab Management\n  - Practice Management\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/dentsply-sirona/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: company\nposition: Producer\naccess: 3rd-Party\napis:\n  - aid: dentsply-sirona:ds-core-api\n    name: DS Core API\n \
  \   description: >-\n      DS Core is the open cloud platform from Dentsply Sirona that connects dental\n      practices, laboratories, and DSOs through a single web-based experience. The\n      DS Core API enables Practice Management System (PMS) providers, Lab Management\n      System (LMS) providers, and DSO enterprise solutions to integrate with DS Core\n      for patient data synchronization, scan and imaging exchange, lab order routing,\n      file and comment exchange, and Single Sign-On user provisioning.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://open.dscore.com/\n    baseURL: https://api.dscore.com\n    tags:\n      - DS Core\n      - Imaging\n      - Lab Management\n      - Patient Data\n      - Practice Management\n      - SSO\n    properties:\n      - type: Documentation\n        url: https://open.dscore.com/\n      - type: Sign Up\n        url: https://open.dscore.com/\n      - type: Marketing\n        url:\
  \ https://www.dentsplysirona.com/en/lp/connected-dentistry.html\n    contact:\n      - FN: DS Core Open Platform\n        url: https://open.dscore.com/\n  - aid: dentsply-sirona:dsio-modality-api\n    name: Dentsply Sirona Intraoral Imaging Modality API\n    description: >-\n      The DSIO modality API enables third-party imaging software to drive\n      Dentsply Sirona intraoral imaging hardware (sensors and cameras) through\n      a documented protocol. The API and its reference client are published on\n      GitHub by the Dentsply Sirona Imaging team and are intended for software\n      vendors that wish to capture, transfer, and store intraoral images from\n      Dentsply Sirona devices in their own dental software.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/dsimaging/dsio-modality-api\n    baseURL: https://api.example.com\n    tags:\n      - GitHub\n      - Imaging\n      - Intraoral\n      - Modality\n\
  \      - Sensors\n    properties:\n      - type: Documentation\n        url: https://github.com/dsimaging/dsio-modality-api\n      - type: Source Code\n        url: https://github.com/dsimaging/dsio-modality-api\n    contact:\n      - FN: Dentsply Sirona Imaging\n        url: https://github.com/dsimaging\ncommon:\n  - type: Website\n    url: https://www.dentsply-sirona.com\n  - type: USA Website\n    url: https://www.dentsplysirona.com/en-us\n  - type: Open Platform\n    url: https://open.dscore.com/\n  - type: DS Core Marketing\n    url: https://www.dentsplysirona.com/en-us/discover/discover-by-brand/ds-core.html\n  - type: Connected Dentistry\n    url: https://www.dentsplysirona.com/en/lp/connected-dentistry.html\n  - type: Connect Software\n    url: https://www.dentsplysirona.com/en-us/discover/discover-by-brand/connect-software.html\n  - type: Service Portal\n    url: https://service.dscore.com/\n  - type: GitHub Imaging\n    url: https://github.com/dsimaging\n  - type: Investors\n\
  \    url: https://investor.dentsplysirona.com\n  - type: Newsroom\n    url: https://www.dentsplysirona.com/en/about-dentsply-sirona/news.html\n  - type: Sustainability\n    url: https://www.dentsplysirona.com/en/about-dentsply-sirona/sustainability.html\n  - type: Careers\n    url: https://www.dentsplysirona.com/en/about-dentsply-sirona/careers.html\n  - type: Contact\n    url: https://www.dentsplysirona.com/en/about-dentsply-sirona/contact-us.html\n  - type: Terms of Use\n    url: https://www.dentsplysirona.com/en/legal-notice.html\n  - type: Privacy Policy\n    url: https://www.dentsplysirona.com/en/legal-notice/privacy-policy.html\n  - type: JSON-LD\n    url: json-ld/dentsply-sirona-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/dentsply-sirona-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/dentsply-sirona-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/dentsply-sirona/refs/heads/main/apis.yml
tags:
- CAD/CAM
- CEREC
- Dental
- DS Core
- Imaging
- Intraoral Imaging
- Lab Management
- Practice Management
url: https://raw.githubusercontent.com/api-evangelist/dentsply-sirona/refs/heads/main/apis.yml
use_cases: []
---
