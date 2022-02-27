# ❄ Pet Passive Skills

A Pet may have many skills depend on its rarity level. And can be categories into 2 groups: Shooting Skills and Non-shooting skills.

### 1. Shooting skills

Currently in PlayPoseidon game, there are 2 shooting skills for Pet:

**Fire-ball**: ![](../../.gitbook/assets/Fire.png) Deal damage to monster in AOE, damage is scaled with Pet base-damage. High level Fire-ball skill can provide larger explosion with Push back effect. Push back effect is depend on the movement speed of the monster and level of this skill. &#x20;



**Ice-ball**: ![](../../.gitbook/assets/Ice.png) Also deal AOE damage to monster. Will deal less damage but can slow down monsters movement speed. The level of this skill will impact the duration of the slow and the movement speed of monster when being slowed.

By default, **Pet** will shoot out **Fire-ball** but some time your Pet will shoot out **Ice-ball** based on the chance mentioned here:  [pet-attributes.md](pet-attributes.md "mention")

### 2. Non Shooting skills

**Shield Hero**: ![](../../.gitbook/assets/Shield.png) Create a shield around your hero which can sustain a damages from monster equal to a small portion of the Hero total HP. This shield when not being damaged can regen over time.

### 3.All Skill tables:

| Pet Rarity                                               | Shooting Skill Level                                                         | Non Shooting Skill                       | Highscore Impact |
| -------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------- | ---------------- |
| **Common**                                               | ![](../../.gitbook/assets/Fire.png)LV1 ![](../../.gitbook/assets/Ice.png)LV1 | N/A                                      | Very Low Impact  |
| _<mark style="background-color:blue;">Uncommon\*</mark>_ | ![](../../.gitbook/assets/Fire.png)LV1 ![](../../.gitbook/assets/Ice.png)LV1 | N/A                                      | Very Low Impact  |
| <mark style="color:blue;">**Rare**</mark>                | ![](../../.gitbook/assets/Fire.png)LV2 ![](../../.gitbook/assets/Ice.png)LV1 | N/A                                      | Low Impact       |
| _<mark style="color:green;">**Very Rare\***</mark>_      | ![](../../.gitbook/assets/Fire.png)LV2 ![](../../.gitbook/assets/Ice.png)LV1 | ![](../../.gitbook/assets/Shield.png)LV1 | Medium Impact    |
| <mark style="color:purple;">**Epic**</mark>              | ![](../../.gitbook/assets/Fire.png)LV2 ![](../../.gitbook/assets/Ice.png)LV2 | ![](../../.gitbook/assets/Shield.png)LV2 | High Impact      |
| <mark style="color:yellow;">**Legendary**</mark>         | ![](../../.gitbook/assets/Fire.png)LV3 ![](../../.gitbook/assets/Ice.png)LV3 | ![](../../.gitbook/assets/Shield.png)LV3 | Very High Impact |
| <mark style="color:red;">**Mythical**</mark>             | ![](../../.gitbook/assets/Fire.png)LV4 ![](../../.gitbook/assets/Ice.png)LV4 | ![](../../.gitbook/assets/Shield.png)LV4 | Enormous Impact  |

{% hint style="info" %}
\*This Rarity class is not released yet.
{% endhint %}

| Skill Level | Fire-ball                        | Ice-ball       | Shield Hero                                                  |
| ----------- | -------------------------------- | -------------- | ------------------------------------------------------------ |
| LV1         | Small explose                    | Slow 3s        | 500 HP, regen very slow                                      |
| LV2         | Large explose                    | Slow 5s        | 1000 HP, regen slow                                          |
| LV3         | Large explose + Push back        | Strong Slow 5s | 2000 HP, regen medium (regen speed scale by Hero HP)         |
| LV4         | Large explose + Strong Push back | Strong Slow 8s | <p>3500 HP, regen fast<br>(regen speed scale by Hero HP)</p> |

