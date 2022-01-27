# Rewards Distribution

![](../.gitbook/assets/Distribution.png)

The base emissions rate is 9 WIGO per second divided across WIGO staking and farming pools. WIGO minting features a mid-term hyper inflationary period of 8 months in which rewards have a 9 times multiplier in the first month, and are reduced automatically every month afterward. All of tokens minted in this period will be released immediately.

## Rewarding Schedule

| Month | Duration    | WIGO/s | Rewards     | Total Rewards |
| ----- | ----------- | ------ | ----------- | ------------- |
| 1     | 2,592,000 s | 81     | 209,952,000 | 209,952,000   |
| 2     | 2,592,000 s | 72     | 186,624,000 | 396,576,000   |
| 3     | 2,592,000 s | 63     | 163,296,000 | 559,872,000   |
| 4     | 2,592,000 s | 54     | 139,968,000 | 699,840,000   |
| 5     | 2,592,000 s | 45     | 116,640,000 | 816,480,000   |
| 6     | 2,592,000 s | 36     | 93,312,000  | 909,792,000   |
| 7     | 2,592,000 s | 27     | 69,984,000  | 979,776,000   |
| 8     | 2,592,000 s | 18     | 46,656,000  | 1,026,432,000 |
| 9     | 2,592,000 s | 9      | 23,328,000  | 1,049,760,000 |
| 10    | 2,592,000 s | 9      | 23,328,000  | 1,073,088,000 |
| 11    | 2,592,000 s | 9      | 23,328,000  | 1,096,416,000 |
| 12    | 2,592,000 s | 9      | 23,328,000  | 1,119,744,000 |
| ...   | ...         | ...    | ...         | ...           |
| 31    | 2,592,000 s | 9      | 23,328,000  | 1,562,976,000 |
| 32    | 2,592,000 s | 9      | 23,328,000  | 1,586,304,000 |
| ...   | ...         | ...    | ...         | ...           |
| n     | 2,592,000 s | 9      | ?           | ?             |

Although WIGO has a 2 billion hard-cap, [Buyback, Burn & Reward](gamified-burning-mechanism-gbm.md) mechanism prolongs the time to reach the hard-cap. Assuming no tokens are burned, it will take about 33 months to reach the hard-cap. The more tokens burned, the longer emissions, but the total supply of WIGO will never exceed the hard-cap.

## **Why WIGO per Second?**

Reading the texts explaining the mechanism of the farms and the calculation of the emissions on WigoSwap, you might have asked yourself why in the terminology “WIGO per second” is used rather than “WIGO per block”? The answer is simple; WigoSwap operates on the Fantom Blockchain, and on Fantom, transaction activities on the blocks determine the block time on the network. Therefore, the block time could range from less than one second to 20+ seconds.

But why is this important for WigoSwap’s ecosystem? Considering the farms, in which you stake your tokens to earn rewards, there is no significant difference between WigoSwap’s farms and the farms that make use of other chains. Nevertheless, with regards to the operations such as swapping, the Fantom Blockchain is outstanding and able to outperform other chains. This is due to the fact that on the Fantom Blockchain there is an inverse relationship between the number of transactions and the block times. In other words, an increase in the number of transactions on the network leads to a decrease in the block times. Consequently, users benefit from a faster transaction speed and a faster trading experience.
