**Links**: [docs](https://docs.lens.xyz/docs), [website](https://lens.xyz/)
**Standard**: [[ERC-721 Standard]]
**Chain:** Polygon

Протокол предлагает использовать проектам (в том числе игровым) функционал базового социального графа, а также расширять его на основе модулей. Проект управляется через DAO.

## Products:

User Profile
```
The LensHub upgradeable contract is the core entry point for the majority of interactions in the Lens Protocol. Nearly all interactions begin and doubles as the ERC721 NFT contract for profile NFTs, which are minted upon profile creation.
```

User Follow List
```
Upon a profile's first follow, a FollowNFT contract is deployed (via minimal proxy cloning), unique to the profile; this is the ERC721 NFT contract that represents follower positions.
```

User Publications
```
Lastly, upon a publication's first collect, a CollectNFT contract is deployed (again, via minimal proxy cloning), unique to the publication; this is the ERC721 NFT contract that represents collected publications.
```

NB! Необходимо уточнение какие свойства присутствуют у этих NFT. Насколько это соответствует стандарту SBT?

**Edits**: `IF, Oct 19, 2022`
#project #project_stub 