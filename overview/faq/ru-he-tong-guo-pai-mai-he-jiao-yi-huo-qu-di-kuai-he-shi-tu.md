# 如何通过拍卖和交易获取地块和使徒？

## **土地和使徒多久放一块出来拍卖？**

以太坊大陆上土地每2小时释放一块开始拍卖，波场大陆上每20分钟释放一块。使徒则是每20分钟开拍一个初代使徒。

## **什么是荷兰式拍卖？**

荷兰式拍卖是一种反向拍卖方式，确定三个参数，一个起拍价（较高），一个最低价以及拍卖进行时间。拍卖将从起拍价开始，随着时间的推移向最低价靠拢，不断线性降价。一旦有用户出价成功，如果30分钟内没有其他用户竞价。用户则获得该标的。每次竞价为当前价格的110%。

初始土地、初代使徒都是以这种方式进行，起拍价根据前20个成交价的平均价格确定，最低价为起拍价的⅕。第二阶段竞价成功时间略有不同，土地拍卖为30分钟，使徒为10分钟。

用户也可以将自己拥有的土地、使徒或者其他资产以这种方式通过游戏内置市场卖出，用户拥有更多灵活性，比如可以设置结束价高于起拍价，则变成传统的正向拍卖；也可以设置起拍价和结束价一致，则可以以固定价卖出。

## **我可以把土地（使徒）卖出去么？**

可以。通过游戏内置交易市场可以卖出。

## **为什么拍卖时交易经常失败？**

很多时候是由于网络延迟，交易需要时间确认造成的。比如说土地拍卖，当前价为100，你进行出价110。你的交易根据支付的手续费不同，被网络确认的时间可能较长。在你的交易被确认前，其他用户可能支付更高的手续费发出竞价，而他的交易先于你的交易被网络收录。那么当你的交易在被处理的时候，合约中可接受的价格已经变成了121（因为其他用户110的竞价已被接受，当前价格再次上浮10%变成121），所以你的竞价变成无效出价而被拒绝。

如何避免呢？一是可以参拍竞争较少的地块；另一个方式是通过拍卖界面中的加价操作。即当前价格为100时，你直接加2挡甚至3挡，出价121设置133.1。这样即使其他人先于你成交，但是你的出价由于有1到2档溢价，也可以被接受。当然如果没有人先于你成交，那么你支付的超出当前价格的溢价部分将退回你的账户，无需担心浪费。

\*\*\*\*
