---
api_count: 5
apis:
- description: Cosmos is Tetra Tech's mobile data collection platform designed for field data capture, project management, and reporting. The Cosmos API and webhook system enables integration with third-party enterp
  name: Cosmos Mobile Data Platform API
  slug: ''
- description: The Data Discovery Tool (DDT) is an open-source environmental data analysis platform developed by Tetra Tech in partnership with USEPA. It provides data query, analysis, and visualization capabilities
  name: Tetra Tech Data Discovery Tool API
  slug: ''
- description: 'baytrends is an open-source R package developed by Tetra Tech for evaluating long-term trends in Chesapeake Bay and similar water bodies using Generalized Additive Modeling (GAM). The package exposes '
  name: baytrends Water Quality Trend API
  slug: ''
- description: The Tetra Tech Delta digital solutions portfolio delivers enterprise data management and analytics capabilities for industrial clients. Services include historian development, automated reporting, ent
  name: Tetra Tech Delta Data Management Services
  slug: ''
- description: 'WaterNet is Tetra Tech''s SaaS water network management solution for utilities. It provides data-driven insights for water infrastructure management, enabling utilities to monitor network performance, '
  name: WaterNet Water Network Management API
  slug: ''
common:
- title: ''
  type: Website
  url: https://www.tetratech.com/
- title: ''
  type: GitHubOrg
  url: https://github.com/tetratech
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/tetra-tech
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/json-schema/tetra-tech-project-schema.json
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/json-schema/tetra-tech-water-quality-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/json-structure/tetra-tech-project-structure.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/json-structure/tetra-tech-water-quality-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/json-ld/tetra-tech-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/vocabulary/tetra-tech-vocabulary.yml
created: '2026-05-03'
description: Tetra Tech is an American consulting and engineering services firm headquartered in Pasadena, California. Founded in 1966, it provides consulting, engineering, program management, and construction management services across water, environment, infrastructure, resource management, energy, and international development. With 30,000 employees across 550 offices worldwide, Tetra Tech delivers data-driven digital solutions under the Tetra Tech Delta brand, encompassing advanced data analytics, artificial intelligence, process automation, and cloud integration. Key digital offerings include the Cosmos mobile data collection platform, WaterNet SaaS for water network management, and environmental data management tools. The company's GitHub organization (tetratech) hosts open-source environmental and water quality analysis tools.
features: []
image: ''
integrations: []
jsonld:
- class_count: 19
  name: Tetra Tech Context
  property_count: 11
  slug: tetra-tech-context
layout: provider
modified: '2026-05-03'
name: Tetra Tech
skills: []
slug: tetra-tech
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "name: Tetra Tech\ndescription: >-\n  Tetra Tech is an American consulting and engineering services firm headquartered\n  in Pasadena, California. Founded in 1966, it provides consulting, engineering,\n  program management, and construction management services across water, environment,\n  infrastructure, resource management, energy, and international development.\n  With 30,000 employees across 550 offices worldwide, Tetra Tech delivers\n  data-driven digital solutions under the Tetra Tech Delta brand, encompassing\n  advanced data analytics, artificial intelligence, process automation, and cloud\n  integration. Key digital offerings include the Cosmos mobile data collection\n  platform, WaterNet SaaS for water network management, and environmental data\n  management tools. The company's GitHub organization (tetratech) hosts open-source\n  environmental and water quality analysis tools.\nurl: https://www.tetratech.com/\ntags:\n  - Analytics\n  - Consulting\n  - Data Management\n\
  \  - Engineering\n  - Environment\n  - Infrastructure\n  - Water\ncreated: '2026-05-03'\nmodified: '2026-05-03'\napis:\n  - name: Cosmos Mobile Data Platform API\n    description: >-\n      Cosmos is Tetra Tech's mobile data collection platform designed for field data\n      capture, project management, and reporting. The Cosmos API and webhook system\n      enables integration with third-party enterprise systems, allowing automated\n      data synchronization, webhook event notifications, and data export in industry\n      standard formats including JSON and CSV.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://cosmos.tetratech.com/\n    baseURL: https://cosmos.tetratech.com/\n    tags:\n      - Data Collection\n      - Field Data\n      - Mobile\n      - Webhooks\n    properties:\n      - type: Documentation\n        url: https://cosmos.tetratech.com/\n      - type: Website\n        url: https://cosmos.tetratech.com/\n\n  -\
  \ name: Tetra Tech Data Discovery Tool API\n    description: >-\n      The Data Discovery Tool (DDT) is an open-source environmental data analysis\n      platform developed by Tetra Tech in partnership with USEPA. It provides\n      data query, analysis, and visualization capabilities for environmental monitoring\n      datasets. The application is available on GitHub with R-based data processing\n      APIs for water quality trend analysis.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/tetratech/DataDiscoveryTool\n    baseURL: https://github.com/tetratech/DataDiscoveryTool\n    tags:\n      - Environmental\n      - Open Source\n      - USEPA\n      - Water Quality\n    properties:\n      - type: Documentation\n        url: https://github.com/tetratech/DataDiscoveryTool\n      - type: GitHubOrg\n        url: https://github.com/tetratech\n\n  - name: baytrends Water Quality Trend API\n    description: >-\n      baytrends\
  \ is an open-source R package developed by Tetra Tech for evaluating\n      long-term trends in Chesapeake Bay and similar water bodies using Generalized\n      Additive Modeling (GAM). The package exposes functions as a programmatic API\n      for water quality data ingestion, trend analysis, and visualization.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://github.com/tetratech/baytrends\n    baseURL: https://github.com/tetratech/baytrends\n    tags:\n      - Chesapeake Bay\n      - Environmental\n      - Open Source\n      - R Package\n      - Water Quality\n    properties:\n      - type: Documentation\n        url: https://github.com/tetratech/baytrends\n      - type: GitHubOrg\n        url: https://github.com/tetratech\n\n  - name: Tetra Tech Delta Data Management Services\n    description: >-\n      The Tetra Tech Delta digital solutions portfolio delivers enterprise data\n      management and analytics capabilities for\
  \ industrial clients. Services include\n      historian development, automated reporting, enterprise data integration,\n      SCADA/OT system integration, and AI-powered analytics through cloud and\n      on-premise deployments.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.tetratech.com/tetra-tech-delta/\n    baseURL: https://www.tetratech.com/\n    tags:\n      - Analytics\n      - Data Management\n      - Digital Transformation\n      - Enterprise\n    properties:\n      - type: Documentation\n        url: https://www.tetratech.com/tetra-tech-delta/\n      - type: Website\n        url: https://www.tetratech.com/solutions/digital-systems/\n\n  - name: WaterNet Water Network Management API\n    description: >-\n      WaterNet is Tetra Tech's SaaS water network management solution for utilities.\n      It provides data-driven insights for water infrastructure management, enabling\n      utilities to monitor network performance,\
  \ analyze asset health, and support\n      decision-making for capital planning and operations.\n    image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://www.tetratech.com/solutions/one-water/digital-water/\n    baseURL: https://www.tetratech.com/\n    tags:\n      - SaaS\n      - Water Infrastructure\n      - Utilities\n    properties:\n      - type: Documentation\n        url: https://www.tetratech.com/solutions/one-water/digital-water/\n      - type: Website\n        url: https://www.tetratech.com/solutions/one-water/digital-water/\n\ncommon:\n  - type: Website\n    url: https://www.tetratech.com/\n  - type: GitHubOrg\n    url: https://github.com/tetratech\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/tetra-tech\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/json-schema/tetra-tech-project-schema.json\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/json-schema/tetra-tech-water-quality-schema.json\n\
  \  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/json-structure/tetra-tech-project-structure.json\n  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/json-structure/tetra-tech-water-quality-structure.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/json-ld/tetra-tech-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/main/vocabulary/tetra-tech-vocabulary.yml\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tetra-tech/refs/heads/main/apis.yml
tags:
- Analytics
- Consulting
- Data Management
- Engineering
- Environment
- Infrastructure
- Water
url: https://www.tetratech.com/
use_cases: []
---
