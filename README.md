# 📊 Market Earnings Dashboard · 全市场财报仪表盘

> A beginner-friendly, bilingual dashboard to read and compare US stock earnings in real time — with plain-language explanations that grow with you.
>
> 一个对小白友好的双语仪表盘，实时查看与对比美股财报，用大白话讲解，并能随你的水平一起成长。

**🔗 Live demo:** https://senjay43223.github.io/market-earnings-dashboard/

---

## ✨ Features · 功能亮点

- **📡 Real-time data** — Live stock prices, P/E, net margin, market cap & company logos via the [Finnhub](https://finnhub.io) API.
  实时股价、市盈率、净利润率、市值与公司图标。
- **🌏 Bilingual (中 / EN)** — One-tap language switch across the entire UI, analysis and glossary.
  全站中英一键切换，连深度解读和词典都翻译。
- **🎚️ Adaptive learning levels** — Beginner → Intermediate → Pro. The metrics shown and the depth of the analysis grow as you level up, so the tool never feels "too basic" once you've learned.
  三级自适应学习：入门 → 进阶 → 专业。指标与解读深度随等级提升，学会了也不会觉得 out。
- **🏭 Six sectors** — Tech, Finance, Energy, Health, Consumer, Industrial — each with curated leaders and sector-specific analysis.
  科技 / 金融 / 能源 / 医疗 / 消费 / 工业，每个板块都有精选龙头和专属解读。
- **🔍 Search any US stock** — Look up any ticker or company name, not just the curated list.
  搜索任意美股，不局限于精选列表。
- **⭐ Watchlist** — Star stocks to build your own watchlist (saved locally in your browser).
  自选股收藏，存在本地浏览器。
- **📰 Live news + impact read** — Recent headlines with an automatic positive / negative / neutral tilt.
  实时新闻 + 自动判断利好/利空倾向。
- **📚 Glossary** — Plain-language definitions of every financial term used, with examples.
  财务术语词典，大白话 + 举例。
- **📱 Mobile-first & dark mode** — Responsive layout, follows your system dark mode, installable feel.
  手机优先，自动深色模式。

---

## 🚀 Quick start · 快速开始

1. **Get a free API key** — Sign up at [finnhub.io/register](https://finnhub.io/register) (email only) and copy your API key.
   去 [finnhub.io/register](https://finnhub.io/register) 免费注册，复制 API Key。
2. **Open the site** — Visit the live demo, or open `index.html` locally in a browser.
   打开网站，或本地用浏览器打开 `index.html`。
3. **Paste the key** — Enter your key in the bar at the bottom and tap *Enable*. It's stored only in your browser — never uploaded.
   在底部填入 Key 点"启用"。Key 只存在你本地浏览器，不会上传。

> ⚠️ **Privacy:** The API key lives in your own browser's `localStorage`. This repo contains **no secrets**, so it's safe to fork and host publicly.
> Key 存在你自己浏览器里，仓库内不含任何密钥，可放心公开 fork / 托管。

---

## 🛠️ Tech · 技术栈

- Single static `index.html` — no build step, no backend.
- [Chart.js](https://www.chartjs.org/) for charts, [Tabler Icons](https://tabler.io/icons) for icons.
- Data: [Finnhub](https://finnhub.io) free tier (60 req/min).

Deploy anywhere static: **Netlify Drop**, **Vercel**, **GitHub Pages** — drag the folder and you're live.

---

## ⚠️ Disclaimer · 免责声明

Quarterly revenue, EV/EBITDA and analyst ratings are **illustrative reference values** for learning the *structure* of earnings; live price / margin / market cap / news come from Finnhub. **Nothing here is investment advice.**

季度营收、EV/EBITDA、评级为**示例参考值**，用于学习财报结构；股价/利润率/市值/新闻为 Finnhub 实时数据。**本项目不构成任何投资建议。**

---

## 🗺️ Roadmap · 后续计划

- [ ] Favorites sync across devices
- [ ] Historical price mini-charts (K-line)
- [ ] More markets (HK / A-shares / ETFs)
- [ ] Manual light/dark theme toggle
- [ ] PWA "add to home screen"

Contributions and ideas welcome — open an issue! 欢迎提 issue 和 PR。

---

## 📄 License

MIT
