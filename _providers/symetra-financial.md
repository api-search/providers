---
api_count: 3
apis:
- description: Symetra's Benefits Administration API enables HR platforms, benefits administrators, and technology partners to integrate with Symetra's group benefits products. The API supports automated data exchan
  name: Symetra Benefits Administration API
  slug: symetra-benefits-api
- description: API for accessing Symetra annuity product information, rates, and illustrations. Supports fixed deferred annuities, fixed indexed annuities, registered index-linked annuities (RILA), and income annuit
  name: Symetra Annuities API
  slug: symetra-annuities-api
- description: API supporting Symetra's life insurance products including term life, SwiftTerm (instant-issue life insurance), and permanent life insurance. Enables financial advisors and distribution partners to ac
  name: Symetra Life Insurance API
  slug: symetra-life-insurance-api
common:
- title: ''
  type: Website
  url: https://www.symetra.com
- title: ''
  type: Login
  url: https://accounts.symetra.com/ui/login
- title: ''
  type: Contact
  url: https://www.symetra.com/contact-us/
- title: ''
  type: Privacy Policy
  url: https://www.symetra.com/privacy-policy/
- title: ''
  type: Help Center
  url: https://www.symetra.com/help-center/
- title: ''
  type: Blog
  url: https://www.symetra.com/benefits-blog-posts/
- title: ''
  type: Technology Solutions
  url: https://www.symetra.com/learn/articles-for-employers/technology-solutions/
- title: ''
  type: For Employers
  url: https://www.symetra.com/for-employers/
- title: ''
  type: For Brokers
  url: https://www.symetra.com/for-brokers/
created: '2026-05-03'
description: Symetra Financial Corporation is a diversified financial services company headquartered in Bellevue, Washington, providing employee benefits, annuities, and life insurance products to individuals, families, and businesses through independent advisors and financial institutions. A subsidiary of Sumitomo Life Insurance Company since 2016, Symetra offers medical stop-loss insurance, group life and disability income protection, supplemental health coverage, fixed and indexed annuities, registered index-linked annuities, income annuities, term life, and permanent life insurance. The company offers API and EDI-based data integrations for benefits administrators and HR platforms.
features: []
image: https://www.symetra.com/favicon.ico
integrations: []
jsonld:
- class_count: 3
  name: Symetra Financial Context
  property_count: 37
  slug: symetra-financial-context
layout: provider
modified: '2026-05-03'
name: Symetra Financial
skills: []
slug: symetra-financial
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: symetra-financial\nurl: https://raw.githubusercontent.com/api-evangelist/symetra-financial/refs/heads/main/apis.yml\nname: Symetra Financial\ndescription: >-\n  Symetra Financial Corporation is a diversified financial services company\n  headquartered in Bellevue, Washington, providing employee benefits, annuities,\n  and life insurance products to individuals, families, and businesses through\n  independent advisors and financial institutions. A subsidiary of Sumitomo Life\n  Insurance Company since 2016, Symetra offers medical stop-loss insurance, group\n  life and disability income protection, supplemental health coverage, fixed and\n  indexed annuities, registered index-linked annuities, income annuities, term\n  life, and permanent life insurance. The company offers API and EDI-based data\n  integrations for benefits administrators and HR platforms.\nimage: https://www.symetra.com/favicon.ico\ntags:\n  - Annuities\n  - Benefits\n  - Employee Benefits\n  - Financial\
  \ Services\n  - Insurance\n  - Life Insurance\n  - Stop Loss\ncreated: '2026-05-03'\nmodified: '2026-05-03'\nspecificationVersion: '0.19'\napis:\n  - aid: symetra-financial:symetra-benefits-api\n    name: Symetra Benefits Administration API\n    description: >-\n      Symetra's Benefits Administration API enables HR platforms, benefits\n      administrators, and technology partners to integrate with Symetra's group\n      benefits products. The API supports automated data exchange for enrollment,\n      eligibility, claims, short-term disability, absence management, and\n      stop-loss insurance. It provides single sign-on (SSO) connectivity for\n      evidence of insurability (EOI) and automated decision status updates,\n      integrating with platforms such as Workday.\n    humanURL: https://www.symetra.com/learn/articles-for-employers/technology-solutions/\n    baseURL: https://api.symetra.com\n    tags:\n      - Benefits Administration\n      - Claims\n      - EDI\n      - Eligibility\n\
  \      - Employee Benefits\n      - Enrollment\n      - HR Integration\n      - Insurance\n      - Stop Loss\n    properties:\n      - type: Documentation\n        url: https://www.symetra.com/learn/articles-for-employers/technology-solutions/\n      - type: Website\n        url: https://www.symetra.com/for-employers/\n  - aid: symetra-financial:symetra-annuities-api\n    name: Symetra Annuities API\n    description: >-\n      API for accessing Symetra annuity product information, rates, and\n      illustrations. Supports fixed deferred annuities, fixed indexed annuities,\n      registered index-linked annuities (RILA), and income annuities. Used by\n      financial institutions and independent advisors to generate product\n      illustrations, submit new business, and manage in-force contracts.\n    humanURL: https://www.symetra.com/annuities/\n    baseURL: https://api.symetra.com\n    tags:\n      - Annuities\n      - Financial Advisors\n      - Financial Services\n      - Fixed Annuities\n\
  \      - Income Annuities\n      - Indexed Annuities\n      - Insurance\n      - RILA\n      - Retirement\n    properties:\n      - type: Documentation\n        url: https://www.symetra.com/annuities/\n      - type: Website\n        url: https://www.symetra.com/annuities/\n  - aid: symetra-financial:symetra-life-insurance-api\n    name: Symetra Life Insurance API\n    description: >-\n      API supporting Symetra's life insurance products including term life,\n      SwiftTerm (instant-issue life insurance), and permanent life insurance.\n      Enables financial advisors and distribution partners to access product\n      information, request quotes, submit applications, track underwriting\n      decisions, and manage in-force policies.\n    humanURL: https://www.symetra.com/life-insurance/\n    baseURL: https://api.symetra.com\n    tags:\n      - Financial Advisors\n      - Insurance\n      - Life Insurance\n      - Permanent Life\n      - Policy Management\n      - Term Life\n      - Underwriting\n\
  \    properties:\n      - type: Documentation\n        url: https://www.symetra.com/life-insurance/\n      - type: Website\n        url: https://www.symetra.com/life-insurance/\ncommon:\n  - type: Website\n    url: https://www.symetra.com\n  - type: Login\n    url: https://accounts.symetra.com/ui/login\n  - type: Contact\n    url: https://www.symetra.com/contact-us/\n  - type: Privacy Policy\n    url: https://www.symetra.com/privacy-policy/\n  - type: Help Center\n    url: https://www.symetra.com/help-center/\n  - type: Blog\n    url: https://www.symetra.com/benefits-blog-posts/\n  - type: Technology Solutions\n    url: https://www.symetra.com/learn/articles-for-employers/technology-solutions/\n  - type: For Employers\n    url: https://www.symetra.com/for-employers/\n  - type: For Brokers\n    url: https://www.symetra.com/for-brokers/\nmaintainers:\n  - FN: API Evangelist\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/symetra-financial/refs/heads/main/apis.yml
tags:
- Annuities
- Benefits
- Employee Benefits
- Financial Services
- Insurance
- Life Insurance
- Stop Loss
url: https://raw.githubusercontent.com/api-evangelist/symetra-financial/refs/heads/main/apis.yml
use_cases: []
---
