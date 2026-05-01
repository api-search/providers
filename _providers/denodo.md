---
api_count: 6
apis:
- description: The Solution Manager REST API provides programmatic access to administer the Denodo Platform across environments and clusters. It exposes endpoints for cluster lifecycle management, environment config
  name: Denodo Solution Manager REST API
  slug: solution-manager-api
- description: The Denodo Data Catalog REST API provides programmatic access to the catalog of virtual views, web services, search, lineage, tags, categories, and certifications managed by the Denodo Platform. It po
  name: Denodo Data Catalog REST API
  slug: data-catalog-api
- description: 'The Denodo RESTful Web Service exposes any view in Virtual DataPort as a resource-oriented REST endpoint. It supports JSON, XML, and HTML representations, query filtering, projection, pagination, and '
  name: Denodo RESTful Web Service
  slug: rest-web-service
- description: The Denodo OData 4.0 service provides an OASIS OData v4 compliant interface for querying Virtual DataPort views over HTTP. It supports filter, select, expand, orderby, top, and skip query options as w
  name: Denodo OData 4.0 Service
  slug: odata-service
- description: The Denodo GraphQL Service enables clients to execute GraphQL queries against virtual views in the Denodo Platform. It generates a GraphQL schema from selected views and supports filtering, pagination
  name: Denodo GraphQL Service
  slug: graphql-service
- description: The Denodo Scheduler REST API allows programmatic management and monitoring of scheduled jobs and projects in the Denodo Scheduler component. Endpoints support listing, creating, executing, cancelling
  name: Denodo Scheduler REST API
  slug: scheduler-rest-api
capabilities: []
common:
- title: ''
  type: Website
  url: https://www.denodo.com
- title: ''
  type: Portal
  url: https://community.denodo.com/
- title: ''
  type: Documentation
  url: https://community.denodo.com/docs/
- title: ''
  type: Knowledge Base
  url: https://community.denodo.com/kb/
- title: ''
  type: Tutorials
  url: https://community.denodo.com/tutorials/
- title: ''
  type: Express Edition
  url: https://www.denodo.com/en/denodo-platform/free-trials
- title: ''
  type: Pricing
  url: https://www.denodo.com/en/pricing
- title: ''
  type: Support
  url: https://support.denodo.com/
- title: ''
  type: Status
  url: https://www.denodo.com/en/legal/denodo-trust-center
- title: ''
  type: Blog
  url: https://www.denodo.com/en/blog
- title: ''
  type: Customers
  url: https://www.denodo.com/en/customers
- title: ''
  type: Partners
  url: https://www.denodo.com/en/partners
- title: ''
  type: Training
  url: https://www.denodo.com/en/services/training
- title: ''
  type: GitHub Organization
  url: https://github.com/denodo
- title: ''
  type: Terms of Service
  url: https://www.denodo.com/en/legal/legal-notice
- title: ''
  type: Privacy Policy
  url: https://www.denodo.com/en/legal/privacy-policy
- title: ''
  type: Security
  url: https://www.denodo.com/en/legal/denodo-trust-center
- title: ''
  type: JSON-LD
  url: json-ld/denodo-context.jsonld
- title: ''
  type: Vocabulary
  url: vocabulary/denodo-vocabulary.yml
- title: ''
  type: Capabilities
  url: capabilities/denodo-capabilities.yml
created: '2026-03-16'
description: Denodo is a leading data virtualization platform that enables real-time access, integration, and delivery of data from disparate sources across enterprise data landscapes. The Denodo Platform exposes a portfolio of REST, OData, GraphQL, and SOAP web service endpoints through Virtual DataPort, the Data Catalog, the Solution Manager, and the Scheduler so that data products can be published, governed, and administered programmatically.
features: []
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
jsonld:
- class_count: 0
  name: Denodo Context
  property_count: 6
  slug: denodo-context
layout: provider
modified: '2026-04-28'
name: Denodo
skills: []
slug: denodo
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: denodo\nname: Denodo\ndescription: >-\n  Denodo is a leading data virtualization platform that enables real-time access,\n  integration, and delivery of data from disparate sources across enterprise data\n  landscapes. The Denodo Platform exposes a portfolio of REST, OData, GraphQL, and\n  SOAP web service endpoints through Virtual DataPort, the Data Catalog, the Solution\n  Manager, and the Scheduler so that data products can be published, governed, and\n  administered programmatically.\ntype: Index\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Data Catalog\n  - Data Fabric\n  - Data Mesh\n  - Data Virtualization\n  - GraphQL\n  - Logical Data Warehouse\n  - OData\n  - REST\n  - Scheduler\n  - Solution Manager\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/denodo/refs/heads/main/apis.yml\ncreated: '2026-03-16'\nmodified: '2026-04-28'\nspecificationVersion: '0.19'\nxType: company\nposition: Producer\naccess:\
  \ 3rd-Party\napis:\n  - aid: denodo:solution-manager-api\n    name: Denodo Solution Manager REST API\n    description: >-\n      The Solution Manager REST API provides programmatic access to administer the\n      Denodo Platform across environments and clusters. It exposes endpoints for\n      cluster lifecycle management, environment configuration, deployment of revisions\n      across servers (VDP, SCHEDULER, VDP_DATA_CATALOG), monitoring, license management,\n      and permissions administration. Most operations require HTTP Basic authentication\n      or token-based authentication.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://community.denodo.com/docs/html/browse/latest/en/solution_manager/administration/appendix/rest_api/rest_api\n    baseURL: https://solution-manager.example.com/solution-manager\n    tags:\n      - Administration\n      - Clusters\n      - Deployment\n      - Environments\n      - Solution Manager\n\
  \    properties:\n      - type: Documentation\n        url: https://community.denodo.com/docs/html/browse/latest/en/solution_manager/administration/appendix/rest_api/rest_api\n      - type: Reference\n        url: https://community.denodo.com/docs/html/browse/9.4/en/solution_manager/administration/appendix/rest_api/rest_api\n    contact:\n      - FN: Denodo Support\n        email: support@denodo.com\n        url: https://support.denodo.com\n  - aid: denodo:data-catalog-api\n    name: Denodo Data Catalog REST API\n    description: >-\n      The Denodo Data Catalog REST API provides programmatic access to the catalog\n      of virtual views, web services, search, lineage, tags, categories, and\n      certifications managed by the Denodo Platform. It powers metadata exploration,\n      data product publishing, and governance workflows. Interactive documentation\n      is available via Swagger at /denodo-data-catalog/swagger-ui/index.html.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n\
  \    humanURL: https://community.denodo.com/docs/html/browse/latest/en/vdp/data_catalog/appendix/rest_api/rest_api\n    baseURL: https://denodo.example.com/denodo-data-catalog\n    tags:\n      - Catalog\n      - Data Catalog\n      - Governance\n      - Metadata\n      - Search\n    properties:\n      - type: Documentation\n        url: https://community.denodo.com/docs/html/browse/latest/en/vdp/data_catalog/appendix/rest_api/rest_api\n      - type: Swagger\n        url: https://community.denodo.com/docs/html/browse/9.0/en/vdp/data_catalog/appendix/rest_api/rest_api\n    contact:\n      - FN: Denodo Support\n        email: support@denodo.com\n        url: https://support.denodo.com\n  - aid: denodo:rest-web-service\n    name: Denodo RESTful Web Service\n    description: >-\n      The Denodo RESTful Web Service exposes any view in Virtual DataPort as a\n      resource-oriented REST endpoint. It supports JSON, XML, and HTML\n      representations, query filtering, projection, pagination,\
  \ and HATEOAS\n      navigation between associated views. The same RESTful approach is used to\n      publish custom REST Web services declared via VQL.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://community.denodo.com/docs/html/browse/latest/en/vdp/administration/restful_architecture/restful_architecture\n    baseURL: https://denodo.example.com/denodo-restfulws\n    tags:\n      - HATEOAS\n      - REST\n      - Virtual DataPort\n      - Web Services\n    properties:\n      - type: Documentation\n        url: https://community.denodo.com/docs/html/browse/latest/en/vdp/administration/restful_architecture/restful_architecture\n      - type: Tutorial\n        url: https://community.denodo.com/tutorials/browse/dataservices/2rest\n    contact:\n      - FN: Denodo Support\n        email: support@denodo.com\n        url: https://support.denodo.com\n  - aid: denodo:odata-service\n    name: Denodo OData 4.0 Service\n    description:\
  \ >-\n      The Denodo OData 4.0 service provides an OASIS OData v4 compliant\n      interface for querying Virtual DataPort views over HTTP. It supports\n      filter, select, expand, orderby, top, and skip query options as well as\n      service metadata documents and entity navigation between related views.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://community.denodo.com/docs/html/browse/latest/en/vdp/administration/restful_architecture/odata_4_service/odata_4_service\n    baseURL: https://denodo.example.com/denodo-odata4-service\n    tags:\n      - OData\n      - Query\n      - REST\n      - Virtual DataPort\n    properties:\n      - type: Documentation\n        url: https://community.denodo.com/docs/html/browse/latest/en/vdp/administration/restful_architecture/odata_4_service/odata_4_service\n    contact:\n      - FN: Denodo Support\n        email: support@denodo.com\n        url: https://support.denodo.com\n  - aid:\
  \ denodo:graphql-service\n    name: Denodo GraphQL Service\n    description: >-\n      The Denodo GraphQL Service enables clients to execute GraphQL queries\n      against virtual views in the Denodo Platform. It generates a GraphQL\n      schema from selected views and supports filtering, pagination, and field\n      selection through standard GraphQL syntax over HTTP.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://community.denodo.com/docs/html/browse/latest/en/vdp/administration/restful_architecture/graphql_service/graphql_service\n    baseURL: https://denodo.example.com/denodo-graphql-service\n    tags:\n      - GraphQL\n      - Query\n      - Virtual DataPort\n    properties:\n      - type: Documentation\n        url: https://community.denodo.com/docs/html/browse/latest/en/vdp/administration/restful_architecture/graphql_service/graphql_service\n    contact:\n      - FN: Denodo Support\n        email: support@denodo.com\n\
  \        url: https://support.denodo.com\n  - aid: denodo:scheduler-rest-api\n    name: Denodo Scheduler REST API\n    description: >-\n      The Denodo Scheduler REST API allows programmatic management and\n      monitoring of scheduled jobs and projects in the Denodo Scheduler\n      component. Endpoints support listing, creating, executing, cancelling\n      jobs and retrieving their status, history, and configuration.\n    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\n    humanURL: https://community.denodo.com/docs/html/browse/latest/en/scheduler/administration/scheduler_rest_web_service/scheduler_rest_web_service\n    baseURL: https://denodo.example.com/webadmin/denodo-scheduler-admin\n    tags:\n      - Jobs\n      - Scheduler\n      - Workflow\n    properties:\n      - type: Documentation\n        url: https://community.denodo.com/docs/html/browse/latest/en/scheduler/administration/scheduler_rest_web_service/scheduler_rest_web_service\n    contact:\n\
  \      - FN: Denodo Support\n        email: support@denodo.com\n        url: https://support.denodo.com\ncommon:\n  - type: Website\n    url: https://www.denodo.com\n  - type: Portal\n    url: https://community.denodo.com/\n  - type: Documentation\n    url: https://community.denodo.com/docs/\n  - type: Knowledge Base\n    url: https://community.denodo.com/kb/\n  - type: Tutorials\n    url: https://community.denodo.com/tutorials/\n  - type: Express Edition\n    url: https://www.denodo.com/en/denodo-platform/free-trials\n  - type: Pricing\n    url: https://www.denodo.com/en/pricing\n  - type: Support\n    url: https://support.denodo.com/\n  - type: Status\n    url: https://www.denodo.com/en/legal/denodo-trust-center\n  - type: Blog\n    url: https://www.denodo.com/en/blog\n  - type: Customers\n    url: https://www.denodo.com/en/customers\n  - type: Partners\n    url: https://www.denodo.com/en/partners\n  - type: Training\n    url: https://www.denodo.com/en/services/training\n  - type: GitHub\
  \ Organization\n    url: https://github.com/denodo\n  - type: Terms of Service\n    url: https://www.denodo.com/en/legal/legal-notice\n  - type: Privacy Policy\n    url: https://www.denodo.com/en/legal/privacy-policy\n  - type: Security\n    url: https://www.denodo.com/en/legal/denodo-trust-center\n  - type: JSON-LD\n    url: json-ld/denodo-context.jsonld\n  - type: Vocabulary\n    url: vocabulary/denodo-vocabulary.yml\n  - type: Capabilities\n    url: capabilities/denodo-capabilities.yml\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/denodo/refs/heads/main/apis.yml
tags:
- Data Catalog
- Data Fabric
- Data Mesh
- Data Virtualization
- GraphQL
- Logical Data Warehouse
- OData
- REST
- Scheduler
- Solution Manager
url: https://raw.githubusercontent.com/api-evangelist/denodo/refs/heads/main/apis.yml
use_cases: []
---
