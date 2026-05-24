# DLF × Awfis: Buy-Side M&A Acquisition Model

A complete buy-side investment banking analysis of a **hypothetical ₹4,580 Cr acquisition of Awfis Space Solutions by DLF Limited**, where India's largest listed flexible-workspace operator is acquired by its largest real-estate developer. The model values the target three ways, structures the deal across six financing alternatives, and tests EPS accretion/dilution and synergy economics to arrive at a recommended offer and structure.

Built end-to-end in Excel, it runs from a WACC-driven DCF and a comps/precedents valuation triangulation through to a pro-forma accretion/dilution build and sensitivity tables, the way an M&A advisory team would prepare a pitch for a strategic acquirer.

> A buy-side pitch, not a stock report. The question isn't "is Awfis a good company." It's *"at what price, funded how, does this deal create value for DLF's shareholders, and where does it stop working."*

---

## The deal in one paragraph

The thesis: DLF (India's largest real-estate developer, ~₹1.4 lakh Cr market cap) would acquire Awfis to build an integrated **"build-to-flex" platform**, where DLF develops and owns the real estate and Awfis operates the flexible workspace on top of it. The model recommends a **₹475/share offer (≈43% premium to CMP of ₹331)**, valuing Awfis at a **₹4,580 Cr enterprise value (9.0× EV/EBITDA)**. That is a deliberately conservative entry, sitting at the low end of the valuation range while still clearing the control-premium hurdle. Recommended structure: **all-stock or a mixed 10/40/50 cash-debt-stock** package, both of which keep dilution minimal and preserve DLF's investment-grade balance sheet.

## What's inside the model

The workbook is a connected set of schedules, each feeding the valuation and deal output:

| Sheet | What it does |
|---|---|
| **Assumptions** | Single source of truth: market data, WACC inputs, growth/margin assumptions, deal parameters |
| **Acquirer / Target Financials** | FY23A–FY29E summaries for DLF and Awfis (revenue, EBITDA, PAT, EPS, net debt, equity) |
| **Ratio_Analysis** | Side-by-side DLF vs Awfis vs sector-median comparison across profitability, leverage, efficiency and valuation ratios |
| **DCF** | 5-year FCFF forecast (FY27E–FY31E) with a CAPM-derived WACC and Gordon-growth terminal value → implied ₹472/share |
| **Trading_Comps** | Listed flex-workspace and commercial-RE peers, EV/EBITDA multiple range → ₹939–1,235/share |
| **Precedent_Transactions** | 8 recent flex-workspace M&A deals, median 13.7× EV/EBITDA with embedded control premia → ₹784–832/share |
| **Football_Field** | Triangulates all methods into a single value range; positions the ₹475 offer against each |
| **Accretion_Dilution** | Pro-forma EPS build across **six financing scenarios** (all-cash, all-debt, all-stock, and three blends), with synergy phase-in |
| **Sensitivity** | EPS accretion/(dilution) across offer price × % stock mix; synergy-realization breakeven |
| **Price_Volume_Trends** | 4-year historical price context for both stocks (entry-timing argument) |
| **Summary** | Recommendation, structure, and key deal metrics |

## Valuation: three methods, triangulated

| Method | Implied value (₹/share) | Notes |
|---|---|---|
| DCF (FCFF) | **~₹472** | WACC 12.4%, terminal growth 5.0%, 5-yr forecast |
| Trading Comparables | **₹939–1,235** | Median peer EV/EBITDA ~17.7× |
| Precedent Transactions | **₹784–832** | Median deal 13.7×, embeds 20–35% control premium |
| **Proposed offer** | **₹475** | ~43% premium to CMP; conservative end of range |

The **₹475 offer sits below the DCF base case and well below comps**. The pitch is built around buying at a defensible, conservative entry rather than chasing the multiple, with a stated negotiating ceiling of ~₹800 if competitive bidding emerges.

## Deal structure & accretion/dilution

Six financing structures were modeled against DLF's standalone FY27E EPS of ₹16.69:

| Scenario | Year-1 EPS impact | Pro-forma Net Debt/EBITDA |
|---|---|---|
| All Cash | −1.8% | 0.21× |
| All Debt | −3.5% | 1.35× |
| **All Stock** | **−0.5% (best)** | 0.78× |
| Cash + Debt (20/80) | −3.1% | 1.13× |
| Debt + Stock (50/50) | −2.0% | 1.07× |
| **Mixed (10/40/50)** | **−1.8%** | 0.95× (preserves promoter stake) |

**Core finding:** every structure is mildly dilutive in Year 1, but **all turn accretive by Year 3** as synergies (₹192 Cr run-rate, ~10% of target revenue) phase in (25% → 65% → 100%). With a synergy PV of ~₹1,150 Cr against a control premium of ~₹1,036 Cr, the deal shows **~₹114 Cr of net value creation**, which is the quantitative spine of the "proceed" recommendation.

## Skills demonstrated

- Full **DCF / FCFF** build: CAPM cost of equity, WACC, Gordon-growth terminal value, EV-to-equity bridge
- **Comparable companies** and **precedent transactions** valuation, including control-premium reasoning
- **Football-field** valuation triangulation
- **EPS accretion/dilution** mechanics across cash / debt / stock financing mixes
- **Synergy valuation** (revenue synergy build, phase-in, PV vs control premium)
- **Two-variable sensitivity** tables (offer price × stock mix) and breakeven analysis
- M&A deal structuring, control-premium and regulatory awareness (SEBI SAST open offer, CCI)
- Clean model architecture: one assumptions tab driving every downstream schedule

## Repository contents

```
├── DLF_x_Awfis_Acquisition_Model.xlsx       # Full model (13 linked sheets)
├── DLF_x_Awfis_Acquisition_Pitch_Deck.pdf   # 23-slide buy-side pitch
└── README.md
```

## How to read it

1. Open the deck (`...Pitch_Deck.pdf`) for the full story: rationale → industry → valuation → structure → recommendation.
2. In the model, start at **Assumptions** (everything flows from there), then **DCF → Trading_Comps → Precedent_Transactions → Football_Field** for the valuation, and **Accretion_Dilution → Sensitivity** for the deal economics.
3. **Summary** holds the recommendation; everything upstream is the build behind it.

## Notes & disclaimers

- An academic / portfolio exercise. All figures are illustrative, built from public filings (NSE/BSE), annual reports, and industry research (Colliers, Savills, Mordor Intelligence). Valuation date: April 2026.
- This is **not** investment advice and not affiliated with DLF or Awfis.

---

*Author: Abhishek Agrawal · MBA Finance · 2026*
*Connect: https://www.linkedin.com/in/abhisheka24 · abhishek.iitk.mba@gmail.com*
