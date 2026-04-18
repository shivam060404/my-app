# Integration Map

How components connect and what data flows between them.

### Erc721-stylus --> Frontend-scaffold

- **Source**: Erc721-stylus (`3503d9bd`)
  - Output ports: NFT Contract (contract)
- **Target**: Frontend-scaffold (`236d1301`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Frontend-scaffold --> Wallet-auth

- **Source**: Frontend-scaffold (`236d1301`)
  - Output ports: App Context (config)
- **Target**: Wallet-auth (`033cb90c`)
  
