# 🥷 Apostle Arena

### 1. Game Overview

Apostle Arena is a 1v1 turn-based game. Each round, players can choose a \[Stance] to face the opponent, and the \[Stance] has a mutual restraint relationship like rock-paper-scissors. When one of the player’s HP drops below zero, the game is over.

Not only NFTs from Evolution Land can participate, but all ERC-721 assets can participate in the gameplay through governance.

### 2. Stance introduction

There are 4 basic stances in the game, namely **charge**, **focus attack**, **attack**, and **parry**.

The restraint relationship between them is that the **focus attack** restrains the **attack**, the attack restrains the **parry**, and the **parry** restrains the **focus attack**.

If you choose the stance that restrains your opponent, his stance would be invalid.

For example, if you choose **focus attack** and the opponent chooses **attack**, the opponent's **attack** will not deal damage to you, and you will deal the full damage of the **focus attack** to the opponent.

Stance introduction

**Charge**: Add one **energy** to yourself.

**Focus Attack**: Consume the number of **energy** to make one attack with 2.5 times (one-time charge)/4 times (two-time charge) ATK. It could trigger a critical hit.

**Attack**: Perform an attack, which will trigger a critical hit.

**Parry**: Repel the opponent's focus attack, take no damage to yourself, and fully reflect the damage to the opponent.

**Standby**: When you disconnect or forget to select your own stance, it will be judged as the standby stance by default, and you will not do anything this round.

Special Mechanism

About the **Parry**:

1. **Parry** stance **cannot** be used for two consecutive rounds.

About energy:

1. Two consecutive successful **attack** will add one **energy**.
2. The **energy** will be reset to zero after performing any other stance than **charge**.
3. The maximum number of **energy** is 2. Continuing to **charge** when there are already 2 **energy** will not increase the number of **energy**, but the charge status can be maintained.
4. After reaching 2 **energy**, you can perform **charge** for 2 consecutive rounds at most, otherwise, you can only choose **focus attack** in the next round.
5. The **energy** will also be cleared after receiving damage from the **focus attack**.

About attack:

1. If both sides perform **attack** at the same time, both sides will receive 50% damage from the opponent's attack.
2. If both sides perform a **focus attack** at the same time, no matter how many **energy** each side is in, they will receive 50% damage from the opponent's attack.

About skills:

Each profession will have three **skills**. You can choose one **skill** to bring into the game on the main page. These skills have powerful effects, but at the same time, they will have a long CD and may have some side effects. These will be released in the subsequent version.

### 3. Game mode

The PVP gameplay has two modes: Casual and Rank. No matter which mode is played, the COO will be used as the power.

**Casual Mode**: In casual mode, users will not change their rank, and will not change their status on rank list.

**Rank mode**: Users need to purchase a season pass and pledge it (it can be retrieved after the season ends, and the pass will be attached with rank information related to this season) to participate in the ranking mode, and participating in the rank mode competition can be win rewards.

### 4. Season Rewards

Each season will last for 3 months. There will be three kinds of season rewards:

\


1. 70% of the season pass sales revenue will form a prize pool, which will be distributed to each player according to the ranking. The calculation formula is as follows:

\


![](https://preview.redd.it/9rxvxr9nhmx81.png?width=510\&format=png\&auto=webp\&s=17fbed0dec5ad9307f53d148fd75d6f136043c9e)

\


2\. Top-ranked users will receive special honorary NFT rewards

3\. Each user will record the rank information of this season on the pass after getting back the pass. The pass of each season is unique, and it will have important commemorative significance.

5\. Participation

At the beginning of the PVP launch, Apostle Arena will cooperate with some well-known NFT/Gamefi projects as initial members to participate in the PVP gameplay.

In the future, other NFTs can be introduced into the PVP gameplay by Evolution Land's governance system.

NFTs will have similar initial properties, with slight differences depending on their rarity.

\
