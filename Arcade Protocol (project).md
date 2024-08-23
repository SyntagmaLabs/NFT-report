Links: [Docs](https://docs.arcade.xyz/docs/what-is-arcade), [ws](https://www.arcade.xyz/)
Standard: [[ERC-721 Standard]]

Arcade.xyz is an application that facilitates NFT liquidity.

### Features

>Asset Vault
>
>-   **Asset Vault** - Create a Vault and deposit one or multiple NFT(s) into the Vault. Vault owners receive an [[ERC-721 Standard]]  token representing ownership of the Vault. Vaults can hold any or all of ETH, ERC20s, ERC721, ERC1155, and/or CryptoPunks.
>-   **Airdrop Utility** - Receive airdrops for NFT assets held in a Vault.
>
> Borrowing
>
>-   **Set Terms** - Asset owners can set terms on their Vault or NFT - specifying (ERC20), duration, interest rate, for term loans of positive duration, collateralized by the assets in the Vault or NFT.
>-   **Trustless Matching** - Lenders can fund a loan request trustlessly and once countersigned, either lender or borrower can marshal a loan for on-chain settlement.
>-   **Borrower Note** - Upon settling a loan on-chain, the funding amount is disbursed to the borrower's address, the encapsulated assets in a Vault are held in escrow by the protocol, and the borrower receives a borrower note (ERC721) that represent their claim to the assets upon loan repayment.
>-   **No Prepayment Penalty** - Loans can be paid off any time to recoup assets held in escrow on-chain with the protocol.
>
>Lending
>
>-   **Offers** - Lenders can make offers on Vaults or NFTs.
>-   **Collection Offers** - Lenders can also make offers on many of the popular collections in the space.
>-   **Trustless Matching** - Borrowers can settle a loan by accepting a loan offer trustlessly since the Lender has digitally signed the terms of the offer and approved the funding amount for those terms to the Arcade Protocol.
>-   **Lender Note** - Upon settling a loan on-chain, the lender transfers the funding amount from their wallet to the borrower's and receive a lender note (ERC721) that represents their claim on the Vault encapsulating the assets collateralizing the loan (and therefore a claim on the assets themselves) if the loan were to default.
>-   **Trustless Claims** - Simple logic embedded in the Arcade Protocol dictates whether a loan is in default. If the principal and interest amount have not been paid by the end of the loan duration, the loan is claimable. The Vault, and therefore the underlying assets collateralizing the defaulted loan, are transferred on-chain to the address that owns the lender note.

[source](https://docs.arcade.xyz/docs/what-is-arcade)

Edits: `PV, Nov 16, 2022`
#project