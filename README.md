# Grey Moon BI Dashboards

Business intelligence analysis of a real restaurant's monthly performance, built from raw Toast POS exports. Two dashboards covering **menu performance** and **daily sales trends**, plus the findings that came out of them.

**[View the live dashboards →](https://your-github-username.github.io/grey-moon-bi-dashboards/)**

---

## Background

Grey Moon Breakfast & Brunch is a Greenville, SC restaurant I founded and operate. Rather than build a portfolio project on sample data, I pulled a full month of real Toast POS exports (June 2026) and analyzed it the way I would for a client: clean the data, find what's actionable, and build something a non-technical owner could actually use to make decisions.

## What's inside

### 📊 Part 1 — Menu Performance
Category mix, top-selling items, kitchen prep insights, and a menu rationalization analysis.

**Key finding:** the top 10 menu items (10% of the food+drink menu) generated **60.1%** of all food revenue. Meanwhile, **34% of food items** sold 3 units or fewer all month, contributing just **2.1%** of food revenue — a clear, low-risk cut-list for simplifying prep and reducing food cost exposure.

### 📈 Part 2 — Sales Trend
Daily sales by day of week, week-over-week momentum, and revenue by seating area (Dining Room / Patio / Bar).

**Key finding:** Grey Moon operates Friday–Sunday only, and Saturdays out-earn Fridays by **9.3×** — consistently, every week. Friday contributes just 5.7% of weekend revenue despite being staffed as a full service day, raising a real question about whether Friday hours, staffing, or concept should change.

## Methodology

- **Source data:** Toast POS exports (Sales Summary, Menu Item by Sales Category, Sales by Day, Top Modifiers, Revenue Center reports), June 1–30, 2026
- **Cleaning:** removed blank/miscategorized rows, flagged POS test entries ($0.01 placeholder items) for removal from the live menu
- **Analysis:** Python (pandas) for aggregation and Pareto/concentration analysis
- **Presentation:** self-contained HTML/CSS/JS dashboards — no build step, no external charting library, so they load reliably anywhere

## Tech stack

`Python` `pandas` `HTML/CSS/JS` — no frameworks, no dependencies. Designed to open instantly in any browser or be hosted for free on GitHub Pages.

## About me

I'm Isaiah Porter, a Business Intelligence & Operations professional with 15+ years running P&L across hospitality, entertainment, and supply chain — most recently as founder of Grey Moon and Director of Operations for a $1M+ revenue venue. TripleTen-certified Business Intelligence Analyst (Jan 2026), working in Power BI, Tableau, SQL, and Python.

📧 Isaiah.analytics@gmail.com
🔗 [linkedin.com/in/isaiahbporter](https://www.linkedin.com/in/isaiahbporter)
📍 Greenville, SC
