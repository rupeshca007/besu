---
name: JSON-RPC API Discrepancy
about: Report errors, unexpected responses, or spec compliance issues with JSON-RPC APIs
title: 'json-rpc: <summary>'
labels: 'component:rpc'
assignees: ''

---

<!-- Have you done the following? -->
<!--   * Read the Code of Conduct? https://github.com/besu-eth/besu/blob/main/CODE_OF_CONDUCT.md -->
<!--   * Verified that the request format matches the Ethereum/Besu JSON-RPC API specification -->

### RPC Method Called
(e.g., `eth_call`, `eth_estimateGas`, `debug_traceTransaction`, `engine_forkchoiceUpdated`)

### Request Details (curl / request body)
Please provide the exact curl command or JSON request payload:
```bash
curl -X POST --data '{"jsonrpc":"2.0","method":"...","params":[],"id":1}' http://localhost:8545
```

### Expected Response / Behavior
What did you expect the API to return? (e.g. spec definition, Geth compliance)

### Actual Response / Behavior
What did Besu actually return?
```json
// Paste JSON response here
```

### Node Environment
* **Besu Version**: (`besu --version`)
* **Genesis Config**: (e.g., Mainnet, QBFT network, etc.)
* **RPC Configuration flags**: (e.g. `--rpc-http-enabled`, `--rpc-http-apis=ETH,NET,DEBUG`)

### Additional Information
* If this issue affects smart contract execution or client tools (e.g. Web3j, Ethers.js, Hardhat), please describe the setup.
