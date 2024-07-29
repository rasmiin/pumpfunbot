## Pump.fun Trading Automation Bot

Welcome to the Pump.fun Trading Automation Bot! This advanced bot automates the buying and selling of pump.fun tokens, acting as a fully automated sniper bot designed for pump.fun tokens. It allows to snipe tokens early and sell them using a take-profit strategy.


### Sniping Capabilities

bot snipes every token and allows to apply filters such as:
- Tokens with social media presence
- Reply/comments count
- Tokens from specific creator wallets

### How to Run
**Setup Config:**
   Navigate to the release directory and setup the config.json file:
   
      ```sh   
         {
          "privateKey": "Your Private Key",
          "APIKey": "Leave it blank",
          "autoSellTimeout": "sell automatically after n seconds",
          "maxInitialBuy": "dev max holding amount (in sol)",
          "minInitialBuy": "dev min holding amount (in sol)",
          "pendingTradesLimit": "Trades limit to run at a time",
          "takeProfit": "target percentage",
          "stopLoss": "Stop loss percantage",
          "buyAmount": "amount (min 0.5 sol recommanded)",
          "sellAmount": "100% (Sell amount in percent or you can use fix amount)",
          "buySlippage": "Slippage during buy transactions. min 20 recommanded",
          "sellSlippage": "Slippage during sell transactions. min 50 recommanded",
          "buyFee": "Priority fee during buy transactions. min 0.005 recommanded",
          "sellFee": "Priority fee during sell transactions. min 0.005 recommanded",
        }

   **Start the Bot:**
   Run the bot using pumpfunbot.exe

### Contact
If you're interested in acquiring the Pump.fun bot, need the archive password, or have any questions, please contact us through the following channels:

- Telegram: [https://t.me/devalexio](https://t.me/devalexio)


### Bot Capabilities:
The bot functions like a token sniper with preset rules and customizable options for nearly every aspect of trading.

- Monitors and tracks new tokens.
- Executes buys.
- Executes sells.
- (Sniper Mode) Super Instant mode for buys without any delay of newly launched tokens.

### YouTube Demo
Watch demo video for a comprehensive overview of the bot in action:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/J9x8PbjrW2E/0.jpg)](https://www.youtube.com/watch?v=J9x8PbjrW2E)




### Telegram Bot
   I have implemented the same functionalty with telegram bot - [https://t.me/solcapturebot](https://t.me/solcapturebot)
