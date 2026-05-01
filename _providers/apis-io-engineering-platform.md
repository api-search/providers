---
api_count: 11
api_specs:
- filename: aws-s3-openapi-original.yml
  format: yaml
  label: Amazon S3
  slug: aws-s3
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/aws-s3-openapi-original.yml
- filename: aws-lambda-openapi-original.yml
  format: yaml
  label: AWS Lambda
  slug: aws-lambda
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/aws-lambda-openapi-original.yml
- filename: aws-api-gateway-openapi-original.yml
  format: yaml
  label: AWS API Gateway
  slug: aws-api-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/aws-api-gateway-openapi-original.yml
- filename: aws-rds-openapi-original.yml
  format: yaml
  label: AWS RDS
  slug: aws-rds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/aws-rds-openapi-original.yml
- filename: aws-iam-openapi-original.yml
  format: yaml
  label: AWS IAM
  slug: aws-iam
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/aws-iam-openapi-original.yml
- filename: microsoft-cognitive-web-search-openapi-original.yml
  format: yaml
  label: Microsoft Bing Search
  slug: microsoft-bing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/microsoft-cognitive-web-search-openapi-original.yml
- filename: postman-openapi-original.yml
  format: yaml
  label: Postman
  slug: postman
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/postman-openapi-original.yml
- filename: cloudflare-openapi-original.yml
  format: yaml
  label: Cloudflare
  slug: cloudflare
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/cloudflare-openapi-original.yml
- filename: github-openapi-original.yml
  format: yaml
  label: GitHub
  slug: github
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/github-openapi-original.yml
apis:
- description: Amazon S3 is used for centralized object storage, managing all images, video, and audio across sites via public and private buckets.
  name: Amazon S3
  slug: aws-s3
- description: AWS Lambda is an event-driven, serverless Function as a Service provided by Amazon as a part of Amazon Web Services.
  name: AWS Lambda
  slug: aws-lambda
- description: Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.
  name: AWS API Gateway
  slug: aws-api-gateway
- description: Amazon Relational Database Service (Amazon RDS) is an easy-to-manage relational database service optimized for total cost of ownership.
  name: AWS RDS
  slug: aws-rds
- description: Amazon S3 is used for centralized object storage, managing all images, video, and audio across sites via public and private buckets.
  name: AWS IAM
  slug: aws-iam
- description: Amazon S3 is used for centralized object storage, managing all images, video, and audio across sites via public and private buckets.
  name: Microsoft Bing Search
  slug: microsoft-bing
- description: Postman is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs faster.
  name: Postman
  slug: postman
- description: Cloudflare, Inc. is an American company that provides content delivery network services, cloud cybersecurity, DDoS mitigation, wide area network services, reverse proxies, Domain Name Service, and ICA
  name: Cloudflare
  slug: cloudflare
- description: GitHub is a developer platform that allows developers to create, store, manage and share their code. It uses Git software, providing the distributed version control of Git plus access control, bug tra
  name: GitHub
  slug: github
- description: Visual Studio Code, also commonly referred to as VS Code, is an integrated development environment developed by Microsoft for Windows, Linux, macOS and web browsers.
  name: VSCode
  slug: vscode
- description: EasyCron is used to run automated tasks, making API calls on a variety of schedules, using all of the APIs produced and consumed.
  name: EasyCron
  slug: aws-s3
common:
- title: ''
  type: PostmanPublicWorkspace
  url: https://www.postman.com/api-evangelist/workspace/apis-io/overview
- title: ''
  type: GitHubOrganization
  url: https://github.com/api-search
- title: ''
  type: Portals
  url: https://developer.apis.io/
created: '2024-09-06'
description: This is an index of all of the infrastructure and services used to operate the engineering side of APIs.io, providing a single manifest of all the 3rd-party suppliers we depend on for digital resources and capabilities.The goal of this engineering platform definition is to define the platform in a way that can be federated and distributed as part of API operations, helping educate teams where they can access platform resources.
features: []
image: ''
integrations: []
layout: provider
modified: '2026-04-28'
name: APIs.io Engineering Platform
skills: []
slug: apis-io-engineering-platform
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: apis-io-engineering-platform\nname: APIs.io Engineering Platform\ntype: Platform\nposition: Producer\naccess: Internal\ndescription: >-\n  This is an index of all of the infrastructure and services used to operate the engineering\n  side of APIs.io, providing a single manifest of all the 3rd-party suppliers we depend\n  on for digital resources and capabilities.The goal of this engineering platform\n  definition is to define the platform in a way that can be federated and distributed\n  as part of API operations, helping educate teams where they can access platform\n  resources.\ntags:\n  - APIs.io\n  - Engineering\n  - Platform\ncreated: '2024-09-06'\nmodified: '2026-04-28'\nurl: >-\n  https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apis-io-engineering-platform:aws-s3\n    name: Amazon S3\n    description: >-\n      Amazon S3 is used for centralized object storage, managing all images,\n\
  \      video, and audio across sites via public and private buckets.\n    humanURL: https://docs.aws.amazon.com/AmazonS3/latest/API/Welcome.html\n    baseURL: https://{bucketname}.s3.amazonaws.com\n    tags:\n      - Cloud\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/AmazonS3/latest/API/Welcome.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/aws-s3-openapi-original.yml\n      - type: PostmanCollection\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-1ab188a6-cc1f-490d-9413-9c6da20918d0?action=share&creator=35240\n      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-0e94f581-cbc1-48e0-b594-1f6b3d07a328?action=share&creator=35240\n\
  \      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-4517d93a-e7f7-4dc2-b572-06762bbe14de?action=share&creator=35240\n  - aid: apis-io-engineering-platform:aws-lambda\n    name: AWS Lambda\n    description: >-\n      AWS Lambda is an event-driven, serverless Function as a Service provided\n      by Amazon as a part of Amazon Web Services.\n    humanURL: https://docs.aws.amazon.com/lambda/\n    baseURL: https://r275xc9bmd.execute-api.us-east-1.amazonaws.com\n    tags:\n      - Compute\n      - Execute\n      - Serverless\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/lambda/latest/api/welcome.html\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/aws-lambda-openapi-original.yml\n      - type: PostmanCollection\n        url:\
  \ >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-88f9ddbb-3115-47dc-b6e5-7fc6f1d2a190?action=share&creator=35240\n      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-3a12caae-4945-4df4-8ab9-bb6219ba7a9f?action=share&creator=35240\n      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-863b18f0-c2f2-4e32-a5fa-0d1e6ccf77a9?action=share&creator=35240\n      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-189876d1-f207-49a2-a4bc-5c67ae78cd19?action=share&creator=35240\n      - type: PostmanCapability\n  \
  \      url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-c1e74fd9-3f84-4d95-943d-d645d6cb82f7?action=share&creator=35240\n      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-b002164d-6e8a-4b6d-b409-4929476e7818?action=share&creator=35240\n  - aid: apis-io-engineering-platform:aws-api-gateway\n    name: AWS API Gateway\n    description: >-\n      Amazon API Gateway is a fully managed service that makes it easy for\n      developers to create, publish, maintain, monitor, and secure APIs at any\n      scale.\n    humanURL: https://aws.amazon.com/api-gateway/\n    baseURL: http://api.example.com\n    tags:\n      - Gateway\n    properties:\n      - type: Documentation\n        url: https://example.com/documentation\n      - type: OpenAPI\n        url: >-\n      \
  \    https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/aws-api-gateway-openapi-original.yml\n      - type: PostmanCollection\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-508660fd-30b8-4c9c-aede-8edbac8a514d?action=share&creator=35240\n      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-da35e0ba-f1a9-42fe-a77a-56ff0a47e341?action=share&creator=35240\n      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-1d4df7d0-9c92-4fa8-946f-2110c2b3b48d?action=share&creator=35240\n      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-2af6f54f-d259-46c0-8f86-78856f5885cd?action=share&creator=35240\n\
  \      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-cc203f31-e7f6-42ec-ad34-c5c4cde58904?action=share&creator=35240\n      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-f19285da-48dd-4691-bbdf-f7d6bec157a3?action=share&creator=35240\n  - aid: apis-io-engineering-platform:aws-rds\n    name: AWS RDS\n    description: >-\n      Amazon Relational Database Service (Amazon RDS) is an easy-to-manage\n      relational database service optimized for total cost of ownership.\n    humanURL: https://aws.amazon.com/rds/\n    baseURL: http://api.example.com\n    tags:\n      - Database\n    properties:\n      - type: Documentation\n        url: >-\n          https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/ProgrammingGuide.html\n\
  \      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/aws-rds-openapi-original.yml\n      - type: PostmanCollection\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-aa69cacc-4bbf-4724-a1d4-78cdad57fee8?action=share&creator=35240\n  - aid: apis-io-engineering-platform:aws-iam\n    name: AWS IAM\n    description: >-\n      Amazon S3 is used for centralized object storage, managing all images,\n      video, and audio across sites via public and private buckets.\n    humanURL: https://aws.amazon.com/iam/\n    baseURL: http://api.example.com\n    tags:\n      - Access\n      - Identity\n      - Keys\n      - Tokens\n      - Users\n    properties:\n      - type: Documentation\n        url: https://docs.aws.amazon.com/IAM/latest/APIReference/welcome.html\n      - type: OpenAPI\n        url: >-\n       \
  \   https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/aws-iam-openapi-original.yml\n      - type: PostmanCollection\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-a5858f86-04d3-4e15-ae11-b42c7516688b?action=share&creator=35240\n  - aid: apis-io-engineering-platform:microsoft-bing\n    name: Microsoft Bing Search\n    description: >-\n      Amazon S3 is used for centralized object storage, managing all images,\n      video, and audio across sites via public and private buckets.\n    humanURL: https://www.microsoft.com/en-us/bing/apis\n    baseURL: https://api.bing.microsoft.com\n    tags:\n      - Search\n    properties:\n      - type: Documentation\n        url: https://www.microsoft.com/en-us/bing/apis/bing-web-search-api\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/microsoft-cognitive-web-search-openapi-original.yml\n\
  \      - type: PostmanCollection\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-c2052341-766c-43c7-b1dc-ed4985e4606b?action=share&creator=35240\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/microsoft-cognitive-video-search-openapi-original.yml\n      - type: PostmanCollection\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-aa777c90-8271-4809-8eac-3ec39a9a899c?action=share&creator=35240\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/microsoft-cognitive-news-search-openapi-original.yml\n      - type: PostmanCollection\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-aa777c90-8271-4809-8eac-3ec39a9a899c?action=share&creator=35240\n\
  \  - aid: apis-io-engineering-platform:postman\n    name: Postman\n    description: >-\n      Postman is an API platform for building and using APIs. Postman simplifies\n      each step of the API lifecycle and streamlines collaboration so you can\n      create better APIs faster.\n    humanURL: https://www.postman.com\n    baseURL: http://api.example.com\n    tags:\n      - Storage\n    properties:\n      - type: Documentation\n        url: https://example.com/documentation\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/postman-openapi-original.yml\n      - type: PostmanCollection\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-4d5957dc-df05-4216-a5fc-d46b3ba811d8?action=share&creator=35240\n  - aid: apis-io-engineering-platform:cloudflare\n    name: Cloudflare\n    description: >-\n   \
  \   Cloudflare, Inc. is an American company that provides content delivery\n      network services, cloud cybersecurity, DDoS mitigation, wide area network\n      services, reverse proxies, Domain Name Service, and ICANN-accredited\n      domain registration services.\n    humanURL: https://developers.cloudflare.com/\n    baseURL: https://api.cloudflare.com/\n    tags:\n      - DNS\n    properties:\n      - type: Documentation\n        url: https://developers.cloudflare.com/api/\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/cloudflare-openapi-original.yml\n      - type: PostmanCollection\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-28d97617-fdba-46a5-ac3e-40f3d2e0fa57?action=share&creator=35240\n  - aid: apis-io-engineering-platform:github\n    name: GitHub\n    description: >-\n    \
  \  GitHub is a developer platform that allows developers to create, store,\n      manage and share their code. It uses Git software, providing the\n      distributed version control of Git plus access control, bug tracking,\n      software feature requests, task management, continuous integration, and\n      wikis for every project.\n    humanURL: https://docs.github.com/en\n    baseURL: https://api.github.com\n    tags:\n      - Pipelines\n      - Source Control\n    properties:\n      - type: Documentation\n        url: https://docs.github.com/en/rest\n      - type: OpenAPI\n        url: >-\n          https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/openapi/github-openapi-original.yml\n      - type: PostmanCollection\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-7429b451-d812-4abc-b497-b763372cf5c5?action=share&creator=35240\n      - type: PostmanCapability\n\
  \        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-b0eafdd0-adaa-48a2-a855-6a31beb86d83?action=share&creator=35240\n      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-209f34ef-13c1-400c-bca8-fcddb304aff5?action=share&creator=35240\n      - type: PostmanCapability\n        url: >-\n          https://api-evangelist.postman.co/workspace/APIs.io-Engineering-Platform/fe320942-e505-4ee8-8b7c-d72eae00d93f/collection/35240-fb2bbbb8-d4cc-48b1-a660-c8e158bfbbea?action=share&creator=35240\n  - aid: apis-io-engineering-platform:vscode\n    name: VSCode\n    description: >-\n      Visual Studio Code, also commonly referred to as VS Code, is an integrated\n      development environment developed by Microsoft for Windows, Linux, macOS\n      and web browsers.\n   \
  \ humanURL: https://code.visualstudio.com/\n    tags:\n      - IDE\n    properties:\n      - type: Documentation\n        url: https://code.visualstudio.com/api/references/vscode-api\n  - aid: apis-io-engineering-platform:aws-s3\n    name: EasyCron\n    description: >-\n      EasyCron is used to run automated tasks, making API calls on a variety of\n      schedules, using all of the APIs produced and consumed.\n    humanURL: https://developer.easycron.com/\n    baseURL: https://api.easycron.com\n    tags:\n      - CRON\n      - Jobs\n      - Scheduling\n    properties:\n      - type: Documentation\n        url: https://developer.easycron.com/docs/api/v1/introduction\ncommon:\n  - type: PostmanPublicWorkspace\n    url: https://www.postman.com/api-evangelist/workspace/apis-io/overview\n  - type: GitHubOrganization\n    url: https://github.com/api-search\n  - type: Portals\n    url: https://developer.apis.io/\nmaintainers:\n  - FN: Kin Lane\n    X-twitter: apievangelist\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apis-io-engineering-platform/refs/heads/main/apis.yml
tags:
- APIs.io
- Engineering
- Platform
url: https://raw.githubusercontent.com/api-search/engineering-platform/refs/heads/main/apis.yml
use_cases: []
---
