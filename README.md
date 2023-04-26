# KaseiCoin Crowdsale

This project demonstrates the creation and deployment of a token and crowdsale using Ethereum smart contracts. KaseiCoin is an ERC20 token, and the crowdsale follows the minted crowdsale model. The project uses Solidity, Remix IDE, MetaMask, and Ganache for development and deployment.

# Requirements

* Remix IDE
* MetaMask browser extension
* Ganache

# Installation
1. Clone this repository to your local machine:

   https://github.com/Mansa6k/Tokenamics.git

2. Install the MetaMask browser extension by following the instructions at https://metamask.io/download.html.

3. Download and install Ganache from https://www.trufflesuite.com/ganache.

# Usage

1. Open Remix IDE in your web browser.
2. Create or upload the smart contract files for KaseiCoin, KaseiCoinCrowdsale, and KaseiCoinCrowdsaleDeployer.
3. Compile the contracts using the appropriate Solidity compiler version in the "Solidity Compiler" tab.
4. Configure MetaMask to connect to your local Ganache blockchain instance by following the steps provided in the deployment guide.
5. Deploy and interact with the smart contracts using Remix IDE and MetaMask.

# Testing
To test the functionality of the crowdsale:
1. In Remix, under the "Deployed Contracts" section, find the KaseiCoinCrowdsaleDeployer instance.
2. Call the kasei_token_address and kasei_crowdsale_address functions to get the addresses of the deployed KaseiCoin and KaseiCoinCrowdsale contracts.
3. Interact with the KaseiCoinCrowdsale contract using Remix by sending Ether from various test accounts and observe the changes in token balances.

# Deployment

1. Deploy the crowdsale to a local blockchain with Remix, MetaMask, and Ganache.

2. Test the functionality of the crowdsale by using test accounts to buy new tokens and then checking the balances associated with those accounts.

3. After purchasing tokens with one or more test accounts, view the total supply of minted tokens and the amount of wei that has been raised in the crowdsale contract.

# Evaluation Evidence 

Compiled Kaseicoin Contract:

<img width="1436" alt="Kaseicoin_Compiled" src="https://user-images.githubusercontent.com/118853744/234434501-72347e65-c13a-4b9f-a0ef-cf11c33040ba.png">
