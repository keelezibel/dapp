# Credits: https://medium.com/@merunasgrincalaitis/the-ultimate-end-to-end-tutorial-to-create-and-deploy-a-fully-descentralized-dapp-in-ethereum-18f0cf6d7e0e

## Technologies 
- Database: Ethereum’s Testnet Ropsten blockchain.
- Hosting: IPFS to get free hosting forever in a descentralized platform.
- Frontend: react.js with webpack, don’t worry I’ll explain the most important steps. You can use whatever framework you like.
- Domain name: godaddy. Here I could use some descentralized domain service like peername but it’s just faster and easier with godaddy or any other domain registrar.
- Contract’s programing language: Solidity 0.4.11, right now the most famous language.
- Frontend contracts: web3.js to use those contracts in your user interface.
- Frameworks: truffle to deploy, test and compile our contracts.
- Development server: node.js to use the app while developing it along with testrpc to use our contracts while developing.
- Metamask: To use the final application like the end user would.

## Solidity contracts
- Start with compiler version
```
pragma solidity ^0.4.11;
```

### Data types
- struct: JS like object
- mapping: Hashmap equivalent

### Modifiers
- payable: in order to execute function you must pay ether
```
function bet(uint number) payable {...
}
```

## Webpack installation
```
npm i webpack -g
```

Have to run webpack to create build.js
