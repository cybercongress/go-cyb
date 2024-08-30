# go-cyb

## Cyb and Neuron personal private blockchain for devices synchronization and earning XP

## cyb-sdk first spec

- Raw content storage - up to 256kB
- Block production on demand (new txs)
- Private chain
- XP token
  - accounting in seconds
  - your attention token
  - put weight on particles
- XP mint
  - mint on particle view
    - authz for minting
- Based on cyber-sdk
  - modules
    - graph
    - clock
    - mint
    - KV
    - CosmWasm
      - with bindings
    - IBC
    - token factory
  - disabled
    - liquid staking
    - V/A and LSP
    - grid
    - ranking -> cyb
    - dex
- Contracts
  - dynamic names for files
- API
  - get cybergraph
  - get content
- IBC
  - particles transfer
  - cyberlinks transfer
- Graph
  - git experience