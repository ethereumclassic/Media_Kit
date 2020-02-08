# Hardfork: Aztlan + Phoenix Estimated on June 10th, 2020

#### Tell Us About The Article
* Published Title: Ethereum Classic Aztlán & Phoenix Upgrades set to Activate on Block 10,500,839 Estimated on June 10th, 2020
* Topic: Cryptocurrency
* Author: Donald McIntyre

#### Article Body

On an Ethereum Classic (ETC) core developer call today, it was decided by rough consensus that the Phoenix upgrade, which solves some problems found in the Aztlán upgrade after it was moved to accepted status, will be moved to last call.

# ETC Aztlán and Phoenix upgrades on block 10,500,839.
This means that, if there are no new objections or no issues are found during the testing period, when Phoenix is moved to accepted, both the Aztlán & Phoenix upgrades will be set to be activated on the ETC mainnet at the same time on the same block number 10,500,839, which is estimated to happen around June 10th of 2020.

Final client versions for these upgrades will be announced soon by the corresponding client developer teams.

# Details
## Aztlán Upgrade (ECIP-1061)
### Abstract:
Add support for a subset of protocol-impacting changes introduced in the Ethereum Foundation (ETH) network via the Istanbul hardforks. The proposed changes for Ethereum Classic’s Aztlán upgrade include:
- Add Blake2 compression function F precompile
- Reduce alt_bn128 precompile gas costs
- Add ChainID opcode
- Calldata gas cost reduction
- Rebalance net-metered SSTORE gas cost with consideration of SLOAD gas cost change

Block Numbers:
- 778_507 on Mordor Classic PoW-testnet (activated on Jan 30th, 2020)
- 2_058_191 on Kotti Classic PoA-testnet (approx Feb 12th, 2020)
- 10_500_839 on Ethereum Classic PoW-mainnet (approx Jun 10th, 2020)

### Specification:
Technical specifications for each EIP can be found at those documents respectively:
- EIP-152: Add Blake2 compression function F precompile
- EIP-1108: Reduce alt_bn128 precompile gas costs
- EIP-1344: Add ChainID opcode
- EIP-2028: Calldata gas cost reduction
- EIP-2200: Rebalance net-metered SSTORE gas cost with consideration of SLOAD gas cost change


## Phoenix Upgrade (ECIP-1078)
### Abstract:
The network participants who took part in the ETC Core Developers call on 27th November 2019 were under the impression at the time that the scope we agreed (“Instanbul without the backward-compatibility breaking parts of EIP-1884”) – ECIP-1061 / ECIP-1072 – would move the ETC protocol to a place where it was 100% compatible with the ETH mainnet.

Wei Tang‘s implementation of ECIP-1061 shortly afterwards revealed two flaws in the specification, together with recommendations on how to address those shortcomings.

This ECIP codifies those recommendations.

Both hard-forks would be activated at the same block and the combination of both sets of changes would result in protocol changes which met the original intent.

Block Numbers:
- 976_231 on Mordor Classic PoW-testnet (approx March 4th, 2020)
- 2_208_203 on Kotti Classic PoA-testnet (approx March 11st, 2020)
- 10_500_839 on Ethereum Classic PoW-mainnet (approx June 10th, 2020)

### Specification:
At HARD_FORK_BLOCK, apply the following changes:
- Disable EIP-2200
- Enable EIP-1283 with EIP-1706 instead.
- Enable ECIP-1080

## Voice Call
Bellow is today’s ETC core developer voice call, which was conducted on the ETC Discord voice channel:
- [ETC Core Developer Call Link](https://youtu.be/kqhr378Kmz8)

## Help & Information
For help and information about these upgrades please use the resources and contacts listed bellow:
- Ethereum Classic Discord Server: https://discord.gg/dwxb6nf
- ETC Core Team: https://twitter.com/etc_core
- Stevan Lohja of ETC Core: https://twitter.com/stevanlohja
- Bob Summerwill of ETC Cooperative: https://twitter.com/BobSummerwill
- Ethereum Classic Community Account: https://twitter.com/eth_classic
- Etherplan: https://twitter.com/MyEtherplan

# Code is Law

#### More Details
* URL: `https://etherplan.com/2020/02/05/ethereum-classic-aztlan-phoenix-upgrades-set-to-activate-on-block-10500839-estimated-on-june-10th-2020/9901/`
* Post Image: `https://etherplan.com/wp-content/uploads/2020/02/ETC-Aztlan-and-Phoenix-upgrades-1-1024x573.png`
