# Base Farcaster Multi-Send Mini App

A **Farcaster Mini App** that lets users send **ETH on Base** to multiple recipients in one flow using:
- Farcaster native wallet (smart wallet)
- MetaMask fallback
- Username (`@farcaster`) or direct address resolution
- Batch transactions (EIP-5792) with safe fallback

Built for **speed, safety, and creator-first UX**.

---

## ✨ Features

- 🔐 **Official Farcaster login**
- 👛 Uses **Farcaster smart wallet**
- 🔁 MetaMask fallback supported
- 🧠 Resolve `@username → wallet address`
- 📦 **Batch send** (wallet_sendCalls)
- 🧯 Auto-fallback to individual tx if batch unsupported
- ⚡ Runs fully client-side (no backend)
- 🌐 Base Mainnet (Chain ID: `8453`)
- 📱 Mobile-friendly (Mini App compatible)

---

## 🧩 How It Works

1. User opens the Mini App inside Farcaster
2. Connects wallet (Farcaster → MetaMask fallback)
3. Enters recipients:
   ```text
   @dwr, 0.001
   0xabc123..., 0.005
