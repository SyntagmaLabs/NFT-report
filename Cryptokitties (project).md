Links: [explanation of breeding](https://medium.com/cryptokitties/getting-started-with-cryptokitties-part-two-buying-and-breeding-792502e54a4d)

Edits: `PV, Nov 9, 2022`

CryptoKitties is a blockchain game on Ethereum developed by Canadian[1] studio Dapper Labs that allows players to purchase, collect, breed and sell virtual cats.


### [[Breeding (mechanic)]]: how does it work?

> The breeding logic is implemented in the `KittyBreeding` sub-contract of the core contract.
> 
   Super-secret genetic combination algorithm
>
		You probably noticed that the `giveBirth` function calls `mixGenes` function to get the child genes. This `mixGenes` function is actually a part of a sibling contract called `GeneScience` (source code: [v1](https://etherscan.io/address/0xf97e0a5b616dffc913e72455fde9ea8bbe946a2b#code) and [v2](https://etherscan.io/address/0xb77feddb7e627a78140a2a32cac65a49ed1dba8e#code)). `KittyBreeding` just stores a pointer to `GeneScience` contract.
>
		GeneScience` involves lots of bit manipulation to mix the genes of the parent kitties. Remember that genes are stored as a 256-bit number in the `Kitty struct`. These bits are mapped to traits (or _cattributes_ as CK likes to say) that determine the appearance of the kittie.

 How is randomness generated?  
> 
	 Solidity does not have a random number generator so CK uses the block number of when the offspring is born as a seed for randomness. This block number is hard to manipulate so it should give enough randomness
[source](https://betterprogramming.pub/cryptokitties-smart-contract-breakdown-2c3c250d33f6)



#project_stub #project 