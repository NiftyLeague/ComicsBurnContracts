## ComicsBurnContracts

### Developer instructions

#### Install dependencies
`yarn install`

#### Compile code
- `yarn run compile` (Compiles the entire project, building all artifacts)

#### Run tests
- `yarn run test ./test/{desired_test_script}`

#### Deploy code 
- `npx hardhat node` (Starts a JSON-RPC server on top of Hardhat Network)
- `yarn run deploy:hardhat` (Deploy the contracts on Harhdat Network)
- `yarn run deploy:remote {network}` (Deploy the contracts on the Mainnet or Testnet)

#### Etherscan verification
- `npx hardhat --network {network} etherscan-verify --api-key {etherscan_api_key}`