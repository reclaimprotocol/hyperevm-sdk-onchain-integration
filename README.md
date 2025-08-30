# HYPEREVM SDK

## Deployments

| Chain Name | Deployed Address | Explorer Link |
|:-----------|:-----------------|:--------------|
| HyperEVM | 0xaC4EBd4b459c29D553B25A55ABA0aBC12bBFd6f5 | https://purrsec.com/address/0xaC4EBd4b459c29D553B25A55ABA0aBC12bBFd6f5/contract |

## Setup

Install dependencies:

```
npm install --legacy-peer-deps
```

Populate your .env:

```
PRIVATE_KEY=your-private-key-here
```

## Commands

Run Tests:

```
npm run test
```

Deploy Contracts on Testnet:

```
npx hardhat run scripts/deploy.ts --network hyperevm
```

Add new epoch:

```
npx hardhat add-new-epoch --host "wss://attestor.reclaimprotocol.org/ws" --address "0x244897572368eadf65bfbc5aec98d8e5443a9072" --network hyperevm
```
