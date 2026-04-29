---
api_count: 1
api_specs:
- filename: agrio-openapi-original.yml
  format: yaml
  label: Agrio Agriculture API
  slug: agrio
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/agrio/refs/heads/main/openapi/agrio-openapi-original.yml
apis:
- description: The Agrio Agriculture API provides AI-powered plant disease and pest diagnosis from images, plus crop advisory data, credit balance management, and access to a catalog of supported crop types. The Ima
  name: Agrio Agriculture API
  slug: agrio
capabilities:
- description: Unified crop protection capability combining Agrio's AI-powered plant disease diagnosis, pest detection, and crop advisory services. Used by agronomists, crop advisors, and precision agriculture platf
  name: Agrio Crop Protection
  slug: crop-protection
common:
- title: ''
  type: Website
  url: https://agrio.app
- title: ''
  type: Portal
  url: https://pro.agrio.app/image-diagnosis-api
- title: ''
  type: Support
  url: mailto:info@saillog.co
- title: ''
  type: SpectralRules
  url: rules/agrio-spectral-rules.yml
- title: ''
  type: NaftikoCapability
  url: capabilities/crop-protection.yaml
- title: ''
  type: Vocabulary
  url: vocabulary/agrio-vocabulary.yaml
created: ''
description: Agrio is a precision plant protection solution that helps growers and crop advisors forecast, identify, and treat plant diseases, pests, and nutrient deficiencies. With Agrio APIs, developers can access AI-powered plant disease diagnosis from images, crop advisory data, weather pattern analysis, pest and disease predictions, and satellite vegetation monitoring to build accurate crop advisory tools.
features:
- description: Computer vision algorithms identify plant diseases, pests, and nutrient deficiencies from uploaded photos with confidence scores.
  name: AI Image Diagnosis
- description: Predictive algorithms forecast disease pressure before or between scouting events to enable proactive intervention.
  name: AgrioShield Pest Prediction
- description: Remote sensing AI detects vegetation issues from satellite data, enabling early detection before visible symptoms appear.
  name: Satellite Imagery Alerts
- description: Returns multiple ranked diagnoses with confidence scores, common names, and scientific names for disambiguation.
  name: Ranked Diagnoses
- description: API usage is metered using a credit system; one credit is consumed per diagnosis request.
  name: Credit-Based Usage
- description: Discoverable catalog of supported crop types for building targeted diagnosis workflows.
  name: Supported Crop Catalog
image: ''
integrations:
- description: Agrio APIs integrate weather pattern data to enhance pest and disease prediction models.
  name: Weather Data Systems
- description: Remote sensing data from satellite providers is used for vegetation monitoring and anomaly detection.
  name: Satellite Imagery Providers
jsonld:
- class_count: 7
  name: Agrio Context
  property_count: 16
  slug: agrio-context
layout: provider
modified: '2026-04-19'
name: agrio
rules:
- name: agrio API Rules
  rule_count: 21
  severity_counts:
    error: 9
    hint: 0
    info: 1
    warn: 11
  slug: agrio-spectral-rules
skills: []
slug: agrio
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: agrio\nurl: https://raw.githubusercontent.com/api-evangelist/agrio/refs/heads/main/apis.yml\nmodified: '2026-04-19'\ndescription: >-\n  Agrio is a precision plant protection solution that helps growers and crop\n  advisors forecast, identify, and treat plant diseases, pests, and nutrient\n  deficiencies. With Agrio APIs, developers can access AI-powered plant disease\n  diagnosis from images, crop advisory data, weather pattern analysis, pest and\n  disease predictions, and satellite vegetation monitoring to build accurate\n  crop advisory tools.\ntags:\n  - Agriculture\n  - Plant Disease\n  - Pest Detection\n  - AI\n  - Crop Advisory\napis:\n  - aid: agrio:agrio\n    name: Agrio Agriculture API\n    description: >-\n      The Agrio Agriculture API provides AI-powered plant disease and pest\n      diagnosis from images, plus crop advisory data, credit balance management,\n      and access to a catalog of supported crop types. The Image Diagnosis API\n      analyzes plant\
  \ photos to return ranked disease and pest identifications\n      with confidence scores, common names, and scientific names.\n    humanURL: https://agrio.app/Agriculture-API/\n    baseURL: https://agrio-api-gateway-6it0wqn1.uc.gateway.dev\n    tags:\n      - Plant Disease\n      - Pest Detection\n      - AI\n      - Image Recognition\n      - Crop Advisory\n    properties:\n      - type: Documentation\n        url: https://agrio.app/Agriculture-API/\n      - type: OpenAPI\n        url: openapi/agrio-openapi-original.yml\n      - type: JSONSchema\n        url: json-schema/agrio-diagnosis-schema.json\n        title: Diagnosis Schema\n      - type: JSONSchema\n        url: json-schema/agrio-diagnosis-result-schema.json\n        title: Diagnosis Result Schema\n      - type: JSONSchema\n        url: json-schema/agrio-crop-schema.json\n        title: Crop Schema\n      - type: JSONSchema\n        url: json-schema/agrio-credit-balance-schema.json\n        title: Credit Balance Schema\n     \
  \ - type: JSONStructure\n        url: json-structure/agrio-diagnosis-structure.json\n        title: Diagnosis Structure\n      - type: JSONStructure\n        url: json-structure/agrio-crop-structure.json\n        title: Crop Structure\n      - type: JSON-LD\n        url: json-ld/agrio-context.jsonld\ncommon:\n  - type: Website\n    url: https://agrio.app\n  - type: Portal\n    url: https://pro.agrio.app/image-diagnosis-api\n  - type: Support\n    url: mailto:info@saillog.co\n  - type: SpectralRules\n    url: rules/agrio-spectral-rules.yml\n  - type: NaftikoCapability\n    url: capabilities/crop-protection.yaml\n  - type: Vocabulary\n    url: vocabulary/agrio-vocabulary.yaml\n  - type: Features\n    data:\n      - name: AI Image Diagnosis\n        description: Computer vision algorithms identify plant diseases, pests, and nutrient deficiencies from uploaded photos with confidence scores.\n      - name: AgrioShield Pest Prediction\n        description: Predictive algorithms forecast disease\
  \ pressure before or between scouting events to enable proactive intervention.\n      - name: Satellite Imagery Alerts\n        description: Remote sensing AI detects vegetation issues from satellite data, enabling early detection before visible symptoms appear.\n      - name: Ranked Diagnoses\n        description: Returns multiple ranked diagnoses with confidence scores, common names, and scientific names for disambiguation.\n      - name: Credit-Based Usage\n        description: API usage is metered using a credit system; one credit is consumed per diagnosis request.\n      - name: Supported Crop Catalog\n        description: Discoverable catalog of supported crop types for building targeted diagnosis workflows.\n  - type: UseCases\n    data:\n      - name: Crop Advisory Tool Integration\n        description: Embed AI plant disease diagnosis into existing crop advisory and farm management applications.\n      - name: In-Field Disease Identification\n        description: Enable agronomists\
  \ and farmers to photograph plant symptoms and receive immediate AI-powered diagnosis.\n      - name: Early Warning Systems\n        description: Use AgrioShield alerts to notify growers when disease or pest conditions become favorable before visible symptoms appear.\n      - name: Precision Agriculture Platforms\n        description: Integrate Agrio diagnosis into precision agriculture platforms for targeted treatment recommendations.\n      - name: Research and Development\n        description: Access Agrio plant disease data for agricultural research and development of new advisory models.\n  - type: Integrations\n    data:\n      - name: Weather Data Systems\n        description: Agrio APIs integrate weather pattern data to enhance pest and disease prediction models.\n      - name: Satellite Imagery Providers\n        description: Remote sensing data from satellite providers is used for vegetation monitoring and anomaly detection.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/agrio/refs/heads/main/apis.yml
tags:
- Agriculture
- Plant Disease
- Pest Detection
- AI
- Crop Advisory
url: https://raw.githubusercontent.com/api-evangelist/agrio/refs/heads/main/apis.yml
use_cases:
- description: Embed AI plant disease diagnosis into existing crop advisory and farm management applications.
  name: Crop Advisory Tool Integration
- description: Enable agronomists and farmers to photograph plant symptoms and receive immediate AI-powered diagnosis.
  name: In-Field Disease Identification
- description: Use AgrioShield alerts to notify growers when disease or pest conditions become favorable before visible symptoms appear.
  name: Early Warning Systems
- description: Integrate Agrio diagnosis into precision agriculture platforms for targeted treatment recommendations.
  name: Precision Agriculture Platforms
- description: Access Agrio plant disease data for agricultural research and development of new advisory models.
  name: Research and Development
---
