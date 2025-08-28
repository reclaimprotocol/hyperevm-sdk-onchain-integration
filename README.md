# HYPEREVM SDK

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
npx hardhat run scripts/deploy.ts --network luksoTestnet
```
