# Fix Pending Transactions

While using MetaMask to make transactions, you may be confronted with a pending transaction that is stuck, and the ‘cancel’ button not working. In this case you can use the following method to fix the issue. Note that using this method, a transaction with higher priority is overwriting the stuck transaction so that the backlog is cleared.&#x20;

### **1. Enable Customized Transaction Nonce**

* Open MetaMask browser extension.&#x20;
* On the top right corner, click on the circle and go to **Settings**. &#x20;
* Select **Advanced Settings** under Settings.&#x20;
* Find **Advanced Gas Controls** and toggle it to **ON**.
* Scroll down to find **Customized Transaction Nonce** in the same menu and toggle this to **ON** as well.

### **2. Find the Stuck Transaction**

In this step, you need to find the nonce related to the transaction that is stuck. The nonce is a kind of identification number which is used later.&#x20;

* Go to MetaMask’s main screen and under the **Assets** tab, select the token the transaction of which is stuck.&#x20;
* Find your **pending transaction** from the list of transactions related to that token. Once you’ve found it, click on it to see more details.&#x20;
* Note down the number written in front of **Nonce** so that you can use it later.&#x20;

### **3. Overwrite the Stuck Transaction**

The next step is to perform a new transaction so that the previous one is overwritten. For the new transaction, the nonce number will be changed to the one you have already written down in the previous step.&#x20;

* You need to create a new transaction so that the older stuck transaction is replaced. However, it is suggested that you increase the amount of **transaction fee (Gas Price)** for the new transaction so that the possibility of the transaction being added to a block is increased.&#x20;
* Prior to confirming the transaction, double-check that the **Gas Price** for the new transaction is higher compared to the previous one.&#x20;
* Change the number of **CUSTOM NONCE** to the one you’ve noted down in the previous step. Click on the **Confirm** button.&#x20;
* Now you can check the **Activity** tab in MetaMask to see if your transaction is accepted to a block or not.&#x20;
* In case the transaction is completed, you are able to see that on top of other transactions under the **Activity** tab. If the transaction is still ‘pending’ you probably need to wait a little longer. If the transaction is taking too long you may have to go through the above process for a second time and try again with a higher transaction fee.&#x20;

As it is not possible for wallets to make transactions with the same nonce, the new transaction will replace the previous stuck transaction if it’s completed successfully.&#x20;
