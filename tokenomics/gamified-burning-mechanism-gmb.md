# Gamified Burning Mechanism (GMB)

![](../.gitbook/assets/GBM.png)

Without rewards, there would be much less incentive to provide liquidity (LP fees etc. would remain). **There's a hard-cap on the supply of WIGO token: 2,000,000,000.** Therefore, we need a mechanism which prolongs the time to reach the hard-cap.

GMB is a mechanism of WigoSwap that uses gamification to support long term price stability and value growth, brings profits to WIGO holders and delays reaching the hard-cap.

> **The More Activities, The Longer Incentives.**

By Gamified Burning Mechanism, WigoSwap provides the possibility of minting new tokens and continues to reward farmers and stakers through burning (de-minting) some of the circulating WIGO tokens and reducing total supply. The goal is for more WIGO to leave circulation than the amount of WIGO that's producing before reaching the hard-cap. We will get closer to this goal only by increasing the activities and transactions on the platform.



In the WIGO, the Total Supply can never exceed the hard-cap (Max Supply), and we have:

`Total Supply = Total Minted - Total Burned`

All three of the above variables are always accessible and readable in the WIGO Smart Contract.

{% content-ref url="../smart-contracts/wigoswap-contracts.md" %}
[wigoswap-contracts.md](../smart-contracts/wigoswap-contracts.md)
{% endcontent-ref %}



Below are the current sources for Gamified Burning Mechanism:

* **2%** of every harvest in the [Automatic](../products/wigo-bank/automatic-vs.-standard.md) staking pool (Performance Fee).
* **0.5%** of every unstake within three days in the [Automatic](../products/wigo-bank/automatic-vs.-standard.md) staking pool.
* **0.01%** of every swap made on WigoSwap. Buyback WIGO and burn it manually every week through the wigoBurn function in the MasterFarmer smart contract.

More sources will be added in the near future.
