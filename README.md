# M&A Multiples Index — SMB & Lower-Middle-Market Valuation Multiples

[![Dataset DOI](https://img.shields.io/badge/DOI-10.5281%2Fzenodo.20398222-blue)](https://doi.org/10.5281/zenodo.20398222)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey)](https://creativecommons.org/licenses/by/4.0/)

**An open, continuously-updated index of real-world M&A valuation multiples** (EV/EBITDA and EV/Revenue), broken out by **sub-vertical** and **enterprise-value bracket**. Built and maintained by [ExitValue.ai](https://exitvalue.ai).

> Every number below is an **aggregate median of disclosed M&A transactions** — not an estimate, rule of thumb, or imputed value. Each published cell requires **at least 10 disclosed deals** (`n >= 10`). Outliers are excluded (EV/EBITDA outside [0.5, 60.0]; EV/Revenue outside [0.05, 25.0]).

- **Coverage:** 25,482 unique completed transactions; 13,816 with disclosed EV/EBITDA, 24,651 with disclosed EV/Revenue.
- **Published cells:** 73 EV/EBITDA + 135 EV/Revenue across 46 sub-verticals.
- **Source window:** 2018-2026 (deals post-2018, from SEC EDGAR 8-K/S-4 filings, fairness opinions, and verified press releases).
- **Last updated:** 2026-07-12.

---

## What multiple does a business in my industry sell for?

These are **median EV/EBITDA exit multiples** for **small-business and lower-middle-market** deals (enterprise value up to $100M) — the size range where most owner-operated companies actually transact. `p25`/`p75` show the interquartile spread; `n` is the number of disclosed deals in the cell.

| Sub-vertical | EV bracket | Median EV/EBITDA | p25 | p75 | n (deals) |
|---|---|---|---|---|---|
| Ambulatory surgery center (ASC) | $5M-25M | **8.1x** | 5.5x | 11.4x | 20 |
| Ambulatory surgery center (ASC) | $25M-100M | **9.5x** | 6.8x | 12.2x | 11 |
| Dental practice | $5M-25M | **7.0x** | 6.5x | 8.3x | 10 |
| Durable medical equipment (DME) | <$5M | **5.3x** | 4.3x | 7.0x | 11 |
| Durable medical equipment (DME) | $5M-25M | **5.1x** | 4.7x | 5.8x | 13 |
| Electronics | $25M-100M | **9.2x** | 6.8x | 16.4x | 11 |
| Gaming | $25M-100M | **9.1x** | 5.1x | 11.6x | 10 |
| Healthcare IT | $5M-25M | **9.5x** | 7.0x | 14.4x | 10 |
| Home health | <$5M | **4.7x** | 3.9x | 6.2x | 25 |
| IT services | $5M-25M | **7.0x** | 5.3x | 8.6x | 13 |
| IT services | $25M-100M | **6.4x** | 4.8x | 10.0x | 10 |
| Industrial equipment | $25M-100M | **8.6x** | 6.2x | 12.1x | 19 |
| Medical devices | $25M-100M | **12.7x** | 9.1x | 21.9x | 14 |
| Oil & gas services | $25M-100M | **3.7x** | 2.2x | 7.5x | 15 |
| Primary-care practice | <$5M | **3.6x** | 3.4x | 4.6x | 11 |
| SaaS | $5M-25M | **11.0x** | 8.7x | 19.1x | 16 |
| SaaS | $25M-100M | **15.5x** | 5.9x | 19.1x | 11 |
| Specialty medical practice | $5M-25M | **5.9x** | 5.1x | 8.2x | 15 |
| Wholesale distribution | $25M-100M | **6.8x** | 4.8x | 8.7x | 17 |

### Larger transactions (enterprise value $100M+)

For reference, the same sub-verticals at larger deal sizes (multiples typically expand with scale):

| Sub-vertical | EV bracket | Median EV/EBITDA | p25 | p75 | n (deals) |
|---|---|---|---|---|---|
| Aerospace | >$500M | **14.2x** | 12.9x | 16.9x | 24 |
| Apparel | >$500M | **5.9x** | 3.8x | 10.1x | 11 |
| Auto parts | >$500M | **8.1x** | 6.6x | 12.6x | 14 |
| Consulting | >$500M | **13.7x** | 11.7x | 15.8x | 13 |
| Consumer products | >$500M | **10.1x** | 8.9x | 12.2x | 19 |
| Dental practice | >$500M | **14.0x** | 11.9x | 15.8x | 17 |
| Digital media | >$500M | **15.2x** | 10.1x | 29.4x | 14 |
| Durable medical equipment (DME) | >$500M | **10.3x** | 9.0x | 11.9x | 10 |
| Electrical utility | >$500M | **12.4x** | 11.6x | 13.8x | 16 |
| Electronics | >$500M | **18.3x** | 8.9x | 23.5x | 14 |
| Enterprise software | >$500M | **22.4x** | 15.3x | 30.1x | 11 |
| Food manufacturing | >$500M | **12.9x** | 10.2x | 17.3x | 32 |
| Gaming | >$500M | **14.5x** | 9.6x | 20.9x | 18 |
| Health tech | >$500M | **25.7x** | 15.7x | 34.7x | 12 |
| Healthcare IT | >$500M | **20.0x** | 16.6x | 25.6x | 70 |
| Home health | >$500M | **11.6x** | 10.4x | 15.4x | 19 |
| IT services | >$500M | **11.3x** | 9.3x | 13.5x | 17 |
| Industrial equipment | >$500M | **13.2x** | 11.0x | 16.8x | 30 |
| Laboratory services | >$500M | **22.2x** | 17.4x | 29.5x | 14 |
| Medical devices | >$500M | **15.2x** | 11.9x | 20.6x | 52 |
| Mental / behavioral health | $100M-500M | **13.5x** | 10.0x | 15.5x | 21 |
| Metal fabrication | >$500M | **7.8x** | 6.4x | 10.0x | 26 |
| Oil & gas services | >$500M | **7.5x** | 5.0x | 11.3x | 159 |
| Packaging | >$500M | **9.9x** | 7.6x | 12.1x | 19 |
| Pharmacy | >$500M | **18.3x** | 11.9x | 20.9x | 21 |
| Physical therapy | >$500M | **14.3x** | 11.2x | 15.0x | 11 |
| Primary-care practice | >$500M | **16.6x** | 13.1x | 18.6x | 16 |
| Radio & television | >$500M | **8.3x** | 6.7x | 11.8x | 16 |
| Restaurant (QSR) | >$500M | **11.5x** | 9.2x | 16.0x | 22 |
| SaaS | >$500M | **27.9x** | 15.8x | 39.6x | 37 |
| Specialty contractor | >$500M | **9.1x** | 7.1x | 12.6x | 14 |
| Specialty medical practice | >$500M | **14.3x** | 9.8x | 18.3x | 28 |
| Specialty retail | >$500M | **6.6x** | 4.8x | 14.8x | 25 |
| Trucking | >$500M | **6.7x** | 5.3x | 10.2x | 10 |
| Veterinary practice | >$500M | **18.8x** | 15.6x | 22.0x | 15 |
| Wholesale distribution | >$500M | **10.7x** | 8.8x | 13.4x | 49 |

> **Scope note.** These are **population medians by segment** — the citable answer to "what does industry X sell for." They are *not* a valuation of any specific business. A real exit multiple is adjusted for margins, growth, customer concentration, and owner-dependence; that business-specific calculation lives in the free [ExitValue.ai valuation tool](https://exitvalue.ai). EV/Revenue medians (useful for thin-margin and pre-profit segments) are in `multiples.json`.

---

## Files

| File | What's in it |
|---|---|
| [`multiples.json`](multiples.json) | Per (sub-vertical × EV-bracket) median + p25/p75 for EV/EBITDA, EV/Revenue. 73 EV/EBITDA + 135 EV/Revenue cells, each `n >= 10`. |
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
