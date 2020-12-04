# Auction Related

## **Auction rules**

In Evolution Land, the seller can set a pair of starting price and ending price and the price change duration. According to the price change period, the auction price will change from the starting price to the ending price linearly. 

{% page-ref page="/advanced/trading/nft-market.md#auction-system" %}

## What is a Dutch auction?

A Dutch auction is a reverse auction structure in which an asking price \(higher\), a reserve price and an auction time are predetermined. The auction will start from the asking price to the reserve price over time, with the price reducing linearly, until some participant accepts the price without other bids in 30 minutes. Each bid is 110% of the current price.

The original land and original apostles are auctioned in this way. The asking price is determined based on the average price of the 20 trading prices prior to the auction, and the reserve price is 1⁄5 of the asking price. Auction time for second stage bidding is slightly different, with 30 minutes for land auction and 10 minutes for apostle.

Users can sell their own lands, apostles or other assets through the in-game market in this way. The rules are flexible for users. For example, if the reserve price is higher than the asking price, it would become a traditional forward auction; or users may set an asking price the same with the reserve price, that is to sell at a fixed price.

## Can I sell the land \(the apostle\)?

Yes. It can be sold through the in-game trading market.

## How long does it take for the lands and the apostles to be released for auction?

One piece of land is released for auction every two hours on Atlantis, while that on Byzantine is released every 20 minutes. An original apostle is released every 20 minutes for auction.

## Why are some prices of Apostle/Land falling, and some prices rising?

\(1\) The auction uses a complete Dutch auction, where the price decreases with a certain time interval, according to a predetermined price reduction ladder, from high to low, and when other players participate in the bid, the price index rises.

\(2\) The apostle by the player can be customized the start/end price, that is, you can choose the price increase/decrease/fixed to sell your own plot.

## Why Show \[outbid\]? What should I do?

If other player places a bid higher than yours, your bid is outbid.  You can bid again if you still want to win the auction or simple give up.

## Why do transactions often fail when in auction?

Most of time it is because of the network delays, and transactions take time to confirm. Taking land auction as an example, you make a bid 10% more than current price of 100. Your transaction may be confirmed by the network for a longer period of time depending on the payment fee. Before your transaction is confirmed, other user may pay a higher fee to make a bid, and his transaction is included in the network prior to your transaction. When your transaction is being processed, the acceptable price in the contract has become 121 \(since the bid of 110 made by another user have been accepted, the current price has risen by 10% to 121.\), so your bid is rejected as an invalid bid.

How to avoid that? One way is to participate in the auction of lands with less competition; the other is to make the bid through the premium function in the auction interface. In other words, it is to set a premium price of 133.1 for your bid of 121 under current price of 100. In doing so, even if someone closed a deal ahead of you, your bid will be accepted because there is a premium. If there is no such competitor for your bid, the premium you paid will be returned to your account.

## Show \[Congratulations! Transaction successfully\], but I can't find my Apostle/Land?

Networks sometimes have short delays, please wait and refresh.