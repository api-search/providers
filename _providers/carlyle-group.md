---
api_count: 3
apis:
- description: LP Connect is Carlyle's secure portal for Limited Partners and their advisors to access fund reporting, capital calls and distributions, investor statements, tax documents, and ad-hoc diligence materi
  name: Carlyle LP Connect Portal
  slug: lp-connect
- description: Carlyle Direct Lending operates a dedicated investor portal for clients of Carlyle's direct lending funds and BDC vehicles. The portal supports modern web browsers and is used for reporting, distribut
  name: Carlyle Direct Lending Investor Portal
  slug: direct-lending-portal
- description: The Carlyle Global Portfolio Solutions Portal (resources.carlyle.com) is the secure workspace used by Carlyle's portfolio operations team, portfolio company executives, and advisors to share tools, te
  name: Carlyle Global Portfolio Solutions Portal
  slug: global-portfolio-solutions
common:
- title: ''
  type: Website
  url: https://www.carlyle.com/
- title: ''
  type: Investor Relations
  url: https://ir.carlyle.com/
- title: ''
  type: Public Investors
  url: https://ir.carlyle.com/
- title: ''
  type: LP Connect
  url: https://lpconnect.carlyle.com
- title: ''
  type: Direct Lending Portal
  url: https://directlending.carlyle.com
- title: ''
  type: Global Portfolio Solutions Portal
  url: https://resources.carlyle.com/carlyle/login
- title: ''
  type: AlpInvest
  url: https://www.carlylealpinvest.com/
- title: ''
  type: Login
  url: https://www.carlyle.com/user/login
- title: ''
  type: About
  url: https://www.carlyle.com/about-carlyle
- title: ''
  type: Careers
  url: https://www.carlyle.com/careers
- title: ''
  type: Contact
  url: https://www.carlyle.com/contact-us
- title: ''
  type: Privacy Policy
  url: https://www.carlyle.com/privacy-policy
- title: ''
  type: Terms of Service
  url: https://www.carlyle.com/terms-of-use
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/the-carlyle-group
- title: ''
  type: X
  url: https://x.com/OneCarlyle
created: '2026-03-23'
description: 'The Carlyle Group (NASDAQ: CG) is a global investment firm that deploys private capital across Global Private Equity, Global Credit, Global Investment Solutions (AlpInvest), and carveouts such as Carlyle Direct Lending. Carlyle does not publish a public developer API. Institutional LPs, co-investors, and portfolio companies interact with the firm through a set of private, authentication-gated portals: LP Connect for fund investors, Carlyle Direct Lending''s portal for direct lending clients, the Carlyle Global Portfolio Solutions (resources.carlyle.com) portal, and brand experiences such as Carlyle & Co. Integrations with fund administrators, custodians, and placement agents run through bespoke secure file exchange and vendor-managed APIs.'
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-23'
name: The Carlyle Group
skills: []
slug: carlyle-group
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: carlyle-group\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/carlyle-group/refs/heads/main/apis.yml\nname: The Carlyle Group\ndescription: >-\n  The Carlyle Group (NASDAQ: CG) is a global investment firm that\n  deploys private capital across Global Private Equity, Global\n  Credit, Global Investment Solutions (AlpInvest), and carveouts\n  such as Carlyle Direct Lending. Carlyle does not publish a public\n  developer API. Institutional LPs, co-investors, and portfolio\n  companies interact with the firm through a set of private,\n  authentication-gated portals: LP Connect for fund investors,\n  Carlyle Direct Lending's portal for direct lending clients,\n  the Carlyle Global Portfolio Solutions (resources.carlyle.com)\n  portal, and brand experiences such as Carlyle & Co. Integrations\n  with fund administrators, custodians, and placement agents run\n  through bespoke secure file exchange and vendor-managed APIs.\ntype: Index\nx-type: company\nposition: Consumer\n\
  access: Partner\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Alternative Assets\n  - Asset Management\n  - Direct Lending\n  - Global Credit\n  - Investment Firm\n  - Investor Portal\n  - Limited Partners\n  - Private Credit\n  - Private Equity\n  - Real Assets\ncreated: '2026-03-23'\nmodified: '2026-04-23'\nspecificationVersion: '0.19'\napis:\n  - aid: carlyle-group:lp-connect\n    name: Carlyle LP Connect Portal\n    description: >-\n      LP Connect is Carlyle's secure portal for Limited Partners and\n      their advisors to access fund reporting, capital calls and\n      distributions, investor statements, tax documents, and ad-hoc\n      diligence materials. Access is provisioned by Carlyle on\n      request. There is no public API; the portal is a web\n      application with email-based credential recovery.\n    humanURL: https://lpconnect.carlyle.com\n    tags:\n      - Investor Portal\n      - Limited Partners\n      - Private Equity\n\
  \    properties:\n      - url: https://lpconnect.carlyle.com\n        type: Portal\n      - url: https://lpconnect.carlyle.com/login.jsp\n        type: Login\n    x-features:\n      - LP fund reporting and capital activity\n      - Capital call and distribution notices\n      - Tax documents (K-1s, PFIC) and investor statements\n      - Ad-hoc diligence and side letter documents\n      - Email-based credential recovery\n    x-use-cases:\n      - Family office LP operations\n      - Pension and endowment staff reporting\n      - Fund-of-funds due diligence workflows\n      - Third-party LP administration\n  - aid: carlyle-group:direct-lending-portal\n    name: Carlyle Direct Lending Investor Portal\n    description: >-\n      Carlyle Direct Lending operates a dedicated investor portal for\n      clients of Carlyle's direct lending funds and BDC vehicles. The\n      portal supports modern web browsers and is used for reporting,\n      distributions, and investor communications.\n    humanURL:\
  \ https://directlending.carlyle.com\n    tags:\n      - BDC\n      - Direct Lending\n      - Investor Portal\n      - Private Credit\n    properties:\n      - url: https://directlending.carlyle.com\n        type: Portal\n    x-features:\n      - BDC and direct lending fund reporting\n      - Distribution and capital activity notices\n      - Modern browser support (Chrome, Edge, Safari, Firefox, Opera)\n    x-use-cases:\n      - BDC shareholder account access\n      - Institutional direct lending LP reporting\n      - RIA/advisor portfolio oversight\n  - aid: carlyle-group:global-portfolio-solutions\n    name: Carlyle Global Portfolio Solutions Portal\n    description: >-\n      The Carlyle Global Portfolio Solutions Portal (resources.carlyle.com)\n      is the secure workspace used by Carlyle's portfolio operations\n      team, portfolio company executives, and advisors to share tools,\n      templates, and operational playbooks across the portfolio.\n    humanURL: https://resources.carlyle.com/carlyle/login\n\
  \    tags:\n      - Portfolio Operations\n      - Portfolio Solutions\n      - Private Equity\n    properties:\n      - url: https://resources.carlyle.com/carlyle/login\n        type: Portal\n    x-features:\n      - Portfolio operations resources and templates\n      - Executive community and tooling\n      - Secure document sharing\n    x-use-cases:\n      - Portco finance and HR standardization\n      - Value-creation playbook distribution\n      - M&A and carve-out support\ncommon:\n  - type: Website\n    url: https://www.carlyle.com/\n  - type: Investor Relations\n    url: https://ir.carlyle.com/\n  - type: Public Investors\n    url: https://ir.carlyle.com/\n  - type: LP Connect\n    url: https://lpconnect.carlyle.com\n  - type: Direct Lending Portal\n    url: https://directlending.carlyle.com\n  - type: Global Portfolio Solutions Portal\n    url: https://resources.carlyle.com/carlyle/login\n  - type: AlpInvest\n    url: https://www.carlylealpinvest.com/\n  - type: Login\n    url:\
  \ https://www.carlyle.com/user/login\n  - type: About\n    url: https://www.carlyle.com/about-carlyle\n  - type: Careers\n    url: https://www.carlyle.com/careers\n  - type: Contact\n    url: https://www.carlyle.com/contact-us\n  - type: Privacy Policy\n    url: https://www.carlyle.com/privacy-policy\n  - type: Terms of Service\n    url: https://www.carlyle.com/terms-of-use\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/the-carlyle-group\n  - type: X\n    url: https://x.com/OneCarlyle\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/carlyle-group/refs/heads/main/apis.yml
tags:
- Alternative Assets
- Asset Management
- Direct Lending
- Global Credit
- Investment Firm
- Investor Portal
- Limited Partners
- Private Credit
- Private Equity
- Real Assets
url: https://raw.githubusercontent.com/api-evangelist/carlyle-group/refs/heads/main/apis.yml
use_cases: []
---
