BettaMinter

This repo contains all the files needed to implement the BettaMinter Front End Design using React + CSS and Bootstrap.

** USE AT YOUR OWN RISK** **NOT RESPONSIBLE FOR ANY ISSUES!! **

1.) Create your react app

npx create-react-app "bettaminter"

2.) Open project folder

https://github.com/ABettaMeta/BettaMinter.git

3.) Install Dependencies:

npm i bootstrap@5.2.0-beta1

npm i react-bootstrap

npm i sf-font

npm i web3modal

npm i @walletconnect/web3-provider

npm i walletlink

npm i web3

npm i axios

npm i ethers axios @nextui-org/react

4.) Fix Webpack limitation for Web3js:

npm uninstall webpack

update "react-scripts" from 5.0.0 to 4.0.3 (or version < 5.0.0) in package.json

delete package-lock.json

npm install webpack@4.44.2

npm install

*https://www.youtube.com/watch?v=IHrcFo1MX60 for help

5.) Deploy your NFT smart contract

6.) Update config.js with all the correct information:

Your NFT Collection Smart Contract Address, Your BSCscan API Key, Your Moralis API Key, Your Alchemy API Key

*Replace any other information regarding the mainnet you are using accordingly. In App.js and nft.js replace infura provider ID's for web3Modal provider. Update to the mainnet you are using (if applicable).

7.) Start your server

npm run start

*Inspired by Net2Dev
