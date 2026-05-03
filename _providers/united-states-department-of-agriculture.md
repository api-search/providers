---
api_count: 4
api_specs:
- filename: yaml-spec
  format: yaml
  label: USDA FoodData Central API
  slug: usda-fooddata-central-api
  spec_type: OpenAPI
  url: https://api.nal.usda.gov/fdc/v1/yaml-spec?api_key=DEMO_KEY
- filename: usda-nass-quickstats-openapi.yml
  format: yaml
  label: USDA NASS Quick Stats API
  slug: usda-nass-quickstats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-nass-quickstats-openapi.yml
- filename: usda-ers-arms-openapi.yml
  format: yaml
  label: USDA ERS ARMS Data API
  slug: usda-ers-arms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-ers-arms-openapi.yml
- filename: usda-nrcs-awdb-openapi.yml
  format: yaml
  label: USDA NRCS AWDB Water and Climate REST API
  slug: usda-nrcs-awdb-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-nrcs-awdb-openapi.yml
apis:
- description: The FoodData Central API provides REST access to FoodData Central (FDC), the USDA's integrated data system that provides expanded nutrient profile data and links to related agricultural and experiment
  name: USDA FoodData Central API
  slug: usda-fooddata-central-api
- description: 'The USDA NASS Quick Stats API provides direct access to the National Agricultural Statistics Service''s official published aggregate estimates related to U.S. agricultural production. Returns data for '
  name: USDA NASS Quick Stats API
  slug: usda-nass-quickstats-api
- description: The USDA Economic Research Service (ERS) ARMS Data API provides access to the Agricultural Resource Management Survey (ARMS), covering farm finances, production practices, and resource use for U.S. fa
  name: USDA ERS ARMS Data API
  slug: usda-ers-arms-api
- description: The USDA Natural Resources Conservation Service (NRCS) Air and Water Database (AWDB) REST API provides access to snow, water, and climate data from SNOTEL (SNOw TELemetry) stations and Soil Climate An
  name: USDA NRCS AWDB Water and Climate REST API
  slug: usda-nrcs-awdb-api
capabilities:
- description: Unified capability for food and agricultural data research workflows combining USDA FoodData Central nutrient data with NASS agricultural production statistics. Used by nutritionists, food researchers
  name: USDA Food and Agriculture Data Research
  slug: food-data-research
common: []
created: '2024-11-14'
description: The United States Department of Agriculture (USDA) is a federal agency responsible for developing and executing policies related to farming, agriculture, forestry, and food. The USDA works to ensure the sustainability and safety of America's food supply, while also supporting rural development and promoting economic growth in rural communities. USDA provides multiple public APIs including FoodData Central for nutrient data, NASS Quick Stats for agricultural statistics, ERS ARMS for farm economics, and NRCS AWDB for water and climate monitoring data.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 4
  name: United States Department Of Agriculture Context
  property_count: 14
  slug: united-states-department-of-agriculture-context
layout: provider
modified: '2026-05-03'
name: United States Department of Agriculture
rules:
- name: United States Department of Agriculture API Rules
  rule_count: 7
  severity_counts:
    error: 3
    hint: 0
    info: 0
    warn: 4
  slug: usda-fooddata-central-rules
skills: []
slug: united-states-department-of-agriculture
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: united-states-department-of-agriculture\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/apis.yml\napis:\n  - aid: >-\n      united-states-department-of-agriculture:usda-fooddata-central-api\n    name: USDA FoodData Central API\n    tags:\n      - Food\n      - Nutrition\n      - Agriculture\n      - Federal Government\n    humanURL: https://fdc.nal.usda.gov/api-guide/\n    baseURL: https://api.nal.usda.gov/fdc/v1\n    properties:\n      - url: https://fdc.nal.usda.gov/api-guide/\n        type: Documentation\n      - url: https://api.nal.usda.gov/fdc/v1/yaml-spec?api_key=DEMO_KEY\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-fooddata-central-openapi.yml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/rules/usda-fooddata-central-rules.yml\n\
  \        type: SpectralRules\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/capabilities/food-data-research.yaml\n        type: NaftikoCapability\n      - url: https://fdc.nal.usda.gov/api-key-signup/\n        type: SignUp\n    description: >-\n      The FoodData Central API provides REST access to FoodData Central (FDC),\n      the USDA's integrated data system that provides expanded nutrient profile\n      data and links to related agricultural and experimental research. The API\n      supports food search, nutrient lookup, and retrieval of food details across\n      multiple food data types including Foundation Foods, SR Legacy, FNDDS,\n      Branded Foods, and Experimental Foods.\n\n  - aid: >-\n      united-states-department-of-agriculture:usda-nass-quickstats-api\n    name: USDA NASS Quick Stats API\n    tags:\n      - Agriculture\n      - Statistics\n      - Crops\n      - Livestock\n      - Federal\
  \ Government\n    humanURL: https://quickstats.nass.usda.gov/api\n    baseURL: https://quickstats.nass.usda.gov/api\n    properties:\n      - url: https://quickstats.nass.usda.gov/api\n        type: Documentation\n      - url: https://www.nass.usda.gov/developer/index.php\n        type: Portal\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-nass-quickstats-openapi.yml\n        type: OpenAPI\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/capabilities/food-data-research.yaml\n        type: NaftikoCapability\n    description: >-\n      The USDA NASS Quick Stats API provides direct access to the National\n      Agricultural Statistics Service's official published aggregate estimates\n      related to U.S. agricultural production. Returns data for commodities,\n      categories, and geographic areas, supporting\
  \ queries on crops, livestock,\n      economics, and demographics with responses in JSON, CSV, or XML formats.\n\n  - aid: >-\n      united-states-department-of-agriculture:usda-ers-arms-api\n    name: USDA ERS ARMS Data API\n    tags:\n      - Agriculture\n      - Economics\n      - Farm Management\n      - Federal Government\n    humanURL: https://www.ers.usda.gov/developer/data-apis/arms-data-api\n    baseURL: https://api.ers.usda.gov/data/arms\n    properties:\n      - url: https://www.ers.usda.gov/developer/data-apis/arms-data-api\n        type: Documentation\n      - url: https://www.ers.usda.gov/developer/data-apis/\n        type: Portal\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-ers-arms-openapi.yml\n        type: OpenAPI\n    description: >-\n      The USDA Economic Research Service (ERS) ARMS Data API provides access to\n      the Agricultural Resource Management Survey (ARMS),\
  \ covering farm finances,\n      production practices, and resource use for U.S. farms. Supports attribute-\n      based querying of farm income, balance sheet, costs, and production data\n      by year, state, and report type.\n\n  - aid: >-\n      united-states-department-of-agriculture:usda-nrcs-awdb-api\n    name: USDA NRCS AWDB Water and Climate REST API\n    tags:\n      - Water\n      - Climate\n      - Snow\n      - SNOTEL\n      - Federal Government\n    humanURL: https://wcc.sc.egov.usda.gov/awdbRestApi/swagger-ui/index.html\n    baseURL: https://wcc.sc.egov.usda.gov/awdbRestApi/services/v1\n    properties:\n      - url: https://wcc.sc.egov.usda.gov/awdbRestApi/swagger-ui/index.html\n        type: SwaggerUI\n      - url: https://www.nrcs.usda.gov/sites/default/files/2023-03/AWDB%20Web%20Service%20User%20Guide.pdf\n        type: Documentation\n      - url: >-\n          https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-nrcs-awdb-openapi.yml\n\
  \        type: OpenAPI\n    description: >-\n      The USDA Natural Resources Conservation Service (NRCS) Air and Water\n      Database (AWDB) REST API provides access to snow, water, and climate data\n      from SNOTEL (SNOw TELemetry) stations and Soil Climate Analysis Network\n      (SCAN) stations. Supports retrieval of daily, monthly, and annual\n      hydrology and climate data for water resource management.\n\nname: United States Department of Agriculture\ntags:\n  - Federal Government\n  - Agriculture\n  - Food Safety\n  - Nutrition\n  - Rural Development\n  - Climate\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-14'\nmodified: '2026-05-03'\nposition: Consuming\ndescription: >-\n  The United States Department of Agriculture (USDA) is a federal agency\n  responsible for developing and executing policies related to farming,\n  agriculture, forestry, and food. The USDA works to ensure the sustainability\n\
  \  and safety of America's food supply, while also supporting rural development\n  and promoting economic growth in rural communities. USDA provides multiple\n  public APIs including FoodData Central for nutrient data, NASS Quick Stats\n  for agricultural statistics, ERS ARMS for farm economics, and NRCS AWDB for\n  water and climate monitoring data.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/apis.yml
tags:
- Federal Government
- Agriculture
- Food Safety
- Nutrition
- Rural Development
- Climate
url: https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/apis.yml
use_cases: []
---
