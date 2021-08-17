# Juni NFT 
An NFT deployed to Ethereum network via Alchemy

## Deploy commands
```shell
# Downloads dependencies
npm i
# Compiles solidity
npx hardhat compile
# Deploys contract to Ropsten Test network
npx hardhat run scripts/deploy.js --network ropsten
# Mint an NFT
node scripts/mint-nft.js
```

Juni is deployed to https://ropsten.etherscan.io/token/0xBcCEB0311735beAd044abE6134CE653df2Ea066d