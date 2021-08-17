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