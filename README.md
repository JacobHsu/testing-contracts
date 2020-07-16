# testing-contracts

## compile

`npm i solc fs-extra`

### solc

> 0.4.x 與 0.5.x 寫法差異大注意

solidity ^0.5.x solc需降版本

`npm i solc@0.5.17` npm run c

It also accepts an optional set of callback functions, which include the import and the smtSolver callbacks. Starting `0.6.0` it only accepts an object in place of the callback to supply the callbacks.

pragma solidity ^0.5.x; 版本讀取異常 npm安裝後重開專案

## test

`npm i mocha ganache-cli web3`  


[Checking events when testing Solidity smart contracts with Truffle](https://kalis.me/check-events-solidity-smart-contract-test-truffle/)