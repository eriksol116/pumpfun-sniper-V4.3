# 🤖Pumpfun Dev Sniper 4.3

A Pump Fun sniper detects all liquidity pools launched on the platform in Dex.

You can snipe and buy pumpfun token that created by dev wallet using this bot.

If you use Next Block service, you can buy more quickly.

## CONTACT INFO

-discord:  erikerik116

-telegram: @erikerik116

## GETTING STARTED

1. Install dependencies

    ```
    npm install
    ```
2. Configure the environment variables

    Rename the .env.example file to .env and set RPC and WSS, main keypair's secret key, and others.

3. Run the bot

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

