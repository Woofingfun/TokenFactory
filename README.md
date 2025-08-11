# Jace TokenFactory

```bash
# A decentralized token creation platform on Binance Smart Chain (BSC)
# Create, manage, and explore tokens with a hacker-style interface
# Powered by BSC | Contract: 0x2D71ba45c6E88b9F819ebD93a263594dABfFF6B6

# Why Jace TokenFactory?
# - Low gas fees on BSC
# - Secure token creation with metadata support
# - Terminal aesthetic for the cyberpunk coder in you

{
  "connectWallet": "Link MetaMask to BSC (chain ID: 56)",
  "createToken": "Mint new tokens with name, symbol, and 100T premine",
  "fetchMyTokens": "List up to 100 tokens created by your address",
  "fetchAllTokens": "Explore the latest 100 tokens on the platform",
  "ui": "Hacker-style interface with matrix background and VT323 font",
  "network": "Binance Smart Chain (BSC) for fast, cheap transactions"
}

# Ensure you have the following:
- MetaMask installed (https://metamask.io)
- BNB in your wallet for gas fees
- A modern browser (Chrome, Firefox, etc.)
- Node.js for local server (optional, for development)

# Clone the repo
git clone https://github.com/<your-username>/jace-tokenfactory.git
cd jace-tokenfactory

# Install dependencies (if using a local server)
npm install

# Run a local server
npx serve

# Open http://localhost:3000 (or your hosted URL) in a browser

# Click "> Connect Wallet"
# Switch MetaMask to BSC (chain ID: 56)
# Ensure BNB balance for gas

# Enter token name (e.g., "JaceCoin") and symbol (e.g., "JACE")
# Click "> Create Token"
# Confirm transaction in MetaMask
# View token address on BscScan

# Click "> Fetch My Tokens" to see your created tokens
# Click "> Fetch Latest Tokens" to explore platform tokens

# Click "> Copy" next to any token address
# Paste into BscScan or your wallet

// TokenFactory Contract
address: 0x2D71ba45c6E88b9F819ebD93a263594dABfFF6B6
network: Binance Smart Chain (BSC)
abi: Available in index.html (tokenFactoryABI, tokenABI)

const bsc = {
  chainId: 56,
  name: 'Binance Smart Chain',
  explorerUrl: 'https://bscscan.com',
  rpcUrl: 'https://bsc-dataseed.binance.org/'
};
