---
api_count: 11
api_specs:
- filename: sitecore-xm-cloud-rest-api-openapi.yml
  format: yaml
  label: Sitecore XM Cloud REST API
  slug: xm-cloud-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-xm-cloud-rest-api-openapi.yml
- filename: sitecore-cdp-rest-api-openapi.yml
  format: yaml
  label: Sitecore CDP REST API
  slug: cdp-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-cdp-rest-api-openapi.yml
- filename: sitecore-cdp-stream-api-asyncapi.yml
  format: yaml
  label: Sitecore CDP Stream API
  slug: cdp-stream-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/asyncapi/sitecore-cdp-stream-api-asyncapi.yml
- filename: sitecore-personalize-rest-api-openapi.yml
  format: yaml
  label: Sitecore Personalize REST API
  slug: personalize-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-personalize-rest-api-openapi.yml
- filename: sitecore-content-hub-rest-api-openapi.yml
  format: yaml
  label: Sitecore Content Hub REST API
  slug: content-hub-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-content-hub-rest-api-openapi.yml
- filename: sitecore-ordercloud-api-openapi.yml
  format: yaml
  label: Sitecore OrderCloud API
  slug: ordercloud-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-ordercloud-api-openapi.yml
- filename: sitecore-discover-api-openapi.yml
  format: yaml
  label: Sitecore Discover API
  slug: discover-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/openapi/sitecore-discover-api-openapi.yml
apis:
- description: The Sitecore XM Cloud GraphQL Delivery API provides access to approved and published content from Sitecore XM Cloud via a GraphQL endpoint optimized for production delivery. Developers use this API to
  name: Sitecore XM Cloud GraphQL Delivery API
  slug: xm-cloud-graphql-delivery-api
- description: The Sitecore XM Cloud Authoring and Management GraphQL API provides a single GraphQL endpoint and schema for managing Sitecore content programmatically. It supports creating, updating, and querying co
  name: Sitecore XM Cloud Authoring and Management GraphQL API
  slug: xm-cloud-authoring-management-graphql-api
- description: The Sitecore XM Cloud REST API provides endpoints for creating and managing collections, sites, analytics identifiers, and languages within an XM Cloud tenant. It follows RESTful conventions and expos
  name: Sitecore XM Cloud REST API
  slug: xm-cloud-rest-api
- description: The Sitecore CDP REST API allows developers to retrieve, create, update, and delete data stored in Sitecore Customer Data Platform. It provides access to guest profiles, orders, sessions, and behavior
  name: Sitecore CDP REST API
  slug: cdp-rest-api
- description: The Sitecore CDP Stream API enables applications to send real-time behavioral and transactional events about users to the Sitecore Customer Data Platform. It is designed for high-throughput event inge
  name: Sitecore CDP Stream API
  slug: cdp-stream-api
- description: The Sitecore CDP Batch API supports uploading large volumes of guest data and offline order records into Sitecore Customer Data Platform. It is intended for bulk data migration, historical data ingest
  name: Sitecore CDP Batch API
  slug: cdp-batch-api
- description: The Sitecore Personalize REST API allows developers to programmatically interact with Sitecore Personalize experiments, decisioning flows, and connection configurations. It supports retrieving, creati
  name: Sitecore Personalize REST API
  slug: personalize-rest-api
- description: 'The Sitecore Content Hub REST API is a hypermedia API built on HTTP that provides programmatic access to the full range of Content Hub resources, including entities, assets, jobs, search, selections, '
  name: Sitecore Content Hub REST API
  slug: content-hub-rest-api
- description: The Sitecore Content Hub Admin API is a GraphQL API that provides access to administrative functions within a Content Hub tenant, accessible at the path /api/graphql/admin/v1 relative to the Content H
  name: Sitecore Content Hub Admin API
  slug: content-hub-admin-api
- description: The Sitecore OrderCloud API is a headless, API-first commerce platform providing RESTful endpoints for managing the full range of e-commerce operations including products, catalogs, orders, buyers, se
  name: Sitecore OrderCloud API
  slug: ordercloud-api
- description: The Sitecore Discover API provides search and product discovery capabilities for commerce applications, enabling developers to build search experiences, product listing pages, and recommendation widge
  name: Sitecore Discover API
  slug: discover-api
asyncapis:
- description: The Sitecore CDP Stream API enables applications to send real-time behavioral and transactional events about users to the Sitecore Customer Data Platform. It is designed for high-throughput event inge
  name: Sitecore CDP Stream API
  slug: sitecore-cdp-stream-api-asyncapi
capabilities:
- description: Unified capability combining Sitecore OrderCloud headless commerce with Sitecore Discover search and recommendations. Enables commerce teams and developers to manage products, catalogs, orders, buyers
  name: Sitecore Commerce and Discovery
  slug: commerce-discovery
- description: Unified capability for managing the full content lifecycle across XM Cloud sites and Content Hub digital assets. Enables developers and content operations teams to automate site provisioning, page man
  name: Sitecore Content Management
  slug: content-management
- description: Unified capability combining Sitecore CDP guest data management with Sitecore Personalize decisioning and experimentation. Enables marketing technologists and developers to manage customer profiles, b
  name: Sitecore Customer Data and Personalization
  slug: customer-data-personalization
common:
- title: ''
  type: JSON-LD
  url: json-ld/sitecore-context.jsonld
- title: ''
  type: JSONSchema
  url: json-schema/sitecore-cdp-guest-schema.json
- title: ''
  type: JSONSchema
  url: json-schema/sitecore-ordercloud-order-schema.json
- title: ''
  type: SpectralRules
  url: rules/sitecore-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/sitecore-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/content-management.yaml
- title: ''
  type: Capabilities
  url: capabilities/customer-data-personalization.yaml
- title: ''
  type: Capabilities
  url: capabilities/commerce-discovery.yaml
created: ''
description: Sitecore is a global digital experience platform that combines content management, marketing automation, e-commerce, customer insight, and personalization to help brands deliver personalized customer experiences. Through its developer documentation at doc.sitecore.com and api-docs.sitecore.com, Sitecore provides REST, GraphQL, and event-streaming APIs spanning XM Cloud, Customer Data Platform, Personalize, OrderCloud, Content Hub, and Discover.
features: []
image: ''
integrations: []
jsonld:
- class_count: 0
  name: Sitecore Context
  property_count: 14
  slug: sitecore-context
layout: provider
modified: '2026-05-02'
name: sitecore
rules:
- name: sitecore API Rules
  rule_count: 14
  severity_counts:
    error: 4
    hint: 0
    info: 4
    warn: 6
  slug: sitecore-rules
skills: []
slug: sitecore
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: sitecore\nurl: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/apis.yml\napis:\n  - aid: sitecore:xm-cloud-graphql-delivery-api\n    name: Sitecore XM Cloud GraphQL Delivery API\n    tags:\n      - Content Delivery\n      - Digital Experience Platform\n      - GraphQL\n      - Headless CMS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://edge.sitecorecloud.io/api/graphql\n    humanURL: https://doc.sitecore.com/xmc/en/developers/xm-cloud/delivery-api.html\n    properties:\n      - url: https://doc.sitecore.com/xmc/en/developers/xm-cloud/delivery-api.html\n        type: Documentation\n    description: >-\n      The Sitecore XM Cloud GraphQL Delivery API provides access to approved and published\n      content from Sitecore XM Cloud via a GraphQL endpoint optimized for production\n      delivery. Developers use this API to query content items, fields, and relationships\n      with precise\
  \ control over the data returned in each request, reducing over-fetching\n      in front-end applications. The API is authenticated via API keys and is designed\n      for high availability and performance at scale.\n\n  - aid: sitecore:xm-cloud-authoring-management-graphql-api\n    name: Sitecore XM Cloud Authoring and Management GraphQL API\n    tags:\n      - Content Management\n      - Digital Experience Platform\n      - GraphQL\n      - Headless CMS\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://edge.sitecorecloud.io/api/graphql\n    humanURL: https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-authoring-and-management-graphql-api.html\n    properties:\n      - url: https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-authoring-and-management-graphql-api.html\n        type: Documentation\n    description: >-\n      The Sitecore XM Cloud Authoring and Management GraphQL API provides a single\n      GraphQL\
  \ endpoint and schema for managing Sitecore content programmatically.\n      It supports creating, updating, and querying content items, templates, and site\n      structures within an XM Cloud environment. This API is intended for integration\n      builders, content migration tools, and CI/CD pipelines that need to automate\n      content operations against an XM Cloud instance.\n\n  - aid: sitecore:xm-cloud-rest-api\n    name: Sitecore XM Cloud REST API\n    tags:\n      - Collections\n      - Content Management\n      - Digital Experience Platform\n      - REST\n      - Sites\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://xmapps-api.sitecorecloud.io\n    humanURL: https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-xm-cloud.html\n    properties:\n      - url: https://doc.sitecore.com/xmc/en/developers/xm-cloud/sitecore-xm-cloud.html\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/sitecore-xm-cloud-rest-api-openapi.yml\n\
  \    description: >-\n      The Sitecore XM Cloud REST API provides endpoints for creating and managing\n      collections, sites, analytics identifiers, and languages within an XM Cloud\n      tenant. It follows RESTful conventions and exposes over 34 endpoints covering\n      the full lifecycle of site and collection management. Developers use this API\n      to automate site provisioning, manage organizational hierarchies, and integrate\n      XM Cloud administration tasks into external workflows.\n\n  - aid: sitecore:cdp-rest-api\n    name: Sitecore CDP REST API\n    tags:\n      - Customer Data Platform\n      - Guest Data\n      - Personalization\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api-engage-us.sitecorecloud.io\n    humanURL: https://doc.sitecore.com/cdp/en/developers/api/rest-apis.html\n    properties:\n      - url: https://doc.sitecore.com/cdp/en/developers/api/rest-apis.html\n        type:\
  \ Documentation\n      - type: OpenAPI\n        url: openapi/sitecore-cdp-rest-api-openapi.yml\n    description: >-\n      The Sitecore CDP REST API allows developers to retrieve, create, update, and\n      delete data stored in Sitecore Customer Data Platform. It provides access to\n      guest profiles, orders, sessions, and behavioral data through standard HTTP\n      methods. Developers use this API to build integrations that read or write customer\n      data programmatically, enabling use cases such as audience segmentation, data\n      enrichment, and reporting.\n\n  - aid: sitecore:cdp-stream-api\n    name: Sitecore CDP Stream API\n    tags:\n      - Behavioral Data\n      - Customer Data Platform\n      - Event Tracking\n      - Real-Time\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api-engage-us.sitecorecloud.io\n    humanURL: https://doc.sitecore.com/cdp/en/developers/api/stream-api.html\n    properties:\n     \
  \ - url: https://doc.sitecore.com/cdp/en/developers/api/stream-api.html\n        type: Documentation\n      - type: AsyncAPI\n        url: asyncapi/sitecore-cdp-stream-api-asyncapi.yml\n    description: >-\n      The Sitecore CDP Stream API enables applications to send real-time behavioral\n      and transactional events about users to the Sitecore Customer Data Platform.\n      It is designed for high-throughput event ingestion from web, mobile, and server-side\n      applications, capturing interactions such as page views, product views, and\n      purchases. Events sent through the Stream API update guest profiles in near\n      real-time, powering personalization and segmentation use cases.\n\n  - aid: sitecore:cdp-batch-api\n    name: Sitecore CDP Batch API\n    tags:\n      - Batch Processing\n      - Customer Data Platform\n      - Data Import\n      - Guest Data\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api-engage-us.sitecorecloud.io\n\
  \    humanURL: https://doc.sitecore.com/cdp/en/developers/api/index-en.html\n    properties:\n      - url: https://doc.sitecore.com/cdp/en/developers/api/index-en.html\n        type: Documentation\n    description: >-\n      The Sitecore CDP Batch API supports uploading large volumes of guest data and\n      offline order records into Sitecore Customer Data Platform. It is intended for\n      bulk data migration, historical data ingestion, and scenarios where real-time\n      streaming is not practical, such as nightly data syncs from CRM or ERP systems.\n      The API accepts structured data files and processes them asynchronously, updating\n      guest profiles and order histories in CDP.\n\n  - aid: sitecore:personalize-rest-api\n    name: Sitecore Personalize REST API\n    tags:\n      - Decisioning\n      - Experiments\n      - Personalization\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.boxever.com\n\
  \    humanURL: https://doc.sitecore.com/personalize/en/developers/api/index-en.html\n    properties:\n      - url: https://doc.sitecore.com/personalize/en/developers/api/index-en.html\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/sitecore-personalize-rest-api-openapi.yml\n    description: >-\n      The Sitecore Personalize REST API allows developers to programmatically interact\n      with Sitecore Personalize experiments, decisioning flows, and connection configurations.\n      It supports retrieving, creating, updating, and deleting personalization resources\n      through standard HTTP methods. Developers use this API to integrate decisioning\n      logic into server-side applications, trigger personalization flows programmatically,\n      and manage personalization assets as part of automated deployment pipelines.\n\n  - aid: sitecore:content-hub-rest-api\n    name: Sitecore Content Hub REST API\n    tags:\n      - Content Hub\n      - Digital Asset Management\n\
  \      - Media Management\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://your-tenant.stylelabs.io/api\n    humanURL: https://doc.sitecore.com/ch/en/developers/cloud-dev/rest-apis.html\n    properties:\n      - url: https://doc.sitecore.com/ch/en/developers/cloud-dev/rest-apis.html\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/sitecore-content-hub-rest-api-openapi.yml\n    description: >-\n      The Sitecore Content Hub REST API is a hypermedia API built on HTTP that provides\n      programmatic access to the full range of Content Hub resources, including entities,\n      assets, jobs, search, selections, and audit logs. Developers use it to automate\n      digital asset management workflows, migrate content, build custom integrations,\n      and manage Content Hub configuration. The API supports standard CRUD operations\n      and is authenticated using OAuth 2.0 tokens obtained from\
  \ the Content Hub identity\n      provider.\n\n  - aid: sitecore:content-hub-admin-api\n    name: Sitecore Content Hub Admin API\n    tags:\n      - Administration\n      - Content Hub\n      - Digital Asset Management\n      - GraphQL\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://your-tenant.stylelabs.io/api/graphql/admin/v1\n    humanURL: https://doc.sitecore.com/ch/en/developers/cloud-dev/content-hub-admin-api.html\n    properties:\n      - url: https://doc.sitecore.com/ch/en/developers/cloud-dev/content-hub-admin-api.html\n        type: Documentation\n    description: >-\n      The Sitecore Content Hub Admin API is a GraphQL API that provides access to\n      administrative functions within a Content Hub tenant, accessible at the path\n      /api/graphql/admin/v1 relative to the Content Hub instance URL. It enables programmatic\n      management of tenant-level configuration, schema definitions, and other administrative\n\
  \      resources that are not exposed through the standard REST API.\n\n  - aid: sitecore:ordercloud-api\n    name: Sitecore OrderCloud API\n    tags:\n      - B2B\n      - B2C\n      - Commerce\n      - Order Management\n      - REST\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.ordercloud.io/v1\n    humanURL: https://api-docs.sitecore.com/ordercloud\n    properties:\n      - url: https://api-docs.sitecore.com/ordercloud\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/sitecore-ordercloud-api-openapi.yml\n      - type: JSONSchema\n        url: json-schema/sitecore-ordercloud-order-schema.json\n    description: >-\n      The Sitecore OrderCloud API is a headless, API-first commerce platform providing\n      RESTful endpoints for managing the full range of e-commerce operations including\n      products, catalogs, orders, buyers, sellers, promotions, and fulfillment. It\n      is designed to support\
  \ B2C, B2B, and B2B2C commerce models with a highly flexible\n      and extensible data model that allows custom properties on most resources.\n\n  - aid: sitecore:discover-api\n    name: Sitecore Discover API\n    tags:\n      - Commerce\n      - Product Discovery\n      - Recommendations\n      - Search\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    baseURL: https://api.rfksrv.com\n    humanURL: https://doc.sitecore.com/discover/en/developers/discover-developer-guide/api-endpoints-and-methods.html\n    properties:\n      - url: https://doc.sitecore.com/discover/en/developers/discover-developer-guide/api-endpoints-and-methods.html\n        type: Documentation\n      - type: OpenAPI\n        url: openapi/sitecore-discover-api-openapi.yml\n    description: >-\n      The Sitecore Discover API provides search and product discovery capabilities\n      for commerce applications, enabling developers to build search experiences,\n      product listing\
  \ pages, and recommendation widgets. It exposes endpoints for\n      full-text search, faceted filtering, product recommendations, and behavioral\n      event tracking that feeds back into the discovery algorithms.\n\ncommon:\n  - type: JSON-LD\n    url: json-ld/sitecore-context.jsonld\n  - type: JSONSchema\n    url: json-schema/sitecore-cdp-guest-schema.json\n  - type: JSONSchema\n    url: json-schema/sitecore-ordercloud-order-schema.json\n  - type: SpectralRules\n    url: rules/sitecore-rules.yml\n  - type: Vocabulary\n    url: vocabulary/sitecore-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/content-management.yaml\n  - type: Capabilities\n    url: capabilities/customer-data-personalization.yaml\n  - type: Capabilities\n    url: capabilities/commerce-discovery.yaml\n\nmodified: '2026-05-02'\ndescription: >-\n  Sitecore is a global digital experience platform that combines content management,\n  marketing automation, e-commerce, customer insight, and personalization to\
  \ help\n  brands deliver personalized customer experiences. Through its developer documentation\n  at doc.sitecore.com and api-docs.sitecore.com, Sitecore provides REST, GraphQL, and\n  event-streaming APIs spanning XM Cloud, Customer Data Platform, Personalize, OrderCloud,\n  Content Hub, and Discover.\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/apis.yml
tags: []
url: https://raw.githubusercontent.com/api-evangelist/sitecore/refs/heads/main/apis.yml
use_cases: []
---
