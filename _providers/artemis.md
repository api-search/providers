---
api_count: 2
apis:
- description: NASA's Open API platform at api.nasa.gov provides programmatic access to NASA data including the Astronomy Picture of the Day (APOD), Near Earth Object Web Service (NeoWs), NASA Image and Video Librar
  name: NASA Open APIs
  slug: nasa-open-api
- description: The NASA Technology Transfer API provides programmatic access to the NASA patent portfolio, software catalog, and spinoff technologies developed through the Artemis program and other NASA missions, en
  name: NASA Technology Transfer API
  slug: nasa-tech-transfer-api
common:
- title: Artemis Program Website
  type: Portal
  url: https://www.nasa.gov/artemis/
- title: NASA Open APIs
  type: Documentation
  url: https://api.nasa.gov/
- title: NASA GitHub Organization
  type: GitHubOrganization
  url: https://github.com/nasa
- title: API Key Signup
  type: SignUp
  url: https://api.nasa.gov/#signUp
- title: Privacy Policy
  type: PrivacyPolicy
  url: https://www.nasa.gov/privacy/
created: '2024-01-15'
description: NASA's Artemis program is the next generation of lunar exploration, aiming to return humans to the Moon and establish a sustainable presence for future missions to Mars. The program includes the Space Launch System (SLS) rocket, Orion spacecraft, the Lunar Gateway space station, and commercial lunar landers from SpaceX and Blue Origin. NASA's Open APIs provide programmatic access to Artemis-related data, including mission imagery, space weather, and planetary data through api.nasa.gov. The program operates under NASA's Science Mission Directorate and Exploration Systems Development Mission Directorate.
features:
- description: Daily NASA astronomy images with descriptions and metadata, providing a public showcase of space imagery relevant to Artemis and broader space exploration.
  name: Astronomy Picture of the Day API
- description: NeoWs API provides data on near earth asteroids and their orbital parameters, supporting space situational awareness for lunar missions.
  name: Near Earth Object Web Service
- description: Access to photos captured by Curiosity, Opportunity, and Spirit Mars rovers, providing precursor science data for future crewed Mars missions planned after Artemis establishes lunar presence.
  name: Mars Rover Photos API
- description: Earth Polychromatic Imaging Camera imagery showing full-disc Earth imagery, relevant to climate monitoring that informs long-duration space missions.
  name: EPIC Earth Imagery
- description: DONKI API provides solar flare, geomagnetic storm, and space weather data critical for mission planning and crew safety on Artemis lunar missions.
  name: Space Weather Database Of Notifications, Knowledge, Information
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Commercial lunar lander integration for Artemis III and V crewed lunar surface missions.
  name: SpaceX Starship
- description: Commercial lunar lander selected for Artemis IV crewed lunar landing mission.
  name: Blue Origin Blue Moon
- description: Program integrating multiple commercial providers to deliver science payloads to the lunar surface in support of Artemis science objectives.
  name: Commercial Lunar Payload Services (CLPS)
layout: provider
modified: '2026-04-19'
name: Artemis
skills: []
slug: artemis
solutions: []
source_filename: apis.yml
source_yaml: "aid: artemis\nname: Artemis\ndescription: >-\n  NASA's Artemis program is the next generation of lunar exploration, aiming to\n  return humans to the Moon and establish a sustainable presence for future\n  missions to Mars. The program includes the Space Launch System (SLS) rocket,\n  Orion spacecraft, the Lunar Gateway space station, and commercial lunar landers\n  from SpaceX and Blue Origin. NASA's Open APIs provide programmatic access to\n  Artemis-related data, including mission imagery, space weather, and planetary\n  data through api.nasa.gov. The program operates under NASA's Science Mission\n  Directorate and Exploration Systems Development Mission Directorate.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Exploration\n  - Lunar\n  - Moon\n  - NASA\n  - Space\n  - Government\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/artemis/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-04-19'\n\
  specificationVersion: '0.19'\napis:\n  - aid: artemis:nasa-open-api\n    name: NASA Open APIs\n    description: >-\n      NASA's Open API platform at api.nasa.gov provides programmatic access to\n      NASA data including the Astronomy Picture of the Day (APOD), Near Earth\n      Object Web Service (NeoWs), NASA Image and Video Library, Mars Rover Photos,\n      EPIC Earth imagery, and space weather data relevant to Artemis mission\n      planning and operations.\n    humanURL: https://api.nasa.gov/\n    baseURL: https://api.nasa.gov\n    tags:\n      - Space\n      - NASA\n      - Science\n      - Imagery\n      - Open Data\n    properties:\n      - type: Documentation\n        url: https://api.nasa.gov/\n      - type: GettingStarted\n        url: https://api.nasa.gov/#getting-started\n  - aid: artemis:nasa-tech-transfer-api\n    name: NASA Technology Transfer API\n    description: >-\n      The NASA Technology Transfer API provides programmatic access to the\n      NASA patent portfolio,\
  \ software catalog, and spinoff technologies developed\n      through the Artemis program and other NASA missions, enabling technology\n      licensing and commercialization queries.\n    humanURL: https://technology.nasa.gov/\n    baseURL: https://technology.nasa.gov\n    tags:\n      - Technology\n      - Patents\n      - Software\n      - Licensing\n    properties:\n      - type: Documentation\n        url: https://technology.nasa.gov/\ncommon:\n  - type: Portal\n    url: https://www.nasa.gov/artemis/\n    title: Artemis Program Website\n  - type: Documentation\n    url: https://api.nasa.gov/\n    title: NASA Open APIs\n  - type: GitHubOrganization\n    url: https://github.com/nasa\n    title: NASA GitHub Organization\n  - type: SignUp\n    url: https://api.nasa.gov/#signUp\n    title: API Key Signup\n  - type: PrivacyPolicy\n    url: https://www.nasa.gov/privacy/\n    title: Privacy Policy\n  - type: Features\n    data:\n      - name: Astronomy Picture of the Day API\n        description:\
  \ >-\n          Daily NASA astronomy images with descriptions and metadata, providing\n          a public showcase of space imagery relevant to Artemis and broader\n          space exploration.\n      - name: Near Earth Object Web Service\n        description: >-\n          NeoWs API provides data on near earth asteroids and their orbital\n          parameters, supporting space situational awareness for lunar missions.\n      - name: Mars Rover Photos API\n        description: >-\n          Access to photos captured by Curiosity, Opportunity, and Spirit Mars\n          rovers, providing precursor science data for future crewed Mars missions\n          planned after Artemis establishes lunar presence.\n      - name: EPIC Earth Imagery\n        description: >-\n          Earth Polychromatic Imaging Camera imagery showing full-disc Earth\n          imagery, relevant to climate monitoring that informs long-duration\n          space missions.\n      - name: Space Weather Database Of Notifications,\
  \ Knowledge, Information\n        description: >-\n          DONKI API provides solar flare, geomagnetic storm, and space weather\n          data critical for mission planning and crew safety on Artemis lunar missions.\n  - type: UseCases\n    data:\n      - name: Mission Data Integration\n        description: >-\n          Researchers and mission planners integrate NASA Open APIs to build\n          dashboards and tools that aggregate space weather, trajectory, and\n          imagery data for Artemis mission support.\n      - name: Education and Outreach\n        description: >-\n          Educators and developers build Artemis-themed applications using\n          NASA imagery and mission data to engage the public in lunar exploration.\n      - name: Research Applications\n        description: >-\n          Scientists access planetary and space environment data programmatically\n          to support research that informs Artemis crew safety and mission planning.\n      - name: Technology\
  \ Transfer\n        description: >-\n          Companies and universities query the NASA Technology Transfer API to\n          identify Artemis-developed patents and software available for licensing.\n  - type: Integrations\n    data:\n      - name: SpaceX Starship\n        description: >-\n          Commercial lunar lander integration for Artemis III and V crewed lunar\n          surface missions.\n      - name: Blue Origin Blue Moon\n        description: >-\n          Commercial lunar lander selected for Artemis IV crewed lunar landing\n          mission.\n      - name: Commercial Lunar Payload Services (CLPS)\n        description: >-\n          Program integrating multiple commercial providers to deliver science\n          payloads to the lunar surface in support of Artemis science objectives.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/artemis/refs/heads/main/apis.yml
tags:
- Exploration
- Lunar
- Moon
- NASA
- Space
- Government
url: https://raw.githubusercontent.com/api-evangelist/artemis/refs/heads/main/apis.yml
use_cases:
- description: Researchers and mission planners integrate NASA Open APIs to build dashboards and tools that aggregate space weather, trajectory, and imagery data for Artemis mission support.
  name: Mission Data Integration
- description: Educators and developers build Artemis-themed applications using NASA imagery and mission data to engage the public in lunar exploration.
  name: Education and Outreach
- description: Scientists access planetary and space environment data programmatically to support research that informs Artemis crew safety and mission planning.
  name: Research Applications
- description: Companies and universities query the NASA Technology Transfer API to identify Artemis-developed patents and software available for licensing.
  name: Technology Transfer
---
