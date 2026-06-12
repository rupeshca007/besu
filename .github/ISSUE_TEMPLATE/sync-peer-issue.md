---
name: Node Syncing & Peer Connectivity Issue
about: Report issues with node synchronization (fast, snap, full sync) or peer connections
title: 'sync: <summary>'
labels: 'component:sync'
assignees: ''

---

<!-- Have you done the following? -->
<!--   * Read the Code of Conduct? https://github.com/besu-eth/besu/blob/main/CODE_OF_CONDUCT.md -->
<!--   * Reproduced or verified this sync issue is not a temporary network glitch -->
<!--   * Searched for existing sync/peer issues in this repository -->

### Sync Configuration
* **Sync Mode**: (e.g. Snap Sync, Fast Sync, Full Sync, Checkpoint Sync)
* **Genesis Config Type**: (e.g. Mainnet, Sepolia, Goerli, Custom Private)
* **Consensus Mechanism**: (e.g. Clique, IBFT 2.0, QBFT, PoS/Merge)
* **Consensus Client & Version**: (if running PoS, e.g. Teku 23.4.0)

### Symptoms & Behavior
* Describe the exact sync issue (e.g., node stuck at block X, no peers found, snap sync loop, CPU spiking during sync).
* **Current block height / target block height**: 
* **Number of active peers**: (from `admin_peers` or logs)

### Diagnostic Logs
Please paste relevant log snippets showing sync errors, peer disconnects, or warnings.
```text
[Paste logs here]
```

### Environment
* **Besu Version**: (`besu --version`)
* **Java Version**: (`java -version`)
* **OS / Kernel**: (`uname -a` or equivalent)
* **Network/Bandwidth Specs**: (e.g. 1 Gbps, restricted ports)
* **Disk/Storage Specs**: (e.g. NVMe, SSD, HDD, cloud storage type)

### Additional Details
* Genesis file content (if custom/private)
* Besu startup command flags
