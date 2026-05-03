---
api_count: 9
api_specs:
- filename: salesforcecom-rest-openapi.yml
  format: yaml
  label: Salesforce REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforcecom/refs/heads/main/openapi/salesforcecom-rest-openapi.yml
apis:
- description: The Salesforce REST API provides programmatic access to your Salesforce org data, letting you create, read, update, and delete records, execute queries, and manage org metadata. Supports OAuth 2.0 aut
  name: Salesforce REST API
  slug: rest-api
- description: 'The Salesforce Bulk API 2.0 is a specialized REST API for loading large numbers of records asynchronously. It is optimized for processing jobs that contain large data sets, supporting insert, update, '
  name: Salesforce Bulk API 2.0
  slug: bulk-api
- description: The Salesforce Streaming API lets you subscribe to changes in Salesforce data using push technology based on the Bayeux protocol. It enables real-time notifications via PushTopic events, Change Data C
  name: Salesforce Streaming API
  slug: streaming-api
- description: The Salesforce Metadata API enables you to retrieve, deploy, create, update, and delete customization information such as custom object definitions and page layouts for your organization. Used primari
  name: Salesforce Metadata API
  slug: metadata-api
- description: Salesforce Connect REST API provides access to Salesforce Experience Cloud, Files, Chatter, and community features. Enables social features, file management, user feeds, and collaboration across Sales
  name: Salesforce Connect REST API
  slug: connect-api
- description: The Marketing Cloud REST API provides access to Marketing Cloud data and functionality including email, SMS, push messaging, contact management, journeys, and data extensions. Enables programmatic man
  name: Salesforce Marketing Cloud REST API
  slug: marketing-cloud-api
- description: 'The Salesforce B2C Commerce API (SCAPI) provides RESTful access to commerce storefront functionality including products, catalogs, pricing, inventory, orders, customers, and baskets. Enables headless '
  name: Salesforce B2C Commerce API
  slug: commerce-cloud-api
- description: The Salesforce Agentforce API enables developers to build, deploy, and manage AI agents that can autonomously complete tasks across the Salesforce platform. Supports agent creation, customization, and
  name: Salesforce Agentforce API
  slug: agentforce-api
- description: The MuleSoft Anypoint Platform API enables programmatic management of APIs, integrations, and integration assets. Supports API lifecycle management, deployment, analytics, and policy enforcement acros
  name: Salesforce MuleSoft Anypoint Platform API
  slug: mulesoft-api
capabilities:
- description: 'CRM data management workflow combining Salesforce REST API record operations, SOQL querying, and SOSL search for managing accounts, contacts, leads, opportunities, and cases. Used by sales ops teams, '
  name: Salesforce CRM Data Management
  slug: crm-data-management
common:
- title: ''
  type: Website
  url: https://www.salesforce.com
- title: ''
  type: Portal
  url: https://developer.salesforce.com
- title: ''
  type: Documentation
  url: https://developer.salesforce.com/docs
- title: ''
  type: APILibrary
  url: https://developer.salesforce.com/docs/apis
- title: ''
  type: Blog
  url: https://developer.salesforce.com/blogs
- title: ''
  type: Community
  url: https://trailblazer.salesforce.com
- title: ''
  type: Pricing
  url: https://www.salesforce.com/editions-pricing/
- title: ''
  type: Status
  url: https://status.salesforce.com
- title: ''
  type: Support
  url: https://help.salesforce.com
- title: ''
  type: Signup
  url: https://www.salesforce.com/form/signup/freetrial-salesforce/
- title: ''
  type: LinkedIn
  url: https://www.linkedin.com/company/salesforce
- title: ''
  type: Twitter
  url: https://twitter.com/salesforce
- title: ''
  type: GitHubOrganization
  url: https://github.com/forcedotcom
- title: ''
  type: GitHubOrganization
  url: https://github.com/salesforcecli
- title: ''
  type: CLI
  url: https://github.com/salesforcecli/cli
- title: ''
  type: PostmanWorkspace
  url: https://www.postman.com/salesforce-developers/salesforce-developers
- title: ''
  type: ChangeLog
  url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/api_rest_whats_new.htm
- title: ''
  type: Trailhead
  url: https://trailhead.salesforce.com
created: '2026-03-24'
description: Salesforce is a global leader in customer relationship management (CRM) software and cloud-based applications. The Salesforce Platform provides a comprehensive suite of APIs for sales, service, marketing, commerce, integration, analytics, and platform development including Agentforce AI capabilities.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Salesforcecom Context
  property_count: 6
  slug: salesforcecom-context
layout: provider
modified: '2026-05-02'
name: Salesforce
rules:
- name: Salesforce API Rules
  rule_count: 14
  severity_counts:
    error: 3
    hint: 0
    info: 5
    warn: 6
  slug: salesforcecom-rules
skills: []
slug: salesforcecom
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: salesforcecom\nurl: https://raw.githubusercontent.com/api-evangelist/salesforcecom/refs/heads/main/apis.yml\nname: Salesforce\ndescription: >-\n  Salesforce is a global leader in customer relationship management (CRM) software\n  and cloud-based applications. The Salesforce Platform provides a comprehensive\n  suite of APIs for sales, service, marketing, commerce, integration, analytics,\n  and platform development including Agentforce AI capabilities.\ntype: Index\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - CRM\n  - Cloud\n  - Sales\n  - Marketing\n  - Automation\n  - AI\naccess: 3rd-Party\ncreated: '2026-03-24'\nmodified: '2026-05-02'\nx-profiled: '2026-05'\nspecificationVersion: '0.19'\napis:\n  - aid: salesforcecom:rest-api\n    name: Salesforce REST API\n    description: >-\n      The Salesforce REST API provides programmatic access to your Salesforce org\n      data, letting you create, read, update, and delete records,\
  \ execute queries,\n      and manage org metadata. Supports OAuth 2.0 authentication and returns JSON\n      or XML responses.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest\n    tags:\n      - CRM\n      - Data\n      - Records\n      - Query\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest\n      - type: Versioning\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/dome_versions.htm\n      - type: OpenAPI\n        url: openapi/salesforcecom-rest-openapi.yml\n      - type: Summary\n        data:\n          numberOfAPITags: 6\n          numberOfAPIGetMethods: 9\n          numberOfAPIPostMethods: 3\n          numberOfAPIPatchMethods: 1\n          numberOfAPIDeleteMethods: 1\n          numberOfAPIOperations: 14\n\n  - aid: salesforcecom:bulk-api\n    name: Salesforce Bulk API 2.0\n    description: >-\n      The Salesforce Bulk API\
  \ 2.0 is a specialized REST API for loading large\n      numbers of records asynchronously. It is optimized for processing jobs that\n      contain large data sets, supporting insert, update, upsert, delete, and query\n      operations.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch\n    tags:\n      - Bulk Data\n      - ETL\n      - Async\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_asynch.meta/api_asynch\n\n  - aid: salesforcecom:streaming-api\n    name: Salesforce Streaming API\n    description: >-\n      The Salesforce Streaming API lets you subscribe to changes in Salesforce\n      data using push technology based on the Bayeux protocol. It enables real-time\n      notifications via PushTopic events, Change Data Capture, Platform Events,\n      and Generic Events.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming\n    tags:\n\
  \      - Streaming\n      - Events\n      - Real-Time\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_streaming.meta/api_streaming\n\n  - aid: salesforcecom:metadata-api\n    name: Salesforce Metadata API\n    description: >-\n      The Salesforce Metadata API enables you to retrieve, deploy, create, update,\n      and delete customization information such as custom object definitions and\n      page layouts for your organization. Used primarily by developer tools and\n      CI/CD pipelines.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta\n    tags:\n      - Metadata\n      - DevOps\n      - Configuration\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.api_meta.meta/api_meta\n\n  - aid: salesforcecom:connect-api\n    name: Salesforce Connect REST API\n    description: >-\n      Salesforce Connect REST API provides access\
  \ to Salesforce Experience Cloud,\n      Files, Chatter, and community features. Enables social features, file management,\n      user feeds, and collaboration across Salesforce orgs.\n    humanURL: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi\n    tags:\n      - Connect\n      - Chatter\n      - Community\n      - Files\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/atlas.en-us.chatterapi.meta/chatterapi\n\n  - aid: salesforcecom:marketing-cloud-api\n    name: Salesforce Marketing Cloud REST API\n    description: >-\n      The Marketing Cloud REST API provides access to Marketing Cloud data and\n      functionality including email, SMS, push messaging, contact management,\n      journeys, and data extensions. Enables programmatic management of marketing\n      campaigns and subscriber data.\n    humanURL: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api.html\n    tags:\n  \
  \    - Marketing\n      - Email\n      - SMS\n      - Campaigns\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/marketing/marketing-cloud/guide/rest-api.html\n\n  - aid: salesforcecom:commerce-cloud-api\n    name: Salesforce B2C Commerce API\n    description: >-\n      The Salesforce B2C Commerce API (SCAPI) provides RESTful access to commerce\n      storefront functionality including products, catalogs, pricing, inventory,\n      orders, customers, and baskets. Enables headless commerce implementations.\n    humanURL: https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/b2c-commerce-api.html\n    tags:\n      - Commerce\n      - Ecommerce\n      - Storefront\n      - B2C\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/docs/commerce/b2c-commerce/guide/b2c-commerce-api.html\n\n  - aid: salesforcecom:agentforce-api\n    name: Salesforce Agentforce API\n    description: >-\n      The\
  \ Salesforce Agentforce API enables developers to build, deploy, and manage\n      AI agents that can autonomously complete tasks across the Salesforce platform.\n      Supports agent creation, customization, and integration with the Agentforce\n      360 Platform.\n    humanURL: https://developer.salesforce.com/agentforce\n    tags:\n      - AI\n      - Agents\n      - Automation\n      - Agentforce\n    properties:\n      - type: Documentation\n        url: https://developer.salesforce.com/agentforce\n\n  - aid: salesforcecom:mulesoft-api\n    name: Salesforce MuleSoft Anypoint Platform API\n    description: >-\n      The MuleSoft Anypoint Platform API enables programmatic management of APIs,\n      integrations, and integration assets. Supports API lifecycle management,\n      deployment, analytics, and policy enforcement across the MuleSoft integration\n      platform.\n    humanURL: https://docs.mulesoft.com/mule-runtime/latest/\n    tags:\n      - Integration\n      - MuleSoft\n\
  \      - API Management\n      - iPaaS\n    properties:\n      - type: Documentation\n        url: https://docs.mulesoft.com/mule-runtime/latest/\n\ncommon:\n  - type: Website\n    url: https://www.salesforce.com\n  - type: Portal\n    url: https://developer.salesforce.com\n  - type: Documentation\n    url: https://developer.salesforce.com/docs\n  - type: APILibrary\n    url: https://developer.salesforce.com/docs/apis\n  - type: Blog\n    url: https://developer.salesforce.com/blogs\n  - type: Community\n    url: https://trailblazer.salesforce.com\n  - type: Pricing\n    url: https://www.salesforce.com/editions-pricing/\n  - type: Status\n    url: https://status.salesforce.com\n  - type: Support\n    url: https://help.salesforce.com\n  - type: Signup\n    url: https://www.salesforce.com/form/signup/freetrial-salesforce/\n  - type: LinkedIn\n    url: https://www.linkedin.com/company/salesforce\n  - type: Twitter\n    url: https://twitter.com/salesforce\n  - type: GitHubOrganization\n   \
  \ url: https://github.com/forcedotcom\n  - type: GitHubOrganization\n    url: https://github.com/salesforcecli\n  - type: CLI\n    url: https://github.com/salesforcecli/cli\n  - type: PostmanWorkspace\n    url: https://www.postman.com/salesforce-developers/salesforce-developers\n  - type: ChangeLog\n    url: https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/api_rest_whats_new.htm\n  - type: Trailhead\n    url: https://trailhead.salesforce.com\n\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/salesforcecom/refs/heads/main/apis.yml
tags:
- CRM
- Cloud
- Sales
- Marketing
- Automation
- AI
url: https://raw.githubusercontent.com/api-evangelist/salesforcecom/refs/heads/main/apis.yml
use_cases: []
---
