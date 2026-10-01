![Sell or Keep? — the moving-day wealth math](assets/preview.png)

![Vintage old-money banner](assets/banner.jpg)

**Live:** https://thebullbrew.github.io/sell-or-keep/

## What it does

You're moving. Now the only question that matters: **sell the house and invest the money**, or **keep it as a rental** and let someone else pay the mortgage?

Sell or Keep? runs the honest ten-year math on both paths:

- **Net proceeds if you sell** — home value minus the mortgage payoff, agent commissions, closing costs and capital-gains tax (with the $250k/$500k exclusion applied when you've lived there 2+ years).
- **Year-by-year wealth comparison** — keeping means equity compounding through appreciation and amortization *plus* every year's after-tax cash flow reinvested in the market; selling means the proceeds compounding at your assumed market return. Apples to apples, not monthly cash flow vs. vibes.
- **The rent that flips the answer** — the exact monthly rent that makes keeping richer than selling.
- **The capital-gains exclusion clock** — lived there 2 of the last 5 years? Your exclusion is intact today, but move out and the 2-of-5-year rule starts ticking (~3 years to sell tax-free). If your gain is big, the clock alone can be the deciding factor.
- **First-year snapshot** — cash flow before and after tax (interest write-off + depreciation shield), cap rate on today's value, equity at work.
- **Saved scenarios** — compare current rent vs. a dream rent, self-managed vs. a 10% manager, side by side.

## The method behind it

Comparing monthly cash flow is the amateur frame. A rental can lose money monthly and still win on equity — landlords get rich on appreciation and amortization, not rent checks. So both paths are measured as **wealth at year N**: keep = equity + reinvested after-tax cash flows; sell = proceeds invested in the market.

The rental side is underwritten like an investor would: vacancy, property tax tracking appreciation, insurance creep, maintenance and CapEx reserves as a percent of value, optional 10% management, rent growth, month-by-month mortgage amortization (it honors payoff mid-horizon), the interest deduction, and the 27.5-year depreciation shield on the building value (land excluded — the IRS doesn't let you depreciate dirt).

Simplified on purpose: no state-by-state tax rules, no PMI, no refinancing, no depreciation recapture on eventual sale (so keeping's edge is slightly overstated on long holds), no "tenant trashes the place" premium. Not tax advice — run the final version past your CPA.

## How to run

No build, no backend, no secrets. Open `docs/index.html` in any browser (works from `file://`), or serve the `docs/` folder with any static host. It's a PWA — add it to your home screen and it works offline.
