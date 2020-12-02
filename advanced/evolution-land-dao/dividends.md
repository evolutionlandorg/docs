# Dividends

To compensate governors who sacrifice their [KTON](../../getting-started/tokens/kton.md) liquidity and participation in the governance process. Revenues in the Governor Pool is paid to these governors based on their staked KTON proportionally against the overall pool.

Dividends are paid through the state channel on a per transaction basis. That means every time a spending transaction takes place. Dividends are cleared and sent to the governor's credits in the state channel on-chain. Governors will need to actively send a claim transaction to the smart contract to collect their dividends \(RING\) to their wallet address.

The dividends are not distributed as regular transactions because each spending transaction might distribute to thousands of beneficiaries with micro amounts. The gas cost will be significant compared to the amount sent. However, using the state channel, dividends can be accumulated and collected once.

From the DeFi perspective, this governance model looks like a DeFi yield farming pool. You stake your KTON in the pool. In return, you receive RING tokens as rewards. The difference is in a regular pool, the reward you mint is the project's base token released at speed set by a fixed algorithm, whose value is driven mostly by speculation; While here, the reward you receive is the revenue from the game. Your financial reward is actually linked with the success of the business.

