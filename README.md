# Magno (Codename)

Magno is a private, in-development trading bot framework designed for perpetuals trading on Hyperliquid.

It uses a combination of machine learning, adaptive execution logic, and modular strategy modes to respond to live market conditions with precision.

Most internal modules and data are currently `.gitignored` while development continues.

---

### ✅ Core Features (Completed)

- Machine learning classifier per symbol (multi-class)
- Volatility-aware SL/TP tuning
- Strategy mode switching (scalp, swing, build, sentry)
- Session-aware execution windows (by market region)
- Multi-timeframe signal fusion
- Confidence-based trade filtering
- Position tracking with dynamic trailing stop logic
- Dry-run vs live mode selector
- Configurable risk and SL/TP settings per symbol
- Trade reason captioning system (blended logic, human-readable)

---

### 🔜 In Progress / Upcoming

- Annotated trade screenshots (entry with logic overlays)
- Backtest equity curve visualization
- Per-mode expectancy and win/loss tracking
- Trade journaling export (JSON per symbol)
- Optional CLI dashboard for live stats
- Experimental alternate strategy overrides per asset

---

### 🛠️ Project Status

- Architecture and naming may evolve as features stabilize
- Repo currently serves as a private R&D space
- Codebase will remain minimal until production-ready

---

This project is being built clean, modular, and sharp — not a fork or clone.