# Trust Wallet Assets PR Submission Instructions

## ✅ Repository Created Successfully!

Your Trust Wallet assets repository has been created and populated:
**https://github.com/yomarfrancisco/trustwallet-assets**

## 🚀 Next Steps for Trust Wallet PR

### 1. Fork the Trust Wallet Assets Repository
Visit: https://github.com/trustwallet/assets
Click "Fork" to create your fork

### 2. Clone Your Fork
```bash
git clone https://github.com/yomarfrancisco/assets.git
cd assets
```

### 3. Copy BRICS Assets
```bash
# Copy the BRICS token assets to your fork
cp -r /Users/ygorfrancisco/buybrics/trustwallet-assets/blockchains/ethereum/assets/0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d/ blockchains/ethereum/assets/
```

### 4. Create PR Branch
```bash
git checkout -b add-brics-token
git add blockchains/ethereum/assets/0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d/
git commit -m "Add BRICS token assets

- Add BRICS Stablecoin (BRICS) token
- Contract: 0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d
- Chain: Ethereum Mainnet
- Type: ERC-20 Non-transferable Receipt Token
- Sovereign-backed yield-bearing stablecoin"
git push origin add-brics-token
```

### 5. Create Pull Request
- Go to: https://github.com/trustwallet/assets
- Click "Compare & pull request" for your branch
- Use the PR description from `PR_TEMPLATE.md`

## 📋 PR Description (Copy from PR_TEMPLATE.md)

```markdown
# Add BRICS Token Assets

## Token Information
- **Name:** BRICS Stablecoin
- **Symbol:** BRICS
- **Contract Address:** `0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d`
- **Chain:** Ethereum Mainnet (Chain ID: 1)
- **Decimals:** 6
- **Type:** ERC-20 Non-transferable Receipt Token

## Description
BRICS is a yield-bearing stablecoin backed by tokenized sovereign credit. It represents a new paradigm in stablecoin design, combining the stability of sovereign backing with the efficiency of blockchain technology.

## Files Added
- `blockchains/ethereum/assets/0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d/logo.png` - 256x256 PNG token logo
- `blockchains/ethereum/assets/0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d/info.json` - Token metadata and links

## Verification
- ✅ Contract verified on Etherscan: https://etherscan.io/token/0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d
- ✅ All metadata verified against deployed contract
- ✅ Logo converted from AVIF to PNG format as required
- ✅ Token name, symbol, and decimals match on-chain data

## Contact Information
- **Website:** https://www.brics.ninja
- **Email:** ygor@brics.ninja
- **Telegram:** @ygorOF
- **GitHub:** https://github.com/yomarfrancisco

## Fee Waiver Request
**Strategic Token Classification:** BRICS represents a sovereign-backed stablecoin initiative that contributes to the broader DeFi ecosystem and financial inclusion. As a strategic token with sovereign backing and full on-chain transparency, we request consideration for fee waiver to support broader adoption and integration.

## Checklist
- [x] Token contract is verified on Etherscan
- [x] Token metadata matches on-chain data
- [x] Logo is 256x256 PNG format
- [x] All links are valid and accessible
- [x] Token is active and functional
- [x] Fee waiver request included for strategic classification
```

## 🎯 Expected Outcome

Once approved, BRICS token will be available in:
- Trust Wallet
- MetaMask (via Trust Wallet integration)
- Other wallets that use Trust Wallet's asset list

## 📞 Contact for Questions
- **Email:** ygor@brics.ninja
- **Telegram:** @ygorOF

---

**Ready to submit!** All files are prepared and verified. 🚀
