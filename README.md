
# ** Pancakewwap Prediction v3.0.1 Bot (Update Jul, 2022)

![PancakeSwap-Logo-Big](https://github.com/parames3010/PancakeswapPredictionBot-2022/blob/main/pancake.png)
<p align="center">
  <a href="https://github.com/parames3010/PancakeswapPredictionBot-2022/releases">
    <img alt="GitHub all releases" src="https://img.shields.io/github/followers/parames3010?style=social">
  </a>
  <a href="https://github.com/parames3010/PancakeswapPredictionBot-2022">
    <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/stars/parames3010/PancakeswapPredictionBot-2022?style=social">
  </a>
   <a href="https://github.com/parames3010/PancakeswapPredictionBot-2022">
    <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/forks/parames3010/PancakeswapPredictionBot-2022?style=social">
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=PancakeSwap">
    <img src="https://img.shields.io/twitter/follow/PancakeSwap?style=social" alt="Follow @PancakeSwap" />
  </a>

This bot wins majority of rounds on PancakeSwap & CandleGenie based on both market conditions, and the strategy chosen.

## Installation

Download & Install Node here :
https://nodejs.org/en/download/

Then run command prompt or powershell

- Type ``cd PancakeswapPredictionBot2.0.1`` (replace with your cloned/downloaded bot folder)
- Type ``npm i``

## Usage

1. Copy/rename **.env_example** to **.env** ``cp .env_example .env``
2. Provide your private key to .env PRIVATE_KEY field.
3. Install dependencies `npm i` or `yarn` if not already completed above.
4. Start the bot using `npm run start -- --with` or `yarn start -- --with`
5. Enjoy!

### 🦊 How to Export Private Key from MetaMask
1. Open your account
2. Click on three points at top-right corner
3. Account details
4. Export Private Key.

### ✔️ Sample ``.ENV`` file 
```
# Your wallet private key.
PRIVATE_KEY="YOUR_PRIVATE_KEY_HERE"
# The maximum bet amount you are willing to execute.
BET_AMOUNT="0.01"
# RPC is the default network for Ether transactions. For Binance Smart Chain, leave it as it is.
RPC="https://bsc-dataseed.binance.org/"
```

## Screenshots

To check history of the rounds you played, head over to: https://pancakeswap.finance/prediction 

![History](https://user-images.githubusercontent.com/37302442/142716425-eb32f875-a767-4f22-abf1-6d97071dbd6d.png)

Running this bot for a day had made me $55 with minimum bets. Please note I was actively monitoring the market as the bot was running.

![History_2](https://user-images.githubusercontent.com/37302442/142724431-48a7c301-ee59-4485-9733-3ee5a0303c00.PNG)

#### Advice:
  
- Run the bot with your wallet at a ratio of 10x the amount you choose to bet
- Adjust the bot accordingly to bet with or against the majority.
- When the chart swings, use the "--with" strategy.
- When the chart trends sideways, use the default, against strategy. 
- Always monitor & adjust the bot accordingly but allow room for error.
- Consistent gains will be made by running smaller betting amounts over longer periods of time. 
- Always account & allow room for error. Losing 3 sucks, but stopping it only prevents it from potentially winning the next 4 & bringing you to a profit. 
- Majority of the runs with over 2k plays I have a standard 54-66% win rate depending on how well I monitor it & based on market conditions.
  

## License 
 
MIT License
  
## Donate

BOT is free-to-use, but you are welcome to appreciate my work ☺️

ETH - 0xEC783330cf7bD08D97a187078635385B066452a7

BNB - 0xEC783330cf7bD08D97a187078635385B066452a7  

## Disclaimers
  
All investment strategies and investments involve risk of loss.

**Nothing contained in this program, scripts, code or repository should be construed as investment advice.**
Any reference to an investment's past or potential performance is not, and should not be construed as, a recommendation or as a guarantee of any specific outcome or profit. By using this program you accept all liabilities, and that no claims can be made against the developers or others connected with the program.
   
## 📧 Contact
 
- khan62482@gmail.com
