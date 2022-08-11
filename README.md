# Introduction

This project simply implements the react/hardhat app described in https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13. I used this project to deploy the Greeter and NDToken contracts to the Ropsten testnet and interact with it using the React app.

One thing to note - when creating the basic hardhat project, the contract created was called Lock.sol, instead of Greeter.sol. As a result, I had to add the Greeter.sol file and modify deploy.js to deploy both contracts.