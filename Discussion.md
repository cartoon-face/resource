# Mimosa Discussion

| Subject | |
|-----|-----|
| Premine | [Goto]() |
| Roadmap | [Goto]() |

___

## Premine

Discusses how Mimosa's premine will be calculated and ideas on how to use it in an advantage for the Mimosa network.

| | |
|-----|-----|
| Amount to be premined | 5,000,000 |
| Delegated governance fund | 2,500,000 |
| Amount to be locked (staked) | 1,000,000 |
| Team funds | 500,000 |
| Private sale? | TBD |

#### Locking Funds (staking)

Staking portions of the premine not only allows for growth & interest of these coins for the future of Mimosa but also this could
prove authenticity of the projects contributing members.

#### Delegated Governance Fund

This fund could be locked for up to 12 months in order to secure funds for airdrops, giveaways...

#### Amount to be locked (staked)

This secures future funds for the Mimosa project developers and community. Can be locked up to 12 months.

#### Team Funds

In order for an effective workflow and to make sure everybody is fairly rewarded for contributing, these funds have been allocated.

#### Private Sale

| Pros | Cons |
|-----|-----|
| Secure funds for the project | Unfair advantage for investors |

___

## Roadmap

General ideas, plans and goals for the Mimosa team to achieve.

### Ideas

- Public Transactions (Overt transactions)
  - [As mentioned by Aivve](https://github.com/seredat/karbowanec/pull/114]), "The “overt transaction” is a normal transaction that includes a special attachment in its “extra” field that contains disclosures of sender and recipient(s) public addresses and corresponding cryptographic signatures proving payment to destination by only revealing key derivation, not the actual transaction secret key, and allowing to determine which transaction outputs belongs to which address, as well as received amounts. These transactions, however, do not reveal involved parties’s wallet balances, nor previous or subsequent operations."
- Blockchain Storage Improvements
  - [Monero](https://github.com/monero-project/monero/) uses LMDB whereas [Bytecoin](https://github.com/amjuarez/bytecoin/tree/frozen-master) uses RocksDB to store their blockchain information. For Mimosa, we could implement one of the two or a new alternative.
