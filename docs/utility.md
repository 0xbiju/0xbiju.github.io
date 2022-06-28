---
layout: page
title: Utility
nav_order: 5
permalink: /utility
---
# Utility
{: .no_toc .text-delta }

## Table of contents
{: .no_toc .text-delta }
1. TOC
{:toc}
---

## Overview
Utility will be implemented primarily in the form of staking. Chin Pokie NFTs will be able to be staked making community members who do so eligible for rewards. Rewards include but are not limited to: \$SWIM token generation, airdrops, raffles, and more. Utility will be developed and implemented post-launch using the aforementioned allocation of mint sale funds. 

## Fertility

### What is Fertility?

Fertility is an invisible attribute that affects staking and utility. 
Every Pokie has a fertility score ranging from 1.0 to 10.0. 
Fertility will be listed on OpenSea, but will not have a designated rarity. 
The value here will directly affect staking/utility with a higher Fertility score resulting in more \$SWIM generated when staked. 

Higher rarity attributes will have a higher base Fertility score when being used to calculate a Pokie's fertility. 
Each attribute will have a higher floor for their fertility score. Fertility score isn't just a number, it's a key component to our algorithm and will help generate tangible rewards as determined by the Team.

### How is Fertility Calculated?

Each Chin Pokie’s Fertility will be calculated by taking the average of the hidden Fertility score of each individual attribute.
The hidden fertility score of each attribute is calculate when generating each Chin Pokie. Meaning the same attribute will most likely have a different hidden Fertility score on different Pokies. The attribute's rarity influences the hidden Fertility as follows:
- **Common -** Randomly generated Fertility between 1-10
- **Uncommon -** Randomly generated Fertility between 1-10 plus 2
- **Rare -** Randomly generated Fertility between 1-10  plus 4
- **Epic -** Randomly generated Fertility between 1-10 plus 6
- **Legendary -** Randomly generated Fertility between 1-10 plus 8
- **Unique Pokies-** Guaranteed Fertility of 10

Example with random numbers.
Chin Pokie#5555 has the following attribute spread:
 - **Rare -**  Randomly generated Fertility between 0-10 + 4 -> (6+4) = 10
 - **Epic -** Randomly generated Fertility between 0-10 + 6 -> (7+6) = 13
 - **Legendary -** Randomly generated Fertility between 0-10 + 8 -> (8+8) = 16
 - **Common -** Randomly generated Fertility between 0-10 -> 1
 - **Common -** Randomly generated Fertility between 0-10 -> 8
 - **Common -** Randomly generated Fertility between 0-10 -> 1
 
The above Chin Pokie’s cumulative fertility is **8.2** (average of the above Fertility scores). 
Final fertility will be **capped at 10.** 

## About \$SWIM
Swimmers (\$SWIM) are a Chin Pokie specific token that will be used to redeem rewards. [Fertility](/attribute-breakdown#fertility) score will determine how much \$SWIM is generated when Pokies are staked. Additionally, staking with multiple Pokies will result in more \$SWIM generated since more fertility will be utilized. Tokenomics around \$SWIM will be released at a later date. 

## Staking & Rewards
Rewards that will be redeemable through the aforementioned utility process include:
1. **Chin Pokies Merchandise** - custom merchandise will be 100% redeemable with earned \$SWIM. The only cost for community members will be shipping.
2. **Giveaway Access** - members actively staking with their Chin Pokie will automatically be entered into AL and NFT raffles as well as giveaways for any future releases.
3. **Raffles & Auctions** - Members can use \$SWIM to enter raffles for Allowlist spots for Gen II Chin Pokies as well as Allowlist spots for collaborative projects. Additionally, members can bid on limited releases & new collections using \$SWIM.

## \$SWIM Tokenomics
Chin Pokies are committed to implementing staking post-launch. Some of the specifics of how $SWIM works have already been defined and will be explained below. Staking functionality will be implemented post-launch on our website using an allocated percentage of the aforementioned community fund (60% of mint sales).

Maximum staked fertility will be capped at 20, regardless of how many Chin Pokies staked.
- Ex: If Chin Pokies holder stakes 4 NFTs with fertilities of 4, 9, 8, and 5, the total fertility staked will still be 20. 
- Ex: If Chin Pokies holder stakes 2 NFTs with fertilities of 4 and 3,  the total fertility staked will be 7.

$SWIM will be accrued at a rate of **Total Fertility Staked<sup>1.5</sup>** each day that Chin Pokie NFTs are staked.

Accrued $SWIM can be collected by clicking the redeem button on our website.

