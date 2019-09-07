# DashD_MN
Dash Diamond MN setup

# Step 1

1. Create account address - use a label such as Masternode1
2. Send 1,000 DASHD to the address you created
3. Wait approximately 1 minute and open the debug console under the Tools menu
4. Enter - ```masternode genkey``` - save this for later, you'll need it
5. Enter -  ```masternode outputs```
6. Save your TX and INDEX number from masternode outputs command
7. Close the wallet

# Step 2

1. SSH to your VPS and enter the following command
```
cd && sudo apt-get -y install git && sudo git clone https://github.com/DashDiamond/DashD_MN.git && cd DashD_MN/ && sudo bash dashd-mn.sh
```
2. Enter ```y``` to install dependencies, and ```y``` again to install the wallet

# Step 3

1. Start your wallet again
2. Open the masternode config file from the Tools menu and follow the example lines to add your new masternode (without the #), using your information
3. Save the file and restart your wallet
4. After the transaction to your address has 16 confirmations, you may go to the masternodes tab and start the masternode!
5. Profit
