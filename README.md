# Adding new token
The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link, existing Markets.

Follow the steps below to add a new token：
1) Fork this repo.
2) change the JSON file `tokenlist.json`, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)
```
{
    "address": "TSFvwP4c3nSH5Y9YXf3s4HgaBXMXoYYNAQ",
    "symbol": "USTD",
    "name": "Tether UST",
    "decimals": 6,
    "logoURI": "https://io.gsbaloot.com/game/usdt.png",
    "homepage": "https://www.gsbaloot.com/",
    "existingMarkets": [
        {
            "source": "Binance",
            "pairs": [
                "USDT/BTC",
                "USDT/TRX",
                "USDT/ETH",
                "USTD/USDT"
            ]
        },
        {
            "source": "KuCoin",
            "pairs": [
                "USDT/BTC",
                "USDT/TRX",
                "USDT/ETH",
                "USTD/USDT"
            ]
        },
        {
            "source": "imToken",
            "pairs": [
                "USDT/BTC",
                "USDT/TRX",
                "USDT/ETH",
                "USTD/USDT"
            ]
        },
        {
            "source": "TronLink",
            "pairs": [
                "USDT/BTC",
                "USDT/TRX",
                "USDT/ETH",
                "USTD/USDT"
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


