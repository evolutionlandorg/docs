# Auction Related

## **Auction rules**

In Evolution Land, the seller can set a pair of starting price and ending price and the price change duration. According to the price change period, the auction price will change from the starting price to the ending price linearly.

## What is a Dutch auction?

A Dutch auction is a reverse auction structure in which an asking price \(higher\), a reserve price and an auction time are predetermined. The auction will start from the asking price to the reserve price over time, with the price reducing linearly, until some participant accepts the price without other bids in 30 minutes. Each bid is 110% of the current price.

The original Land and original apostles are auctioned in this way. The asking price is determined based on the average price of the 20 trading prices prior to the auction, and the reserve price is 1⁄5 of the asking price. Auction time for second stage bidding is slightly different, with 30 minutes for Land auction and 10 minutes for Apostle.

Users can sell their own Lands, apostles or other assets through the in-game market in this way. The rules are flexible for users. For example, if the reserve price is higher than the asking price, it would become a traditional forward auction; or users may set an asking price the same with the reserve price, that is to sell at a fixed price.

## Can I sell the Land \(the Apostle\)?

Yes. It can be sold through the in-game trading market.

## How long does it take for the ands and the apostles to be released for auction?

One piece of Land is released for auction every two hours on Atlantis, while that on Byzantine is released every 20 minutes. An original apostle is released every 20 minutes for auction.

## Why are some prices of Apostle/Land falling, and some prices rising?

\(1\) The auction uses a complete Dutch auction, where the price decreases with a certain time interval, according to a predetermined price reduction ladder, from high to low, and when other players participate in the bid, the price index rises.

\(2\) The apostle by the player can be customized the start/end price, that is, you can choose the price increase/decrease/fixed to sell your own plot.

## Why Show \[outbid\]? What should I do?

If other player places a bid higher than yours, your bid is outbid. You can bid again if you still want to win the auction or simple give up.

## Why do transactions often fail when in auction?

There may be a "transaction fail" when participating in a land auction. There're many possible reasons:

* You may provide less gas limit that the transaction requires to complete. You should not tune down the gas limit estimated by your wallet or tune up a little bit to be sure.
* The asset you are trying to purchase is not for sale \(sell pulled it off, someone else bought it, or placed a bid result your bid amount unqualified\) when your transaction is processed, hence failed.

Taking the Land auction as an example, you make a bid 10% more than the current price of 100. The network may confirm your transaction for a longer time, depending on the payment fee. Before your transaction is confirmed, another user may pay a higher gas fee to make a bid, and his transaction is included in the network before your transaction. Your bid might be lower when your transaction is being processed than the latest offer, so your bid is rejected as an invalid bid.

It could also be some un-discovered bug, let us [know](https://github.com/evolutionlandorg/docs/tree/6311cb781553ee3b79984ab2d0df7865d51a103e/overview/feedback-and-support/README.md)

## Show \[Congratulations! Transaction successfully\], but I can't find my Apostle/Land?

Networks sometimes have short delays, please wait and refresh.

