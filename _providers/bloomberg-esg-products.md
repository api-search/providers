---
api_count: 3
apis:
- description: Access Bloomberg ESG scores, environmental metrics, social indicators, and governance data for thousands of publicly listed companies globally. Data sourced directly from company disclosures and stand
  name: Bloomberg ESG Data API
  slug: esg-data-api
- description: Access physical and transition climate risk data, carbon emissions data, TCFD-aligned metrics, and scenario analysis tools through Bloomberg's climate data solutions.
  name: Bloomberg Climate Data API
  slug: climate-data-api
- description: Comprehensive data on green, social, sustainability, and sustainability-linked bonds including use of proceeds, certifications, and post-issuance reporting aligned to ICMA principles.
  name: Bloomberg Green Bond Data
  slug: green-bond-data
common:
- title: ''
  type: Portal
  url: https://www.bloomberg.com/professional/
- title: ''
  type: Documentation
  url: https://developer.bloomberg.com/
- title: ''
  type: TermsOfService
  url: https://www.bloomberg.com/notices/tos/
- title: ''
  type: PrivacyPolicy
  url: https://www.bloomberg.com/privacy/
- title: ''
  type: Support
  url: https://www.bloomberg.com/professional/support/
created: '2024-01-01'
description: Bloomberg ESG Products provide environmental, social, and governance data, analytics, and scores to help investors assess sustainability risks and opportunities. Bloomberg collects ESG data from thousands of companies globally, offering ESG scores, climate data, green bond data, and sustainable finance analytics through the Bloomberg Terminal and API.
features:
- description: Standardized ESG scores for thousands of companies based on disclosed data.
  name: ESG Scores
- description: Carbon emissions, water usage, energy consumption, and waste data.
  name: Environmental Metrics
- description: Employee relations, diversity metrics, health and safety, and community data.
  name: Social Indicators
- description: Board composition, executive compensation, shareholder rights, and audit data.
  name: Governance Data
- description: Physical and transition climate risk metrics aligned to TCFD framework.
  name: Climate Risk Analytics
- description: Green bond, social bond, and sustainability-linked loan data.
  name: Sustainable Finance Data
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg ESG Products
skills: []
slug: bloomberg-esg-products
solutions: []
source_yaml: "aid: bloomberg-esg-products\nname: Bloomberg ESG Products\ndescription: Bloomberg ESG Products provide environmental, social, and governance\n  data, analytics, and scores to help investors assess sustainability risks and opportunities.\n  Bloomberg collects ESG data from thousands of companies globally, offering ESG scores,\n  climate data, green bond data, and sustainable finance analytics through the Bloomberg\n  Terminal and API.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-esg-products/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- ESG\n- Sustainability\n- Environmental Data\n- Social Data\n- Governance Data\n- Climate Data\n- Bloomberg\napis:\n- aid: bloomberg-esg-products:esg-data-api\n  name: Bloomberg ESG Data API\n  description: Access Bloomberg ESG scores, environmental metrics, social\
  \ indicators,\n    and governance data for thousands of publicly listed companies globally. Data\n    sourced directly from company disclosures and standardized for comparability.\n  humanURL: https://www.bloomberg.com/professional/solution/esg-data/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - ESG\n  - Environmental\n  - Social\n  - Governance\n  - Scores\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/esg-data/\n- aid: bloomberg-esg-products:climate-data-api\n  name: Bloomberg Climate Data API\n  description: Access physical and transition climate risk data, carbon emissions\n    data, TCFD-aligned metrics, and scenario analysis tools through Bloomberg's climate\n    data solutions.\n  humanURL: https://www.bloomberg.com/professional/solution/climate-data/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Climate\n  - Carbon Emissions\n  - TCFD\n  - Physical Risk\n  - Transition Risk\n  properties:\n  - type: Documentation\n    url:\
  \ https://www.bloomberg.com/professional/solution/climate-data/\n- aid: bloomberg-esg-products:green-bond-data\n  name: Bloomberg Green Bond Data\n  description: Comprehensive data on green, social, sustainability, and sustainability-linked\n    bonds including use of proceeds, certifications, and post-issuance reporting\n    aligned to ICMA principles.\n  humanURL: https://www.bloomberg.com/professional/solution/sustainable-finance/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Green Bonds\n  - Sustainable Finance\n  - Fixed Income\n  - ICMA\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/sustainable-finance/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://developer.bloomberg.com/\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n\
  - type: Features\n  data:\n  - name: ESG Scores\n    description: Standardized ESG scores for thousands of companies based on disclosed\n      data.\n  - name: Environmental Metrics\n    description: Carbon emissions, water usage, energy consumption, and waste data.\n  - name: Social Indicators\n    description: Employee relations, diversity metrics, health and safety, and community\n      data.\n  - name: Governance Data\n    description: Board composition, executive compensation, shareholder rights, and\n      audit data.\n  - name: Climate Risk Analytics\n    description: Physical and transition climate risk metrics aligned to TCFD framework.\n  - name: Sustainable Finance Data\n    description: Green bond, social bond, and sustainability-linked loan data.\n- type: UseCases\n  data:\n  - name: ESG Integration\n    description: Integrate ESG factors into investment analysis and portfolio construction.\n  - name: Regulatory Reporting\n    description: Support SFDR, EU Taxonomy, and other\
  \ ESG regulatory reporting requirements.\n  - name: Stewardship and Engagement\n    description: Use ESG data to support shareholder engagement and proxy voting decisions.\n  - name: Sustainable Product Development\n    description: Develop ESG-linked financial products and indices.\n  - name: Climate Risk Assessment\n    description: Assess and disclose climate-related financial risks in portfolios.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-esg-products/refs/heads/main/apis.yml
tags:
- ESG
- Sustainability
- Environmental Data
- Social Data
- Governance Data
- Climate Data
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-esg-products/refs/heads/main/apis.yml
use_cases:
- description: Integrate ESG factors into investment analysis and portfolio construction.
  name: ESG Integration
- description: Support SFDR, EU Taxonomy, and other ESG regulatory reporting requirements.
  name: Regulatory Reporting
- description: Use ESG data to support shareholder engagement and proxy voting decisions.
  name: Stewardship and Engagement
- description: Develop ESG-linked financial products and indices.
  name: Sustainable Product Development
- description: Assess and disclose climate-related financial risks in portfolios.
  name: Climate Risk Assessment
---
