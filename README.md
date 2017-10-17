
# CryptoTicker

Extension for Visual Studio Code -  Allows you to keep track of all the different crypto coin values in a currency you prefer on the status bar. Now also allows selection of exchange for the prices.

## Features

Add as many Crypto coin symbols as you like to the status bar, and they will be updated every 60 seconds. Just set `cryptoticker.cryptoSymbols` to an array of crypto coin symbols to monitor. Example:

```json
"cryptoticker.cryptoSymbols": [
    "BTC",
    "ETH",
    "XMR"
    ],
       
```

One can change the default currency from `USD` to any currency using the standard TLA for them 

```json

"cryptoticker.cryptoCurrency" : "USD"
```


One can change the exchange used by using :

```json

"cryptoticker.cryptoExchange" : "Coinbase"
```

Supported options include : BTC38, BTCC, BTCE, BTER, Bit2C, Bitfinex, Bitstamp, Bittrex, CCEDK, Cexio, Coinbase, Coinfloor, Coinse, Coinsetter, Cryptopia, Cryptsy, Gatecoin, Gemini, HitBTC, Huobi, itBit, Kraken, LakeBTC, LocalBitcoins, MonetaGo, OKCoin, Poloniex, Yacuna, Yunbi, Yobit, Korbit, BitBay, BTCMarkets, QuadrigaCX, CoinCheck, BitSquare, Vaultoro, MercadoBitcoin, Unocoin, Bitso, BTCXIndia, Paymium, TheRockTrading, bitFlyer, Quoine, Luno, EtherDelta, Liqui, bitFlyerFX, BitMarket, LiveCoin, Coinone, Tidex, Bleutrade, EthexIndia
(basically any exchange supported by [cryptocompare.com](https://www.cryptocompare.com/api/#introduction))

```Note```: if a selected currency is not traded at the selected exchange, you will see `undefined` values 


 A representative screenshot:
<img src="https://raw.githubusercontent.com/udayankumar/cryptoticker/master/assets/screenshot.PNG">

## Disclaimer

Come with absolutely no guarantees. The code is my personal work and does not in any way represent my employer


## Credits 

Icon: https://www.flickr.com/photos/105644709@N08/10305978055/in/photostream/ 

Code: I used  https://github.com/roblourens/vscode-stocks as a template to build upon
