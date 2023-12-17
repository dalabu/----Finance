# Royal Vault - Liquid staking

### Are we a rebase model of liquid staking or claim reward whenever user wants model of staking ? If we are making rebase token is it going to be tradeable on DEX ?

### Why do we need Liquid staking derivatives (LSD's) ?

In order to provide flexibility LSD's allow users to buy, sell, or trade tokens while actively participating in staking, thereby boosting liquidity in decentralized finance (DeFi).

Staking typically involves locking assets, rendering them illiquid, but LSD's address this challenge by tokenizing staked assets, making them tradable and usable in DeFi protocols, thereby preserving liquidity. The growing popularity of LSDs is attributed to their improved liquidity, interoperability, and their role in activities like yield farming and collateral utilization.

Key benefits include heightened capital efficiency, increased flexibility in market engagement, and the ability to diversify investment strategies. For instance, on --- Finance, you might choose to convert your Jewel into stJewel, effectively creating a liquid staked derivative.

### Concept of **stJewel**

One of the most important functions of the protocol is to allow user to liquid staking of Jewel. Liquid staking of Jewel can be done in Royal Vaults and the process is very simple.\
User goes into Royal Vaults page on our site and  press the stake button and then choose the amount of Jewel and for how much time you want to stake your Jewel.\
By doing this user initiates a sequence of smart contract interactions that will lead to Jeweler in DefiKingdoms.\
There are two main reasons why users should stake your Jewel in Royal Vaults:

* user will receive LSD token named stJewel
* user rewards for staking will be payed both in Jewel and Sapphire in the 80:20 ratio

### Why is stJewel beneficial for everyone inside of DFK Chain ecosystem ?

For example user on --- Finance can decide to supply their stJewel to the protocol thus receiving suppliers interest rates and also unlocking the option to borrow USDC against their overcollateralized stJewel. With the USDC borrowed user can decide to further invest the asset either on the protocol or elsewhere on the DFK Chain.\
Other way stJewel could be used is by providing liquidity for Jewel/stJewel LP or any other LP user chooses to provide liquidity to.\
\
These are some of the examples how by using stJewel users can use their capital more efficiently and diversify their investment strategies.\


#### Important note: some of the functions mentioned in the example wont be available at the launch of the protocol (see roadmap).



### How to Stake

In order to stake your Jewel you need to go to Royal Vaults. When you open the page, you will next to "STAKE" button have an option to put the amount of Jewel you want to stake and right below it a scrollbar with which you can set your lock period from 7 days to 1095 days (3 years).

Another feature Royal Vaults offer is to calculate the APR for the last 24 hours to 30 days. This  aggregate APR accounts for Jewel accumulated from Jeweler as well as Sapphire rewarded.&#x20;

Based on the amount of time and Jewel users decide to lock, they will receive stJewel based on those two variables. Formula for how much stJewel users will receive for staking is the same one used by the Jeweler in DefiKingdoms that calculates how much cJewel users get for staking Jewel.

\
Example I: if user stakes 1000 Jewel to the Royal Vaults for 1095 days, they will receive 1000 stJewel.\
Example II: f user stakes 1000 Jewel to the Royal Vaults for 365 days, they will receive 333.333 stJewel.\
\
Before staking users are advised to check our Rewards calculator.\
<mark style="color:red;">(option I)</mark>\
\
\---------------------------------------------------------------------------------------------------------------------

To stake your Jewel, visit the Royal Vaults platform. Upon accessing the page, locate the "STAKE" button, where you can specify the amount of Jewel you wish to stake. Just below, there's a scrollbar allowing you to choose your lock period, ranging from 7 days to 1095 days (3 years).

Additionally, Royal Vaults provides a feature to calculate the APR (Annual Percentage Rate) for the past 24 hours to 30 days. This APR calculation takes into account the Jewel accumulated from Jeweler and the Sapphire rewarded.&#x20;

The quantity of stJewel that users receive is determined by the duration and amount of Jewel they choose to lock. The formula for calculating the stJewel received during staking mirrors the one employed by the Jeweler in DefiKingdoms, which determines the cJewel users receive for staking Jewel.

Example I: If a user stakes 1000 Jewel in Royal Vaults for 1095 days, they will be receive 1000 stJewel.\
Example II: If a user stakes 1000 Jewel in Royal Vaults for 365 days, they will receive 333.333 stJewel.

Prior to engaging in staking, users are encouraged to check our Rewards calculator.\
<mark style="color:red;">(option II)</mark>

### How to Unstake

Right next to "STAKE" button users can find "UNSTAKE" button option. if you wish to unstake your stJewel you can withdraw only the entire amount of your stJewel staked.

There are two scenarios when unstaking your stJewel in order to get Jewel back. First one being if you wish to unstake stJewel after your lock staking period expired.\
In this scenario users can unstake their stJewel without any additional fees, you will however have to pay the gas fees for the transaction.\
Important note: even after your lock period expires and user does not unstake their stJewel from the protocol they will continue getting rewards.

Second scenario is if a user decides to unstake their stJewel before lock expiry period they will be get back only 48% of the Jewel they initially staked. Two variables are contributing to 52% withdrawal fee, Jeweler in DefiKingdoms will instantly burn 50% of users staked Jewel by triggering emergency withdrawal option and 2% will be given to the protocols treasury as a fee for early unstaking.\
<mark style="color:red;">(option I)</mark>

\---------------------------------------------------------------------------------------------------------------------

Adjacent to the "STAKE" button, users will find the "UNSTAKE" option. If you intend to unstake your stJewel, you can only withdraw the entire amount of stJewel that has been staked.

There are two scenarios for unstaking stJewel to reclaim Jewel. The first scenario occurs when a user wishes to unstake stJewel after the expiration of the lock staking period. In this case, users can unstake their stJewel without incurring additional fees, but they will need to cover the gas fees for the transaction. \
Important note: even after the lock period expires, users who do not unstake their stJewel will continue to receive rewards.

The second scenario arises when a user decides to unstake their stJewel before the lock expiry period. In this situation, they will only receive back 48% of the initially staked Jewel. Two factors contribute to the 52% withdrawal fee: in DefiKingdoms, the Jeweler will immediately burn 50% of the user's staked Jewel by triggering the emergency withdrawal option, and the remaining 2% will be allocated to the protocol's treasury as a fee for early unstaking.\
<mark style="color:red;">(option II)</mark>

### How to Claim

Next to the "UNSTAKE" button there  "CLAIM" option that allows you to collect&#x20;

<mark style="color:red;">Ako neko stake 100 Jewela na 7 dana kolko dobija stJewel-a ? Jer ja kod Jewelera ne dobijam isti amount cJewela ako stakujem 7 dana ili 3 godine. Kako to racunat ? Da li napravit varijantu da zavisno kolko cJewela dobijem kod Jewelra tolko stJewela dajem userima ?</mark>&#x20;

<mark style="color:red;">Claim options:</mark>

* <mark style="color:red;">Claim rewards and get Jewel + Sapphire (in this situation am I buying Sapphire with Jewel or giving it from the Treasury)</mark>
* <mark style="color:red;">After x amount of time claim more Jewel (Sapphire buying Jewel over time to increase Jewel ammount ?)</mark>

<mark style="color:red;">Sto ja odje nudim sto vec ne daje Jeweler, osim likvidnog Jewela ? Kako mogu da increase Jewel amount kad neko unstake stJewel, kojom matematikom ?</mark>

<mark style="color:red;">stETH pravi APR putem staking + MEV (they run validators and infrastructure) koji je moj ekvivalent ovoga da mogu da prenesem na stJewel ?</mark>

### Reward protocol fee

For the service of providing stJewel to users, protocol reward fee accounts to 10% of all staking rewards (not total amount of Jewel staked). All protocol reward fees are directed to Treasury.\
<mark style="color:red;">(option I)</mark>

\---------------------------------------------------------------------------------------------------------------------

In facilitating the provision of stJewel to users, a protocol reward fee equivalent to 10% of all staking rewards is applied (based on the staking rewards and NOT the total staked Jewel amount).\
All protocol reward fees are funneled into the Treasury.\
<mark style="color:red;">(option II)</mark>



### Calculation Jewel to stJewel ratio once you unstake, how much Jewel you get back ? how are rewards calculated ?

Re-base token, the more time you stake your coin/token the more coins/tokens you will have once you decide to unstake it.

Example: you start with the ratio Jewel/stJewel 1:1. After 1 year passes lets say the APR for 12 months was 5% the ratio is 1:1.05 which means that if you unstake your stJewel after 12 months you get 1.05 Jewel back.



\
Example:\
\
User goes to our stJewel page on the --- Finance website and click "Stake" option and then choose the amount of Jewel they want to stake.\
As you can see the stJewel : Jewel ratio is 1 : 1.019 which means that for every stJewel you need to deposit 1.019 Jewel at the given APY that depends on the current market conditions of the protocol.\
By submitting this transaction you will lock your 1.019 Jewel but get a new token called stJewel which you can further use while still staking and getting APY for the Jewel you staked.\
\
When user decides to unstake their Jewel, they can do so by going to the very same page and clicking "Unstake" section where they will have an option to put the amount of stJewel they want to unstake in order to get Jewel.\
\
Third option on the page is called "Claim" and it servers as users tool to claim the aggregated rewards that they earned by staking their Jewel.



\---------------------------------------------------------------------------------------------------------------------







Check out Plutus finance for ideas

LSD JEWEL - unlock your liquidity + extra farm \
stake jewel > get stJEWEL \
choose lock period - 15/30/90/360 days \
we take 10% cut you get extra emission of our governance and utility token $sapphire (edited)

emergency withdrawal/redemption 50% (dfk fee) + 2% protocol fee

stJEWEL/JEWEL - emisije $sapphire na Defi Kingdoms DEX\
na dfk dex i trazit alokaciju $crystal-a za pool









Calculation of cJewel apr:



For those of you that like scripts, you can use this code:\


\# vars\
initial\_deposit = 10000 \
final\_balance = 10000 + 1341 # Initial deposit plus earnings \
days\_invested = 402 # Duration of the investment\
\
\# Calculating the rate of return per day\
rate\_of\_return\_per\_day = ((final\_balance / initial\_deposit) - 1) / days\_invested

Calculating the monthly and annual APR\
monthly\_apr = rate\_of\_return\_per\_day \* 30.44 # days per month avg \
annual\_apr = monthly\_apr \* 12\
\
rate\_of\_return\_per\_day, monthly\_apr, annual\_apr\
\
\
[https://twitter.com/DeFiKujo/status/1734323415098474553](https://twitter.com/DeFiKujo/status/1734323415098474553)
