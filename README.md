# Satoshi Dashboard - Umbrel Community App Store

Community app store for installing [Satoshi Dashboard](https://github.com/Satoshi-Dashboard/main) on your Umbrel node.

## Install on Umbrel

1. Open your Umbrel dashboard
2. Go to **App Store** > **Community App Stores**
3. Add this URL:
   ```
   https://github.com/Satoshi-Dashboard/umbrel-app-store
   ```
4. Find **Satoshi Dashboard** in the store and click **Install**

## What is Satoshi Dashboard?

A real-time Bitcoin analytics dashboard featuring:

- Live BTC price tracking across 139+ currencies
- Mempool visualization and fee estimates
- Halving cycle spiral analysis
- Lightning Network map and stats
- BTC vs Gold comparison
- Address distribution and whale watching
- Stock-to-Flow, Power Law, MVRV models
- Fear & Greed Index
- And 20+ more modules

## App Details

| | |
|---|---|
| **Port** | 8787 |
| **Image** | `ghcr.io/satoshi-dashboard/main:v1.0.0` |
| **Category** | Bitcoin |
| **Version** | 1.0.0 |

## Structure

```
umbrel-app-store.yml
satoshi-dashboard/
  ├── umbrel-app.yml
  ├── docker-compose.yml
  └── icon.svg
```

## Source

- App source code: [Satoshi-Dashboard/main](https://github.com/Satoshi-Dashboard/main)
- Issues & support: [GitHub Issues](https://github.com/Satoshi-Dashboard/main/issues)
