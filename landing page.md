# Landing Page

![](https://i.imgur.com/CfmicbK.png)

The default landing page is your Dashboard. The buttons on the top menu give access to other pages and configurations.

## Configuration
![](https://i.imgur.com/aejOren.png)

On the right top corner, there are two buttons. The "cog" is a global settings menu where the user can change several configurations.

![](https://i.imgur.com/VCb6laO.png)

The other one shows the wallet currently connected with the website and the network where this wallet is. It also offers the option to copy the wallet address, view it on the block explorer, and disconnect the app from the wallet.  

# Dashboard

The first information available on the **Dashboard** main area is the wallet's current balance (net worth) and the APY of this position.
Below are two sections: **Your supplies** and **Your borrows.**

## Assets to supply Overview

The **Your supplies** section shows the assets available for deposit on AAVE markets. In addition, the user can deselect the "Show assets with 0 balance" filter to show only assets with a balance on the wallet connected.

![](https://i.imgur.com/l8TSh8O.gif)

### Information on each asset

Each asset row on this section shows the **Wallet balance** and the expected **APY** when supplying it to the protocol. In addition, there is also the information if this asset can be used as collateral for borrowing.

Two buttons trigger the actions available in this section: **Supply** and **Details**.

### Details

![](https://i.imgur.com/ndI34gm.png)

Clicking the **Details** button will lead to the asset's market page.

### Supply

![](https://i.imgur.com/2DK7n7Y.gif)

Clicking the **Supply** button will open a popup where the user can select the amount. If it is the first interaction with the protocol, and approval transaction will be necessary before the supply one.
After this step, the **Your Supplies** section will reflect this deposit.


## Your supplies Overview

![](https://i.imgur.com/lUlBviP.gif)

Here is an overview of the current assets supplied, the APY of the position, and a selector to enable/disable the asset as collateral.

![](https://i.imgur.com/0IoV16d.png)


Two buttons trigger the actions available in this section: **Withdraw** and **Swap**.

### Withdraw

![](https://i.imgur.com/kEFcIqo.gif)

The process of withdrawing is similar to the one of supplying the asset. Select the amount and confirm the transaction.

### Swap

![](https://i.imgur.com/J0jJAqM.gif)

The swap button enables the exchange of one asset for another, and this swapped asset is automatically supplied to the respective market.

## Assets to borrow Overview

Likewise the Supply section, two buttons trigger the actions available in this section: **Borrow** and **Details**.

![](https://i.imgur.com/8PKvCB2.png)

The borrow function is not enabled if the user doesn't provide any collateral asset.

![](https://i.imgur.com/lIHdDPM.png)

After depositing assets as collateral, the **borrow** button is enabled.

### Information on each asset

Each asset row on this section shows the amount **Available** for borrowing taking into account the collateral deposited. In addition, it also indicates the **APY, variable** and **APY, stable** rates for the borrow, where the first one changes due to the market conditions and the latter are the same over the loan duration. Not every asset has the **APY, stable** option.

### Details

![](https://i.imgur.com/ndI34gm.png)

Clicking the **Details** button will lead to the asset's market page.

### Borrow

![](https://i.imgur.com/w4FOEtp.gif)

Clicking the **Borrow** button will prompt a popup where the amount and type of rate can be selected.

## Your borrows Overview

![](https://i.imgur.com/K16e1YQ.png)

Here is an overview of the current **Debt**, the **APY** that must be paid for the position, and a selector where you can change the **APY type** of the loan. This section has two buttons: **Repay** and **Borrow**.

### Borrow

![](https://i.imgur.com/WPWc90H.gif)

The user can **borrow** more of the asset previously borrowed through this section. If the stable APY is available, it can be selected. When this type is chosen, the user must borrow an amount larger than the supplied as collateral.

### APY Type

![](https://i.imgur.com/gA0TuBC.gif)

The user can also switch the loan's APY type selecting the desired option and performing the transaction.

### Repay

![](https://i.imgur.com/pigZqKl.gif)

Clicking the **Repay** button will prompt a popup where the user can choose to repay the loan with the wallet balance or collateral available on the platform. The loan can be paid in full or partially. After the transaction is completed, the new overall position is shown on the dashboard.

## Summary

![](https://i.imgur.com/dYFSr4o.gif)


Every interaction the user has (supplying, borrowing, withdrawing, repaying, etc.) with the protocol changes his overall position. The summary shows the updated position for this market.
The user can check his **Net APY** and the **Health Factor** of the loan by clicking on the **risk details**.

![](https://i.imgur.com/lEzoGsQ.png)

On the popup, there is an explanation of the factors that lead to the loan's liquidation and its current status against the liquidation limits. In addition, the user can find every collateral available and its specific parameters for borrowing in the [risk parameters](https://docs.aave.com/risk/asset-risk/risk-parameters) section.
