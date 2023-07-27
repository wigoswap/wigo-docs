# Troubleshoot

While using WigoSwap, you may run into issues you find difficult to deal with. Hence, you may need to check the following troubleshooting tips to find the solution to the problem you’ve been confronted with.  &#x20;

## **Swap-related Issues**

### **Insufficient\_output\_amount**

> The transaction cannot succeed due to error: WigoswapRouter: INSUFFICIENT\_OUTPUT\_AMOUNT. This is probably an issue with one of the tokens you are swapping.
>
> or
>
> The transaction cannot succeed due to error: execution reverted: WigoswapRouter: insufficient\_output\_amount.

You cannot swap tokens due to low slippage tolerance or low liquidity of the related token pair.

<details>

<summary><strong>Reason</strong></summary>

The liquidity for the tokens you try to swap is insufficient. This can partly be due to the low market cap of the tokens you want to swap, and the fact that fewer people are trading those tokens.&#x20;

Another reason for this type of problem can be related to scam tokens that cannot be sold due to their fraudulent nature. In such cases WigoSwap does not have the authority to block those tokens, and is also unable to return funds.

</details>

<details>

<summary><strong>Solution</strong></summary>

1. Refresh your page or try swapping the tokens later.
2. Lower the amount you decide to trade with.&#x20;
3. Raise the level of your slippage tolerance; to do so, first open the ‘settings’ on the liquidity page. Then use the buttons to choose a higher slippage tolerance or enter the amount manually and try again.&#x20;
4. Finally, use fewer decimal places in the amount you have entered.

</details>



### **Insufficient\_A\_amount or Insufficient\_B\_amount**

> Fail with error 'WigoswapRouter: INSUFFICIENT\_A\_AMOUNT'\
> or\
> Fail with error 'WigoswapRouter: INSUFFICIENT\_B\_AMOUNT'

You may face this problem while adding/removing liquidity from a pool with an insufficient amount of one of tokens in the pair.

<details>

<summary><strong>Reason</strong></summary>

The primary reason for this type of error is the insufficient amount of one of the tokens in the liquidity pool you decide to add/remove your liquidity from.

Other possible reasons can be the fast rate of price updates, or your low slippage tolerance.

</details>

<details>

<summary><strong>Solution</strong></summary>

1. Refresh the page and try again.
2. If the problem is not solved, open the ‘settings’ on the liquidity page. Then use the buttons to increase the slippage tolerance or enter the amount manually and try again.

</details>



### **WigoswapRouter: Expired**

> The transaction cannot succeed due to error: WigoswapRouter: EXPIRED. This is probably an issue with one of the tokens you are swapping.

<details>

<summary><strong>Reason</strong></summary>

This error occurs when you don’t confirm the transaction within the limited time. In other words, confirming the transaction has been done with a significant delay.&#x20;

</details>

<details>

<summary>Solution</summary>

Try repeating the transaction, and ‘confirm’ the operation immediately after you are asked to do so.&#x20;

</details>



### **Wigoswap: K**

> The transaction cannot succeed due to error: Wigoswap: K. This is probably an issue with one of the tokens you are swapping.

<details>

<summary><strong>Reason</strong></summary>

This error usually occurs when the operation includes swapping a token with its own fee.

</details>

<details>

<summary>Solution</summary>

Set the amount in the “To” field manually so that the estimation is done for the token in the “From” field.

</details>



### **Wigoswap: Transfer\_Failed**

> The transaction cannot succeed due to error: execution reverted: Wigoswap: TRANSFER\_FAILED.

<details>

<summary><strong>Reason</strong></summary>

This error can be is caused by the design of Restorative Rebase Tokens like tDoge or tBTC. Learn more here:

[Restorative Rebase](https://btcst.medium.com/stp-8-restorative-rebase-b4fbbdfd96c)

</details>

<details>

<summary>Solution</summary>

Ensure that there are 30% more tokens in your wallet than the amount you decide to trade. You may have to enter 69% or 70% (instead of 100%) if you intend to sell the entire amount you have.&#x20;

</details>

{% hint style="warning" %}
There may be other reasons besides the one mentioned above. For example, a dishonest token issuer might suspend the trading of its tokens. The token issuer can also prevent you from selling, while allowing certain addresses to sell their tokens. In order to avoid such risks, please exercise due diligence before investing in any type of project. In some cases, swapping tokens obtained through airdrops may lead to this error. This can indicate that the airdrop was probably a scam in the first place. In such a situation avoid the approval of any tokens or following any links as it can lead to your funds being at risk.
{% endhint %}

\


### **Transaction cannot succeed**

<details>

<summary><strong>Reason</strong></summary>

This error occurs due to low liquidity.

</details>

<details>

<summary>Solution</summary>

Repeat the transaction with a lower amount, or a higher slippage tolerance. To increase the slippage tolerance, open the ‘settings’ on the liquidity page. Then use the buttons to choose a higher slippage tolerance or enter the amount manually and try again.

</details>



### **Price impact is too high**

<details>

<summary><strong>Reason</strong></summary>

This error occurs due to low liquidity.

</details>

<details>

<summary>Solution</summary>

Repeat the transaction with a lower amount, or a higher slippage tolerance. To increase the slippage tolerance, open the ‘settings’ on the liquidity page. Then use the buttons to choose a higher slippage tolerance or enter the amount manually and try again.&#x20;

</details>



### **Cannot read property ‘toHexString’ of undefined**

> "Unknown error: "Cannot read property 'toHexString' of undefined"

Usually seen on smartphones using TrustWallet, this error is displayed while trying to swap tokens.

<details>

<summary><strong>Reason</strong></summary>

This is probably caused by the insufficient slippage allowed on TrustWallet. The details of the error are not clear though.&#x20;

</details>

<details>

<summary>Solution</summary>

Increase the slippage tolerance and try performing the transaction again.&#x20;

In case the problem is not solved, you probably need to use another wallet on your device to perform the transaction.

</details>



### **Execution reverted: Transferhelper: Transfer\_From\_Failed**

> The transaction cannot succeed due to error: execution reverted: TransferHelper: TRANSFER\_FROM\_FAILED.

Reported on various platforms, this error is displayed while trying to swap tokens. &#x20;

<details>

<summary><strong>Reason</strong></summary>

There are some possible reasons for this error. The reasons include insufficient amount of funds in the wallet, or disagreement between the amount permitted to be spent and the amount being spent. Furthermore, since trading tokens with Restorative Rebase requires adequate knowledge about their features, take your time to use this guide for more information**:**

[Restorative Rebase](https://btcst.medium.com/stp-8-restorative-rebase-b4fbbdfd96c)

</details>

<details>

<summary>Solution</summary>

You have to check the amount of your funds to see if it’s sufficient.&#x20;

Ensure that the amount of funds you are trading with does not exceed the amount of funds you have given the contract the permission to spend.&#x20;

</details>

## **Issues Related to WigoBank**&#x20;

### **Burn amount exceeds balance**

> Fail with error 'ERC20: burn amount exceeds balance'
>
> or
>
> EmergencyWithdraw: You do not have enough xWIGO!

<details>

<summary><strong>Reason</strong></summary>

Since you need the WigoBank (xWIGO) Tokens to unstake your WIGO tokens from the [Standard](../wigoswap-the-defi/defi-products/staking-wigo/automatic-vs.-standard.md) staking pool in the WigoBank, you should not sell or transfer those tokens. The ratio of the xWIGO tokens transferred to your wallet to the WIGO tokens you’ve staked is 1:1. Therefore, when you want to unstake your WIGO tokens, the same amount of xWIGO tokens must be burned. If the amount of xWIGO tokens you have is insufficient, you will face this error.&#x20;

</details>

<details>

<summary>Solution</summary>

If you are trying to unstake WIGO and this error occurs, you have to obtain as many WigoBank (xWIGO) tokens as the amount of WIGO tokens you decide to unstake.&#x20;

</details>



### **Out of gas error**

> Warning! Error encountered during contract execution \[out of gas]

The gas limit you have set while performing a transaction is low.&#x20;

<details>

<summary><strong>Reason</strong></summary>

This problem is caused by your wallet being unable to complete the action. The reason is that your wallet considers the determined gas limit to be too low. Therefore, the gas is finished before the function is completed.

</details>

<details>

<summary><strong>Solution</strong></summary>

Prior to confirming the transaction, raise the amount of ‘Gas Limit’ in your wallet. Note that adjusting the gas limit might be slightly different in various wallets. To find the related information you can check your wallet’s documentation. &#x20;

</details>



### **Transfer amount exceeds allowance**

> Fail with error 'ERC20: transfer amount exceeds allowance'

<details>

<summary><strong>Reason</strong></summary>

This happens when you set a limit on your spend allowance when you first approved the contract, then try to swap more than the limit.

</details>

<details>

<summary><strong>Solution</strong></summary>

1. Use Unrekt.net to revoke approval for the smart contract you're trying to interact with
2. Approve the contract again, without setting a limit on spend allowance
3. Try interacting with the contract again.

</details>



### **Transfer amount exceeds balance**

> Fail with error 'ERC20: transfer amount exceeds balance'

This type of error is displayed when you are attempting to unstake from an old WigoBank staking pool with low rewards to harvest. Therefore, the transaction fails. &#x20;

<details>

<summary><strong>Reason</strong></summary>

You may see this error if you are attempting to withdraw from a WigoBank staking pool in which the reward is lower than expected.&#x20;

If this is not the case, the other reason for such an error might be sending tokens that are not available in your wallet (for example, tokens that have already been sent and the process has not completed yet, or the transaction is pending). Therefore, double-check the availability of the tokens you want to transfer.&#x20;

</details>

<details>

<summary><strong>Solution</strong></summary>

Inform the team about the problem with the WigoBank so that they increase the rewards to the desired level. However, if you are fine with not harvesting the unclaimed rewards, you can use ‘emergency withdrawal’. To do so you can follow the steps below:

1. Find the contract address of the WigoBank staking pool from which you are attempting to unstake your tokens. The address is shown in your wallet’s transaction log. &#x20;
2. Open [FTMScan](https://ftmscan.com) and in the search field enter the contract address.&#x20;
3. Select the ‘Write Contract’ tab.&#x20;
4. Connect your wallet by clicking on the ‘connect to web 3.0’ button.
5. Enter 0 in the ‘emergency withdraw’ box, and click on the ‘write’ button.

Note that by unstaking your tokens using this method, it would not be possible to harvest any unclaimed rewards.

</details>

## **Other Issues**

### **Provider Error**

> Provider Error\
> No provider was found

<details>

<summary><strong>Reason</strong></summary>

This error is displayed in case you’ve not installed your wallet’s browser extension (e.g. MetaMask browser extension) and you try to connect your wallet.

</details>

<details>

<summary><strong>Solution</strong></summary>

Install the browser extension of the wallet you wish to connect to WigoSwap from official sources. You can learn how to connect your wallet to WigoSwap [here](connect-your-wallet-to-wigoswap.md).\


</details>



### **Unsupported Chain ID**

In this case you have to change your chain to Fantom Opera Network. You may also need to get help from your wallet’s official documentations. \


### **Internal JSON-RPC errors**

> MetaMask - RPC Error: Internal JSON-RPC error. estimateGas failed removeLiquidityETHWithPermitSupportingFeeOnTransferTokens estimateGas failed removeLiquidityETHWithPermit

There is no certainty regarding the cause of this error. It usually occurs when you attempt to remove liquidity from some tokens using MetaMask. Trying another wallet for the operation solves the problem. &#x20;

> Internal JSON-RPC error. { "code": -32000, "message": "insufficient funds for transfer" } - Please try again.

The amount of FTM you need to pay for the transaction fee is not sufficient. Try providing the adequate amount.&#x20;



### **Error: \[ethjs-query]**&#x20;

> Error: \[ethjs-query] while formatting outputs from RPC '{"value":{"code":-32603,"data":{"code":-32000,"message":"transaction underpriced"\}}}"

To solve this problem, you need to raise the transaction’s gas in your wallet. You can check your wallet’s guides to understand the process for increasing the gas limit.&#x20;

> Swap failed: Error: \[ethjs-query] while formatting outputs from RPC '{"value":{"code":-32603,"data":{"code":-32603,"message":"handle request error"\}}}'

To solve the above problem, go through the following steps:

* Increase the gas limit
* Increase the slippage tolerance
* Clear cache
