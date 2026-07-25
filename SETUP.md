# GoldTrack 🥇

Gold, Silver, Platinum & Palladium prices in WhatsApp. Built for global markets.

## Stack
- **API:** fawazahmed0/currency-api (free, no key, CDN-hosted)
- **Workflows:** n8n v2 (single Code node)
- **WhatsApp:** Evolution API → wasapea-7c7a2c6c
- **Landing:** nginx:alpine + Dokploy

## n8n Workflows
1. `001-goldtrack-daily.json` — Gold/Silver/Platinum/Palladium every 12h

## Deploy
1. Dokploy → Create Project → `goldtrack`
2. Git Repo → `https://github.com/samu1606/goldtrack`
3. Domain: `goldtrack.148-230-90-171.nip.io`
4. Container port: 80

## Plans (Landing)
- Starter ($0): Gold + Silver, 1 daily update
- Investor ($9/mo): All 4 metals, every 6h, ±$50 alerts
- Trader ($19/mo): Every hour, CSV export, email
