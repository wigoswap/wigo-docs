# Predict FAQ

#### How much time do I have to collect my winnings?

There is no limit. You are able to collect your winnings at any time in future.\


#### How is the payout calculated?

Payout Ratio for UP Pool = Total FTM in Both Pools ÷ FTM in UP Pool

Payout Ratio for DOWN Pool = Total FTM in Both Pools ÷ FTM in DOWN Pool

\
If there’s 20 FTM in the UP pool, and the overall round's value is 200 FTM, the UP payout ratio is (200/20)=10x.

\
Payout Amount = Payout Ratio × Position × (1 - Treasury Fee)

\
In the same case, if the round ends on a UP result, if you deposit 3 FTM to a UP position, you’d get a payout of (3\*10) × (1-0.04) = 28.8 FTM. Your profit would be 25.8 FTM (28.8 - 3).\


The treasury fee is currently set at 4% which may change in the future, which would be announced on WigoSwap’s official communication channels. Treasury fees are used to buy back and burn WIGO tokens.\


#### Does the Predict include fees?

Yes. 4% of the round's total value will go to the treasury, which will be used to buyback and burn WIGO tokens.\
\


#### What are you using for your price feed?

We use ChainLink Oracle for the Lock price and End price to know whether a user has won or not.\


#### Why did the round's result change after it ended?

Sometimes, after a round closes, the final result may be different from the last result shown while the round was live. If you watch a round end on "DOWN", it may appear to flip to "UP" a few seconds later. This is because we use the ChainLink Oracle price feed to determine the final outcome of a round. The period between the end of one round and the start of the next is 30 seconds, but the Oracle refreshes every 20 seconds. It's possible that during this short period, Oracle might send an update while the transaction to trigger the next round is being minted. This can appear to "flip" the outcome of the previous round.\


#### What happens if no one enters an opposing position?

If only one side of a round has positions entered into it and loses, all the losing funds will be sent to the treasury. For example, User X enters UP position and there is no participant in UP position. If X loses the round, funds will be sent to treasury, and if wins, user X can reclaim the fund.\
\


#### What happens if the Locked Price and Closed Price are the exact same?

In very rare rounds that the Locked Price is exactly the same as the Closed Price, we have no winner and all funds entered into both positions will be sent to the treasury to buy back WIGO and burn.\


#### Can I edit or cancel my entered position?

No. There is no way to cancel or edit your position, so be absolutely precise.\


#### What does it mean when Predict is paused?

Predict is paused when there are conditions that affect the reliability of the contract. Predict being paused means no bets will be taking place for any rounds.\


#### What causes WigoSwap Predict to pause?

The Predict will pause under the following conditions:

1. The prediction contract has been unable to fetch the price from the ChainLink oracle due to the Oracle not having posted the price when the round ended.
2. The prediction contract has been unable to execute an action (ending a round or getting a price from the Oracle) due to the tx being stuck in the mempool for longer than 15 blocks.
3. When will the Predict resume after being paused?

Predict will resume when an admin manually resumes it.\


#### What happens to the position if the Predict pauses?

If the Predict pause while you have a live position, your funds will be available to reclaim. To reclaim funds, you’ll need to pay some gas fees.\


#### What happens to the position if the Predict pauses?

If the Predict pause while you have a live position, your funds will be available to reclaim. To reclaim funds, you’ll need to pay some gas fees.\


#### What’s the WigoSwap PREDICT contract address?

....
