# this is my Simulated Mall

The JSON schema for the tokens includes: address, name, decimals, symbol, logoURI, official homepage, MarketCap link,
existing Markets.

Follow the steps below to add a new token：

1) Fork this repo.
2) change the JSON file `tokenlist.json`, adding such as: (PLEASE DO NOT REMOVE EXISITING TOKENS)

```
{
    "address": "TLGPtTVYqFer9Ci9djvPuuhphPXUMnHLYY",
    "symbol": "GS",
    "name": "GoldShark",
    "decimals": 8,
    "logoURI": "https://static.tronscan.org/production/upload/logo/new/TLGPtTVYqFer9Ci9djvPuuhphPXUMnHLYY.png",
    "homepage": "https://app.strx.finance/",
    "existingMarkets": [
        {
            "source": "Binance",
            "pairs": [
                "GS/USDT",
                "GS/BTC",
                "GS/TRX",
                "GS/ETH"
            ]
        },
        {
            "source": "KuCoin",
            "pairs": [
                "GS/USDT",
                "GS/BTC",
                "GS/TRX",
                "GS/ETH"
            ]
        },
        {
            "source": "imToken",
            "pairs": [
                "GS/USDT",
                "GS/BTC",
                "GS/TRX",
                "GS/ETH"
            ]
        },
        {
            "source": "TronLink",
            "pairs": [
                "GS/USDT",
                "GS/BTC",
                "GS/TRX",
                "GS/ETH"
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


