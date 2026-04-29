---
api_count: 3
apis:
- description: MINA Core provides a Java NIO-based API for building high-performance network applications with support for TCP and UDP protocols, an event-driven filter chain for protocol codecs, session management,
  name: Apache MINA Core
  slug: apache-mina-core
- description: Apache MINA SSHD is a comprehensive Java library for client- and server-side SSH protocol implementation. It supports SCP, SFTP, port forwarding, key management, and various authentication methods. Cu
  name: Apache MINA SSHD
  slug: apache-mina-sshd
- description: Apache FtpServer is a 100% pure Java FTP server built on MINA. It is designed to be used as a complete and portable FTP server engine solution based on currently available open protocols. Current vers
  name: Apache FtpServer
  slug: apache-ftpserver
common:
- title: ''
  type: Portal
  url: https://mina.apache.org/
- title: ''
  type: GitHubOrganization
  url: https://github.com/apache
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/mina
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/mina-sshd
- title: ''
  type: GitHubRepository
  url: https://github.com/apache/mina-site
- title: ''
  type: IssueTracker
  url: https://issues.apache.org/jira/browse/DIRMINA
- title: ''
  type: MailingList
  url: https://mina.apache.org/mina-project/mailing-lists.html
- title: ''
  type: TermsOfService
  url: https://www.apache.org/licenses/LICENSE-2.0
created: '2026-03-16'
description: Apache MINA is a network application framework that helps develop high-performance and high-scalability network applications. It provides an abstract event-driven asynchronous API over various transports such as TCP/IP and UDP/IP via Java NIO. MINA includes sub-projects for SSH (SSHD), FTP (FtpServer), and XMPP (Vysper) protocols.
features:
- description: Abstract event-driven asynchronous API enabling high-performance non-blocking I/O network application development.
  name: Event-Driven Architecture
- description: Built on Java NIO for scalable, non-blocking network I/O supporting thousands of concurrent connections.
  name: Java NIO Foundation
- description: Pluggable filter chain architecture for protocol codec, logging, compression, and security processing.
  name: Filter Chain
- description: Supports TCP/IP and UDP/IP transports with a unified programming model across both.
  name: Multi-Transport Support
- description: SSHD sub-project provides full SSH client and server implementation with SCP, SFTP, and port forwarding.
  name: SSH Client and Server
- description: FtpServer sub-project provides a complete, embeddable FTP server implementation built on MINA.
  name: FTP Server
- description: Vysper sub-project provides an extensible XMPP server implementation for instant messaging.
  name: XMPP Server
- description: Comprehensive session lifecycle management with configurable timeouts, idle detection, and connection throttling.
  name: Session Management
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations:
- description: MINA integrates with the Spring Framework for dependency injection and application lifecycle management.
  name: Spring Framework
- description: Native SLF4J logging integration for structured logging across all MINA components.
  name: SLF4J and Logback
- description: Bouncy Castle cryptography library integration for SSH key management and cryptographic operations in SSHD.
  name: Bouncy Castle
- description: MINA components can be deployed as OSGi bundles in Apache Karaf container.
  name: Apache Karaf
layout: provider
modified: '2026-04-19'
name: Apache MINA
skills: []
slug: apache-mina
solutions: []
source_yaml: "aid: apache-mina\nname: Apache MINA\ndescription: >-\n  Apache MINA is a network application framework that helps develop high-performance and high-scalability network applications. It provides an abstract event-driven asynchronous API over various transports such as TCP/IP and UDP/IP via Java NIO. MINA includes sub-projects for SSH (SSHD), FTP (FtpServer), and XMPP (Vysper) protocols.\ntype: Index\nposition: Consumer\naccess: 3rd-Party\nimage: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Async I/O\n  - Java\n  - Networking\n  - NIO\n  - Protocol Framework\n  - SSH\ncreated: '2026-03-16'\nmodified: '2026-04-19'\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/apache-mina/refs/heads/main/apis.yml\nspecificationVersion: '0.19'\napis:\n  - aid: apache-mina:apache-mina-core\n    name: Apache MINA Core\n    description: >-\n      MINA Core provides a Java NIO-based API for building high-performance network applications with support\
  \ for TCP and UDP protocols, an event-driven filter chain for protocol codecs, session management, and both client and server roles. Current version is 2.2.5.\n    humanURL: https://mina.apache.org/mina-project/documentation.html\n    tags:\n      - Java\n      - NIO\n      - Networking\n      - TCP\n      - UDP\n    properties:\n      - type: Documentation\n        url: https://mina.apache.org/mina-project/documentation.html\n      - type: GettingStarted\n        url: https://mina.apache.org/mina-project/userguide/user-guide-toc.html\n      - type: SDK\n        url: https://central.sonatype.com/artifact/org.apache.mina/mina-core\n        title: Maven Central (Java)\n      - type: GitHubRepository\n        url: https://github.com/apache/mina\n  - aid: apache-mina:apache-mina-sshd\n    name: Apache MINA SSHD\n    description: >-\n      Apache MINA SSHD is a comprehensive Java library for client- and server-side SSH protocol implementation. It supports SCP, SFTP, port forwarding, key management,\
  \ and various authentication methods. Current version is 2.17.1.\n    humanURL: https://mina.apache.org/sshd-project/index.html\n    tags:\n      - Java\n      - Security\n      - SCP\n      - SFTP\n      - SSH\n    properties:\n      - type: Documentation\n        url: https://mina.apache.org/sshd-project/index.html\n      - type: SDK\n        url: https://central.sonatype.com/artifact/org.apache.sshd/sshd-core\n        title: Maven Central (Java)\n      - type: GitHubRepository\n        url: https://github.com/apache/mina-sshd\n  - aid: apache-mina:apache-ftpserver\n    name: Apache FtpServer\n    description: >-\n      Apache FtpServer is a 100% pure Java FTP server built on MINA. It is designed to be used as a complete and portable FTP server engine solution based on currently available open protocols. Current version is 1.2.1.\n    humanURL: https://mina.apache.org/ftpserver-project/index.html\n    tags:\n      - FTP\n      - Java\n      - Server\n    properties:\n      - type: Documentation\n\
  \        url: https://mina.apache.org/ftpserver-project/index.html\n      - type: SDK\n        url: https://central.sonatype.com/artifact/org.apache.ftpserver/ftpserver-core\n        title: Maven Central (Java)\n      - type: GitHubRepository\n        url: https://github.com/apache/mina\ncommon:\n  - type: Portal\n    url: https://mina.apache.org/\n  - type: GitHubOrganization\n    url: https://github.com/apache\n  - type: GitHubRepository\n    url: https://github.com/apache/mina\n  - type: GitHubRepository\n    url: https://github.com/apache/mina-sshd\n  - type: GitHubRepository\n    url: https://github.com/apache/mina-site\n  - type: IssueTracker\n    url: https://issues.apache.org/jira/browse/DIRMINA\n  - type: MailingList\n    url: https://mina.apache.org/mina-project/mailing-lists.html\n  - type: TermsOfService\n    url: https://www.apache.org/licenses/LICENSE-2.0\n  - type: Features\n    data:\n      - name: Event-Driven Architecture\n        description: Abstract event-driven asynchronous\
  \ API enabling high-performance non-blocking I/O network application development.\n      - name: Java NIO Foundation\n        description: Built on Java NIO for scalable, non-blocking network I/O supporting thousands of concurrent connections.\n      - name: Filter Chain\n        description: Pluggable filter chain architecture for protocol codec, logging, compression, and security processing.\n      - name: Multi-Transport Support\n        description: Supports TCP/IP and UDP/IP transports with a unified programming model across both.\n      - name: SSH Client and Server\n        description: SSHD sub-project provides full SSH client and server implementation with SCP, SFTP, and port forwarding.\n      - name: FTP Server\n        description: FtpServer sub-project provides a complete, embeddable FTP server implementation built on MINA.\n      - name: XMPP Server\n        description: Vysper sub-project provides an extensible XMPP server implementation for instant messaging.\n      - name:\
  \ Session Management\n        description: Comprehensive session lifecycle management with configurable timeouts, idle detection, and connection throttling.\n  - type: UseCases\n    data:\n      - name: Custom Network Protocol Implementation\n        description: Build custom client-server protocols over TCP/UDP using MINA's filter chain and codec framework.\n      - name: SSH Automation and File Transfer\n        description: Implement SSH automation, SFTP file transfer, and SCP operations using Apache MINA SSHD.\n      - name: Embedded FTP Server\n        description: Embed a fully functional FTP server within Java applications using Apache FtpServer.\n      - name: High-Concurrency Network Services\n        description: Build network services handling thousands of concurrent connections with minimal resource usage via NIO.\n      - name: IoT Device Communication\n        description: Implement lightweight IoT device communication protocols over TCP/UDP using MINA's framework.\n  - type:\
  \ Integrations\n    data:\n      - name: Spring Framework\n        description: MINA integrates with the Spring Framework for dependency injection and application lifecycle management.\n      - name: SLF4J and Logback\n        description: Native SLF4J logging integration for structured logging across all MINA components.\n      - name: Bouncy Castle\n        description: Bouncy Castle cryptography library integration for SSH key management and cryptographic operations in SSHD.\n      - name: Apache Karaf\n        description: MINA components can be deployed as OSGi bundles in Apache Karaf container.\nmaintainers:\n  - FN: Kin Lane\n    email: info@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/apache-mina/refs/heads/main/apis.yml
tags:
- Async I/O
- Java
- Networking
- NIO
- Protocol Framework
- SSH
url: https://raw.githubusercontent.com/api-evangelist/apache-mina/refs/heads/main/apis.yml
use_cases:
- description: Build custom client-server protocols over TCP/UDP using MINA's filter chain and codec framework.
  name: Custom Network Protocol Implementation
- description: Implement SSH automation, SFTP file transfer, and SCP operations using Apache MINA SSHD.
  name: SSH Automation and File Transfer
- description: Embed a fully functional FTP server within Java applications using Apache FtpServer.
  name: Embedded FTP Server
- description: Build network services handling thousands of concurrent connections with minimal resource usage via NIO.
  name: High-Concurrency Network Services
- description: Implement lightweight IoT device communication protocols over TCP/UDP using MINA's framework.
  name: IoT Device Communication
---
