# Mimosa Discussion

| Subject | |
|-----|-----|
| Premine | [Goto](https://github.com/cartoon-face/resource/blob/main/Discussion.md#premine) |
| Roadmap | [Goto](https://github.com/cartoon-face/resource/blob/main/Discussion.md#roadmap) |

___

## Premine

Discusses how Mimosa's premine will be calculated and ideas on how to use it in an advantage for the Mimosa network.

| | |
|-----|-----|
| Amount to be premined | TBD (?%) |
| Delegated governance fund | TBD |
| Amount to be locked (staked) | TBD |
| Team funds | TBD |
| Private sale? | TBD |
| Initial Giveaway for new users | TBD |

- **Locking Funds (staking)**
  - Staking portions of the premine not only allows for growth & interest of these coins for the future of Mimosa but also this could
prove authenticity of the projects contributing members.
- **Delegated Governance Fund**
  - This fund could be locked for up to 12 months in order to secure funds for airdrops, giveaways...
- **Amount to be locked (staked)**
  - This secures future funds for the Mimosa project developers and community. Can be locked up to 12 months.
- **Team Funds**
  - In order for an effective workflow and to make sure everybody is fairly rewarded for contributing, these funds have been allocated.
- **Initial Giveaway for new users**
  - This could be done as an insentive for people to start engaging in the Mimosa Ecosystem.
  - I.E: We could give 1 full Mimosa coin, plus an additional amount to cover fees, so then people could instantly begin _banking_ coins, allowing the chance to earn more passively.

#### Private Sale

| Pros | Cons |
|-----|-----|
| Secure funds for the project | Unfair advantage for investors |

___

## Roadmap

General ideas, plans and goals for the Mimosa team to achieve.

### Ideas

- **Public Transactions (Overt transactions)**
  - [As mentioned by Aivve](https://github.com/seredat/karbowanec/pull/114]), "The “overt transaction” is a normal transaction that includes a special attachment in its “extra” field that contains disclosures of sender and recipient(s) public addresses and corresponding cryptographic signatures proving payment to destination by only revealing key derivation, not the actual transaction secret key, and allowing to determine which transaction outputs belongs to which address, as well as received amounts. These transactions, however, do not reveal involved parties’s wallet balances, nor previous or subsequent operations."
  - Possible NFO (Non-Fungible Object). As the public address is stored in the "extra" field of a transaction, there is possibility of NFO creation to a limited extent. We would need to figure out how we would implement this into the blockchain (possibly adding an extra field to each tx?) and how we could send them to another address.
- **Blockchain Storage Improvements**
  - [Monero](https://github.com/monero-project/monero/) uses LMDB whereas [Bytecoin](https://github.com/amjuarez/bytecoin/tree/frozen-master) uses RocksDB to store their blockchain information. For Mimosa, we could implement one of the two or a new alternative.
