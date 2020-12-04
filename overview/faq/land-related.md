# Land Related

## What is the Land Auction rules

In Evolution Land, the seller can set a pair of starting price and ending price and the price change duration. According to the price change period, the auction price will change from the starting price to the ending price linearly. 

{% page-ref page="/advanced/trading/nft-market#auction-system" %}

## Can the map be rotated?

In [v1](https://v1.evolution.land) interface, the continent map can be rotated on Mac and Windows System.   

- On the Mac system, you can hold down the "command" and drag the land with the mouse to rotate the land to adjust the angle of view.
- On windows system, you can hold down "control" and drag the land with the mouse to rotate the land to adjust the angle of view.

In [v2](https://evolution.land) interface, the continent map can no longer be rotated.

## **Why are some prices of lands falling, and some prices rising?**

\(1\) The auction uses a complete Dutch auction, where the price decreases with a certain time interval, according to a predetermined price reduction ladder, from high to low, and when other players participate in the bid, the price index rises.

\(2\) The land sold by the player can be customized the start/end price, that is, you can choose the price increase/decrease/fixed to sell your own plot.

## Why Show \[outbid\]? What should I do?

If other player places a bid higher than yours, your bid is outbid.  You can bid again if you still want to win the auction or simple give up.

## Why is \[transaction failed\]?

There may be a "transaction fail" when participating in a land auction. There're many possible reasons:

- You may provide less gas limit that the transaction requires to complete. You should not tune down the gas limit estimated by your wallet or tune up a little bit to be sure.
- The asset you are trying to purchase is not for sale (sell pulled it off, someone else bought it, or placed a bid result your bid amount unqualified) when your transaction is processed, hence failed. 

- Or it could be some un-discovered bug, let us [know](/overview/feedback-and-support)

## Why stopped at \[waiting for confirmation\]?

There may be a "waiting for confirmation" when participating in the Land's auction/claim. The reason may be that the Gas fee you provide is low, and the transaction is waiting for miners to process. The player can choose to wait, increase the gas price, or cancel the transaction according to the transaction status at this time.

## Show \[Congratulations! Transaction successfully\], but I can't find my land?

Networks sometimes have short delays, please wait and refresh page.

## After the land is sold, will the picture on it still exist?

The auction center will temporarily keep the Land during the sale. At this time, the picture on the Land will be temporarily removed. When the player or the auction buys the Land is cancel, the picture will be displayed again.

## When the land is sold, do the apostles still on the land be sold together?

The Land sale does not include the Apostles working on it.  

If you are the Land seller, you still can manage those Apostles to make them stop working and come back.  But you can't deploy them on the Land (has a new owner now) again.  The Apostles mined resource will go to the new land owner.

If you are the Land buyer, those Apostles will keep mining.  The resource earned go to your wallet.

## Who is EVE? Why are there so many land?

[EVE](/) is an NPC.  She represents the group of smart contracts.

In the story of the Evolution Land, to continue human civilization, all countries have joined together to successfully cultivate the first truly self-conscious intelligent body A.H.S. (Artificial Homo sapiens) named Eve (Eve). 

EVE took the last hope of life on earth to the depths of the universe. After years of exploration, he discovered a planet suitable for the earth's life: the Evolution Land.

EVE creates lands, and she is facilitating the Initial Land Offering and other asset auctions and trading.

