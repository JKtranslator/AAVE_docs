# AAVE V3 features

## V3 Markets

![](https://i.imgur.com/4u5Rjo0.gif)

The user can access the V3 Markets in the dropbox selection. After the selection, the page will load the assets available for supplying and borrowing in this specific market.
This section will focus on the new features that the V3 Markets introduced. To check how to supply or borrow an asset, please check the [**landing page walkthrough**](https://github.com/JKtranslator/AAVE_docs/blob/main/landing%20page.md)

## Isolation Mode

New assets can be listed as isolated in Aave protocol V3. Borrowers supplying an isolated asset as collateral cannot use other assets as collateral (though they can still provide it to the protocol to receive yield).

### How to enter isolation mode

![](https://i.imgur.com/cGXl8PB.gif)

To enter into isolation mode, the user must supply the asset to the protocol and activate it as collateral, clicking on the toggle and enabling it on the popup. 

After the isolation mode is activated, no other asset can be added as collateral, and the list of assets available for borrowing is also updated.

### How to exit isolation mode

![](https://i.imgur.com/zUdDmwi.gif)

Click the slider button to disable the isolated asset to exit isolation mode from the **Your Supplies** section. Now all other assets are available again.

## Efficiency Mode (E-mode)

The E-mode feature maximizes capital efficiency when collateral and borrowed assets have correlated prices. For example, DAI, USDC, USDT are all stablecoins pegged to USD. These stablecoins are all within the same E-mode category. Accordingly, a user supplying DAI in E-mode will have higher collateralization power when borrowing assets like USDC or USDT. 
Only assets of the same category (for example stablecoins) can be used as collateral and be borrowed in E-mode. 

### How to enter E-mode

![](https://i.imgur.com/yuAKmmN.gif)

To enter E-mode from the dashboard, the user must go to the dropdown menu under **Your Borrows**, where will find an "Enable E-mode" button. Initially, the switch to enable E-mode will indicate that E-mode is "disabled." Next, click "Enable E-mode" and follow the instructions in the popup. Once all the steps are done, the user will have enhanced borrowing power (i.e., up to 97.5% LTV) within E-mode. Only assets within the same category can be borrowed (for example, stablecoins).

![](https://i.imgur.com/HED4aGI.gif)

Obs: The E-mode can be enabled even if the isolation mode is actived.

![](https://i.imgur.com/d0yrI9z.gif)


### How to exit E-mode

![](https://i.imgur.com/sbEyB3f.gif)

To exit E-mode and enable different assets to borrow, the borrowed power used can't be higher than the standard mode threshold. The system won't let the user disable the eMode, as this action would lead to an instant liquidation of the loan. Therefore, the user must bring the borrowed power to a value under the threshold for the option to be enabled on the popup.

![](https://i.imgur.com/3kjvxCu.gif)

After successfully exiting the E-mode, the other assets are now available for borrowing.


## Multiple rewards

AAVE V3 introduced the possibility of different tokens being added as rewards to incentivize actions inside the market.

![](https://i.imgur.com/2efkmsv.gif)

When the market has these rewards, they are shown on the **APY** column on the **Supply** and **Borrow** sections. To claim the rewards accrued, the user needs to click on the **Claim** button on the **Available rewards section**. Then, the contract will send them directly to the user's wallet.

![](https://i.imgur.com/5lgJMGv.png)
