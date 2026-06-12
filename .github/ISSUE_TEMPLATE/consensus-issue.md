---
name: Consensus Protocol / Network Upgrade Bug
about: Report bugs with consensus mechanisms (QBFT, IBFT 2.0, Clique, PoS) or network fork transitions
title: 'consensus: <summary>'
labels: 'component:consensus'
assignees: ''

---

<!-- Have you done the following? -->
<!--   * Read the Code of Conduct? https://github.com/besu-eth/besu/blob/main/CODE_OF_CONDUCT.md -->
<!--   * Ensured this is related to consensus mechanics, validator behavior, or hard forks -->

### Consensus Protocol Type
* **Protocol**: (e.g. QBFT, IBFT 2.0, Clique, Proof-of-Stake / Engine API)
* **Fork / Upgrade Name**: (if applicable, e.g. Shanghai, Cancun)

### Problem Description
<!--- Describe the consensus issue. (e.g., validators stuck in a round, fork transition failure, bad block validation error, voting/proposer issues) -->

### Validator / Proposer Details
* **Number of validators in the network**: 
* **Proposer node role**: (was the reporting node the proposer?)
* **Validator voting/configuration**: (e.g., block time, epoch, transitions config)

### Network Topology & Setup
* **Genesis Config**: (Please attach or paste the relevant parts of your `genesis.json`)
* **Consensus engine settings**: (e.g., blockperiodseconds, roundexpiryseconds)

### Diagnostic Logs
Please attach validator/consensus specific log files or trace logs:
```text
[Paste logs here]
```

### Software Versions
* **Besu Version**: (`besu --version`)
* **Consensus Client & Version**: (if running PoS)
