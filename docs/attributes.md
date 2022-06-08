---
layout: page
title: Attribute Breakdown
permalink: /attribute-breakdown
---
# Attribute Breakdown 
{: .no-toc}
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
---
## Attributes
Each Chin Pokie has 6 cosmetic attribute categories and an additional attribute called Fertility. 

Each cosmetic attribute category has a different number of total attributes.
Each cosmetic attribute category has 6 rarities, listed in ascending order by rarity: Common, Uncommon, Rare, Epic, Legendary, Unique.
- Within a specific attribute category, an attribute with a lower rarity will always appear more often than a rarer attribute within that same category. 
- Unique attributes will appear only once in the whole collection. 
- Distribution quantities for each rarity tier varies per attribute category. Our goal was to distribute attribute rarity as evenly as possible. Due to different numbers of attributes per category, rarity per attribute has some variation. 
  - Ex:  A Legendary Face attribute will always be rarer than Epic Face attribute. 
  - Ex: A Legendary Body attribute is slightly less rare than a Legendary Face attribute. 

Attribute categories can be seen below. Learn more about the cosmetic aspects of each attribute on the Attributes Page. A rarity breakdown of each attribute category has also been included on the attributes page. 

**Fertility -** number ranging from 1-10. 
    

**Ruler -** a standard ruler with a measurement ranging from 1-12 (for non-unique Chin Pokies). 

**Face -** 49 variants + uniques

**Body -** 32 variants + uniques

**Head -** 52 variants + uniques

**Background -** 21 variants + uniques

**Skin -** 17 variants + uniques

| Attribute        | Variations          |
|:-------------|:------------------|
| Ruler           | 12 | 
| Face | 49  | 
| Body           | 32      | 
| Head           | 52 | 
| Background           | 21 | 
| Skin           | 17 | 
| Skin           | 17 | 


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
> 
The above Chin Pokie’s cumulative fertility is **8.2** (average of the above Fertility scores). 
Final fertility will be **capped at 10.** 