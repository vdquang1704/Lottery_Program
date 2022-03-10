# Prerequisites
1. Install nodejs
2. Install python

# Installation
1. Install Brownie

```bash
python3 -m pipx ensurepath
restart your terminal
pip install eth-brownie
```

2. Get a WEB3_INFURA_PROJECT_ID by getting a free trial Infura, get PRIVATE_KEY from metamask wallet and add your environments variables to .env 

3. Install ganache-cli for local testing
```bash
npm install -g ganache-cli
```
or
```bash
yarn add global ganache-cli
```

# Deploying
```bash
brownie run scripts/deploy.py (on local test net)
```
or
```bash
brownie run scripts/deploy_lottery.py --network "network_name" (on testnet)
```

# Testing
```bash
brownie test (on local testnet)
```
or
```bash
brownie test --netwrok "network_name" (on testnet)
```




