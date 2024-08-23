**Links**:  
* [Website](https://decentraland.org/)
* [FAQ](https://docs.decentraland.org/player/general/faq/)
* [WP](https://decentraland.org/whitepaper.pdf)

**Chains**: Ethereum

Decentraland is one of the first and biggest metaverse plays to date. It provides a single, consistent virtual world with individual ownable NFT land parcels inhabited by whatever their owners build on top.

## Architecture
![[decentraland_architecture.png]]
*Source:  [WP](https://decentraland.org/whitepaper.pdf)*

## NFTs
Decentraland runs three types of NFTs:
1. Land parcels
2. Estates
3. Items and assets

### 1) Land parcel NFTs
Standard: [[ERC-721 Standard]] 

**NFT properties**:
* Doesn't evolve over time
* Stable metadata
* No fractuanalization (?)
* Total amount restriction:  the amount of land in Decentraland corresponds to the fixed, total amount of MANA (platform token) (1000 MANA = 1 LAND)

#### How does it look? + What does it include?
	* LAND is divided into parcels that are referenced using unique x,y cartesian coordinates. Each LAND token includes a record of its coordinates, its owner, and a reference to a content description file or [parcel manifest](https://github.com/decentraland/proposals/blob/master/dsp/0020.mediawiki) that describes and encodes the content the owner wishes to serve on his or her land.
*Source: [Docs](https://docs.decentraland.org/player/market/land-manager/)

#### What can you do with it?
* Buy/sell land
* Build some 3D object (e.g.buildings) on it using the [Builder](https://builder.decentraland.org/) or the [SDK](https://docs.decentraland.org/getting-started/installation-guide/)
* Invite people & host digital events on this land
* Showcase other NFTs on this land (e.g. like an art gallery)
* Rent land to other users (read more [here](https://metaverse.properties/rent-in-decentraland/) and [here](https://decentraland.org/blog/community-projects/community-highlights-a-new-way-to-rent-land-in-decentraland/))
* Sale objects that you built on this land 
* Restrict access & Collect revenues from visitors of your land. 
For example, you could make 3D models, images, video, or sound content only visible to a player in Decentraland after they have submitted a payment or fulfilled some other requirement.
* Advertising: brands may advertise using billboards near, or in, high-traffic land parcels to promote their products, services, and events.

Belongs to [[Virtual location ownership rights (mechanic)]]

### 2) ESTATE
An estate is an association of two or more directly adjacent parcels of LAND. These parcels must be directly adjacent and cannot be separated by a road, plaza or any other parcel. By connecting parcels to form Estates, you can more easily manage your larger LAND holdings. Estates are especially useful when building larger scenes that span more than one parcel.

Belongs to [[Transformation (mechanic)]]

### 3) Items and assets

1) **Wearables**:
an avatar appearance items: skin, clothes, accessories, etc.

Links: [opensea](https://opensea.io/collection/decentraland-wearables) 
Belongs to [[Virtual avatar (mechanic)]] 
Chain: Two versions of NFTs in [Ethereum](https://opensea.io/collection/decentraland-wearables) and [Polygon](https://opensea.io/collection/decentraland-polygon-wearables)
Standard: [[ERC-721 Standard]]

2) **Names** 
Domains, fully integrated with the [[ENS Ethereum Name Service (project)]]. 

Belongs to [[Domains (mechanic)]]
Links: [opensea](https://opensea.io/collection/dcl-names)
Chain: Ethereum
Standard: [[ERC-721 Standard]]

3) **Emotes**
Movement of avatar, promoted as a add-on for those who are interested in going to metaverse music festivals. Allows your avatar to dance and do other (sometime weird) movements to stand out.

Belongs to [[Virtual avatar (mechanic)]]
Links: [Decentraland marketplace](https://market.decentraland.org/browse?assetType=item&section=emotes&emotePlayMode=simple)
Chain: Polygon


**Edits**: `PV, Sep 28, 2022`, `AB, Sep 30, 2022`, `PV, Oct 19, 2022`

#project
