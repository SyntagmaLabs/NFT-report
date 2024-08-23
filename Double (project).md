
**Links:** [Docs]([https://docs.double.one/](https://vk.com/away.php?to=https%3A%2F%2Fdocs.double.one%2F&cc_key=)) [Glossary](https://docs.double.one/concepts/glossary) [ws](https://double.one/)
**Standards:** [[ERC-5006 Standard (extension)]] and [[ERC-4907 Standard (extension)]]

Double Protocol is an open-source protocol for lending and renting ERC-721 and ERC-1155 NFTs.
It operates accprding to [[Splitting of ownership, revenue and usage rights (mechanic)]]

### How does it work?

oNFT(Original NFT) is ERC-4907 standard NFT that is created to assign a new “User role” that would represent a renter with limited rights.

For NFT’s that cannot be upgraded to the ERC-4907 / 5006 standard, a new wNFT is created:

	The lender can deposit the original NFT into Double’s contract, which will then mint a new *“wNFT”* that would contain the user role and expires function which would facilitate renting. This technique is inspired by the *wrapped ETH (wETH)* model that guarantees the 1-to-1 ratio in order to prevent double-spending.  
  
To limit the time of useage of an NFT doNFTs are created:

	doNFT complies with the ERC-721 standard and represents a certificate for the right to use the NFT within a specific time.  Corresponding doNFT contracts can be created according to the original NFT contracts, where each oNFT ID corresponds to one or more doNFTs.  [...] doNFT’s automatically expire. After the expiration, the doNFT holder can choose to burn the doNFT, or keep it in the wallet as a souvenir. The Double frontend will not display expired doNFTs by default.  
  
In order to redeem the original NFT a voucher vNFT  is created:
  
	A vNFT is a special kind of doNFT whose duration is infinite once minted. The user can redeem the oNFT only when all durations from now until the future are under the name of the owner of the vNFT.  [...] Users can freely transfer ownership of vNFT to any third party, but this is something users need to be cautious of because once it is transferred to someone else, it is assumed that the user cannot get the oNFT back.  
  
***Royalty treatment***
The royalty-related information is recorded in the doNFT contract, and the doNFT deployer can set it accordingly so that a third-party market can directly distribute the royalty based on the existing interface of the doNFT without the need for secondary configuration in the market.

***The mechanics:***


![[Double_ERC4907-Model-Time-Diagram.jpg]]

**Edits:** `PV, Oct 18, 2022`

#project 