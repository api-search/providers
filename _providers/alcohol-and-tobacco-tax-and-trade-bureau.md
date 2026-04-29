---
api_count: 3
apis:
- description: The TTB Open Data API provides programmatic access to TTB statistical and regulatory datasets via the Socrata Open Data API (SODA). Available datasets include alcohol beverage tax collections by commo
  name: TTB Open Data API
  slug: ttb-open-data-api
- description: The TTB Public COLA (Certificate of Label Approval) Registry provides access to approved alcohol beverage labels. Users and industry members can search for approved labels by product type, brand name,
  name: TTB COLA Registry
  slug: ttb-cola-registry
- description: TTB Permits Online is the electronic portal for applying for and managing federal basic permits, brewer's notices, distilled spirits plant permits, and tobacco permits. The system allows industry memb
  name: TTB Permits Online
  slug: ttb-permits-online
common:
- title: ''
  type: Website
  url: https://www.ttb.gov
- title: ''
  type: Portal
  url: https://www.ttb.gov/open-government/open-data
- title: ''
  type: DataPortal
  url: https://data.ttb.gov
- title: ''
  type: Documentation
  url: https://www.ttb.gov/about-ttb/laws-and-regulations
- title: ''
  type: Contact
  url: https://www.ttb.gov/contact
- title: ''
  type: PrivacyPolicy
  url: https://www.ttb.gov/about-ttb/privacy-policy
- title: ''
  type: FOIA
  url: https://www.ttb.gov/about-ttb/foia
- title: ''
  type: GitHubOrganization
  url: https://github.com/ttb-gov
created: '2024-11-21T00:00:00.000Z'
description: The Alcohol and Tobacco Tax and Trade Bureau (TTB), statutorily named the Tax and Trade Bureau, is a bureau of the United States Department of the Treasury. TTB regulates and collects federal excise taxes on alcohol, tobacco, firearms, and ammunition. The bureau enforces Federal laws and regulations related to alcohol and tobacco products, issues permits for producers, importers, and wholesalers, approves label applications for alcohol beverages, and provides open data on tax collections, permit holders, and approved product labels. TTB administers approximately $20 billion in annual federal excise tax collections from the alcohol and tobacco industries.
features:
- description: Annual and monthly federal excise tax collections broken down by alcohol and tobacco commodity type and by state.
  name: Excise Tax Data
- description: Public searchable database of all approved Certificate of Label Approval (COLA) records for wine, spirits, and malt beverages.
  name: COLA Registry
- description: Open data on federal basic permit holders including producers, importers, wholesalers, and retailers of alcohol beverages.
  name: Permit Holder Data
- description: TTB datasets are published on the Socrata platform, accessible via the standard Socrata Open Data API (SODA) with JSON and CSV output.
  name: Socrata SODA API
- description: Annual statistical reports on alcohol and tobacco tax collections, industry production volumes, and commodity statistics.
  name: Statistical Reports
- description: Electronic Freedom of Information Act (eFOIA) request submission and tracking for TTB records not available through open data.
  name: eFOIA Portal
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: TTB datasets are accessible through api.data.gov, the government-wide API management platform hosted by GSA.
  name: api.data.gov
- description: TTB open datasets are cataloged on data.gov, the federal open data portal managed by GSA.
  name: Data.gov Catalog
- description: TTB uses the Socrata platform (data.ttb.gov) to publish and provide API access to regulatory datasets.
  name: Socrata Open Data Platform
- description: TTB coordinates with the Internal Revenue Service on excise tax administration and data sharing.
  name: IRS
- description: TTB coordinates with U.S. Customs and Border Protection on alcohol and tobacco import regulation and taxation.
  name: CBP (US Customs)
- description: TTB works with the Bureau of Alcohol, Tobacco, Firearms and Explosives on shared jurisdiction over alcohol and tobacco regulation.
  name: ATF
layout: provider
modified: '2026-04-19'
name: Alcohol and Tobacco Tax and Trade Bureau
skills: []
slug: alcohol-and-tobacco-tax-and-trade-bureau
solutions: []
source_filename: apis.yml
source_yaml: "aid: alcohol-and-tobacco-tax-and-trade-bureau\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/alcohol-and-tobacco-tax-and-trade-bureau/refs/heads/main/apis.yml\nname: Alcohol and Tobacco Tax and Trade Bureau\ntags:\n  - Alcohol\n  - Tobacco\n  - Federal Government\n  - Excise Tax\n  - Regulation\n  - Treasury\ntype: Contract\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\ncreated: '2024-11-21T00:00:00.000Z'\nmodified: '2026-04-19'\nposition: Consuming\ndescription: >-\n  The Alcohol and Tobacco Tax and Trade Bureau (TTB), statutorily named the Tax\n  and Trade Bureau, is a bureau of the United States Department of the Treasury.\n  TTB regulates and collects federal excise taxes on alcohol, tobacco, firearms,\n  and ammunition. The bureau enforces Federal laws and regulations related to\n  alcohol and tobacco products, issues permits for producers, importers, and\n  wholesalers, approves label applications for\
  \ alcohol beverages, and provides\n  open data on tax collections, permit holders, and approved product labels.\n  TTB administers approximately $20 billion in annual federal excise tax\n  collections from the alcohol and tobacco industries.\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\nspecificationVersion: '0.19'\napis:\n  - aid: alcohol-and-tobacco-tax-and-trade-bureau:ttb-open-data-api\n    name: TTB Open Data API\n    tags:\n      - Open Data\n      - Socrata\n      - Excise Tax\n    humanURL: https://www.ttb.gov/open-government/open-data\n    description: >-\n      The TTB Open Data API provides programmatic access to TTB statistical and\n      regulatory datasets via the Socrata Open Data API (SODA). Available\n      datasets include alcohol beverage tax collections by commodity and state,\n      federal basic permit holders, approved Certificate of Label Approval (COLA)\n      records, and brewery/winery/distillery permit data. The SODA API supports\n     \
  \ filtering, sorting, pagination, and JSON/CSV output formats.\n    properties:\n      - type: DataAPI\n        url: https://data.ttb.gov/resource/\n\n  - aid: alcohol-and-tobacco-tax-and-trade-bureau:ttb-cola-registry\n    name: TTB COLA Registry\n    tags:\n      - Alcohol Beverage Labels\n      - COLA\n      - Open Data\n    humanURL: https://www.ttb.gov/labeling/cola-registry\n    description: >-\n      The TTB Public COLA (Certificate of Label Approval) Registry provides\n      access to approved alcohol beverage labels. Users and industry members\n      can search for approved labels by product type, brand name, filer name,\n      and approval date. The registry covers wine, distilled spirits, and malt\n      beverage label approvals required before commercial sale in interstate or\n      foreign commerce.\n    properties:\n      - type: DataAPI\n        url: https://www.ttb.gov/labeling/cola-registry\n\n  - aid: alcohol-and-tobacco-tax-and-trade-bureau:ttb-permits-online\n    name:\
  \ TTB Permits Online\n    tags:\n      - Permits\n      - Licensing\n      - Alcohol\n      - Tobacco\n    humanURL: https://www.ttb.gov/permitting/permits-online\n    description: >-\n      TTB Permits Online is the electronic portal for applying for and managing\n      federal basic permits, brewer's notices, distilled spirits plant permits,\n      and tobacco permits. The system allows industry members to submit permit\n      applications, file operational reports, and pay federal excise taxes\n      electronically. Permit status and holder data are published as open data.\n    properties:\n      - type: GovernmentAPI\n        url: https://www.ttb.gov/permitting/permits-online\n\ncommon:\n  - type: Website\n    url: https://www.ttb.gov\n  - type: Portal\n    url: https://www.ttb.gov/open-government/open-data\n  - type: DataPortal\n    url: https://data.ttb.gov\n  - type: Documentation\n    url: https://www.ttb.gov/about-ttb/laws-and-regulations\n  - type: Contact\n    url: https://www.ttb.gov/contact\n\
  \  - type: PrivacyPolicy\n    url: https://www.ttb.gov/about-ttb/privacy-policy\n  - type: FOIA\n    url: https://www.ttb.gov/about-ttb/foia\n  - type: GitHubOrganization\n    url: https://github.com/ttb-gov\n  - type: Features\n    data:\n      - name: Excise Tax Data\n        description: Annual and monthly federal excise tax collections broken down by alcohol and tobacco commodity type and by state.\n      - name: COLA Registry\n        description: Public searchable database of all approved Certificate of Label Approval (COLA) records for wine, spirits, and malt beverages.\n      - name: Permit Holder Data\n        description: Open data on federal basic permit holders including producers, importers, wholesalers, and retailers of alcohol beverages.\n      - name: Socrata SODA API\n        description: TTB datasets are published on the Socrata platform, accessible via the standard Socrata Open Data API (SODA) with JSON and CSV output.\n      - name: Statistical Reports\n        description:\
  \ Annual statistical reports on alcohol and tobacco tax collections, industry production volumes, and commodity statistics.\n      - name: eFOIA Portal\n        description: Electronic Freedom of Information Act (eFOIA) request submission and tracking for TTB records not available through open data.\n  - type: UseCases\n    data:\n      - name: Alcohol Industry Compliance Research\n        description: Producers, importers, and retailers use TTB permit and label data to verify compliance status and competitive market intelligence.\n      - name: Tax Revenue Analysis\n        description: Policy researchers and economists analyze TTB excise tax collection data to study alcohol and tobacco market trends.\n      - name: Label Approval Tracking\n        description: Alcohol beverage companies track COLA approval status and research competitor label approvals in the public registry.\n      - name: Market Research\n        description: Industry analysts use production volume statistics and permit\
  \ holder counts to assess market size and industry structure.\n      - name: Academic Research\n        description: Public health researchers use TTB consumption proxy data (tax collection volumes) to study alcohol consumption patterns.\n      - name: Journalism and FOIA Research\n        description: Journalists and public interest groups use TTB open data and FOIA to investigate regulatory compliance and enforcement actions.\n  - type: Integrations\n    data:\n      - name: api.data.gov\n        description: TTB datasets are accessible through api.data.gov, the government-wide API management platform hosted by GSA.\n      - name: Data.gov Catalog\n        description: TTB open datasets are cataloged on data.gov, the federal open data portal managed by GSA.\n      - name: Socrata Open Data Platform\n        description: TTB uses the Socrata platform (data.ttb.gov) to publish and provide API access to regulatory datasets.\n      - name: IRS\n        description: TTB coordinates with the\
  \ Internal Revenue Service on excise tax administration and data sharing.\n      - name: CBP (US Customs)\n        description: TTB coordinates with U.S. Customs and Border Protection on alcohol and tobacco import regulation and taxation.\n      - name: ATF\n        description: TTB works with the Bureau of Alcohol, Tobacco, Firearms and Explosives on shared jurisdiction over alcohol and tobacco regulation.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/alcohol-and-tobacco-tax-and-trade-bureau/refs/heads/main/apis.yml
tags:
- Alcohol
- Tobacco
- Federal Government
- Excise Tax
- Regulation
- Treasury
url: https://raw.githubusercontent.com/api-evangelist/alcohol-and-tobacco-tax-and-trade-bureau/refs/heads/main/apis.yml
use_cases:
- description: Producers, importers, and retailers use TTB permit and label data to verify compliance status and competitive market intelligence.
  name: Alcohol Industry Compliance Research
- description: Policy researchers and economists analyze TTB excise tax collection data to study alcohol and tobacco market trends.
  name: Tax Revenue Analysis
- description: Alcohol beverage companies track COLA approval status and research competitor label approvals in the public registry.
  name: Label Approval Tracking
- description: Industry analysts use production volume statistics and permit holder counts to assess market size and industry structure.
  name: Market Research
- description: Public health researchers use TTB consumption proxy data (tax collection volumes) to study alcohol consumption patterns.
  name: Academic Research
- description: Journalists and public interest groups use TTB open data and FOIA to investigate regulatory compliance and enforcement actions.
  name: Journalism and FOIA Research
---
