# How to claim your Cardano ITN rewards in Daedalus wallet

:exclamation::exclamation: **USE Daedalus Mainnet 2.0.0 or newer than 2.0.1** (expected 4th Aug 2020)

Daedalus is a Cardano native full-node wallet available to download at [https://daedaluswallet.io/en/download/](https://daedaluswallet.io/en/download/). Please note that version 2.0.1 has a bug preventing users from claiming their ITN rewards so make sure to use version 2.0.0 or higher than 2.0.1..


:bulb: **If your wallet contains rewards only check [step 5](#5-sending-funds-to-different-wallet)**

If you need to transfer your rewards into any different wallet and have no other funds there (rewards only) you will not be able to pay fees for the transaction as rewards can not be used for that.


**Daedalus Mainnet 2.0.0 direct download links - just for testing purposes**

Please note that Daedalus will force you to download latest version of the wallet after each run so the links below are just for a purpose we figure out how to run it without this update check. Current version **2.0.1 is not supporting ITN reward wallets.**

* MacOS - [https://update-cardano-mainnet.iohk.io/daedalus-2.0.0-mainnet-13980.pkg](https://update-cardano-mainnet.iohk.io/daedalus-2.0.0-mainnet-13980.pkg)
* Windows - [https://update-cardano-mainnet.iohk.io/daedalus-2.0.0-mainnet-13980.exe](https://update-cardano-mainnet.iohk.io/daedalus-2.0.0-mainnet-13980.exe)


**Contacts**
* Homepage: [https://lunarpool.io](https://lunarpool.io)
* Twitter: [@lunarpool_io](https://twitter.com/lunarpool_io)
* Telegram: [@lunarpool_io](https://t.me/lunarpool_io)
* Telegram group: [https://t.me/lunarpool](https://t.me/lunarpool)

## 1. Download and install
Download Daedalus wallet using the links at the top of the page or make sure you have **version 2.0.0 or newer than 2.0.1** downloaded or installed. Install the wallet like you would any other application on your computer.

Once installed, start Daedalus and keep it running until the initial synchronization is done. **This can take time** as this is a full-node wallet having whole Cardano chain download locally on your computer. Chain storage will consume aroung **5 GB** of your hard-drive space.

## 2. Restore your wallet

### 2.1. Click Restore button
When the wallet is fully synchronized you will have couple of button available, click **Restore** button.
![image](https://github.com/lunarpool/claim-itn-rewards/blob/master/files/01_Restore_Wallet.png)

### 2.2. Select Yoroi Incentivized Testnet wallet
If you have your 15 words seed select the option combination according to the image below and click **Continue** button. Even if you didn't use Yoroi feel free to use this option as well.
![image](https://github.com/lunarpool/claim-itn-rewards/blob/master/files/02_Yoroi_ITN.png)

### 2.3. Type in your Recovery Phrase
Find your 15 word Recovery Phrase (also known as Seed) and type the words in correct order into the box. Daedalus will automatically recognize the words and put them into cyan boxes. Click **Check recovery phrase** when finished.
![image](https://github.com/lunarpool/claim-itn-rewards/blob/master/files/03_Recovery_phrase.png)

### 2.4. Wallet name and spending password
Enter your wallet name, try to use a unique one so it can be easily identified among your wallets. Also enter your **spending password** into both boxes, this password must be entered whenever you want to send some ADA out of the wallet.
![image](https://github.com/lunarpool/claim-itn-rewards/blob/master/files/04_Wallet_Spending_Passwd.png)

### 2.5. Wallet restored
If all the above steps were successfull you should see following confirmation dialog. Click **Close** button.
![image](https://github.com/lunarpool/claim-itn-rewards/blob/master/files/05_Restored.png)

## 3. Synchronize transaction history
Daedalus will automatically start transaction history synchronization right after wallet recovery, you can check the progress in the wallet header. This could take a few minutes.
![image](https://github.com/lunarpool/claim-itn-rewards/blob/master/files/06_Sync_wait.png)

## 4. Finished - wallet balance
You should be able to see your wallet total balance which consist of both the amount of ADA you had in your wallet and the rewards you received during the ITN (Incentivized Testnet).

## 5. Sending funds to different wallet
As you know only Daedalus and Yoroi wallets were part of the November 2019 snapshot and therefore could participate in ITN, stake their ADA and get rewards. This means that there were a lot of people commonly holding their ADA in different wallets (e.g. AdaLite - with Ledger or Trezor) and moving them to Daedalus and Yoroi just for the snapshot and then back to their original wallet.

This could lead to a situation that the wallet balance consist only of rewards and no additional ADA holding. In this case you would not be able to send the rewards out of the wallet, because you want be able to pay for the transaction fee. To resolve that you have to send at least 1 ADA to your restored wallet and then send out whole wallet balance including the rewards to any other wallet.-

Following image shows a reward wallet that originally had ```1.096,738712 ADA``` rewards from ITN. To send the rewards to different wallet we sent in ```1 ADA``` and then whole balance to our paper wallet. This way you can pay the transaction fee for real ADA not rewards.
![image](https://github.com/lunarpool/claim-itn-rewards/blob/master/files/07_Withdraw.png)
