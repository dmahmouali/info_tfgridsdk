# Getting started

## Before you Start
To get your workloads up and running you will need to meet a few prerequisites.
All of them are pretty straight forward and you be able to start your journey shortly.

In short you need to have the following items done before you can proceed:
- First you need to get yourself a **3bot.connect** identity.  This can be done by getting an app and creating yourself an identity.  Please be aware that this is to be your digital indentity on the grid.  The app provides you with access to  ThreeFold sociall media platforms has a wallet for managing TFT's and provides support access.  The app can be found on the google play store and apple app store.
- The you can install and the jumpscale SDK (and get access to it by your 3bot.connect).  The jumpscale SDK is available for local install and will be available for grid deployment (with secure web access).  For local installations we use docker container technology to run the SDK software locally.  Going forward we recommend to move to the TF Grid based version as this will provide you access from all web browsers on any device.
- Last you will need TFT tokens in your 3bot.connect app. There are two type of token available (2020 H1):  FreeTFT's and TFT's. The free TFT's are meant for developers and interested parties to testdrive the TF grid.  





## 3Bot Connect App

<!--- original content: https://github.com/threefoldfoundation/info_threefold/tree/development/src/docs/token/apps_wallets --->


3Bot is a revolutionary digital avatar that will execute your digital needs. It is an unprecedented leap in digital privacy and comes with all the functionalities you need to interact and exchange on the new Internet. With 3Bot, everything changes.

Follow the steps below to set up your 3Bot Connect wallet, and receive and send your first ThreeFold Tokens:

### Step 1: Download
  Download 3Bot from [3Bot.org website](https://3bot.org/3bot.html)

### Step 2: Registration and login
  
To use the 3Bot Connect App you simply need to download the 3Bot Connect App available in the Appstore or Google Play Store. Folow the steps and register using your email address.

### Step 3: Save the seed phrase in a safe place.

In the future, it may help to restore your wallet in case your devise is lost.

<!-- 
![3bot](img/3bot_seed_phrase.jpg)
-->
<img src="img/3bot_seed_phrase.jpg" alt="drawing" width="200"/>
<!--
TODO #8 See if we can change the seed phrase screenshot into a nices / smaller one
-->

The seed Phrase allows you to access and recover your 3bot on any device. We highly recommend to write down your seed key on a paper and store it safely offline. The seed phrase is the only "key" to your 3bot and 3bot assets (not only digital currency but also all of the reservations, deployments and data storage on the P2P cloud)

A few very important things to remember you 

- **3Bot does not have any access to or maintain records of your private key. It is your personal responsibility to keep your 24-word private key in a safe place.**
- **Do not share your private key with anyone, it is strictly personal. Losing your private key means losing access to your wallet and all your ThreeFold Tokens.**
- **Anybody with access to your private key can take ownership of your 3Bot Connect wallet and ThreeFold tokens**
- **To access your wallet from another wallet (on another phone or online) you will need your private key (seed), without this private key your account cannot be recovered on another device or online wallet.**

Finish this steps and choose your new pin, then confirm it and confirm your e-mail adress.

For more explanation about the 3bot app workings please find it [here](3bot_connect_app.md)


## Installing The ThreeFold SDK
The Jumpscale SDK is the interface where you get acces to different ways to build and deploy digital services on the peer2peer grid.  There will be a grid hosted version available soon, but for now we need to have the SDK installed on a local OS
<!--
TODO #7: Get an idea about then the Jumpscale SDK is to be released as an flist on the grid.
-->

Local installation instructions can be found here:

- [Installing The SDK For MacOS](sdk_macos.md)
- [Installing The SDK For Linux](sdk_linux.md)
- [Installing The SDK For Windows*](sdk_windows.md)

**Available Soon*