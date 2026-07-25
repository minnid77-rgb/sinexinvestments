# Sinex Investment Platform

![Status](https://img.shields.io/badge/Status-Live-brightgreen) ![License](https://img.shields.io/badge/License-MIT-blue)

Premium wealth management dashboard with automated 20% 3-week yield ROI calculator and multi-tier investment system.

## 🎯 Features

- 💼 **Portfolio Dashboard** - Real-time balance, invested capital, and ROI tracking
- 📈 **4-Tier Investment System**
  - Gold Tier: $7k - $14.9k
  - Diamond Tier: $15k - $29.9k
  - Platinum Tier: $30k - $59.9k
  - Multi-Platinum Tier: $60k+
- 🧮 **Interactive ROI Calculator** - Simulate guaranteed 20% returns on any investment amount
- 🛡️ **Express KYC Verification** - 30-second AI biometric & ID verification
- 📜 **Audited Ledger** - Complete transaction history and settlement tracking
- ⚡ **Admin Control Center** - Account management with PIN security (Default: 8821)
- 💰 **Multi-Currency Support** - USDT TRC20, Bitcoin, Ethereum, USD, EUR
- 🔄 **Auto-Ticker Engine** - Real-time balance updates every 4 seconds

## 🚀 Deployment

### GitHub Pages (Live)
```bash
# Push to main branch → Auto-deploys to GitHub Pages
git push origin main
```

**Access live at:** 🌐 https://minnid77-rgb.github.io/Sinex-static/

### Local Development
```bash
# Clone the repository
git clone https://github.com/minnid77-rgb/Sinex-static.git

# Open in browser
open index.html
# or just drag index.html into your browser
```

## 📱 Branch Strategy

- **main** - Production deployment (auto-deploys to GitHub Pages)
- **develop** - Staging branch for testing new features

### Creating Features

```bash
# Create feature branch
git checkout -b feature/your-feature-name

# Make changes, commit
git add .
git commit -m "Add feature description"

# Push and create Pull Request
git push origin feature/your-feature-name
```

## 💾 Data Persistence

All user data is stored in browser **localStorage**:
- User profile (name, balance, tier, KYC status)
- Active investments and positions
- Transaction history/ledger

**Note:** Data persists only in the same browser. Clearing cache or using incognito mode will reset data.

## 🔐 Admin Access

**PIN:** `8821` (or `admin`)

### Admin Features
- Edit user account details
- Modify portfolio balance
- Instant capital injection (+$5k, +$10k, +$50k)
- View user accounts table
- Manage tier assignments

## 📊 Investment Example

**Investment:** $10,000 in Gold Tier
- Principal: $10,000
- 20% ROI: +$2,000
- 3-Week Payout: $12,000
- Duration: 21 days

## 🛠️ Tech Stack

- **Frontend:** HTML5 + CSS3 + Vanilla JavaScript
- **Styling:** Custom CSS variables with dark theme
- **Storage:** Browser localStorage API
- **Fonts:** Google Fonts (Plus Jakarta Sans, Space Grotesk)
- **Hosting:** GitHub Pages (static)

## 📋 File Structure

```
Sinex-static/
├── index.html       # Main dashboard (all-in-one)
├── README.md        # This file
└── .gitignore       # Git configuration
```

## 🔄 CI/CD Pipeline

Automatic deployment on:
- ✅ Push to `main` branch → GitHub Pages live
- ✅ Pull requests auto-validate formatting
- ✅ Zero-downtime deployments

## 📝 License

MIT License - See LICENSE file for details

## 👤 Author

**minnid77-rgb**  
GitHub: [@minnid77-rgb](https://github.com/minnid77-rgb)

---

**📍 Live Platform:** [https://minnid77-rgb.github.io/Sinex-static/](https://minnid77-rgb.github.io/Sinex-static/)

**📦 Repository:** [https://github.com/minnid77-rgb/Sinex-static](https://github.com/minnid77-rgb/Sinex-static)
