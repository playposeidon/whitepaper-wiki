# ❄ Pet Passive Skills

A Pet may have many skills depend on its rarity level. And can be categories into 2 groups: Shooting Skills and Non-shooting skills.

### 1. Shooting skills

Currently in PlayPoseidon game, there are 2 shooting skills for Pet:

**Fire-ball**: <img src="../../.gitbook/assets/Fire.png" alt="" data-size="original"> Deal huge damage to monster in AOE, damage is scaled with Pet base-damage. Fire-ball deal **2x Pet's base damage** in a large AOE explosion. The level of this skill will heavily impact the AOE of the explosion.

**Ice-ball**: ![](../../.gitbook/assets/Ice.png) Deal small AOE damage to monster. Will deal **1x Pet's base damage** but can slow down monsters movement speed and attack speed via _<mark style="color:blue;">Slow</mark>_ effect. The level of this skill will impact the duration of the slow and the speed of monster when being slowed.

**Tornado-ball**: <img src="../../.gitbook/assets/Storm skill.png" alt="" data-size="line"> Deal small AOE damage to monster. Will deal **1x Pet's base damage** but can provide the _<mark style="color:blue;">KnockBack</mark>_ effect <img src="../../.gitbook/assets/Skill_Pet_Air_Knockback.png" alt="" data-size="line"> when explode which push monsters away from base. The level of this skill will impact the distance of _KnockBack._

**Earth-ball:** <img src="../../.gitbook/assets/Earth_skill.png" alt="" data-size="line"> Deal small AOE damage to monster. Will deal **1x Pet's base damage** but can provide the _<mark style="color:blue;">Stun</mark>_ effect which stun monsters when explode. After the explosion, it leaves a stone boulder which fall to the ground and block the monster from moving. The level of this skill will impact the duration of the stun, the HP of the stone boulder and max duration the stone can stay on the ground.

**Pet** will shoot out **Fire-ball** or **Ice-ball** or **Wind-ball** or **Earth-ball** or **all of the shooting skill mentioned above .** The chance for each skill to be triggered will increase along with the level of skill. And also chances for each skill are independent of each other.

Note: **Pet** may shoot out one or multiple energy sparkles which deal **1x base-damage** to a single monster hit if none of the Shooting skill is triggered.&#x20;

### 2. Non Shooting skills

**Shield Hero**: ![](../../.gitbook/assets/Shield.png)Create a shield around your hero which can sustain a damages from monster equal to a small portion of the Hero total HP. This shield when not being damaged can regen over time.

### 3.All Skill tables:

| Pet Rarity                                               | Shooting Skill Level                                                                                                                                                                                                                                                      | Non Shooting Skill                       | Highscore Impact |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- | ---------------- |
| **Common**                                               | <img src="../../.gitbook/assets/Fire.png" alt="" data-size="original">LV1 ![](../../.gitbook/assets/Ice.png)LV1                                                                                                                                                           | N/A                                      | Very Low Impact  |
| _<mark style="background-color:blue;">Uncommon\*</mark>_ | <img src="../../.gitbook/assets/Fire.png" alt="" data-size="original">LV1 ![](../../.gitbook/assets/Ice.png)LV1                                                                                                                                                           | N/A                                      | Very Low Impact  |
| <mark style="color:blue;">**Rare**</mark>                | <img src="../../.gitbook/assets/Fire.png" alt="" data-size="original">LV1 ![](../../.gitbook/assets/Ice.png)LV1                                                                                                                                                           | N/A                                      | Low Impact       |
| _<mark style="color:green;">**Very Rare\***</mark>_      | <img src="../../.gitbook/assets/Fire.png" alt="" data-size="original">LV2 ![](../../.gitbook/assets/Ice.png)LV1 <img src="../../.gitbook/assets/Storm skill.png" alt="" data-size="line">LV1 <img src="../../.gitbook/assets/Earth_skill.png" alt="" data-size="line">LV1 | ![](../../.gitbook/assets/Shield.png)LV1 | Medium Impact    |
| <mark style="color:purple;">**Epic**</mark>              | <img src="../../.gitbook/assets/Fire.png" alt="" data-size="original">LV2 ![](../../.gitbook/assets/Ice.png)LV2 <img src="../../.gitbook/assets/Storm skill.png" alt="" data-size="line">LV2 <img src="../../.gitbook/assets/Earth_skill.png" alt="" data-size="line">LV2 | ![](../../.gitbook/assets/Shield.png)LV2 | High Impact      |
| <mark style="color:yellow;">**Legendary**</mark>         | <img src="../../.gitbook/assets/Fire.png" alt="" data-size="original">LV3 ![](../../.gitbook/assets/Ice.png)LV3 <img src="../../.gitbook/assets/Storm skill.png" alt="" data-size="line">LV3 <img src="../../.gitbook/assets/Earth_skill.png" alt="" data-size="line">LV3 | ![](../../.gitbook/assets/Shield.png)LV3 | Very High Impact |
| <mark style="color:red;">**Mythical**</mark>             | <img src="../../.gitbook/assets/Fire.png" alt="" data-size="original">LV4 ![](../../.gitbook/assets/Ice.png)LV4 <img src="../../.gitbook/assets/Storm skill.png" alt="" data-size="line">LV4 <img src="../../.gitbook/assets/Earth_skill.png" alt="" data-size="line">LV4 | ![](../../.gitbook/assets/Shield.png)LV4 | Enormous Impact  |



{% hint style="info" %}
\*This Rarity class is not released yet.
{% endhint %}

| Skill Level | Fire-ball                      | Ice-ball                         | Tornado-ball                         | Earth-ball                                        | Shield Hero                  |
| ----------- | ------------------------------ | -------------------------------- | ------------------------------------ | ------------------------------------------------- | ---------------------------- |
| LV1         | Medium chance                  | Low Chance, Slow 2s              | Very Low chance, Small KnockBack     | Super Low chance, 0.5s stun, 100 HP stone for 5s  | 500 SP, shield regen slow    |
| LV2         | Medium chance                  | Low Chance, Slow 2s              | Low chance, Medium KnockBack         | Super Low chance, 1.5s stun, 200 HP stone for 10s | 1000 SP, shield regen slow   |
| LV3         | High Chance + Large explosion  | High Chance + Large AOE, Slow 4s | Low chance, Strong KnockBack         | Very Low chance, 3s stun, 400 HP stone for 15s    | 2000 SP, shield regen medium |
| LV4         | High Chance + Large explosion  | High Chance + Large AOE, Slow 5s | Low chance, chance, Strong KnockBack | Very Low chance, 5s stun, 800 HP stone for 20s    | 3500 SP, shield regen fast   |

