---
api_count: 1
apis:
- description: The AmeriCorps Open Data portal provides programmatic access to AmeriCorps research, evaluation, and program datasets via the Socrata Open Data API (SODA). The portal includes datasets on program outc
  name: AmeriCorps Open Data SODA API
  slug: americorps-open-data-soda-api
common:
- title: ''
  type: Website
  url: https://americorps.gov
- title: ''
  type: Portal
  url: https://data.americorps.gov
- title: ''
  type: DataAPI
  url: https://data.americorps.gov/api/views
- title: ''
  type: GettingStarted
  url: https://dev.socrata.com/docs/endpoints.html
- title: ''
  type: GitHubOrganization
  url: https://github.com/americorps
created: '2024-11-21'
description: AmeriCorps is a federal agency that engages millions of Americans in service to their communities through programs including AmeriCorps State and National, AmeriCorps VISTA, AmeriCorps NCCC, AmeriCorps Seniors, and the Volunteer Generation Fund. Established in 1993 under the Corporation for National and Community Service (CNCS), AmeriCorps addresses critical community needs in education, disaster response, environmental conservation, economic opportunity, and healthy futures. The agency operates the AmeriCorps Open Data portal (data.americorps.gov) providing programmatic access to research, evaluation, and program data via the Socrata Open Data API (SODA).
features:
- description: Program engaging more than 75,000 Americans in intensive service through nonprofits, schools, public agencies, and community organizations addressing critical needs across all 50 states.
  name: AmeriCorps State and National
- description: Volunteers in Service to America (VISTA) program placing members with nonprofits and public agencies to build capacity and fight poverty.
  name: AmeriCorps VISTA
- description: National Civilian Community Corps residential service program for young adults completing team-based service projects on environmental and disaster relief efforts.
  name: AmeriCorps NCCC
- description: Programs engaging adults 55 and older in volunteer service through RSVP, Foster Grandparents, and Senior Companions programs.
  name: AmeriCorps Seniors
- description: Research and evaluation data portal (data.americorps.gov) providing SODA API access to program effectiveness studies, member outcome data, and ROI analyses.
  name: Evidence Exchange Open Data
- description: Grant program supporting organizations that recruit, manage, and support volunteers to meet critical community needs.
  name: Volunteer Generation Fund
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: Standard Socrata SODA API integration enabling applications to query, filter, and aggregate AmeriCorps program data programmatically.
  name: Socrata Open Data API
- description: OData V2 and V4 endpoints enabling connection to Microsoft Excel, Tableau, Power BI, and other business intelligence tools.
  name: OData Endpoints
- description: AmeriCorps eGrants system for grantee organizations to submit applications, manage awards, and report on AmeriCorps program activities.
  name: eGrants Grant Management System
layout: provider
modified: '2026-04-19'
name: AmeriCorps
skills: []
slug: americorps
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: americorps\nurl: https://raw.githubusercontent.com/api-evangelist/americorps/refs/heads/main/apis.yml\nname: AmeriCorps\ndescription: >-\n  AmeriCorps is a federal agency that engages millions of Americans in service to their\n  communities through programs including AmeriCorps State and National, AmeriCorps VISTA,\n  AmeriCorps NCCC, AmeriCorps Seniors, and the Volunteer Generation Fund. Established in\n  1993 under the Corporation for National and Community Service (CNCS), AmeriCorps addresses\n  critical community needs in education, disaster response, environmental conservation,\n  economic opportunity, and healthy futures. The agency operates the AmeriCorps Open Data\n  portal (data.americorps.gov) providing programmatic access to research, evaluation, and\n  program data via the Socrata Open Data API (SODA).\ntags:\n  - Federal Government\n  - National Service\n  - Volunteerism\n  - Community Development\n  - Civic Engagement\n  - Education\n  - Disaster Response\n\
  \  - Environmental Conservation\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\naccess: 3rd-Party\napis:\n  - aid: americorps:americorps-open-data-soda-api\n    name: AmeriCorps Open Data SODA API\n    tags:\n      - Open Data\n      - Research\n      - Evaluation\n      - National Service\n    humanURL: https://data.americorps.gov\n    baseURL: https://data.americorps.gov/resource\n    properties:\n      - url: https://data.americorps.gov\n        type: Documentation\n      - url: https://data.americorps.gov/api/views\n        type: DataAPI\n    description: >-\n      The AmeriCorps Open Data portal provides programmatic access to AmeriCorps research,\n      evaluation, and program datasets via the Socrata Open Data API (SODA). The portal\n      includes datasets on program outcomes, member experiences, return on investment\n      studies, evidence snapshots for each AmeriCorps program, and evaluation reports.\n      Data is available in\
  \ JSON, CSV, XML, and RDF formats, with OData endpoints for\n      connecting to tools like Excel and Tableau.\ncommon:\n  - type: Website\n    url: https://americorps.gov\n  - type: Portal\n    url: https://data.americorps.gov\n    name: AmeriCorps Open Data Portal\n  - type: DataAPI\n    url: https://data.americorps.gov/api/views\n    name: SODA Dataset Discovery Endpoint\n  - type: GettingStarted\n    url: https://dev.socrata.com/docs/endpoints.html\n    name: Socrata SODA API Documentation\n  - type: GitHubOrganization\n    url: https://github.com/americorps\n    name: AmeriCorps GitHub\n  - type: Features\n    data:\n      - name: AmeriCorps State and National\n        description: >-\n          Program engaging more than 75,000 Americans in intensive service through\n          nonprofits, schools, public agencies, and community organizations addressing\n          critical needs across all 50 states.\n      - name: AmeriCorps VISTA\n        description: >-\n          Volunteers in\
  \ Service to America (VISTA) program placing members with\n          nonprofits and public agencies to build capacity and fight poverty.\n      - name: AmeriCorps NCCC\n        description: >-\n          National Civilian Community Corps residential service program for young adults\n          completing team-based service projects on environmental and disaster relief efforts.\n      - name: AmeriCorps Seniors\n        description: >-\n          Programs engaging adults 55 and older in volunteer service through RSVP,\n          Foster Grandparents, and Senior Companions programs.\n      - name: Evidence Exchange Open Data\n        description: >-\n          Research and evaluation data portal (data.americorps.gov) providing SODA API\n          access to program effectiveness studies, member outcome data, and ROI analyses.\n      - name: Volunteer Generation Fund\n        description: >-\n          Grant program supporting organizations that recruit, manage, and support\n          volunteers\
  \ to meet critical community needs.\n  - type: UseCases\n    data:\n      - name: Program Evaluation Research\n        description: >-\n          Accessing AmeriCorps program evaluation reports and impact data via the SODA\n          API to conduct independent research on national service effectiveness.\n      - name: Grant Management and Reporting\n        description: >-\n          Partners and grantees accessing program data and reporting resources to\n          manage AmeriCorps grants and measure member outcomes.\n      - name: Volunteer Engagement Analytics\n        description: >-\n          Analyzing volunteer engagement patterns, member satisfaction data, and\n          civic participation trends using AmeriCorps open datasets.\n      - name: Policy and Advocacy Research\n        description: >-\n          Accessing return-on-investment studies, evidence snapshots, and program\n          outcome data to support policy development and advocacy for national service.\n  - type: Integrations\n\
  \    data:\n      - name: Socrata Open Data API\n        description: >-\n          Standard Socrata SODA API integration enabling applications to query, filter,\n          and aggregate AmeriCorps program data programmatically.\n      - name: OData Endpoints\n        description: >-\n          OData V2 and V4 endpoints enabling connection to Microsoft Excel, Tableau,\n          Power BI, and other business intelligence tools.\n      - name: eGrants Grant Management System\n        description: >-\n          AmeriCorps eGrants system for grantee organizations to submit applications,\n          manage awards, and report on AmeriCorps program activities.\ncreated: '2024-11-21'\nmodified: '2026-04-19'\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\nspecificationVersion: '0.19'\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/americorps/refs/heads/main/apis.yml
tags:
- Federal Government
- National Service
- Volunteerism
- Community Development
- Civic Engagement
- Education
- Disaster Response
- Environmental Conservation
url: https://raw.githubusercontent.com/api-evangelist/americorps/refs/heads/main/apis.yml
use_cases:
- description: Accessing AmeriCorps program evaluation reports and impact data via the SODA API to conduct independent research on national service effectiveness.
  name: Program Evaluation Research
- description: Partners and grantees accessing program data and reporting resources to manage AmeriCorps grants and measure member outcomes.
  name: Grant Management and Reporting
- description: Analyzing volunteer engagement patterns, member satisfaction data, and civic participation trends using AmeriCorps open datasets.
  name: Volunteer Engagement Analytics
- description: Accessing return-on-investment studies, evidence snapshots, and program outcome data to support policy development and advocacy for national service.
  name: Policy and Advocacy Research
---
