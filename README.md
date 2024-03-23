# Hardhat fast setup

This repo contains all the information necessary to create and setup a hardhat project quickly. The objective is to have all the information in the same place on the different EVM chains. Do not hesitate to remove the chains that you do not use or adapte the config file to your needs.

## Create & setup Hardhat

Commands from the [doc](https://hardhat.org/hardhat-runner/docs/getting-started):
```shell
npm init -y
npm install --save-dev hardhat
npx hardhat init

npm install --save-dev dotenv
```

I added the `dotenv` package because I use it (and you too probably) in all my projects.

## Config file and .env

You can copy/past the content of the `hardhat.config.ts` file and remove or adapt to fit your needs.

You can do the same with the `.env.example` file but remember to rename it `.env` and add it to your `.gitignore` so you don't push your private information!

## Testnets

Testnets included:
- Polygon Mumbai
- Ethereum Sepolia
- Etherlink Testnet
- Arbitrum Sepolia
- BSC Testnet

## Note

If you don't want to use Alchemy as provider for some of the RPCs, you can go on [ChainList](https://chainlist.org/) and select a public RPC.