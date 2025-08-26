# Trust Wallet Assets PR Submission Guide

## 🎯 Ready for Submission

All files have been prepared for the Trust Wallet assets PR. Here's what you need to do:

## 📁 Files Prepared

```
trustwallet-assets/
├── README.md                           # Project overview and fee waiver request
├── PR_TEMPLATE.md                      # PR description template
├── SUBMISSION_GUIDE.md                 # This file
└── blockchains/
    └── ethereum/
        └── assets/
            └── 0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d/
                ├── logo.png            # 256x256 PNG token logo
                └── info.json           # Token metadata
```

## 🚀 GitHub PR Steps

### 1. Fork the Repository
```bash
# Fork https://github.com/trustwallet/assets
# Clone your fork locally
git clone https://github.com/YOUR_USERNAME/assets.git
cd assets
```

### 2. Copy Files
```bash
# Copy the prepared files to your local assets repo
cp -r /Users/ygorfrancisco/buybrics/trustwallet-assets/blockchains/ethereum/assets/0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d/ blockchains/ethereum/assets/
```

### 3. Create Branch and Commit
```bash
git checkout -b add-brics-token
git add blockchains/ethereum/assets/0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d/
git commit -m "Add BRICS token assets

- Add BRICS Stablecoin (BRICS) token
- Contract: 0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d
- Chain: Ethereum Mainnet
- Type: ERC-20 Non-transferable Receipt Token
- Sovereign-backed yield-bearing stablecoin"
```

### 4. Push and Create PR
```bash
git push origin add-brics-token
# Create PR on GitHub using the PR_TEMPLATE.md content
```

## 📋 PR Description

Use the content from `PR_TEMPLATE.md` as your PR description. Key points:

- **Token:** BRICS Stablecoin (BRICS)
- **Contract:** 0x9d82c77578FE4114ba55fAbb43F6F4c4650ae85d
- **Chain:** Ethereum Mainnet
- **Type:** Sovereign-backed yield-bearing stablecoin
- **Fee Waiver:** Requested for strategic token classification

## ✅ Verification Checklist

- [x] Contract verified on Etherscan
- [x] Logo converted to 256x256 PNG
- [x] Metadata matches on-chain data
- [x] All links are valid
- [x] Fee waiver request included

## 📞 Contact Information

- **Email:** ygor@brics.ninja
- **Telegram:** @ygorOF
- **GitHub:** https://github.com/yomarfrancisco

## 🎉 Expected Outcome

Once approved, BRICS token will be available in:
- Trust Wallet
- MetaMask (via Trust Wallet integration)
- Other wallets that use Trust Wallet's asset list

The token will appear with the correct logo, name, and metadata across all supported platforms.
