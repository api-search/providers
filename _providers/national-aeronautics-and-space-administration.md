---
api_count: 13
apis:
- description: One of the most popular websites at NASA is the Astronomy Picture of the Day. This API exposes the same featured image with metadata.
  name: APOD - Astronomy Picture of the Day
  slug: apod
- description: Near Earth Object Web Service is a RESTful web service for near earth Asteroid information including closest approach data and orbital data.
  name: NeoWs - Near Earth Object Web Service
  slug: neows
- description: The Space Weather Database Of Notifications, Knowledge, Information (DONKI) is a comprehensive online tool for space weather forecasters, scientists, and researchers.
  name: DONKI - Space Weather Database Of Notifications, Knowledge, Information
  slug: donki
- description: Earth imagery API providing Landsat 8 imagery and asset metadata for a given lat/lon location and date.
  name: Earth Imagery and Assets
  slug: earth
- description: EONET is a prototype web service that provides a curated source of continuously updated natural event metadata.
  name: EONET - Earth Observatory Natural Event Tracker
  slug: eonet
- description: The EPIC API provides full disc imagery of the Earth captured by the DSCOVR spacecraft, including natural and enhanced color images.
  name: EPIC - Earth Polychromatic Imaging Camera
  slug: epic
- description: Image data gathered by NASA's Curiosity, Opportunity, Perseverance, and Spirit rovers on Mars, accessible through this API.
  name: Mars Rover Photos
  slug: mars-rover-photos
- description: The NASA Image and Video Library API exposes the public NASA media library content including imagery, video, and audio.
  name: NASA Image and Video Library
  slug: nasa-image-library
- description: The TLE API provides up to date two line element set records, the standardized format for distributing earth-orbiting object orbital data.
  name: TLE - Two Line Element Set
  slug: tle
- description: Programmatic access to NASA's Exoplanet Archive database of confirmed exoplanets and planet candidates.
  name: Exoplanet Archive API
  slug: exoplanet
- description: Per-Sol summary data for each of the last seven available Sols (Martian days) from the InSight lander on Mars.
  name: InSight - Mars Weather Service
  slug: insight
- description: RESTful web services to make NASA technology project data available in a machine readable format.
  name: TechPort
  slug: techport
- description: Provides access to a number of resources from the Solar System Dynamics group and the Center for Near-Earth Object Studies.
  name: SSD/CNEOS - Solar System Dynamics and Center for Near-Earth Object Studies
  slug: ssd-cneos
common:
- title: ''
  type: Portal
  url: https://api.nasa.gov/
- title: ''
  type: Website
  url: https://www.nasa.gov/
- title: ''
  type: SignUp
  url: https://api.nasa.gov/#signUp
- title: ''
  type: TermsOfService
  url: https://www.nasa.gov/about/highlights/HP_Privacy.html
created: '2024-01-01'
description: NASA explores the unknown in air and space, innovates for the benefit of humanity, and inspires the world through discovery. The api.nasa.gov portal hosts a federated set of APIs that make NASA imagery, science, and mission data accessible to application developers.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: The National Aeronautics and Space Administration
skills: []
slug: national-aeronautics-and-space-administration
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: national-aeronautics-and-space-administration\nname: The National Aeronautics and Space Administration\ndescription: >-\n  NASA explores the unknown in air and space, innovates for the benefit of\n  humanity, and inspires the world through discovery. The api.nasa.gov portal\n  hosts a federated set of APIs that make NASA imagery, science, and mission\n  data accessible to application developers.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://api.nasa.gov/\ncreated: '2024-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Government\n  - Science\n  - Space\n  - Imagery\n  - Earth Observation\napis:\n  - aid: national-aeronautics-and-space-administration:apod\n    name: APOD - Astronomy Picture of the Day\n    description: >-\n      One of the most popular websites at NASA is the Astronomy Picture of the\n      Day. This API exposes the same featured image with metadata.\n    humanURL: https://api.nasa.gov/\n\
  \    baseURL: https://api.nasa.gov/planetary/apod\n    tags:\n      - Astronomy\n      - Imagery\n    properties:\n      - type: Documentation\n        url: https://api.nasa.gov/\n      - type: SourceCode\n        url: https://github.com/nasa/apod-api\n  - aid: national-aeronautics-and-space-administration:neows\n    name: NeoWs - Near Earth Object Web Service\n    description: >-\n      Near Earth Object Web Service is a RESTful web service for near earth\n      Asteroid information including closest approach data and orbital data.\n    humanURL: https://api.nasa.gov/\n    baseURL: https://api.nasa.gov/neo/rest/v1\n    tags:\n      - Asteroids\n      - Space\n    properties:\n      - type: Documentation\n        url: https://api.nasa.gov/\n      - type: SourceCode\n        url: https://github.com/SpaceRocks/NeoWs\n  - aid: national-aeronautics-and-space-administration:donki\n    name: DONKI - Space Weather Database Of Notifications, Knowledge, Information\n    description: >-\n      The\
  \ Space Weather Database Of Notifications, Knowledge, Information\n      (DONKI) is a comprehensive online tool for space weather forecasters,\n      scientists, and researchers.\n    humanURL: https://api.nasa.gov/\n    baseURL: https://api.nasa.gov/DONKI\n    tags:\n      - Space Weather\n      - Science\n    properties:\n      - type: Documentation\n        url: https://api.nasa.gov/\n  - aid: national-aeronautics-and-space-administration:earth\n    name: Earth Imagery and Assets\n    description: >-\n      Earth imagery API providing Landsat 8 imagery and asset metadata for a\n      given lat/lon location and date.\n    humanURL: https://api.nasa.gov/\n    baseURL: https://api.nasa.gov/planetary/earth\n    tags:\n      - Earth Observation\n      - Imagery\n    properties:\n      - type: Documentation\n        url: https://api.nasa.gov/\n  - aid: national-aeronautics-and-space-administration:eonet\n    name: EONET - Earth Observatory Natural Event Tracker\n    description: >-\n    \
  \  EONET is a prototype web service that provides a curated source of\n      continuously updated natural event metadata.\n    humanURL: https://eonet.gsfc.nasa.gov/\n    baseURL: https://eonet.gsfc.nasa.gov/api/v3\n    tags:\n      - Earth Observation\n      - Natural Events\n    properties:\n      - type: Documentation\n        url: https://eonet.gsfc.nasa.gov/docs/v3\n  - aid: national-aeronautics-and-space-administration:epic\n    name: EPIC - Earth Polychromatic Imaging Camera\n    description: >-\n      The EPIC API provides full disc imagery of the Earth captured by the\n      DSCOVR spacecraft, including natural and enhanced color images.\n    humanURL: https://epic.gsfc.nasa.gov/\n    baseURL: https://api.nasa.gov/EPIC/api\n    tags:\n      - Earth Observation\n      - Imagery\n    properties:\n      - type: Documentation\n        url: https://epic.gsfc.nasa.gov/about/api\n  - aid: national-aeronautics-and-space-administration:mars-rover-photos\n    name: Mars Rover Photos\n \
  \   description: >-\n      Image data gathered by NASA's Curiosity, Opportunity, Perseverance, and\n      Spirit rovers on Mars, accessible through this API.\n    humanURL: https://api.nasa.gov/\n    baseURL: https://api.nasa.gov/mars-photos/api/v1\n    tags:\n      - Mars\n      - Imagery\n      - Rover\n    properties:\n      - type: Documentation\n        url: https://api.nasa.gov/\n      - type: SourceCode\n        url: https://github.com/chrisccerami/mars-photo-api\n  - aid: national-aeronautics-and-space-administration:nasa-image-library\n    name: NASA Image and Video Library\n    description: >-\n      The NASA Image and Video Library API exposes the public NASA media\n      library content including imagery, video, and audio.\n    humanURL: https://images.nasa.gov/\n    baseURL: https://images-api.nasa.gov\n    tags:\n      - Imagery\n      - Video\n      - Media\n    properties:\n      - type: Documentation\n        url: https://images.nasa.gov/docs/images.nasa.gov_api_docs.pdf\n\
  \  - aid: national-aeronautics-and-space-administration:tle\n    name: TLE - Two Line Element Set\n    description: >-\n      The TLE API provides up to date two line element set records, the\n      standardized format for distributing earth-orbiting object orbital data.\n    humanURL: https://tle.ivanstanojevic.me/\n    baseURL: https://tle.ivanstanojevic.me/api\n    tags:\n      - Satellites\n      - Orbital Data\n    properties:\n      - type: Documentation\n        url: https://tle.ivanstanojevic.me/\n  - aid: national-aeronautics-and-space-administration:exoplanet\n    name: Exoplanet Archive API\n    description: >-\n      Programmatic access to NASA's Exoplanet Archive database of confirmed\n      exoplanets and planet candidates.\n    humanURL: https://exoplanetarchive.ipac.caltech.edu/\n    baseURL: https://exoplanetarchive.ipac.caltech.edu/TAP\n    tags:\n      - Exoplanets\n      - Astronomy\n    properties:\n      - type: Documentation\n        url: https://exoplanetarchive.ipac.caltech.edu/docs/program_interfaces.html\n\
  \  - aid: national-aeronautics-and-space-administration:insight\n    name: InSight - Mars Weather Service\n    description: >-\n      Per-Sol summary data for each of the last seven available Sols (Martian\n      days) from the InSight lander on Mars.\n    humanURL: https://api.nasa.gov/\n    baseURL: https://api.nasa.gov/insight_weather\n    tags:\n      - Mars\n      - Weather\n    properties:\n      - type: Documentation\n        url: https://api.nasa.gov/\n  - aid: national-aeronautics-and-space-administration:techport\n    name: TechPort\n    description: >-\n      RESTful web services to make NASA technology project data available in a\n      machine readable format.\n    humanURL: https://techport.nasa.gov/\n    baseURL: https://api.nasa.gov/techport/api\n    tags:\n      - Technology\n      - Research\n    properties:\n      - type: Documentation\n        url: https://techport.nasa.gov/api\n  - aid: national-aeronautics-and-space-administration:ssd-cneos\n    name: SSD/CNEOS -\
  \ Solar System Dynamics and Center for Near-Earth Object Studies\n    description: >-\n      Provides access to a number of resources from the Solar System Dynamics\n      group and the Center for Near-Earth Object Studies.\n    humanURL: https://ssd-api.jpl.nasa.gov/\n    baseURL: https://ssd-api.jpl.nasa.gov\n    tags:\n      - Solar System\n      - Asteroids\n      - Comets\n    properties:\n      - type: Documentation\n        url: https://ssd-api.jpl.nasa.gov/doc/\ncommon:\n  - type: Portal\n    url: https://api.nasa.gov/\n  - type: Website\n    url: https://www.nasa.gov/\n  - type: SignUp\n    url: https://api.nasa.gov/#signUp\n  - type: TermsOfService\n    url: https://www.nasa.gov/about/highlights/HP_Privacy.html\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/national-aeronautics-and-space-administration/refs/heads/main/apis.yml
tags:
- Government
- Science
- Space
- Imagery
- Earth Observation
url: https://api.nasa.gov/
use_cases: []
---
