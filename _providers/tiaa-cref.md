---
api_count: 4
apis:
- description: TIAA's retirement plan services for individual participants, covering 403(b), 457(b), 401(k), and IRA accounts. Products include TIAA Traditional fixed annuity, CREF variable annuities (stock, bond, m
  name: TIAA Retirement Plans
  slug: tiaa-retirement-plans
- description: 'TIAA''s flagship annuity products for retirement income, including TIAA Traditional (a participating fixed annuity with guaranteed minimum plus historical above-floor credits), CREF variable annuities '
  name: TIAA Annuities
  slug: tiaa-annuities
- description: Nuveen is TIAA's wholly owned institutional asset management subsidiary with $1.5 trillion AUM (as of March 2026). Nuveen provides mutual funds, ETFs, closed-end funds, target-date series with embedde
  name: Nuveen Investments
  slug: nuveen-investments
- description: TIAA's wealth management services for individuals, including managed accounts, brokerage services, financial advisory services, life insurance, educational savings (529 plans), and banking products.
  name: TIAA Wealth Management
  slug: tiaa-wealth-management
common:
- title: ''
  type: Website
  url: https://www.tiaa.org/public
- title: ''
  type: About
  url: https://www.tiaa.org/public/about-tiaa
- title: ''
  type: Plan Sponsors
  url: https://www.tiaa.org/public/plansponsors
- title: ''
  type: Individual Investors
  url: https://www.tiaa.org/public
- title: ''
  type: Login
  url: https://auth.tiaa.org/public/authentication/login
- title: ''
  type: Nuveen
  url: https://www.nuveen.com/
- title: ''
  type: Annual Report
  url: https://www.tiaa.org/public/about-tiaa/corporate-governance
- title: ''
  type: Wikipedia
  url: https://en.wikipedia.org/wiki/TIAA
- title: ''
  type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/json-schema/tiaa-cref-retirement-account-schema.json
- title: ''
  type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/json-structure/tiaa-cref-retirement-account-structure.json
- title: ''
  type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/json-ld/tiaa-cref-context.jsonld
- title: ''
  type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/vocabulary/tiaa-cref-vocabulary.yml
created: '2026-03-24'
description: TIAA (Teachers Insurance and Annuity Association of America, formerly TIAA-CREF) is a Fortune 100 leading provider of financial services for people in the academic, research, medical, cultural, and government fields. With $1.5 trillion in assets under management, TIAA serves over 4.7 million individual customers and more than 12,000 institutional clients. Founded in 1918, TIAA invented the variable annuity in 1952 via the College Retirement Equities Fund (CREF) and is known for its TIAA Traditional fixed annuity and lifetime income solutions. TIAA wholly owns Nuveen Investments, a major institutional asset management firm. TIAA serves primarily non-profit organizations, universities, hospitals, and government entities with retirement plans including 403(b), 457(b), and 401(k) plans.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 21
  name: Tiaa Cref Context
  property_count: 22
  slug: tiaa-cref-context
layout: provider
modified: '2026-05-03'
name: TIAA-CREF
skills: []
slug: tiaa-cref
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: tiaa-cref\nname: TIAA-CREF\ndescription: >-\n  TIAA (Teachers Insurance and Annuity Association of America, formerly TIAA-CREF)\n  is a Fortune 100 leading provider of financial services for people in the academic,\n  research, medical, cultural, and government fields. With $1.5 trillion in assets\n  under management, TIAA serves over 4.7 million individual customers and more than\n  12,000 institutional clients. Founded in 1918, TIAA invented the variable annuity\n  in 1952 via the College Retirement Equities Fund (CREF) and is known for its TIAA\n  Traditional fixed annuity and lifetime income solutions. TIAA wholly owns Nuveen\n  Investments, a major institutional asset management firm. TIAA serves primarily\n  non-profit organizations, universities, hospitals, and government entities with\n  retirement plans including 403(b), 457(b), and 401(k) plans.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - 403b\n \
  \ - Annuities\n  - Asset Management\n  - Fortune 100\n  - Higher Education\n  - Institutional\n  - Insurance\n  - Investments\n  - Non Profit\n  - Nuveen\n  - Retirement\n  - TIAA\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/apis.yml\ncreated: '2026-03-24'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: tiaa-cref:tiaa-retirement-plans\n    name: TIAA Retirement Plans\n    description: >-\n      TIAA's retirement plan services for individual participants, covering\n      403(b), 457(b), 401(k), and IRA accounts. Products include TIAA\n      Traditional fixed annuity, CREF variable annuities (stock, bond, money\n      market, social choice, global equities, inflation-linked bond, equity\n      index accounts), mutual funds, and the Brokerage Window for self-directed\n      investing. TIAA RetirePlus provides custom target-date strategies with\n      embedded lifetime income for institutional clients.\n    humanURL: https://www.tiaa.org/public\n\
  \    baseURL: https://www.tiaa.org/\n    tags:\n      - 403b\n      - 457b\n      - Annuities\n      - CREF\n      - IRA\n      - Mutual Funds\n      - Retirement\n      - TIAA\n    properties:\n      - type: Website\n        url: https://www.tiaa.org/public\n      - type: Login\n        url: https://auth.tiaa.org/public/authentication/login\n      - type: Plan Sponsors\n        url: https://www.tiaa.org/public/plansponsors\n      - type: Investment Products\n        url: https://www.tiaa.org/public/invest/services/wealth-management/investment-products\n      - type: Lifetime Income\n        url: https://www.tiaa.org/public/plansponsors/lifetime-income-leader\n    contact:\n      - FN: TIAA Customer Support\n        url: https://www.tiaa.org/public/about-tiaa/contact\n\n  - aid: tiaa-cref:tiaa-annuities\n    name: TIAA Annuities\n    description: >-\n      TIAA's flagship annuity products for retirement income, including\n      TIAA Traditional (a participating fixed annuity with guaranteed\
  \ minimum\n      plus historical above-floor credits), CREF variable annuities across\n      multiple investment accounts, and the new TIAA MyChoice MYGA (a\n      flexible-premium multi-year guaranteed annuity). TIAA is rated A++ by\n      AM Best. Portfolios with TIAA Traditional have outperformed in over 90%\n      of retirement scenarios per major studies.\n    humanURL: https://www.tiaa.org/public\n    tags:\n      - Annuities\n      - Fixed Annuity\n      - Insurance\n      - Lifetime Income\n      - Retirement Income\n      - Variable Annuity\n    properties:\n      - type: Documentation\n        url: https://www.tiaa.org/public/pdf/t/tiaa-retirement-product-primer.pdf\n\n  - aid: tiaa-cref:nuveen-investments\n    name: Nuveen Investments\n    description: >-\n      Nuveen is TIAA's wholly owned institutional asset management subsidiary\n      with $1.5 trillion AUM (as of March 2026). Nuveen provides mutual funds,\n      ETFs, closed-end funds, target-date series with embedded\
  \ lifetime income\n      (Nuveen Lifecycle Income), responsible investing ESG strategies, fixed\n      income, real assets, and alternatives. Nuveen collaborates with\n      Morningstar Retirement, Transamerica, and other partners to distribute\n      TIAA Secure Income Account solutions.\n    humanURL: https://www.nuveen.com/\n    baseURL: https://www.nuveen.com/\n    tags:\n      - Asset Management\n      - ETFs\n      - Fixed Income\n      - Institutional\n      - Mutual Funds\n      - Nuveen\n      - Target Date\n    properties:\n      - type: Website\n        url: https://www.nuveen.com/\n      - type: Documentation\n        url: https://www.nuveen.com/en-us\n\n  - aid: tiaa-cref:tiaa-wealth-management\n    name: TIAA Wealth Management\n    description: >-\n      TIAA's wealth management services for individuals, including managed\n      accounts, brokerage services, financial advisory services, life insurance,\n      educational savings (529 plans), and banking products.\n    humanURL:\
  \ https://www.tiaa.org/public/invest/services/wealth-management\n    tags:\n      - Banking\n      - Brokerage\n      - Financial Advice\n      - Insurance\n      - Investments\n      - Wealth Management\n    properties:\n      - type: Documentation\n        url: https://www.tiaa.org/public/invest/services/wealth-management\n\ncommon:\n  - type: Website\n    url: https://www.tiaa.org/public\n  - type: About\n    url: https://www.tiaa.org/public/about-tiaa\n  - type: Plan Sponsors\n    url: https://www.tiaa.org/public/plansponsors\n  - type: Individual Investors\n    url: https://www.tiaa.org/public\n  - type: Login\n    url: https://auth.tiaa.org/public/authentication/login\n  - type: Nuveen\n    url: https://www.nuveen.com/\n  - type: Annual Report\n    url: https://www.tiaa.org/public/about-tiaa/corporate-governance\n  - type: Wikipedia\n    url: https://en.wikipedia.org/wiki/TIAA\n  - type: JSONSchema\n    url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/json-schema/tiaa-cref-retirement-account-schema.json\n\
  \  - type: JSONStructure\n    url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/json-structure/tiaa-cref-retirement-account-structure.json\n  - type: JSONLDContext\n    url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/json-ld/tiaa-cref-context.jsonld\n  - type: Vocabulary\n    url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/vocabulary/tiaa-cref-vocabulary.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/apis.yml
tags:
- 403b
- Annuities
- Asset Management
- Fortune 100
- Higher Education
- Institutional
- Insurance
- Investments
- Non Profit
- Nuveen
- Retirement
- TIAA
url: https://raw.githubusercontent.com/api-evangelist/tiaa-cref/refs/heads/main/apis.yml
use_cases: []
---
