# Muhalat Finance — Investment & Fixed Income Calculator

A clean, modern, browser-based financial calculator suite built in pure HTML, CSS, and JavaScript. No frameworks, no build tools, no backend — open the files and they work.

Built specifically for **Nigerian Naira (₦)** with Nigerian market context (NGX returns, CBN rates, T-bills, FGN bonds, PFAs).

---

## Live Demo

> **[View on GitHub Pages](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)**  
> *(Replace with your actual GitHub Pages URL after deployment)*

---

## Pages

### 1. Investment Calculator (`index.html`)

Estimates how a lump sum + regular contributions grow over time using compound interest.

**Inputs**
- Initial investment amount (₦)
- Monthly contribution (₦)
- Investment length (1–50 years)
- Estimated annual rate of return (no upper limit)
- Compound frequency (Monthly / Quarterly / Semi-Annually / Annually)

**Outputs**
- Total portfolio value at end of term
- Total amount invested vs. total interest earned
- Stacked bar chart showing growth year by year
- Collapsible year-by-year breakdown table

**Also includes — Dividend & Withdrawal Calculator**

A Phase 2 section on the same page that answers: *"Once my portfolio is built, how much income can it pay me?"*

- Enter any portfolio value (or pull it directly from Phase 1 with one click)
- Set a withdrawal/dividend rate
- See annual, monthly, quarterly, and weekly income
- Sustainability meter — tells you whether your withdrawal rate is **sustainable**, **break-even**, or **depleting** the portfolio, with an estimated depletion timeline

---

### 2. Fixed Income Calculator (`fixed-income.html`)

Calculates simple interest yield on a fixed principal — no compounding, just clean income figures.

**Inputs**
- Principal amount (₦)
- Annual interest rate (% p.a., no upper limit)
- Tenor — switchable between Days / Months / Years
- Quick-pick instrument buttons (pre-loads typical Nigerian market rates):
  - Treasury Bill (~22%), FGN Bond (~19%), Money Market (~21%), Fixed Deposit (~15%), Commercial Paper (~18%)

**Outputs**
- Annual interest income
- Monthly, quarterly, weekly, and daily breakdowns
- Maturity summary — total interest earned + maturity value over the chosen tenor

---

## Features

- **Naira-first** — all values in ₦, formatted with Nigerian locale separators
- **No ceiling on rate of return** — type any % value beyond the slider range
- **Financial Joke of the Day** — rotates daily, drawn from a curated list of 30 finance jokes
- **Motivational Quote** — daily rotating encouraging message on the investment page
- **Fully responsive** — works on desktop, tablet, and mobile
- **No dependencies** — only Chart.js (loaded via CDN) for the bar chart; everything else is vanilla JS
- **Instant calculations** — all results update in real time as you move sliders or type

---

## Project Structure

```
muhalat-finance/
├── index.html          # Investment Calculator + Dividend Calculator
├── fixed-income.html   # Fixed Income / Simple Interest Calculator
├── favicon.svg         # Custom M + ₦ tab icon
└── README.md
```

---

## Getting Started

No installation required. Just clone or download and open in a browser.

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
cd YOUR-REPO-NAME
```

Then open `index.html` in any modern browser.

---

## Deploying to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to **main** branch, **/ (root)**
4. Click **Save** — your site will be live within a minute at:
   `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

---

## Technologies

| Tech | Purpose |
|------|---------|
| HTML5 | Structure |
| CSS3 (custom properties, grid, flexbox) | Styling & layout |
| Vanilla JavaScript (ES6+) | All calculations and interactivity |
| [Chart.js 4.4](https://www.chartjs.org/) | Stacked bar chart (CDN) |
| SVG | Custom favicon |

---

## Inspiration & Credit

The investment calculator on this site was inspired by the **[Ramsey Solutions Investment Calculator](https://www.ramseysolutions.com/retirement/investment-calculator)** created by **Dave Ramsey** and the Ramsey Solutions team.

Dave Ramsey's calculator is an excellent tool for estimating long-term investment growth, and it served as the design and functional reference for this project. This version adapts the concept for the Nigerian market — using Naira (₦), Nigerian investment instruments, and local financial context — and extends it with a dividend/withdrawal calculator and a fixed income tool.

All credit for the original calculator concept and layout goes to Dave Ramsey and Ramsey Solutions.

---

## Disclaimer

All figures produced by these calculators are **estimates for illustrative purposes only**. Past performance is not a guarantee of future results. This tool does not constitute financial advice. Consult a qualified financial adviser before making investment decisions.

---

© Copyright Muhalat Finance 2026. All rights reserved.
