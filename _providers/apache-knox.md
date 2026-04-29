---
api_count: 2
apis:
- description: The Knox Admin REST API provides endpoints for topology management, service descriptor management, provider configuration, and version information for administering the Knox gateway.
  name: Apache Knox Admin REST API
  slug: admin-api
- description: The Knox gateway proxies and secures access to Hadoop ecosystem services including HDFS WebHDFS, Hive, HBase REST, YARN, Oozie, Ambari, and Ranger with authentication and authorization enforcement.
  name: Apache Knox Gateway API
  slug: gateway-api
capabilities:
- description: Workflow capability for Hadoop administrators and security engineers to manage Knox gateway topologies, service descriptors, and provider configurations.
  name: Apache Knox Gateway Management
  slug: gateway-management
common:
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/knox
- title: ''
  type: Documentation
  url: https://knox.apache.org/books/knox-2-0-0/user-guide.html
- title: ''
  type: GettingStarted
  url: https://knox.apache.org/books/knox-2-0-0/user-guide.html#Quick+Start
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
- title: ''
  type: Versioning
  url: https://knox.apache.org/books/
- title: ''
  type: SpectralRules
  url: rules/apache-knox-spectral-rules.yml
- title: ''
  type: Vocabulary
  url: vocabulary/apache-knox-vocabulary.yaml
- title: ''
  type: NaftikoCapability
  url: capabilities/gateway-management.yaml
created: '2026-03-16'
description: Apache Knox is a REST API and application gateway for the Apache Hadoop ecosystem. It provides a single access point for all REST and HTTP interactions with Apache Hadoop clusters, with authentication, authorization, SSO, and audit capabilities. Governed by the Apache Software Foundation under Apache 2.0.
features:
- description: Unified gateway for all Hadoop REST services eliminating direct cluster access.
  name: Single Access Point
- description: Kerberos, LDAP, OAuth2, and JWT authentication support.
  name: Authentication
- description: SAML2-based SSO and token-based federation across Hadoop services.
  name: SSO Integration
- description: Fine-grained authorization via Apache Ranger integration.
  name: Authorization
- description: SSL/TLS termination at the gateway for encrypted communication.
  name: SSL/TLS Termination
- description: Automatic service discovery via Ambari and Cloudera Manager integration.
  name: Service Discovery
- description: Dynamic topology configuration without gateway restarts.
  name: Topology Management
- description: Comprehensive audit logs for all gateway interactions.
  name: Audit Logging
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: WebHDFS REST API proxied and secured through Knox.
  name: Apache Hadoop HDFS
- description: Hive JDBC and REST API access via Knox gateway.
  name: Apache Hive
- description: HBase REST API proxied through Knox with authentication.
  name: Apache HBase
- description: Authorization policy enforcement via Ranger Knox plugin.
  name: Apache Ranger
- description: Ambari REST API proxied through Knox for cluster management.
  name: Apache Ambari
jsonld:
- class_count: 3
  name: Apache Knox Admin Api Descriptor Context
  property_count: 6
  slug: apache-knox-admin-api-descriptor-context
- class_count: 2
  name: Apache Knox Admin Api Knox Context
  property_count: 1
  slug: apache-knox-admin-api-knox-context
- class_count: 3
  name: Apache Knox Admin Api Topology Context
  property_count: 4
  slug: apache-knox-admin-api-topology-context
layout: provider
modified: '2026-04-19'
name: Apache Knox
rules:
- name: Apache Knox API Rules
  rule_count: 12
  severity_counts:
    error: 9
    hint: 0
    info: 0
    warn: 3
  slug: apache-knox-spectral-rules
skills: []
slug: apache-knox
solutions: []
source_yaml: "aid: apache-knox\nname: Apache Knox\ndescription: >-\n  Apache Knox is a REST API and application gateway for the Apache Hadoop ecosystem. It provides a single access point for all REST and HTTP interactions with Apache Hadoop clusters, with authentication, authorization, SSO, and audit capabilities. Governed by the Apache Software Foundation under Apache 2.0.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - API Gateway\n  - Authentication\n  - Hadoop\n  - Open Source\n  - Security\n  - SSO\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-knox/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-knox:admin-api\n    name: Apache Knox Admin REST API\n    description: >-\n      The Knox Admin REST API provides endpoints for topology management, service descriptor management, provider configuration,\
  \ and version information for administering the Knox gateway.\n    humanURL: https://knox.apache.org/books/knox-2-0-0/user-guide.html\n    tags:\n      - Administration\n      - API Gateway\n      - REST\n    properties:\n      - type: Documentation\n        url: https://knox.apache.org/books/knox-2-0-0/user-guide.html\n      - type: OpenAPI\n        url: openapi/apache-knox-admin-api.yaml\n\n  - aid: apache-knox:gateway-api\n    name: Apache Knox Gateway API\n    description: >-\n      The Knox gateway proxies and secures access to Hadoop ecosystem services including HDFS WebHDFS, Hive, HBase REST, YARN, Oozie, Ambari, and Ranger with authentication and authorization enforcement.\n    humanURL: https://knox.apache.org/books/knox-2-0-0/user-guide.html#Service+Details\n    tags:\n      - API Gateway\n      - Hadoop\n      - Proxy\n      - Security\n    properties:\n      - type: Documentation\n        url: https://knox.apache.org/books/knox-2-0-0/user-guide.html#Service+Details\n\ncommon:\n\
  \  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/knox\n  - type: Documentation\n    url: https://knox.apache.org/books/knox-2-0-0/user-guide.html\n  - type: GettingStarted\n    url: https://knox.apache.org/books/knox-2-0-0/user-guide.html#Quick+Start\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Versioning\n    url: https://knox.apache.org/books/\n  - type: SpectralRules\n    url: rules/apache-knox-spectral-rules.yml\n  - type: Vocabulary\n    url: vocabulary/apache-knox-vocabulary.yaml\n  - type: NaftikoCapability\n    url: capabilities/gateway-management.yaml\n  - type: Features\n    data:\n      - name: Single Access Point\n        description: Unified gateway for all Hadoop REST services eliminating direct cluster access.\n      - name: Authentication\n        description: Kerberos, LDAP, OAuth2, and JWT authentication support.\n      - name: SSO Integration\n\
  \        description: SAML2-based SSO and token-based federation across Hadoop services.\n      - name: Authorization\n        description: Fine-grained authorization via Apache Ranger integration.\n      - name: SSL/TLS Termination\n        description: SSL/TLS termination at the gateway for encrypted communication.\n      - name: Service Discovery\n        description: Automatic service discovery via Ambari and Cloudera Manager integration.\n      - name: Topology Management\n        description: Dynamic topology configuration without gateway restarts.\n      - name: Audit Logging\n        description: Comprehensive audit logs for all gateway interactions.\n  - type: UseCases\n    data:\n      - name: Hadoop Cluster Security\n        description: Secure and centralize access to all Hadoop REST APIs through Knox.\n      - name: Cloud Hadoop Access\n        description: Provide secure REST access to EMR, HDInsight, and Dataproc clusters.\n      - name: Hadoop SSO\n        description:\
  \ Enable single sign-on across Ambari, Hue, Spark UI, and other Hadoop UIs.\n      - name: REST API Proxying\n        description: Proxy WebHDFS, Hive JDBC/REST, HBase REST, and YARN REST through Knox.\n  - type: Integrations\n    data:\n      - name: Apache Hadoop HDFS\n        description: WebHDFS REST API proxied and secured through Knox.\n      - name: Apache Hive\n        description: Hive JDBC and REST API access via Knox gateway.\n      - name: Apache HBase\n        description: HBase REST API proxied through Knox with authentication.\n      - name: Apache Ranger\n        description: Authorization policy enforcement via Ranger Knox plugin.\n      - name: Apache Ambari\n        description: Ambari REST API proxied through Knox for cluster management.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-knox/refs/heads/main/apis.yml
tags:
- API Gateway
- Authentication
- Hadoop
- Open Source
- Security
- SSO
url: https://raw.githubusercontent.com/api-evangelist/apache-knox/refs/heads/main/apis.yml
use_cases:
- description: Secure and centralize access to all Hadoop REST APIs through Knox.
  name: Hadoop Cluster Security
- description: Provide secure REST access to EMR, HDInsight, and Dataproc clusters.
  name: Cloud Hadoop Access
- description: Enable single sign-on across Ambari, Hue, Spark UI, and other Hadoop UIs.
  name: Hadoop SSO
- description: Proxy WebHDFS, Hive JDBC/REST, HBase REST, and YARN REST through Knox.
  name: REST API Proxying
---
