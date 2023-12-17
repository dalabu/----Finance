# Liquidations

## <mark style="color:red;">Compound V2 or V3 ?</mark>

## Liquidations

### Introduction <a href="#introduction" id="introduction"></a>

Liquidation occurs when a borrower's health factor reaches or surpasses 100%, resulting from insufficient collateral to cover the supply value adequately. This situation can arise from a decline in collateral value of the asset or assets supplied.\
This collateral vs loan value ratio is shown in the health factor.

��= ���������� �����×����������� �ℎ���ℎ���​���� �����Hf​=LoanValueCollateralValue×LiquidationThreshold​​When��<1Hf​<1the position may be liquidated.

### How does liquidation work ? <a href="#how-much-is-the-liquidation-penalty" id="how-much-is-the-liquidation-penalty"></a>

The best way to explain it would be by giving some example.\
**Example 1:**\
**User** deposits 10 Jewel and borrows 5 Jewel worth of USDC. If users Borrow limit goes above 100% (because users collateral assets lost value) his loan will be eligible for liquidation. Protocol will instantly sell users 5 borrowed Jewel in order to cover value and equal out the sum that user initially borrowed from the platform.

### How can I avoid getting liquidated? <a href="#how-can-i-avoid-getting-liquidated" id="how-can-i-avoid-getting-liquidated"></a>

To prevent liquidation, users can increase their health factor by depositing more collateral assets or repaying a portion of their loan. Repayments generally have a greater impact on the health factor than deposits. Monitoring and maintaining a healthy Borrow limit , such as keeping it below 50% for example, provides a buffer against liquidation risk. Users should be aware of stable coin price fluctuations influenced by market conditions, as deviations from the expected value can impact the health factor. For instance, a stable coin with a market price of $0.95 instead of the expected $1.00 affects the health factor, emphasizing the need for vigilant monitoring.\
\


## V3

Problem of paying liquidations out of protocol resrves (soft&#x20;

Liquidation mechanism.

If CR < LR, the position becomes eligible for liquidation.

1. Liquidator calls absorb() function.
2. absorb() uses the funds from the protocol reserves of the base asset to pay back the debt.
3. In return, the protocol receives the collateral assets.

The excess of the collateral (if any) is returned to the user (minus a penalty) in the form of a base asset, leaving the position with a positive base asset balance. \
The caller has the amount of gas spent noted. In the future, they could be compensated via governance.\


If the remaining reserves are less than a governance-set target (targetReserves), liquidators are able to buy the collateral at a discount using the base asset, which increases the protocol’s base asset reserves.

The discount at which the liquidators can buy collateral is calculated using the formula: DiscountFactor = StoreFrontPriceFactor \* (1 - LiquidationFactor) StoreFrontPriceFactor - a fraction of the liquidation penalty that goes to buyers of collateral instead of the protocol.



Reserves.

Reserves are a balance of the base asset, stored internally in the protocol, which automatically protect users from bad debt.

Reserves are generated in two ways:

1. via reserve factor (from borrowers).
2. liquidations (liquidators buying collateral with base asset).



Other notable new features in Compound III:

* min. borrow position size (baseBorrowMin)
* min. amount of base asset supplied for accounts to accrue rewards (baseMinForRewards)
* gov sets parameters using a single Configurator contract
* Chainlink is the exclusive price feed  ?????????????



{% embed url="https://medium.com/scallopio/scallop-education-compound-v2-vs-v3-53b459f4fad3" %}
Difference between Compound v2 and v3 whene it comes to liquidation factors
{% endembed %}

<figure><img src="../.gitbook/assets/Liquidations difference on v2 and v3 (1).PNG" alt=""><figcaption></figcaption></figure>

{% embed url="https://www.comp.xyz/t/compound-iii/3351/18" %}
Info for the pic below
{% endembed %}

<figure><img src="../.gitbook/assets/Borrow, liquidation parameters and liquidation fee (1).PNG" alt=""><figcaption></figcaption></figure>
