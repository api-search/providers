---
api_count: 2
apis:
- description: The BPA GIS Data Hub provides publicly available geospatial data from Bonneville Power Administration. The hub is built on ArcGIS and supports data downloads in multiple formats including CSV, KML, Ge
  name: BPA GIS Data Hub API
  slug: gis-data-api
- description: BPA publishes real-time and historical wind and solar generation data for the Balancing Authority area. Data includes total wind generation, total solar generation, net generation, and load data avail
  name: BPA Wind and Solar Generation Data
  slug: wind-solar-data
common:
- title: ''
  type: Website
  url: https://www.bpa.gov
- title: ''
  type: About
  url: https://www.bpa.gov/about/
- title: ''
  type: OpenData
  url: https://data-bpagis.hub.arcgis.com
- title: ''
  type: DataDownload
  url: https://transmission.bpa.gov/business/operations/Wind/
- title: ''
  type: CustomerPortal
  url: https://www.bpa.gov/energy-and-services/
- title: ''
  type: Contact
  url: https://www.bpa.gov/about/contact/
created: '2024-11-25'
description: The Bonneville Power Administration (BPA) is a federal agency within the U.S. Department of Energy that markets wholesale electrical power from federal hydroelectric projects in the Pacific Northwest. BPA also operates and maintains about three-quarters of the high-voltage transmission in the Pacific Northwest. The agency provides publicly available GIS data, energy statistics, and operational data through its data hub and web services.
features:
- features:
  - ArcGIS REST API
  - GeoJSON Export
  - CSV Export
  - KML Export
  - GeoTIFF Export
  - Web Map Service (WMS)
  - Web Feature Service (WFS)
  name: GeoServices API
  url: https://data-bpagis.hub.arcgis.com
- features:
  - CSV Download
  - JSON Download
  - GeoJSON Download
  - Shapefile Download
  - KML Download
  name: Open Data Downloads
  url: https://data-bpagis.hub.arcgis.com
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-19'
name: Bonneville Power Administration
skills: []
slug: bonneville-power-administration
solutions: []
source_filename: apis.yml
source_yaml: "aid: bonneville-power-administration\nname: Bonneville Power Administration\ndescription: >-\n  The Bonneville Power Administration (BPA) is a federal agency within the U.S.\n  Department of Energy that markets wholesale electrical power from federal hydroelectric\n  projects in the Pacific Northwest. BPA also operates and maintains about three-quarters\n  of the high-voltage transmission in the Pacific Northwest. The agency provides publicly\n  available GIS data, energy statistics, and operational data through its data hub and\n  web services.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bonneville-power-administration/refs/heads/main/apis.yml\ncreated: '2024-11-25'\nmodified: '2026-04-19'\nspecificationVersion: '0.19'\ntags:\n  - Energy\n  - Federal Government\n  - GIS\n  - Hydroelectric\n  - Pacific Northwest\n  - Power\n  - Transmission\n  - Wind\napis:\n  - aid: bonneville-power-administration:gis-data-api\n\
  \    name: BPA GIS Data Hub API\n    tags:\n      - ArcGIS\n      - GeoServices\n      - GIS\n      - Government\n      - Geospatial\n      - WFS\n      - WMS\n    humanURL: https://data-bpagis.hub.arcgis.com\n    properties:\n      - url: https://data-bpagis.hub.arcgis.com\n        type: Documentation\n      - url: https://data-bpagis.hub.arcgis.com/datasets/998ba568128d46c0a38e285235b55d0c_0/geoservice\n        type: GeoService\n    description: >-\n      The BPA GIS Data Hub provides publicly available geospatial data from Bonneville\n      Power Administration. The hub is built on ArcGIS and supports data downloads in\n      multiple formats including CSV, KML, GeoJSON, GeoTIFF, and PNG. Developer API\n      access is available through GeoServices (ArcGIS REST API), WMS (Web Map Service),\n      and WFS (Web Feature Service) endpoints. Datasets include BPA service area boundaries,\n      transmission infrastructure, and energy facility data.\n  - aid: bonneville-power-administration:wind-solar-data\n\
  \    name: BPA Wind and Solar Generation Data\n    tags:\n      - Energy\n      - Government\n      - Renewable Energy\n      - Solar\n      - Statistics\n      - Wind\n    humanURL: https://transmission.bpa.gov/business/operations/Wind/\n    properties:\n      - url: https://transmission.bpa.gov/business/operations/Wind/\n        type: Documentation\n      - url: https://transmission.bpa.gov/business/operations/Wind/twndbspt.aspx\n        type: DataAPI\n    description: >-\n      BPA publishes real-time and historical wind and solar generation data for\n      the Balancing Authority area. Data includes total wind generation, total solar\n      generation, net generation, and load data available for download. The data\n      is used for grid operations planning and renewable energy tracking.\ncommon:\n  - type: Website\n    url: https://www.bpa.gov\n  - type: About\n    url: https://www.bpa.gov/about/\n  - type: OpenData\n    url: https://data-bpagis.hub.arcgis.com\n  - type: DataDownload\n\
  \    url: https://transmission.bpa.gov/business/operations/Wind/\n  - type: CustomerPortal\n    url: https://www.bpa.gov/energy-and-services/\n  - type: Contact\n    url: https://www.bpa.gov/about/contact/\n  - name: Use Cases\n    type: UseCases\n    data:\n      - name: GIS Data Analysis\n        url: https://data-bpagis.hub.arcgis.com\n        features:\n          - Geospatial Data Download\n          - Map Visualization\n          - Service Area Data\n          - Transmission Infrastructure Mapping\n          - Energy Facility Locations\n      - name: Renewable Energy Monitoring\n        url: https://transmission.bpa.gov/business/operations/Wind/\n        features:\n          - Wind Generation Data\n          - Solar Generation Data\n          - Real-Time Generation Monitoring\n          - Historical Data Access\n          - Grid Load Tracking\n      - name: Transmission System Monitoring\n        url: https://www.bpa.gov/energy-and-services/transmission/\n        features:\n     \
  \     - Transmission Availability\n          - Hourly Firm Data\n          - System Load Monitoring\n          - Grid Operations Data\n  - name: Features\n    type: Features\n    data:\n      - name: GeoServices API\n        url: https://data-bpagis.hub.arcgis.com\n        features:\n          - ArcGIS REST API\n          - GeoJSON Export\n          - CSV Export\n          - KML Export\n          - GeoTIFF Export\n          - Web Map Service (WMS)\n          - Web Feature Service (WFS)\n      - name: Open Data Downloads\n        url: https://data-bpagis.hub.arcgis.com\n        features:\n          - CSV Download\n          - JSON Download\n          - GeoJSON Download\n          - Shapefile Download\n          - KML Download\nmaintainers:\n  - FN: Kin Lane\n    email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bonneville-power-administration/refs/heads/main/apis.yml
tags:
- Energy
- Federal Government
- GIS
- Hydroelectric
- Pacific Northwest
- Power
- Transmission
- Wind
url: https://raw.githubusercontent.com/api-evangelist/bonneville-power-administration/refs/heads/main/apis.yml
use_cases:
- features:
  - Geospatial Data Download
  - Map Visualization
  - Service Area Data
  - Transmission Infrastructure Mapping
  - Energy Facility Locations
  name: GIS Data Analysis
  url: https://data-bpagis.hub.arcgis.com
- features:
  - Wind Generation Data
  - Solar Generation Data
  - Real-Time Generation Monitoring
  - Historical Data Access
  - Grid Load Tracking
  name: Renewable Energy Monitoring
  url: https://transmission.bpa.gov/business/operations/Wind/
- features:
  - Transmission Availability
  - Hourly Firm Data
  - System Load Monitoring
  - Grid Operations Data
  name: Transmission System Monitoring
  url: https://www.bpa.gov/energy-and-services/transmission/
---
