Links: [ws]( https://fractional.art/), [FAQ](https://medium.com/fractional-art/things-to-know-before-fractionalizing-nft-s-83d95a12f52c)
Standards: [[ERC-20 Standard]] or [[ERC-1155 Standard]]


The Fractional project allows users to fractionalize their NFTs

NB: the support for the project is reduced, the core team has started developing new project Tessera - http://tessera.co/.

### Principle

An NFT that is splited into fractions stored in Fractional Vault.
Once an NFT is fractionalized it is possible to use it for:
-   Sending them to friends to split and share ownership of an NFT
-   Airdropping them to community members or owners of certain tokens
-   Providing liquidity to a decentralized exchange (DEX)

The only way to retrieve NFT(s) from a vault is by redeeming 100% of the fractions for the vault, or by buying out the vault through an auction.
[source](https://medium.com/fractional-art/so-you-fractionalized-your-nft-now-what-86d896eb3edc)
### Deep-dive into [[Fractionalization (mechanic)]] 

>**What determines the price of a fraction?**
   Initially, the price of a fraction is set by the creator of the vault. They typically make fractions available in a liquidity pool via a fraction-to-ETH pairing using an AMM (e.g., Uniswap v3) which sets the price in ETH. Once purchases of the vault’s fractions begin, the price per fraction is dynamic and impacted by supply, demand, AMM bonding curves, whoever else decides to provide liquidity, and even how many fractions you are looking to collect.

>**Q: What does buying a fraction mean for me?**
> **_Fractional Ownership_**: You can say you own a part of the NFT(s) within the vault, prove to everyone you do in your wallet, join token-gated communities related to the vault, and appreciate the art within the vault collection you are now an owner of.
>
>**_Flexibility_**: You have full control over what you do with the fractions you now own, which function as typical ERC-20 tokens. Voting Rights: When you own fractions, you can vote on the reserve price (ETH) for its vault which is the weighted average of all reserve price votes, based on the % of total fraction supply the voter owns. The reserve price is the minimum price someone needs to bid in order to trigger an auction!
>
>**_ETH_**: If and when a buyout for the vault completes, all fraction owners will be able to trade in their fractions in exchange for the winning ETH. Your owned % of the total supply of fractions equals the % of winning ETH you will receive. So if you own 5% of ΞFRACTIONAL for example, and ΞFRACTIONAL gets bought out for 100 ETH, you can claim 5 ETH back in return for your ΞFRACTIONAL tokens.

>**Q: Why is this token so expensive?**
>
  A: This is a function of how liquidity pools work. The more liquidity there is, relative to the position you’re trying to trade, the easier it is to find a lower price. Note: _If you’re interacting with a vault, and you see this warning, it’s a sign that liquidity is low. The implied valuation or “value” of the token at time of your trade may differ from the overall implied valuation of the vault._

>**Q: Who sets the reserve price?**
>A: The reserve price is the weighted average of all owners of the fraction who have set a reserve price. The auction process is kicked off when a bidder sets a bid that’s equal to or higher than the reserve price. The minimum length of an auction is 3 days and maximum is 8 days.
   [source](https://medium.com/fractional-art/a-beginners-guide-to-buying-fractions-on-fractional-art-dfa91a355d0f)

### How unfractionalization works?

>Un-fractionalizing NFTs is one of the hardest challenges builders in this space face. In Fractional, un-fractionalization is determined by token holders voting on a reserve price, a weighted average of all reserve price votes. When a big enough majority of holders vote on a minimum price, a buyout is triggered and all owners can trade in their tokens for ETH (see here for fuller details).

[More info about unfractionalization](https://medium.com/fractional-art/dust-rekt-me-what-now-2c175e687978)

Edits: `PV, Nov 16, 2022`
#project