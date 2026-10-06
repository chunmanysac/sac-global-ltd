# 字棧 ZiZaan — Content outsourcing site

Bilingual (繁體中文／English) one-pager for **字棧 ZiZaan**, the content-outsourcing brand of SAC Global Ltd (Simon Yeung, Hong Kong).

Hero offer: **內容外包 / content & copy outsourcing** for HK **餐飲 (F&B)** + **物流 (logistics)** — menu blurbs, promo copy, social text posts, service-page text, email copy.

## Brand name

| 中文 | EN | Why |
|------|----|-----|
| **字棧** | **ZiZaan** | 字 = words/characters (the product). 棧 = depot / staging warehouse — logistics DNA, and a place where copy is stocked ready to ship. Short (2 chars), memorable in 繁中; **ZiZaan** is pronounceable and unique in EN. Fits both restaurants (content “on the shelf”) and logistics (depot metaphor). Not “SAC Global” as the public brand; not a generic “AI Content Factory”. |

Footer credits the company: **SAC Global Ltd 出品**.

## Local files

- `index.html` — main page
- `styles.css` — layout & design
- `script.js` — mobile nav + year
- `assets/logo.svg` — full wordmark (SVG)
- `assets/logo.png` — high-res wordmark (PNG)
- `assets/logo-mark.svg` / `logo-mark.png` — icon mark only

Open `index.html` in a browser, or serve the folder:

```bash
npx --yes serve /workspace/sac-global-site
```

## How to update payment placeholders

On the Contact section (`#contact`) there are two clear placeholders:

| Placeholder | Meaning | What to put |
|-------------|---------|-------------|
| `[PAYPAL_LINK]` | Primary PayPal payment link | Full `https://…` PayPal.me or invoice URL |
| `[FPS_DETAILS]` | 轉數快／銀行過數 | FPS ID / bank name / account name (no invented numbers) |

Do **not** invent PayPal or FPS numbers.

## Packages (reference prices)

- Starter ≈ HK$3,800/mo（參考價）
- Growth ≈ HK$6,800/mo（參考價）

## Public URL

- https://chunmanysac.github.io/sac-global-ltd/
- Source repo: https://github.com/chunmanysac/sac-global-ltd

After editing files, commit and `git push origin main` — GitHub Pages rebuilds from `main` (root).

## Contact

- Email: marketing@sacgloballtd.com
