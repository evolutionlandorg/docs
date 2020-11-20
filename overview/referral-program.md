# 引荐计划

![](https://imgland.oss-cn-hangzhou.aliyuncs.com/photo/2018/a8b9ee44-585c-48ba-b6f9-5125b2825bc2.jpg?x-oss-process=image/resize,w_1920)

## **什么是推荐奖励？**

（1）每个玩家在登陆之后都会有一个自己的拍地专属推荐链接。

![\_\_\_1.png](https://evolutionland.zendesk.com/hc/article_attachments/360095136174/___1.png)![\_\_\_2.png](https://evolutionland.zendesk.com/hc/article_attachments/360095136154/___2.png)

（2）其他玩家通过你的链接进入拍地，并竞价成功，你都能得到一定的奖励。

（3）你得到的奖励数额是官方收取手续费的 20%。

## **奖励分析**

（1）玩家A第一次出价 1000 RING

（2）玩家B通过玩家C分享的链接参与拍地，并成功出价，出价金额 1100 RING

（3）玩家B出价成功之后我们来看下TxHash中Tokens Transfered的信息：

![](https://imgland.oss-cn-hangzhou.aliyuncs.com/photo/2018/628d3489-2e91-4339-a406-394e864cefe0.png?x-oss-process=image/resize,w_1920)

Tokens Transfered中共有5笔交易，由上至下依次是：

交易1、玩家B to 合约：1101 RING

交易2、合约 to 玩家B：1 RING

交易3、合约 to 地块持有者：48 RING

交易4、合约 to 玩家A：1048 RING

交易5、合约 to 玩家C：0.8 RING

![](https://imgland.oss-cn-hangzhou.aliyuncs.com/photo/2018/95c8327e-7c73-4369-9f90-e22372e6dc0f.jpg?x-oss-process=image/resize,w_1920)

关于交易1、交易2两笔交易的解释：

玩家B to 合约给了1101 RING，因为在实际交易中，为了让玩家能够出价成功，系统要求的价格为10分钟之后的价格，多出的部分会退给玩家，就是交易2中合约 to 玩家B的 1 RING。

