# EUR/USD Scalping Helper

A single-file, browser-based tool to size EUR/USD scalping trades and check risk/reward.

## Live Site
After your first push to `main`, GitHub Actions will publish at:
`https://georgetolin.github.io/eurusd-scalper`

## Use
1. Open the site.
2. Enter **entry**, **stop**, **take-profit**, **balance**, and **risk%**.
3. Click **Calculate** to see pips, risk in USD, and position size (lots & units).

## Notes
- Assumes typical pip value: EUR/USD ≈ **$10/pip per 1.0 standard lot**.
- For scalping, common stops are **5–10 pips** and targets **10–20 pips**.
- Liquidity is best during the **London–New York overlap**.

## Local Development
Just open `index.html` in your browser — no dependencies required.

## License
MIT — see `LICENSE`.
