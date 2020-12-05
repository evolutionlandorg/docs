---
description: Self-funding Mechanism
---

# 收入模型

## 系统收入来源

（1）创世拍卖收入：拍卖创世地块、创世使徒的部分收入。（创世拍卖分配模型：图1-1）

（2）资产交易手续费：游戏内用户间资产交易时收取的手续费。比如分成模型中地块交易时收取的手续费，后期人物形象、道具等资产的交易也会产生相应的手续费。这些手续费在扣除推荐奖励之后，剩余部分均会流向系统收入。

（3）税收。

（4）其他收入：如使徒生育费等。

【注：税收和其他收入不断完善中，后期补充说明】

![](https://imgland.oss-cn-hangzhou.aliyuncs.com/photo/2018/15e1de9a-4f10-4f5d-84f7-0ed3078c1f53.jpg?x-oss-process=image/resize,w_1920)

（图1-1）

## 系统收入分配

【注：系统收入先扣除推荐奖励，余额将进入系统收入池，并按照比例进行分配】

（1）推荐奖励（已扣除，列举只为完整性）：每一个星球用户在不同资产的交易中都有自己的推荐链接，其他星球用户通过该推荐链接进入系统，在完成有手续费的交易后，系统会进行相应的推荐奖励。

（2）交易奖励池（占10%）：进化星球 - 交易抽奖：[https://forum.evolution.land/posts/27](https://forum.evolution.land/posts/27)

（3）内容贡献激励（占30%）：向游戏内经济贡献前x名发放，暂时锁在合约内，待游戏上线后有内容贡献后进行分账。

（4）氪石持有者（占30%）：向氪石持有人发放。

（5）运营和开发（占30%）：其中部分进行团队激励，部分留存作为开发基金，由团队自行分配。

## 系统收入来源与分配模型图

![](https://imgland.oss-cn-hangzhou.aliyuncs.com/photo/2018/4bf48120-c8e7-4b3a-a414-caaf3253e50f.jpg?x-oss-process=image/resize,w_1920)


# Revenue Model

Just like any traditional game, Evolution Land generates revenue from players' activities.

## Revenue Sources

This revenue comes through these channels:

* **New Land Auction** When new Land is put into the market, the auction income contributes to the revenue.
* **New Apostle sales** Limited first-generation Apostle were sold at a fixed price; these contribute to the revenue pool.
* **Second Market Trade Tax** When a user lists their property Land, Apostle, or other props on the in-game marketplace, a small fee is charged if the trade is successful.
* **Apostle Birth Fee** When breeding a new Apostle, a small birth fee is charged.
* **Magic Potion Sales** Magic Potion sales income contributes to the revenue pool.
* **Inter-continent Import Tax** When some goods, resources, or Apostles are transferred from other continents, inter-continent import tax is charged.
* **Business Tax** Any other commercial business activities are charged for a small tax.

The Parliament determines all the tax rates and fees listed above through the Governance process. Altogether, they build up the revenue to be distributed.

## Revenue Distribution

When game revenue is generated, it's distributed automatically and simultaneously within the same transaction. The processing logic for each transaction is as follows:

1. Send expense to the designated recipient
2. Invoke on-chain logic to process the transaction \(such as transfer ownership of an asset\)
3. Pay referral reward to the referrer if there's any
4. Split revenue \(tax/fee\) and send to destination contract for further distribution.

System revenue will be split and sent to four special-purpose pools for further distribution. Their allocation is as follows:

* Trading Reward Pool \(Lottery Pool\): 10%
* Content Contribution Incentive Pool: 30%
* Governors Pool: 30%
* Operations & Dev Pool: 30%

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

