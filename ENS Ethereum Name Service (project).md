**Links**: [website](https://ens.domains/), [opensea](https://opensea.io/collection/ens), [docs](https://docs.ens.domains/)
**Chain**: Ethereum
**Standard**: [[ERC-721 Standard]]

An NFT gives access to the domain name. 
```
ENS’s job is to map human-readable names like ‘alice.eth’ to machine-readable identifiers such as Ethereum addresses, other cryptocurrency addresses, content hashes, and metadata.
```
## How does it work
Three components: 
* **registry** -- for stores information 
* **resolver** -- for the actual process of translating names into addresses.
* **namehash**  -- to generate a unique hash for any valid domain name.

Regarding the registry: 
```
The ENS registry consists of a single smart contract that maintains a list of all domains and subdomains, and stores three critical pieces of information about each:

> -   The owner of the domain
> -   The resolver for the domain
> -   The caching time-to-live for all records under the domain
```
Regarding the resolver:
```
Resolving a name in ENS is a two-step process: First, ask the registry what resolver is responsible for the name, and second, ask that resolver for the answer to your query.
```
*source:* [docs](https://docs.ens.domains/)

## Features
* ENS has a hierarchal nature: anyone who owns a domain at any level may configure subdomains. E.g. from *alice.eth* to *pay.alice.eth*

### Similar projects
1. Unstoppable
2. RNS
3. Handshake
4. Butterfly

**Edits**: `PV, Oct 12, 2022` , `PV, 18 Oct, 2022`
#project