# Pump.fun Trading bot using the PumpPortal API

PumpPortal Trading Bot is an automated trading tool designed for cryptocurrency enthusiasts. This bot allows users to create wallets, set up trading parameters, and execute automated buying and selling strategies on the PumpPortal platform.

Download: [release page](https://github.com/Some1private/pumpfunbot/releases).

## Features

- Create multiple wallets automatically
- Set contract addresses for trading
- Configure trading parameters (slippage, priority fee, buy amount, buy interval, number of buys)
- Automated buying of tokens
- Sell tokens from all wallets simultaneously
- Load and save wallet information
- Real-time logging of trading activities

## Documentation

### Getting Started

1. Launch the application
2. Create wallets or load existing ones
3. Set contract addresses for trading
4. Configure trading parameters
5. Start automated buying
6. Monitor the process through the log display
7. Stop buying when desired
8. Sell tokens from all wallets if needed

### Wallet Management

- **Create Wallets**: Enter the number of wallets you want to create and click "Create Wallets"
- **Load Wallets**: Click "Load Wallets from File" to import existing wallet information
- **Download Wallet Info**: After creating or loading wallets, you can save the wallet information by clicking "Download Wallet Info"

### Trading Configuration

- **Set Contracts**: Enter comma-separated contract addresses and click "Set Contracts"
- **Set Parameters**: Fill in the following fields and click "Set Parameters":
  - Slippage (%)
  - Priority Fee
  - Buy Amount (SOL)
  - Buy Interval (seconds)
  - Number of buys per wallet

### Trading Operations

- **Start Automated Buying**: Click "Start Automated Buying" to begin the trading process
- **Stop Automated Buying**: Click "Stop Automated Buying" to halt the process
- **Sell from All Wallets**: Click "Sell from All Wallets" to liquidate all bought tokens

## FAQ

Q: How many wallets can I create?
A: You can create as many wallets as you need.

Q: Can I use my existing wallets?
A: Yes, you can load existing wallet information using the "Load Wallets from File" feature. 

Q: Is there a limit to how many contract addresses I can set?
A: There's no hard limit, but it's recommended to keep the number manageable for optimal performance.

Q: What happens if I stop the automated buying process?
A: The bot will complete the current buy operation and then halt. You can resume by clicking "Start Automated Buying" again.

Q: Can I sell tokens from specific wallets only?
A: Currently, the "Sell from All Wallets" feature sells from all wallets that have bought tokens. Individual wallet selling is not supported in this version.

Q: How can I monitor the bot's activities?
A: All activities are logged in real-time in the log display within the application.

Q: Is my wallet information secure?
A: The application handles wallet information locally on your machine. Always ensure you're running the application in a secure environment.

For more information or support, please contact @elijahxz on telegram.
