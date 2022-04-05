Udacity Blockchain Capstone
The capstone project is to build a decentralized real estate marketplace.

Install
To install, download or clone the repo, then:

npm install
cd eth-contracts/
truffle compile
Test
To run truffle tests:

truffle test
Rinkeby Details
See rinkeby_deployment.txt for Contract address and other information

Owner account address -
0x7Ef674F56bc1be485FA083bdD93d549D943c3608

Mint details on Etherscan
Mint Tokens - Asset ID
Open Sea details
https://testnets.opensea.io/assets/0x7Ef674F56bc1be485FA083bdD93d549D943c3608/11

https://testnets.opensea.io/assets/0x7Ef674F56bc1be485FA083bdD93d549D943c3608/22

https://testnets.opensea.io/assets/0x7Ef674F56bc1be485FA083bdD93d549D943c3608/33

https://testnets.opensea.io/assets/0x7Ef674F56bc1be485FA083bdD93d549D943c3608/44

https://testnets.opensea.io/assets/0x7Ef674F56bc1be485FA083bdD93d549D943c3608/55

https://testnets.opensea.io/assets/0x7Ef674F56bc1be485FA083bdD93d549D943c3608/66

https://testnets.opensea.io/assets/0x7Ef674F56bc1be485FA083bdD93d549D943c3608/77

https://testnets.opensea.io/assets/0x7Ef674F56bc1be485FA083bdD93d549D943c3608/88

https://testnets.opensea.io/assets/0x7Ef674F56bc1be485FA083bdD93d549D943c3608/99


Sold House - Asset ID 11, 22,

Deploying
Create a .env file (in eth-contracts) with MNEMONIC & Infura ENDPOINT_KEY
truffle compile
truffle migrate --network rinkeby
Tests
truffle test
Using network 'development'.


Compiling your contracts...
===========================
> Everything is up to date, there is nothing to compile.



  Contract: TestERC721Mintable
    match erc721 spec
      ✓ should return total supply
      ✓ should get token balance (91ms)
      ✓ should return token uri
      ✓ should transfer token from one owner to another (285ms)
    have ownership properties
      ✓ should return contract owner
      ✓ should fail minting when address is not contract owner
    have pausable properties
      ✓ can pause and unpause (151ms)
      ✓ should return pause status (40ms)
      ✓ should fail minting when contract is paused (96ms)

  Contract: Test SolnSquareVerifier
    test token minting by providing solution
      ✓ should mint token for correct proof (741ms)
      ✓ should not allow solution reuse (722ms)
      ✓ should not mint token for incorrect proof (1295ms)

  Contract: Test SquareVerifier
    test verification
      ✓ should return true for correct proof (658ms)
      ✓ should return false for incorrect proof (628ms)


  14 passing (13s)



Project Resources
Remix - Solidity IDE
Visual Studio Code
Truffle Framework
Ganache - One Click Blockchain
Open Zeppelin
Interactive zero knowledge 3-colorability demonstration
Docker
ZoKrates