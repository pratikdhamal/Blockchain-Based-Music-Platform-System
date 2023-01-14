# Blockchain-Based-Music-Platform-System
Developed a blockchain-based music platform to address issues with music copyright, lack of transparency, and made a decentralized network to provide the revenue model for an artist payment.

# Setup for Blackchain NFT Metamask account- 

1. First Clone this project and open index.html main file & then do below setup for blockchain inside particular directory.

Step1- Install Dependencies:
  
  $ cd music_nfts
  
  $ npm install

Step2- Boot up local development blockchain

$ cd music_nfts

$ npx hardhat node

Step3- Connect development blockchain accounts to Metamask

Step4- Copy private key of the addresses and import to Metamask

Step5- Connect your metamask to hardhat blockchain, network 127.0.0.1:8545.

If you have not added hardhat to the list of networks on your metamask, open up a browser, click the fox icon, then click the top center dropdown button that lists all the available networks then click add networks. A form should pop up. For the "Network Name" field enter "Hardhat". For the "New RPC URL" field enter "http://127.0.0.1:8545". For the chain ID enter "31337". Then click save.

Step6- Run deploy script to migrate smart contracts

npm run deploy

Step7- Run Tests

$ npx hardhat test

Step8- Launch Frontend
$ npm run start

