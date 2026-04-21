---
api_count: 1
apis:
- description: The Arlula API provides programmatic access to satellite imagery search, ordering, and delivery. It covers archive search for historical imagery, tasking for future satellite captures, and order manag
  name: Arlula API
  slug: arlula-api
capabilities:
- description: ''
  name: Satellite Imagery Operations
  slug: satellite-imagery-operations
common:
- title: ''
  type: Website
  url: https://arlula.com/
- title: ''
  type: Documentation
  url: https://arlula.com/documentation/
- title: ''
  type: GettingStarted
  url: https://arlula.com/documentation/
- title: ''
  type: Portal
  url: https://dashboard.arlula.com
- title: ''
  type: GitHubOrganization
  url: https://github.com/Arlula
- title: ''
  type: SpectralRules
  url: rules/arlula-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/satellite-imagery-operations.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/arlula-vocabulary.yaml
created: '2025-02-06'
description: Arlula is a satellite imagery marketplace and API platform providing programmatic access to archive and tasking satellite imagery from multiple providers. The Arlula API enables developers to search the global satellite archive, discover tasking opportunities, place imagery orders, and download delivered datasets including GeoTIFF imagery, preview images, and metadata files.
features:
- description: Search a global satellite image archive from multiple providers using area-of-interest (polygon/bounding box) and temporal filters to find available historical scenes.
  name: Archive Search
- description: Commission future satellite captures by searching tasking opportunities and placing orders for specific areas of interest and time windows.
  name: Satellite Tasking
- description: Access imagery from multiple satellite providers through a single unified API, enabling price and resolution comparisons across providers.
  name: Multi-Provider Access
- description: Choose from available product bundles (e.g., analytic, visual) when ordering scenes to match data requirements and budget.
  name: Bundle Selection
- description: Download delivered imagery resources including GeoTIFF files, preview images, and metadata through the Orders API after capture and processing.
  name: Dataset Download
- description: Place multiple archive or tasking orders in a single batch API request to efficiently process large-scale imagery acquisitions.
  name: Batch Ordering
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 19
  name: Arlula Api Context
  property_count: 26
  slug: arlula-api-context
layout: provider
modified: '2026-04-19'
name: Arlula
rules:
- name: Arlula API Rules
  rule_count: 30
  severity_counts:
    error: 14
    hint: 0
    info: 2
    warn: 14
  slug: arlula-spectral-rules
skills: []
slug: arlula
solutions: []
tags:
- Earth Observation
- Geospatial
- Imagery
- Remote Sensing
- Satellites
url: https://raw.githubusercontent.com/api-evangelist/arlula/refs/heads/main/apis.yml
use_cases:
- description: Search and order archive or tasking imagery to monitor crop health, irrigation patterns, and field conditions over growing seasons.
  name: Agricultural Monitoring
- description: Acquire multi-temporal satellite imagery to detect deforestation, coastal erosion, urban expansion, or disaster impact areas.
  name: Environmental Change Detection
- description: Order high-resolution imagery for remote inspection of pipelines, power lines, roads, and construction site progress monitoring.
  name: Infrastructure Inspection
- description: Rapidly search and order post-event imagery to assess damage extent and support emergency response and recovery planning.
  name: Disaster Response
---
