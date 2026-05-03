---
api_count: 1
api_specs:
- filename: Compensation.yaml
  format: yaml
  label: Workday Advanced Compensation API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Compensation/v41.1/Compensation.yaml
apis:
- description: RESTful and SOAP APIs for managing compensation plans, merit increases, bonuses, stock awards, and compensation budgets.
  name: Workday Advanced Compensation API
  slug: ''
common:
- title: ''
  type: Developer Portal
  url: https://developer.workday.com/
- title: ''
  type: API Status
  url: https://status.workday.com/
- title: ''
  type: Terms of Service
  url: https://www.workday.com/en-us/legal.html
- title: ''
  type: Privacy Policy
  url: https://www.workday.com/en-us/privacy.html
- title: ''
  type: Security
  url: https://www.workday.com/en-us/why-workday/security-trust.html
- title: ''
  type: Rate Limits
  url: https://doc.workday.com/r/Workday_Web_Services/Workday_Web_Services_Directory/Web_Service_Rate_Limiting
- title: ''
  type: Sandbox Environment
  url: https://doc.workday.com/r/en-us/workday-studio/workday-studio-user-guide/sandboxes
- title: ''
  type: SDKs
  url: https://github.com/Workday
created: '2024-01-15'
description: API for managing compensation plans, budgets, allocations, and related processes in Workday.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-03-16'
name: Workday Advanced Compensation
skills: []
slug: workday-advanced-compensation
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: workday-advanced-compensation\nname: Workday Advanced Compensation\ndescription: >-\n  API for managing compensation plans, budgets, allocations, and related processes\n  in Workday.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/workday-advanced-compensation/refs/heads/main/apis.yml\ncreated: '2024-01-15'\nmodified: '2026-03-16'\nspecificationVersion: '0.19'\napis:\n  - name: Workday Advanced Compensation API\n    description: >-\n      RESTful and SOAP APIs for managing compensation plans, merit increases, bonuses,\n      stock awards, and compensation budgets.\n    image: https://www.workday.com/content/dam/web/images/logo.png\n    humanUrl: https://community.workday.com/sites/default/files/file-hosting/productionapi/Compensation/v41.1/index.html\n    baseUrl: https://wd2-impl-services1.workday.com/ccx/service\n    tags:\n      - Bonuses\n      - Compensation\n      - HR\n\
  \      - Merit\n      - Payroll\n      - Salary Planning\n      - Stock Awards\n    properties:\n      - type: Documentation\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Compensation/v41.1/index.html\n      - type: OpenAPI\n        url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Compensation/v41.1/Compensation.yaml\n      - type: Authentication\n        url: https://doc.workday.com/admin-guide/en-us/integration-security/securing-workday-web-services/authentication-types.html\n      - type: Versioning\n        url: https://doc.workday.com/r/Workday_Web_Services/Workday_Web_Services_Directory/About_Workday_Web_Services_Versioning\n    contact:\n      - type: Support\n        url: https://www.workday.com/en-us/customer-experience/support.html\n      - type: Community\n        url: https://community.workday.com/\n    operations:\n      - name: Get Compensation Plans\n        description: Retrieve compensation plan\
  \ details including eligibility rules and budget pools\n        method: GET\n        path: /Compensation_Plan\n      - name: Submit Compensation Changes\n        description: Submit compensation change requests for employees\n        method: POST\n        path: /Submit_Compensation_Change_Request\n      - name: Get Compensation Budgets\n        description: Retrieve compensation budget information and allocations\n        method: GET\n        path: /Compensation_Budget\n      - name: Get Merit Plans\n        description: Retrieve merit increase plan configurations\n        method: GET\n        path: /Merit_Plan\n      - name: Get Bonus Plans\n        description: Retrieve bonus plan details and award criteria\n        method: GET\n        path: /Bonus_Plan\n      - name: Get Stock Plans\n        description: Retrieve stock and equity compensation plan information\n        method: GET\n        path: /Stock_Plan\n      - name: Get Compensation Grades\n        description: Retrieve compensation\
  \ grade profiles and ranges\n        method: GET\n        path: /Compensation_Grade_Profile\n      - name: Get Salary Survey Data\n        description: Retrieve market survey data and benchmarking information\n        method: GET\n        path: /Salary_Survey_Data\n      - name: Get Compensation Review Process\n        description: Retrieve compensation review process status and workflow\n        method: GET\n        path: /Compensation_Review_Process\n      - name: Update Compensation Package\n        description: Update employee compensation package details\n        method: PUT\n        path: /Compensation_Package\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\ninclude:\n  - name: Workday Human Capital Management\n    url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Human_Resources/index.html\n  - name: Workday Payroll\n    url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Payroll/index.html\ncommon:\n\
  \  - type: Developer Portal\n    url: https://developer.workday.com/\n  - type: API Status\n    url: https://status.workday.com/\n  - type: Terms of Service\n    url: https://www.workday.com/en-us/legal.html\n  - type: Privacy Policy\n    url: https://www.workday.com/en-us/privacy.html\n  - type: Security\n    url: https://www.workday.com/en-us/why-workday/security-trust.html\n  - type: Rate Limits\n    url: https://doc.workday.com/r/Workday_Web_Services/Workday_Web_Services_Directory/Web_Service_Rate_Limiting\n  - type: Sandbox Environment\n    url: https://doc.workday.com/r/en-us/workday-studio/workday-studio-user-guide/sandboxes\n  - type: SDKs\n    url: https://github.com/Workday\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/workday-advanced-compensation/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/workday-advanced-compensation/refs/heads/main/apis.yml
use_cases: []
---
