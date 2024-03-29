---
description: Contribute and help the world evolve
---

# Developers

Evolution Land is owned by players and created by developers. Any developer, no matter you are a designer, front-end engineer, or smart contract developer, you can find contribute and help the world evolve. The [incentive](https://github.com/evolutionlandorg/docs/tree/81207c410a2c2ae52f984b5c643a2a82d18ca54b/overview/referral-program/README.md#smart-contract-based-referral) is built into the base smart contracts.

## UI

### Front-end Interface

Evolution Land's game logic is stored on the blockchain. Any web3 supported front-end can interact with the smart contracts without prior permission. Right now, players can access the game through v1 and v2 interfaces. They are perfect samples to show how you can design and develop various UIs while interacting with the same backend. We will open-source v1 front-end soon. It's a minimal design interface that serves as a scaffold project upon which you can develop.

### Architecture Designers

Evolution Land plans to release new gameplays of constructing buildings that players can construct or purchase to be deployed on the Land they own. A building market will be in place. Designers can model and design architectures to sell on the market.

## SDK

A client-side javascript SDK library is already open sourced on the github.

```javascript
const evo = new Evolution();

evo.createWeb3js({provider: web3.currentProvider})
evo.createTronweb({
  fullHost: 'https://api.shasta.trongrid.io',
})

// evo.createEvolutionLand('ethereum', 'ropsten')
evo.createEvolutionLand('tron', 'shasta')

evo.ethEvoland.buyRing(10000)
```

* Read the [docs](https://evolutionland.js.org)
* Visit the code [repo](https://github.com/evolutionlandorg/js-sdk)
* Visit the [EVO-Tools](evo-tools.md)

## Smart-contract Interaction

Assets and game logics are all on-chain. You can:

* Propose to introduce your asset to be used in Evolution Land
* Use Evolution Land assets in your application
* Invoke game plays contract from your application

Check out smart-contract source code at the [repos](https://github.com/evolutionlandorg).

### Contract addresses are the mainnet and testnet:

**Ethereum Mainnet**

```text
TOKEN_DEX_BRIDGE: "0xab1Cb6a9467b77B9451c1c61140FB34494baFFDD",
TOKEN_RING: "0x9469d013805bffb7d3debe5e7839237e535ec483",
TOKEN_WITHDRAW: "0xf45e406067798d2df7913704edcc2ac8d07f3d9e", // takeback
TOKEN_WITHDRAW_KTON: "0xE073698faEDB15ef7c64131e51704d52C9A9f55F", // takeback
TOKEN_AUCTION: "0xf4f5da5d5141f73998bb9c2ef548bf47104e9d8f",
TOKEN_LAND: "0x14a4123da9ad21b2215dc0ab6984ec1e89842c6d",
TOKEN_LUCKYBAG: "0xe19866986976e84b2c2691169c9f9b1baa433893",
TOKEN_REDPACKAGE: "0xb5e00e37ded86ec82992dd1c842d5e23aeee2329",
TOKEN_BANCOR: "0x74744f8f676feba599e6668a8513b97bf5306e77", // bancorExchange
TOKEN_BANK: "0x649fdf6ee483a96e020b889571e93700fbd82d88",
TOKEN_KTON: "0x9f284e1337a815fe77d2ff4ae46544645b20c5ff",
TOKEN_LOTTERY: "0xa4db07460c7473ef3aaf2c26da46b00a4d986d72", // PointsRewardPool
TOKEN_USER_POINTS: "0x335e07b1465d1158b8300c675ee8903c65981266", //UserPoints
TOKEN_ROLES_UPDATER: "0xab5e712d3f90d68b2356b613a7af6012bbd301ca", // rolesUpdater
TOKEN_GEN0_APOSTLE: "0xf44c58e703070d4ce7b2440533f29f62713ee071", //Gen0Apostle
TOKEN_APOSTLE_TAKE_BACK: "0x2f67ee58945a3d13801e6f016aa84abdce6d72a7", //TakeBackNFT
TOKEN_APOSTLE_CLOCK_AUCTION: "0xa665271c365f9d9a149866574a5b047dd9e3d31b", //ApostleClockAuction
TOKEN_APOSTLE_SIRING_AUCTION: "0xe0a0489d93aeb831a04e8b631ebd9827a4db4a58", //SiringClockAuction
TOKEN_APOSTLE_BASE: "0x7469966be391e8fe5e85ab972819560c7c3d6e4c", //ApostleBase
TOKEN_LAND_RESOURCE: "0xa9203f3303126243c8d181006ab03b2474e3c084", //landResource
TOKEN_TOKEN_USE: "0xa70abeaca1d6bba0f511758a0d66b7f59fd3f166", //token use

TOKEN_KITTY_CORE: "0x06012c8cf97bead5deae237070f9587f8e7a266d", // KittyCore
TOKEN_PET_BASE: "0xb0c85c099094e73ffc1df23c8309a8b14c64420a", // PetBaseProxy

TOKEN_ELEMENT_GOLD: "0x358dba28848cca268ba8a76b65e5b3ef9ef92238",
TOKEN_ELEMENT_WOOD: "0xd4b784ae5c12153d11ca55853d832d2a2d514a08",
TOKEN_ELEMENT_WATER: "0x19e22a73a046f19ecb51a46ace4ca7a4bb7c20c6",
TOKEN_ELEMENT_FIRE: "0x8469a695d70033ecd170c82be1253842162aa77e",
TOKEN_ELEMENT_SOIL: "0x1320994fa466e19f17b143995999c7275eae50e1",

GENESISHOLDER: "0x36f061bc3314793c5637fb79421294c061ead108",
AUCTIONHOLDER: "0xba332453b171aac634b3bed88bfef28770acf7e3",
UNISWAP_EXCHANGE: "0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D",

FURNACE_TREASURE: "0xc7D7E731d6bf9182701096adCd5bba3bb0CF76fc",
FURNACE_TAKEBACK: "0x8d7af9d2310016712b8f269df266f957cb12a27b",
```

**Ethereum Ropston Testnet**

```text
TOKEN_DEX_BRIDGE: "0xD42AA035Ea64feBAE5d2b3fd08Dc7bD89874C6dc", // DexBridge swap
TOKEN_RING: "0xb52FBE2B925ab79a821b261C82c5Ba0814AAA5e0",
TOKEN_WITHDRAW: "0x115493f616F3D213913F843fB5594C4d004b4782", // takeback
TOKEN_WITHDRAW_KTON: "0xb12C4fdDb1f4fC9C4C6592DbC705AC16509a70D5", // takeback
TOKEN_AUCTION: "0x9a6144237be8B5a6dc793E8848B6AeFc99bd2256", // ClockAuction
TOKEN_LAND: "0x5eA9ea8E80230E514b5e023e8d956550a22D02c6", //objectOwnership
TOKEN_LUCKYBAG: "0x87a1f4d7f8dABa01315bcFE0873cE250b0cF47fB",
TOKEN_REDPACKAGE: "0x4088Db66B8acAA673333b2Ef32648137A95c4476",
TOKEN_BANCOR: "", // BancorExchange
TOKEN_BANK: "0x6EF538314829EfA8386Fc43386cB13B4e0A67D1e",
TOKEN_KTON: "0x1994100c58753793D52c6f457f189aa3ce9cEe94",
TOKEN_LOTTERY: "0xc7eFAaa1b57EB6d5A1855dAf1a37f27cBEa5b5A5", // PointsRewardPool
TOKEN_USER_POINTS: "0x42a1D26d764a4ec858aB9e955B70e55FE409C749", //UserPoints
TOKEN_ROLES_UPDATER: "0xdB131373218b9E3bAAAC807C540F4EAeEb2274b3", // rolesUpdater

TOKEN_GEN0_APOSTLE: "0x30F7e8C1e53D1201AfBC99e32272e98fc168E4A6", //Gen0Apostle
TOKEN_APOSTLE_TAKE_BACK: "", //TakeBackNFT
TOKEN_APOSTLE_CLOCK_AUCTION: "0xE862c7551b4361ee7DA08806affdB09850E8A284", //ApostleClockAuction
TOKEN_APOSTLE_SIRING_AUCTION: "0xfBe870C1084E6e5AE51b89765F70f1673bb9F6Ab", //SiringClockAuction
TOKEN_APOSTLE_BASE: "0x2E1dd56F118505a9D420Bf50D3bbAd80B3Aa2Ef3", //ApostleBase
TOKEN_LAND_RESOURCE: "0xD22065369994568096FB841e024462F4d7F5f2f9", //landResource
TOKEN_TOKEN_USE: "0xfD9512e7c8d5D481661032768bBBdEA683D78865", //token use

TOKEN_KITTY_CORE: "0x56eeea3d9fc769cd8229d10ed40b7b1c897bc750", // KittyCore
TOKEN_PET_BASE: "0x100CFd21Fa502c706Ca33fCB544b626B20300b8E", // PetBaseProxy

TOKEN_ELEMENT_GOLD: "0xB6A07A36FA73758Ce9D58a2C6a8Da74CECCa438d",
TOKEN_ELEMENT_WOOD: "0xda4d84c604977220D58ade0CF0D915b1a4099E35",
TOKEN_ELEMENT_WATER: "0x40766Ce658Ae73E29242A3EDd75cF83F84c7120e",
TOKEN_ELEMENT_FIRE: "0xC5C0f115C05dd10625A5d4d0fAf284100AD56E68",
TOKEN_ELEMENT_SOIL: "0x5102d99fa797a12f611744cDAE69FF7A5F34b38D",

GENESISHOLDER: "0xfE3EE13c28830F7F91Bbb62305D3B616e49998EC",
UNISWAP_EXCHANGE: "0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D",
AUCTIONHOLDER: "",

FURNACE_TREASURE: "0xF72361096f11d7E4e45046d7a83726b1A9107D5E",
FURNACE_TAKEBACK: "0xA10D0C6e04845A5e998d1936249A30563c553417",
```

**Tron Mainnet**

```text
TOKEN_DEX_BRIDGE: "4165798DC18E6F8382FE96EC797105FC270FD4F466",
TOKEN_RING: "416e0d26adf5323f5b82d5714354dc3c6870adee7c",
TOKEN_WITHDRAW: "418507305db28a11038a493821b84117cf9a9f08fe", // takeback
TOKEN_WITHDRAW_KTON: "412594D59E47C9CDD2AE0C5BBFD64ACC2D6F67737D", // takeback
TOKEN_AUCTION: "4176cb443f8280d28d6f84531a92c1330dd3203fdb", // ClockAuction
TOKEN_LAND: "4100dfe66a889aa22228e7b17236ceb7e6d3b286b2", // objectOwnership
TOKEN_LUCKYBAG: "",
TOKEN_REDPACKAGE: "",
TOKEN_BANCOR: "413f702ea3d0c08a9e7be7b433c66f8e5f13aa3879", // bancorExchange
TOKEN_BANK: "41c04e43cb87b432329a32aa99605982590b0191ec",
TOKEN_KTON: "41dc3e713213d0403f82addbfb66b8574b86851c19",
TOKEN_LOTTERY: "41d067d15418edcd7ba2da26589bdc2bf961e640dc", // PointsRewardPool
TOKEN_USER_POINTS: "41b580669bb5b33a97267861d1176fe412a800f791", //UserPoints
TOKEN_ROLES_UPDATER: "", // rolesUpdater

TOKEN_GEN0_APOSTLE: "41edc57d25fb6a9432313013075e6775b75b381f6a", //Gen0Apostle
TOKEN_APOSTLE_CLOCK_AUCTION: "41d80524bd98439612184c481cc6a6a3608491551f", //ApostleClockAuction
TOKEN_APOSTLE_SIRING_AUCTION: "41f80ba670704296752b1a3c8f17ff17e24bc7234e", //SiringClockAuction
TOKEN_APOSTLE_BASE: "416af8a99d0539ac273ef92b13b0edefedfcf51bc8", //ApostleBase
TOKEN_LAND_RESOURCE: "41f738cb701d94a35352621de20bc48ba598ae142e", //landResource
TOKEN_TOKEN_USE: "41ca9d92d82e7a4054f9dee7e8c6b4451cfff3c87d", //token use

TOKEN_ELEMENT_GOLD: "4117ff7d2060e2f91b6cbc0b4b335c1d37cd8861f5",
TOKEN_ELEMENT_WOOD: "414c0a6059688ff86c4bfd88312bceb4e0e050b078",
TOKEN_ELEMENT_WATER: "4186f29de0e912e4ffdabc6de1b9666fa8d63b66a7",
TOKEN_ELEMENT_FIRE: "41ba6c9bf5cd0b9209a4ac0c82b53f6cbe4fff5623",
TOKEN_ELEMENT_SOIL: "41a0002398fcf33c6fa50206751f70f2f8f553fe58",

GENESISHOLDER: "41fd9ac1a0b242ba7116399174dd7ce5ff462e6c0f",
AUCTIONHOLDER: "",
JUSTSWAP_EXCHANGE: "41394CFB02DA445B95CA61DB8A993AF63E2AAE907A",
```

**Tron Testnet**

```text
TOKEN_DEX_BRIDGE: "41061CC649E56EB386949A789034B9EF61FC6B11D0", // DexBridge swap
TOKEN_RING: "415e465875334b3960e6fc3f6e018ef70d66dedf15",
TOKEN_WITHDRAW: "41B139BBA1233BB4F2AE2F019CFDD9C1DD15C6EA37", // takeback
TOKEN_WITHDRAW_KTON: "4196947D2BF03D0A54ADFCF287D89E3489334F7274", // takeback
TOKEN_AUCTION: "41a77b64c3751e29ed15c7ca936a219609b7974955", // ClockAuction
TOKEN_LAND: "410eb26cd69aba0f5f3b866747b014313a5ddef076", //objectOwnership
TOKEN_LUCKYBAG: "41F2BB94F74ED2ED955DF22C20215F1CD28D4B0999",
TOKEN_REDPACKAGE: "41B17861AD5FC8BE9E2BD146E403AEF4415FDB8851",
TOKEN_BANCOR: "4108b5e5c13baf1cd59030f3c6fb8fb2b56dc8a8e4", // BancorExchange
TOKEN_BANK: "4173cf78be000e13783422f8595f9a1778b8da4615", // GringottsBank
TOKEN_KTON: "41fe4170545a81503a0a328a368f9e0d7c1f6a204c",
TOKEN_LOTTERY: "41afdfc017691fd4665f4b70ccd5d297acb880dba1", // PointsRewardPool
TOKEN_USER_POINTS: "413bf3f7b094ef56acdf5e430756e43694ac83a6bb", //UserPoints
TOKEN_ROLES_UPDATER: "41a5538a8697eeb4e891e2c2ae97366cfde9386531", // rolesUpdater

TOKEN_GEN0_APOSTLE: "41a9f1dc23a938d27820496795ca241d9024d0f296", //Gen0Apostle
TOKEN_APOSTLE_TAKE_BACK: "", //TakeBackNFT
TOKEN_APOSTLE_CLOCK_AUCTION:
"41441ceeff97d96c1d50173503c571915b2dc2b45f", //ApostleClockAuction
TOKEN_APOSTLE_SIRING_AUCTION:
"419e7827155234ad4bd8102532de8c1dc74eb3aadc", //SiringClockAuction
TOKEN_APOSTLE_BASE: "41238fe04997359169aa65fe5b4631db220dfe540e", //ApostleBase
TOKEN_LAND_RESOURCE: "410cce145a83f344e290613028ea3123eb473e69cb", //landResource
TOKEN_TOKEN_USE: "4184793cf50f45330256265e7b14af096438057670", //token use

TOKEN_ELEMENT_GOLD: "41ec0ff3527ddba81f0cf5101fb31dc42b808ca1ab", //金
TOKEN_ELEMENT_WOOD: "41da966f8718feea81a500ab193838e2be208bf987", //木
TOKEN_ELEMENT_WATER: "41e9eaec1529b2030e3704cb41f08fc4e15117add0", //水
TOKEN_ELEMENT_FIRE: "41f9c329dbb1bc5f84ab731a7f0a64cd226c0cb1ab", //火
TOKEN_ELEMENT_SOIL: "41d23d40f91f9dcd27218307351be1173ed43943c9", //土

GENESISHOLDER: "4196c53cc5b77b6ef212c3db360dd3d4d33516787a",
AUCTIONHOLDER: "",
```

