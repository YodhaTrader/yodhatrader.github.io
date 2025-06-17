# YodhaTrader Public Website

Welcome to **YodhaTrader** — a platform focused on empowering retail traders and investors with tools, insights, and a path to SEBI-compliant research.

---

## 🌟 Project Vision

| Goal | Status |
|------|--------|
| Build SEBI-compliant Research Infrastructure | ✅ Yes |
| Help Independent RAs publish & monetize research | ✅ In progress |
| Enable segment-based analytics & subscriptions | ✅ To be finalized |
| Create tools and visuals for rookies & pros alike | ✅ Yes |
| Evolve into SEBI-licensed brokerage (10yr plan) | ✅ Long-term goal |

---

## 🌐 Live Demo

- 🚀 Website: [https://yodhatrader.github.io](https://yodhatrader.github.io)
- 🔐 Private backend: [https://yodha-private-api.fly.dev](https://yodha-private-api.fly.dev)

---

## ✅ Current Features

- [x] Public static site hosted on GitHub Pages
- [x] Legal sections: Disclaimer, Privacy, Terms
- [x] Private backend with Kite API (Zerodha)
- [x] Access token refresh via `/refresh-token` interface
- [x] GitHub Actions CI/CD to Fly.io

---

## ⛔️ Compliance Note

This project is **not** an investment advisory.

- ✅ The founder is preparing for **SEBI Research Analyst certification**
- ❌ No public research or stock advice is published yet
- ✅ All tools/content are **educational** at this stage

---

## 📂 Repositories

| Name | Description |
|------|-------------|
| [`yodhatrader.github.io`](https://github.com/YodhaTrader/yodhatrader.github.io) | Public website repo |
| [`yodhatrader-private-api`](https://github.com/YodhaTrader/yodhatrader-private-api) | Flask app for KiteConnect & deployment |

---

## 🔐 API Usage

Kite Connect integration uses `.env` for secure keys:

```bash
KITE_API_KEY=your_key
KITE_API_SECRET=your_secret
REDIRECT_URL=https://api.yodhatrader.com/kite/callback
```

### Access Token Flow
1. Visit `/refresh-token`
2. Log in via Zerodha
3. Copy `request_token`
4. Paste back into the form
5. Access token saved to Fly.io secrets

---

## 📌 Best Practices

- ❌ Never commit secrets to GitHub
- ✅ Use `flyctl secrets set` for production keys
- ✅ Update token manually daily or schedule with GitHub Actions

---

## 💡 Promotion Plans (Ideation)

| Format | Tool Suggestion | Notes |
|--------|------------------|-------|
| 📸 Quote Wallpapers | Canva / Figma | LinkedIn/Insta/Telegram |
| 🎞️ Short Videos | CapCut / InVideo | Voiceover + quote motion |
| 📊 Visual Charts | TradingView | "Market Anatomy" style |
| 📜 Threads | Twitter / LinkedIn | Break quote → insight |
| 🧠 Thought of Day | Cron + `quotes.json` | Auto-post planned |

---

## 🚪 Onboarding Checklist

- [x] Created GitHub Repos
- [x] Set up GitHub Pages
- [x] Deployed Fly.io App
- [x] Configured `.env` securely
- [x] Added token refresh endpoint
- [x] Connected custom domain (via Cloudflare)

---

## 📊 Roadmap (v0.1)

- [ ] Interactive chart library
- [ ] Research publishing interface (private)
- [ ] Subscription logic (segment-based)
- [ ] SEO + Speed optimization for GitHub Pages

---

## 📅 Last Updated

**Generated:** 2025-06-17

---

## © 2025 YodhaTrader. All rights reserved.
