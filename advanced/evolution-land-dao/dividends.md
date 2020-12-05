# 分红

## **拍地分成**

（1）每次出价都是上一次出价的 1.1 倍，不包含第一次出价。

（2）被超越的竞价用户取回原竞价款。

（3）两次出价差价部分的 4% 作为官方收取的手续费。

（4）差价部分扣除手续费之后会平分给地主和上一个玩家。

（5）没有推荐人的情况下，手续费直接流向系统收入。

（6）有推荐人的情况下，推荐人的奖励是手续费的20%，剩余 80% 流向系统收入。

## **详细分析**

前提条件： n &gt; 1

玩家 M，第 n 次出价： a

玩家 M+1，第 n+1 次出价： b

两次出价差价：b - a

（1）出价规则：b = a \* 1.1【注：第 n+1 次出价是第 n 次出价的 1.1 倍】

（2）手续费：fee = \( b-a \) \* 4%【注：两次出价差价部分的 4%】

（3）地主得到：\( b - a \) \* 96% \* ½【注：差价部分扣除手续费之后的一半给地主】

（4）玩家 M 得到：a + \[ \( b - a \) \* 96% \* ½ \]【注：拿回失败的竞标款 a 和差价部分扣除手续费之后的一半】

（5）推荐人奖励：手续费 \* 20%【注：推荐人的奖励金额为手续费的 20%】

（6）在没有推荐人的情况下，手续费直接流向系统收入。

![](https://imgland.oss-cn-hangzhou.aliyuncs.com/photo/2018/78fdda1d-c8e1-4f91-baba-08a01c061485.jpg?x-oss-process=image/resize,w_1920)

![](https://imgland.oss-cn-hangzhou.aliyuncs.com/photo/2018/493cf263-dcb2-4791-a974-9f0fbd3800c3.jpg?x-oss-process=image/resize,w_1920)

## **举例说明**

![](../../.gitbook/assets/image%20%289%29.png)

To compensate governors who sacrifice their [KTON](../../getting-started/tokens/kton.md) liquidity and participation in the governance process. Revenues in the Governor Pool is paid to these governors based on their staked KTON proportionally against the overall pool.

Dividends are paid through the state channel on a per transaction basis. That means every time a spending transaction takes place. Dividends are cleared and sent to the governor's credits in the state channel on-chain. Governors will need to actively send a claim transaction to the smart contract to collect their dividends \(RING\) to their wallet address.

The dividends are not distributed as regular transactions because each spending transaction might distribute to thousands of beneficiaries with micro amounts. The gas cost will be significant compared to the amount sent. However, using the state channel, dividends can be accumulated and collected once.

From the DeFi perspective, this governance model looks like a DeFi yield farming pool. You stake your KTON in the pool. In return, you receive RING tokens as rewards. The difference is in a regular pool, the reward you mint is the project's base token released at speed set by a fixed algorithm, whose value is driven mostly by speculation; While here, the reward you receive is the revenue from the game. Your financial reward is actually linked with the success of the business.

