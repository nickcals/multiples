# SMB and Lower Middle Market M&A Multiples (ExitValue.ai)

Open dataset of valuation multiples for 107 SMB and lower-middle-market
sub-verticals, derived from 25,592+ verified M&A transactions across SEC
EDGAR filings, 8-K disclosures, and verified press releases.

## Files

- `multiples.json` — per (sub-vertical × EV-bracket) median + p25/p75
  EV/EBITDA, EV/Revenue, SDE multiples. ~38 cells with n>=10 deals.
- `multiples-by-year.json` — per (sub-vertical × year) date-stamped
  quartiles. ~210 cells with n>=10 deals. Years 2018-2025.

## Source

- Live JSON: https://exitvalue.ai/data/multiples.json
- Methodology: https://exitvalue.ai/methodology
- Continuously updated from EDGAR ingest pipeline

## License

CC-BY-4.0. Free to use with attribution to ExitValue.ai.

## Citation

```
ExitValue.ai. (2026). SMB and Lower Middle Market M&A Multiples.
GitHub: https://github.com/nickcals/multiples
```
