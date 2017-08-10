
# CryptoTicker

Extension for Visual Studio Code -  Allows you to keep track of all the different crypto coin values in a currency you prefer on the status bar

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


 A representative screenshot:
<img src="https://raw.githubusercontent.com/udayankumar/cryptoticker/master/assets/screenshot.PNG">

## Disclaimer

Come with absolutely no guarantees. The code is my personal work and does not in any way represent my employer


## Credits 

Icon: https://www.flickr.com/photos/105644709@N08/10305978055/in/photostream/ 

Code: I used  https://github.com/roblourens/vscode-stocks as a template to build upon
