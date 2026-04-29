---
api_count: 1
api_specs:
- filename: amazon-location-service-openapi.yml
  format: yaml
  label: Amazon Location Service REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-location-service/refs/heads/main/openapi/amazon-location-service-openapi.yml
apis:
- description: RESTful API for Amazon Location Service operations including maps, places, routes, geofences, trackers, and device position management for location-aware applications.
  name: Amazon Location Service REST API
  slug: ''
capabilities:
- description: Unified workflow capability for Amazon Location Service combining resource management and operations.
  name: Amazon Location Service Workflow
  slug: amazon-location-service-workflow
common:
- title: ''
  type: Portal
  url: https://aws.amazon.com/
- title: ''
  type: Portal
  url: https://aws.amazon.com/location/
- title: ''
  type: Documentation
  url: https://docs.aws.amazon.com/location/
- title: ''
  type: TermsOfService
  url: https://aws.amazon.com/service-terms/
- title: ''
  type: PrivacyPolicy
  url: https://aws.amazon.com/privacy/
- title: ''
  type: Support
  url: https://aws.amazon.com/premiumsupport/
- title: ''
  type: Blog
  url: https://aws.amazon.com/blogs/mobile/
- title: ''
  type: GitHubOrganization
  url: https://github.com/aws
- title: ''
  type: Console
  url: https://console.aws.amazon.com/location/
- title: ''
  type: SignUp
  url: https://signin.aws.amazon.com/signup?request_type=register
- title: ''
  type: Login
  url: https://aws.amazon.com/console/
- title: ''
  type: Status
  url: https://health.aws.amazon.com/health/status
- title: ''
  type: Knowledge Center
  url: https://repost.aws/knowledge-center
- title: ''
  type: YouTube
  url: https://www.youtube.com/user/AmazonWebServices
- title: ''
  type: Stack Overflow
  url: https://stackoverflow.com/questions/tagged/amazon-location-service
- title: ''
  type: Contact
  url: https://aws.amazon.com/contact-us/
- title: ''
  type: SpectralRules
  url: rules/amazon-location-service-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/amazon-location-service-workflow.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/amazon-location-service-vocabulary.yaml
created: '2024-01-15'
description: Amazon Location Service provides location-based services including maps, places, routes, trackers, and geofences, enabling developers to add location functionality to applications securely and cost-effectively.
features:
- description: Render interactive maps with customizable styles using vector tiles and raster tiles.
  name: Maps
- description: Search for addresses, points of interest, and geographic coordinates.
  name: Places Search
- description: Calculate optimal routes with turn-by-turn directions and estimated travel time.
  name: Route Calculation
- description: Create virtual boundaries and detect when tracked devices enter or exit those areas.
  name: Geofencing
- description: Track the real-time position of assets, vehicles, and people.
  name: Asset Tracking
- description: Data does not leave AWS infrastructure, keeping location data private and secure.
  name: Data Privacy
image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png
integrations:
- description: Authenticate map and location requests using Cognito identity pools.
  name: Amazon Cognito
- description: Ingest device location data from IoT Core into Location Service tracking.
  name: AWS IoT Core
- description: Trigger events when geofences are entered or exited via EventBridge.
  name: Amazon EventBridge
- description: Use HERE maps and location data as a data provider within Location Service.
  name: HERE Technologies
- description: Access Esri basemaps and location data through Amazon Location Service.
  name: Esri
jsonld:
- class_count: 2
  name: Amazon Location Service Context
  property_count: 7
  slug: amazon-location-service-context
layout: provider
modified: '2026-04-19'
name: Amazon Location Service
rules:
- name: Amazon Location Service API Rules
  rule_count: 16
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 7
  slug: amazon-location-service-spectral-rules
skills: []
slug: amazon-location-service
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Amazon Location Service\ndescription: Amazon Location Service provides location-based services including maps, places, routes, trackers, and geofences, enabling developers to add location functionality to applications \n  securely and cost-effectively.\nimage: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\nurl: https://aws.amazon.com/location/\ncreated: '2024-01-15'\nmodified: '2026-04-19'\napis:\n- name: Amazon Location Service REST API\n  description: RESTful API for Amazon Location Service operations including maps, places, routes, geofences, trackers, and device position management for location-aware applications.\n  image: https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png\n  humanURL: https://aws.amazon.com/location/\n  baseURL: https://geo.amazonaws.com\n  tags:\n  - AWS\n  - Geofencing\n  - Location\n  - Maps\n  properties:\n  - type: Documentation\n    url: https://docs.aws.amazon.com/location/latest/APIReference/\n\
  \  - type: OpenAPI\n    url: openapi/amazon-location-service-openapi.yml\n  - type: OpenAPI\n    url: https://api.apis.guru/v2/specs/amazonaws.com/location/2020-11-19/openapi.yaml\n  - type: JSONSchema\n    url: json-schema/amazon-location-service-geofence-schema.json\n  - type: JSONLD\n    url: json-ld/amazon-location-service-context.jsonld\n  - type: Pricing\n    url: https://aws.amazon.com/location/pricing/\n  - type: GettingStarted\n    url: https://aws.amazon.com/location/getting-started/\n  - type: Authentication\n    url: https://docs.aws.amazon.com/location/latest/APIReference/CommonParameters.html\n  - type: SDKs\n    url: https://aws.amazon.com/tools/\n  - type: Status\n    url: https://status.aws.amazon.com/\n  - type: FAQ\n    url: https://aws.amazon.com/location/faqs/\n  - type: Service Level Agreement\n    url: https://aws.amazon.com/location/sla/\n  - type: User Guide\n    url: https://docs.aws.amazon.com/location/latest/developerguide/welcome.html\n  - type: APIReference\n\
  \    url: https://docs.aws.amazon.com/location/latest/APIReference/Welcome.html\n  - type: Code Examples\n    url: https://docs.aws.amazon.com/location/latest/developerguide/samples.html\n  - type: Security\n    url: https://docs.aws.amazon.com/location/latest/developerguide/security.html\n  - type: JSONSchema\n    url: json-schema/amazon-location-service-map-schema.json\n  - type: JSONSchema\n    url: json-schema/amazon-location-service-tracker-schema.json\ncommon:\n- type: Portal\n  url: https://aws.amazon.com/\n- type: Portal\n  url: https://aws.amazon.com/location/\n- type: Documentation\n  url: https://docs.aws.amazon.com/location/\n- type: TermsOfService\n  url: https://aws.amazon.com/service-terms/\n- type: PrivacyPolicy\n  url: https://aws.amazon.com/privacy/\n- type: Support\n  url: https://aws.amazon.com/premiumsupport/\n- type: Blog\n  url: https://aws.amazon.com/blogs/mobile/\n- type: GitHubOrganization\n  url: https://github.com/aws\n- type: Console\n  url: https://console.aws.amazon.com/location/\n\
  - type: SignUp\n  url: https://signin.aws.amazon.com/signup?request_type=register\n- type: Login\n  url: https://aws.amazon.com/console/\n- type: Status\n  url: https://health.aws.amazon.com/health/status\n- type: Knowledge Center\n  url: https://repost.aws/knowledge-center\n- type: YouTube\n  url: https://www.youtube.com/user/AmazonWebServices\n- type: Stack Overflow\n  url: https://stackoverflow.com/questions/tagged/amazon-location-service\n- type: Contact\n  url: https://aws.amazon.com/contact-us/\n- type: Features\n  data:\n  - name: Maps\n    description: Render interactive maps with customizable styles using vector tiles and raster tiles.\n  - name: Places Search\n    description: Search for addresses, points of interest, and geographic coordinates.\n  - name: Route Calculation\n    description: Calculate optimal routes with turn-by-turn directions and estimated travel time.\n  - name: Geofencing\n    description: Create virtual boundaries and detect when tracked devices enter or\
  \ exit those areas.\n  - name: Asset Tracking\n    description: Track the real-time position of assets, vehicles, and people.\n  - name: Data Privacy\n    description: Data does not leave AWS infrastructure, keeping location data private and secure.\n- type: UseCases\n  data:\n  - name: Fleet Management\n    description: Track vehicle fleets in real time and optimize routes for delivery efficiency.\n  - name: Store Locator\n    description: Build store locators and proximity-based search for retail applications.\n  - name: Geofence Alerts\n    description: Send notifications when assets enter or exit defined geographic boundaries.\n  - name: Map Visualization\n    description: Embed interactive maps in web and mobile applications.\n- type: Integrations\n  data:\n  - name: Amazon Cognito\n    description: Authenticate map and location requests using Cognito identity pools.\n  - name: AWS IoT Core\n    description: Ingest device location data from IoT Core into Location Service tracking.\n\
  \  - name: Amazon EventBridge\n    description: Trigger events when geofences are entered or exited via EventBridge.\n  - name: HERE Technologies\n    description: Use HERE maps and location data as a data provider within Location Service.\n  - name: Esri\n    description: Access Esri basemaps and location data through Amazon Location Service.\n- type: SpectralRules\n  url: rules/amazon-location-service-spectral-rules.yml\n- type: NaftikoCapability\n  url: capabilities/amazon-location-service-workflow.yaml\n- type: Vocabulary\n  url: vocabulary/amazon-location-service-vocabulary.yaml\nmaintainers:\n- FN: Kin Lane\n  email: kin@apievangelist.com\n  url: https://apievangelist.com\ntags:\n- AWS\n- Geocoding\n- Geofencing\n- Location\n- Maps\n- Routing\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/amazon-location-service/refs/heads/main/apis.yml
tags:
- AWS
- Geocoding
- Geofencing
- Location
- Maps
- Routing
url: https://aws.amazon.com/location/
use_cases:
- description: Track vehicle fleets in real time and optimize routes for delivery efficiency.
  name: Fleet Management
- description: Build store locators and proximity-based search for retail applications.
  name: Store Locator
- description: Send notifications when assets enter or exit defined geographic boundaries.
  name: Geofence Alerts
- description: Embed interactive maps in web and mobile applications.
  name: Map Visualization
---
