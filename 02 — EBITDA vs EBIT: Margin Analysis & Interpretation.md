# 02 — EBITDA vs EBIT: Margin Analysis & Interpretation

This is one of the most reliably-asked questions in a Controller interview. Know the definitions cold, but more importantly, know the *interpretation* — that's what separates an AP/analyst-level answer from a Controller-level one.

## P&L Build Order

| Line Item | Formula |
|---|---|
| Gross Profit | Revenue − COGS |
| EBITDA | Gross Profit − Operating Expenses |
| EBIT | EBITDA − Depreciation & Amortization |
| PBT (Profit Before Tax) | EBIT − Finance Costs |
| Net Profit | PBT − Tax |

## The Definitions

| | EBITDA | EBIT |
|---|---|---|
| Stands for | Earnings Before Interest, Tax, Depreciation & Amortization | Earnings Before Interest & Tax |
| Includes D&A impact? | No | Yes |
| Best used for | Comparing operating performance across companies, independent of financing structure, tax rate, or depreciation policy | Assessing profitability after the cost of consuming fixed assets |

**Relationship:** `EBITDA − D&A = EBIT`

## Why EBITDA Is Useful — and Where It Misleads

EBITDA strips out financing structure, tax jurisdiction, and depreciation policy — which makes it a fairer way to compare operating performance across companies that differ in those areas.

> ⚠️ **The trap:** EBITDA is *not* cash flow. It ignores working capital movement, capital expenditure, interest, and tax. Saying this unprompted in an interview signals Controller-level maturity.

**Interview line to memorize:**
> "EBITDA is a useful measure of operating performance, but it is not a direct measure of cash flow because it ignores working capital movements, capital expenditure, interest and taxes."

## Margins to Quote Instantly

- **Gross Margin** = Gross Profit ÷ Revenue
- **EBITDA Margin** = EBITDA ÷ Revenue
- **EBIT Margin** = EBIT ÷ Revenue
- **Net Profit Margin** = Net Profit ÷ Revenue

## Worked Example (ABC Manufacturing Ltd., FY 2025–26)

| Metric | ₹M | Margin |
|---|---|---|
| Revenue | 300 | — |
| Gross Profit | 130 | 43.3% |
| EBITDA | 75 | 25.0% |
| EBIT | 60 | 20.0% |
| Net Profit | 45 | 15.0% |

Check: EBITDA (75) − Depreciation (15) = EBIT (60). ✓

**Interpretation to say out loud in an interview:**
> "The company generates a 25% EBITDA margin, indicating strong operating profitability before depreciation, interest and tax. The EBIT margin is 20% — the 5-point gap is entirely depreciation. I'd want to see whether that D&A load is growing faster than revenue, which would signal aging assets or heavy recent capex."

## Quick-Fire Q&A

**Q: Why is EBITDA different from EBIT?**
EBITDA excludes depreciation and amortization; EBIT includes them.

**Q: Is EBITDA the same as cash flow?**
No — it ignores working capital, capex, interest, and tax.

**Q: When would EBITDA and EBIT tell two different stories?**
When a company has a large fixed-asset base and heavy D&A — EBITDA can look strong while EBIT (and eventually net profit) is squeezed by depreciation. Also watch for companies that have recently made large acquisitions with high amortization of intangibles.

**Next:** see `03-balance-sheet-deep-dive.md` for how these P&L outputs connect to the Balance Sheet.
