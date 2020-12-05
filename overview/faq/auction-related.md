# 关于拍卖

## 竞拍规则

* **拍卖方式**：采用完整荷兰式拍卖，30分钟内如无其他玩家参与拍卖，则地块成交。

  【完整荷兰式拍卖：价格随着一定的时间间隔，按照事先确定的降价阶梯，由高到低递减，当有其他玩家参与出价之后，价格指数上升。】

* **地块释放速度**：前期地块释放速度为1小时一块地，后期释放速度会根据拍卖进程进行调整。

* **地块起拍价格**：前10个地块起始价为 5000 RING，结束价为 1000 RING，期限为6小时。从第11个地块开始，地块起始价为前10个地块最终成交价的平均价，如果前10块地有未成交的，取地块的当前价格。

* **加价模式**：第一次出价为地块当前价格。从第二次出价开始，每次出价为上次出价价格的110%。

## 什么是荷兰式拍卖？

荷兰式拍卖是一种反向拍卖方式，确定三个参数，一个起拍价（较高），一个最低价以及拍卖进行时间。拍卖将从起拍价开始，随着时间的推移向最低价靠拢，不断线性降价。一旦有用户出价成功，如果30分钟内没有其他用户竞价。用户则获得该标的。每次竞价为当前价格的110%。

初始土地、初代使徒都是以这种方式进行，起拍价根据前20个成交价的平均价格确定，最低价为起拍价的⅕。第二阶段竞价成功时间略有不同，土地拍卖为30分钟，使徒为10分钟。

用户也可以将自己拥有的土地、使徒或者其他资产以这种方式通过游戏内置市场卖出，用户拥有更多灵活性，比如可以设置结束价高于起拍价，则变成传统的正向拍卖；也可以设置起拍价和结束价一致，则可以以固定价卖出。

## 我可以把土地（使徒）卖出去么？

可以。通过游戏内置交易市场可以卖出。

## 土地和使徒多久放一块出来拍卖？

首次拍卖时，以太坊大陆上土地每2小时释放一块开始拍卖，波场大陆上每20分钟释放一块。使徒则是每20分钟开拍一个初代使徒。目前首次拍卖已结束。

## 为什么有的价格在下降，有的价格在上涨？

拍卖使用完整荷兰式拍卖，即价格随着一定的时间间隔，按照事先确定的降价阶梯，由高到低递减，当有其他玩家参与出价之后，价格指数上升；

玩家在出售时可以自定义起始价格和结束价格，即可以选择价格上升/降低/固定来出售自己的地块或使徒。

## 显示【被抢拍了】是怎么回事？我该怎么办？

拍卖采用完整荷兰式拍卖，若玩家A拍下后30分钟内无其他玩家参与拍卖，则地块或使徒成交；

若玩家A拍下后30分钟内有其他玩家再次出价参与拍卖，玩家A将看到该地块显示「被抢拍了」。

此时玩家A可以选择不再出价放弃该地块或者再次出价参与拍卖以获得该资产。

## 为什么会【交易失败】？

There may be a "transaction fail" when participating in a land auction. There're many possible reasons:

* You may provide less gas limit that the transaction requires to complete. You should not tune down the gas limit estimated by your wallet or tune up a little bit to be sure.
* The asset you are trying to purchase is not for sale \(sell pulled it off, someone else bought it, or placed a bid result your bid amount unqualified\) when your transaction is processed, hence failed.

Taking the Land auction as an example, you make a bid 10% more than the current price of 100. The network may confirm your transaction for a longer time, depending on the payment fee. Before your transaction is confirmed, another user may pay a higher gas fee to make a bid, and his transaction is included in the network before your transaction. Your bid might be lower when your transaction is being processed than the latest offer, so your bid is rejected as an invalid bid.

It could also be some un-discovered bug, let us [know](/overview/feedback-and-support.md)

## 显示【交易成功】，但我找不到我的物品？

网络和系统有时可能会有短暂的延时，请等待并刷新查看。

