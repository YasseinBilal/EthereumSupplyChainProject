# Supply chain & data auditing

## UML Diagrams

As part of the project planning, I created UML activity, sequence, and state diagrams which are included in UML folder.

## Libraries Write-up

```
 "dependencies": {
    "truffle": "^5.1.51",
    "truffle-assertions": "^0.9.2",
    "truffle-hdwallet-provider": "^1.0.17",
    "web3": "^1.3.0"
  }
```

### Why I used each library:

- truffle: truffle is a development framework for Ethereum that makes it easy to compile, test, and migrate solidity contracts to Ethereum networks. For example, I used truffle to deploy my smart contracts to the Rinkeby test network.

- truffle-assertions: the assertions library for truffle has convenience functions designed for solidity assertions inside of truffle tests. I used the assertion syntax to test whether my contracts correctly emitted different events as expected.

- truffle-hdwallet-provider: this libarary was used to enable my truffle deployments to spend test coins from my Metamask wallet on the goerli network as part of deploying my contracts to goerli

- web3: used to interact with a local or remote ethereum node

## IPFS Write-up
I did not use IPFS for this project.

## General Write-up

I built the dApp in five parts:

Part 1 - Plan the project: I made UML diagrams and described the libraries that I chose to use and why I chose to use them

Part 2 - Write smart contracts: Based on the drafted specifications, I defined the required interfaces for the smart contracts and added the specific logic to each of the contracts: (i) AccessControl (ii) Base (iii) Core

Part 3 - Test smart contract code coverage: I drafted tests to cover every function in the sequence diagram from Part 1 and ensured that all tests were passing.

Part 4 - Deploy smart contracts on Goerli: I used the Truffle framework and Infura to deploy my smart contracts onto the Goerli test network.

Part 5 - Build the frontend: I created a frontend interface that allows users to interact with the smart contracts from the web.

The Goerli contract address for this project is: `0x5C4577DC26D3F37D5Fafa9bA5b37540773534bB7`

The Goerli transaction hash is: `0x05f47b685a2bba6d4206d9f99da80d317b2ca7f33b47abad1c9b255e9659fba7`

## Notes

Goerli network is used for deployment instead on Rinkbey since Rinkeby network is deprecated.



