1. Users can enter lottery with ETH based on a USD fee
2. An admin will choose when the lottery is over
3. The lottery will select a random winner

Prerequisites
1. Install nodejs
2. Install python

Installation
1. Install Brownie
python3 -m pipx ensurepath
# restart your terminal
pip install eth-brownie

2. Get a WEB3_INFURA_PROJECT_ID by getting a free trial Infura, get PRIVATE_KEY from metamask wallet and add your environments variables to .env 

3. Install ganache-cli for local testing
npm install -g ganache-cli
or
yarn add global ganache-cli

4. Deploying
brownie run scripts/deploy.py (on local test net)
or
brownie run scripts/deploy_lottery.py --network "network_name" (on testnet)

5. Testing
brownie test (on local testnet)
or
brownie test --netwrok "network_name" (on testnet)




