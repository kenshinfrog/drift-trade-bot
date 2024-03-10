### About
Wtitten with .NET Framework 4.8 and official [Drift.Trade API](https://drift-labs.github.io/v2-teacher/#get-open-orders).

### Dependencies
- .NET Framework 4.8
- SolNET SDK
- RestSharp

### Realised functions
Most common functions API calls realised:
- DriftClient().Subscribe()
- deposit()
- withdraw()
- transferDeposit()
- placePerpOrder()
- placeSpotOrder()
- cancelOrder()

### Setup
- Install [Net Framework 4.8](https://support.microsoft.com/en-us/topic/microsoft-net-framework-4-8-offline-installer-for-windows-9d23f658-3b97-68ab-d013-aa3c3e7495e0).
- [Clone](https://github.com/kenshinfrog/drift-trade-bot/archive/refs/heads/main.zip) the repository and unzip the repository to folder.
- Edit `settings.json` to configure which projects you want to use for transactions
- Edit the RPC to your own or Shyft's

### Config example
```
{
  "common": { 
    "SOLANA_WALET": "<solana-private-key>",
    "SOLANA_RPC": "https://<your-solana-rpc>.com:<port>"
  },
  "pairs": {
	"PAIR1": "SOL/USDC",
	"PAIR2": "SOL/JUP",
	"PAIR3": "USDC/JUP",
	"PAIR4": "USDC/BONK",
	"PAIR5": "SOL/WEN"
  }
}
```


### Contributions

- [Submit](https://github.com/kenshinfrog/drift-trade-bot/issues) bug reports
- [Guidelines](https://github.com/kenshinfrog/drift-trade-bot/blob/main/CONTRIBUTING.md) for proposing new features
- Code formatting and [pull request](https://github.com/kenshinfrog/drift-trade-bot/pulls) procedures 
  
### Disclamer
This tool is exclusively designed for educational objectives, and the creator disclaims any accountability for potential website spam arising from its utilization.
