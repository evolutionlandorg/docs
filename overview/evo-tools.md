---
description: Evo-contract command tool set
---

# Evo Tools

## Introduction

EVO Tools is a set to interact with EVO contracts. It is developed based on `dapp.tools` and inherits the configuration information of `sethrc`.

## Install

1. Install `Nix`

```
# user must be in sudoers
curl -L https://nixos.org/nix/install | sh

# Run this or login again to use Nix
. "$HOME/.nix-profile/etc/profile.d/nix.sh"
```

&#x20;  2\. Run the script

```
curl https://gist.githubusercontent.com/hujw77/ce3d9ed102de1fa1c9eba7754459333a/raw/5ec0e1a2a249e77e87753f4317f642cdf75283be/install.sh | sh
```

## Config

The default configuration file: `~/.sethrc`

```
#!/usr/bin/env bash
export ETH_FROM=0x4Ffa8667Fe2db498DCb95A322b448eA688Ce430c  #你的evo账户地址
export SETH_CHAIN=crab                                      #网络配置 
export ETH_PASSWORD="/home/user/evo/pass.txt"               #密码文件,可选,如果只查看合约信息可不填写
export ETH_KEYSTORE="/home/user/.ethereum/keystore"         #keystore文件,可选,如果只查看合约信息可不填写
export ETH_RPC_URL="<https://crab-rpc.darwinia.network>"      #可选,自定义rpc-url
```

## Check all EVO-NFTs in your address

```
~ evo obj ls
Count 17
Index Class      Level TokenId
0     ⛰  Land    5     0x2a04000104000101000000000000000400000000000000000000000000000272
1     ⛰  Land    4     0x2a04000104000101000000000000000400000000000000000000000000000273
2     ⛰  Land    5     0x2a04000104000101000000000000000400000000000000000000000000000279
3     ⛏  Drill   0     0x2a04000104000104000000000000000400000000000000000000000000000174
4     ⛏  Drill   2     0x2a04000104000104000000000000000400020000000000000000000000000182
5     ⛏  Drill   2     0x2a04000104000104000000000000000400020000000000000000000000000183
6     ⛏  Drill   2     0x2a0400010400010400000000000000040002000000000000000000000000018b
7     ⛏  Drill   2     0x2a04000104000104000000000000000400020000000000000000000000000185
8     ⛏  Drill   2     0x2a04000104000104000000000000000400020000000000000000000000000186
9     ⛏  Drill   2     0x2a04000104000104000000000000000400020000000000000000000000000187
10    ⛏  Drill   2     0x2a04000104000104000000000000000400020000000000000000000000000188
11    ⛏  Drill   2     0x2a04000104000104000000000000000400020000000000000000000000000189
12    ⛏  Drill   3     0x2a0400010400010400000000000000040003000000000000000000000000018a
13    🔨  Item    0     0x2a0400010400010500000000000000040000000000000000000000000000000f
14    👨  Apostle 1.53  0x2a0400010400010200000000000000040000000000000000000000000000003b
15    👨  Apostle .89   0x2a0400010400010200000000000000040000000000000000000000000000003c
16    👨  Apostle .45   0x2a0400010400010200000000000000040000000000000000000000000000020c
```

Tips: Higher level means greater quality

## Check the land information

```
~ evo sts lnd 0x2a04000104000101000000000000000400000000000000000000000000000109 --chain heco
########## Mask ##############
is_reserved 0   
is_special  0   
has_box     0
######## Locatoin ############
x -32
y -14
########## Rate ##############
Resource Start     Current
gold     97        96.3986
wood     1         .9938
water    99        98.3862
fire     2         1.9876
soil     101       100.3738
------------------------------
LEVEL    8
########## Miner #############
lastUpdateSpeedInSeconds  0
lastDestoryAttenInSeconds 0
industryIndex             0
lastUpdateTime            1628038873
totalMiners               5
maxMiners                 0
########## Item ##############
Index Staker                                     ItemId
0     0xf233bBD8F73fca654a84aEe1462F0c54b7fFE2bD 0x2a040001040001040000000000000004000300000000000000000000000003e1
1     0xf233bBD8F73fca654a84aEe1462F0c54b7fFE2bD 0x2a040001040001040000000000000004000200000000000000000000000007f8
2     0xf233bBD8F73fca654a84aEe1462F0c54b7fFE2bD 0x2a040001040001040000000000000004000300000000000000000000000003ec
3     0xf233bBD8F73fca654a84aEe1462F0c54b7fFE2bD 0x2a040001040001040000000000000004000300000000000000000000000003e9
4     0xf233bBD8F73fca654a84aEe1462F0c54b7fFE2bD 0x2a04000104000104000000000000000400030000000000000000000000000457
######## Stength #############
Resource    Land                   Item                   Total
Gold        0.000000000000000000   0.000000000000000000   0
Fire        0.000000000000000000   0.000000000000000000   0
Soil        0.000000000000000000   0.000000000000000000   0
Water       16.278438331854480916  8.627572315882874885   24.906010647737355801
Wood        0.000000000000000000   0.000000000000000000   0
```

## Check the apostle information

```
~ evo sts apo 0x2a0400010400010200000000000000040000000000000000000000000000003b
####### Talent ##########
LIFE  54(0)   MOOD  49(0)
STR   23(0)   AGI   28(0)
DEX   10(0)   HP    53(0)
INT   9(0)    LUK   24(0)
POT   60(0)   CHA   0(0)
######### Prefer ###########
GOLD  WOOD  HOO   FIRE  SIOO
Lv.0  Lv.0  Lv.1  Lv.0  Lv.0
basic 1.533333333333333333  #使徒基础挖矿能力,越高越好, 与力量*敏捷成正比,潜力成反比
```

## Help

```
~ evo help
EVO - EVO Command Line Interface

Special commands:

   --addr-of       Get address of id
   --uint-of       Get uint of id

Commands:

   apo             Apostle Management
   apo-auc         Apostle Auction Management
   apo-bas         Apostle Base Management
   apo-gen         Apostle Gen0 Management
   apo-sir         Apostle SiringAuction Management
   cmn             Common Management
   cmn-enc         Common Encoder Management
   cmn-loc         Common Location Management
   cmn-ownership   Common Ownership Management
   cmn-pts         Common Points Management
   cmn-reg         Common Registry Management
   cmn-tokenuse    Common Ownership Management
   fnc             Furnace Management
   fnc-box         Furnace Drill Lucky Box Management
   fnc-drl         Furnace Drill Base Management
   fnc-fml         Furnace fml Management
   fnc-itm         Furnace Drill Base Management
   fnc-tel         Furnace MetaData Teller Management
   fnc-tkd         Market Drill TakeBack Management
   gen             EVO GeneScience Management
   help            Print help about evo(1) or one of its subcommands
   lnd             Land Management
   lnd-bar         Land Item Bar Management
   lnd-bas         Land Base Management
   lnd-mst         Land MysteriousTreasure Management
   lnd-res         Land Resource Management
   mkt             Market Management
   mkt-auc         Market Land Auction Management
   mkt-gen         Market Genesis Holder Management
   mkt-pts         Market Points Reward Pool Management
   mkt-rvn         Market Revenue Pool Management
   mkt-tk1         Market TakeBack Management
   mkt-tk2         Market TakeBack Management
   obj             Object Management
   sts             Object Status Management
   sts-apo         Apostle Status Management
   sts-lnd         Land Object Status

Report bugs to <https://github.com/evolutionlandorg/evo-tools/issues>.
```
