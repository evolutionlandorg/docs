# Land

The size of each land is 100m x 100m, and there is no limit on the height (assuming it is also 100m). Then each land is a three-dimensional Euclidean Space. In this land space, the player can construct buildings. The building is made up of a number of basic units called “square blocks”, each of which is 1m x 1m. Each land can only be placed in a building that does not exceed its size. Multiple buildings can be placed on the top of the block, as long as there is no overlapping area between any two of them, and can be separated by smooth movement.

LAND has five resource reserves that can be mined indicated as number called Max Resource Attenuation Rate(MRAR).  It means at full speed, the max amount of resource can be mined daily.   The resource decays daily at a rate about 1/10000 every day.

![Land Resource Reserves](../../.gitbook/assets/land-resource.png)

In the Land diagram above, `90,-7` is the coordinates of this land, `B769` stands for continent B (Byzantine), `land id` is `769`.  On the right side, fives resource MRAR is listed. They are GOLD, WOOD, HHO, FIRE, SIOO.  The higher the reserve, the easier you can mine, and the higher the ceiling you might reach.

## Switch views

At the left bottom of the map, there's an `question mark` icon allow you to switch land view.

### What does the color represent?

1. Blue(reservation): The land officially reserve
2. Dark blue(no owner): The land unsold and waiting for an official open auction
3. Red(Taken): The land bought by another player; these lands have not entered the auction yet.

Orange(Mine): The land that you successfully bought and has claimed.

1. Purple（Mystical）: The land's resource reserves are hidden and will not be made public until the player has claimed. The player may purchase the land with the elemental output comparable to the reserved land at the average land price.
2. Dark green(On sale): The second-hand land sold by the owner of the land, you can participate in the auction.
3. Light green(First sale): The land sold officially. You can participate in the auction. By buying these lands, you will get more points to join the lottery.
4. Yellow(Scenery): Lands composed of roads, lakes, plants, buildings, etc. They cannot be bought or sold.

![](../../.gitbook/assets/image%20%2823%29.png)



### What's land named Reserved/Mystical?

**Reserved:** The lands in the central part of the mainland will be reserved later for commercial cooperation or open auctions that need to be purchased using KTON.

**Mystical:** The land resources are hidden and will not be made public until the player has claimed them. The player may purchase the land with the elemental output comparable to the reserved land at the average land price.

### How to distinguish between official land and second-hand land?

1. The simplest way to distinguish is based on color recognition. Green with a logo of Evolution Land is the official Land;
2. Some naughty players will upload the Evolution Land logo to pretend the official Land. In this case, you can distinguish between the official Land and the second-hand Land by this way: click on the Land and view the details of the Land. If you see that the Landowner is EVE and the Land has no transaction records, it is the “True official land.”

## How to buy a land?

1. Click on the land you want to buy
2. Bid with RING/(ETH/TRX)
3. Confirm transaction (Metamask/TronLink/Itering ID/imToken/Math Wallet)
4. If no one continues to bid after 30 minutes of your successful bidding, you will get the land.

PS. After successfully bought, you can view and claim the land in [My Land] - [Unclaimed].

