# Aptos InChat Module
Chatting app built on Aptos Token Module and Profile System

#### Intro
Utilize the properties of Token (NFT) on Aptos to manage the account authentication and social graph.

#### Details
Token (NFT) on Aptos, unlike ERC721 on Ethereum, can't directly transfer (airdrop) to others. You have to make offers to receivers and they have to claim to take the NFTs into their inventories. The procedure is like inviting others and waiting for them to confirm. Tokens serve as invitations, which need confirmations to form the relations.

#### Chat Room Token
We designed chat room tokens to send to others as invitation, receivers can enter the chat room after their confirmations (claim the pending offers of tokens). The profile system of this social app is based on [Aptos Profile System](https://github.com/JustaLiang/aptos-profile-system), and the inchat_v1 module wraps 0x3::token_transfers module functions as invite and confirm.

#### Frontend Repo
https://github.com/gregshen0925/aptos-inchat