# Prerequisites
1. Install nodejs
2. Install python

# Installation
Install Brownie

python3 -m pipx ensurepath
restart your terminal
pip install eth-brownie

Get a WEB3_INFURA_PROJECT_ID by getting a free trial Infura, get PRIVATE_KEY from metamask wallet and add your environments variables to .env 

Install ganache-cli for local testing
npm install -g ganache-cli
or
yarn add global ganache-cli

# Deploying
brownie run scripts/deploy.py (on local test net)
or
brownie run scripts/deploy_lottery.py --network "network_name" (on testnet)

# Testing
brownie test (on local testnet)
or
brownie test --netwrok "network_name" (on testnet)




