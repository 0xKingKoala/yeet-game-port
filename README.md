# Yeet Game - Desktop Edition

A standalone desktop application for playing the Yeet game on Berachain with a built-in local wallet.


## 🚨 IMPORTANT - macOS Security Fix

If the app shows as **"damaged and can't be opened"**, run this command in Terminal:

```bash
xattr -c /Applications/<path to .app>
```

This removes the quarantine flag that macOS adds to downloaded apps. [Learn more →](https://discussions.apple.com/thread/253714860?answerId=257037956022&sortBy=rank#257037956022)


## Installation

1. Download the `Yeet Game.app` file
2. Drag the app to your Applications folder
3. **First Launch**:
   - Right-click the app and select "Open"
   - Click "Open" when macOS warns about an unidentified developer
   - This only needs to be done once

## Getting Started

### 1. Launch the App
When you first open the app, it will automatically:
- Generate a secure local wallet
- Display your wallet address in the Config section

### 2. Fund Your Wallet
- Send BERA tokens to your generated address
- The address is displayed in the Config section
- Click the address or "Copy" button to copy it to clipboard
- Your balance will update automatically (~5 seconds)

### 3. Configure "Yeet As" Address (REQUIRED)
Before you can play:
1. In the Config section, find "Yeet As Address"
2. Enter the address that will receive BGT emissions
3. This is required - the game won't work without it

## Wallet Management

### Viewing Your Wallet
- Your address is shown in the Config section (top of screen)
- Balance displays in BERA
- Click the address to copy it

### Withdrawing Funds
1. Click "Withdrawal" button (appears when balance > 0)
2. Enter recipient address
3. Enter amount to send
4. Confirm transaction

### Data Storage
Your wallet and settings are saved locally at:
- **macOS**: `~/Library/Application Support/game-v2-electron/`

## Important Security Notes

⚠️ **Your wallet private key is stored locally on your computer**
- Never share your private key files
- Back up the data folder if needed
- Losing these files means losing access to your wallet

## Troubleshooting

### App Won't Open
- Make sure you right-clicked and selected "Open" on first launch
- Check System Preferences > Security & Privacy
- Try moving the app to Applications folder first

### Can't See Balance
- Ensure you have an internet connection
- Wait 5-10 seconds for balance to update
- Check that you sent BERA to the correct address

### Transaction Failed
- Verify you have enough BERA for gas fees
- Check your internet connection
- Ensure "Yeet As" address is valid

### Reset Wallet (Advanced)
To completely reset and generate a new wallet:
1. Quit the app
2. Delete: `~/Library/Application Support/game-v2-electron/wallet.json`
3. Restart the app

## Network Information

- **Network**: Berachain Mainnet
- **Token**: BERA
- **Block Explorer**: https://berascan.com

---

**Note**: This is a local wallet application. Keep your computer secure and never share your wallet files with anyone.
