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
