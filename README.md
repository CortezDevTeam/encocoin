EncoCoin Core integration/staging repository
=====================================

[![Build Status](https://travis-ci.org/EncoCoin-Project/EncoCoin.svg?branch=master)](https://travis-ci.org/EncoCoin-Project/EncoCoin) [![GitHub version](https://badge.fury.io/gh/EncoCoin-Project%2FEncoCoin.svg)](https://badge.fury.io/gh/EncoCoin-Project%2FEncoCoin)

EncoCoin is an open source crypto-currency focused on fast private transactions using the Zerocoin protocol, with low transaction fees & environmental footprint.  It utilizes the first ever anonymous proof of stake protocol, called zPoS, combined with regular PoS and masternodes for securing its network. zPoS incentivises using the privacy features available in EncoCoin by granting a higher block reward for zPoS over regular PoS and masternodes. In practice EncoCoin has between 4 to 10 times higher use of it's privacy features in comparison to other coins that combine public and private transactions. This is thanks to innovations like zPoS and integrating the Zerocoin protocol into light/mobile wallets, allowing for a complete and lightweight privacy protocol that can be used on the go. As well as security improvements like [deterministic generation of zXNK for easy backups.](https://www.reddit.com/r/encocoin/comments/8gbjf7/how_to_use_deterministic_zerocoin_generation/)
The goal of EncoCoin is to achieve a decentralized sustainable crypto currency with near instant full-time private transactions, fair governance and community intelligence.
- Anonymized transactions & consensus using the [_Zerocoin Protocol_](http://www.encocoin.org/zpiv) and [zPoS](https://encocoin.org/zpos/).
- light/mobile wallet privacy using the [Zerocoin Light Node Protocol](https://encocoin.org/wp-content/uploads/2018/11/Zerocoin_Light_Node_Protocol.pdf)
- Fast transactions featuring guaranteed zero confirmation transactions, we call it _SwiftX_.
- Decentralized blockchain voting utilizing Masternode technology to form a DAO. The blockchain will distribute monthly treasury funds based on successful proposals submitted by the community and voted on by the DAO.

More information at [encocoin.org](http://www.encocoin.org) Visit our ANN thread at [BitcoinTalk](http://www.bitcointalk.org/index.php?topic=1262920)

### Coin Specs
<table>
<tr><td>Algo</td><td>Quark</td></tr>
<tr><td>Block Time</td><td>60 Seconds</td></tr>
<tr><td>Difficulty Retargeting</td><td>Every Block</td></tr>
<tr><td>Max Coin Supply (PoW Phase)</td><td>43,199,500 XNK</td></tr>
<tr><td>Max Coin Supply (PoS Phase)</td><td>Infinite</td></tr>
<tr><td>Premine</td><td>60,000 XNK*</td></tr>
</table>

*60,000 XNK Premine was burned in block [279917](http://www.presstab.pw/phpexplorer/EncoCoin/block.php?blockhash=206d9cfe859798a0b0898ab00d7300be94de0f5469bb446cecb41c3e173a57e0)

### Reward Distribution

<table>
<th colspan=4>Genesis Block</th>
<tr><th>Block Height</th><th>Reward Amount</th><th>Notes</th></tr>
<tr><td>1</td><td>60,000 XNK</td><td>Initial Pre-mine, burnt in block <a href="http://www.presstab.pw/phpexplorer/EncoCoin/block.php?blockhash=206d9cfe859798a0b0898ab00d7300be94de0f5469bb446cecb41c3e173a57e0">279917</a></td></tr>
</table>

### PoW Rewards Breakdown

<table>
<th>Block Height</th><th>Masternodes</th><th>Miner</th><th>Budget</th>
<tr><td>2-43200</td><td>20% (50 XNK)</td><td>80% (200 XNK)</td><td>N/A</td></tr>
<tr><td>43201-151200</td><td>20% (50 XNK)</td><td>70% (200 XNK)</td><td>10% (25 XNK)</td></tr>
<tr><td>151201-259200</td><td>45% (22.5 XNK)</td><td>45% (22.5 XNK)</td><td>10% (5 XNK)</td></tr>
</table>

### PoS Rewards Breakdown

<table>
<th>Phase</th><th>Block Height</th><th>Reward</th><th>Masternodes & Stakers</th><th>Budget</th>
<tr><td>Phase 0</td><td>259201-302399</td><td>50 XNK</td><td>90% (45 XNK)</td><td>10% (5 XNK)</td></tr>
<tr><td>Phase 1</td><td>302400-345599</td><td>45 XNK</td><td>90% (40.5 XNK)</td><td>10% (4.5 XNK)</td></tr>
<tr><td>Phase 2</td><td>345600-388799</td><td>40 XNK</td><td>90% (36 XNK)</td><td>10% (4 XNK)</td></tr>
<tr><td>Phase 3</td><td>388800-431999</td><td>35 XNK</td><td>90% (31.5 XNK)</td><td>10% (3.5 XNK)</td></tr>
<tr><td>Phase 4</td><td>432000-475199</td><td>30 XNK</td><td>90% (27 XNK)</td><td>10% (3 XNK)</td></tr>
<tr><td>Phase 5</td><td>475200-518399</td><td>25 XNK</td><td>90% (22.5 XNK)</td><td>10% (2.5 XNK)</td></tr>
<tr><td>Phase 6</td><td>518400-561599</td><td>20 XNK</td><td>90% (18 XNK)</td><td>10% (2 XNK)</td></tr>
<tr><td>Phase 7</td><td>561600-604799</td><td>15 XNK</td><td>90% (13.5 XNK)</td><td>10% (1.5 XNK)</td></tr>
<tr><td>Phase 8</td><td>604800-647999</td><td>10 XNK</td><td>90% (9 XNK)</td><td>10% (1 XNK)</td></tr>
<tr><td>Phase 9</td><td>648000-1154203</td><td>5 XNK</td><td>90% (4.5 XNK)</td><td>10% (0.5 XNK)</td></tr>
<tr><td>Phase X</td><td>1154203-∞</td><td>6 XNK</td><td>84% (5 XNK/zXNK)</td><td>16% (1 XNK)</td></tr>
</table>
