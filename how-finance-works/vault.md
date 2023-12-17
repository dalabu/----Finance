# Vault



### Overview

The main function of Vault is to give users option on the money market part of the protocol to earn higher interest rates or pay lower borrowing interest rates by locking xSapphire in the Vault.

### How the Vault Operates

To access features of the Vault, such as higher interest rates on supplied assets or reduced borrowing interest rates, users must meet two specific conditions:

* have supplied or borrowed assets on the protocol (users can acquire borrowed assets only by supplying to the protocol)
* stake xSapphire into Vault

To activate emissions on both increased supply interest rates or lowered borrow interest rates, users must lock minimum 10% worth of xSapphire in USDC value in the Vault. <mark style="color:red;">(option I)</mark>

To trigger emissions for both increased supply interest rates and reduced borrow interest rates, users need to lock a minimum of 10% equivalent in USDC value of xSapphire in the Vault. <mark style="color:red;">(option II)</mark>

Example 1: If you deposit $1000 USDC but have zero xSapphire tokens locked into Vault, you'll earn the basic APY but won't qualify for additional Vault emissions.

Example 2: Supply $1,000 USDC and lock $100 worth of xSapphire tokens in Vault. Now you're eligible for additional emissions, thanks to hitting that 10% threshold.

Example 3: Supply $1,000 USDC and $1,000 worth of Jewel to the protocol. You will have to stake $200 worth of xSapphire into Vault in order to unlock additional emissions for both USDC and Jewel.\
If you have only $100 worth of xSapphire you can choose and $2,000 worth of supplied assets you can choose which asset emission you want to boost.

Example 4 (for borrowed interest rates): If you borrow $1,000 USDC and your borrowed interest rate is at 8.00% (borrowed interest rates depend on market conditions) you can by staking $100 worth of xSapphire in the Vault decrease your borrowing interest rate by 2% (also depends on the market conditions).\
\- borrowed interest rates depend on multiple factors: utility rate,                ?\
\- decrease borrowing rate:          ?

Important note, if the asset that is supplied increases in value users will have to increase the amount of their xSapphire staked in the Vault to match 10% USDC parity that unlocks boosted emissions, also if value of xSapphire decreases users will have to add more xSapphire to the Vaults to achieve the 10% threshold parity asset staked USDC worth and xSapphire USDC worth. <mark style="color:red;">(option I)</mark>

Crucial reminder: Should the value of the supplied asset rise, users need to increase the amount of xSapphire staked in the Vault to align with the 10% USDC parity that unlocks access to enhanced emissions. \
Similarly, if the value of xSapphire decreases, users must add more xSapphire to the Vaults to attain the 10% threshold parity in both the asset-staked USDC worth and xSapphire USDC worth. <mark style="color:red;">(option II)</mark>

If the xSapphire threshold in the Vault falls below 10%, users face the possibility of being liquidated by bounty hunters ([find more about our bounty system](vault.md#bounty-system)). <mark style="color:red;">DO WE DO THIS</mark>

### How to enable Vault functions

Users can choose which supplied asset they want to increase their supplied interest rate on by going to the markets and clicking on the asset that they supplied. After this on the screen they will have an option to enable Vault boosted emissions.\
It is important for users to know that while they might decide to supply different assets to the protocol, it is only of their choosing which asset they will increase supplied rates for.\
For example if user supplies to the protocol JEWEL, USDC, AVAX and ETHEREUM they can decide that they want to activate only increased supply interest rates for JEWEL asset and not the entire pool of all supplied assets. In this scenario user will have to provide 10% threshold requirement in order to activate the increased supply interest rates only for JEWEL asset and not for the all assets it supplies to the protocol.

Same process goes for borrowed USDC asset, if the users choose to lower borrowed interest rates on it.

Another very important detail is, same as in supply and borrow money market, these increase or decrease in interest rates depends on the given market conditions and utilization of the asset.\
<mark style="color:red;">(option I)</mark>

### How to Enable Vault Features

Users can designate the supplied asset for which they wish to increase the supplied interest rate by navigating to the markets and selecting the asset they have supplied. Subsequently, on the screen, they will find an option to activate Vault boosted emissions.

It is essential for users to understand that, while they may choose to supply various assets to the protocol, the decision to increase supplied rates applies only to the asset of their choice. For instance, if a user supplies JEWEL, USDC, AVAX, and ETHEREUM to the protocol, they can specify that they want to activate increased supply interest rates exclusively for the JEWEL asset, rather than for the entire pool of supplied assets.\
In such a scenario, the user must meet the 10% threshold requirement to activate the increased supply interest rates solely for the JEWEL asset, not for all assets supplied to the protocol.

The same process applies to the borrowed USDC asset if users opt to decrease the borrowed interest rates on it, they have to meet the 10% threshold requirement.&#x20;

Another crucial detail to note is that, similar to the supply and borrow money market, these adjustments in interest rates depend on prevailing market conditions and the utilization of the asset.<mark style="color:red;">(option II)</mark>

### Bounty system

Idea from [https://docs.radiant.capital/radiant/project-info/dlp/bounties](https://docs.radiant.capital/radiant/project-info/dlp/bounties)

### Maximize your lock APR

There is one more variable that you need to take into consideration when considering staking your xSapphire in the Vault and that is lock time period.

<mark style="color:blue;">Option I</mark>

<mark style="color:blue;">Minimum lock period of xSapphire into the Vault equals the time xSapphire stays locked for.</mark>

<mark style="color:blue;">Example 1: If your xSapphire is locked for 12 months you can lock your xSapphire into the Vault for minimum of 12 months</mark>

<mark style="color:blue;">Example 2: If your xSapphire locked period is 6 months you can lock your xSapphire into the Vault for minimum of 6 months.</mark>

<mark style="color:blue;">However it is important to know that even if your xSapphire is locked for less then 12 months formula that will be used for calculating your APR will be the one that is used for 12 months locked period of xSapphire in the Vault</mark>

<mark style="color:purple;">Option II</mark>

<mark style="color:purple;">Minimum lock period of xSapphire into the Vault is 3 months</mark>



**Maximum lock APR (taken from** [**https://docs.radiant.capital/radiant/project-info/dlp/dlp-utility**](https://docs.radiant.capital/radiant/project-info/dlp/dlp-utility)**) -** \


This is calculated as the highest APR achievable when xSapphire is locked for a three-year period in the Vault.

* **Formula**: `1-month lock APR * 3-year lock multiplier (25x)`

#### 36 months locking APR

This is the current APR for locking your xSapphire tokens for a 3 year period.

* **Formula**: `(Total 1 Month Lockers’ Share of Annualized Protocol Fees) / (Total 1 Month Lockers’ Share of dLP Pool Size)`

#### **12 months locker share of protocol fees **<mark style="color:red;">**? WE HAVE THIS WITH xSapphire function !!!**</mark>&#x20;

<mark style="color:red;">Can we divide stakers that stake xSapphire for monimum of 12 months, if we can we allow them to collect protocol fees and for the ones that stake less then 12 months their is no protocol fees.</mark>

* **Formula**: `(1 Month Locker Share of Protocol Power) / (Total Protocol Locking Power)`

#### Total Protocol Locking Power

The sum of all lockers’ shares, each adjusted by its respective multiplier.

* **Formula**:\
  for less then 12 months of locking xSapphire to the Vault locker multiplier is 1.2x \
  \- (12 Month Lockers' Share of dLP Pool Size \* 1 Month Locker Multiplier (1.2x))   ?

<pre><code><strong>= (12 Month Lockers' Share of dLP Pool Size * 1 Month Locker Multiplier (2x)) 
</strong>+ (18 Month Lockers’ Share of dLP Pool Size * 3 Month Locker Multiplier (4x))
+ (24 Month Lockers’ Share of dLP Pool Size * 6 Month Lockers’ Multiplier (10x))
+ (36 Month Lockers' Share of dLP Pool Size * 12 Month Locker Multiplier)
</code></pre>

###

### <mark style="color:red;">Adding additional xSapphire to the vault</mark>

<mark style="color:red;">How does this corelate with the lock period, when users add extra xSapphire to the Vault ? Can we divide stakers that stake xSapphire for more then 12 months, if we can we allow them to collect protocol fees and for the one that stake less then 12 months their is no protocol fees.</mark>



Wihtdrawing xSapphire from the Vault





Requirement of locking liquidity tokens in the Vault benefits the money market protocol in various ways:

1. Long-Term Engagement: By locking xSapphire tokens in the Vault, users are essentially committing to a specific duration, enhancing the probability that they will uphold their deposited collateral over an extended period.
2. Drawing in New Participants: These dynamics enhance the attractiveness of --- Finance money market to potential liquidity providers, consequently fostering both growth and development while showcasing the sustainability of the protocol.
