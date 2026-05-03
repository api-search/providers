---
api_count: 2
api_specs:
- filename: apispec
  format: yaml
  label: USDA FoodData Central API
  slug: fooddata-central-api
  spec_type: OpenAPI
  url: https://fdc.nal.usda.gov/portal-data/external/apispec
- filename: usda-ars-ag-data-commons-openapi.yml
  format: yaml
  label: USDA Ag Data Commons CKAN API
  slug: ag-data-commons-ckan-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/usda-agricultural-research-service-ars-/refs/heads/main/openapi/usda-ars-ag-data-commons-openapi.yml
apis:
- description: The USDA FoodData Central (FDC) API provides access to an integrated data system containing extended nutritional and food component data for thousands of foods. Data types include Foundation Foods, SR
  name: USDA FoodData Central API
  slug: fooddata-central-api
- description: The USDA Ag Data Commons is a DKAN/CKAN-based open data repository for USDA agricultural research datasets. The API provides metadata search and retrieval for datasets from ARS national programs inclu
  name: USDA Ag Data Commons CKAN API
  slug: ag-data-commons-ckan-api
capabilities:
- description: Unified capability for USDA Agricultural Research Service data access, combining FoodData Central nutritional data with Ag Data Commons agricultural research dataset discovery. Supports nutritionists,
  name: USDA ARS Agricultural Research Data
  slug: agricultural-research-data
common: []
created: '2024-11-21'
description: The USDA Agricultural Research Service (ARS) is the principal in-house research agency of the US Department of Agriculture. ARS conducts research to develop and implement solutions to agricultural problems that affect Americans every day. Research areas include crop protection, animal health, food safety, natural resource management, sustainable agriculture, and nutrition. ARS provides public data access through FoodData Central (nutrition data) and the Ag Data Commons (agricultural research datasets repository with CKAN/DKAN API).
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 3
  name: Usda Agricultural Research Service Ars Context
  property_count: 17
  slug: usda-agricultural-research-service-ars--context
layout: provider
modified: '2026-05-03'
name: USDA Agricultural Research Service (ARS)
rules:
- name: USDA Agricultural Research Service (ARS) API Rules
  rule_count: 7
  severity_counts:
    error: 2
    hint: 0
    info: 2
    warn: 3
  slug: usda-agricultural-research-service-ars--rules
skills: []
slug: usda-agricultural-research-service-ars-
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: usda-agricultural-research-service-ars-\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/usda-agricultural-research-service-ars-/refs/heads/main/apis.yml\napis:\n  - aid: usda-agricultural-research-service-ars-:fooddata-central-api\n    name: USDA FoodData Central API\n    tags:\n      - Food Data\n      - Nutrition\n      - Agriculture\n      - Federal Government\n      - Open Data\n    humanURL: https://fdc.nal.usda.gov/api-guide/\n    properties:\n      - url: https://fdc.nal.usda.gov/api-guide/\n        type: Documentation\n      - url: https://fdc.nal.usda.gov/portal-data/external/apispec\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/usda-agricultural-research-service-ars-/refs/heads/main/openapi/usda-ars-fooddata-central-openapi.yml\n        type: OpenAPI\n    description: >-\n      The USDA FoodData Central (FDC) API provides access to an integrated\n      data system containing extended nutritional\
  \ and food component data for\n      thousands of foods. Data types include Foundation Foods, SR Legacy,\n      Survey Foods (FNDDS), Branded Foods, and Experimental Foods. Requires\n      a free data.gov API key.\n  - aid: usda-agricultural-research-service-ars-:ag-data-commons-ckan-api\n    name: USDA Ag Data Commons CKAN API\n    tags:\n      - Agricultural Research\n      - Open Data\n      - Datasets\n      - CKAN\n      - Federal Government\n    humanURL: https://agdatacommons.nal.usda.gov\n    properties:\n      - url: https://agdatacommons.nal.usda.gov\n        type: Portal\n      - url: https://data.nal.usda.gov/about-ag-data-commons\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/usda-agricultural-research-service-ars-/refs/heads/main/openapi/usda-ars-ag-data-commons-openapi.yml\n        type: OpenAPI\n    description: >-\n      The USDA Ag Data Commons is a DKAN/CKAN-based open data repository for\n      USDA agricultural\
  \ research datasets. The API provides metadata search\n      and retrieval for datasets from ARS national programs including\n      genomics, crop science, soil health, animal production, and more.\n      No authentication required for read access.\nname: USDA Agricultural Research Service (ARS)\ntags:\n  - Federal Government\n  - Agriculture\n  - Food Safety\n  - Nutrition\n  - Open Data\n  - Research\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-21'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The USDA Agricultural Research Service (ARS) is the principal in-house research\n  agency of the US Department of Agriculture. ARS conducts research to develop and\n  implement solutions to agricultural problems that affect Americans every day.\n  Research areas include crop protection, animal health, food safety, natural resource\n  management, sustainable agriculture, and nutrition. ARS\
  \ provides public data\n  access through FoodData Central (nutrition data) and the Ag Data Commons\n  (agricultural research datasets repository with CKAN/DKAN API).\nfeatures:\n  - Food Nutrition Data (FoodData Central)\n  - Agricultural Research Datasets (Ag Data Commons)\n  - Germplasm Resources (GRIN)\n  - Plant Variety Protection\n  - Soil Health Data\n  - Genomics and Bioinformatics Tools\nuseCases:\n  - Nutrition research and dietary analysis\n  - Food labeling and composition analysis\n  - Agricultural research data discovery\n  - Plant genetics and germplasm research\n  - Food safety assessment\n  - Sustainable agriculture research\n  - Climate and soil health monitoring\nintegrations:\n  - data.gov\n  - Ag Data Commons\n  - FoodData Central\nsolutions:\n  - Food and Nutrition Research\n  - Agricultural Data Discovery\n  - Crop and Animal Genetics Research\ngithub:\n  - https://github.com/USDA-ARS\n  - https://github.com/usda-ars-gbru\n  - https://github.com/usda-ars-nwrc\nmaintainers:\n\
  \  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/usda-agricultural-research-service-ars-/refs/heads/main/apis.yml
tags:
- Federal Government
- Agriculture
- Food Safety
- Nutrition
- Open Data
- Research
url: https://raw.githubusercontent.com/api-evangelist/usda-agricultural-research-service-ars-/refs/heads/main/apis.yml
use_cases: []
---
