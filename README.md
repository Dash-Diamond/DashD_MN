# DashDiamond Masternode
Dash Diamond MN setup

# Step 1

1. Create account address - use a label such as Masternode1
2. Send DASHD collateral amount to the address you created(Check reward table and match with explorer blocks to know about current collateral amount or check MNO directly)
***MNO: https://masternodes.online/currencies/DASHD***
3. Wait approximately 1 minute and open the debug console under the Tools menu
4. Enter - ```createmasternodekey``` - save this for later, you'll need it
5. Enter -  ```getmasternodeoutputs```
6. Save your TX and INDEX number from ``getmasternodeoutputs`` command
7. Close the wallet

# Step 2

# MasternodeSetup
DashDiamond masternode setup

<img src="https://i.imgur.com/FfYCYOu.png"  alt="DASHD SPECIFICATIONS">

### Required:

1. DashDiamond(DASHD) for Collateral <br>
(You can buy DASHD from exchange for collateral) <br>
***•https://dex.heliobank.net/market/BIRAKE.DASHD_BIRAKE.BTC <br>
•https://crex24.com/exchange/DASHD-BTC <br>
•https://graviex.net/markets/dashdbtc <br>
•https://graviex.net/markets/dashdeth <br>***
Also you can check MNO to know more details:
***https://masternodes.online/currencies/DASHD***

2. Download Local Wallet for your operating system: : https://github.com/Dash-Diamond/DASHD/releases

Reward structure:
<img src="https://i.imgur.com/cKCS5Co.png" alt="DASHD Reward Structure">

3. You will need also VPS with Ubuntu 16.04 or 18.04

**VPS WALLET:**

To install Dashdiamond(DASHD) Masternode use the following command:

`bash <( curl -sL https://raw.githubusercontent.com/Dash-Diamond/MasternodeSetup/master/dashd-masternode-install.sh)`

- Enjoy

check your masternode status using `dashdiamond-cli getmasternodestatus` after run it from local wallet

If you still facing any issues then join our <a href="https://discordapp.com/invite/JWkvmNyNgc">Discord server</a> for support, We available 24 hour for support you.


# Step 3

1. Start your wallet again
2. Open the masternode config file from the Tools menu and follow the example lines to add your new masternode (without the #), using your information
3. Save the file and restart your wallet
4. After the transaction to your address has 16 confirmations, you may go to the masternodes tab and start the masternode!
5. Done
