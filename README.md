# Crypto Boy NFT Marketplace
<i>NFT marketplace DApp where users mint HRC721 implemented Crypto Boy NFTs.</i>
#
<img align="right" width="350" src="./image.png"></img>
### Features
- Mint custom HRC721 implemented Crypto Boy Tokens.
- Sell Crypto Boy tokens on the marketplace.
- Set desired token price.
- Toggle between keeping the token for sale and not for sale.
- Keeps track of all the tokens owned by an account - minted and bought.
- Query blockchain for token owner and token metadata.
- User can mint a token only after every 5 minutes.
#
### Stack
- [Solidity](https://docs.soliditylang.org/en/v0.7.6/) - Object-oriented, high-level language for implementing smart contracts.
- [Bootstrap 4](https://getbootstrap.com/) - CSS framework for faster and easier web development.
- [React.js](https://reactjs.org/) - JavaScript library for building user interfaces.
- [web3.js](https://web3js.readthedocs.io/en/v1.3.4/) - Allows users to interact with a local or remote ethereum node using HTTP, IPC or WebSocket.
- [Truffle](https://www.trufflesuite.com/truffle) - Development environment, testing framework and asset pipeline for blockchains using the Ethereum Virtual Machine (EVM).
- [Ganache](https://www.trufflesuite.com/ganache) - Personal blockchain for Ethereum development used to deploy contracts, develop DApps, and run tests.
#
### Interact with the deployed DApp
- Crypto Boy Marketplace DApp requires [Altmasq](https://github.com/HTMLCOIN/metamask-extension/releases/) browser wallet extension to interact with.
- Request and get HTML for the altmasq account from [Htmlcoin Faucet](https://gruvin.me/htmlcoin) to make transactions.
- Crypto Boy Marketplace Smart Contract is deployed to Htmlcoin Mainnet - [0x2f1f618697481ababa29083fd9cd37adcd7a1656](https://explorer.htmlcoin.com/address/0x2f1f618697481ababa29083fd9cd37adcd7a1656)
- Access Crypto Boy Marketplace DApp at [cryptoboys-NFT-marketplace](https://janus.htmlcoin.dev/cryptoboys/) and start minting your Crypto Boys.
#
### Run the DApp Locally
#### Install truffle
```
npm install -g truffle
```
#### Install ganache-cli
```
npm i ganache-cli
```
#### Run ganache-cli
```
ganache-cli --port 7545
```
#### Open new terminal window and clone this repository
```
git clone https://github.com/htmlcoin/cryptoboys-NFT-marketplace.git
```
#### Install dependencies
```
cd cryptoboys-NFT-marketplace
npm install
```
#### Compile smart contract
```
truffle compile
```
#### Deploy smart contract to ganache
```
truffle migrate
```
#### Test smart contract
```
truffle test
```
#### Start DApp
```
npm start
```
- Open altmasq browser wallet and connect network to Localhost 4889.
- Import accounts from ganache-cli into the metamask browser wallet to make transactions on the DApp.
