---
description: Self-funding Mechanism
---

# Revenue Model

Just like any traditional game, Evolution Land generates revenue from players' activities. 

## Revenue Sources

This revenue comes through these channels:

- **New Land Auction**
  When new Land is put into the market, the auction income contributes to the revenue.

- **New Apostle sales** 
  Limited first-generation Apostle were sold at a fixed price; these contribute to the revenue pool.

- **Second Market Trade Tax** 
  When a user lists their property Land, Apostle, or other props on the in-game marketplace, a small fee is charged if the trade is successful. 

- **Apostle Birth Fee** 
  When breeding a new Apostle, a small birth fee is charged.

- **Magic Potion Sales** 
  Magic Potion sales income contributes to the revenue pool.

- **Inter-continent Import Tax** 
  When some goods, resources, or Apostles are transferred from other continents, inter-continent import tax is charged.

- **Business Tax** 
  Any other commercial business activities are charged for a small tax.

The Parliament determines all the tax rates and fees listed above through the Governance process. Altogether, they build up the revenue to be distributed.

## Revenue Distribution

When game revenue is generated, it's distributed automatically and simultaneously within the same transaction. The processing logic for each transaction is as follows:

1. Send expense to the designated recipient
2. Invoke on-chain logic to process the transaction (such as transfer ownership of an asset)
3. Pay referral reward to the referrer if there's any
4. Split revenue (tax/fee) and send to destination contract for further distribution.

System revenue will be split and sent to four special-purpose pools for further distribution. Their allocation is as follows:

- Trading Reward Pool (Lottery Pool): 10%
- Content Contribution Incentive Pool: 30%
- Governors Pool: 30%
- Operations & Dev Pool: 30%

The allocation percentage is subject to the governance process.

![Revenue Distribution](../../.gitbook/assets/system-revenue.png)

### Trading Reward Pool

This is also called the lottery pool. When players spent some money in the game, they are rewarded with Points that act as lottery tickets. Players can use them in the "Happy Lottery" gameplay to win a grand prize. The prize pool is filled up by this lottery tax from each spending transaction.

Check out Point and Lottery for more information.

### Content Contribution Incentive Pool

This pool's purpose is to incentivize users that contribute to the prosperity of the game eco-system, either by designing buildings, attracting more users to the game, other any constructive ways to help the community grow. This pool can also serve as the funding for per-case grant applicants.

Because of the subjective nature of this pool's purpose, no money has been spent yet. With the Governance module coming online, users can submit a proposal to apply for funding or tips.

### Governor Pool

Governor is a paying job. Any player can become a governor to participate in the governance process as long as they have staked interest in the game. This pool incentivizes governors' sacrificed liquidity.

Check out [Governance](governance.md) for more information.

### Operations & Dev Pool

This pool is reserved for the bootstrapping dev team to subside human resources and operation costs.