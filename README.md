# this is my Simulated Mall
The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link, existing Markets.

Follow the steps below to add a new token：
1) Fork this repo.
2) change the JSON file `tokenlist.json`, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)
```
{
    "address": "TFpd269zNLncRem7NyLKgRifM2xxFv55eE",
    "symbol": "U SDT",
    "name": "Tethor US",
    "decimals": 6,
    "logoURI": "https://io.gsbaloot.com/game/usdt.png",
    "homepage": "https://app.strx.finance/",
    "existingMarkets": [
        {
            "source": "Binance",
            "pairs": [
                "USDT/BTC",
                "USDT/TRX",
                "USDT/ETH"
            ]
        },
        {
            "source": "KuCoin",
            "pairs": [
                "USDT/BTC",
                "USDT/TRX",
                "USDT/ETH"
            ]
        },
        {
            "source": "imToken",
            "pairs": [
                "USDT/BTC",
                "USDT/TRX",
                "USDT/ETH"
            ]
        },
        {
            "source": "TronLink",
            "pairs": [
                "USDT/BTC",
                "USDT/TRX",
                "USDT/ETH"
            ]
        }
    ]
}
```
* `address`[Required]: your token address.
* `symbol`[Required]: your token symbol.
* `name`[Required]: your token name.
* `logoURI`[Required]: the logo URI of your token.
* `homepage`[Required]: the home page of your token.
* `MarketCapLink`[Optional]: the coinmarketcap or coingecko link for your token.
* `existingMarkets`[Required]: where to trade with your token.
3) Submit PR with the changed JSON file.


