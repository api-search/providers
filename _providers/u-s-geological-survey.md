---
api_count: 7
api_specs:
- filename: usgs-earthquake-api-openapi.yaml
  format: yaml
  label: Earthquake Notifications, Feeds, and Web Services
  slug: earthquake-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/openapi/usgs-earthquake-api-openapi.yaml
- filename: usgs-water-data-api-openapi.yaml
  format: yaml
  label: USGS Water Data APIs
  slug: water-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/openapi/usgs-water-data-api-openapi.yaml
apis:
- description: The USGS Earthquake Hazards Program provides real-time notifications and historical earthquake data through the FDSN Event Web Service. Search the ANSS ComCat earthquake catalog by geography, time, ma
  name: Earthquake Notifications, Feeds, and Web Services
  slug: earthquake-api
- description: The USGS Water Data OGC APIs provide standardized access to USGS water monitoring data including continuous streamflow, daily values, groundwater levels, discrete water quality measurements, and monit
  name: USGS Water Data APIs
  slug: water-data-api
- description: The USGS Asset Identifier Service (AIS) allows USGS personnel to reserve, register, publish, and manage USGS persistent identifiers to make research more Findable, Accessible, Interoperable, and Reusa
  name: Asset Identifier Service (AIS)
  slug: asset-identifier-service-ais
- description: Web services produced by the U.S. Geological Survey for calculating parameter values from various seismic design reference documents for engineering and construction purposes.
  name: Seismic Design Web Service
  slug: seismic-design-web-service
- description: ScienceBase is a USGS Trusted Digital Repository that provides permission-controlled and public access to scientific data products through a REST API supporting upload, documentation, and sharing of r
  name: ScienceBase
  slug: sciencebase
- description: The StreamStats Web Services provide HTTP-accessible hydrological analysis services for delineating drainage areas, estimating peak flows, and computing basin characteristics for water resources plann
  name: StreamStats Web Services
  slug: streamstats-web-services
- description: The original USGS NWIS water services API providing streamflow, groundwater, water quality, and site information via REST protocol in XML and other media types. High availability and fault-tolerant de
  name: USGS Water Services (Legacy)
  slug: usgs-water-services
capabilities:
- description: Workflow capability for geoscientists, emergency managers, hydrologists, and researchers to access USGS real-time earthquake data and water monitoring data. Combines the USGS Earthquake API and USGS W
  name: USGS Geoscience Data Access
  slug: geoscience-data-access
common:
- title: ''
  type: Website
  url: https://www.usgs.gov/
- title: ''
  type: GitHubOrganization
  url: https://github.com/usgs
- title: ''
  type: Documentation
  url: https://www.usgs.gov/products/web-tools/apis
- title: ''
  type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/rules/usgs-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/vocabulary/u-s-geological-survey-vocabulary.yaml
- title: Geoscience Data Access
  type: NaftikoCapability
  url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/capabilities/geoscience-data-access.yaml
created: '2024-11-14'
description: The U.S. Geological Survey (USGS) is a scientific agency of the U.S. government that conducts research and provides data on the natural resources and hazards of the United States. The USGS is known for its work in mapping and monitoring earthquakes, volcanoes, and landslides to help mitigate risks and protect communities. USGS also studies water resources including streamflow, groundwater, and water quality through a nationwide network of monitoring stations. Their public APIs provide programmatic access to real-time earthquake data, water monitoring observations, seismic design parameters, and geospatial data products.
features:
- description: Search the USGS ANSS ComCat earthquake catalog by geography, time, magnitude, depth, and event type with 20,000 event limit per query.
  name: Earthquake Catalog Query
- description: Access near real-time earthquake data updated within minutes of events occurring anywhere in the world.
  name: Real-Time Earthquake Data
- description: Query USGS stream gages, groundwater wells, and other water quality monitoring stations by state, watershed, or geographic area.
  name: Water Monitoring Locations
- description: Retrieve continuous and daily water data including streamflow, stage, temperature, and water quality parameters.
  name: Water Data Time Series
- description: USGS Water Data APIs implement OGC API Features standard supporting CQL2 filtering, spatial queries, and standardized output formats.
  name: OGC API Compliance
- description: All spatial data returned in GeoJSON format compatible with mapping libraries and geospatial analysis tools.
  name: GeoJSON Output
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Open-source tools including libcomcat, rcomcat, and other clients for accessing USGS earthquake and water data.
  name: USGS GitHub Organization
- description: The flagship USGS water data portal at waterdata.usgs.gov providing maps and tools built on the NWIS water services API.
  name: USGS Water Data for the Nation
- description: Legacy USGS water data system providing the underlying data for Water Data APIs with millions of site records.
  name: National Water Information System (NWIS)
- description: USGS earthquake API implements FDSN (International Federation of Digital Seismograph Networks) web service specifications.
  name: FDSN Standards
jsonld:
- class_count: 6
  name: Usgs Earthquake Api Context
  property_count: 35
  slug: usgs-earthquake-api-context
- class_count: 12
  name: Usgs Water Data Api Context
  property_count: 30
  slug: usgs-water-data-api-context
layout: provider
modified: '2026-05-03'
name: U.S. Geological Survey
rules:
- name: U.S. Geological Survey API Rules
  rule_count: 33
  severity_counts:
    error: 9
    hint: 0
    info: 10
    warn: 14
  slug: usgs-spectral-rules
skills: []
slug: u-s-geological-survey
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: u-s-geological-survey\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/apis.yml\napis:\n  - aid: u-s-geological-survey:earthquake-api\n    name: Earthquake Notifications, Feeds, and Web Services\n    tags:\n      - Earthquakes\n      - Seismic\n      - Geoscience\n    humanURL: https://earthquake.usgs.gov/earthquakes/feed/\n    baseURL: https://earthquake.usgs.gov/fdsnws/event/1\n    properties:\n      - url: https://earthquake.usgs.gov/fdsnws/event/1/\n        type: Documentation\n      - url: https://earthquake.usgs.gov/earthquakes/feed/\n        type: GettingStarted\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/openapi/usgs-earthquake-api-openapi.yaml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/json-schema/usgs-earthquake-api-earthquake-properties-schema.json\n\
  \        type: JSONSchema\n        title: Earthquake Properties Schema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/json-ld/usgs-earthquake-api-context.jsonld\n        type: JSON-LD\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/examples/usgs-earthquake-api-earthquake-properties-example.json\n        type: Example\n        title: Earthquake Properties Example\n    description: >-\n      The USGS Earthquake Hazards Program provides real-time notifications and\n      historical earthquake data through the FDSN Event Web Service. Search the\n      ANSS ComCat earthquake catalog by geography, time, magnitude, and depth.\n      Responses available in GeoJSON, CSV, KML, and QuakeML formats.\n\n  - aid: u-s-geological-survey:water-data-api\n    name: USGS Water Data APIs\n    tags:\n      - Water\n      - Hydrology\n      - Streamflow\n      - Groundwater\n\
  \    humanURL: https://api.waterdata.usgs.gov/\n    baseURL: https://api.waterdata.usgs.gov/ogcapi/v0\n    properties:\n      - url: https://api.waterdata.usgs.gov/docs/\n        type: Documentation\n      - url: https://api.waterdata.usgs.gov/signup/\n        type: Authentication\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/openapi/usgs-water-data-api-openapi.yaml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/json-schema/usgs-water-data-api-monitoring-location-properties-schema.json\n        type: JSONSchema\n        title: Monitoring Location Schema\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/json-schema/usgs-water-data-api-time-series-properties-schema.json\n        type: JSONSchema\n        title: Time Series Properties Schema\n      - url: >-\n       \
  \   https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/json-ld/usgs-water-data-api-context.jsonld\n        type: JSON-LD\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/examples/usgs-water-data-api-monitoring-location-properties-example.json\n        type: Example\n        title: Monitoring Location Example\n    description: >-\n      The USGS Water Data OGC APIs provide standardized access to USGS water\n      monitoring data including continuous streamflow, daily values, groundwater\n      levels, discrete water quality measurements, and monitoring location\n      metadata. Implements OGC API Features standard with spatial and temporal\n      filtering support.\n\n  - aid: u-s-geological-survey:asset-identifier-service-ais\n    name: Asset Identifier Service (AIS)\n    tags:\n      - Identifiers\n      - Research Data\n    humanURL: https://www.usgs.gov/tools/asset-identifier-service-ais\n\
  \    properties:\n      - url: https://www.usgs.gov/tools/asset-identifier-service-ais\n        type: Documentation\n    description: >-\n      The USGS Asset Identifier Service (AIS) allows USGS personnel to reserve,\n      register, publish, and manage USGS persistent identifiers to make research\n      more Findable, Accessible, Interoperable, and Reusable (FAIR).\n\n  - aid: u-s-geological-survey:seismic-design-web-service\n    name: Seismic Design Web Service\n    tags:\n      - Seismic\n      - Engineering\n    humanURL: https://earthquake.usgs.gov/ws/designmaps/\n    properties:\n      - url: https://earthquake.usgs.gov/ws/designmaps/\n        type: Documentation\n    description: >-\n      Web services produced by the U.S. Geological Survey for calculating\n      parameter values from various seismic design reference documents for\n      engineering and construction purposes.\n\n  - aid: u-s-geological-survey:sciencebase\n    name: ScienceBase\n    tags:\n      - Research Data\n\
  \      - Data Repository\n    humanURL: https://www.usgs.gov/tools/sciencebase\n    properties:\n      - url: https://www.usgs.gov/tools/sciencebase\n        type: Documentation\n      - url: https://www.usgs.gov/sciencebase-instructions-and-documentation/api-and-web-services\n        type: Documentation\n        title: ScienceBase API Documentation\n    description: >-\n      ScienceBase is a USGS Trusted Digital Repository that provides\n      permission-controlled and public access to scientific data products\n      through a REST API supporting upload, documentation, and sharing of\n      research data.\n\n  - aid: u-s-geological-survey:streamstats-web-services\n    name: StreamStats Web Services\n    tags:\n      - Hydrology\n      - Streamflow\n      - Statistics\n    humanURL: https://www.usgs.gov/tools/streamstats-web-services\n    properties:\n      - url: https://www.usgs.gov/tools/streamstats-web-services\n        type: Documentation\n    description: >-\n      The StreamStats\
  \ Web Services provide HTTP-accessible hydrological analysis\n      services for delineating drainage areas, estimating peak flows, and\n      computing basin characteristics for water resources planning.\n\n  - aid: u-s-geological-survey:usgs-water-services\n    name: USGS Water Services (Legacy)\n    tags:\n      - Water\n      - Hydrology\n      - Legacy\n    humanURL: https://www.usgs.gov/tools/usgs-water-services\n    properties:\n      - url: https://nwis.waterservices.usgs.gov/\n        type: Documentation\n    description: >-\n      The original USGS NWIS water services API providing streamflow, groundwater,\n      water quality, and site information via REST protocol in XML and other media\n      types. High availability and fault-tolerant design.\n\nname: U.S. Geological Survey\ntags:\n  - Federal Government\n  - Geological\n  - Earth Science\n  - Natural Resources\n  - Earthquake\n  - Water\n  - Hydrology\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  access: 3rd-Party\ncommon:\n  - type: Website\n    url: https://www.usgs.gov/\n  - type: GitHubOrganization\n    url: https://github.com/usgs\n  - type: Documentation\n    url: https://www.usgs.gov/products/web-tools/apis\n  - type: SpectralRules\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/rules/usgs-spectral-rules.yml\n  - type: Vocabulary\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/vocabulary/u-s-geological-survey-vocabulary.yaml\n  - type: NaftikoCapability\n    url: >-\n      https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/capabilities/geoscience-data-access.yaml\n    title: Geoscience Data Access\n  - type: Features\n    data:\n      - name: Earthquake Catalog Query\n        description: >-\n          Search the USGS ANSS ComCat earthquake catalog by geography, time,\n          magnitude, depth, and event type with 20,000\
  \ event limit per query.\n      - name: Real-Time Earthquake Data\n        description: >-\n          Access near real-time earthquake data updated within minutes of\n          events occurring anywhere in the world.\n      - name: Water Monitoring Locations\n        description: >-\n          Query USGS stream gages, groundwater wells, and other water quality\n          monitoring stations by state, watershed, or geographic area.\n      - name: Water Data Time Series\n        description: >-\n          Retrieve continuous and daily water data including streamflow, stage,\n          temperature, and water quality parameters.\n      - name: OGC API Compliance\n        description: >-\n          USGS Water Data APIs implement OGC API Features standard supporting\n          CQL2 filtering, spatial queries, and standardized output formats.\n      - name: GeoJSON Output\n        description: >-\n          All spatial data returned in GeoJSON format compatible with mapping\n          libraries\
  \ and geospatial analysis tools.\n  - type: UseCases\n    data:\n      - name: Earthquake Hazard Monitoring\n        description: >-\n          Emergency managers and scientists monitor real-time earthquake activity\n          for hazard assessment and emergency response planning.\n      - name: Flood Forecasting\n        description: >-\n          Hydrologists use USGS streamflow data for flood prediction, water\n          supply forecasting, and reservoir management.\n      - name: Groundwater Management\n        description: >-\n          Water managers track groundwater level trends for sustainable\n          aquifer management and drought assessment.\n      - name: Environmental Research\n        description: >-\n          Researchers use USGS geological and water data for environmental impact\n          assessments and climate change studies.\n      - name: Engineering Design\n        description: >-\n          Civil engineers use USGS water data and seismic design services for\n\
  \          infrastructure planning and construction.\n  - type: Integrations\n    data:\n      - name: USGS GitHub Organization\n        description: >-\n          Open-source tools including libcomcat, rcomcat, and other clients\n          for accessing USGS earthquake and water data.\n      - name: USGS Water Data for the Nation\n        description: >-\n          The flagship USGS water data portal at waterdata.usgs.gov providing\n          maps and tools built on the NWIS water services API.\n      - name: National Water Information System (NWIS)\n        description: >-\n          Legacy USGS water data system providing the underlying data for\n          Water Data APIs with millions of site records.\n      - name: FDSN Standards\n        description: >-\n          USGS earthquake API implements FDSN (International Federation of\n          Digital Seismograph Networks) web service specifications.\ncreated: '2024-11-14'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n\
  \  The U.S. Geological Survey (USGS) is a scientific agency of the U.S.\n  government that conducts research and provides data on the natural resources\n  and hazards of the United States. The USGS is known for its work in mapping\n  and monitoring earthquakes, volcanoes, and landslides to help mitigate risks\n  and protect communities. USGS also studies water resources including\n  streamflow, groundwater, and water quality through a nationwide network of\n  monitoring stations. Their public APIs provide programmatic access to\n  real-time earthquake data, water monitoring observations, seismic design\n  parameters, and geospatial data products.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/apis.yml
tags:
- Federal Government
- Geological
- Earth Science
- Natural Resources
- Earthquake
- Water
- Hydrology
url: https://raw.githubusercontent.com/api-evangelist/u-s-geological-survey/refs/heads/main/apis.yml
use_cases:
- description: Emergency managers and scientists monitor real-time earthquake activity for hazard assessment and emergency response planning.
  name: Earthquake Hazard Monitoring
- description: Hydrologists use USGS streamflow data for flood prediction, water supply forecasting, and reservoir management.
  name: Flood Forecasting
- description: Water managers track groundwater level trends for sustainable aquifer management and drought assessment.
  name: Groundwater Management
- description: Researchers use USGS geological and water data for environmental impact assessments and climate change studies.
  name: Environmental Research
- description: Civil engineers use USGS water data and seismic design services for infrastructure planning and construction.
  name: Engineering Design
---
