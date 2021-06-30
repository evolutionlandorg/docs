# Land

[![Land \#A1345](../../.gitbook/assets/land-1.png)](https://www.evolution.land/land/1?gx=26&gy=42) [![Land \#A311](../../.gitbook/assets/land-2.png)](https://www.evolution.land/land/1?gx=50&gy=10) [![Land \#A1969](../../.gitbook/assets/land-3.png)](https://www.evolution.land/land/1?gx=11&gy=37) [![Land \#A1302](../../.gitbook/assets/land-4.png)](https://www.evolution.land/land/1?gx=11&gy=13) [![Land \#B538](../../.gitbook/assets/land-5.png)](https://www.evolution.land/land/2?gx=5&gy=33) [![Land \#B351](../../.gitbook/assets/land-6.png)](https://www.evolution.land/land/2?gx=44&gy=37)

The size of each land is 100m x 100m, and there is no limit on the height \(assuming it is also 100m\). Then each land is a three-dimensional Euclidean Space. In this land space, the player can construct buildings. The building is made up of a number of basic units called “square blocks”, each of which is 1m x 1m. Each land can only be placed in a building that does not exceed its size. Multiple buildings can be placed on the top of the block, as long as there is no overlapping area between any two of them, and can be separated by smooth movement.

LAND has five [resource](resource/) reserves that can be mined indicated as a number called Max Resource Attenuation Rate\(MRAR\). It means at full speed, the max amount of resources can be mined daily. The resource decays daily at a rate of about 1/10,000 every day.

![Land Resource Reserves](../../.gitbook/assets/land-resource.png)

In the Land diagram above, `90,-7` are the coordinates of this land, `B769` stands for continent B \(Byzantine\), `land id` is `769`. On the right side, fives resource MRAR is listed. They are [GOLD](resource/), [WOOD](resource/), [HHO](resource/), [FIRE](resource/), [SIOO](resource/). The higher the reserve, the easier you can mine, and the higher the ceiling you might reach.

## Ownership

The Land is an NFT \(non-fungible token, ERC721\). When you purchased a Land, the Land NFT token is transferred to your wallet address from the marketplace \(a smart-contract auction, for example\). From now on, you are the sole owner of this Land. You can transfer it to another player as a gift or a third-party exchange. All these actions need to be initiated from your wallet with your permission.

## Mining Pool

From the perspective of a DeFi user, each Land is a mining pool with a unique reserve. You work on it by deploying Apostles, Equipment to mine as many resources from it. The reward you get is resources. Apart from trading those resources, they are useful and demanded by other game players who need them to forge pieces of equipment or construct buildings.

## Switch Land Views

At the left bottom of the map, there's an `question mark` icon that allows you to switch the land view.

### What does the color represent?

1. Blue\(reservation\): The land officially reserve
2. Dark blue\(no owner\): The land unsold and waiting for an official open auction
3. Red\(Taken\): The land bought by another player; these lands have not entered the auction yet.

Orange\(Mine\): The land that you successfully bought and has claimed.

1. Purple（Mystical）: The land's resource reserves are hidden and will not be made public until the player has claimed. The player may purchase the land with the elemental output comparable to the reserved land at the average land price.
2. Dark green\(On sale\): The second-hand land sold by the owner of the land, you can participate in the auction.
3. Light green\(First sale\): The land sold officially. You can participate in the auction. By buying these lands, you will get more points to join the lottery.
4. Yellow\(Scenery\): Lands composed of roads, lakes, plants, buildings, etc. They cannot be bought or sold.

![](../../.gitbook/assets/resource-legend.png)

### What's a land named Reserved/Mystical?

**Reserved:** The lands in the central part of the mainland will be reserved later for commercial cooperation or open auctions that need to be purchased using KTON.

**Mystical:** The land resources are hidden and will not be made public until the player has claimed them. The player may purchase the land with the elemental output comparable to the reserved land at the average land price.

### How to distinguish between official land and second-hand land?

1. The simplest way to distinguish is based on color recognition. Green with a logo of Evolution Land is the official Land;
2. Some naughty players will upload the Evolution Land logo to pretend the official Land. In this case, you can distinguish between the official Land and the second-hand Land by this way: click on the Land and view the details of the Land. If you see that the Landowner is EVE and the Land has no transaction records, it is the “True official land.”

## How to buy land?

1. Click on the land you want to buy
2. Bid with [RING](../tokens/ring.md)/\(ETH/TRX\)
3. Confirm transaction \(Metamask/TronLink/Itering ID/imToken/Math Wallet\)
4. If no one continues to bid after 30 minutes of your successful bidding, you will get the land.

PS. After successfully bought, you can view and claim the land in \[My Land\] - \[Unclaimed\].

