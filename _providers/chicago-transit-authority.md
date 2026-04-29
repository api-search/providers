---
api_count: 4
api_specs:
- filename: cta-train-tracker-openapi.yml
  format: yaml
  label: CTA Train Tracker API
  slug: train-tracker-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/openapi/cta-train-tracker-openapi.yml
- filename: cta-bus-tracker-openapi.yml
  format: yaml
  label: CTA Bus Tracker API
  slug: bus-tracker-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/openapi/cta-bus-tracker-openapi.yml
apis:
- description: The Train Tracker API provides real-time train arrival predictions and run/location information for all CTA L train lines. Endpoints include arrival predictions by station or stop, follow-this-train r
  name: CTA Train Tracker API
  slug: train-tracker-api
- description: 'The Bus Tracker API series provides real-time bus arrival predictions, vehicle locations, route patterns, route lists, and stop directories for the CTA bus network. Endpoints support route, stop, and '
  name: CTA Bus Tracker API
  slug: bus-tracker-api
- description: The Customer Alerts API delivers real-time service status, planned outages, and disruption information for CTA bus and rail services. It provides both a route-level status feed and per-route or per-st
  name: CTA Customer Alerts API
  slug: customer-alerts-api
- description: CTA publishes a GTFS (General Transit Feed Specification) schedule feed covering the physical layout, stop locations, and static schedules for the entire CTA bus and L train system. The feed is a down
  name: CTA GTFS Schedule Feed
  slug: gtfs-feed
common:
- title: ''
  type: Website
  url: https://www.transitchicago.com/
- title: ''
  type: Portal
  url: https://www.transitchicago.com/developers/
- title: ''
  type: TermsOfUse
  url: https://www.transitchicago.com/developers/terms/
- title: ''
  type: PrivacyPolicy
  url: https://www.transitchicago.com/privacy/
- title: ''
  type: APIKeyApplication
  url: https://www.transitchicago.com/developers/traintrackerapply/
- title: ''
  type: ChicagoDataPortal
  url: https://data.cityofchicago.org
- title: ''
  type: SystemMap
  url: https://www.transitchicago.com/maps/
- title: ''
  type: Newsroom
  url: https://www.transitchicago.com/news/
- title: ''
  type: ContactUs
  url: https://www.transitchicago.com/contactus/
- title: ''
  type: JSONLD
  url: json-ld/chicago-transit-authority-context.jsonld
- title: ''
  type: NaftikoCapabilities
  url: naftiko/chicago-transit-authority-capabilities.yml
- title: ''
  type: Spectral
  url: spectral/chicago-transit-authority-spectral.yml
- title: ''
  type: Standards
  url: ''
created: '2025-05-02'
description: The Chicago Transit Authority (CTA) is the public transit operator for the City of Chicago and 35 surrounding suburbs, operating the second largest public transit system in the United States with bus and rapid-transit (L) train services. The CTA Developer Center publishes open transit data feeds and APIs for developers building rider-facing applications, including the Train Tracker API for real-time L-train arrivals, the Bus Tracker API for real-time bus arrivals and vehicle locations, the Customer Alerts API for service status and disruptions, and GTFS schedule data feeds for the entire CTA bus and rail network.
features:
- name: Real-Time Train Arrivals
- name: Real-Time Bus Arrivals
- name: Train Run Locations
- name: Bus Vehicle Locations
- name: Route and Stop Directories
- name: Customer Alerts and Service Status
- name: Planned Outage Notifications
- name: GTFS Static Schedule Feed
- name: API Key Issuance
- name: Open Chicago Transit Data
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Chicago Transit Authority Context
  property_count: 4
  slug: chicago-transit-authority-context
layout: provider
modified: '2026-04-23'
name: Chicago Transit Authority
skills: []
slug: chicago-transit-authority
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: chicago-transit-authority\nname: Chicago Transit Authority\nx-type: government\ndescription: >-\n  The Chicago Transit Authority (CTA) is the public transit operator for\n  the City of Chicago and 35 surrounding suburbs, operating the second\n  largest public transit system in the United States with bus and\n  rapid-transit (L) train services. The CTA Developer Center publishes\n  open transit data feeds and APIs for developers building rider-facing\n  applications, including the Train Tracker API for real-time L-train\n  arrivals, the Bus Tracker API for real-time bus arrivals and vehicle\n  locations, the Customer Alerts API for service status and disruptions,\n  and GTFS schedule data feeds for the entire CTA bus and rail network.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/apis.yml\n\
  tags:\n  - Bus\n  - Bus Tracker\n  - Chicago\n  - CTA\n  - Customer Alerts\n  - GTFS\n  - L Train\n  - Open Data\n  - Public Transit\n  - Real-Time\n  - Train\n  - Train Tracker\n  - Transit\n  - Transportation\ncreated: '2025-05-02'\nmodified: '2026-04-23'\nspecificationVersion: '0.20'\napis:\n  - aid: chicago-transit-authority:train-tracker-api\n    name: CTA Train Tracker API\n    description: >-\n      The Train Tracker API provides real-time train arrival predictions\n      and run/location information for all CTA L train lines. Endpoints\n      include arrival predictions by station or stop, follow-this-train\n      run tracking, and a locations service exposing the current\n      latitude/longitude of in-service trains. Authentication requires\n      a developer API key issued through the CTA Developer Center.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.transitchicago.com/developers/traintracker/\n    baseURL:\
  \ http://lapi.transitchicago.com/api/1.0\n    tags:\n      - L Train\n      - Real-Time\n      - Train Tracker\n      - Transit\n    properties:\n      - type: Documentation\n        url: https://www.transitchicago.com/developers/traintracker/\n      - type: APIDocs\n        url: https://www.transitchicago.com/developers/ttdocs/\n      - type: APIKeyApplication\n        url: https://www.transitchicago.com/developers/traintrackerapply/\n      - type: TermsOfUse\n        url: https://www.transitchicago.com/developers/terms/\n      - type: OpenAPI\n        url: openapi/cta-train-tracker-openapi.yml\n      - type: Spectral\n        url: spectral/chicago-transit-authority-spectral.yml\n  - aid: chicago-transit-authority:bus-tracker-api\n    name: CTA Bus Tracker API\n    description: >-\n      The Bus Tracker API series provides real-time bus arrival\n      predictions, vehicle locations, route patterns, route lists, and\n      stop directories for the CTA bus network. Endpoints support\n \
  \     route, stop, and vehicle-based queries returning JSON or XML.\n      Authentication requires a developer API key issued through the\n      CTA Developer Center.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.transitchicago.com/developers/bustracker/\n    baseURL: http://www.ctabustracker.com/bustime/api/v2\n    tags:\n      - Bus\n      - Bus Tracker\n      - Real-Time\n      - Transit\n    properties:\n      - type: Documentation\n        url: https://www.transitchicago.com/developers/bustracker/\n      - type: TermsOfUse\n        url: https://www.transitchicago.com/developers/terms/\n      - type: OpenAPI\n        url: openapi/cta-bus-tracker-openapi.yml\n  - aid: chicago-transit-authority:customer-alerts-api\n    name: CTA Customer Alerts API\n    description: >-\n      The Customer Alerts API delivers real-time service status, planned\n      outages, and disruption information for CTA bus and rail services.\n\
  \      It provides both a route-level status feed and per-route or\n      per-station detail. Authentication is not required for the public\n      Customer Alerts feeds.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.transitchicago.com/developers/alerts/\n    baseURL: http://www.transitchicago.com/api/1.0\n    tags:\n      - Customer Alerts\n      - Real-Time\n      - Service Status\n      - Transit\n    properties:\n      - type: Documentation\n        url: https://www.transitchicago.com/developers/alerts/\n  - aid: chicago-transit-authority:gtfs-feed\n    name: CTA GTFS Schedule Feed\n    description: >-\n      CTA publishes a GTFS (General Transit Feed Specification) schedule\n      feed covering the physical layout, stop locations, and static\n      schedules for the entire CTA bus and L train system. The feed is\n      a downloadable ZIP archive that conforms to the GTFS reference and\n      is updated when CTA service\
  \ changes.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.transitchicago.com/developers/gtfs/\n    baseURL: https://www.transitchicago.com/downloads/sch_data/google_transit.zip\n    tags:\n      - GTFS\n      - Schedule\n      - Static\n      - Transit\n    properties:\n      - type: Documentation\n        url: https://www.transitchicago.com/developers/gtfs/\n      - type: Feed\n        url: https://www.transitchicago.com/downloads/sch_data/google_transit.zip\n      - type: DataGov\n        url: https://catalog.data.gov/dataset/cta-system-information-developer-tool-gtfs-data\n      - type: Transitland\n        url: https://www.transit.land/feeds/f-dp3-cta\n      - type: ChicagoDataPortal\n        url: https://data.cityofchicago.org/Transportation/CTA-System-Information-Developer-Tool-GTFS-Data/sp6w-yusg\ncommon:\n  - type: Website\n    url: https://www.transitchicago.com/\n  - type: Portal\n    name: CTA Developer Center\n\
  \    url: https://www.transitchicago.com/developers/\n  - type: TermsOfUse\n    url: https://www.transitchicago.com/developers/terms/\n  - type: PrivacyPolicy\n    url: https://www.transitchicago.com/privacy/\n  - type: APIKeyApplication\n    url: https://www.transitchicago.com/developers/traintrackerapply/\n  - type: ChicagoDataPortal\n    url: https://data.cityofchicago.org\n  - type: SystemMap\n    url: https://www.transitchicago.com/maps/\n  - type: Newsroom\n    url: https://www.transitchicago.com/news/\n  - type: ContactUs\n    url: https://www.transitchicago.com/contactus/\n  - type: JSONLD\n    url: json-ld/chicago-transit-authority-context.jsonld\n  - type: NaftikoCapabilities\n    url: naftiko/chicago-transit-authority-capabilities.yml\n  - type: Spectral\n    url: spectral/chicago-transit-authority-spectral.yml\n  - name: Features\n    type: Features\n    data:\n      - name: Real-Time Train Arrivals\n      - name: Real-Time Bus Arrivals\n      - name: Train Run Locations\n\
  \      - name: Bus Vehicle Locations\n      - name: Route and Stop Directories\n      - name: Customer Alerts and Service Status\n      - name: Planned Outage Notifications\n      - name: GTFS Static Schedule Feed\n      - name: API Key Issuance\n      - name: Open Chicago Transit Data\n  - name: UseCases\n    type: UseCases\n    data:\n      - name: Rider-Facing Mobile Apps\n      - name: Trip Planners and Routing\n      - name: Real-Time Arrival Displays\n      - name: Service Disruption Notifications\n      - name: Schedule Visualizations\n      - name: Accessibility Tooling\n      - name: Smart City Dashboards\n      - name: Multimodal Transit Apps\n      - name: Research and Open Data Analysis\n  - name: Standards\n    type: Standards\n    data:\n      - name: GTFS\n      - name: GTFS-Realtime (consumed via partners)\n      - name: REST\n      - name: JSON\n      - name: XML\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/apis.yml
tags:
- Bus
- Bus Tracker
- Chicago
- CTA
- Customer Alerts
- GTFS
- L Train
- Open Data
- Public Transit
- Real-Time
- Train
- Train Tracker
- Transit
- Transportation
url: https://raw.githubusercontent.com/api-evangelist/chicago-transit-authority/refs/heads/main/apis.yml
use_cases:
- name: Rider-Facing Mobile Apps
- name: Trip Planners and Routing
- name: Real-Time Arrival Displays
- name: Service Disruption Notifications
- name: Schedule Visualizations
- name: Accessibility Tooling
- name: Smart City Dashboards
- name: Multimodal Transit Apps
- name: Research and Open Data Analysis
---
