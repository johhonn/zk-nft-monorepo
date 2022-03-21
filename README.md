# zk-nft-monorepo
smart contracts, front-end, and discord bot for a zero knowledge verification service

Check out the Demo:https://zk-keeper-vue-ui.vercel.app/

Add the Discord bot: https://discord.com/api/oauth2/authorize?client_id=951330025699934259&permissions=534992387136&scope=bot

## TLDR: Prove you own an NFT anonymously and.... profit!
**How it works:** You stake your NFT in the ZK-NFT contract. The contract will add you to a whitelist. In the contract, a commitment is added to an Incremental Binary Tree which can be verified via Circom based on the Groth16 protocol.

Then, you can generate a proof (a cryptographic string) using our frontend. You can think of the proof as a one-time-use password which can be used in any situation (proving you own an NFT, voting anonymously for a DAO, or entering a Bufficorn party!) In our demo, we show you how to access private channels in Discord!

**Inspiration:** Collab.land had a vulnerability where people were proving they owned NFTs without anonymity. People were hacked because they interacted Discord with their private wallet! The solution is to limit Discord's from directly interacting with wallets

For EthDenver Virtual 3/21/2022
