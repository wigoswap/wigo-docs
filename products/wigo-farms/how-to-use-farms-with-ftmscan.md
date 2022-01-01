# How to Use Farms with FTMScan

The steps involved in using farms through [FTMScan](https://ftmscan.com) is a little more complicated compared with interacting with the Wigo Farms directly. Therefore, this type of interaction is recommended to expert users. &#x20;



### **Finding Farm PID**

Utilizing the farming smart contracts requires the Process Identifier (PID) that corresponds to your LP pair. You can easily check WigoSwap's GitHub to access the PID. To do so, you can follow the steps below:

1\. Open the [farms list](https://github.com/wigoswap/wigo-interface/blob/master/src/config/constants/farms.ts) on GitHub.&#x20;

2\. Use ‘control/command + F’ to search for a certain pair of tokens, e. g. ‘FTM-WIGO’. &#x20;

3\. You can then see the PID number which you should keep somewhere so that you can use it afterwards.&#x20;



### Depositing **LP Tokens via FTMScan**

In order to deposit LP tokens using FTMScan, you need to follow the steps mentioned here:

First, you have to obtain the address related to the MasterFarmer Contract. The address is ………. . If you ever need to check the address you can visit <mark style="color:blue;">MasterFarmer Contract</mark> in FTMScan. The address is shown on top of the page and you can easily copy the address by clicking on the copy icon.

Then, in order to approve the smart contract that is related to the LP token you want to deposit in a farm, follow the steps below:

#### **From the source code;**

* Open the [farms list](https://github.com/wigoswap/wigo-interface/blob/master/src/config/constants/farms.ts) on GitHub.&#x20;
* Use ‘control/command + F’ to search for the desired pair of tokens, e. g. ‘FTM-WIGO’. &#x20;
* As illustrated in the picture, you can then find the address written after ’250:’.&#x20;

#### **From the UI;**

* Open the Wigo Farms page, and find your desired pair using the search box on top of the page.
* Click on ‘details’ to view more information regarding your pair.
* In order to see the smart contract on FTMScan, click on the ‘View Contract’ button. \


### **Granting Permission to the LP Token Contract**

Having done the above steps to find your chosen LP token contract on FTMScan, you now have to confirm the use of your LP tokens in the Wigo Farms.&#x20;

* From the LP token’s contract page, choose the ‘Contract’ tab and select ‘Write Contract’ from the subcategories.&#x20;
* Connect your wallet and confirm the connection in your wallet.&#x20;
* In the ‘approve’ section, enter the MasterFarmer Contract’s address you’ve copied in the previous step into the ‘spender (address)’ field.&#x20;
* In order to determine the amount of LP tokens the contract is allowed to spend, you should also enter the desired amount in the ‘Value’ field.&#x20;
* Finally, you are ready to deposit LP tokens to the farm by clicking on the ‘Write’ button and confirming the operation in your wallet. Needless to say, the amount of LP tokens you can use in the farm is limited to that you’ve already approved in this stage.

{% hint style="info" %}
You can also use `-1` as the value to give unlimited spend approval. This does not mean you will spend everything by default, but only that a transaction of any size using this contract will be allowed by your wallet.
{% endhint %}



### **Depositing LP Tokens Using the MasterFarmer Smart Contract**&#x20;

Now that you’ve gone through the prerequisite of depositing your LP tokens, you are ready to do so following the steps below:&#x20;

* Open <mark style="color:blue;">MasterFarmer Contract</mark> in FTMScan. Select the ‘Contract’ tab and choose ‘Write Contract’ from the subcategories.
* Connect your MetaMask wallet by clicking on the ‘Connect to Web3’ button.&#x20;
* Move on to the ’Deposit’ section, and enter the PID you’ve copied in the first stage. (You can find the necessary information on how to find the PID by reading **Farm Process Identifier** section on this page.)
* In the ‘Amount’ field below the ‘PID’, you also need to enter the amount you have approved for your LP token to spend in the previous section.
* Confirm the operation in your wallet by clicking on the ‘Write’ button.&#x20;
* You are now able to view the details of your transaction by clicking on the ‘View your transaction’ button.&#x20;



### **Withdrawal from a Farm**

In case you decide to withdraw your LP tokens from a farm, the steps you need to follow are not different from those of depositing. However, the function you interact with is different;

* Open <mark style="color:blue;">MasterFarmer Contract</mark> in FTMScan. Select the ‘Contract’ tab and choose ‘Write Contract’ from the subcategories.
* Connect the MetaMask wallet by clicking on the ‘Connect to Web3’ button.&#x20;
* As illustrated in the picture, scroll down to the ‘Withdraw’ section, and enter your PID number in the related box. (You might need to read **Farm Process Identifier** section on this page to find out how you can find the PID.)
* After entering the PID number, you also have to enter the amount of LP tokens you decide to withdraw in the ‘Amount’ box.&#x20;
* Confirm the operation in your wallet by clicking on the ‘Write’ button.&#x20;
* You can see your transaction details by clicking on the ‘View your transaction’ button.&#x20;



### **Emergency Withdrawal**&#x20;

As the name suggests, this method should only be used when there is no other possible way for the withdrawal operation. It is worth mentioning that using the emergency withdrawal function leads to the loss of your WIGO rewards. Therefore, We recommend you not to use this operation unless there is a special situation involved, or you are an expert in understanding smart contracts and the codes involved.&#x20;

* Open <mark style="color:blue;">MasterFarmer Contract</mark> in FTMScan. Select the ‘Contract’ tab and choose ‘Write Contract’ from the subcategories.
* Connect the MetaMask wallet by clicking on the ‘Connect to Web3’ button.&#x20;
* Scroll down to the ‘Emergency Withdraw’ section, and enter your PID number in the related box. (You can find the necessary information on how to find the PID by reading **Farm Process Identifier** section on this page.)
* Confirm the operation in your wallet by clicking on the ‘Write’ button.&#x20;
* You are now able to view the details of your transaction by clicking on the ‘View your transaction’ button.&#x20;
