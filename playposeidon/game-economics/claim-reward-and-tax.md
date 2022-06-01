# 💰 Claim Reward and Tax

Every **PPP** earned from **NFT Hero** daily farm\*\*, Selling NFT Hero/Pet, Selling NFT Items\*\* in the Game is consider Player Income and will be a Taxed if Player want to claim it out to On-Chain **PPP**

{% hint style="info" %}
There is a minimum amount to Claim PPP to On-Chain, you can only claim when you have greater than or equal to **20 in-game PPP**. \
For non P2E player (player whom doesn't own any NFT Hero) this limit is 120 PPP.\
\*This minimum claim limit may be adjusted in the future.
{% endhint %}

### 1.Dynamic Tax Rate

The tax model is based around a fact that Claim **PPP** reward out have a cool-down period. When the game is launched this period is first set to 3 days. Then increasing by one day every week. At 4 weeks after Game launching, this cool-down period will be 7 days. Then it will be keep constant until further notice.

Every time you want to claim your **PPP**, a portion of your claimed amount will be taxed. Based on this model of 3 brackets: 20%(free) 30%(low-tax) 50%(high-tax)

**20%** of your total unclaimed In-Game **PPP** is free to claim.

**30%** of your total In-Game **PPP** will be taxed using curve formula follow a targeted price **P1** with (**b**)ase is 30% and (**M**)ax rate is 50% (min 20%)

$$
r1 = M-b *|ln(P/P1)|
$$

**50%** of total In-Game **PPP** will be taxed using curve formula follow a targeted price **P2** with (**b**)ase is 50% and (**M**)ax rate is 80% (min 30%)

$$
r2 = M-b *|ln(P/P2)|
$$

{% hint style="info" %}
**P** is current price of token **PPP**

**P1** is following 25 days MA (Moving Average) of price of token **PPP**

**P2** is following 7 days MA (Moving Average) of price of token **PPP**
{% endhint %}

This tax rate formula will create a incentive for Player to hold the PPP coin when the current Price start drifting from targeted price. The further price is moving away the lower the tax rate.

The total maximum tax rate if player withdraw all is theoretically capped at **55%** according to this formula (when **P=P1=P2**) In-realty the tax rate will be lower than that. For example, if player have **100 PPP** unclaimed reward and he want to claim **80 PPP**. At the claim moment, the price of **PPP = 1.5$** while targeted price **P1 = 1$** and target price **P2 = 2$.**

> **20 PPP** at **r=0% tax** , player receive 20 PPP
>
> **30 PPP** at **r1= 37.83% tax** , player receive 18.65 PPP
>
> **30 PPP** at **r2= 54.45% tax** , player receive 13.66 PPP
>
> Final **claimed** amount will be **52.31 PPP** (27.69 PPP is taxed) resulting a total **34% tax**

However if Player only claim **20%** of his total In-Game **PPP** at a time. He will not be taxed at all (**r=0% tax**). He can keep claiming 20% at a time for each cool-down period to **avoid the tax** completely.

This tax mechanism encourages player to spend his unclaimed **PPP** to reinvest or just diamond hand holding it to wait for a lower tax rate to claim.

### 2. Frequency of altering Tax Rate

For first 2 weeks of the game the tax rate will be set fixed to a low minimum:

**r1=20%** and **r2=30%**

After that the tax rate will be recalculated daily using formula above but with targeted price **P1** and **P2** set by the team. Depend on market sentiment and growth expectation we will set these targeted price to reflect that.

Once the game finish its first quarter. The targeted price **P1** will be automatically set to follow the current 25 days MA price and **P2** will be automatically set to follow the 7 days MA price.

{% hint style="info" %}
Note: The targeted price **P1,** **P2** may some time will be keep constant and not tracking Moving Average price of **PPP** token on purpose to keep the economy stable.\
Currently the targeted prices are set by the team:\
**P1** is set to **0.15$** (this is the price of **PPP** that the team want to achieve)  ****  \
**P2** is set to **0.072$** (**PPP** price was stable at this level for a month now)  **** &#x20;
{% endhint %}
