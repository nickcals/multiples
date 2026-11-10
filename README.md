# M&A Multiples Index — SMB & Lower-Middle-Market Valuation Multiples

[![Dataset DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20398222-blue)](https://doi.org/10.5281/zenodo.20398222)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](https://creativecommons.org/licenses/by/4.0/)

**An open, continuously-updated index of real-world M&A valuation multiples** (EV/EBITDA and EV/Revenue), broken out by **sub-vertical** and **enterprise-value bracket**. Built and maintained by [ExitValue.ai](https://exitvalue.ai).

> **Want a number for a specific business?** This dataset gives population medians. The free calculator at exitvalue.ai applies them to your revenue/EBITDA, size and industry: [Value a business →](https://exitvalue.ai/valuate?src=dataset-github)

> Every number below is an **aggregate median of disclosed M&A transactions** — not an estimate, rule of thumb, or imputed value. Each published cell requires **at least 10 disclosed deals** (`n >= 10`). Outliers are excluded (EV/EBITDA outside [0.5, 60.0]; EV/Revenue outside [0.05, 25.0]).

- **Coverage:** 21,349 unique completed transactions; 11,189 with disclosed EV/EBITDA, 20,597 with disclosed EV/Revenue.
- **Published cells:** 61 EV/EBITDA + 118 EV/Revenue across 44 sub-verticals.
- **Source window:** 2018-2026 (deals post-2018, from SEC EDGAR 8-K/S-4 filings, fairness opinions, and verified press releases).
- **Last updated:** 2026-10-30.
- **Browse by industry:** [nickcals.github.io/multiples](https://nickcals.github.io/multiples/), one page per industry.

---

## What multiple does a business in my industry sell for?

These are **median EV/EBITDA exit multiples** for **small-business and lower-middle-market** deals (enterprise value up to $100M) — the size range where most owner-operated companies actually transact. `p25`/`p75` show the interquartile spread; `n` is the number of disclosed deals in the cell.

| Sub-vertical | EV bracket | Median EV/EBITDA | p25 | p75 | n (deals) |
|---|---|---|---|---|---|
| [Ambulatory surgery center (ASC)](https://exitvalue.ai/valuation/ambulatory-surgery-center) | $5M-25M | **8.1x** | 5.5x | 11.4x | 20 |
| [Ambulatory surgery center (ASC)](https://exitvalue.ai/valuation/ambulatory-surgery-center) | $25M-100M | **9.1x** | 6.7x | 12.3x | 10 |
| [Dental practice](https://exitvalue.ai/valuation/dental-practice) | $5M-25M | **7.0x** | 6.5x | 8.3x | 10 |
| [Durable medical equipment (DME)](https://exitvalue.ai/valuation/medical-equipment) | <$5M | **5.3x** | 4.3x | 7.0x | 11 |
| [Durable medical equipment (DME)](https://exitvalue.ai/valuation/medical-equipment) | $5M-25M | **5.0x** | 4.7x | 5.7x | 12 |
| [Electronics](https://exitvalue.ai/valuation/electronics) | $25M-100M | **9.1x** | 6.7x | 18.4x | 10 |
| [Home health](https://exitvalue.ai/valuation/home-health) | <$5M | **4.7x** | 3.9x | 6.2x | 25 |
| [Industrial equipment](https://exitvalue.ai/valuation/industrial-equipment) | $25M-100M | **8.4x** | 6.2x | 11.3x | 18 |
| [Medical devices](https://exitvalue.ai/valuation/medical-devices) | $25M-100M | **13.0x** | 10.3x | 23.2x | 13 |
| [Oil & gas services](https://exitvalue.ai/valuation/oil-gas-services) | $25M-100M | **4.0x** | 2.2x | 9.1x | 13 |
| [Primary-care practice](https://exitvalue.ai/valuation/medical-practice-primary-care) | <$5M | **3.6x** | 3.4x | 4.6x | 11 |
| [SaaS](https://exitvalue.ai/valuation/saas-software) | $5M-25M | **10.7x** | 8.2x | 17.8x | 14 |
| [SaaS](https://exitvalue.ai/valuation/saas-software) | $25M-100M | **12.8x** | 5.7x | 19.6x | 10 |
| [Specialty medical practice](https://exitvalue.ai/valuation/medical-practice) | $5M-25M | **5.9x** | 5.1x | 8.2x | 15 |
| [Wholesale distribution](https://exitvalue.ai/valuation/wholesale-distribution) | $25M-100M | **6.2x** | 4.8x | 8.8x | 16 |

### Larger transactions (enterprise value $100M+)

For reference, the same sub-verticals at larger deal sizes (multiples typically expand with scale):

| Sub-vertical | EV bracket | Median EV/EBITDA | p25 | p75 | n (deals) |
|---|---|---|---|---|---|
| Aerospace | >$500M | **14.7x** | 13.4x | 17.7x | 18 |
| Auto parts | >$500M | **8.1x** | 6.6x | 12.5x | 10 |
| Consumer products | >$500M | **9.9x** | 8.7x | 11.3x | 14 |
| Dental practice | >$500M | **14.0x** | 11.9x | 15.8x | 17 |
| Electronics | $100M-500M | **14.7x** | 9.4x | 20.7x | 12 |
| Enterprise software | >$500M | **22.2x** | 15.2x | 34.6x | 10 |
| Food manufacturing | >$500M | **14.6x** | 10.5x | 21.1x | 25 |
| Gaming | $100M-500M | **9.2x** | 7.8x | 12.2x | 14 |
| Healthcare IT | >$500M | **19.9x** | 16.5x | 25.0x | 63 |
| Home health | >$500M | **11.7x** | 10.8x | 15.3x | 16 |
| IT services | >$500M | **11.5x** | 10.0x | 13.9x | 14 |
| Industrial equipment | >$500M | **13.1x** | 10.0x | 15.4x | 26 |
| Laboratory services | >$500M | **25.9x** | 16.8x | 31.1x | 10 |
| Medical devices | >$500M | **15.2x** | 11.7x | 20.1x | 41 |
| Mental / behavioral health | $100M-500M | **13.7x** | 10.0x | 15.5x | 20 |
| Metal fabrication | >$500M | **7.9x** | 6.2x | 9.9x | 18 |
| Oil & gas services | >$500M | **7.9x** | 5.0x | 11.3x | 120 |
| Packaging | >$500M | **9.9x** | 7.6x | 12.1x | 19 |
| Pharmacy | >$500M | **18.9x** | 12.0x | 20.8x | 18 |
| Primary-care practice | >$500M | **17.6x** | 14.4x | 19.6x | 12 |
| Radio & television | >$500M | **10.9x** | 6.8x | 13.6x | 10 |
| Restaurant (QSR) | >$500M | **10.6x** | 9.3x | 16.0x | 15 |
| SaaS | >$500M | **28.2x** | 17.1x | 42.6x | 31 |
| Specialty contractor | $100M-500M | **8.7x** | 7.2x | 11.9x | 12 |
| Specialty medical practice | >$500M | **14.6x** | 10.0x | 18.4x | 27 |
| Specialty retail | >$500M | **6.7x** | 4.9x | 14.5x | 18 |
| Veterinary practice | >$500M | **18.8x** | 16.5x | 24.8x | 11 |
| Wholesale distribution | >$500M | **10.6x** | 8.6x | 13.3x | 40 |

> **Scope note.** These are **population medians by segment** — the citable answer to "what does industry X sell for." They are *not* a valuation of any specific business. A real exit multiple is adjusted for margins, growth, customer concentration, and owner-dependence; that business-specific calculation lives in the free [ExitValue.ai valuation tool](https://exitvalue.ai). EV/Revenue medians (useful for thin-margin and pre-profit segments) are in `multiples.json`.

---

## Value a specific business

The tables give medians for groups of deals. To get a range for one business, open the free calculator with your industry already selected (full disclosure: it's built by the publisher of this dataset):

[Accounting / CPA firm](https://exitvalue.ai/valuate?industry=accounting-cpa&src=dataset-github-accounting-cpa) · [Ambulatory surgery center](https://exitvalue.ai/valuate?industry=ambulatory-surgery-center&src=dataset-github-ambulatory-surgery-center) · [Dental practice](https://exitvalue.ai/valuate?industry=dental-practice&src=dataset-github-dental-practice) · [Home health agency](https://exitvalue.ai/valuate?industry=home-health&src=dataset-github-home-health) · [HVAC company](https://exitvalue.ai/valuate?industry=hvac&src=dataset-github-hvac) · [Insurance agency](https://exitvalue.ai/valuate?industry=insurance-agency&src=dataset-github-insurance-agency) · [IT services / MSP](https://exitvalue.ai/valuate?industry=managed-services-msp&src=dataset-github-managed-services-msp) · [Pest control](https://exitvalue.ai/valuate?industry=pest-control&src=dataset-github-pest-control) · [Physical therapy](https://exitvalue.ai/valuate?industry=physical-therapy&src=dataset-github-physical-therapy) · [Plumbing company](https://exitvalue.ai/valuate?industry=plumbing&src=dataset-github-plumbing) · [Primary care practice](https://exitvalue.ai/valuate?industry=medical-practice-primary-care&src=dataset-github-medical-practice-primary-care) · [SaaS company](https://exitvalue.ai/valuate?industry=saas&src=dataset-github-saas) · [Veterinary practice](https://exitvalue.ai/valuate?industry=veterinary-practice&src=dataset-github-veterinary-practice)

Any other industry: [exitvalue.ai/valuate](https://exitvalue.ai/valuate?src=dataset-github).

## Use it from ChatGPT, Claude or Cursor (MCP)

The same medians are available through a free, read-only [MCP](https://modelcontextprotocol.io/) server, with no signup and no API key:

```
https://exitvalue.ai/api/mcp
```

Claude Code: `claude mcp add --transport http exitvalue https://exitvalue.ai/api/mcp`. Setup for other clients: https://exitvalue.ai/ai-connector. Listed in the official MCP Registry as `ai.exitvalue/ma-multiples`.

---

## Files

| File | What's in it |
|---|---|
| [`multiples.json`](multiples.json) | Per (sub-vertical × EV-bracket) median + p25/p75 for EV/EBITDA, EV/Revenue. 61 EV/EBITDA + 118 EV/Revenue cells, each `n >= 10`. |
| [`multiples-by-year.json`](multiples-by-year.json) | Per (sub-vertical × year) date-stamped quartiles, 2018-2026. Tracks how multiples move over time. |
| [`datapackage.json`](datapackage.json) | [Frictionless Data](https://specs.frictionlessdata.io/) descriptor for the two resources above. |
| [`CITATION.cff`](CITATION.cff) | Machine-readable citation metadata. |

### Schema (`multiples.json`)

```json
{
  "data": {
    "dental-practice": {
      "5m_25m_ev": {
        "ev_ebitda": { "n": 10, "p25": 6.5, "p50": 7.0, "p75": 8.3 }
      }
    }
  },
  "source_window": "2018-2026",
  "min_cell_n": 10
}
```

`p50` is the median. EV brackets: `under_5m_ev`, `5m_25m_ev`, `25m_100m_ev`, `100m_500m_ev`, `over_500m_ev`.

---

## Methodology

Multiples are computed as aggregate quartiles of **disclosed** transaction multiples within each (sub-vertical × EV-bracket) cell, restricted to post-2018 deals. All metrics are **at the time of acquisition**, not current state. No values are estimated, imputed, or fabricated — cells without enough disclosed deals (`n < 10`) are simply omitted rather than filled in.

Full methodology and the live data: **<https://exitvalue.ai/methodology>**
State of SMB & Mid-Market M&A report: **<https://exitvalue.ai/research>**

## License

Data licensed **[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)** — free to use, including commercially, **with attribution to ExitValue.ai**.

## Citation

If you use this dataset in research, reporting, or a product, please cite it (see [`CITATION.cff`](CITATION.cff)):

```
ExitValue.ai. (2026). M&A Multiples Index — SMB & Lower-Middle-Market Valuation Multiples.
DOI: 10.5281/zenodo.20398222. https://github.com/nickcals/multiples
```
