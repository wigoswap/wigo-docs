# Predict FAQ

### **How much time do I have to collect my winnings?**

There is no limit. You are able to collect your winnings at any time in the future.\


### **How is the payout calculated?**

Payout Ratio for GREEN Pool = Total FTM in Both Pools ÷ FTM in GREEN Pool

Payout Ratio for RED Pool = Total FTM in Both Pools ÷ FTM in RED Pool\
If there’s 20 FTM in the GREEN pool, and the overall round's value is 200 FTM, the GREEN payout ratio is (200/20)=10x.

\
Payout Amount = Payout Ratio × Position × (1 - Treasury Fee) × (1 - Referrer Fee)

\
In the same case, if the round ends on a GREEN result, if you deposit 3 FTM to a GREEN position, you’d get a payout of (3×10) × (1-0.04) × (1-0.01)  = 28.512 FTM. Your profit would be 25.512 FTM (28.512 - 3).\


The treasury fee is currently set at 4%, and the referrer fee is currently set at 1%, which may change in the future and would be announced on WigoSwap's official communication channels. Treasury fees are used to buy back and burn WIGO tokens. Every time the prize is collected, if the user has a referrer on WigoGalaxy, the referrer fee will be paid to the referrer. If the user hasn't had a referrer, the referrer fee will be sent to the Treasury to buy back and burn WIGO tokens.\


### Does the Predict include fees?

Yes.\
Treasury Fee = 4%\
Referrer Fee = 1%

Payout Amount = Payout Ratio × Position × (1 - Treasury Fee) × (1 - Referrer Fee)\


### What are you using for your price feed?

We use ChainLink Oracle for the Lock price and End price to know whether a user has won or not.\


### Why did the round's result change after it ended?

Sometimes, after a round closes, the final result may be different from the last result shown while the round was live. If you watch a round end on "RED", it may appear to flip to "GREEN" a few seconds later. This is because we use the ChainLink Oracle price feed to determine the final outcome of a round. The period between the end of one round and the start of the next is 60 seconds, but the Oracle refreshes every 20 seconds. It's possible that during this short period, Oracle might send an update while the transaction to trigger the next round is being minted. This can appear to "flip" the outcome of the previous round.\


### What happens if no one enters an opposing position?

If only one side of a round has positions entered into it and loses, all the losing funds will be sent to the treasury. For example, User X enters GREEN position and there is no participant in GREEN position. If X loses the round, funds will be sent to treasury, and if wins, user X can reclaim the fund.\
\


### What happens if the Locked Price and Closed Price are the exact same?

In very rare rounds that the Locked Price is exactly the same as the Closed Price, we have no winner and all funds entered into both positions will be sent to the treasury to buy back WIGO and burn.\


### Can I edit or cancel my entered position?

No. There is no way to cancel or edit your position, so be absolutely precise.\


### What does it mean when Predict is paused?

Predict is paused when there are conditions that affect the reliability of the contract. Predict being paused means no bets will be taking place for any rounds.\


### What causes WigoSwap Predict to pause?

The Predict will pause under the following conditions:

1. The prediction contract has been unable to fetch the price from the ChainLink oracle due to the Oracle not having posted the price when the round ended.
2. The prediction contract has been unable to execute an action (ending a round or getting a price from the Oracle) due to the TX being stuck in the mempool for a long time.
3. When will the Predict resume after being paused?

The Predict contract will resume automatically after some minutes.\


### What happens to the position if the Predict pauses?

If the Predict pause while you have a live position, your funds will be available to reclaim. To reclaim funds, you’ll need to pay some gas fees.\


### What happens to the position if the Predict pauses?

If the Predict pause while you have a live position, your funds will be available to reclaim. To reclaim funds, you’ll need to pay some gas fees.\


### What’s the WigoSwap PREDICT contract address?

{% embed url="https://ftmscan.com/address/0x2D0fd558fE73915322184Dcf99C20c5Eba86A1f3" %}
