---
api_count: 6
apis:
- description: 'The CIA''s primary public-facing website at cia.gov hosts agency news stories, leadership biographies, mission statements, careers and recruiting information, and links to all other public CIA digital '
  name: CIA Public Website
  slug: cia-website
- description: The CIA's FOIA Electronic Reading Room (CREST - CIA Records Search Tool) is a publicly searchable interface to declassified CIA records released under the Freedom of Information Act. The site provides
  name: CIA FOIA Electronic Reading Room (CREST)
  slug: cia-foia-reading-room
- description: The CIA World Factbook is the long-running unclassified almanac of reference information on 260 world entities including all sovereign countries, dependencies, and oceans, organized into the categorie
  name: CIA World Factbook (Country Profiles)
  slug: cia-world-factbook
- description: The CIA Museum digital collection is the public-facing online catalog of artifacts, exhibits, and stories from the CIA Museum, including historical espionage tools, declassified mission gear, and cura
  name: CIA Museum Digital Collection
  slug: cia-museum
- description: Studies in Intelligence is the CIA's professional journal published by the Center for the Study of Intelligence (CSI). The site provides unclassified articles, book reviews, and historical analyses on
  name: Studies in Intelligence Journal
  slug: cia-studies-in-intelligence
- description: The CIA Careers portal is the agency's public recruiting site, listing open positions across analysis, operations, science and technology, digital innovation, and support functions, along with eligibi
  name: CIA Careers Portal
  slug: cia-careers
common:
- title: ''
  type: Website
  url: https://www.cia.gov/
- title: ''
  type: About
  url: https://www.cia.gov/about/
- title: ''
  type: News
  url: https://www.cia.gov/stories/
- title: ''
  type: FOIA
  url: https://www.cia.gov/readingroom/
- title: ''
  type: WorldFactbook
  url: https://www.cia.gov/the-world-factbook/
- title: ''
  type: Museum
  url: https://www.cia.gov/legacy/museum/
- title: ''
  type: Careers
  url: https://www.cia.gov/careers/
- title: ''
  type: Contact
  url: https://www.cia.gov/contact-cia/
- title: ''
  type: Privacy Policy
  url: https://www.cia.gov/privacy-statement/
- title: ''
  type: NoFearAct
  url: https://www.cia.gov/no-fear-act/
- title: ''
  type: AccessibilityStatement
  url: https://www.cia.gov/accessibility/
- title: ''
  type: Tor
  url: http://ciadotgov4sjwlzihbbgxnqg3xiyrg7so2r2o3lt5wz5ypk4sxyjstad.onion/
- title: ''
  type: ProgramAreas
  url: ''
- title: ''
  type: PublicResources
  url: ''
created: '2024-12-03'
description: The Central Intelligence Agency (CIA) is the United States' civilian foreign intelligence service of the federal government, tasked with gathering, processing, and analyzing national security information from around the world. While the CIA does not maintain a formal public developer program, it publishes a small number of digital resources of interest to civic technologists and researchers, including the CIA.gov public website, the FOIA Electronic Reading Room (CREST) of declassified records, the World Factbook country profiles (open dataset, public domain), the CIA Museum digital collection, the Studies in Intelligence journal archive, and the agency's careers portal. Note that the World Factbook web product was discontinued on 4 February 2026, but a CC0-licensed JSON dataset of all 260 Factbook entities is preserved on GitHub by the community.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Central Intelligence Agency
skills: []
slug: central-intelligence-agency
solutions: []
source_yaml: "aid: central-intelligence-agency\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/central-intelligence-agency/refs/heads/main/apis.yml\nname: Central Intelligence Agency\ntags:\n  - Federal Government\n  - FOIA\n  - Government\n  - Intelligence\n  - National Security\n  - Open Data\n  - World Factbook\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-04-23'\nposition: Consumer\nspecificationVersion: '0.19'\ndescription: >-\n  The Central Intelligence Agency (CIA) is the United States' civilian foreign\n  intelligence service of the federal government, tasked with gathering,\n  processing, and analyzing national security information from around the\n  world. While the CIA does not maintain a formal public developer program,\n  it publishes a small number of digital resources of interest to civic\n  technologists and researchers, including the CIA.gov public website,\
  \ the\n  FOIA Electronic Reading Room (CREST) of declassified records, the World\n  Factbook country profiles (open dataset, public domain), the CIA Museum\n  digital collection, the Studies in Intelligence journal archive, and the\n  agency's careers portal. Note that the World Factbook web product was\n  discontinued on 4 February 2026, but a CC0-licensed JSON dataset of all 260\n  Factbook entities is preserved on GitHub by the community.\napis:\n  - aid: central-intelligence-agency:cia-website\n    name: CIA Public Website\n    tags:\n      - Federal Government\n      - Intelligence\n      - News\n    humanURL: https://www.cia.gov/\n    properties:\n      - url: https://www.cia.gov/\n        type: Website\n      - url: https://www.cia.gov/about/\n        type: About\n      - url: https://www.cia.gov/stories/\n        type: News\n    description: >-\n      The CIA's primary public-facing website at cia.gov hosts agency news\n      stories, leadership biographies, mission statements,\
  \ careers and\n      recruiting information, and links to all other public CIA digital\n      properties.\n  - aid: central-intelligence-agency:cia-foia-reading-room\n    name: CIA FOIA Electronic Reading Room (CREST)\n    tags:\n      - Declassified\n      - Documents\n      - FOIA\n      - Records Search\n      - Transparency\n    humanURL: https://www.cia.gov/readingroom/\n    properties:\n      - url: https://www.cia.gov/readingroom/\n        type: Website\n      - url: https://www.cia.gov/readingroom/search/site\n        type: Search\n      - url: https://www.cia.gov/readingroom/collections\n        type: Collections\n    description: >-\n      The CIA's FOIA Electronic Reading Room (CREST - CIA Records Search Tool)\n      is a publicly searchable interface to declassified CIA records released\n      under the Freedom of Information Act. The site provides full-text\n      search, document downloads, and curated topical collections suitable\n      for researchers and historians.\n\
  \  - aid: central-intelligence-agency:cia-world-factbook\n    name: CIA World Factbook (Country Profiles)\n    tags:\n      - Country Profiles\n      - Demographics\n      - Geography\n      - Open Data\n      - Reference\n      - World Factbook\n    humanURL: https://www.cia.gov/the-world-factbook/\n    properties:\n      - url: https://www.cia.gov/the-world-factbook/\n        type: Website\n      - url: https://github.com/factbook/factbook.json\n        type: OpenData\n      - url: https://github.com/factbook/factbook.json\n        type: GitHubRepository\n    description: >-\n      The CIA World Factbook is the long-running unclassified almanac of\n      reference information on 260 world entities including all sovereign\n      countries, dependencies, and oceans, organized into the categories of\n      Geography, People and Society, Environment, Government, Economy,\n      Energy, Communications, Transportation, Military and Security, Space,\n      Terrorism, and Transnational Issues.\
  \ The web product was discontinued\n      4 February 2026; the community-maintained `factbook.json` GitHub\n      project preserves a CC0 / public-domain JSON dataset of all entities\n      for programmatic access.\n  - aid: central-intelligence-agency:cia-museum\n    name: CIA Museum Digital Collection\n    tags:\n      - Artifacts\n      - History\n      - Museum\n    humanURL: https://www.cia.gov/legacy/museum/\n    properties:\n      - url: https://www.cia.gov/legacy/museum/\n        type: Website\n      - url: https://www.cia.gov/legacy/museum/artifacts/\n        type: Catalog\n    description: >-\n      The CIA Museum digital collection is the public-facing online catalog\n      of artifacts, exhibits, and stories from the CIA Museum, including\n      historical espionage tools, declassified mission gear, and curated\n      narratives about agency history.\n  - aid: central-intelligence-agency:cia-studies-in-intelligence\n    name: Studies in Intelligence Journal\n    tags:\n   \
  \   - Analysis\n      - Intelligence\n      - Journal\n      - Publications\n    humanURL: https://www.cia.gov/resources/csi/studies-in-intelligence/\n    properties:\n      - url: https://www.cia.gov/resources/csi/studies-in-intelligence/\n        type: Website\n      - url: https://www.cia.gov/resources/csi/\n        type: CSI\n    description: >-\n      Studies in Intelligence is the CIA's professional journal published by\n      the Center for the Study of Intelligence (CSI). The site provides\n      unclassified articles, book reviews, and historical analyses on the\n      intelligence profession in PDF and HTML formats.\n  - aid: central-intelligence-agency:cia-careers\n    name: CIA Careers Portal\n    tags:\n      - Careers\n      - Hiring\n      - Jobs\n    humanURL: https://www.cia.gov/careers/\n    properties:\n      - url: https://www.cia.gov/careers/\n        type: Website\n      - url: https://www.cia.gov/careers/jobs/\n        type: Jobs\n    description: >-\n      The CIA\
  \ Careers portal is the agency's public recruiting site, listing\n      open positions across analysis, operations, science and technology,\n      digital innovation, and support functions, along with eligibility,\n      hiring process, and student/internship program information.\ncommon:\n  - type: Website\n    url: https://www.cia.gov/\n  - type: About\n    url: https://www.cia.gov/about/\n  - type: News\n    url: https://www.cia.gov/stories/\n  - type: FOIA\n    url: https://www.cia.gov/readingroom/\n  - type: WorldFactbook\n    url: https://www.cia.gov/the-world-factbook/\n  - type: Museum\n    url: https://www.cia.gov/legacy/museum/\n  - type: Careers\n    url: https://www.cia.gov/careers/\n  - type: Contact\n    url: https://www.cia.gov/contact-cia/\n  - type: Privacy Policy\n    url: https://www.cia.gov/privacy-statement/\n  - type: NoFearAct\n    url: https://www.cia.gov/no-fear-act/\n  - type: AccessibilityStatement\n    url: https://www.cia.gov/accessibility/\n  - type: Tor\n\
  \    url: http://ciadotgov4sjwlzihbbgxnqg3xiyrg7so2r2o3lt5wz5ypk4sxyjstad.onion/\n  - name: ProgramAreas\n    type: ProgramAreas\n    data:\n      - name: Foreign Intelligence Collection\n      - name: All-Source Analysis\n      - name: Covert Action\n      - name: Counterintelligence\n      - name: Counterterrorism\n      - name: Cybersecurity\n      - name: Science and Technology\n      - name: Open-Source Intelligence (OSINT)\n  - name: PublicResources\n    type: PublicResources\n    data:\n      - name: World Factbook (Discontinued)\n      - name: FOIA Electronic Reading Room (CREST)\n      - name: CIA Museum\n      - name: Studies in Intelligence Journal\n      - name: News and Stories\n      - name: Careers Portal\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/central-intelligence-agency/refs/heads/main/apis.yml
tags:
- Federal Government
- FOIA
- Government
- Intelligence
- National Security
- Open Data
- World Factbook
url: https://raw.githubusercontent.com/api-evangelist/central-intelligence-agency/refs/heads/main/apis.yml
use_cases: []
---
