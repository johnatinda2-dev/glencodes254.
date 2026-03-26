# AfriImpact — Revenue Engine for African Growth Markets

## 🚀 Project Structure

```
afriimpact/
├── index.html              → Root redirect to landing page
├── css/
│   └── design-system.css   → Shared design tokens, components, utilities
├── js/
│   └── utils.js            → Shared JS (Toast, countUp, animations)
└── pages/
    ├── index.html          → 🌐 Public Marketing Landing Page
    ├── app.html            → 📊 Internal Client Dashboard (full SaaS app)
    └── onboarding.html     → 🎯 Onboarding Wizard + Pricing + Signup
```

## 📄 Pages

### 1. `pages/index.html` — Marketing Landing Page
Full public-facing site with:
- Fixed nav with blur
- Hero with animated stats (3.4× conversion, $12K+ MRR, 48h setup, 97% retention)
- Marquee ticker of industries
- How It Works (3-step flow)
- Channels section — WhatsApp, Email, **X (Twitter)**, LinkedIn, SMS
- Features grid (6 cards)
- Industry niches with tabbed panels (Real Estate, Fintech, Edtech, Insurance)
- Pricing — **Starter $100/mo**, Growth $297/mo, Enterprise $697/mo
- Testimonials
- FAQ with accordion
- CTA section + full footer

### 2. `pages/app.html` — Client Dashboard
Full internal SaaS app with 6 navigable pages:
- **Metrics** — KPI cards, MRR bar chart, revenue donut, conversion funnel, channel performance, live activity feed
- **CRM** — searchable/filterable contact table with scores, statuses, deal values
- **Pipeline** — 5-column Kanban board with deal cards and probability bars
- **Conversations** — split-panel inbox with AI insight bar, message threads, send functionality
- **Workflows** — 6 automation cards with live toggle switches + visual workflow canvas
- **Bookings** — March 2026 calendar grid + upcoming meetings list + booking stats

### 3. `pages/onboarding.html` — Onboarding Flow
4-step wizard:
1. **Business Info** — Name, email, company, country, industry niche selection
2. **Channels** — Multi-select (WhatsApp, Email, X, LinkedIn, SMS)
3. **Plan Selection** — Starter $100, Growth $297, Enterprise $697 with full feature comparison
4. **Payment** — Card form (trial, $0 due today)
5. **Success** — Next steps breakdown + go to dashboard CTA

## 🎨 Design System
- **Aesthetic**: Afrofuturist Premium SaaS — deep obsidian bg, amber gold (#F5A623) + electric teal (#00D4B4) accents
- **Fonts**: Clash Display (headings) + DM Sans (body) + JetBrains Mono (data)
- **Animations**: scroll-reveal, count-up, gradient shifts, CSS transitions

## 🔧 How to Run
Open `index.html` in a browser — no build step needed. Pure HTML/CSS/JS.
All font imports are via CDN (internet required for fonts).

## 💰 Pricing (Updated)
| Plan | Monthly | Setup |
|------|---------|-------|
| Starter | **$100/mo** | $500 |
| Growth | $297/mo | $1,000 |
| Enterprise | $697/mo | $2,000 |

## 📡 Channels Supported
- 💬 WhatsApp (Business API)
- ✉️ Email (sequences & drips)
- 𝕏 **X / Twitter** (DM funnels & engagement — NEW)
- 💼 LinkedIn (B2B outreach)
- 📱 SMS (52 African countries)
