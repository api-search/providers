---
api_count: 8
apis:
- description: 'Core nonprofit search and lookup. Provides fast search over Candid''s database of U.S. nonprofits by name, EIN, location, NTEE code, size, and more. Returns summary records suitable for autocompletes, '
  name: Candid Essentials API
  slug: essentials-api
- description: Deep nonprofit profile data. Returns comprehensive records for a given organization including financials, programs, leadership, board, grants received and awarded, operating details, affiliations, and
  name: Candid Premier API
  slug: premier-api
- description: 'Real-time nonprofit verification and compliance screening used for due diligence, donation compliance, and tax-deductibility checks. Returns IRS 501(c)(3) status, revocation history, public-charity / '
  name: Candid Charity Check API
  slug: charity-check-api
- description: Structured demographic data voluntarily provided by nonprofits about their staff, board, and populations served. Enables funders and platforms to analyze equity, diversity, and inclusion across the so
  name: Candid Demographics API
  slug: demographics-api
- description: Access to Candid's global grants dataset — summary statistics, funders, recipients, and individual transaction records. Useful for philanthropic benchmarking, funder research, and grant-market intelli
  name: Candid Grants API
  slug: grants-api
- description: Search and retrieve philanthropic news content from Candid's curated news database covering funders, grantees, sector trends, and policy. Supports customizable parameters for date range, topic, geogra
  name: Candid News API
  slug: news-api
- description: 'Returns Candid''s philanthropic classification system (subject, population, support-strategy, and geographic area taxonomies) so integrators can consistently tag and query nonprofit, grant, and funder '
  name: Candid Taxonomy API
  slug: taxonomy-api
- description: Evaluates whether a given nonprofit is eligible to receive a grant or donation based on configurable rules — IRS status, country, OFAC, custom program criteria — to automate grantmaking and giving wor
  name: Candid Nonprofit Eligibility API
  slug: nonprofit-eligibility-api
common:
- title: ''
  type: Website
  url: https://candid.org
- title: ''
  type: DeveloperPortal
  url: https://developer.candid.org/
- title: ''
  type: DataPortal
  url: https://data.candid.org/reference/welcome-to-candids-data-portal
- title: ''
  type: APIsOverview
  url: https://candid.org/use-our-data
- title: ''
  type: PricingAndAccess
  url: https://candid.org/use-our-data
- title: ''
  type: PrivacyPolicy
  url: https://candid.org/privacy-policy
- title: ''
  type: TermsOfService
  url: https://candid.org/terms-of-use
- title: ''
  type: Support
  url: https://help.candid.org/
created: '2025-03-01'
description: Candid (formed from the 2019 merger of Foundation Center and GuideStar) helps social sector organizations advance their missions by sharing information, breaking down barriers, and improving giving. Candid maintains the most comprehensive set of data on U.S. nonprofits, foundations, grants, and philanthropy, and exposes that data through a family of developer APIs — Essentials, Premier, Charity Check, Demographics, Grants, News, Taxonomy, Eligibility, and PDF/Bulk variants — available through the Candid Developer Portal.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: Candid
skills: []
slug: candid
solutions: []
source_filename: apis.yml
source_yaml: "aid: candid\nname: Candid\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/candid/refs/heads/main/apis.yml\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntype: Index\ntags:\n  - Charities\n  - Donations\n  - Non-Profits\n  - Philanthropy\n  - Foundations\n  - Grants\n  - 990s\n  - Demographics\naccess: 3rd-Party\ncreated: '2025-03-01'\nmodified: '2026-04-23'\nposition: Provider\nspecificationVersion: '0.19'\ndescription: >-\n  Candid (formed from the 2019 merger of Foundation Center and GuideStar)\n  helps social sector organizations advance their missions by sharing\n  information, breaking down barriers, and improving giving. Candid\n  maintains the most comprehensive set of data on U.S. nonprofits,\n  foundations, grants, and philanthropy, and exposes that data through a\n  family of developer APIs — Essentials, Premier, Charity Check,\n  Demographics, Grants, News, Taxonomy, Eligibility, and PDF/Bulk variants —\n  available\
  \ through the Candid Developer Portal.\napis:\n  - aid: candid:essentials-api\n    name: Candid Essentials API\n    description: >-\n      Core nonprofit search and lookup. Provides fast search over Candid's\n      database of U.S. nonprofits by name, EIN, location, NTEE code, size,\n      and more. Returns summary records suitable for autocompletes, lookups,\n      and basic-verification flows. Available in versions v1–v4 with POST\n      and GET variants.\n    humanURL: https://developer.candid.org/reference/welcome\n    baseURL: https://api.candid.org/essentials\n    tags:\n      - Nonprofits\n      - Search\n      - Lookup\n    properties:\n      - type: Documentation\n        url: https://developer.candid.org/reference/welcome\n      - type: Portal\n        url: https://developer.candid.org/\n  - aid: candid:premier-api\n    name: Candid Premier API\n    description: >-\n      Deep nonprofit profile data. Returns comprehensive records for a given\n      organization including financials,\
  \ programs, leadership, board, grants\n      received and awarded, operating details, affiliations, and FTA\n      (Financial Trend Analysis). Supports a Profile PDF generation endpoint\n      for building ready-to-share nonprofit briefs.\n    humanURL: https://developer.candid.org/reference/welcome\n    baseURL: https://api.candid.org/premier\n    tags:\n      - Nonprofits\n      - Financials\n      - Profiles\n      - PDF\n    properties:\n      - type: Documentation\n        url: https://developer.candid.org/reference/welcome\n      - type: Portal\n        url: https://developer.candid.org/\n  - aid: candid:charity-check-api\n    name: Candid Charity Check API\n    description: >-\n      Real-time nonprofit verification and compliance screening used for due\n      diligence, donation compliance, and tax-deductibility checks. Returns\n      IRS 501(c)(3) status, revocation history, public-charity / private-\n      foundation classification, OFAC watchlist screening, and more. Offers\n\
  \      national and state-level endpoints.\n    humanURL: https://developer.candid.org/reference/welcome\n    baseURL: https://api.candid.org/charitycheck\n    tags:\n      - Compliance\n      - Verification\n      - IRS\n      - Due Diligence\n    properties:\n      - type: Documentation\n        url: https://developer.candid.org/reference/welcome\n      - type: Portal\n        url: https://developer.candid.org/\n  - aid: candid:demographics-api\n    name: Candid Demographics API\n    description: >-\n      Structured demographic data voluntarily provided by nonprofits about\n      their staff, board, and populations served. Enables funders and\n      platforms to analyze equity, diversity, and inclusion across the\n      social sector.\n    humanURL: https://developer.candid.org/reference/welcome\n    baseURL: https://api.candid.org/demographics\n    tags:\n      - Demographics\n      - DEI\n      - Nonprofits\n    properties:\n      - type: Documentation\n        url: https://developer.candid.org/reference/welcome\n\
  \      - type: Portal\n        url: https://developer.candid.org/\n  - aid: candid:grants-api\n    name: Candid Grants API\n    description: >-\n      Access to Candid's global grants dataset — summary statistics, funders,\n      recipients, and individual transaction records. Useful for\n      philanthropic benchmarking, funder research, and grant-market\n      intelligence.\n    humanURL: https://developer.candid.org/reference/welcome\n    baseURL: https://api.candid.org/grants\n    tags:\n      - Grants\n      - Funders\n      - Recipients\n      - Transactions\n    properties:\n      - type: Documentation\n        url: https://developer.candid.org/reference/welcome\n      - type: Portal\n        url: https://developer.candid.org/\n  - aid: candid:news-api\n    name: Candid News API\n    description: >-\n      Search and retrieve philanthropic news content from Candid's curated\n      news database covering funders, grantees, sector trends, and policy.\n      Supports customizable parameters\
  \ for date range, topic, geography,\n      and organization.\n    humanURL: https://developer.candid.org/reference/welcome\n    baseURL: https://api.candid.org/news\n    tags:\n      - News\n      - Philanthropy\n      - Content\n    properties:\n      - type: Documentation\n        url: https://developer.candid.org/reference/welcome\n      - type: Portal\n        url: https://developer.candid.org/\n  - aid: candid:taxonomy-api\n    name: Candid Taxonomy API\n    description: >-\n      Returns Candid's philanthropic classification system (subject,\n      population, support-strategy, and geographic area taxonomies) so\n      integrators can consistently tag and query nonprofit, grant, and\n      funder records.\n    humanURL: https://developer.candid.org/reference/welcome\n    baseURL: https://api.candid.org/taxonomy\n    tags:\n      - Taxonomy\n      - Classification\n      - Metadata\n    properties:\n      - type: Documentation\n        url: https://developer.candid.org/reference/welcome\n\
  \      - type: Portal\n        url: https://developer.candid.org/\n  - aid: candid:nonprofit-eligibility-api\n    name: Candid Nonprofit Eligibility API\n    description: >-\n      Evaluates whether a given nonprofit is eligible to receive a grant or\n      donation based on configurable rules — IRS status, country, OFAC,\n      custom program criteria — to automate grantmaking and giving\n      workflows.\n    humanURL: https://developer.candid.org/reference/welcome\n    baseURL: https://api.candid.org/eligibility\n    tags:\n      - Eligibility\n      - Grantmaking\n      - Compliance\n    properties:\n      - type: Documentation\n        url: https://developer.candid.org/reference/welcome\n      - type: Portal\n        url: https://developer.candid.org/\ncommon:\n  - type: Website\n    url: https://candid.org\n  - type: DeveloperPortal\n    url: https://developer.candid.org/\n  - type: DataPortal\n    url: https://data.candid.org/reference/welcome-to-candids-data-portal\n  - type: APIsOverview\n\
  \    url: https://candid.org/use-our-data\n  - type: PricingAndAccess\n    url: https://candid.org/use-our-data\n  - type: PrivacyPolicy\n    url: https://candid.org/privacy-policy\n  - type: TermsOfService\n    url: https://candid.org/terms-of-use\n  - type: Support\n    url: https://help.candid.org/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/candid/refs/heads/main/apis.yml
tags:
- Charities
- Donations
- Non-Profits
- Philanthropy
- Foundations
- Grants
- 990s
- Demographics
url: https://raw.githubusercontent.com/api-evangelist/candid/refs/heads/main/apis.yml
use_cases: []
---
