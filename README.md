# Assetlists

# Add Asset Details to StreamSwap
1. Add your asset details
```sh
{
    "image": "https://raw.githubusercontent.com/StreamSwapProtocol/assetlists/main/images/flix.svg",
    "denom": "ibc/CEE970BB3D26F4B907097B6B660489F13F3B0DA765B83CC7D9A0BC0CE220FA6F",
    "displayDenom": "FLIX",
    "decimals": 6
}
 ```

Note: By default, exponent will be 6 to override use below object
```sh
{
    "image": "https://raw.githubusercontent.com/StreamSwapProtocol/assetlists/main/images/tnkr.svg",
    "denom": "ibc/3A0A392E610A8D477851ABFEA74F3D828F36C015AB8E93B0FBB7566A6D13C4D6",
    "displayDenom": "TNKR",
    "coinDenom": "TNKR",
    "decimals": 12,
    "denom_units": [
      {
        "denom": "TNKR",
        "exponent": 12
      }
    ]
}
 ```

2. Commit and push to your fork for PR
