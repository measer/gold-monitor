[README.md](https://github.com/user-attachments/files/29587272/README.md)
# 👀 金盯盯 · Aurex · 专治买金选择困难症  (◕‿◕)♡

> 自己刚开始关注黄金的时候，打开支付宝觉得太复杂，翻银行 App 又嫌太零散。  
> 后来想着，不如把那些"小白真正需要看的东西"都整理到一个页面上，方便自己每天瞄一眼。  
> 这就是做这个小工具的初衷 —— 让想买黄金的普通人，不用看懂复杂图表也能心里有数。  
> 第一次尝试做这样的工具，还有很多不完善的地方，希望它能帮到你，也欢迎随时提建议 🙏

**👉 在线预览：** https://measer.github.io/gold-monitor/

---

## 🔥 它解决了哪三个麻烦？

| 你的感受 | 金盯盯怎么帮你 |
| :--- | :--- |
| **信息太散** | 国际金价、国内 AU9999、10 家银行积存金、6 支黄金 ETF、品牌金饰、平台终端……**全部汇聚一页**，打开即看，30 秒内完成每日行情巡检。 |
| **没空一直盯着** | 设置价格提醒，**涨到或跌到你设定的价位，页面会弹窗 + 响铃**。切出去看别的网页时，浏览器标签栏也会闪烁提示，不容易错过。 |
| **算不清赚了还是亏了** | 自带 **持仓成本计算器**，选品种、填买入价和数量，自动算浮动盈亏。数据存在你浏览器里，关掉再打开也还在。 |

---

## ✨ 功能概览

### 👁️ 金价汇总
- **国际金价**：实时 USD/oz、CNY/oz，自动换算 24K/22K/18K 每克单价
- **国内金价**：上海黄金交易所 AU9999 现货，自动识别交易时段（日盘/夜盘/休市）
- **银行积存金**：10 家银行积存金参考价（工、建、农、中、交、邮储、招商、兴业、浙商、光大）对比
- **黄金 ETF**：6 支主流黄金 ETF 实时价格（华安 518880、易方达 159934、博时 159937、华夏 518850、富国 518680、国泰 159830）
- **零售金饰**：周大福系、菜百系金饰估价
- **平台终端报价**：支付宝、微信、京东金融、天天基金等 6 个平台费率对比

### 📈 期货参考
- 沪金主力合约 AU0 实时价格
- COMEX 国际黄金参考价
- 现货 / 期货价差自动计算（基差分析）
- 沪金近月合约列表（成交量、持仓量）

### 🔔 实用工具
- **价格走势图**：实时数据 + 历史 30 日/90 日/1 年 K 线
- **持仓成本计算器**：18 个品种可选，自动计算浮动盈亏，数据本地持久化
- **价格预警**：自定义涨跌阈值，触达后弹窗 + 响铃提醒
- **中英文双语**：一键切换，手机/电脑都可用

---

## 🚀 如何使用 / 部署

### 方式一：直接打开（本地）
下载 `gold-monitor.html`，双击在浏览器中打开即可。

> ⚠️ 部分接口在 `file://` 协议下会被浏览器拦截跨域请求，建议使用方式二。

### 方式二：部署到 GitHub Pages（推荐）

1. Fork 或下载本仓库
2. 进入仓库 **Settings → Pages**
3. Source 选择 `main` 分支，保存
4. 等待 1～2 分钟，访问 `https://<你的用户名>.github.io/<仓库名>/`

整个项目是单一 HTML 文件，没有构建步骤，没有依赖安装，托管在任何静态网站服务（GitHub Pages / Vercel / Netlify / Cloudflare Pages）均可直接运行。

---

## ⚠️ 需要注意

这个工具**没有后端服务器，没有数据库，也不收集任何个人信息**。
所有价格**仅供参考**，帮你做初步对比，但**不是实际交易价**：

- 银行积存金、金饰价格为估算，并非准实时挂牌价
- 期货价格和国内现货金价之间本身存在基差，两者不是同一个价格体系
- 盈亏计算未包含手续费、税费、买卖点差等成本

> 在「金盯盯」看完对比后，最后一步建议去银行 App 或品牌官网确认一下实时报价。市场有风险，下手前多看一眼没坏处 😊

---

## 🙋 反馈 & 贡献

欢迎提 Issue 或 PR，功能建议、数据源更新、翻译改进都非常欢迎。

---

## 📄 License

MIT

---
---

# 👀 Aurex · Your Daily Gold Price Dashboard  (◕‿◕)♡

> When I first started paying attention to gold, every app felt either too complex or too fragmented.  
> So I built a single page with just what a beginner actually needs — something you can glance at each day and feel informed.  
> That's the idea behind Aurex: give everyday people a clear picture of the gold market, no chart-reading expertise required.  
> It's a first attempt and still a work in progress — I hope it helps, and feedback is always welcome 🙏

**👉 Live Demo：** https://measer.github.io/gold-monitor/

---

## 🔥 Three Problems It Solves

| Your frustration | How Aurex helps |
| :--- | :--- |
| **Too many sources** | International spot price, Chinese AU9999, 10 bank gold savings plans, 6 gold ETFs, retail jewelry, and platform rates — **all on one page**. Open it, scan it, done in 30 seconds. |
| **Can't watch it all day** | Set a price alert. When gold hits your target — up or down — **the page pops up an alert and plays a chime**. Even when you're on another tab, the browser title bar flashes so you won't miss it. |
| **Can't tell if you're up or down** | The built-in **position cost calculator** lets you pick a product, enter your buy price and quantity, and instantly shows your floating P&L. Data is stored locally in your browser — it'll still be there next time you open the page. |

---

## ✨ Feature Overview

### 👁️ Gold Price Hub
- **International spot price**: Live USD/oz and CNY/oz, auto-converted to per-gram prices for 24K / 22K / 18K
- **China domestic price**: Shanghai Gold Exchange AU9999 spot, with automatic session detection (day / evening / closed)
- **Bank gold savings**: Reference prices from 10 major banks (ICBC, CCB, ABC, BOC, BOCOM, PSBC, CMB, CIB, CZB, CEB)
- **Gold ETFs**: Live prices for 6 mainstream ETFs (Huaan 518880, E-Fund 159934, Bosera 159937, ChinaAMC 518850, Fullgoal 518680, Guotai 159830)
- **Retail jewelry**: Estimated prices from Chow Tai Fook and Caibai product lines
- **Platform rates**: Fee comparison across 6 consumer platforms including Alipay, WeChat, JD Finance, and TiantianFund

### 📈 Futures Reference
- Shanghai Gold Futures front-month contract (AU0) live price
- COMEX international gold reference price
- Auto-calculated spot / futures spread (basis analysis)
- Near-month contract list with volume and open interest

### 🔔 Tools
- **Price chart**: Live feed + historical candlestick view for 30-day / 90-day / 1-year periods
- **Position cost calculator**: 18 product types, auto P&L calculation, data persisted locally in your browser
- **Price alerts**: Custom thresholds for rises and drops, with pop-up + chime notification on trigger
- **Bilingual UI**: Switch between Chinese and English in one click, works on mobile and desktop

---

## 🚀 Usage & Deployment

### Option 1: Open Locally
Download `gold-monitor.html` and open it directly in your browser.

> ⚠️ Some data sources block cross-origin requests under the `file://` protocol. Option 2 is recommended for full functionality.

### Option 2: Deploy to GitHub Pages (Recommended)

1. Fork or download this repository
2. Go to **Settings → Pages**
3. Set Source to the `main` branch and save
4. Wait 1–2 minutes, then visit `https://<your-username>.github.io/<repo-name>/`

The entire project is a single HTML file — no build step, no dependencies. It runs out of the box on any static hosting service (GitHub Pages / Vercel / Netlify / Cloudflare Pages).

---

## ⚠️ Disclaimer

This tool has **no backend server, no database, and collects no personal information whatsoever**.
All prices are **for reference only** and are **not live tradable quotes**:

- Bank gold savings and jewelry prices are estimates, not real-time posted rates
- Futures prices and domestic spot prices operate in different price systems with an inherent basis spread — they should not be treated as equivalent
- P&L calculations do not account for transaction fees, taxes, bid/ask spreads, or other trading costs

> Use Aurex to get the lay of the land, then confirm the exact rate in your bank app or on the brand's official site before making a move. Markets move — one extra glance never hurts 😊

---

## 🙋 Feedback & Contributions

Issues and PRs are very welcome — whether it's a feature idea, a data source update, or a translation fix.

---

## 📄 License

MIT
