# Ordinals

## Overview

- Ordinals were created in early 2022, when the Ordinals specification was finalized.


## Resources 

- [Ordinal Theory Handbook](https://docs.ordinals.com/#)
- [Github](https://github.com/casey/ord/)
- [BIP](https://github.com/casey/ord/blob/master/bip.mediawiki)
- [Mainnet Explorer](https://ordinals.com/)
- [Testnet (Signet) Explorer](https://signet.ordinals.com/)



## Notes

Ordinal Theory is an annotation / tagging system for Bitcoin. It does not alter the Bitcoin protocol in any way, and is fully compatible with all existing Bitcoin software.

Among the first consequences is that Satoshis (the smallest unit of Bitcoin, like 1 wei is the smallest unit of Ether) can be non-fungible. Thus, there are inherent "rarities" to Satoshis.

**Satoshi Rarity**
| Rarity      | Description | Current Supply | Total Supply |
| ----------- | ----------- | ---------- | ------------ |
| Common      | Any Sat not first in block | 1.9 quadrillion | 2.1 quadrillion |
| Uncommon   | First Sat in a block | 745,855 | 6,929,999 |
| Rare      | First Sat of diff adj period | 369 | 3437 |
| Epic   | First Sat of halving epoch | 3 | 32 |
| Legendary | First Sat of each cycle | 0 | 5 |
| Mythix   | First Sat of Genesis block | 1 | 1 |

**Satoshi Names**

> Each satoshi has a name, consisting of the letters A through Z, that get shorter the further into the future the satoshi was mined. They could start short and get longer, but then all the good, short names would be trapped in the unspendable genesis block.
> 
> As an example, 1905530482684727°'s name is "iaiufjszmoba". The name of the last satoshi to be mined is "a". Every combination of 10 characters or less is out there, or will be out there, some day.

**Reads**

- On August 21st, 2012, Charlie Lee posted a [proposal](https://bitcointalk.org/index.php?topic=102355.0) to add proof-of-stake to Bitcoin to the Bitocin Talk forum. This wasn't an asset scheme, but did use the ordinal algorithm, and was implemented but never deployed.

- On October 8th, 2012, jl2012 posted a [scheme](https://bitcointalk.org/index.php?topic=117224.0) to the the same forum which uses decimal notation and has all the important properties of ordinals. The scheme was discussed but never implemented.



