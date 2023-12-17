# Protocol Assets

A list of suppliable and borrowable assets and their Borrow CF and Liquidation CF.

* JEWEL
* stJEWEL
* AVAX
* USDC
* ETHEREUM
* BITCOIN

{% tabs %}
{% tab title="Loan to value (LTV)" %}
Maximum Loan to value ratio represents the maximum borrowing power of a specific collateral. For example, if a collateral has an LTV of 50.00%, user can borrow up to 0.50 worth of JEWEL in USDC for every 1 Jewel worth of collateral.
{% endtab %}

{% tab title="Liquidation threshold" %}
Liquidation threshold represents the percentage at which a borrow position will be considered undercollateralized and subject to liquidation. For example, if a collateral has a liquidation threshold of 77.00%, it means that the loan will be liquidated when the debt value is worth 77.00% of the collateral value.

The difference between the Loan-To-Value and the Liquidation Threshold serves as a safety buffer for borrowers.
{% endtab %}

{% tab title="Liquidation penalty" %}
If the borrowers position becomes undercollateralized protocol begins the liquidation process. For this protocol will levy a liquidation penalty of 15%. Entire liquidation penalty is allocated to the protocol fees where part of those fees are redistributed to xSapphire holders, incentives funds and Treasury.\
Following the liquidation, if there are assets left from the borrowers collateral that were not sold to repay the debt, those assets will be returned to the borrower.\
<mark style="color:red;">(option I)</mark>

In the event that a borrower's position falls into undercollateralization, the protocol initiates the liquidation process, imposing a 15% liquidation penalty. The entire liquidation penalty is directed towards protocol fees, with a portion of these fees being distributed among xSapphire holders, incentive funds, and the Treasury. \
After liquidation, any remaining assets from the borrower's collateral that were not sold to settle the debt will be returned to the borrower.\
<mark style="color:red;">(option II)</mark>
{% endtab %}
{% endtabs %}

<table data-full-width="true"><thead><tr><th align="center">Currency</th><th align="center">Borrow CF</th><th align="center">Liquidation threshold</th><th align="center">Liquidation fee</th></tr></thead><tbody><tr><td align="center">JEWEL</td><td align="center">50.00%</td><td align="center">77.00%</td><td align="center">15.00%</td></tr><tr><td align="center">stJEWEL</td><td align="center">50.00%</td><td align="center">70.00%</td><td align="center">15.00%</td></tr><tr><td align="center">AVAX</td><td align="center">60.00%</td><td align="center">75.00%</td><td align="center">15.00%</td></tr><tr><td align="center">USDC</td><td align="center">70.00%</td><td align="center">80.00%</td><td align="center">15.00%</td></tr><tr><td align="center">ETHEREUM</td><td align="center">65.00%</td><td align="center">80.00%</td><td align="center">15.00%</td></tr><tr><td align="center">BITCOIN</td><td align="center">70.00%</td><td align="center">80.00%</td><td align="center">15.00%</td></tr></tbody></table>



\*During the initial phases of the protocol, the parameters for Borrow CF, Liquidation CF, and Liquidation fee are configured to safeguard the protocol against potential high volatility of certain assets. However, these settings are subject to modification in the future, particularly as the stability of treasury assets becomes established.

