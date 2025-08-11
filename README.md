# Jace TokenFactory

```bash
# Decentralized token creator on Binance Smart Chain (BSC)
# Build tokens, hack the vibe
# Contract: 0x2D71ba45c6E88b9F819ebD93a263594dABfFF6B6
```

## > Mission

Jace TokenFactory: a terminal-style DApp to mint tokens on BSC (chain ID: 56). Cyberpunk UI, fast, secure.
- Connect MetaMask to BSC.
- Create tokens (name, symbol, 100T premine).
- List your tokens or latest 100 on platform.
- Matrix animations, VT323 font.

```bash
# Why this?
# - BSC = low gas
# - Secure minting + metadata
# - Hacker aesthetic
```

## > Setup

```bash
# Need:
- MetaMask (metamask.io)
- BNB for gas
- Browser (Chrome/Firefox)
- Node.js (optional, dev)

# Clone
git clone https://github.com/YOUR_USERNAME/jace-tokenfactory.git
cd jace-tokenfactory

# Install
npm install

# Run
npx serve
```

## > How to Use

1. **Open DApp**:
   ```bash
   # Visit http://localhost:3000
   ```

2. **Connect**:
   ```bash
   # Click "> Connect Wallet"
   # Set MetaMask to BSC (chain ID: 56)
   # Got BNB? Good.
   ```

3. **Mint Token**:
   ```bash
   # Input name (e.g., "JaceCoin"), symbol (e.g., "JACE")
   # Click "> Create Token"
   # Sign in MetaMask
   # Check BscScan
   ```

4. **View Tokens**:
   ```bash
   # "> Fetch My Tokens" for yours
   # "> Fetch Latest Tokens" for all
   ```

5. **Copy**:
   ```bash
   # Click "> Copy" for token address
   ```

## > Contract

```solidity
// TokenFactory
address: 0x2D71ba45c6E88b9F819ebD93a263594dABfFF6B6
network: BSC
abi: In index.html
```

Verify: [BscScan](https://bscscan.com/address/0x2D71ba45c6E88b9F819ebD93a263594dABfFF6B6)

## > Config

```javascript
const bsc = {
  chainId: 56,
  name: "Binance Smart Chain",
  explorerUrl: "https://bscscan.com",
  rpcUrl: "https://bsc-dataseed.binance.org/"
};
```

## > Dev

```bash
# Edit index.html
# VT323 font = terminal vibe
# Matrix bg in canvas
# Alt RPCs:
# - https://bsc-dataseed1.ninicoin.io/
# - https://bsc-dataseed2.defibit.io/
```

## > Debug

```bash
# Wallet dead?
> Check MetaMask, BSC setup, BNB balance

# Mint failed?
> Need more BNB
> Console for errors

# RPC down?
> Try alt RPCs
> https://docs.bscscan.com/misc-tools-and-utilities/public-rpc-nodes
```

## > Security

```bash
# Verify contract on BscScan
# Keep keys safe
# Gas: 0.01-0.1 BNB
# Testnet (chain ID: 97) for practice
```

## > Contribute

```bash
# Fork it
# Branch
git checkout -b feature/your-stuff
# Commit
git commit -m "New stuff"
# Push
git push origin feature/your-stuff
```

## > License

```bash
# MIT License
# (c) 2025 Jace TokenFactory
```

## > Contact

```bash
# Bugs: GitHub issues
# Ideas: DM @YOUR_TWITTER
# Chat: t.me/YOUR_TELEGRAM
```

```bash
# Code. Mint. Hack.
# Jace TokenFactory © 2025
```
```

---

### Instructions
- **Copy**: Select all, copy, paste into your GitHub repo's `README.md`.
- **Edit**:
  - Replace `YOUR_USERNAME` with your GitHub username.
  - Swap `@YOUR_TWITTER` and `t.me/YOUR_TELEGRAM` with your actual handles, or delete if not applicable.
- **Preview**: GitHub renders it with code blocks and hacker style.
- **Optional**: Add a screenshot with `![UI](screenshots/ui.png)` after uploading an image to your repo.

This is the one file, trimmed down, hacker vibe intact. If it’s still not what you need, tell me exactly what’s off, and I’ll fix it!
