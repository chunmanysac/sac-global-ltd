# SAC Global Ltd — Intro site

Simple bilingual (繁體中文／English) one-pager for **SAC Global Ltd** (Simon Yeung, Hong Kong).

## Local files

- `index.html` — main page
- `styles.css` — layout & design
- `script.js` — mobile nav + year

Open `index.html` in a browser, or serve the folder:

```bash
npx --yes serve /workspace/sac-global-site
```

## How to update payment placeholders

On the Contact section (`#contact`) there are two clear placeholders Simon will fill in later:

| Placeholder | Meaning | What to put |
|-------------|---------|-------------|
| `[PAYPAL_LINK]` | Primary PayPal payment link | Full `https://…` PayPal.me or invoice URL |
| `[FPS_DETAILS]` | 轉數快／銀行過數 | FPS ID / bank name / account name (no invented numbers) |

**Steps:**

1. Open `index.html`.
2. Search for `[PAYPAL_LINK]` and replace the whole placeholder span text with the real link (or wrap it in an `<a href="…">`).
3. Search for `[FPS_DETAILS]` and replace with real FPS / bank transfer details.
4. PayMe / Stripe remain backup — add details in the same list item when ready.
5. Redeploy the folder (same method used for the public URL).

Do **not** invent PayPal or FPS numbers.

## Packages (reference prices)

- Starter ≈ HK$3,800/mo（參考價）
- Growth ≈ HK$6,800/mo（參考價）

Explicit exclusions: 唔包影相／拍片／設計.

## Contact

- Email: marketing@sacgloballtd.com
