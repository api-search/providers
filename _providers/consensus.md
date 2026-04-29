---
api_count: 5
apis:
- description: Paxos is the classical crash-fault-tolerant consensus algorithm introduced by Leslie Lamport in 1989. Paxos and its derivatives (Multi-Paxos, Cheap Paxos, Vertical Paxos, EPaxos, Flexible Paxos) are f
  name: Paxos
  slug: paxos
- description: Raft is a consensus algorithm designed for understandability, published by Ongaro and Ousterhout in 2014. Raft separates leader election, log replication, and safety into distinct concepts and is impl
  name: Raft
  slug: raft
- description: PBFT, by Castro and Liskov (1999), is a Byzantine fault-tolerant consensus protocol that tolerates up to f Byzantine failures with 3f+1 replicas. PBFT influenced subsequent BFT protocols including Ten
  name: Practical Byzantine Fault Tolerance (PBFT)
  slug: pbft
- description: Tendermint (now CometBFT) is a Byzantine fault-tolerant consensus engine that powers Cosmos SDK chains. CometBFT decouples consensus from application logic via the Application Blockchain Interface (AB
  name: Tendermint / CometBFT
  slug: tendermint
- description: HotStuff is a leader-based BFT consensus protocol with linear view change and three-chain commit, designed by Yin et al. HotStuff is the foundation for Diem/Libra BFT and inspired modern protocols lik
  name: HotStuff
  slug: hotstuff
common:
- title: ''
  type: Reference
  url: https://en.wikipedia.org/wiki/Consensus_(computer_science)
- title: ''
  type: Reference
  url: https://en.wikipedia.org/wiki/Paxos_(computer_science)
- title: ''
  type: Reference
  url: https://en.wikipedia.org/wiki/Raft_(algorithm)
- title: ''
  type: Reference
  url: https://en.wikipedia.org/wiki/Byzantine_fault
- title: ''
  type: Reference
  url: https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf
- title: ''
  type: Resources
  url: https://raft.github.io/
created: '2025-01-01'
description: Consensus is the distributed systems problem of getting a set of unreliable processes to agree on a value or sequence of values. Consensus algorithms power state-machine replication for databases, key-value stores, configuration systems, and blockchains. The consensus topic spans classical crash-fault tolerant algorithms (Paxos, Raft, Multi-Paxos, Zab, Viewstamped Replication) and Byzantine fault tolerant algorithms (PBFT, Tendermint, HotStuff, Casper FFG/CBC), and the impossibility result FLP that bounds what is possible in fully asynchronous models.
features: []
image: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg
integrations: []
layout: provider
modified: '2026-04-28'
name: Consensus
skills: []
slug: consensus
solutions: []
source_filename: apis.yml
source_heading: Sources
source_yaml: "aid: consensus\nurl: >-\n  https://raw.githubusercontent.com/api-evangelist/consensus/refs/heads/main/apis.yml\nname: Consensus\nx-type: topic\ndescription: >-\n  Consensus is the distributed systems problem of getting a set of unreliable\n  processes to agree on a value or sequence of values. Consensus algorithms\n  power state-machine replication for databases, key-value stores, configuration\n  systems, and blockchains. The consensus topic spans classical crash-fault\n  tolerant algorithms (Paxos, Raft, Multi-Paxos, Zab, Viewstamped Replication)\n  and Byzantine fault tolerant algorithms (PBFT, Tendermint, HotStuff,\n  Casper FFG/CBC), and the impossibility result FLP that bounds what is\n  possible in fully asynchronous models.\nimage: https://kinlane-productions.s3.amazonaws.com/apis-json/apis-json-logo.jpg\ntags:\n  - Algorithms\n  - BFT\n  - Blockchain\n  - Consensus\n  - Crash Fault Tolerance\n  - Distributed Systems\n  - Replication\n  - State Machine\ncreated: '2025-01-01'\n\
  modified: '2026-04-28'\nspecificationVersion: '0.19'\napis:\n  - aid: consensus:paxos\n    name: Paxos\n    description: >-\n      Paxos is the classical crash-fault-tolerant consensus algorithm\n      introduced by Leslie Lamport in 1989. Paxos and its derivatives\n      (Multi-Paxos, Cheap Paxos, Vertical Paxos, EPaxos, Flexible Paxos)\n      are foundational to distributed systems theory and are used in\n      Google Chubby, Spanner, Megastore, and others.\n    humanURL: https://lamport.azurewebsites.net/pubs/paxos-simple.pdf\n    baseURL: https://lamport.azurewebsites.net\n    tags:\n      - Lamport\n      - Paxos\n      - Replication\n    properties:\n      - type: Specification\n        url: https://lamport.azurewebsites.net/pubs/paxos-simple.pdf\n      - type: Reference\n        url: https://www.cs.utexas.edu/users/lorenzo/corsi/cs380d/papers/paper2-1.pdf\n      - type: Reference\n        url: https://en.wikipedia.org/wiki/Paxos_(computer_science)\n    x-features:\n      - Tolerates\
  \ up to f crash failures with 2f+1 acceptors\n      - Phases prepare, promise, accept, accepted\n      - Multi-Paxos pipelines decisions for log replication\n      - Underlies Google Chubby and Spanner\n    x-useCases:\n      - Replicated state machines\n      - Distributed configuration services (Chubby, ZooKeeper-like)\n      - Globally consistent databases\n  - aid: consensus:raft\n    name: Raft\n    description: >-\n      Raft is a consensus algorithm designed for understandability,\n      published by Ongaro and Ousterhout in 2014. Raft separates leader\n      election, log replication, and safety into distinct concepts and\n      is implemented widely in etcd, Consul, CockroachDB, TiKV, MongoDB,\n      and many other production systems.\n    humanURL: https://raft.github.io/\n    baseURL: https://raft.github.io\n    tags:\n      - etcd\n      - Leader Election\n      - Log Replication\n      - Raft\n    properties:\n      - type: Specification\n        url: https://raft.github.io/raft.pdf\n\
  \      - type: Documentation\n        url: https://raft.github.io/\n      - type: Reference\n        url: https://thesecretlivesofdata.com/raft/\n    x-features:\n      - Strong leader simplifies log replication\n      - Randomized election timeouts\n      - Membership changes via joint consensus\n      - Snapshotting for log compaction\n    x-useCases:\n      - etcd, Consul, CockroachDB, TiKV, MongoDB replica sets\n      - Replicated key-value stores\n      - Configuration management for orchestrators\n  - aid: consensus:pbft\n    name: Practical Byzantine Fault Tolerance (PBFT)\n    description: >-\n      PBFT, by Castro and Liskov (1999), is a Byzantine fault-tolerant\n      consensus protocol that tolerates up to f Byzantine failures with\n      3f+1 replicas. PBFT influenced subsequent BFT protocols including\n      Tendermint and HotStuff.\n    humanURL: http://pmg.csail.mit.edu/papers/osdi99.pdf\n    baseURL: http://pmg.csail.mit.edu\n    tags:\n      - BFT\n      - PBFT\n    properties:\n\
  \      - type: Specification\n        url: http://pmg.csail.mit.edu/papers/osdi99.pdf\n      - type: Reference\n        url: https://en.wikipedia.org/wiki/Byzantine_fault\n    x-features:\n      - Tolerates Byzantine (arbitrary) failures\n      - Three-phase commit protocol (pre-prepare, prepare, commit)\n      - Foundation for many blockchain BFT consensus algorithms\n    x-useCases:\n      - Permissioned blockchains\n      - Hardened configuration systems\n      - Research baseline for new BFT protocols\n  - aid: consensus:tendermint\n    name: Tendermint / CometBFT\n    description: >-\n      Tendermint (now CometBFT) is a Byzantine fault-tolerant consensus\n      engine that powers Cosmos SDK chains. CometBFT decouples consensus\n      from application logic via the Application Blockchain Interface\n      (ABCI), allowing custom blockchain applications in Go, Rust, and\n      other languages.\n    humanURL: https://docs.cometbft.com/\n    baseURL: https://docs.cometbft.com\n    tags:\n\
  \      - ABCI\n      - BFT\n      - Blockchain\n      - CometBFT\n      - Cosmos\n    properties:\n      - type: Documentation\n        url: https://docs.cometbft.com/\n      - type: GitHubRepository\n        url: https://github.com/cometbft/cometbft\n      - type: Reference\n        url: https://docs.cometbft.com/main/spec/consensus/consensus.html\n    x-features:\n      - Round-based BFT consensus with leader rotation\n      - ABCI protocol decouples consensus from application\n      - Instant finality on commit\n      - Powers Cosmos Hub, Osmosis, and other Cosmos SDK chains\n    x-useCases:\n      - Building permissioned and permissionless blockchains\n      - Custom application chains in the Cosmos ecosystem\n  - aid: consensus:hotstuff\n    name: HotStuff\n    description: >-\n      HotStuff is a leader-based BFT consensus protocol with linear view\n      change and three-chain commit, designed by Yin et al. HotStuff is\n      the foundation for Diem/Libra BFT and inspired modern\
  \ protocols\n      like Aptos AptosBFT and Sui's Mysticeti.\n    humanURL: https://arxiv.org/abs/1803.05069\n    baseURL: https://arxiv.org\n    tags:\n      - BFT\n      - HotStuff\n      - Linear\n    properties:\n      - type: Specification\n        url: https://arxiv.org/abs/1803.05069\n      - type: Reference\n        url: https://github.com/hot-stuff/libhotstuff\n      - type: Reference\n        url: https://github.com/aptos-labs/aptos-core\n    x-features:\n      - Linear view change (O(n) message complexity)\n      - Three-chain commit rule\n      - Optimistic responsiveness\n      - Foundation for Diem, Aptos, Sui consensus\n    x-useCases:\n      - Modern blockchain consensus designs\n      - High-throughput, low-latency BFT systems\ncommon:\n  - type: Reference\n    url: https://en.wikipedia.org/wiki/Consensus_(computer_science)\n  - type: Reference\n    url: https://en.wikipedia.org/wiki/Paxos_(computer_science)\n  - type: Reference\n    url: https://en.wikipedia.org/wiki/Raft_(algorithm)\n\
  \  - type: Reference\n    url: https://en.wikipedia.org/wiki/Byzantine_fault\n  - type: Reference\n    url: https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf\n  - type: Resources\n    url: https://raft.github.io/\nmaintainers:\n  - FN: Kin Lane\n    email: kin@apievangelist.com\n"
source_yaml_url: https://raw.githubusercontent.com/api-evangelist/consensus/refs/heads/main/apis.yml
tags:
- Algorithms
- BFT
- Blockchain
- Consensus
- Crash Fault Tolerance
- Distributed Systems
- Replication
- State Machine
url: https://raw.githubusercontent.com/api-evangelist/consensus/refs/heads/main/apis.yml
use_cases: []
---
