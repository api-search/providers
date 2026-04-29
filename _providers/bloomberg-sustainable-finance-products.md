---
api_count: 4
apis:
- description: Access Bloomberg ESG scores, environmental KPIs, social metrics, and governance data for thousands of companies globally. Sourced from company disclosures and standardized for comparability across sec
  name: Bloomberg ESG Data API
  slug: esg-data-api
- description: Access comprehensive green, social, sustainability, and sustainability-linked bond data including use of proceeds, project categories, certifications, and post-issuance reporting aligned to ICMA Green
  name: Bloomberg Green Bond API
  slug: green-bond-api
- description: Access physical climate risk scores, transition risk metrics, carbon emissions data, and TCFD-aligned analytics for companies and portfolios. Supports climate stress testing and scenario analysis.
  name: Bloomberg Climate Risk Data API
  slug: climate-risk-api
- description: Access Principal Adverse Indicators (PAIs) and other data points required for EU Sustainable Finance Disclosure Regulation (SFDR) reporting for investment products and portfolios.
  name: Bloomberg SFDR Data API
  slug: sfdr-api
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
description: Bloomberg Sustainable Finance Products provide comprehensive data, analytics, and tools for sustainable investing, green bond markets, ESG integration, and climate risk assessment. Bloomberg serves as a key data provider for sustainable finance markets, offering green bond data, ESG scores, climate analytics, and impact measurement tools aligned with major regulatory frameworks including SFDR, EU Taxonomy, and TCFD.
features:
- description: Standardized ESG disclosure scores for thousands of public companies.
  name: ESG Scores
- description: Use of proceeds, certifications, and reporting data for green and social bonds.
  name: Green Bond Data
- description: Physical and transition climate risk scores and scenario analysis.
  name: Climate Risk Metrics
- description: Principal Adverse Indicators data for EU SFDR regulatory reporting.
  name: SFDR PAI Indicators
- description: Data on company revenue alignment with EU Taxonomy environmental objectives.
  name: EU Taxonomy Alignment
- description: Environmental and social impact metrics for sustainable investments.
  name: Impact Reporting
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-21'
name: Bloomberg Sustainable Finance Products
skills: []
slug: bloomberg-sustainable-finance-products
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: bloomberg-sustainable-finance-products\nname: Bloomberg Sustainable Finance Products\ndescription: Bloomberg Sustainable Finance Products provide comprehensive data, analytics,\n  and tools for sustainable investing, green bond markets, ESG integration, and climate\n  risk assessment. Bloomberg serves as a key data provider for sustainable finance\n  markets, offering green bond data, ESG scores, climate analytics, and impact measurement\n  tools aligned with major regulatory frameworks including SFDR, EU Taxonomy, and\n  TCFD.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: https://raw.githubusercontent.com/api-evangelist/bloomberg-sustainable-finance-products/refs/heads/main/apis.yml\ncreated: '2024-01-01'\nmodified: '2026-04-21'\nspecificationVersion: '0.19'\ntags:\n- Sustainable Finance\n- ESG\n- Green Bonds\n- Climate Risk\n- SFDR\n- EU Taxonomy\n- Bloomberg\napis:\n- aid: bloomberg-sustainable-finance-products:esg-data-api\n\
  \  name: Bloomberg ESG Data API\n  description: Access Bloomberg ESG scores, environmental KPIs, social metrics, and\n    governance data for thousands of companies globally. Sourced from company disclosures\n    and standardized for comparability across sectors and geographies.\n  humanURL: https://www.bloomberg.com/professional/solution/esg-data/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - ESG\n  - Environmental\n  - Social\n  - Governance\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/esg-data/\n- aid: bloomberg-sustainable-finance-products:green-bond-api\n  name: Bloomberg Green Bond API\n  description: Access comprehensive green, social, sustainability, and sustainability-linked\n    bond data including use of proceeds, project categories, certifications, and\n    post-issuance reporting aligned to ICMA Green Bond Principles.\n  humanURL: https://www.bloomberg.com/professional/solution/sustainable-finance/\n  baseURL: blpapi://localhost:8194\n\
  \  tags:\n  - Green Bonds\n  - Social Bonds\n  - Sustainability Bonds\n  - ICMA\n  - Fixed Income\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/sustainable-finance/\n- aid: bloomberg-sustainable-finance-products:climate-risk-api\n  name: Bloomberg Climate Risk Data API\n  description: Access physical climate risk scores, transition risk metrics, carbon\n    emissions data, and TCFD-aligned analytics for companies and portfolios. Supports\n    climate stress testing and scenario analysis.\n  humanURL: https://www.bloomberg.com/professional/solution/climate-data/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - Climate Risk\n  - Physical Risk\n  - Transition Risk\n  - TCFD\n  - Carbon Emissions\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/climate-data/\n- aid: bloomberg-sustainable-finance-products:sfdr-api\n  name: Bloomberg SFDR Data API\n  description: Access Principal Adverse Indicators\
  \ (PAIs) and other data points required\n    for EU Sustainable Finance Disclosure Regulation (SFDR) reporting for investment\n    products and portfolios.\n  humanURL: https://www.bloomberg.com/professional/solution/regulatory-data/\n  baseURL: blpapi://localhost:8194\n  tags:\n  - SFDR\n  - PAI\n  - Regulatory\n  - EU Taxonomy\n  - Disclosure\n  properties:\n  - type: Documentation\n    url: https://www.bloomberg.com/professional/solution/regulatory-data/\ncommon:\n- type: Portal\n  url: https://www.bloomberg.com/professional/\n- type: Documentation\n  url: https://developer.bloomberg.com/\n- type: TermsOfService\n  url: https://www.bloomberg.com/notices/tos/\n- type: PrivacyPolicy\n  url: https://www.bloomberg.com/privacy/\n- type: Support\n  url: https://www.bloomberg.com/professional/support/\n- type: Features\n  data:\n  - name: ESG Scores\n    description: Standardized ESG disclosure scores for thousands of public companies.\n  - name: Green Bond Data\n    description: Use of proceeds,\
  \ certifications, and reporting data for green and\n      social bonds.\n  - name: Climate Risk Metrics\n    description: Physical and transition climate risk scores and scenario analysis.\n  - name: SFDR PAI Indicators\n    description: Principal Adverse Indicators data for EU SFDR regulatory reporting.\n  - name: EU Taxonomy Alignment\n    description: Data on company revenue alignment with EU Taxonomy environmental\n      objectives.\n  - name: Impact Reporting\n    description: Environmental and social impact metrics for sustainable investments.\n- type: UseCases\n  data:\n  - name: ESG Integration\n    description: Integrate ESG data into investment analysis and portfolio construction.\n  - name: SFDR Reporting\n    description: Satisfy SFDR disclosure requirements for EU-domiciled investment\n      products.\n  - name: Green Bond Issuance\n    description: Access market data and reporting frameworks for green bond issuance.\n  - name: Climate Risk Disclosure\n    description: Disclose\
  \ TCFD-aligned climate risks in investment portfolios.\n  - name: Impact Measurement\n    description: Measure and report the environmental and social impact of investments.\nmaintainers:\n- FN: Kin Lane\n  email: kinlane@gmail.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/bloomberg-sustainable-finance-products/refs/heads/main/apis.yml
tags:
- Sustainable Finance
- ESG
- Green Bonds
- Climate Risk
- SFDR
- EU Taxonomy
- Bloomberg
url: https://raw.githubusercontent.com/api-evangelist/bloomberg-sustainable-finance-products/refs/heads/main/apis.yml
use_cases:
- description: Integrate ESG data into investment analysis and portfolio construction.
  name: ESG Integration
- description: Satisfy SFDR disclosure requirements for EU-domiciled investment products.
  name: SFDR Reporting
- description: Access market data and reporting frameworks for green bond issuance.
  name: Green Bond Issuance
- description: Disclose TCFD-aligned climate risks in investment portfolios.
  name: Climate Risk Disclosure
- description: Measure and report the environmental and social impact of investments.
  name: Impact Measurement
---
