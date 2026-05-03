---
api_count: 6
api_specs:
- filename: usgs-earthquake-catalog-openapi.yml
  format: yaml
  label: USGS Earthquake Catalog API
  slug: earthquake-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/openapi/usgs-earthquake-catalog-openapi.yml
- filename: openapi
  format: yaml
  label: USGS Water Data OGC API
  slug: water-data-api
  spec_type: OpenAPI
  url: https://api.waterdata.usgs.gov/ogcapi/v0/openapi?f=json
apis:
- description: The USGS Earthquake Catalog API implements the FDSN Event Web Service Specification, providing real-time and historical access to global earthquake data from the USGS National Earthquake Information C
  name: USGS Earthquake Catalog API
  slug: earthquake-catalog-api
- description: The USGS Water Data OGC APIs provide OGC-compliant interfaces to USGS water data including real-time continuous measurements from automated sensor networks, daily summary values, field measurements, a
  name: USGS Water Data OGC API
  slug: water-data-api
- description: The USGS ScienceBase Catalog API provides access to USGS scientific data management infrastructure, enabling upload, documentation, sharing, and dynamic data services for USGS research datasets and sc
  name: USGS ScienceBase Catalog API
  slug: sciencebase-api
- description: The USGS Geomagnetism Web Service provides programmatic access to geomagnetic data collected by USGS magnetic observatories across the United States and territories, supporting navigation, space weath
  name: USGS Geomagnetism Web Service
  slug: geomagnetism-api
- description: The USGS Seismic Design Data Web Services provide parameter values from seismic design reference documents for building and infrastructure design, supporting compliance with ASCE 7 and other engineeri
  name: USGS Seismic Design Data Web Services
  slug: seismic-design-api
- description: The USGS National Map services provide geospatial data and elevation products via OGC web services, REST APIs, and download services covering topographic data, imagery, hydrography, boundaries, transp
  name: USGS National Map Services
  slug: national-map-api
capabilities:
- description: Workflow capability for USGS earth science monitoring combining earthquake catalog data and water resources data. Supports hazard assessment, natural disaster response, environmental monitoring, and s
  name: USGS Earth Science Monitoring
  slug: earth-science-monitoring
common: []
created: '2024-12-03'
description: The US Geological Survey is a scientific agency of the United States government that conducts research on the natural resources, natural hazards, and environmental health of the United States. The USGS is responsible for monitoring and assessing the country's water, energy, mineral, and biological resources, as well as investigating geological hazards such as earthquakes, volcanoes, landslides, and floods. USGS provides a broad portfolio of public REST APIs covering earthquake data, water resources, geomagnetism, mapping, seismic design, and scientific data catalogs - all available without cost as US Government works.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 22
  name: Us Geological Survey Context
  property_count: 6
  slug: us-geological-survey-context
layout: provider
modified: '2026-05-03'
name: US Geological Survey
rules:
- name: US Geological Survey API Rules
  rule_count: 10
  severity_counts:
    error: 2
    hint: 0
    info: 4
    warn: 4
  slug: usgs-earthquake-api-rules
skills: []
slug: us-geological-survey
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: us-geological-survey\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/apis.yml\napis:\n  - aid: us-geological-survey:earthquake-catalog-api\n    name: USGS Earthquake Catalog API\n    tags:\n      - Earthquakes\n      - Seismology\n      - Hazards\n      - Federal Government\n    humanURL: https://earthquake.usgs.gov/fdsnws/event/1/\n    properties:\n      - url: https://earthquake.usgs.gov/fdsnws/event/1/\n        type: Documentation\n      - url: https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/openapi/usgs-earthquake-catalog-openapi.yml\n        type: OpenAPI\n    description: >-\n      The USGS Earthquake Catalog API implements the FDSN Event Web Service\n      Specification, providing real-time and historical access to global\n      earthquake data from the USGS National Earthquake Information Center.\n      Query by time, location, magnitude, depth, and other parameters. Returns\n\
  \      data in GeoJSON, QuakeML, KML, CSV, or text formats. No authentication\n      required.\n\n  - aid: us-geological-survey:water-data-api\n    name: USGS Water Data OGC API\n    tags:\n      - Water Data\n      - Hydrology\n      - Streamflow\n      - Federal Government\n    humanURL: https://api.waterdata.usgs.gov\n    properties:\n      - url: https://api.waterdata.usgs.gov\n        type: Documentation\n      - url: https://api.waterdata.usgs.gov/ogcapi/v0/openapi?f=json\n        type: OpenAPI\n      - url: https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/openapi/usgs-water-data-openapi.yml\n        type: OpenAPI\n    description: >-\n      The USGS Water Data OGC APIs provide OGC-compliant interfaces to USGS\n      water data including real-time continuous measurements from automated\n      sensor networks, daily summary values, field measurements, and monitoring\n      location metadata. Covers streamflow, gage height, groundwater levels,\n\
  \      water quality, and hundreds of other parameters. API key required.\n      Legacy WaterServices decommissioning in Q1 2027.\n\n  - aid: us-geological-survey:sciencebase-api\n    name: USGS ScienceBase Catalog API\n    tags:\n      - Scientific Data\n      - Research\n      - Catalog\n      - Federal Government\n    humanURL: https://www.sciencebase.gov/catalog/\n    properties:\n      - url: https://www.sciencebase.gov/catalog/\n        type: Documentation\n      - url: https://www.sciencebase.gov/catalog/swagger-ui.html\n        type: SwaggerUI\n    description: >-\n      The USGS ScienceBase Catalog API provides access to USGS scientific\n      data management infrastructure, enabling upload, documentation, sharing,\n      and dynamic data services for USGS research datasets and scientific\n      publications.\n\n  - aid: us-geological-survey:geomagnetism-api\n    name: USGS Geomagnetism Web Service\n    tags:\n      - Geomagnetism\n      - Magnetic Data\n      - Federal Government\n\
  \    humanURL: https://www.usgs.gov/tools/web-service-geomagnetism-data\n    properties:\n      - url: https://www.usgs.gov/tools/web-service-geomagnetism-data\n        type: Documentation\n      - url: https://geomag.usgs.gov/ws/edge/\n        type: BaseURL\n    description: >-\n      The USGS Geomagnetism Web Service provides programmatic access to\n      geomagnetic data collected by USGS magnetic observatories across the\n      United States and territories, supporting navigation, space weather,\n      and geophysical research.\n\n  - aid: us-geological-survey:seismic-design-api\n    name: USGS Seismic Design Data Web Services\n    tags:\n      - Seismic Design\n      - Engineering\n      - Hazards\n      - Federal Government\n    humanURL: https://earthquake.usgs.gov/ws/designmaps/\n    properties:\n      - url: https://earthquake.usgs.gov/ws/designmaps/\n        type: Documentation\n    description: >-\n      The USGS Seismic Design Data Web Services provide parameter values from\n\
  \      seismic design reference documents for building and infrastructure design,\n      supporting compliance with ASCE 7 and other engineering standards.\n\n  - aid: us-geological-survey:national-map-api\n    name: USGS National Map Services\n    tags:\n      - Mapping\n      - Geospatial\n      - Topography\n      - Federal Government\n    humanURL: https://apps.nationalmap.gov/api/\n    properties:\n      - url: https://apps.nationalmap.gov/api/\n        type: Documentation\n    description: >-\n      The USGS National Map services provide geospatial data and elevation\n      products via OGC web services, REST APIs, and download services covering\n      topographic data, imagery, hydrography, boundaries, transportation,\n      structures, and land cover for the United States.\n\nname: US Geological Survey\ntags:\n  - Federal Government\n  - Earth Science\n  - Earthquakes\n  - Water Data\n  - Geospatial\n  - Hazards\n  - Environment\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: 3rd-Party\ncreated: '2024-12-03'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The US Geological Survey is a scientific agency of the United States government\n  that conducts research on the natural resources, natural hazards, and environmental\n  health of the United States. The USGS is responsible for monitoring and assessing\n  the country's water, energy, mineral, and biological resources, as well as\n  investigating geological hazards such as earthquakes, volcanoes, landslides,\n  and floods. USGS provides a broad portfolio of public REST APIs covering\n  earthquake data, water resources, geomagnetism, mapping, seismic design, and\n  scientific data catalogs - all available without cost as US Government works.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/apis.yml
tags:
- Federal Government
- Earth Science
- Earthquakes
- Water Data
- Geospatial
- Hazards
- Environment
url: https://raw.githubusercontent.com/api-evangelist/us-geological-survey/refs/heads/main/apis.yml
use_cases: []
---
