---
description: NFT - ERC721 - Pet - EXP
cover: ../../.gitbook/assets/9 pets horizontal.png
coverY: 0
---

# 🐼 NFT Pets

### Intro

This is the secondary **NFT** of the game which is an **ERC-721** token that allow Player to level up their NFT Hero and help deal AOE damage, slow effect to monster when fighting battle in **PlayPoseidon** game. During battle, player must have a Pet to fight along with the Hero.

**NFT Pets** need to be spawned from an **Egg** item. Egg items is **Gacha** type item, You can read this section: [#2.-egg](../../playposeidon/earn-mechanism/gacha-items.md#2.-egg "mention") from Gacha page to check the details on spawn chances.

### Rarity Level

**NFT Pets** are divided into different Rarity Level, with each tier is extremely rare compare to lower tier according to the Spawn chances stated in **Gacha** page. Therefor the more rare the Pet the higher the benefit it can provide to the NFT Hero.&#x20;

| Pet Rarity                                       | Hero Attributes bonus Buff | Energy (Time to fully recover) |
| ------------------------------------------------ | -------------------------- | ------------------------------ |
| **Common**                                       | 0%                         | 20 (24 Hours)                  |
| <mark style="color:blue;">**Rare**</mark>        | 0-9.99%                    | 30 (24 Hours)                  |
| <mark style="color:purple;">**Epic**</mark>      | 10-19.99%                  | 40 (24 Hours)                  |
| <mark style="color:yellow;">**Legendary**</mark> | 20-24.99%                  | 50 (12 Hours)                  |
| <mark style="color:red;">**Mythical**</mark>     | 25-30%                     | 50 (6 Hours)                   |

#### 1. Hero Attributes buff

Each NFT Pet can provide an attributes bonus buff to the Hero when fight together. The amount of buff is random and given to the pet when it spawn out of an egg. With maximum buff is 30% for a <mark style="color:red;">**Mythical**</mark> Pet. Exception is **Common** Pet, which doesn't have this buff at all.&#x20;

This buff will increase these Hero attributes stated below:

* Hero Health Point
* Arrow Base Damage
* Stamina

For example a **Hero LV4** with HP: 4600, Base Damage: 60, Stamina: 50, when pair with a <mark style="color:yellow;">**Legendary**</mark> Pet with **22%** Hero Attributes bonus buff will become: HP: 5612, Base Damage: 73.2, Stamina: 61

#### 2. Pet Energy&#x20;

Each NFT Pet have a energy bar. After each winning match your Pet will lose some energy (depend on the difficulty level of the Stage), if the Pet have low energy, not enough to start a new match you need to select another Pet or fight a lower level Stage.

| Map Difficulty Level | Low and Mid value Pet                                                                            | High value Pet                                   | High value Pet                               |
| -------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------ | -------------------------------------------- |
|                      | **Common,**<mark style="color:blue;">**Rare,**</mark><mark style="color:purple;">**Epic**</mark> | <mark style="color:yellow;">**Legendary**</mark> | <mark style="color:red;">**Mythical**</mark> |
| Level 1              | -1 Energy per Match                                                                              | -1 Energy/Match                                  | No cost                                      |
| Level 2              | -2 Energy per Match                                                                              | -1 Energy/Match                                  | -1 Energy/Match                              |
| Level 3              | -3 Energy per Match                                                                              | -2 Energy/Match                                  | -1 Energy/Match                              |
| Level 4              | -4 Energy per Match                                                                              | -3 Energy/Match                                  | -2 Energy/Match                              |
| Level 5              | -5 Energy per Match                                                                              | -4 Energy/Match                                  | -3 Energy/Match                              |
| Level 6              | -6 Energy per Match                                                                              | -5 Energy/Match                                  | -4 Energy/Match                              |
| Level 7              | -7 Energy per Match                                                                              | -6 Energy/Match                                  | -5 Energy/Match                              |
| Level 8              | -8 Energy per Match                                                                              | -7 Energy/Match                                  | -6 Energy/Match                              |
| Level 9              | -9 Energy per Match                                                                              | -8 Energy/Match                                  | -7 Energy/Match                              |

Also higher rarity Pet may give a small EXP bonus per match. <mark style="color:red;">**Mythical**</mark> pet EXP bonus giving a conversion of 1 Energy to **4 EXP**, <mark style="color:yellow;">**Legendary**</mark> giving a conversion of 1 Energy to **2 EXP.** You can check this excel file below to fully understand the impact of Pet Rarity level when leveling up your Hero.&#x20;

{% embed url="https://docs.google.com/spreadsheets/d/1FYfa2-MHKCJOYbPH3jDbX5t9KG2_nJKaa4cWuNRmACA/edit?usp=sharing" %}

### Other Attributes:

#### A NFT Pet can be either a male :male\_sign: or a female :female\_sign:&#x20;

This will be displayed on the NFT Pet card or Pet detail. In **2021 Q4** the Game will release **NFT Farming** feature to allow NFT Pet owner to use a pair of Pet of different sex to breed a new Pet **Egg**&#x20;
