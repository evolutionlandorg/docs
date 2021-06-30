---
description: A Special Opportunity for Pioneers!
---

# Gold Rush

Inhabitants of Evolution Land are eager explorers! Whenever a new continent is discovered, there are some who choose to abandon their comfortable lives and donate their lands back to EVE, in hopes of exchanging them for new and abundant lands on the new continent. EVE then selects the best candidates to become Explorers and Pioneers; who undertake the journey and settle on the new lands.

## Participation

Prior to official launch of the New Continent, players who own land on the Original Continent will be able to participate in the Gold Rush event through the official website [evolution.land](https://www.evolution.land/) -&gt; Gold Rush.

1. Enter [evolution.land](https://www.evolution.land/), click "GoldRush" at the top of the page, and then connect your wallet.
2. Select the "original continent" and the "target continent".
3. Select a land you own on the original continent you would like to give back to EVE for recycling.
4. Fill in the number of RINGs as a reserve fund to participate in the lottery of the New World.
   * _During the registration period, players need to bind the land from the Original Continent to any number of RINGs as a reserve fund to participate in the lottery of the New World._
   * _The higher the reserve fund is, the higher the probability of being selected to earn the chance for exchanging lands. Besides, the land used for relocation and the number of RINGs can be adjusted before the registration period is over._
5. Fill in an address for receiving the land on the new continent.
   * _After the lottery is over, players need to hand over the land on the original continent to EVE on the event page. After confirmation, players pick up the land in the target new continent._
   * _Players who have not been drawn can claim back the reserve fund on the event page._

**Notes**

* Before handing over the land, please take out the apostles and items placed on the original land in time.
* Increasing the reserve fund for land relocation will increase the probability of being selected. The higher the reserve fund is, the higher the probability of being selected to earn the chance for exchanging lands.
* Once the drawing process completed, players first need to send their land from the original continents on the event page. Then, they are able to claim their new land in the game. If not drawn, players could claim their reserve fund on the event page.
* 24 hours before the deadline for registration, you can add/delete land, adjust fees, and modify the address receiving the land on the new continent.
* The lands on the New Continent will be sorted from high to low according to the total amount of resources, according to the value of \(total resources of plots x 0.6 + investment RING x 0.4\), and awarded in descending order.
* Results will be announced when the lottery ends; and afterward, players will be able to view the details on the event announcement page. Players will also be able to check the continent the event was held on to view the historical details.

## Lottery Rules

The lottery uses a [random weighted algorithm](https://github.com/hujw77/raffle) that makes a selection from one of N elements with different weights, and the overall selection result is then distributed according to the weights.

Assuming that 4 plots of land: A, B, C, and D participate in the lottery.

And the mortgage amounts are 1, 2, 3, and 4 respectively.

In the random result, the ratio of A:B:C:D would be 1:2:3:4.

Accumulate the weights of each land A\(1\)-B\(3\)-C\(6\)-D\(10\), and the weight jurisdictional intervals of the 4 elements become \(0,1\), \(1,3\), \(3,6\), \(6,10\).

Then, generate a random number between \(0,10\). In which interval, the elements of the interval are elements that fall within the same weight.

To select M pieces of land: select a piece of land according to the above method, remove it from the collection, and then iterate over the remaining land according to the above method.

The random number is selected as the hash of the block. If the final lottery block is B, we start with B-M blocks, and draw a total of M block hashes as the random number for the lottery.

An example of a lucky draw on ropsten:

```text
Assume that 4 plots of land A, B, C, and D participate in lottery, and the mortgage amount is 1, 2, 3, and 4 respectively.

The final lottery block is 10000

The hash of the 9998th block is: 0x09cc4bb3ab6bb019e6bdca3a79d07c8d72919cf561489ac9101e4217b3cb8131

The remainder of 1e19 plus 1 is: 0.094 RING; which falls in the (0,1) interval, so corresponding land A wins the prize.

After removing land A, the intervals of B, C, D are (0,2) (2,5) (5,9)

The hash of the 9999th block is:
0x9e552bad9996f391acea81a0d77556958e96314f897ed0abbb16d0d36a54668f

The remainder of 9e18 plus 1 is: 1.087 RING; which falls in the (0,2) interval, and so the corresponding land B wins the prize.

When the lottery draw is over, both land A and land B win prizes.
```

We will use the block height before the end of the event as the random seed, and the lottery will be performed according to the above algorithm. All players who are chosen get to undertake the migration!

