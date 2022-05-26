* Buy early gems with custom gas fee, slippage, amount.
* Auto approve token after buy.
* Sell buyed token with custom gas fee, slippage, amount.
* Sell token with your custom increasing profits, like 50%, 100%, 200%.


HOW TO RUN
* clone this repository
* ```$ npm install```
* edit your ```env.json```
* run ```node sniper.js```
```json
{
    "PRIVATE_KEY": "REPLACEME with your private key",
    "YOUR_ADDRESS": "REPLACEME with your address that will buy",
    "NODE": "https://bsc-dataseed.binance.org/",  //replace with another node or leave this one here 
    "TOKEN": "CONTRACTTOSNIPEADDRESSHERE", //replace with the contract address you wish to snipe 
    "INVESTMENT": "BNB OR ETHER VALUE HERE", //replace with the number with decimals such as 0.01 or 5.1 etc. The currency ETHER or BNB is determined by which node, if you use a BSC node you will be paying in BNB here
    "GASLIMIT": "1000000", //custom gas limit
    "GWEI": "5",
    "AUTOSELL": "TRUE",  //if true then the bot will detect profits and sell for you
    "AUTOSELLPERCENT": "110"  //set the % profit to sell at
}
```
