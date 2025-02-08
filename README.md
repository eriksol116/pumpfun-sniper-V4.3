# 🤖Pumpfun Sniper Bot V4.3

A Pump Fun sniper detects all liquidity pools launched on the platform in Dex.

You can snipe and buy pumpfun token that created by dev wallet using this bot.


## CONTACT INFO

-discord:  erikerik116

-telegram: @erikerik116

## GETTING STARTED

1. Clone repository

    ```
    git clone https://github.com/eriksol116/pumpfun-sniper-V4.3

    cd pumpfun-sniper-V4.3
    ```


2. Install dependencies

    ```
    npm install
    ```
3. Configure the environment variables

    Rename the .env.example file to .env and set RPC and WSS, main keypair's secret key, and others.

4. Run the bot

    ```
    npm run start
    ```


## SETTING ENV FILE

You can set the .env like following:

PRIVATE_KEY =
    Your main wallet private key

RPC_ENDPOINT = 

RPC_WEBSOCKET_ENDPOINT=

BUY_AMOUNT = 
    buy sol amount

JITO_FEE = 0.0001
    jito fee

PRICE_CHECK_INTERVAL (ms) :
   Interval in milliseconds for checking the take profit and stop loss conditions
   Set to zero to disable take profit and stop loss.

TAKE_PROFIT : x %

STOP_LOSS : x  %

SELL_SLIPPAGE : x %

SKIP_SELLING_IF_LOST_MORE_THAN : x %
   If token loses more than X% of value, bot will not try to sell

PRICE_CHECK_DURATION (ms) : x %
   Time in milliseconds to wait for stop loss/take profit conditions
   If you don't reach profit or loss bot will auto sell after this time
   Set to zero to disable take profit and stop loss

MAX_SELL_RETRIES - Maximum number of retries for selling a token

## Mention

This is public code for ad. So this dont have buy and sell functions with conditions.

If you want running bot, contact me.

## Record Video


https://github.com/user-attachments/assets/7a2a0b67-3222-47fd-9c58-8b68887e59d6




https://github.com/user-attachments/assets/ed9c1748-925f-4437-8a7d-ff3312c5b363


