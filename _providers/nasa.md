---
api_count: 6
api_specs:
- filename: nasa-apod-openapi.yml
  format: yaml
  label: NASA Astronomy Picture of the Day (APOD) API
  slug: apod
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-apod-openapi.yml
- filename: nasa-mars-rover-photos-openapi.yml
  format: yaml
  label: NASA Mars Rover Photos API
  slug: mars-rover-photos
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-mars-rover-photos-openapi.yml
- filename: nasa-neo-openapi.yml
  format: yaml
  label: NASA NeoWs (Near Earth Object Web Service) API
  slug: neo
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-neo-openapi.yml
- filename: nasa-donki-openapi.yml
  format: yaml
  label: NASA DONKI (Space Weather) API
  slug: donki
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-donki-openapi.yml
- filename: nasa-epic-openapi.yml
  format: yaml
  label: NASA EPIC (Earth Polychromatic Imaging Camera) API
  slug: epic
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-epic-openapi.yml
- filename: nasa-nasa-image-and-video-library-openapi.yml
  format: yaml
  label: NASA Image and Video Library API
  slug: image-and-video-library
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-nasa-image-and-video-library-openapi.yml
apis:
- description: The Astronomy Picture of the Day API provides access to NASA's popular APOD service, returning the astronomy picture or video of the day along with an explanation written by a professional astronomer.
  name: NASA Astronomy Picture of the Day (APOD) API
  slug: apod
- description: The Mars Rover Photos API provides access to images collected by NASA's Curiosity, Opportunity, and Spirit rovers on Mars.
  name: NASA Mars Rover Photos API
  slug: mars-rover-photos
- description: NeoWs is a RESTful web service for near-Earth asteroid information sourced from the NASA JPL Asteroid team.
  name: NASA NeoWs (Near Earth Object Web Service) API
  slug: neo
- description: The DONKI API provides access to space weather events and notifications from NASA's Space Weather Database Of Notifications, Knowledge, Information.
  name: NASA DONKI (Space Weather) API
  slug: donki
- description: The EPIC API provides access to imagery from NASA's Earth Polychromatic Imaging Camera onboard the DSCOVR spacecraft.
  name: NASA EPIC (Earth Polychromatic Imaging Camera) API
  slug: epic
- description: The NASA Image and Video Library API provides access to NASA's media archive including images, videos, and audio.
  name: NASA Image and Video Library API
  slug: image-and-video-library
common:
- title: ''
  type: Portal
  url: https://api.nasa.gov
- title: ''
  type: Website
  url: https://www.nasa.gov
- title: ''
  type: Documentation
  url: https://data.nasa.gov
- title: ''
  type: GitHub Organization
  url: https://github.com/nasa
created: '2025-01-01'
description: NASA (National Aeronautics and Space Administration) provides a suite of public APIs at api.nasa.gov offering access to space, Earth science, and aeronautics data. Key APIs include Astronomy Picture of the Day (APOD), Mars Rover Photos, Near Earth Object Web Service (NeoWs), DONKI space weather events, EPIC Earth imagery, and the NASA Image and Video Library. All APIs are free and accessible with an API key.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 35
  name: Nasa Context
  property_count: 0
  slug: nasa-context
layout: provider
modified: '2026-04-28'
name: NASA
skills: []
slug: nasa
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: nasa\nname: NASA\ndescription: >-\n  NASA (National Aeronautics and Space Administration) provides a suite of\n  public APIs at api.nasa.gov offering access to space, Earth science, and\n  aeronautics data. Key APIs include Astronomy Picture of the Day (APOD),\n  Mars Rover Photos, Near Earth Object Web Service (NeoWs), DONKI space\n  weather events, EPIC Earth imagery, and the NASA Image and Video Library.\n  All APIs are free and accessible with an API key.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/apis.yml\ncreated: '2025-01-01'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\ntags:\n  - Government\n  - Science\n  - Space\napis:\n  - aid: nasa:apod\n    name: NASA Astronomy Picture of the Day (APOD) API\n    tags:\n      - Astronomy\n      - Images\n      - Space\n    humanURL: https://api.nasa.gov/#apod\n    properties:\n      - url:\
  \ https://api.nasa.gov/#apod\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-apod-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Astronomy Picture of the Day API provides access to NASA's popular\n      APOD service, returning the astronomy picture or video of the day along\n      with an explanation written by a professional astronomer.\n  - aid: nasa:mars-rover-photos\n    name: NASA Mars Rover Photos API\n    tags:\n      - Images\n      - Mars\n      - Rovers\n      - Space\n    humanURL: https://api.nasa.gov/#MarsPhotos\n    properties:\n      - url: https://api.nasa.gov/#MarsPhotos\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-mars-rover-photos-openapi.yml\n        type: OpenAPI\n    description: >-\n      The Mars Rover Photos API provides access to images collected by NASA's\n      Curiosity, Opportunity,\
  \ and Spirit rovers on Mars.\n  - aid: nasa:neo\n    name: NASA NeoWs (Near Earth Object Web Service) API\n    tags:\n      - Asteroids\n      - Near Earth Objects\n      - Space\n    humanURL: https://api.nasa.gov/#NeoWS\n    properties:\n      - url: https://api.nasa.gov/#NeoWS\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-neo-openapi.yml\n        type: OpenAPI\n    description: >-\n      NeoWs is a RESTful web service for near-Earth asteroid information sourced\n      from the NASA JPL Asteroid team.\n  - aid: nasa:donki\n    name: NASA DONKI (Space Weather) API\n    tags:\n      - Solar\n      - Space\n      - Space Weather\n    humanURL: https://api.nasa.gov/#DONKI\n    properties:\n      - url: https://api.nasa.gov/#DONKI\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-donki-openapi.yml\n        type: OpenAPI\n    description:\
  \ >-\n      The DONKI API provides access to space weather events and notifications\n      from NASA's Space Weather Database Of Notifications, Knowledge, Information.\n  - aid: nasa:epic\n    name: NASA EPIC (Earth Polychromatic Imaging Camera) API\n    tags:\n      - Earth\n      - Images\n      - Space\n    humanURL: https://api.nasa.gov/#EPIC\n    properties:\n      - url: https://api.nasa.gov/#EPIC\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-epic-openapi.yml\n        type: OpenAPI\n    description: >-\n      The EPIC API provides access to imagery from NASA's Earth Polychromatic\n      Imaging Camera onboard the DSCOVR spacecraft.\n  - aid: nasa:image-and-video-library\n    name: NASA Image and Video Library API\n    tags:\n      - Images\n      - Media\n      - Space\n      - Video\n    humanURL: https://api.nasa.gov/#Images\n    properties:\n      - url: https://api.nasa.gov/#Images\n        type:\
  \ Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/openapi/nasa-nasa-image-and-video-library-openapi.yml\n        type: OpenAPI\n    description: >-\n      The NASA Image and Video Library API provides access to NASA's media\n      archive including images, videos, and audio.\ncommon:\n  - url: https://api.nasa.gov\n    type: Portal\n  - url: https://www.nasa.gov\n    type: Website\n  - url: https://data.nasa.gov\n    type: Documentation\n  - url: https://github.com/nasa\n    type: GitHub Organization\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/apis.yml
tags:
- Government
- Science
- Space
url: https://raw.githubusercontent.com/api-evangelist/nasa/refs/heads/main/apis.yml
use_cases: []
---
